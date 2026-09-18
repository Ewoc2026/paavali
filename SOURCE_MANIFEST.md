# PAAVALI — source manifest

Tämä tiedosto yksilöi PAAVALI-projektin nykyiset paikalliset lähdetiedostot niin, että sama tutkimusympäristö voidaan siirtää toiselle ChatGPT-tilille ilman riippuvuutta vanhan tilin tiedostokontekstista.

Manifesti ei tee lähdeteksteistä GitHub-repon osaa. Repo on julkinen, ja varsinaiset lähdetiedostot säilytetään erillään, ellei niiden julkaisemista ja lisenssiehtoja myöhemmin arvioida erikseen.

## Yleinen siirtosääntö

Uudelle ChatGPT-tilille siirrettäessä:

1. säilytä näistä tiedostoista täsmälliset kopiot ChatGPT:n ulkopuolella,
2. lataa ne uuden PAAVALI-projektin lähdetiedostoiksi,
3. tarkista tiedoston SHA-256 tätä manifestia vasten,
4. jos tarkistussumma poikkeaa, käsittele tiedostoa uutena versiona ja selvitä ero ennen tutkimuksen jatkamista.

Paikallisiin lähdetiedostoihin ei niiden syntyvaiheessa tallennettu upstream-repositorion commit-SHA:ta. Siksi sitä ei rekonstruoida jälkikäteen arvauksella. Tässä manifestissa SHA-256 yksilöi täsmälleen projektissa nyt käytetyn paikallisen tiedoston.

---

## 1. `SRC_N1904_CORE.txt`

**Sisältö:** valikoitu kreikankielinen Uuden testamentin ydinkorpus PAAVALI-tutkimukseen.

**Mukana olevat kirjat:**
- Matteus
- Roomalaiskirje
- 1. Korinttilaiskirje
- 2. Korinttilaiskirje
- Galatalaiskirje
- Filippiläiskirje

**Editio/data:** HELFI extended Nestle 1904 Greek New Testament.

**Lähderepo:**  
https://github.com/amikael/HELFI

**Paikallisen tiedoston koko:** 2 811 607 tavua

**SHA-256:**  
`de94b617791f7f19772e46be46975926f4cd5737941c15b74d6645e140abe033`

### Provenienssi ja lisenssi

HELFI:n lisenssitiedoston mukaan:
- laajennettu Nestle 1904 -kreikankielinen Uusi testamentti on public domain,
- kreikan lemmat ja morfologia ovat public domain,
- HELFI:n erillinen cross-lingual alignment -data on CC BY 4.0.

Tämä paikallinen tiedosto sisältää HELFI:n sarakeaineistoa eikä manifestissa oleteta ilman erillistä kenttäkohtaista tarkistusta, että jokainen metatietokenttä olisi saman oikeusaseman piirissä.

**Lisenssilähde:**  
https://github.com/amikael/HELFI/blob/master/LICENSES.md

### Repo-status

Ei tällä hetkellä versionhallinnassa PAAVALI-repossa.

**Siirtosuositus:** säilytä täsmällinen tiedosto erillisenä ja lataa uuden ChatGPT-projektin lähteeksi. Älä commitoi julkiseen repoon vain siirron vuoksi.

---

## 2. `SRC_FINPR_CORE.txt`

**Sisältö:** PAAVALI-tutkimukseen valikoitu suomalainen vertailukorpus.

**Mukana olevat kirjat:**
- Habakuk
- Matteus
- Roomalaiskirje
- 1. Korinttilaiskirje
- 2. Korinttilaiskirje
- Galatalaiskirje
- Filippiläiskirje

**Editio/data:** Finnish Bible 1933/1938, FABC 2020.3 Text Edition / HELFI.

**Lähderepo:**  
https://github.com/amikael/HELFI

**Paikallisen tiedoston koko:** 432 494 tavua

**SHA-256:**  
`d7b3ed1aa3a8630ea4b45e258fb4a75dd18601de0b46cbd6c0200fa0a5bbb9cd`

### Provenienssi ja lisenssi

HELFI:n lisenssitiedoston mukaan:
- Suomen 1933/1938-raamatunkäännös on public domain,
- FABC 2020.3 Text Edition on public domain,
- FABC-edition kuvausdokumentilla ja erillisillä lemma-/morfologia-aineistoilla on omat lisenssinsä.

Tämä paikallinen CORE-tiedosto on tekstikorpus, ei oletusarvoisesti koko HELFI:n morfologia- tai alignment-aineiston kopio.

**Lisenssilähde:**  
https://github.com/amikael/HELFI/blob/master/LICENSES.md

### Repo-status

Ei tällä hetkellä versionhallinnassa PAAVALI-repossa.

**Siirtosuositus:** säilytä täsmällinen tiedosto erillisenä ja lataa uuden ChatGPT-projektin lähteeksi. Julkiseen repoon lisääminen ei ole siirron kannalta tarpeen.

---

## 3. `SRC_HEB1008_HAB.txt`

**Sisältö:** Habakukin kirja hepreaksi, mukana HELFI/OSHB-pohjainen lemma- ja morfologinen data sekä translitterointi.

**Kattavuus:** Hab. 1:1–3:19.

**Editio/data:** HELFI Hebrew1008, based on Leningrad Codex / Open Scriptures Hebrew Bible.

**Lähderepo:**  
https://github.com/amikael/HELFI

**Paikallisen tiedoston koko:** 48 622 tavua

**SHA-256:**  
`c8b895f29a02a3a5aa452190d3ae197e141f0489baa5b58b4a2c2bc915888983`

### Provenienssi ja lisenssi

HELFI:n lisenssitiedoston mukaan:
- Leningradin koodeksin hepreankielinen teksti HELFI-jakelussa on public domain,
- Open Scriptures Hebrew Bible -projektin heprean lemmat ja morfologia ovat CC BY 4.0,
- HELFI antaa oman huomautuksensa translitteraation keskeneräisyydestä ja käytöstä käyttäjän vastuulla.

**Attribuutio lemma- ja morfologia-aineistolle:** Open Scriptures Hebrew Bible Project.

**Lisenssilähde:**  
https://github.com/amikael/HELFI/blob/master/LICENSES.md

### Repo-status

Ei tällä hetkellä versionhallinnassa PAAVALI-repossa.

**Siirtosuositus:** säilytä täsmällinen tiedosto erillisenä ja lataa uuden ChatGPT-projektin lähteeksi. Jos tiedostoa joskus julkaistaan repossa, säilytä OSHB-attribuutio ja tarkista silloin kaikki mukana olevat sarakkeet ja niiden ehdot.

---

## 4. `SRC_LXX_SWETE_HAB.txt`

**Sisältö:** Habakukin kirja kreikankielisenä Septuagintana.

**Kattavuus:** Hab. 1:1–3:19.

**Editio:** Henry Barclay Swete, *The Old Testament in Greek According to the Septuagint*.

**Lähderepo:**  
https://github.com/nathans/lxx-swete

**Tärkeä rajaus:** tämä on Sweten teksti, ei Rahlfsin eikä Göttingenin editio.

**Paikallisen tiedoston koko:** 21 737 tavua

**SHA-256:**  
`ed1b394ac3a4ffb8ba60fe786a57b9983f132975abefcacc77a7485dc4bcaf61`

### Provenienssi ja lisenssi

`nathans/lxx-swete` ilmoittaa README-tiedostossaan, että:
- data on johdettu Open Greek and Latin Projectin First1KGreek-aineistosta,
- `data`-hakemiston kreikankielinen teksti ja annotaatiot julkaistaan CC BY-SA 4.0 -lisenssillä,
- vain lähdekoodi on MIT-lisensoitu.

Siksi GitHub-repon yleinen MIT-merkintä ei saa johtaa siihen päätelmään, että itse kreikankielinen data olisi MIT-lisensoitu.

**Lisenssi- ja provenienssilähde:**  
https://github.com/nathans/lxx-swete/blob/master/README.md

### Repo-status

Ei tällä hetkellä versionhallinnassa PAAVALI-repossa.

**Siirtosuositus:** säilytä täsmällinen tiedosto erillisenä ja lataa uuden ChatGPT-projektin lähteeksi. Jos dataa myöhemmin julkaistaan tai muokataan repossa, CC BY-SA 4.0:n attribuutio- ja share-alike-ehdot on arvioitava kyseisessä käyttötavassa.

---

## Rekonstruktioperiaate

Näiden neljän tiedoston SHA-256-tarkistussummat määrittelevät PAAVALI-projektin nykyisen lähdetiedostotilan.

Jos täsmällinen paikallinen tiedosto katoaa:
- ensisijainen tavoite on palauttaa sama tiedosto ulkoisesta varmuuskopiosta,
- vasta toissijaisesti rakennetaan uusi tiedosto alkuperäisestä lähdereposta,
- uudelleenrakennettua tiedostoa ei pidetä automaattisesti samana versiona, ellei SHA-256 täsmää.

Upstream-repojen myöhempi muuttuminen ei itsessään muuta tämän manifestin kuvaamaa historiallista projektitilaa.

## Suhde muihin PAAVALI-tiedostoihin

- `PAAVALI_LAHTEET.md` kertoo projektin lähdeperiaatteet ja aineistolliset rajat.
- Tämä `SOURCE_MANIFEST.md` kertoo, mitkä konkreettiset paikalliset lähdetiedostot muodostavat nykyisen työaineiston.
- `CHATGPT_HANDOFF.md` määrää lukemaan tämän manifestin ennen lähdeteksteihin perustuvaa työtä uudella ChatGPT-tilillä.
