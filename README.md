# Data-Science project of Global Warming
- The task was to do modelling and predictions based on global warming data. 


# Brief (in Finnish) 
- Below you can find a given brief. 

Ilmastonmuutos ja hiilidioksidipäästöt ovat ihmiskunnan suurimpia haasteita. Maailman populaation kasvaessa ja elintason noustessa myös päästöt lisääntyvät. IPCC:n julkaiseman raportin mukaan tarvitaan nopeita ja laaja-alaisia muutoksia. Hiilidioksidipäästöjä tulisi tiputtaa vuoteen 2030 mennessä noin 45 prosenttia vuoden 2010 tasosta. Vuoteen 2050 mennessä planeetan koko väestön hiilijalanjäljen tulisi olla neutraali ja pian tämän jälkeen selvästi negatiivinen.

Asiakas on tilannut meiltä sovelluksen, jonka avulla käyttäjät ymmärtävät paremmin ilmastonmuutosta. Tehtävänäsi on osana sovelluksen design-prosessia mallintaa hiilidioksidipäästöjä ja maapallon lämpenemistä.

Tuoteomistajan terveiset

Tuoteomistaja on lähettänyt projektitiimille (tässä tilanteessa sinulle) toiveita koskien sovelluksen sisältöjä ja ne on dokumentoitu alle kohdiksi 1–5. Sinua on pyydetty toteuttamaan kohdista 1–3 vähintään yksi sekä kohdat 4 ja 5 eli yhteensä kolme kohtaa. Halutessasi voit toteuttaa useammankin kohdan. Lisäohjeita tehtävän toteutukseen on annettu terveisten jälkeen.

(1) Meille on tärkeää pystyä osoittamaan havainnollisesti mallintamalla, miten eri asiat selittävät maapallon lämpenemistä ja korostamaan, miten merkittävä osa hiilidioksidilla lämpenemisessä on. Olemme nähneet mallinnuksia, joissa ENSO, tulivuoret ja auringon aktiivisuus on otettu huomioon ja datan avulla osoitettu, että ne selittävät hyvin “kupruja”, mutta eivät isompaa trendiä. Haluaisimme tästä sovellukseen interaktiivisen visualisaation.

(2) Arktiksen on havaittu lämpenevän huomattavasti keskiarvoa nopeammin, mikä on meidän suomalaisten kannalta tietenkin merkittävä havainto. Sovelluksesta olisi hyvä löytyä visualisaatio, jossa eri leveysasteiden ja vuodenaikojen eritahtinen lämpeneminen näkyisi selvästi. Voit hyödyntää visualisaatiossasi haluamaasi dataa. Aiemmin sopiviksi on todettu esimerkiksi NASA GISS:n tarjoama data. Ennusteita varten tarvitaan myös malli.

(3) Olemme kiinnostuneita myös BKT:n ja päästöjen suhteesta. Haluaisimmekin nähdä sovelluksessa visualisaation siitä, miten päästöjen ja BKT:n suhde on historiallisesti muuttunut ja mikä tilanne on tällä hetkellä.

Toteuta seuraavat kohdat 4 ja 5 perustuen tehtävän ensimmäisessä vaiheessa valitsemaasi toteutukseen.

(4) Meitä kiinnostaa myös tietää, mitä tulevaisuudessa tapahtuu, jos jatketaan nykyisellä linjalla. Asia on tietysti monimutkainen ja pelkän datan perusteella on vaikea sanoa, käyttäytyvätkö kaikki suureet samalla tavalla tulevaisuudessa. Toiveenamme kuitenkin on, että sovelluksella pystyisimme näkemään ekstrapoloimalla tehdyn pääpiirteisen ennusteen tulevaisuuden tilasta ja miten varmana malli sitä tulevaisuutta pitää (luottamusvälit).

(5) Haluamme sovelluksesta sekä selain- että mobiiliversion. Design-prosessin osana toivoisimme näkevämme myös hahmotelman rajapinnoista yleisellä tasolla. Mitä rajapinnoissa pääpiirteittäin kulkisi ja mitä toteutettaisiin backendissä ja mitä frontendissä. Entä miten saamme datat ja mallit päivittymään automaattisesti, kun uutta dataa tulee kuukausittain lisää?

Vaikka olemme vasta projektin design-vaiheessa toivomme, että mallinnukset on tehty niin, että ne olisi helposti siirrettävissä backendiin ja lähtötiedot saataisiin päivittymään automaattisesti.

Tehtävässä käytettävä data

Data Scientistit ovat projekteissamme usein vastuussa datan hankkimisesta, minkä vuoksi tehtävään ei ole annettu valmiita datalähteitä. Internet on kuitenkin pullollaan erilaisia datalähteitä, joita voit tehtävässä hyödyntää. Hyviksi todettuja lähteitä ovat esimerkiksi World Bank ja Berkeley Earth.

Ohjeita tehtävän tekemiseen

Tehtävän ratkaisun on tarkoitus olla näyte data science- ja data engineering -taidoistasi, ei siis vain tehtävänannon täyttämistä. Keskity ratkaisussasi osiin, joissa taitosi pääsevät mielestäsi oikeuksiinsa. Tehtävänanto on laaja ja ajoittain epämääräinen kuten usein reaalielämässäkin, ja oikeassa asiakasprojektissa kommunikoisimme intensiivisesti ja jatkuvasti asiakkaan kanssa. Tässä tehtävässä se ei ole mahdollista, joten saat vapauden tehdä valintoja luottaen omaan tulkintaasi tehtävänannosta.
Toteuta tehtävänannon kohdista 1–3 siis vähintään yksi, ja lisäksi kohdan 4 mukainen ennuste valitsemallesi kohtien 1–3 tehtävälle sekä kohdan 5 mukainen hahmotelma sovelluksen mallinnus- ja data-arkkitehtuurista. Kerro vastauksessasi myös, mitä mieltä olet ennusteesi laadusta. Mitä ennuste ja sen epävarmuusestimaatit ottavat ja eivät ota huomioon? Arvostamme ongelman, mallien, datan ja ratkaisun ymmärtämistä.

Visualisoinnit voit raportoida meille esimerkiksi markdownina. Halutessasi voit toki toteuttaa myös interaktiivisen demon, esimerkiksi Shinylla. Kiinnitä ratkaisussasi huomiota koodin luettavuuteen ja sen jakamiseen järkeviin kokonaisuuksiin.
Mikäli sinulla herää kysymyksiä tehtävästä, voit laittaa niitä meille osoitteeseen summerjob@reaktor.com
Toimita kesätyötehtävän lähdekoodit ja visualisaatiot (md, pdf, jpg, …) meille linkkinä esimerkiksi GitHub- tai GitLab-repositorioon yhdessä hakemuksesi ja CV:si kanssa kesätyöpaikkailmoituksen alta löytyvän lomakkeen avulla. Huomioi, että lomake mahdollistaa vain yhden liitteen lähettämisen, joten paketoi kaikki tiedostosi yhdeksi PDF:ksi tai lähetä ne meille .zip-muodossa. 

