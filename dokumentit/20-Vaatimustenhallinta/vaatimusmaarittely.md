# Palvelu XYZ:n vaatimusmäärittely (Anna palvelulle nimi)

> Täydennä seuraavat kentät! 

* [SIJOITA TOIMEKSIANNON KOODI TÄHÄN] 
* Nimimerkkisi/gitlab tunnus
* Dokumentin versionumero X.Y
* Vaatimusmäärittely pohjan versio 2.1 - 09.09.2020 (NarsuMan)

## Ohjeita määrittelytyön tekijälle

> Pidä sisällysluettelo kunnossa, eli päivitä tarvittaessa MarkDown-ankkurilinkitys. 

> Dokumentin sisällä viitataan useissa kohdissa kansioon "/pohjat". Kyseinen kansio sisältää ns. "templaatti"-tiedostoja joita käytetään apuna eri määrittelyjen kirjaamisessa. 
Tämä tarkoittaa, että tuosta kansiosta voi tarvittasessa kopioida tiedostoja.

> PlantUML-työkalun avulla on mahdollista piirtää esim. UML-kuvauskielen mukaisia kuvauksia ja liittää ne osaksi MarkDown-kuvauksia. Kurssin aikana on 
hyödyllistä tutustua sen käyttöön http://plantuml.com/ ja pyrkiä soveltamaan sitä mahdollisimman paljon eri osa-alueilla.

> HUOMIO! Älä käytä PlantUML-kuvauksissa skandinaavisia merkkejä, koska tämä johtaa ongelmiin CI/CD-prosessin aikana

> Tutustu seuraavan linkin takaa löytyvään MindMap-kuvaan, siitä miten eri käsitteet liittyvät toisiinsa. Kannattaa keskittyä ymmärtämään yhteyksien merkitys, eli kysyminen kannattaa aina :)
Kuvaus voi päivittyä kurssin aikana! 

[http://ttos0100.pages.labranet.jamk.fi/amk-2020/kurssimateriaali/kasitekartta/](http://ttos0100.pages.labranet.jamk.fi/amk-2020/kurssimateriaali/kasitekartta/)

> HUOMIO! Kun teet harjoitusta, niin poista ennen lopullista luovutusta kaikki ohjekommentit ja video-linkit sisällöstä. 

> Tiedostojen nimeämisestä: Kannattaa pyrkiä nimeämään kaikki tiedostot säännönmukaisesti esim. __use-case-001.md__,  __profiili_asiakas-2__, ominaisuus-ft1.md__ etc
> Itse MarkDown -tiedostossa ylä otsikko kannattaa täyttää myös samalla menetelmällä.   
> __Use Case: Uuden käyttäjän kirjautuminen__ 
> __Profiili: Asiakas 2__ 
> __Ominaisuus: Raportti generaattori__
> Tämä helpottaa hahmottamaan myöhemmin koko vaatimusmäärittelyn rakennetta

## Sisällysluettelo 

1. [Johdanto](#johdanto)
1. [Toimeksiantaja](#toimeksiantaja)
1. [Vaatimusmäärittelyn tekijä](#vaatimusmäärittelyn-tekijä)
1. [Palvelukuvaus](#Palvelukuvaus)
1. [Sidosryhmäkartta](#Sidosryhmäkartta)
1. [Sidosryhmät ja profiilit](#Sidosryhmät ja profiilit) 
1. [Tunnistetut riskit](#Tunnistetut-riskit)
1. [Valitut asiakastarinat](#Valitut-asiakastarinat)
1. [Palveluun liittyviä asiakaspolkuja](#Palveluun-liittyviä-asiakaspolkuja)
1. [Oleelliset käyttötapaukset](#Oleelliset-käyttötapaukset) 
1. [Tärkeimmät yleiset ominaisuudet/toiminnallisuudet](#Tärkeimmät-ominaisuudet/toiminnallisuudet) 
1. [MockUp-prototyyppi](#MockUp-prototyyppi)
1. [Alustavat Käyttäjätarinat](#Alustavat-käyttäjätarinat)
1. [Palvelun järjestelmävaatimukset](#Palvelun-järjestelmävaatimukset) 
1. [Palveluun vaikuttavat rajaukset](#Palveluun vaikuttavat rajaukset) 
1. [Palvelun liityvät laitevaatimukset](#Palvelun liityvät laitevaatimukset)
1. [Palvelun suoritusympäristöön liittyvät vaatimukset](#Palvelun suoritusympäristöön liittyvät vaatimukset)
1. [Palvelun määritellyt ominaisuudet/toiminnnallisuudet](#Palvelun määritellyt ominaisuudet/toiminnnallisuudet)
1. [Palvelun toiminnalliset vaatimukset](#Palvelun toiminnalliset vaatimukset)
1. [Palvelun ei-toiminnalliset vaatimukset](#Palvelun ei-toiminnalliset vaatimukset)
1. [Palvelun alustava arkkitehtuuri](#Palvelun alustava arkkitehtuuri)
1. [Palvelun alustava sijoittelunäkymä](#Palvelun alustava sijoittelunäkymä)
1. [Palvelun alustava tietokantakuvaus)](#Palvelun alustava tietokantakuvaus)
1. [Palvelun integraatiot muihin järjestelmiin](#Palvelun integraatiot muihin järjestelmiin)
1. [Palvelun laadun varmistuksesta](#Palvelun laadun varmistuksesta)
1. [Palvelun hyväksyntätestit](#Palvelun hyväksyntätestit)
1. [Julkaisusuunnitelma](#Julkaisusuunnitelma)
1. [Aiheeseen liityvä standardit ja lähteet](#Aiheeseen liityvä standardit ja lähteet)

## Johdanto

>Kuvaa millaisesta projektista on kyse, hieman taustaa ja aiheeseen olennaisesti liittyviä asioita? Jos kyseessä harjoitustehtävä, niin tarkista voitko 
käytää todellisten tilaajien oikeita nimiä! Muuta aina oletuksena henkilötiedot ja toimeksiantajan viralliset tiedot 

## Toimeksiantaja

>Kuka on vaatimusmäärittelyn tilaaja? Muista vaihtaa oikeat tilaajan nimet ja tiedot omiin keksittyihin!

## Vaatimusmäärittelyn tekijästä

>Kerro lyhyesti itsestäsi (tarvittaessa pseudonyyminä) tai esim. kuvitteellisen yrityksen työntekijänä.

## Palvelukuvaus

[![](http://img.youtube.com/vi/55H2C0fSiHM/0.jpg)](http://www.youtube.com/watch?v=55H2C0fSiHM "")

>Mitä palvelun avulla voidaan tehdä? Millaisia ovat sen käyttäjät? Mikä sen tehtävä on yleisesti eri sidosryhmien kannalta? 
Kannattaa nostaa esiin lyhyesti mahdolliset loppukäyttäjä ja oleellisiin palvelusta hyötyviin sidosryhmät

## Sidosryhmäkartta

>Mietitään tarkemmin millaisia käyttäjä/sidosryhmiä liittyy suunniteltuun ohjelmisto/palvelukokonaisuuteen? 
Näitä selkeyttääksemme kirjataan kaikki sidosryhmät sidosryhmäkartan muotoon. Nostetaan samalla esiin mikä on 
ko. sidosryhmän/edustajan palveluun liittyvä motivaatio. Kuvauksen voi laatia esim. piirtämällä, MindMap-muodossa tai soveltaen sopivaa UML-notaatiota.

[![](http://img.youtube.com/vi/wiNjgClkJoM/0.jpg)](http://www.youtube.com/watch?v=wiNjgClkJoM "")

> Voit tutustu nyt aiemmin mainittuun PlantUML-työkaluun ja kokeilla luoda sidosryhmäkartta käyttäen (http://plantuml.com/)
> Huomaa! PlantUML-lohkon määrittelyssä käytetään Gitlab-ympäristössä eri avainsanoja @startuml/@enduml- rivien sijaan  
> Älä käytä skandinaavisia merkkejä PlantUML-kuvauksessa,koska niiden julkaisu www-sivulla ei toimi!**

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

> Voit kuvata sidosryhmät myös esimerkiksi piirtämällä kuvan, jolloin eri profiilien erot tulevat ehkä "selkeämmin" esiin!
> Jos kuitenkin hyödynnät PlantUML kuvausta, niin päivitys ja kuvauksen ylläpito on huomattavasti nopeampaa

![](https://camo.githubusercontent.com/0d665c81987cc940b4d93c0dfdfcf0128d1d5754/68747470733a2f2f7777772e6c7563696463686172742e636f6d2f7075626c69635365676d656e74732f766965772f30303736373365342d333361362d346131312d623465312d6163366461633130306537352f696d6167652e706e67)

## Sidosryhmät ja profiilit 

> Määritellään tarkemmin hahmotellusta sidosryhmäkartasta oleelliset sidosryhmät/profiilit. Huomio, että isossa yksittäisessä sidosryhmässä voi 
olla tarve määritellä useampia eri profiileja. Tämä tarkoittaa sitä, että laaja sidosryhmä, kuten esim. __asiakaskunta__ voi käsittää useita erilaisia asiakasprofiileja, 
joilla voi olla eroja motiiveissa/arvoissa, mutta ne kuuluvat kuitenkin olennaisesti asiakaskuntaan.    

[![](http://img.youtube.com/vi/w5oXMtOGcC4/0.jpg)](http://www.youtube.com/watch?v=w5oXMtOGcC4 "")

> Huomaa! Kaikki määritellyt profiilikuvaukset kirjoitetaan itsenäiseksi MarkDown-tiedostoksi, koska tämä helpottaa niihin viittaamista muualla dokumentaatiossa esim. [Loppukäyttäjä - Keijo Korhonen](profiili-loppukayttaja.md) 
**Alla olevat profiili/sidosryhmätkuvaukset vain suuntaa antavia! Nimeä ne tarkoituksenmukaisiksi. Varmista, että ne ovat löydettävissä sidosryhmäkartasta!**

> Tässä kohtaa on aika etsiä profiilikuvauksen runkoa /pohjat kansiosta
> Profiili voi olla siis henkilö tai selkeä sidosryhmä edustaja. Tärkeää on nostaa nämä alkuvaiheessa ja käyttää niitä sitten määrittelyn edetessä

| Sidosryhmä/Profiili | Lisätietoa |
|:-:|:-:|
| [Sidosryhmä-1](pohjat/pohja-profiilikuvaus.md) | Edustaa esim x % asiakkaista |
| [Sidosryhmä-2](pohjat/pohja-profiilikuvaus.md) | Edustaa esim y % asiakaskunnasta |
| [Henkilö profiili 1](pohjat/pohja-profiilikuvaus.md) | Mieti edustaako profiili joitan määrättyä [Sidosryhmä-2](pohjat/pohja-profiilikuvaus.md) |
| [Henkilö profiili 1](pohjat/pohja-profiilikuvaus.md) | Edustaako profiili jotain sidosryhmän osaa [Sidosryhmä-3](pohjat/pohja-profiilikuvaus.md) |
| [Henkilö profiili 1](pohjat/pohja-profiilikuvaus.md) | Vai onko kyseessä ainut [Sidosryhmän-X](pohjat/pohja-profiilikuvaus.md) edustaja |

## Asiakkaan tarpeet/toiveet?

> Pohdi millaisia toiveita/tarpeita on loppukäyttäjällä liittyen palveluun? 
> Mitä kuulet asiakkaan / loppukäyttäjän suusta, kun haastattelet ko. henkilöä?
> Haastattele henkilöitä todellisessa tilanteessa? Millaisia toiveita hänellä on palvelua kohtaan?
> Kun keskustelet mahdollisen loppukäyttäjän (palvelun yksi sidosryhmä) kanssa on harvoin vastauksena tekninen toteutustapa tai muus syvälle menevä ratkaisu liittyen palveluun.
> Vastauksena voit kuitenkin saada kasan toiveita, joita asiakas odottaa palvelulta. Nämä kannattaa kirjata tässä vaiheessa talteen.

| VaatimusID | Tyyppi | Kuvaus | 								
|:-:|:-:|:-:|
| CUSTOMER-REQ-0001 | Customer Requirement | Käyttäjänä haluan kirjautua käyttäen Facebook-tunnuksia, ettei tarvitse turhaan häslätä | 
| CUSTOMER-REQ-0002 | Customer Requirement ||
| CUSTOMER-REQ-0003 | Customer Requirement ||
| CUSTOMER-REQ-0004 | Customer Requirement ||
| CUSTOMER-REQ-0005 | Customer Requirement ||

## Liiketoiminnan vaatimukset/tavoitteet?

> Pohdi millaisia toiveita/tarpeita on Liiketoiminnan näkökulmasta liittyen palveluun? 
> Jos mitään ei tule mieleen, niin pohdi millä perusteilla "kassaan" saadaa rahaa palvelusta? Saavutetaanko palvelulla kustannushyötyjä? Parantaako kustannustehokkuutta ? Antaako se jotain loppukäyttäjlle, josta hän selkeästi hyötyy ?
> Jos voit osoittaa selkeitä hyötyjä, niin ne antavat "liiketoiminnalle" merkityksen tuottaa palvelua. 

**VAPAAEHTOINEN**

| VaatimusID | Tyyppi | Kuvaus | 								
|:-:|:-:|:-:|
| BUSINESS-REQ-0001 | Business Requirement | Palvelun kirjautuminen tulee olla helppoa, että voimme saavuttaa laajan käyttäjäkunnan = 35% kohderyhmästä | 
| BUSINESS-REQ-0002 | Business Requirement ||
| BUSINESS-REQ-0003 | Business Requirement ||
| BUSINESS-REQ-0004 | Business Requirement ||
| BUSINESS-REQ-0005 | Business Requirement ||

## Tunnistetut riskit

> Millaisia riskeja liittyy tuoteen kehittämiseen, tuotteen markkinoihin, mahdollisiin kilpailijoihin, resursseihin? 
Nämä on hyvä tunnistaa alkuvaiheessa 

**VAPAAEHTOINEN**

> Avainsanat SWOT, Riskianalyysi

## Valitut asiakastarinat

> Haastattele tai "kuvittele" haastattelevasi palvelun kannalta olleellisia profiili/sidosryhmän edustajia ja pyydä heitä kuvaamaan palvelun käyttöön liittyviä oleellisia tilanteita. 
> Miten henkilö/sidosryhmä hyötyy/käyttää palvelua. Kirjoita tämä tarinan muotoon. Kerro mitä palvelun käyttö käytännössä tarkoittaa asiakkaan, pääkäyttäjän etc. näkökulmasta! 
> Alla olevassa videossa näet millaisia tarinoita **ei** ole tarkoitus kirjata tähän osioon :)

[![](http://img.youtube.com/vi/KKM_7N1-6Ew/0.jpg)](http://www.youtube.com/watch?v=KKM_7N1-6Ew "")

> Pyri kirjoittamaan auki tarina vain valitun profiilin/sidosryhmän näkökulmasta (toiset profiilit/sidosryhmät saattavat kyllä esiintyä tarinassa). Tarinassa on kätevä viitata jo aiemmin luotuihin [Profiili](pohjat/pohja-profiilikuvaus.md)-kuvauksiin.** 
> HUOMIO! Älä sekoita asiakastarinaa (Customer story) käyttäjätarinaan (User Story)

**Asiakastarina 1** 

[Profiili 1](pohjat/pohja-profiilikuvaus.md) herää aamusta ja tarkistaa puhelimellaan onko X-palvelussa tilaa aamupäivästä. Huomatessaan, että palvelussa on vapaa aika klo 11:00.........

**Asiakastarina 2** 

[Asiakas-tyyppi 3](pohjat/pohja-profiilikuvaus.md) käynnistää iltapäivällä rakennustyömaalla sementtimyllyä, kun hänelle tulee viesti X-palvelusta.........

## Palveluun liittyviä asiakaspolkuja

> Mieti auki aiemmin kirjoittamaasi asiakastarinaa ja piirrä sen pohjalta hahmotelma asiakaspolusta. 
> Mitä tapahtumia siihen liittyy? Mieti palvelua laajempana kokonaisuutena!
> Asiaspolkukuvauksen avulla kuvataan tapahtuma sarjaa joka käydään jossain valitussa tilanteessa läpi palvelun käytön aikana. 
> Asiakas kohtaisia palvelupolkuja voi olla useita, mutta tärkeintä on tunnistaa alkuvaiheessa oleellisimmat. 
> Palvelupolkua kuvattaessa voi hyödyntää esim. Swim lane/BluePrint/tilakone-kuvausta tai muuta sopivaksi katsottua kuvausta.
> Tärkeää on kuitenkin kuvata polku ja käyttää sitä tarvittaessa selkeyttämään ymmärrystä tavoitellusta palvelusta. 
> Käy läpi tekemäsi kuvausta jonkun toisen henkilön kanssa yhdessä? Käy läpi polku ja kerro mitä sen aikana tapahtuu..

[![](http://img.youtube.com/vi/kNXjKquK3A0/0.jpg)](http://www.youtube.com/watch?v=kNXjKquK3A0 "")

> Asiakaspolun luonnostelu on hyvä aloittaa esim. asiakastarinan pohjalta. Polkuja laaditaan tarvittaessa useampia eri profiilien/tilanteiden näkökulmasta. Yhteen kuvaukseen ei siis kannata upottaa liikaa tapahtumia

[![](http://img.youtube.com/vi/j7U8pqUN9EM/0.jpg)](http://www.youtube.com/watch?v=j7U8pqUN9EM "")

**asiakaspolku PlantUML-esimerkki tilakoneena**

> Kokeillaan luonnostella asiakaspolkua PlantUML-työkalun avulla. Kannattaa kokeilla ehdottomasti myös muita tapoja!
> Sovella esim. PlantUML SDL/Swimlane kuvausta?

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
> Palvelupolkujen kuvauksissa voi tarvittaessa soveltaa myös muita työkaluja. Esim. https://canvanizer.com, PowerPoint etc
> Tutustu esim. Blueprint-kuvaukseen

## Oleelliset käyttötapaukset

> Palvelupolun  kuljettaessa käydään läpi laajempi ketju palveluun käyttöön liittyviä käyttötilanteitaa. Näitä tilanteita, joissa käsitellään itse ohjelmistopalvelua 
sähköisten rajapintojen/käyttöliittymien kautta kuvata ns. käyttötapauksien (Use Case) avulla.   
> **Käyttötapaus** (Use Case) ymmärretään helposti väärin, koska se liitetään usein pelkästään tuotteen 
**käyttötarkoituksen** kuvaamiseen. Palvelusta ensi kertaa keskusteltaessa puhutaan sen eri **käyttötarkoituksista**, eli sitä mihin 
ohjelmistoa/palvelua voidaan hyödyntää. Kun puhutaan palvelun määrittelystä ja siihen liittyvien käyttötapauksien tunnistamisesta 
on kyseessä hieman eri asia. Käyttötapauksessa keskitytään tarkastelmaan palvelun käyttöä varsin rajatussa tilanteessa. 
Käyttötapaukset (Use Case) kuvaataan UML-kuvauskielen avulla.

>UML Use Case-kuvaus voidaan tehdä PlantUML-kuvauksena, mutta tarkempi käyttötapauksen avaaminen vaatii erillisen kuvaus dokumentin

```plantuml

rectangle Tilaus {
Profiili_1--(Tilauksen tekeminen)
Profiili_1--(Tilauksen muokkaus)
Profiili_1--(Tilauksen peruminen)
}

rectangle Tilausten_hallinta {
Hallinto_1--(Tilauksien tarkistaminen)
Hallinto_1--(Tilauksen muokkaus)
Hallinto_1--(Tilauksen siirto)
Huolto_1--(Tilauksen manuaalinen poisto)
Huolto_1--(Tilauksen tyhjennys)
}

```

> On hyödyllistä kirjata kaikki oleelliset käyttötapaukset yhteen laajempaan Use Case-kuvaukseen, koska sen avulla voi tarkastella
helpommin koko järjestelmää. Huomio! Laajemmassa järjestelmä kokonaisuudessa saattaa olla useita satoja eri käyttötapauksia. 

[![](http://img.youtube.com/vi/DupdE35Ilps/0.jpg)](http://www.youtube.com/watch?v=DupdE35Ilps "")

[![](http://img.youtube.com/vi/-3YtgJGuIek/0.jpg)](http://www.youtube.com/watch?v=-3YtgJGuIek "")

[![](http://img.youtube.com/vi/oVGmIOavB74/0.jpg)](http://www.youtube.com/watch?v=oVGmIOavB74 "")

> Käyttötapauksen tarkempi kuvaus harjoitusympäristössä tapahtuu käyttötapaus-kohtaisen pohja-tiedoston avulla. Jokaista käyttötapausta varten 
laaditaan itsenäinen tiedosto.

| Käyttötapaus | Osa-alue | toiminnallisuus/ominaisuus johon UC -liittyy |
|:-:|:-:|:-:|
| [Käyttötapaus 1 - Tilauksen muokkaus](pohjat/pohja-kayttotapaus.md) | Tilausten hallinta | [Tilaushallinta-paneeli](pohjat/pohja-ominaisuus.md) | 
| [Käyttötapaus 2 - Tilauksen tarkistaminen](pohjat/pohja-kayttotapaus.md) | Tilausten hallinta | [Tilaushallinta-paneeli](pohjat/pohja-ominaisuus.md) | 
| [Käyttötapaus 2 - Tilauksen siirto](pohjat/pohja-kayttotapaus.md) | Tilausten hallinta | [Tilaushallinta-paneeli](pohjat/pohja-ominaisuus.md) |

## Tärkeimmät ominaisuudet/toiminnallisuudet 

> Hahmotellaan tähän kohtaan ominaisuudet pelkästään "ranskalaisilla viivoilla", eli mitä palvelulla mielestäsi on mahdollista tehdä?
> Mieti tilannetta, kun joku kysyy mitä palvelulla voi tehdä? Mitä vastaat ja mitkä toiminnot nostatat esiin ehdottomasti valtteina verrattuna muihin vastaaviin palveluihin?
> Päivitä lista myöhemmin, kun se tarkentuu? 
> Tässä kohtaa kannattaa tarkistaa mitä olivat asiakkaan esittämät toiveet palvelusta? Niistä voisi löytyä ehkä joitain tässä vaiheessa?
> Tarkemmat toiminnallisuudet tarkentuvat myöhemmin dokumentissa.  
> Tässä vaiheessa riittää:


- Oleellisia toimintoja 
    - Asiaksi-profiili-1 voi lähettää postia toiselle henkilölle
    - Asiakas-profiili-2 voi saada tietoa aiemmin tehdyistä valinnoista
    - Ylläpito-henkilö voi poistaa laskun
    - Ylläpito-henkilö voi luoda uuden laskun
    - muita?


## MockUp-prototyyppi

> Suunniteltavan palvelun toimintoja määriteltäessä voi olla hyödyllistä piirtää avuksi MockUp-kuvausta käyttötilanteen 
> tai toiminnallisuuksien hahmottamiseksi. Kun palvelun käyttöliittymää tai palvelupolkua käydään läpi mockup-kuvauksen kautta
> voi ymmärtää helpommin mitä tarvittavia toimintoja on kirjattava myös vaatimusmäärittelyyn. 
> MockUp-kuvaus on myös hyödyllinen apuväline tilaajan/toimeksiantajan väliseen keskusteluun.

[![](http://img.youtube.com/vi/a5qLMBYWv5A/0.jpg)](http://www.youtube.com/watch?v=a5qLMBYWv5A "")

> Kun laadit harjoitustehtävään MockUp-näkymän pohdi haluatko kuvata koko palvelua vai keskittyä yksittäisen toiminnallisuuden tarkasteluun?
> Harjoitustehtävän kannalta on oleellista, että käytät MockUp-kuvausta tarpeellisen asian esittämiseen. Pyri kuvaamaan kokonaisuutta ja esittämään siinä
> tunnistamiesi toimintojen tarkoituksen mukaisuutta. Jos huomaat piirtämisvaiheessa puutteita vaatimuksissa tai tarvetta kirjata niitä lisää, niin se on juuri
> tarkoitus. Vaatimusmäärittely tarkentuu tekemällä aktiivista hahmottelua vaaditusta kokonaisuudesta. 


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

## Palvelun liittyvät tuotannolliset ja tekniset vaatimukset 

**Tämä osa-alue vielä kesken**

> Sähköisiä palveluita määriteltäessa teknisestä vaatimukset liittyvät tarvittaviin
teknologioihin, laitteistoihin tai palvelun vaatimiin fyysisiin rakenteisiin. Ohjelmistopalvelua määriteltäessä
kannattaa tunnistaa ajoissa puhtaasti tekniset/tuotannolliset vaatimukset ja kirjata ne vaatimusmäärittelyyn niille varattuun osaan. 
Liiallinen keskittyminen teknisten tuotanto/toteutusvaatimusten kirjaukseen ei ole välttämättä suositeltavaa, koska 
suunnittelun aikana ohjelmistoa/palvelun toteutusvaatimukset voivat vielä muuttua. Kehitysvaiheessa kätevästi koettu ratkaisu 
voi osoittatua kalliiksi palvelun tuotteistamisvaiheessa. 
> Usein määrittelyn avuksi pyydetään erilaisia asiantuntijalausuntoja liittyen esimerkiksi järjestelmän arkkitehtuuriin ja tuotantoalustaan
> Yleisesti ottaen tässä osiossa voidaan pohtia esim seuraavia kysymyksiä.

- Miten palvelu tullaan tuottamaan? Pilvessä, omilla palvelimilla etc? 
- Onko tarkoistus tarjota esim. SAAS/HOSTED-palveluna etc 
- Käytetäänkö Pilvipalveluita osana ratkaisua vai hyödynnetäänkö omia palvelimia
- Mitä muita palveluita tarvitaan ko. palvelun tueksi? Käyttäjien tunnistamis palvelut?
- Miten palvelu on oltava saatavilla 24/7h 100% ? 
- Millainen SLA palvelulle laaditaan?
- Miten paljon kustannuksia saa palvelun tuotannolle sallitaan ?
- Millaiset tiedonsäilytys/arkistointi tarpeet liittyvät palveluun? 

[![](http://img.youtube.com/vi/s7AcxrxcVd0/0.jpg)](http://www.youtube.com/watch?v=s7AcxrxcVd0 "")

> Millaisia tuotantoympäristöjä/teknologisia ratkaisuja käyteään käytetään oikeasti? Voit tutkia esimerkkejä [Stack Share](https://stackshare.io/):palvelussa
> Esim. millainen on tekninen ratkaisu toteutukselle ja miten eri teknologioita tullaan hyödyntämään. 
> Harjoitustehtävässä tekniset vaatimukset jäävät tarkoituksella sivuasemaan. Keskitymme ohjelmiston vaatimuksiin!
> Voit kuitenkin miettiä millaisia vaatimuksia esim. tuotantoympäristöllä on? 

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| SYSTEM-HW-REQ-0002 | System Technical Requirement | Palvelun tärkeimpien palvelujen on oltava vähintään kahdennettu N+1 | |
| SYSTEM-HW-REQ-0003 | System Technical Requirement | Palvelimien vähimmäis muistikapasiteeti >32GB  ||
| SYSTEM-HW-REQ-0004 | System Technical Requirement | Prosessorin tyyppi Intel/AMD x64||
| SYSTEM-HW-REQ-0005 | System Technical Requirement | Palvelimen fyysinen sijainti on kotimaassa (FI) ||
| SYSTEM-HW-REQ-0005 | System Technical Requirement | Verkkoyhteyden nopeus palveluun vähintään >100MB/s ||
| SYSTEM-HW-REQ-0005 | System Technical Requirement | Palvelinkaapin suositeltava koko 1m X 1m X 2m ||

### Palvelun toteuttamisen kannalta tärkeät oleelliset rajaukset ja standardit

Rajaus/rajoite = Constrain

> Eri ohjelmistojena/palvelujen toteutusta ja käyttöä ohjaavat usein lait ja säädökset. Näiden edellyttämät vaatimukset voidaan kirjataan tarvittaessa vaatimusmäärittelyyn.
Rajausten vaikutus koskee usein palvelun jonkin osa-kokonaisuuden toteuttamista. Tästä syystä eri rajoitteet on tunnistettava ajoissa, koska vaikutus 
saataa olla varsin ratkaiseva pitemmällä tähtäimella. Esimerkkinä tästä on viime vuonna voimaan tullut [EU GDPR-säädös](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation).
> Kannattaa tutkia esimerkiksi https://www.sfs.fi/aihealueet/terveydenhuolto/laakinnalliset_laitteet tai http://docs.jhs-suositukset.fi/jhs-suositukset/JHS190/JHS190.html

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| CONSTRAINT-REQ-S00000 | Constrain | Palvelun kirjautumisprosessin on noudatettava XYZ-käytäntöjä  | [Kirjautuminen ft1](pohjat/pohja-ominaisuus.md) |
| CONSTRAINT-REQ-S00001 | Constrain | On huomioitava Standardi ZZZ osana palvelun tapahtuma login talletusta | [Log-palvelin](pohjat/pohja-ominaisuus.md)|
| CONSTRAINT-REQ-S00002 | Constrain |||
| CONSTRAINT-REQ-S00003 | Constrain |||
| CONSTRAINT-REQ-S00004 | Constrain |||
| CONSTRAINT-REQ-S00005 | Constrain |||
| CONSTRAINT-REQ-S00006 | Constrain |||


### Palvelun toiminnalliset vaatimukset (Functional Requirements)

>Mitä toimintoja palveluun liittyy? Nämä kannattaa kirjata ensi ns. toiminnallisina vaatimuksina? Toiminnallisilla vaatimuksilla kuvataan ohjelmistolta/järjestelmältä vaadittuja toimintoja.
Toiminnalliset vaatimukset ovat helpoimmin tunnistettavia. Vältä useamman vaatimuksen kirjaamista samaan lauseeseen! Jokainen vaatimus erikseen.


[![](http://img.youtube.com/vi/qO2qEIEHy_A/0.jpg)](http://www.youtube.com/watch?v=qO2qEIEHy_A "")

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| FUNCTIONAL-REQ-C0001 | Functional Requirement | Käyttäjänä (Asiakas Profiilit 1-4) voin kirjautua käyttäen Facebook-tunnuksia | [Kirjautuminen ft1](pohjat/pohja-ominaisuus.md) |
| FUNCTIONAL-REQ-C0002 | Functional Requirement | Käyttöliittymän on toimittava myös ääniohjattuna, koska käyttäjillä saattaa olla näkövammoja | [Kirjautuminen ft1](pohjat/pohja-ominaisuus.md), [Tilaushallinta](pohjat/pohja-ominaisuus.md) |
| FUNCTIONAL-REQ-C0003 | Functional Requirement |||
| FUNCTIONAL-REQ-C0004 | Functional Requirement |||
| FUNCTIONAL-REQ-C0005 | Functional Requirement |||
| FUNCTIONAL-REQ-C0006 | Functional Requirement |||
| FUNCTIONAL-REQ-C0007 | Functional Requirement |||
| FUNCTIONAL-REQ-C0008 | Functional Requirement |||
| FUNCTIONAL-REQ-C0009 | Functional Requirement |||
| FUNCTIONAL-REQ-C0010 | Functional Requirement |||

### Palvelun ohjelmiston ominaisuudet, eli "featuret"

Yllä olevassa listassa on kirjattu muistiin erilaisia toiminteita, joita palvelum avulla voi suorittaa. Mieti seuraavaksi, mitkä näistä toiminnoista liittyvät isompii toiminnallisuuksiin.  
Kirjaa alla olevaan taulukkoon nämä päätoiminnot. Niitä voidaan kutsua "Featureiksi" ja on tärkeää ymmärtää eri toimintojen kokoluokat. Tunnistat karkeasti päätoiminnallisuuden kun mietit mitä palvelulla on oleellisinta saada aikaan. 
Ylempänä määritellyt toiminnalliset vaatimukset mahdollisesti tarkentavat tai liittyä oleellisesti päätoiminnallisuuteen.   
Esimerkkinä Verkkopankki palvelussa on oleellinen toiminto "maksu tililtä", joka on käytännössä tärkeä palvelun ominaisuus. Tähän 
toiminnallisuuteen liittyy useita muita pienempiä ja tarkentavia toiminnallisia vaatimuksia. Mieti millä eri tavoin maksu tililtä toimintoa voi käyttää?

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
| [Feature 6](pohjat/pohja-ominaisuus.md) | P5 | Esim [FUNCTIONAL-REQ-C0221]() |
| [Feature 7](pohjat/pohja-ominaisuus.md) | P5 | Esim [FUNCTIONAL-REQ-C0021]() |
| [Feature 8](pohjat/pohja-ominaisuus.md) | P5 | EEsim [FUNCTIONAL-REQ-C0301]() |
| [Feature 9](pohjat/pohja-ominaisuus.md) | P5 | Esim [FUNCTIONAL-REQ-C0401]() |
| [Feature 10](pohjat/pohja-ominaisuus.md) | P5 | Esim [FUNCTIONAL-REQ-C0401]() |



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
| PERFORMANCE-REQ-0002 | Non-Functional Performance |||
| PERFORMANCE-REQ-0003 | Non-Functional Performance |||
| PERFORMANCE-REQ-0004 | Non-Functional Performance |||
| PERFORMANCE-REQ-0005 | Non-Functional Performance |||

>Millaisia vaatimuksia palveluun kohdistuu tietoturvan näkökulmasta?

> Tutustu [Ssecurity cards-metodiin](http://securitycards.cs.washington.edu/cards.html)

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| SECURITY-REQ-0001 | Non-Functional Security | Salasanassa on käytettävä vähintään MD5-tason salausta, koska standardi XY112 sitä edellyttää | [Kirjautuminen ft1](ft1-ominaisuus.md) |								
| SECURITY-REQ-0002 | Non-Functional Security |||
| SECURITY-REQ-0003 | Non-Functional Security |||
| SECURITY-REQ-0004 | Non-Functional Security |||
| SECURITY-REQ-0005 | Non-Functional Security |||
| SECURITY-REQ-0006 | Non-Functional Security |||
| SECURITY-REQ-0007 | Non-Functional Security |||
| SECURITY-REQ-0008 | Non-Functional Security |||
| SECURITY-REQ-0009 | Non-Functional Security |||
| SECURITY-REQ-0010 | Non-Functional Security |||

>Mitä tarkoitetaan käyttävyydellä? Millaisia asioita/ohjeistuksia on otettava huomioon palvelua toteutettaessa?

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| USABILITY-REQ-0000 | Non-Functional Usability | | [Kirjautuminen ft1](ft1-ominaisuus.md) | |	
| USABILITY-REQ-0001 | Non-Functional Usability | | [Käytettävyys](https://fi.wikipedia.org/wiki/K%C3%A4ytett%C3%A4vyys) |
| USABILITY-REQ-0002 | Non-Functional Usability | | [Käytettävyys](https://fi.wikipedia.org/wiki/K%C3%A4ytett%C3%A4vyys) |
| USABILITY-REQ-0003 | Non-Functional Usability | | [Käytettävyys](https://fi.wikipedia.org/wiki/K%C3%A4ytett%C3%A4vyys)|
| USABILITY-REQ-0004 | Non-Functional Usability | | |[Käytettävyys](https://fi.wikipedia.org/wiki/K%C3%A4ytett%C3%A4vyys)|
| USABILITY-REQ-0005 | Non-Functional Usability | | [Käytettävyys](https://fi.wikipedia.org/wiki/K%C3%A4ytett%C3%A4vyys)|

>Millaisia asioita on otettava huomioon tuotteen laadunvarmistamisen kannalta?. Kehityksen aikana ohjelmistotuotteeseen on luotava tarvittavat rajapinnat tai työkalu-ohjelmistoja, 
joiden avulla voidaan hallita testikohteena olevaa tuoteversiota. Nämä vaatimukset on kirjattava ajoissa, koska ne vaikuttavat ratkaisevasti tuotteen testausmahdollisuuksiin.
Esimerkkinä voidaan miettiä logien hallintaa, niiden keräämistä, alkutilanteeseen saattamista. 

| VaatimusID | Tyyppi | Kuvaus | Ominaisuus johon vaikuttaa |								
|:-:|:-:|:-:|:-:|
| TESTABILITY-REQ-0000 | Non-Functional Testability | Käyttäjärekisteri on kyettävä palauttamaan alkutilaan ennen testien ajoa  | [Kirjautuminen ft1](ft1-ominaisuus.md)	 |	
| TESTABILITY-REQ-0001 | Non-Functional Testability ||[Lisätietoa](https://fi.wikipedia.org/wiki/Ohjelmiston_laatu)|	
| TESTABILITY-REQ-0002 | Non-Functional Testability ||[Lisätietoa](https://fi.wikipedia.org/wiki/Ohjelmiston_laatu)|	
| TESTABILITY-REQ-0003 | Non-Functional Testability ||[Lisätietoa](https://fi.wikipedia.org/wiki/Ohjelmiston_laatu)|	
| TESTABILITY-REQ-0004 | Non-Functional Testability ||[Lisätietoa](https://fi.wikipedia.org/wiki/Ohjelmiston_laatu)|	
| TESTABILITY-REQ-0005 | Non-Functional Testability ||[Lisätietoa](https://fi.wikipedia.org/wiki/Ohjelmiston_laatu)|


## Extra

>Kannattaa tutustua :) https://www.etteplan.com/services/testing-and-test-laboratory/product-safety-and-training

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

**Integraation kuvaaminen sekvenssikaaviona**

> Järjestelmien välisiä tapahtumia voi kuvata tarvittaessa esim. sekvenssikaavion muodossa. 


```plantuml
node1 ->node2: Log Start Request
node2 --> node1 : Logging started
```

## Palvelun laadun varmistus

>Ohjelmisto

### Palvelun/Ohjelmiston alustavat hyväksyntätestit

>Hyväksyntätesteissä keskitytään yleisesti asiakkaan/loppukäyttäjän näkökulmaan. Tavoitteena on kelpuuttaa, eli validoida , onko tuote asiakkaan toiveiden mukainen ja täyttääkö se asetetut vaatimukset.
Hyväksyntätesteillä voidaan selvittää onko tuote myös riittävän suorituskykyinen, käytettävä tai tietoturvallinen asiakkaiden käyttötarkoitukseen. 

[![](http://img.youtube.com/vi/WfMrCdAr-GM/0.jpg)](http://www.youtube.com/watch?v=WfMrCdAr-GM "")



>Kiinnitetään alustavat hyväksyntätestit vaatimuksiin taulukon muodossa.

| Lähde | Testitapaus Id | Kuvaus | Tyyppi  |								
|:-:|:-:|:-:|:-:|
| [Feature 1](pohjat/pohja-ominaisuus.md), [FUNCTIONAL-REQ-0001]() | [Testitapaus 1](pohjat/pohja-hyvaksyntatesti.md) | esim. Tarkista kirjautuminen palveluun uutena käyttäjänä  | Hyväksyntätesti  |
| [Feature 2](pohjat/pohja-ominaisuus.md), [FUNCTIONAL-REQ-0201](), [USE-CASE-017](pohjat/pohja-hyvaksyntatesti.md) | [Testitapaus 2](pohjat/pohja-testitapaus.md) | esim. Tarkista kenkilökohtaisten tietojen poisto | Hyväksyntätesti  |
| [Feature 3](pohjat/pohja-ominaisuus.md),  | [Testitapaus 101](pohjat/pohja-hyvaksyntatesti.md) | esim. Takista Kirjautuminen toimivalla salasanalla | Hyväksyntätesti  |

## Julkaisusuunnitelma


> Julkaisusuunnitelman visualisoidulla muodolla on helpompi esittää ominaisuuksien julkaisut kehityksen aikanan.
Alla oleva kuva on luotu hyödyntäen PlantUML-työkalua. Sen avulla on luoto ns. Gantt-kaavio ominaisuuksien julkaisuajankohdista.

> Oletamme, että tuotteessa on muutamia ominaisuuksia, joiden järjestys on mietitty ennakkoon..

```plantuml
Project starts the 2019-5-15
[Version v1.0 EarlyAdopter] Starts 2019-5-15 and ends 2019-7-30 
[Design Phase] Starts 2019-5-15 and ends 2019-6-15
[Feature 1 v 1.0] Starts 2019-5-25 and ends 2019-6-15
[Feature 2 v 1.0] Starts 2019-5-25 and ends 2019-7-1
[Feature 3 v 1.1] Starts 2019-6-15 and ends 2019-7-15
[Feature 4 v 1.1] Starts 2019-6-25 and ends 2019-7-20
[Feature 5 v 2.3] Starts 2019-6-1 and ends 2019-7-21
[Accceptance Testing ] Starts 2019-7-21 and ends 2019-7-23
```

[![](http://img.youtube.com/vi/Z1cSK_IMqMs/0.jpg)](http://www.youtube.com/watch?v=Z1cSK_IMqMs "")

>Tuotteen/ohjelmiston eri ominaisuuksista kehitetään usein eri versioita ja tämä johtaa usein erilaisiin tuotekokonaisuuksiin. Puhutaan ns. tuotekonfiguraatiosta, jonka avulla kiinnitetään eri 
ominaisuusversiot yhteen ohjelmiston julkaisu versionn. 

> Alla olevassa taulukossa on esitelty julkaisuun "EarlyAdopter - Versio 1.0" valitut toiminnallisuudet 

| Ominaisuus/toiminnallisuus | Versio | Milloin testattavissa | Julkaisu  |
|:-:|:-:|:-:|:-:|
| [Feature 1](pohjat/pohja-ominaisuus.md) | 1.0 | 15.6.2019 | V1.0 |
| [Feature 2](pohjat/pohja-ominaisuus.md) | 1.0 | 1.7.2019  | V1.0 |
| [Feature 3](pohjat/pohja-ominaisuus.md) | 1.1 | 15.7.2019 | V1.0 |
| [Feature 4](pohjat/pohja-ominaisuus.md) | 1.1 | 20.7.2019 | V1.0 |
| [Feature 5](pohjat/pohja-ominaisuus.md) | 2.3 | 23.7.2019 | V1.0 |


## Standardit ja lähteet

> Vaatimusmäärittelyn osana on oleellista tuoda esiin tärkeät lähteet, joista on hyötyä tai merkitystä kokonaisuuden kannalta. Standardit ja ennalta jaetut ohjeistukset ovat hyödyllisiä lähteitä ja tarvittaessa 
selkeyttävät vaatimusten merkitystä.

| ID | Linkki |  |  
|:-:|:-:|:-:|
| JHS 165 ICT | http://www.jhs-suositukset.fi/c/document_library/get_file?uuid=b8118ad7-8ee4-459a-a12b-f56655e4ab9d&groupId=14 | Vaatimusmäärittely |
| SO 9241-11 | https://fi.wikipedia.org/wiki/K%C3%A4ytett%C3%A4vyys  | Käytettävyys | 
| ISO9001 | https://www.sfs.fi/julkaisut_ja_palvelut/tuotteet_valokeilassa/iso_9000_laadunhallinta/iso_9001_2015  | - | 
| - | -  | - | 
