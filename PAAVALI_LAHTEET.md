# PAAVALI — lähteet ja tekstiaineiston suunnitelma

## Periaate

Projektin alkuun ei tarvitse tuoda `kaikkea mahdollista raamattutavaraa`.

Ensimmäinen tavoite on:
1. vakaa raamatuntekstin vertailupohja,
2. alkukielet,
3. tekstien käyttöoikeuksien selkeys,
4. mahdollisimman vähän tarpeetonta lähdekohinaa.

Tästä syystä koko modernia kommentaarikirjastoa tai kymmeniä käännöksiä ei lisätä alkuvaiheessa.

---

## Suositeltu ensimmäinen tekstikerros

### 1. Suomi: FinPR — Pyhä Raamattu 1933/1938
CrossWire-moduuli: `FinPR`

Käyttö:
- nopea suomalainen työteksti
- vanhempi mutta tutkimuskäytössä selkeä vertailuteksti

CrossWire ilmoittaa moduulin **Public Domain** -aineistoksi.

Huomio:
Nykyisiä suomalaisia käännöksiä voidaan käyttää vertailuun erikseen, mutta niitä ei oleteta vapaasti uudelleenjaettaviksi tai projektin pysyväksi avoimeksi korpukseksi ilman käyttöehtojen tarkistamista.

---

### 2. Kreikan UT: Nestle 1904
CrossWire-moduuli: `Nestle1904`

Käyttö:
- avoin kreikankielinen peruskorpus
- sanasto- ja syntaksihakujen projektipohja

CrossWire ilmoittaa moduulin **Public Domain** -aineistoksi.

Rajoitus:
Nestle 1904 ei ole sama asia kuin NA28/SBLGNT eikä korvaa nykyistä tekstikritiikkiä. Merkittävät variantit tarkistetaan tarvittaessa uudemmista kriittisistä editioista.

---

### 3. Heprea: Open Scriptures Hebrew Bible
CrossWire-moduuli: `OSHB`

Käyttö:
- Habakuk ja muu heprealainen VT
- Strong-/morfologiatiedot tarpeen mukaan

CrossWire ilmoittaa lisenssiksi **CC BY 4.0**.

---

## Toisen kerroksen hyödylliset lähteet

### SBLGNT
CrossWire-moduuli: `SBLGNT`

Hyödyllinen nykyisempi kriittinen kreikan teksti.
CrossWire ilmoittaa sen olevan tekijänoikeuden alainen mutta vapaasti ei-kaupalliseen levitykseen saatettu.

Älä oleta tästä yleistä `public domain` -vapautta.

### MorphGNT
CrossWire-moduuli: `MorphGNT`

Hyödyllinen morfologisesti analysoitu SBLGNT-pohjainen aineisto.
Morfologinen data ja itse kreikankielinen pohjateksti eivät välttämättä ole saman lisenssin alaisia; tarkista attribuutio- ja jakeluehdot ennen aineiston uudelleenjulkaisua.

### Septuaginta
CrossWire-moduuli: `LXX`

Hyödyllinen erityisesti Hab. 2:4:n ja Paavalin lainaustavan tutkimiseen.
CrossWire ilmoittaa moduulin lisenssiksi **Copyrighted; Free non-commercial distribution**.

Siksi LXX-moduulia kannattaa käyttää tutkimustyökaluna, mutta sitä ei pidä käsitellä automaattisesti täysin vapaana uudelleenjulkaisukorpuksena.

---

## Mitä en vielä lisäisi projektin lähteisiin

- kymmeniä englanninkielisiä käännöksiä
- kokonaisia kommentaarisarjoja
- systemaattisen teologian kirjoja
- valmiiksi valikoituja `Paavali vs. Jeesus` -puolustus- tai ristiriitakirjoituksia

Syy:
ne voivat alkaa ohjata kysymyksenasettelua ennen kuin oma tekstikartta on vakaa.

---

## Ensimmäinen käytännöllinen projektikorpus

Jos PAAVALI-projektiin halutaan tiedostopohjainen tekstikorpus, hyvä ensimmäinen yhdistelmä on:

1. `FinPR` — suomi
2. `Nestle1904` — kreikan UT
3. `OSHB` — heprealainen VT
4. `LXX` — tarvittaessa Habakukia varten, käyttöehtojen mukaisesti

Näiden päälle voidaan käyttää tutkimuksessa verkkolähteitä ja nykyisiä kriittisiä editioita tapauskohtaisesti.

---

## CrossWire ei tarkoita automaattisesti `vapaata tekstiä`

CrossWire/SWORD on ennen kaikkea jakelujärjestelmä ja moduuliekosysteemi.

Jokaisen moduulin:
- `About`
- `DistributionLicense`
- `Copyright`

on tarkistettava erikseen.

CrossWire itse korostaa, että sen ohjelmisto on GPL-lisensoitu, mutta tekstimoduuleilla on erilaiset tekijänoikeudet ja jakeluehdot.

---

## Linkit

CrossWire SWORD modules:
https://www.crosswire.org/sword/modules/

CrossWire copyright policy:
https://wiki.crosswire.org/Copyright

FinPR:
https://www.crosswire.org/sword/modules/ModInfo.jsp?modName=FinPR

Nestle1904 copyright information:
https://www.crosswire.org/sword/copyright/ModInfoCopyright.jsp?modName=Nestle1904

OSHB:
https://crosswire.org/sword/modules/ModInfo.jsp?modName=OSHB

SBLGNT:
https://www.crosswire.org/sword/modules/ModInfo.jsp?modName=SBLGNT

MorphGNT:
https://www.crosswire.org/sword/modules/ModInfo.jsp?modName=MorphGNT

LXX:
https://crosswire.org/sword/modules/ModInfo.jsp?modName=LXX
