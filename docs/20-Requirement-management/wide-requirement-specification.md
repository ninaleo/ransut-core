# Requirement Specification for Service/Solution X  x.y 

* Project: [INSERT PROJECT NAME HERE]
* Autohor: [Your Name/Team]
* Version: Document version number X.Y
* Template version: 1.9 - 28.9.2021 (NarsuMan)

## Some guidelines for writer of requirement specification

> Keep the table of contents in good condition, ie update the MarkDown anchor link if necessary.

> Within the document, the "/ templates" folder is referred to in several places. This folder contains the so-called "template" files used to help record various definitions.
This means that files can be copied from that folder if 

> With the PlantUML tool, it is possible to draw, for example, descriptions in the UML markup language and integrate them into MarkDown descriptions. During the course there is
useful to familiarize yourself with its use http://plantuml.com/ and try to apply it as much as possible in different areas.

> ATTENTION! Do not use Scandinavian characters in PlantUML descriptions, as this will cause problems during the CI / CD process


## Table of contents
 
>Update according you own document..

1. [Introduction](#introduction)
1. [Principal / client](#Principal)
1. [Requirement Definition Factor](#Requirement Definition Factor)
1. [Service Description](#Service Description)
1. [Stakeholder Map](#Stakeholder Map)
1. [Stakeholders and Profiles](#Stakeholders and Profiles)
1. [Identified risks](#Identified risks)
1. [Selected Customer Stories](#Selected Customer Stories)
1. [Service-Related Customer Paths](#Service-Related Customer Paths)
1. [Relevant Use Cases](#Relevant Use Cases)
1. [Key General Features/Functionalities](#Key Features / Functionalities)
1. [MockUp Prototype](#MockUp Prototype)
1. [Preliminary User Stories](#Preliminary User Stories)
1. [Service System Requirements](#Service System Requirements)
1. [Restrictions Affecting the Service](#Restrictions Affecting the Service)
1. [Service Related Equipment Requirements](#service Related Equipment Requirements)
1. [Requirements related to the service execution environment](#Requirements related to the service execution environment)
1. [Service-defined features / functionalities](#Service-defined features / functionalities)
1. [Functional Requirements for the Service](#Functional Requirements for the Service)
1. [Non-functional requirements of the service](#Non-functional requirements of the service)
1. [Preliminary Service Architecture](#Preliminary Service Architecture)
1. [Preliminary Service Placement View](#Preliminary Service Placement View)
1. [Preliminary database description of the service](#Preliminary database description of the service)
1. [Service Integrations with Other Systems](#Service Integrations with Other Systems)
1. [On Quality of Service](#On Quality of Service)
1. [Service Acceptance Tests](#Service Acceptance Tests)
1. [Release plan](#Release plan)
1. [Related Standards and Sources](#Related Standards and Sources)


## Introduction

> Describe what kind of project it is, a little background and essentially related things? If this is an exercise, then check if you can
use the real names of the real subscribers! If necessary, change the personal data and the official data of the client

## Principal / client

> Who is the subscriber to the requirements specification?

## About the author 

> Tell us briefly about yourself (as a pseudonym if necessary) or, for example, as an employee of an imaginary company.

## Short description of service/solution

> What can the service do? What are its users like? What is its role in general for the various stakeholders?
It is worth highlighting briefly the potential end user and the relevant stakeholders who will benefit from the service


## Stakeholder map


Let's consider little what kind of user / stakeholders are involved in the planned software / service package?
To clarify these, all stakeholders are recorded in the form of a stakeholder map. At the same time, let's highlight what is
ko. motivation related to the service of the stakeholder / representative. The description can be created, for example, by drawing, in MindMap format or by applying a suitable UML notation.

[![](http://img.youtube.com/vi/wiNjgClkJoM/0.jpg)](http://www.youtube.com/watch?v=wiNjgClkJoM "")

> You can now check out the PlantUML tool mentioned earlier and try creating a stakeholder map (http://plantuml.com/)
> Note! The *PlantUML code block* is defined in the Gitlab's markdown version using different keywords instead of commonly used @ startuml / @ enduml lines. You will find example down below..

```plantuml
actor profile1
actor profile3
actor stake_holder1
actor stake_holder3
cloud example_of_service
profile1 -- example_of_service  : uses
profile2 -- example_of_service  : benefits
stake_holder1 -- example_of_service  : threat
stake_holder2 -- example_of_service  : competitor
```
> You can also describe stakeholders using other visualisation methods, so that the differences between the different profiles may become visible more "clearer"!

![](https://openclipart.org/image/400px/283178)


## Stakeholders and profiles

> We should define more precise some of relevant stakeholde profiles. Note that a large stakeholder instace (eg. company, institution) can contain several different stakehold profiles. Because of that there may be a need to define several different profiles. Different profiles can be users, but because of different need they can have specific needs, motives and values. We have to find and define those different groups if needed.   

[![](http://img.youtube.com/vi/w5oXMtOGcC4/0.jpg)](http://www.youtube.com/watch?v=w5oXMtOGcC4 "")


| Stakeholde/profile | Info / Link to description | Motivation? |
|:-:|:-:|:-:|
| Stakeholder 1 | [Sidosryhmä-1](pohjat/template-profileilikuvaus.md) | |
| Stakeholder 2 | [Sidosryhmä-2](pohjat/pohja-profiilikuvaus.md) | |
| Stakeholder 3 / End user 1 | Person 17-35 Years old | Benefits x, y and z |
| Stakeholder 3 / End user 2 | Person 36-45 Years old | Primary reason is... |
| Stakeholder 3 / End user 3 | Person 46-65 Years old | Because of.... |
| Admin user | [adminuser-profile](pohjat/pohja-profiilikuvaus.md) | supports service users |

## Customer needs / wishes?

> Continuously complete this throughout the course!
> Consider what kind of wishes / needs the end user has regarding the service? Interview people in a real situation?

| ReqID | Type | Description | 								
|:-:|:-:|:-:|
| CUSTOMER-REQ-0001 | Customer Requirement | As a user of solution I would like to use Faceboot authentication | 
| CUSTOMER-REQ-0002 | Customer Requirement ||


## Business requirements / goals?

> Consider what kind of wishes / needs there are from a business perspective related to the service?
> If nothing comes to mind, then consider whose "cashier" the money comes from the service? Does the service achieve cost benefits? Does it improve cost efficiency? etc

| ReqID | Type | Description | 								
|:-:|:-:|:-:|
| BUSINESS-REQ-0001 | Business Requirement | Registration as a new user should be easy for old users, because is's our user focus group 35% | 
| BUSINESS-REQ-0002 | Business Requirement ||



## Customer Storys as background information

>During requirement gatheringphase for a service/solution it is a good practice to do some interview among possible users and other stakeholders. Gathering some knowledge among this group will help to understand basic need of different user groups. It's important to understand in early phase how the person / stakeholder benefits or uses the solution/service in future. This process could be written as a customer story. 

> Try to write a story from the perspective of the selected profile/stakeholder (other profiles / stakeholders may appear in the story). It is convenient to refer to previously created [Profile] descriptions as as a back ground of the story.

**Example of end use/customer story** 

[Profiili 1](template/template-profile.md) wakes up in the morning and checks on his phone if there is room in the X service from the morning. By using application he can find that there is several open slots available .........

**end user profile 1 point of view** 

[End user profile  1](pohjat/pohja-profiilikuvaus.md) is goint to start a cement mill on a construction site in the afternoon when she receives a message from the X service .........


## Customer Journey paths in Service/solution 

> Think about the customer story you wrote earlier and draw an outline of the customer path based on it.
What events are involved? Think of the service as a whole!
The case path description is used to describe a series of events that go through a selected situation during the use of the service.
There can be several customer-specific service paths, but the most important thing is to identify the most relevant at the beginning.
When describing the service path, you can use, for example, the Swim lane / BluePrint / state machine description or other description deemed appropriate.
However, it is important to describe the path and use it, if necessary, to clarify the understanding of the service sought.
Go through the description you made with someone else? Go through the path and tell what happens during it.

[![](http://img.youtube.com/vi/kNXjKquK3A0/0.jpg)](http://www.youtube.com/watch?v=kNXjKquK3A0 "")

> It is a good idea to start sketching the customer path, for example on the basis of a customer story. If necessary, several paths are created from the perspective of different profiles / situations. So it is not worth immersing too many events in one description

[![](http://img.youtube.com/vi/j7U8pqUN9EM/0.jpg)](http://www.youtube.com/watch?v=j7U8pqUN9EM "")

**Customer journey path as PlantUML Statemachine -diagram **

> Trying to sketch a customer path using the PlantUML tool. Definitely worth trying other ways too!
> Apply eg PlantUML SDL / Swimlane description?


```plantuml
[*] --> Step1

Step1 : First contact to service 
Step2 : Under Service 
Step3 : End of service
Step4 : Queue for service 

Step1 --> Step2
Step1 --> Step4
Step4 --> Step2
Step2 --> Step3
Step3 --> [*]
```
> If necessary, other tools can be applied to the descriptions of the service paths. Eg https://canvanizer.com, PowerPoint etc

## Mandatory Use Case of service/solution

> As user "travels" trough the service/solution by using it several service-related events is traversed. Situations involving the service/solution can be described as Touchpoints of service. All needed usage steps and actions neede can be described as a Use Case.
> In software design, the ** Use Case ** is easily misunderstood because it is easily associated with the product alone.
** to describe the purpose **. When discussing a service for the first time, we talk about its different ** uses **, ie what it is for
the software / service can be utilized. When talking about defining a service and identifying related use cases
it is a slightly different matter. In the use case, the focus is on the use of the service in a very limited situation.
Use Cases are described using a UML markup language.

> UML Use Case description can be done as PlantUML description, but a more detailed use case requires a separate description document

```plantuml

rectangle Order {
Profile_1--(Making order)
Profile_1--(Modifying order)
Profile_1--(Cancelling order)
}

rectangle Order_management {
Hallinto_1--(Checking the Order)
Hallinto_1--(Modification of order)
Hallinto_1--(Transferring the order)
Huolto_1--(Order manual cancelling)
Huolto_1--(Order clear and restart)
}

```

> On hyödyllistä kirjata kaikki oleelliset käyttötapaukset yhteen laajempaan Use Case-kuvaukseen, koska sen avulla voi tarkastella
helpommin koko järjestelmää. Huomio! Laajemmassa järjestelmä kokonaisuudessa saattaa olla useita satoja eri käyttötapauksia. 

[![](http://img.youtube.com/vi/DupdE35Ilps/0.jpg)](http://www.youtube.com/watch?v=DupdE35Ilps "")

[![](http://img.youtube.com/vi/-3YtgJGuIek/0.jpg)](http://www.youtube.com/watch?v=-3YtgJGuIek "")

[![](http://img.youtube.com/vi/oVGmIOavB74/0.jpg)](http://www.youtube.com/watch?v=oVGmIOavB74 "")

> Käyttötapauksen tarkempi kuvaus harjoitusympäristössä tapahtuu käyttötapaus-kohtaisen pohja-tiedoston avulla. Jokaista käyttötapausta varten 
laaditaan itsenäinen tiedosto.

| Käyttötapaus | Osa-alue | Ominaisuus? |
|:-:|:-:|:-:|
| [Käyttötapaus 1 - Tilauksen muokkaus](pohjat/pohja-kayttotapaus.md) | Tilausten hallinta | [Tilaushallinta-paneeli](pohjat/pohja-ominaisuus.md) | 
| [Käyttötapaus 2 - Tilauksen tarkistaminen](pohjat/pohja-kayttotapaus.md) | Tilausten hallinta | [Tilaushallinta-paneeli](pohjat/pohja-ominaisuus.md) | 
| [Käyttötapaus 2 - Tilauksen siirto](pohjat/pohja-kayttotapaus.md) | Tilausten hallinta | [Tilaushallinta-paneeli](pohjat/pohja-ominaisuus.md) |

## Tärkeimmät ominaisuudet/toiminnallisuudet 

> Hahmotellaan tähän kohtaan ominaisuudet pelkästään "ranskalaisilla viivoilla", eli mitä palvelulla mielestäsi on mahdollista tehdä?
> Päivitä lista myöhemmin, kun se tarkentuu? 

> On hyödyllistä laatia toimeksiantajan kanssa yhdessä tiivistelmä (A4-kokoa), josta löytyy tarvittaessa koko tuote kiteytettynä
Löydät esimerkin dokumentista [täältä](../pohjat/pohja-tuotekuvaus-a4.md)

> Toiminnallisuudet tullaan kiinnittämään myöhemmin 

- Toiminnot 
    - Käyttäjä voi lähettää postia toiselle henkilölle
    - Asiakas saa tiedot aiemmin tehdyistä valinnoista
    - Henkilö voi maksaa laskun 

## MockUp-prototyyppi

> Suunniteltavan palvelun toimintoja määriteltäessä voi olla hyödyllistä piirtää avuksi MockUp-kuvausta käyttötilanteen 
tai toiminnallisuuden todentamiseksi. Kun palvelun käyttöliittymää tai palvelupolkua käydään läpi mockup-kuvauksen kautta
voi hahmottaa huomattavasti helpommin tarvittavia toiminnallisuuksia tai tarpeita, joita voidaan kirjata vaatimusmäärittelyyn. 
MockUp-kuvaus on hyödyllinen apuväline palvelun tilaajan/toimeksiantajan kanssa käydyissä keskusteluissa.

[![](http://img.youtube.com/vi/a5qLMBYWv5A/0.jpg)](http://www.youtube.com/watch?v=a5qLMBYWv5A "")

> Kun laadit harjoitustehtävään MockUp-näkymän pohdi haluatko kuvata koko palvelua vai keskittyä yksittäisen toiminnallisuuden tarkasteluun?

> Voit kokeilla myös PlantUML-kuvausta rajatuissa kohdissa

```plantuml
salt
{
  Just plain text
  [This is my button]
  ()  Unchecked radio
  (X) Checked radio
  []  Unchecked box
  [X] Checked box
  "Enter text here   "
  ^This is a droplist^
}
```

## Alustavat käyttäjätarinat

>**NYT HUOMIO!** Tähän kohtaan kannattaa keskittyä vasta kun kaikki muut osiot on käyty läpi! 
Kyseessä ei ole asiakastarina vaan ketterässä kehityksessä (Agile Development) käytettävä käyttäjätarina - User Story. 
Sen avulla kuvataan palveluun liittyvää toiminnallisuutta, jolle käyttäjälle on tarvetta.

[Aiheesta löytyy pohdintoja eri muodossa](https://suomidigi.fi/kayttajatarinoilla-ryhtia-asiakaslahtoisyyteen/)

[![](http://img.youtube.com/vi/ndJdF3R7wqI/0.jpg)](http://www.youtube.com/watch?v=ndJdF3R7wqI "")

* User Story: [Käyttäjänä haluan, että voin luoda raportin tekemistäni ostoista viimeisen kuukauden ajalta, koska se helpottaa oman talouteni hallintaa]()
* User Story: [Pääkäyttäjän haluan poistaa vanhat tunnukset kokonaan, koska se selkeyttää ylläpitoa]()
* Käytännössä ylempi kuvaus on hieman jäykkä ja on järkevitä kirjata storyt suoraan esim. GitLab-issuen muotoon! 
* Kokeile osoittaa hiirelle linkkejä oikealla ja avaa ne tämän jälkeen ---> #25 tai #26

## Palvelun järjestelmävaatimukset 


> Järjestelmävaatimukset ovat korkeamman tason vaatimuksia, joiden pohjalta järjestelmä kokonaisuutta lähdetään määrittelemään.
> Palveluita suunniteltaessa nousevat teknisestä näkökulmasta tarkasteltuna esiin vaatimukset, jotka liittyvät eri 
teknologioihin, laitteistoihin tai totetuksen fyysisiin rakenteisiin. Ohjelmistopalvelua määriteltäessä
kannattaa tunnistaa ajoissa puhtaasti järjestelmän tekniset/tuotannolliset vaatimukset ja kirjata ne vaatimusmäärittelyyn. 
Liiallinen keskittyminen teknisten tuotanto/toteutusvaatimusten kirjaukseen ei ole välttämättä suositeltavaa, koska 
suunnittelun aikana ohjelmistoa/palvelun toteutusvaatimukset voivat vielä muuttua. Kehitysvaiheessa näppäräksi koettu ratkaisu 
voi osoittatua kalliiksi palvelun tuotteistamisvaiheessa.

> Tässä osiossa Kannattaa pohtia esim seuraavia kohti

- Miten palvelu tuotetaan? SAAS/PAAS/IAAS/HOSTED-palveluna etc 
- Käytetäänkö Pilvipalveluita osana ratkaisua vai hyödynnetäänkö omia palvelimia
- Onko kyseessä ns. Hybridi-palvelu, joka hyödyntää useampia erillis palvelua 
- Miten palvelu on oltava saatavilla 24/7h 100% ? Niin onko tuo edes mahdollista :) ?
- Millainen SLA palvelulle laaditaan?
- Miten paljon kustannuksia saa palvelun tuotanto tuottaa?
- Millaiset tiedonsäilytys/arkistointi tarpeet liittyvät palveluun? 

[![](http://img.youtube.com/vi/s7AcxrxcVd0/0.jpg)](http://www.youtube.com/watch?v=s7AcxrxcVd0 "")

> Järjestelmä tason vaatimuksissa tarkastellaan ohjelmistoa/palvelua kokonaisuutena ja sen pohjalta määritellään 
esim. tekniset vaatimukset suoritusympäristölle, vaadittaville resursseille palvelun ylläpitoa varten. 

> Järjestelmän suoritusympäristön vaatimukset käsittävät esimerkiksi laitevaatimukset tuotantoympäristöstä tai 
järjestelmän ajoympäristön vaatimuksia, joihin voivat sisältyä vaatimukset suorituskyvystä, ylläpidosta, varmennuksista etc

> Millaisia suoritusympäristöjä sitten käytetään esim. kaupallisissa ratkaisuissa ? Voit tutkia esimerkkejä [Stack Share](https://stackshare.io/):palvelussa


> Esim. millainen on tekninen ratkaisu toteutukselle ja miten eri teknologioita tullaan hyödyntämään. 

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| SYSTEM-HW-REQ-0002 | System Technical Requirement | Palvelun tärkeimpien palvelujen on oltava vähintään kahdennettu N+1 | |
| SYSTEM-HW-REQ-0003 | System Technical Requirement | Palvelimen muistikapasiteeti >16GB  ||
| SYSTEM-HW-REQ-0004 | System Technical Requirement | Prosessori Intel/AMD x64||
| SYSTEM-HW-REQ-0005 | System Technical Requirement | Palvelimen fyysinen sijainti on oltava kotimaassa (Suomi) ||
| SYSTEM-HW-REQ-0005 | System Technical Requirement | Verkkoyhteyden nopeus >100MB/s ||
| SYSTEM-HW-REQ-0005 | System Technical Requirement | Laitekaapin suositeltava koko 1m X 1m X 2m ||




 
> Avainsanat: pilvipalvelun tuotanto, Palveluiden hallinta, SLA 

### Palvelun suunnitteluun vaikuttavat rajaukset ja standardit

> Eri ohjelmistojena/palvelujen toteutusta ja käyttöä ohjaavat usein lait ja säädökset. Näiden edellyttämät vaatimukset kirjataan yleensä rajoitteina 
ja niiden vaikutus koskee usein koko ohjelmiston/järjestelmän toteuttamista. Tästä syystä ne kannattaa tunnistaa ja selvittää ajoissa, koska vaikutus 
saataa olla varsin ratkaiseva pitemmällä tähtäimella. Esimerkkinä [EU GDPR-säädös](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation).

> Kannattaa tutkia esimerkiksi https://www.sfs.fi/aihealueet/terveydenhuolto/laakinnalliset_laitteet tai http://docs.jhs-suositukset.fi/jhs-suositukset/JHS190/JHS190.html

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| CONSTRAINT-REQ-S00000 | Constrain | Palvelun kirjautumisprosessin on noudatettava XYZ-käytäntöjä  | [Kirjautuminen ft1](pohjat/pohja-ominaisuus.md) |
| CONSTRAINT-REQ-S00002 | Constrain |||





### Palvelun toiminnallisuudet/ominaisuudet

> Kirjataan taulukkoon "kaikki" toiminnot, joista osaa tullaan käsittelemään myöhemmin tuotteen toiminnallisina ominaisuuksina. 
Kannattaa huomata, että osa toiminnallista vaatimuksista ovat käytännössä oleellisia toimintoja, eli ne voidaan "korottaa" ominaisuuksiksi. 
Esimerkkinä Verkkopankki palvelussa on oleellinen toiminto "maksu tililtä", joka on käytännössä tärkeä palvelun ominaisuus. Tähän 
toiminnallisuuteen liittyy useita muita pienempiä ja tarkentavia toiminnallisia vaatimuksia

> Jos sinulta kysytään mitä palvelulla/ohjelmistolla voi tehdä pyri tunnistamaan tärkeimmät toiminnot! 
Ne ovat melko varmasti oleelliset ominaisuudet. 
> Mieti mitä toimintoja pysyt tekemään esim. verkkopankin sivulla? Mitkä ovat tärkeimmät toiminnot, joita käytät useimmin?

> Kannataa pohtia määrittelyvaiheessa ovatko kaikki ominaisuudet tarpeellisia? Kannattaa pyrkiä ryhmittelemään tärkeimmät ominaisuudet ensin.
Ominaisuuksia voidaa tarkentaa toiminnallisilla vaatimuksilla, jotka ns. laajentavat ominaisuuden kuvausta. Ominaisuudet ovat käytännössä isompia kokonaisuuksia, joista koko palvelu/ohjelmisto on muodostunut.
Suomenkielen sana ominaisuus saattaa olla hieman harhaan johtava, koska usein tuotteita esiteltäessä pyritään korostamaan tuotteen ominaisuutena sen "tietoturvallisutta". 
Tämä ei tarkoita, että kyseessä on tuoteeen ohjelmiston yksi ominaisuus vaan yleinen "suunnittelu filosofia". Tuote voi sisältää ominaisuuksia, joiden myötä sitä voidaan kutsua voidaan tietoturvalliseksi.

> Tuotteen ominaisuus vai toiminto?

[![](http://img.youtube.com/vi/6dVrBsvUStg/0.jpg)](http://www.youtube.com/watch?v=6dVrBsvUStg "")

> Ominaisuuksien todellinen tarve?

[![](http://img.youtube.com/vi/pIDSK21PE9M/0.jpg)](http://www.youtube.com/watch?v=pIDSK21PE9M "")

> Ylikirjoita pohjalla olevat ehdotuksen ja toimintoja toimeksiantoon pohjautuen ja priorisoi niistä tärkeimmät toiminnot, joita määrittelet tarkemmin. 

**Priorisoi oleelliset ominaisuudet/toiminnot**

* P1 = Pakollinen
* P3 = Tarpeellinen
* P5 = Tehdään, kun tarve ilmenee

| Ominaisuus | Prioriteetti | Ominaisuuteen liittyvät vaatimukset/käyttötapaukset |
|:-:|:-:|:-:|
| [Feature 1 - raportti-generaattori](pohjat/pohja-ominaisuus.md) | P1 | Esim [FUNCTIONAL-REQ-C0001]() | 
| [Feature 2 - lasku-arkisto](pohjat/pohja-ominaisuus.md) | P1 | Esim [FUNCTIONAL-REQ-C0011]() | 
| [Feature 3 - avatar-valinta](pohjat/pohja-ominaisuus.md) | P2 | Esim [FUNCTIONAL-REQ-C0023]() |
| [Feature 4 - oikeushallinta](pohjat/pohja-ominaisuus.md) | P3 | Esim [FUNCTIONAL-REQ-C0133]() |
| [Feature 5](pohjat/pohja-ominaisuus.md) | P4 | Esim [FUNCTIONAL-REQ-C0231]() |




### Palvelun toiminnalliset vaatimukset

>Mitä ovat toiminnalliset vaatimukset? Toiminnallisilla vaatimuksilla kuvataan ohjelmistolta/järjestelmältä vaadittua toimintaa
Toiminnalliset vaatimukset ovat helpoimmin tunnistettavia. Vältä useamman vaatimuksen kirjaamista samaan lauseeseen! Jokainen vaatimus erikseen..
Voit esittää ne taulukossa tai viitata [yhteen](pohjat/pohja-vaatimuslistalle.md) laajempaan kokonaisuuteen

[![](http://img.youtube.com/vi/qO2qEIEHy_A/0.jpg)](http://www.youtube.com/watch?v=qO2qEIEHy_A "")

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| FUNCTIONAL-REQ-C0001 | Functional Requirement | Käyttäjänä (Asiakas Profiilit 1-4) voin kirjautua käyttäen Facebook-tunnuksia | [Kirjautuminen ft1](pohjat/pohja-ominaisuus.md) |
| FUNCTIONAL-REQ-C0002 | Functional Requirement | Käyttöliittymän on toimittava myös ääniohjattuna, koska käyttäjillä saattaa olla näkövammoja | [Kirjautuminen ft1](pohjat/pohja-ominaisuus.md), [Tilaushallinta](pohjat/pohja-ominaisuus.md) |
| FUNCTIONAL-REQ-C0003 | Functional Requirement |||


### Ohjelmiston/palveluun ei-toiminnallisia vaatimuksia

>Mitä olivat ei-toiminnalliset vaatimukset? Voit esittää eri vaatimuksia erillisessä taulukossa tai viitata tässä [yhteen](pohjat/pohja-vaatimuslistalle.md) laajempaan taulukkoon.
[Ei-toiminnalliset vaatimukset](https://en.wikipedia.org/wiki/Non-functional_requirement) sisältää laajan joukko eri näkökulmia ohjelmiostotuotteeseen liittyen. Tärkeimmät kirjoittajan 
näkökulmasta ovat seuraavat: Suorituskyky, käytettävyys, tietoturva ja ylläpidettävyys 
>Voit esittää eri vaatimuksia erillisessä taulukossa tai viitata tässä [yhteen](pohjat/pohja-vaatimuslistalle.md) laajempaan taulukkoon..
Miten hyvin palvelu/komponentti tai muu osa-alue palvelusta suoriutuu kuormituksen aikana? Mitkä ovat pullonkaulat. Mihin vaatimuksiin palvelun tulee kyetä vastaamaan?

[![](http://img.youtube.com/vi/Tta7bAFlg54/0.jpg)](http://www.youtube.com/watch?v=Tta7bAFlg54 "")


>Millaisia vaatimuksia palveluun kohdistuu suorituskyvyn näkökulmasta?

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| PERFORMANCE-REQ-0000 | Non-Functional Performance | Kirjautuminen on mahdollista yhtäaikaa 100 käyttäjällä (100 request/s) | [Kirjautuminen ft1](ft1-ominaisuus.md) |								
| PERFORMANCE-REQ-0001 | Non-Functional Performance |||


>Millaisia vaatimuksia palveluun kohdistuu tietoturvan näkökulmasta?

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| SECURITY-REQ-0001 | Non-Functional Security | Salasanassa on käytettävä vähintään MD5-tason salausta, koska standardi XY112 sitä edellyttää | [Kirjautuminen ft1](ft1-ominaisuus.md) |								
| SECURITY-REQ-0002 | Non-Functional Security |||


>Mitä tarkoitetaan käyttävyydellä? Millaisia asioita/ohjeistuksia on otettava huomioon palvelua toteutettaessa?

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| USABILITY-REQ-0000 | Non-Functional Usability | | [Kirjautuminen ft1](ft1-ominaisuus.md) | |	
| USABILITY-REQ-0001 | Non-Functional Usability | | [Käytettävyys](https://fi.wikipedia.org/wiki/K%C3%A4ytett%C3%A4vyys) |


>Millaisia asioita on otettava huomioon tuotteen laadunvarmistamisen kannalta?. Kehityksen aikana ohjelmistotuotteeseen on luotava tarvittavat rajapinnat tai työkalu-ohjelmistoja, 
joiden avulla voidaan hallita testikohteena olevaa tuoteversiota. Nämä vaatimukset on kirjattava ajoissa, koska ne vaikuttavat ratkaisevasti tuotteen testausmahdollisuuksiin.
Esimerkkinä voidaan miettiä logien hallintaa, niiden keräämistä, alkutilanteeseen saattamista. 

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| TESTABILITY-REQ-0000 | Non-Functional Testability | Käyttäjärekisteri on kyettävä palauttamaan alkutilaan ennen testien ajoa  | [Kirjautuminen ft1](ft1-ominaisuus.md)	 |	
| TESTABILITY-REQ-0001 | Non-Functional Testability ||[Lisätietoa](https://fi.wikipedia.org/wiki/Ohjelmiston_laatu)|	


## Ohjelmiston arkkitehtuuri, sijoittelunäkymä, tietokantakuvaus ja integraatiot

>Ohjelmiston toteutus vaatimuksiin voidaan asettaa ennalta määriteltyjä teknologioita, joita on noudatettava kehityksessä. 
Tämä tilanne tulee usein eteen, kun ohjelmisto liittyy aiemmin toteutettuun ratkaisuun

### Palvelun sijoittelunäkymä (Deployment diagram )

>Sijoittelunäkyvän avulla voi kuvata miten eri palvelu osat toimivat sen ollessa toiminnassa. 

[![](http://img.youtube.com/vi/tLuiQ9p8RkU/0.jpg)](http://www.youtube.com/watch?v=tLuiQ9p8RkU "")

### Tietokantakuvaus (Database ER-diagram)

>Palvelua määriteltäessä on yleistä kuvata tarvittavan tietovaraston karkeaa rakennetta esim. ER-kaavion muodossa. 
Tämä antaa kuvaa siitä millainen ratkaisu tarvitaan Voit soveltaa PlantUML-kuvausta ER-kaavion tuottamiseen.

**Esimerkki**

```plantuml
' hide the spot
hide circle

' avoid problems with angled crows feet
skinparam linetype ortho

entity "Entity01" as e01 {
  *e1_id : number <<generated>>
  --
  *name : text
  description : text
}

entity "Entity02" as e02 {
  *e2_id : number <<generated>>
  --
  *e1_id : number <<FK>>
  other_details : text
}

entity "Entity03" as e03 {
  *e3_id : number <<generated>>
  --
  *e1_id : number <<FK>>
  other_details : text
}

e01 ||..o{ e02
e01 |o..o{ e03
```

### Integraatiot muihin järjestelmiin

>Vaatimusmäärittelyssä on kuvata palvelun/tuoteen riippuvuus muista järjestelmistä. Onko joitain palvelun osia tarkoitus ostaa ulkopuoliselta palvelun tarjoajalta.
Esimerkkeinä virtuaalikoneet, laskutusjärjestelmät, valvonta ja muut palvelutuotannon ratkaisut.

* [Integraatioista IteWIkissä](https://www.itewiki.fi/opas/integraatiot/)

```plantuml
node node1
node node2
node node3
node node4
node1 -0)- node2 : service X 
node1 -0)- node3 : service Y
node1 -0)- node4 : service Z
```

** Describing integration as a sequence diagram **

> If necessary, events between systems can be described, for example, in the form of a sequence diagram.

```plantuml
node1 ->node2: Log Start Request
node2 --> node1 : Logging started
```

## Quality  Assurance

> Software

### Preliminary Service / Software Acceptance Tests

> Acceptance tests generally focus on the customer / end-user perspective. The aim is to validate, ie to validate whether the product meets the customer's wishes and whether it meets the set requirements.
Acceptance tests can be used to determine whether a product is also sufficiently high-performance, usable, or secure for customer use.

[![](http://img.youtube.com/vi/WfMrCdAr-GM/0.jpg)](http://www.youtube.com/watch?v=WfMrCdAr-GM "")


> Attach preliminary acceptance tests to the requirements in tabular form.

| Lähde | Testitapaus Id | Kuvaus | Tyyppi  |								
|:-:|:-:|:-:|:-:|
| [Feature 1](pohjat/pohja-ominaisuus.md), [FUNCTIONAL-REQ-0001]() | [Testitapaus 1](pohjat/pohja-hyvaksyntatesti.md) | esim. Tarkista kirjautuminen palveluun uutena käyttäjänä  | Hyväksyntätesti  |
| [Feature 2](pohjat/pohja-ominaisuus.md), [FUNCTIONAL-REQ-0201](), [USE-CASE-017](pohjat/pohja-hyvaksyntatesti.md) | [Testitapaus 2](pohjat/pohja-testitapaus.md) | esim. Tarkista kenkilökohtaisten tietojen poisto | Hyväksyntätesti  |
| [Feature 3](pohjat/pohja-ominaisuus.md),  | [Testitapaus 101](pohjat/pohja-hyvaksyntatesti.md) | esim. Tarkista Kirjautuminen toimivalla salasanalla | Hyväksyntätesti  |




## Standards and sources

> As part of the requirements definition, it is essential to identify important sources that are useful or relevant to the whole. Standards and pre-distributed guidelines are useful sources and as needed
clarify the meaning of the requirements.

| ID | Linkki |  |  
|:-:|:-:|:-:|
| JHS 165 ICT | http://www.jhs-suositukset.fi/c/document_library/get_file?uuid=b8118ad7-8ee4-459a-a12b-f56655e4ab9d&groupId=14 | Vaatimusmäärittely |
| SO 9241-11 | https://fi.wikipedia.org/wiki/K%C3%A4ytett%C3%A4vyys  | Käytettävyys | 
| ISO9001 | https://www.sfs.fi/julkaisut_ja_palvelut/tuotteet_valokeilassa/iso_9000_laadunhallinta/iso_9001_2015  | - | 
| - | -  | - | 
