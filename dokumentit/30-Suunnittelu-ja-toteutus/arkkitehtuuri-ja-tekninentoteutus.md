# Ohjelmistoarkkitehtuuri

|  |  |
|:-:|:-:|
| Dokumentti | Ohjelmiston arkkitehtuurikuvaus |
| Laatija: | *nimi* |
| Versio: | *0.0?* |
| Päivämäärä: | 1.x.202y |


![](https://openclipart.org/image/400px/svg_to_png/290580/dogskeleton.png)

Tämä dokumentin pohjana käytetään alkuperäistä http://www.cs.tut.fi/ohj/dokumenttipohjat/pohjat/suunnittelu/hytt_drsuunnittelu.doc

*Nöyrin kiitos alkuperäisen tekijöille!*

# 1.JOHDANTO

### 1.1		Tarkoitus ja kattavuus


>Esitetään dokumentin tarkoitus, miksi se on tehty ja mihin tarkoitukseen ja kenelle se on tarkoitettu (oman firman toteutusporukka vai alihankkija vai kuka).
Luetellaan, mitä asioita dokumentissa kuvataan; varsinkin jos lukija ei ole tottunut lukemaan suunnitteludokumentteja.
Määritetään suunnittelun kattavuus suhteessa määrittelyyn. Mikäli suunnittelu ei kata koko määrittelyä tulee se mainita tässä (eli mitä muita suunnitteluvaiheen dokumentteja on olemassa, esim. jos käyttöliittymän tai tietokannan suunnittelu on irrotettu omiksi dokumenteikseen).

### 1.2		Tuote ja ympäristö

> Mainitaan tuotteen nimi, tarkoitus ja tavoitteet. Tuotteen toimintaympäristö yleisesti: esimerkiksi PC, Windows98 ja lähiverkko.

### 1.3		Määritelmät, merkintätavat ja lyhenteet 

>Selitetään aakkosjärjestyksessä sanat ja käsitteet, jotka eivät ole lukijalle tuttuja, tai joiden voidaan ajatella tuottavan sekaannuksia erikoisella käytöllään tai jotka eivät yleisesti ole tiedossa. Nämä kannattaa esittää aakkosjärjestyksessä. Esim. ASCIImerkistöstä ilmoitetaan, onko se 7bittinen (esim. ISO 10646) tai 8bittinen (esim. ISO 88591).

### 1.4		Viitteet

>Luetellaan viittaukset muihin lähteisiin (dokumentit, standardit, käsikirjat, tyyliohjeet, jne.) viitteen mukaan aakkosjärjestyksessä. Viitteistä ilmoitetaan nimi, versio, päiväys ja mistä ne ovat löydettävissä. Viitteiksi voidaan laittaa esimerkiksi:

  * dokumentit, joihin on viitattu (esim. määrittely)
  * dokumentit, jotka liittyvät systeemiin tai sen rakentamiseen
  * lisätiedot
  * (koodaus)tyyliohjeet. 
  * Mikäli suunnittelu ei kata koko määrittelyä, se mainitaan tässä. Samalla selvitetään, mitä muita suunnitteluvaiheen dokumentteja on olemassa. 
  * Esimerkiksi tietokannan tai käyttöliittymän suunnittelu on voitu irrottaa omaksi dokumentikseen).

### 1.5		Yleiskatsaus dokumenttiin 

>Kohdassa kuvataan dokumentin rakenne, sisältö ja organisointi; mitä missäkin luvussa käsitellään. Tämä on tärkeää varsinkin jos lukija ei ole tottunut lukemaan suunnitteludokumentteja.
>Mikäli ensimmäinen luku on kokonaisuudessaan samalla sivulla kuin tämä kohta (1.5 yleiskatsaus) tai se on kovin lyhyt, ei sitä tarvitse tässä kohdassa mainita, vaan voidaan aloittaa >luvun 2 asioista.
>Kunkin luvun sisältöä kuvataan enemmän kuin mitä pelkkä sisällysluettelon selaaminen kertoo.
>Myös mahdolliset liitteet kuvaillaan tässä, esim. liitteet 14 sisältävät järjestelmän pääosien luokkakaaviot.

## 2.		JÄRJESTELMÄN YLEISKUVAUS

>Luvussa esitetään toteutettavan järjestelmän yleiskuvaus, johdatus asiakkaan ympäristöön ja sovellusalueeseen.

### 2.1		Sovellusalueen kuvaus

>Kuvataan ympäristö, johon tuote tai järjestelmä liittyy. Esimerkiksi TUT:n opintotoimiston salivarausjärjestelmä.

### 2.2		Järjestelmän liittyminen ympäristöönsä

>Määritetään, mitä järjestelmä tässä ympäristössä tekee, ja käyttääkö kuvattu järjestelmä muita ohjelmia tai järjestelmiä, eli onko se jonkin suuremman järjestelmän osa.

### 2.3		Laitteistoympäristö

>Kuvataan laitteistoympäristö, jossa järjestelmä toimii. Esimerkiksi mitä oheislaitteita tarvitaan, mitä keskusyksiköltä odotetaan, mitä laitteiden ominaisuuksia ohjelma hyödyntää, mitkä laitteiston ominaisuudet rajoittavat teknisiä ratkaisuja ja millaiset ovat liittymät muihin tietokoneisiin.

### 2.4		Ohjelmistoympäristö

>Esitetään järjestelmän ohjelmistoympäristö tarkkoine versioineen: käyttöjärjestelmä, kääntäjä, muut apuvälineet, tietokantaohjelmisto, tietoliikenneohjelmisto, wwwselain, liittymät muihin ohjelmistoihin ja sovelluksiin sekä muut laitteistossa yhtä aikaa ajettavat ohjelmat. Tarvittaessa voidaan selittää myös kehitys ja testausympäristö. 

### 2.5		Toteutuksen keskeiset reunaehdot

>Mainitaan tärkeät reunaehdot. Ne ovat usein asiakkaalta vaatimuksia.  Niitä voivat olla esimerkiksi toteutuslaitteisto, ohjelmisto, lait tai asetukset, vasteajat, kriittisyys, oikeellisuus, turvallisuus ja ohjelmointikieli.
Tässä voidaan mainita myös ohje dokumentin sekä koodin kommenttien, muuttujien ja funktioiden yms. kielisyydestä.

### 2.6		Sopimukset ja standardit

>Jos käytetään standardien ja/tai eri sopimusten mukaisia suunnittelumenetelmiä, kuvaustapoja, dokumentointimalleja tms., niin ne mainitaan. Kuvataan myös mahdollisesti valmisosien käyttö ja niiden nimeämissäännöt (tarvittaessa viittaus liitteeseen tai omaan dokumenttiinsa).
Myös erilaiset direktiivit, viranomaismääräykset ja ohjeistot mainitaan, mikäli ne vaikuttavat suunnitteluun. Tässä ne voi mainita nimeltä ja kohdassa 1.5 esitetään koko lähde tarkasti.
Otetaan kantaa myös projektin aineiston luottamuksellisuuteen mikäli siitä on aiheellista mainita. Luottamuksellisuuteen liittyviä asioita ovat esimerkiksi: jakelu, säilytys, vanhojen versioiden hävittäminen jne.

## 3.		ARKKITEHTUURIN KUVAUS

>Tämä on suunnitteludokumentin tärkein kohta. Luku sisältää asiat, jotka kaikkien järjestelmän toteutusta tekevien täytyy tietää ja ymmärtää. Luvussa kuvataan (perusteluineen) mm. suunnittelu¬periaatteet, teknologiavalinnat ja ohjelmiston arkkitehtuuri yleisesti.  Jaottelua alilukuihin ei välttämättä kannata tehdä tässä esitetyllä tavalla, vaan kannattaa miettiä, mikä on kulloisessakin tapauksessa järkevin esitysjärjestys luvun asioille. Esimerkiksi kohdat 3.1 ja 3.2 kannattaa joskus yhdistää.

### 3.1		Suunnitteluperiaatteet

>Tässä kohdassa esitetään kehitettävän järjestelmän toteutuksen  ”perusfilosofia”. Filosofia määrittelee mahdollisimman suppean ja yksinkertaisen joukon peruskäsitteitä ja sääntöjä, joiden mukaan suunnittelupäätöksiä nyt ja tulevaisuudessa tehdään. Peruskäsitteet ja säännöt voivat liittyä kohdan 3.2 arkkitehtuurikuvauksen joihinkin keskeisiin moduuleihin niin kiinteästi, että niiden kuvaus kannattaa siirtää tähän (tai jopa yhdistää kohdat 3.1 ja 3.2). Myös tehdyt teknologiavalinnat voivat olla osa ”sääntöjä”. Filosofian voi ajatella sisältävän järjestelmän toteutuksesta sellaiset asiat, jotka säilyvät (todennäköisesti) muuttumattomina koko elinkaaren ajan. Filosofia helpottaa toteuttajien keskinäistä kommunikointia ja yhdenmukaistaa suunnitteluratkaisuja järjestelmän eri osissa. Esimerkkejä:


  * Ohjausjärjestelmä toteutetaan mikrokontrollerissa ilman käyttöjärjestelmätukea.
  * Järjestelmä jakaantuu osiin seuraavasti: laitteisto¬abstraktiokerros, käyttöjärjestelmäkerros ja sovellusmoduulikerros.
  * Laitteistoabstraktiokerroksen tarkoituksena on piilottaa käytettävän piirikortin ominaisuudet, jotta toteutusalusta on myöhemmin tarvittaessa vaihdettavissa.
  * Käyttöjärjestelmä toteuttaa sovellusmoduulikerroksen prosessien skeduloinnin ja keskeytyskäsittelyn ohjauksen sovellusmoduulikerrokselle.
  * Sovellusmoduulikerroksen moduulit ovat joko passiivisia (kirjastoja) tai aktiivisia (prosesseja). Molempien tyyppien koodirungoista on esimerkki liitteessä x.
  * Kutakin ulkoista keskeytyslähdettä kohti määritellään ko. keskeytyksen käsittelevä aktiivinen sovellusmoduuli.
Esimerkiksi luokka ja tapahtumasekvenssikaavioita voi käyttää kuvauksen selkeyttämiseksi.

### 3.2	 	Ohjelmistoarkkitehtuuri, moduulit ja prosessit

>Tässä kohdassa esitetään yksityiskohtaisesti ohjelmiston jako osajärjestelmiin, ohjelmiin, prosesseihin, moduuleihin, pakkauksiin ja/tai luokkiin. Lisäksi kuvataan moduulinen välistä kommunikointia esimerkiksi tapahtumasekvenssikaavioiden avulla.
Moduuleista erotellaan "valmisosat", eli muualta sellaisenaan tai muokaten napatut osat. Nämä seikat voi kuvata esim. moduulikaaviossa erilaisilla korostuskeinoilla.  
Tässä voidaan myös esittää nimeämiskäytäntöjä, viittauksia tyylioppaisiin yms. kaikkien moduulien toteutukseen liittyviä asioita.

## Suoritysympäristön (tuotanto) kuvaus

  * Miten tuote ajetaan tuotannossa 
  * Sijoittelunäkymä (Depoyment diagram)

```plantuml
@startuml
actor User
node "Client_Host" as WIN10{
node "Browser"{
}
}

cloud "Network" as net{
queue "https"{
}
}

node "Uno Server / Ubuntu 20.04" as AWS{ 
node "Frontend_Container"{ 
}
node "Backend_Container" {
}
database "MariaDB_Container" {
}
node "Logger_Container" {
}

}
User  Browser
Browser  https
https  Frontend_Container
Frontend_Container  Backend_Container
Backend_Container  MariaDB_Container
Logger_Container  Frontend_Container
Logger_Container  Backend_Container
Logger_Container  MariaDB_Container

@enduml
```




### 3.3		Tietokantaarkkitehtuuri

>Tässä kohdassa kuvataan tiedostot ja tietokannat, mm. jako tiedostoihin ja/tai tietokantoihin, tiedostojen ja tietokantojen väliset liittymät, tiedostojen ja tietokantojen organisointi, käytettävät tietokantaohjelmistot (jos on), suojaukset, toipuminen, varmistukset, huolto, ylläpito. 
Tiedostoista ja tietokannoista esitetään rakenne (esim. taulut eli relaatiokuvaukset, mikäli toteutus tehdään relaatiotietokannalla). Suunnitteludokumentissa määrittelydokumentin tietosisältökuvaukset muunnetaan fyysisen tietokannan kuvauksiksi. Esimerkiksi relaatio¬tieto¬kantaa käytettäessä määrittelydokumentin tietosisältökuvauksessa mahdollisesti olevat periytymissuhteet ja montamoneen –yhteydet puretaan. Lisäksi määritellään navigointia varten tarvittavat indeksit. Kuvauksen perusteella pitäisi pystyä kirjoittamaan tietokantaa luotaessa tarvittavat SQLkielen create table ja create index lauseet. Tietokantaratkaisusta ja tiedostoista kuvataan:

  * ratkaisun yleiskuva, tietokannat, tiedostot ja niiden väliset liittymät
  * tietokantaa käyttävät muut ohjelmistot tai järjestelmät
  * tietokannan tukiohjelmisto (esim. varmistukset, toipuminen, testaus)
  * tietokannoista ja tiedostoista
  * tietokannan rakenne (luokkakaavio selityksineen)
  * tiedoston tietueiden kenttien ja tietokannan taulujen sarakkeiden kuvaukset:
  * kentän nimi tai tunniste
  * kentän merkitys
  * kentän pituus ja muoto
  * sallitut arvot tyyppi
  * käsittely tai laskentasäännöt
  * suhteet muihin tietoihin
  * päivityskriteerit ja tavat
  * tilavaatimukset
  * ylläpitonäkökohdat
  * varmistusnäkökohdat
  * suojausnäkökohdat.
	
### 3.4	Virhe ja poikkeusmenettelyt

>Virhe ja poikkeusmenettelyt yleisellä (arkkitehtuuri) tasolla. Luvussa 4 kuvataan tarkemmin moduulitasolla. 
Virheilmoitusten tekstit tulee kiinnittää viimeistään suunnittelussa (olisi parempi miettiä ne jo määrittelyvaiheessa). Virheenkäsittelystä otetaan huomioon seuraavanlaisia asioita:

  * yleiset virhekäsittelysäännöt
  * yleiset moduulit virheiden käsittelemiseksi
  * virheilmoitusten tunnistaminen
  * virheilmoitusten tallettaminen (muistiin, levylle)
  * virheilmoitusten ryhmittely (vakavuus, käyttäjän vai järjestelmän)
  * virheilmoitustekstit.

Toiminta epänormaaleissa tilanteissa kuuluu määrittelydokumenttiin, mutta viimeistään suunnittelussa on asiaan otettava kantaa. Esimerkiksi miten järjestelmä käyttäytyy virtakatkoksissa: "nouseeko itse pystyyn" vai "jääkö jumiin".

### 3.5 Tuotekehitysympäristön kuvaus

>Kuvaa ainakin seuraavat:

* Kehitysympäristö
* Testiympäristö
* Ajo/suoritusympäristö
* Demoympäristö

>Eli miten nuo eri ympäristöt on toteutettu ko. projektissa

## Käytetyt työvälineet ja niiden versionumerot

* Kääntäjä xyz v1.0.1
* debuggeri zky v2.05
* Firefox 123

## 4.		MODUULI /LUOKKA/PROSESSIKUVAUKSET

>Tämän luvun lukurakenne suunnitellaan ohjelman arkkitehtuurin mukaiseksi: Jos yksitasoinen jaottelu riittää, käytetään tässä esitettyä tapaa (4.1 Moduuli X, 4.2 Moduuli Y…). Jos ohjelma jakaantuu esimerkiksi pakkauksiin, joiden sisällä on useita luokkia, kannattaa kullekin pakkaukselle tehdä oma kohtansa, jonka alakohdissa kukin luokka kuvataan. Pakkauksen kaikille luokille yhteiset asiat kuvataan luvun alussa, ja jos pakkauksella on rajapinta, myös se kuvataan tässä. Laajoissa hankkeissa kunkin pakkauksen tai osajärjestelmän sisäisestä rakenteesta kirjoitetaan erillinen suunnitteludokumentti.
Jokaisesta moduulista kuvataan sen tehtävä, liittymät muihin osiin, rajapinta sekä toteutusnäkökohdat. Tekniset yksityiskohdat täytyy selittää niin tarkasti, että kuvauksen perusteella pystytään suorittamaan moduulin testaus mustalaatikkotestauksena.

### 4.1		Moduuli X (kustakin moduulista oma alakohtansa 4.i)

### 4.1.1		Yleiskuvaus 

>Moduulin nimi:
Moduulin tyyppi: (luokka, funktio, prosessi, pakkaus, alijärjestelmä, kirjasto)
Yleiskuvaus: Lyhyt kuvaus moduulista – miksi se on olemassa, mitä se tekee.
Asiakkaat: mitkä/minkä tyyppiset osat järjestelmästä tarvitsevat tämän osan palveluita (yleiskäyttöisen komponentin tapauksessa tämä kohta puuttuu).
Riippuvuudet ja liittymät muihin moduuleihin: Kuvataan lyhyesti, miten moduuli käyttää hyväkseen muita moduuleita ja palveluita ympäristössään (voi usein yhdistää yleiskuvaukseen).

### 4.1.2		Rajapinta yleisesti

>Kuvataan yleisesti moduulin tarjoamat palvelut ja rajapintafunktioiden yhteiset ominaisuudet (esimerkiksi virhetilanteiden käsittely). Joissain tapauksissa kannattaa antaa esimerkkejä moduulin käytöstä kuvaamalla asiakkaan ja moduulin välinen kommunikointi esimerkiksi tapahtumasekvenssikaaviona. Tässä mainitaan myös rajapinnasta mahdollisesti ulos näkyvät vakiot yms. määrittelyt, mahdolliset kapasiteettirajoitukset ja niiden muuttaminen, moduulin tallettamat tilatiedot jne.

### 4.1.3	 	Rajapintafunktiot

>Tässä kuvataan erikseen omassa alakohdassaan jokainen rajapintafunktio:

  * Funktion nimi
  * Funktion parametrit ja paluuarvo
  * Toiminta: mitä funktio tekee
  * Esiehdot: kuvataan, mikä ohjelman tilan pitää olla ennen funktion kutsua.
  * Jälkiehdot: kuvataan, mikä ohjelman tila on funktion kutsun jälkeen (mm. sivuvaikutukset).
  * Virhetilanteet: poikkeukset ja muut virhetilanteet, toiminta kun esiehdot eivät kutsuttaessa pidä paikkaansa

### 4.1.4	 	Moduulin toteutus

Tarvittaessa voidaan antaa ohjeita toteutusta varten, esimerkiksi:
  * Ajatuksia moduulin sisäisten tietorakenteiden toteutuksesta.
  * Ajatuksia käytettävistä algoritmeista. 
  * Tiedossa olevat mahdollisesti uudelleenkäytettävät komponentit.
  * Mikäli moduuli on monimutkainen, voidaan käyttää pseudokoodia, aktiviteettikaavioita yms. Tarvittaessa voidaan tehdä erillinen moduulisuunnitteludokumentti.

### 4.1.5	 	Virhekäsittely

>Kuvataan virheiden ja poikkeusten käsittely moduulitasolla.

## 5.		VALMISOSAT JA ERITYISET TEKNISET RATKAISUT

>Mikäli on valmisosia eli ulkopuolisia komponentteja, niin sellaisista selostetaan:

  * mistä ne saadaan 
  * mihin ne sijoitetaan 
  * käyttö 
  * muuta olennaista (jotta joku toinen osaisi koota sovelluksen tai lisätä ne mukaan). 

>Mikäli jotkin asiat poikkeavat projektin tavanomaisista työtavoista. "Alan tavanomaisista käytännöistä poikkeavat ratkaisut", joita alan työntekijä ei ehkä heti arvaisi. 
>Esimerkiksi seuraavia asioita, mikäli tarpeellista:
  * suojaukset, turvallisuus
  * varmistukset
  * toipumiset
  * ylläpidettävyys
  * joustavuus
  * siirrettävyys tai kannettavuus.

>Varsinkin jos on jokin erityinen tai poikkeava tapa tehdä jotakin. 
Myös toteutusvälineet voidaan mainita tässä, mikäli se on todellakin oleellista kertoa jo tässä (suunnittelu) vaiheessa (harvinaista eikä suositeltavaa, esimerkiksi Bkääntäjän versio 2.77 joka tukee Dkirjastoa 4.56). Projektisuunnitelmassahan on tarkat tiedot toteutusvälineistä. 
Esimerkiksi pystyykö ohjelma toipumaan automaattisesti sähkökatkoista tai käyttöjärjestelmän "kaatumisista"?

	
## 6.	HYLÄTYT RATKAISUVAIHTOEHDOT

>Mietityt, mutta hylätyt, ratkaisuvaihtoehdot kannattaa kirjata perusteluineen johonkin sopivaan lukuun tai kohtaan päivämäärineen. Siten seuraava dokumentin lukija näkee, että tuotakin asiaa on mietitty. Samoin jos itse lukee suunnitteludokumenttia puolen vuoden päästä, voi olla vaikea muistaa, mitä asioita on mietitty järjestelmää tehtäessä. Projektin lopussa hylätyt ratkaisuvaihtoehdot kerätään projektisuunnitelman loppuun.

## 7.	JATKOKEHITYSAJATUKSIA

>Kerätään matkan varrella mieleen tulleita hyödyllisiä ajatuksia, joita ei tämän projektin puitteissa kuitenkaan suunnitella tarkemmin tai toteuteta; esimerkiksi ajan puutteen, rahan puutteen, resurssien puutteen tai taitojen ja osaamisen takia.
Jatkokehitysajatukset kannattaa esimerkiksi numeroida, jotta niihin viittaaminen olisi helpompaa myöhemmin. Päiväys ja ehdottajan nimi(kirjaimet) auttavat jälkitarkastelussa, varsinkin jos lähde on projektin ulkopuolinen, jos vuoden kuluttua projekti saa yllättäen rahoitusta jatkokehitystä varten.
Projektin lopussa tämä luku kerätään projektisuunnitelman loppuun. Jatkokehitysajatukset voi esittää myös omana liitteenään, joka voi tarvittaessa kulkea muidenkin projektin dokumenttien liitteenä. 

## 8.	VIELÄ AVOIMET ASIAT

>Luku on epävirallinen ja sitä ei pitäisi olla enää projektin lopussa. Tähän voidaan merkitä dokumentin elinkaaren aikana avoinna olevia eli ratkaisua vaativia asioita, jotta ne muistettaisiin selvittää ennen dokumentin lopullista valmistumista.






  
