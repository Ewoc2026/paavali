# PAAVALI — ChatGPT handoff

Tämän tiedoston tarkoitus on mahdollistaa PAAVALI-projektin jatkaminen uudella ChatGPT-tilillä ilman riippuvuutta vanhan tilin keskusteluhistoriasta, muistista tai projektikohtaisesta kontekstista.

## 1. Kanoninen projektitila

Kanoninen repo:

`Ewoc2026/paavali`

GitHub-repo on projektin ensisijainen pysyvä työmuisti.

Keskustelu:
- on työskentelytila,
- ei korvaa repoa,
- ei ole oletusarvoisesti kanoninen lähde projektin nykytilalle.

Ennen merkittävää tutkimustyötä tarkista aina repon ajantasainen `main`.

## 2. Lue nämä ennen tutkimuksen jatkamista

Lue vähintään seuraavat tiedostot tässä järjestyksessä:

1. `README.md`
2. `PAAVALI_METODI.md`
3. `PAAVALI_TEKSTIKARTTA.md`
4. `PAAVALI_HYPOTEESIT.md`
5. `PAAVALI_LAHTEET.md`
6. `PAAVALI_IDEAT.md`
7. `TUTKIJAPANEELI.md`
8. `PAAVALI_AI_KOKEET.md`
9. `PUBLIC_REPO_POLICY.md`

Kun `SOURCE_MANIFEST.md` on repossa, lue myös se ennen lähdeteksteihin perustuvaa työtä.

Älä rekonstruoi projektin tutkimustilaa vanhoista ChatGPT-keskusteluista, jos sama asia on jo kirjattu repoon.

## 3. Tutkimuksen perussäännöt

Pidä aina erillään:

- **tekstihavainto** — suoraan tekstistä osoitettavissa oleva asia
- **tulkinta** — selitys sille, mitä havaittu rakenne todennäköisesti merkitsee
- **hypoteesi** — laajempi selitysmalli, joka vaatii testaamista
- **spekulaatio** — mahdollinen mutta heikosti osoitettavissa oleva rekonstruktio

Testaa vahvistuvaa hypoteesia myös:
- sitä tukevaa aineistoa vasten,
- sitä vaikeuttavaa aineistoa vasten,
- vaihtoehtoista selitystä vasten.

Vasta-aineistoa ei harmonisoida pois ennen käsittelyä.

Käytä alkukieliä silloin, kun sanasto, syntaksi, tekstivariantti tai intertekstuaalinen yhteys ratkaisee asian.

Älä:
- harmonisoi Jeesusta ja Paavalia etukäteen,
- oleta ristiriitaa etukäteen,
- kohtele Room. 7:n `minää` automaattisesti Paavalin psykologisena päiväkirjana,
- päättele suorasta kirjallisesta riippuvuudesta pelkän rakenteellisen analogian perusteella.

## 4. Mitä GitHubiin palautetaan

Kun keskustelussa syntyy säilyttämisen arvoista uutta tutkimustietoa, päivitä relevantti repo-tiedosto.

Pysyvästi säilytettäviä ovat erityisesti:
- uusi tekstihavainto,
- hypoteesin vahvuuden perusteltu muutos,
- merkittävä vasta-aineisto,
- avoimeksi jäänyt tutkimuskysymys,
- menetelmällinen päätös,
- tutkimuksen kannalta arvokas jatkoidea.

Älä tee commit-kohinaa pelkästä:
- keskustelun välivaiheesta,
- paremmasta sanamuodosta,
- julkaisun retorisesta hiomisesta,
- ohimenevästä ideasta, joka ei muuta tutkimustilaa.

## 5. Julkisen repon turvallisuus

Repo on julkinen. Commit on käytännössä julkaisemista.

Älä commitoi automaattisesti:
- kokonaisia lähdetekstikorpuksia ilman lisenssin tarkistamista,
- tekijänoikeuden alaista kirjallisuutta tai pitkiä lainauksia,
- henkilökohtaisia tai arkaluonteisia tietoja,
- API-avaimia, tokeneita, salasanoja tai muuta salaista aineistoa,
- aineistoa, jonka julkaisukelpoisuus on epäselvä.

Projektin oma alkuperäinen ei-ohjelmistollinen sisältö on lähtökohtaisesti CC BY 4.0 -lisensoitua repon ehtojen mukaisesti. Kolmansien osapuolten aineisto säilyttää omat oikeutensa.

## 6. Vanhan ChatGPT-tilin asema

Vanhan ChatGPT-tilin keskustelut eivät ole projektin pysyvä tietokanta.

Tilinvaihdon tavoite on, että projektin tutkimuksellinen tila voidaan rekonstruoida:
1. GitHub-reposta,
2. erikseen säilytetyistä ja manifestoiduista lähdetiedostoista,
3. ilman vanhan ChatGPT-tilin muistia.

Jos vanhasta keskusteluarkistosta myöhemmin löytyy väite, joka ei ole repossa:
- älä pidä sitä automaattisesti kanonisena,
- tarkista sen aineistopohja,
- luokittele se metodin mukaisesti,
- siirrä vain säilyttämisen arvoinen tulos repoon.

## 7. Suositeltu Project Instructions -teksti uudelle ChatGPT-projektille

```text
PAAVALI on avoin eksegeettinen tutkimusprojekti. GitHub-repo Ewoc2026/paavali on projektin ensisijainen pysyvä työmuisti.

Lue CHATGPT_HANDOFF.md ja siinä määrätyt repo-tiedostot ennen merkittävää tutkimustyötä. Tarkista aina ajantasainen main-haara.

Erottele aina tekstihavainto, tulkinta, hypoteesi ja spekulaatio. Testaa hypoteeseja myös vasta-aineistolla ja vaihtoehtoisilla selityksillä. Käytä alkukieliä silloin, kun sanasto, syntaksi, tekstivariantti tai intertekstuaalinen yhteys ratkaisee asian.

Älä harmonisoi Jeesusta ja Paavalia etukäteen äläkä oleta ristiriitaa etukäteen.

Säilyttämisen arvoiset uudet tekstihavainnot, hypoteesimuutokset, vasta-aineisto, avoimet tutkimuskysymykset ja menetelmälliset päätökset päivitetään relevantteihin repo-tiedostoihin. Keskustelu ei korvaa GitHubia.

Repo on julkinen. Noudata PUBLIC_REPO_POLICY.md-tiedostoa ennen commitointia.
```

## 8. Ensimmäinen viesti uudella tilillä

Suositeltu ensimmäinen viesti:

```text
Lue ensin Ewoc2026/paavali-repon CHATGPT_HANDOFF.md ja noudata sitä. Älä aloita tutkimuksen jatkamista ennen kuin olet lukenut siinä määrätyt tiedostot ja tarkistanut nykyisen main-haaran. Kerro sen jälkeen tiiviisti, mikä on projektin nykyinen tutkimustila ja mitkä kysymykset ovat vielä avoinna.
```

## 9. Siirron hyväksymiskriteeri

Tilinvaihto on tutkimuksen kannalta onnistunut vasta, kun uusi ChatGPT-tili pystyy ilman vanhan tilin muistia:
- tunnistamaan projektin pääkysymyksen,
- nimeämään aktiiviset tutkimushaarat,
- erottamaan vahvat ja heikot työhypoteesit,
- nimeämään keskeisen vasta-aineiston,
- käyttämään oikeita lähdetiedostoja,
- jatkamaan tutkimusta metodin mukaisesti,
- palauttamaan uuden kestävän tutkimustiedon GitHubiin.
