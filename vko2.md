## 2.3. Lyhyt kirjoitus

Miten Jekyll-sivustoa voisi automatisoida käyttäen GitHub Actions-toimintoja?

GitHub Actions on pilvipalveluna toimiva jatkuvan integroinnin ja jatkuvan toimittamisen (CI/CD) alusta, jonka avulla voidaan automatisoida rakennus-, testaus- ja käyttöönottoprosessit. Sen avulla voidaan automatisoida Jekyll-kääntöohjelmaa käyttävän sivuston rakennus ja julkaisu. Kun uusia tiedostoja viedään repositoryyn, niin julkaisu tapahtuu automatisoidusti. 

GitHub Actions toimii siten, että määrittelemällä työnkulun voidaan käynnistää automaattisesti sarja toimenpiteitä aina, kun repositoryyn viedään uusia tiedostoja tai tehdään muutoksia. Jekyll-sivuston tapauksessa tämä tarkoittaa, että työkalulla voidaan ajaa koko sivuston rakennusprosessi Jekyll-kääntöohjelmalla ja siirtää lopulliset HTML-tiedostot julkaisuun, esimerkiksi GitHub Pages -palveluun. Työnkulku määritellään YAML-tiedostona GitHub workflows-kansiossa, jossa määritellään tarkasti, milloin ja miten rakennusprosessi suoritetaan.

Web-sovelluksen CI/CD-putkisto voidaan rakentaa hyödyntämällä useita työkaluja ja tekniikoita, jotka tukevat automaatiota, testausta ja jatkuvaa julkaisua. GitHub Actions toimii hyvin putkiston ytimenä ja kehitykseen voidaan yhdistää seuraavia työkaluja, kuten Docker ja Jenkins.








