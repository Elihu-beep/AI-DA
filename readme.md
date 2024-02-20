# AI/DA
Projektin tavoitteena oli toteuttaa autokauppaketjulle koneoppimismalli, jota voi hyödyntää käytettyjen autojen hinnan ennustamisessa auton ominaisuuksien perusteella. Toteutus tapahtui Python-ohjelmointikielellä, sekä muun muassa Pythonin datan käsittely-, matikka-, ja koneoppimiskirjastoilla.

Liiketoimintaan sekä datasettiin perehtyminen olivat projektin ensiaskeleet. Projektin datasetti koostui kolmesta miljoonasta autosta Yhdysvaltojen markkinoilta. Data tuli muotoilla niin, että sitä pystyi käyttää mallintamisessa. Datan suuren koon vuoksi esikäsittely vei merkittävästi aikaa.

Mallinnuksessa päädyttiin käyttämään KNeighbor-regressori-mallia. Tähän tulokseen saavuttiin vertailemalla useita eri malleja keskenään. Projektin käyttöönotto toteutettiin Pythonin Streamlit-kirjastolla. Mallista kehitettiin toimiva prototyyppi käyttöliittymineen, joka pyörii lokaalisti. Streamlit-kirjasto ei anna vaikuttaa käyttöliittymän ulkonäköön merkittävästi. Nykyisessä muodossaan projektista olisi kuitenkin suhteellisen helppoa jalostaa lopullisempi sovellus.

Kaiken kaikkiaan projektista voidaan todeta, että haasteista huolimatta olemme tyytyväisiä projektin lopputulokseen. Saimme toimivan prototyypin valmiiksi. Projekti toimi hyvänä oppimiskokemuksena ja avarsi näkemystämme siitä, miten AI/DA-projekti voidaan toteuttaa käytännössä.

![GIF](./Gifs/gif.gif)