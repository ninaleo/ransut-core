# Ohjelmistoarkkitehtuuri

![](https://openclipart.org/image/400px/svg_to_png/290580/dogskeleton.png)

Tämä dokumentti on "elävä"-dokumentti, joka päivittyy jatkuvasti. Se on nykymuodossaan vain karkea runko, jota "voi" käyttää projektien teknisen dokumentoinnin pohjana. Rakennetta saa ja pitää muokata! Tavoitteena on luoda dokumentti, joka yhdistää suunnitteludokumentaation saumattomasti yhteen projektin muun dokumentaation kanssa. Tekijä ei ota mitään vastuuta dokumentin sisällöstä.

tv:NarsuMan

## Otsikko

Versionumero

Luokittelu (Salainen/Julkinen etc..)

Vastuuhenkilö





## Johdatus

* Johdatus dokumenttiin..




## Yleiskuvaus

* Esittele lyhyesti tuote tai kohde
* Dokumentin tehtävä on avata esim. jatkokehittäjälle käsitys siitä miten tuote on toteutettu (Pelkkä lähdekoodi ei riitä)
* Millaisia välineitä/työkaluja ja ympäristöjä tarvitaan, jos aioitaa kehitää tuotetta eteenpäin


## Käytetyt teknologiat

  * JAVA / Java Script ?
  * HABA kieli
  * Perustelut miksi! 

  
## Tuotekehitysympäristöjen kuvaukset

Kuvaa ainakin seuraavat:

* Kehitysympäristö
* Testausympäristö
* Ajo/suoritusympäristö
* Demoympäristö

Eli miten nuo eri ympäristöt on toteutettu ko. projektissa

## Käytetyt työvälineet ja niiden versionumerot

* Kääntäjä xyz v1.0.1
* debuggeri zky v2.05
* Firefox 123
* Perustelut miksi! 



## Tärkeimmät tekniset ratkaisut joihin tuote nojaa


  * Käytetyt kirjastot(library)/kehikot(Framework) (JQuery v 23456, JAVA EE 8 + Spring ZZZ, React IO)   
  * Muut jipot ja kikat
  * Perustelut miksi! 
  

## Yleinen ohjelmsto arkkitehtuuri

  * 
  * Palvelut
  

## Palvelujen/n rajapinnat (Interfaces)

  * [Esimerkki elävästä elämästä](https://virkailija.opintopolku.fi/koodisto-service/swagger/index.html)

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
User -- Browser
Browser -- https
https -- Frontend_Container
Frontend_Container -- Backend_Container
Backend_Container -- MariaDB_Container
Logger_Container -- Frontend_Container
Logger_Container -- Backend_Container
Logger_Container -- MariaDB_Container

@enduml
```


## Tietokantakuvaukset


ER-kaavio


## 






TBD
