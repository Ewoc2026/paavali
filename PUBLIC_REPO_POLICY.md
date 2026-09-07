# PAAVALI — public repo policy

Repo on julkinen. Siksi kaikkea commitoitavaa käsitellään lähtökohtaisesti julkaistuna aineistona.

## Saa commitoida normaalisti

- projektin omat tutkimusmuistiinpanot
- tekstihavainnot, tulkinnat ja hypoteesit, kun niiden status on merkitty selvästi
- vasta-aineisto ja hylätyt/korjatut hypoteesit
- tutkijapaneelin rakenne ja julkisiin lähteisiin perustuvat tutkijaprofiilit
- AI-kokeiden menetelmät, promptit ja tulokset, kun ne eivät sisällä salassa pidettävää aineistoa
- linkit ja bibliografiset tiedot

## Älä commitoi automaattisesti

- kokonaisia raamatuntekstikorpuksia tai muita lähdetekstejä ennen lisenssin ja attribuutiovaatimusten tarkistamista
- tekijänoikeuden alaista kirjallisuutta tai pitkiä lainauksia
- henkilökohtaisia tai arkaluonteisia tietoja
- API-avaimia, tokeneita, salasanoja, .env-tiedostoja tai muita tunnisteita
- aineistoa, jonka julkisuudesta on epäselvyyttä

## Julkisen Git-historian sääntö

Commitia pidetään käytännössä julkaisemisena. Myöhempi tiedoston poistaminen ei takaa, että aineisto katoaa historiasta, forkeista tai välimuisteista.

Jos julkaisukelpoisuus on epäselvä, aineistoa käytetään tutkimuksessa ilman commitointia, kunnes asia on tarkistettu.

## Tutkimuksellinen läpinäkyvyys

Keskeneräisyys ei ole ongelma, jos se merkitään oikein. Repo saa sisältää vahvojakin hypoteeseja, mutta tekstihavainto, tulkinta, hypoteesi ja spekulaatio pidetään erillään. Merkittävä vasta-aineisto säilytetään näkyvissä.

## Lisenssit

Projektin oma alkuperäinen tutkimusteksti ja muu alkuperäinen ei-ohjelmistollinen sisältö julkaistaan **Creative Commons Attribution 4.0 International (CC BY 4.0)** -lisenssillä, ellei yksittäisen aineiston yhteydessä toisin ilmoiteta.

CC BY 4.0 sallii jakamisen ja muokkaamisen myös kaupallisiin tarkoituksiin, kun lisenssin nimeämis- ja muut ehdot täyttyvät.

Lisenssi ei automaattisesti ulotu kolmansien osapuolten lähdeteksteihin, raamatunlaitoksiin, dataan, lainauksiin, kuviin tai muuhun aineistoon, joilla voi olla omat lisenssi-, tekijänoikeus- ja attribuutioehtonsa.

Mahdollinen ohjelmakoodi lisensoidaan tarvittaessa erikseen eikä sitä pidetä automaattisesti CC BY 4.0 -lisensoituna.

Katso repon `LICENSE`-tiedosto.
