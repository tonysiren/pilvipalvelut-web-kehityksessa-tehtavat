<a href="https://tonysiren.github.io/pilvipalvelut-web-kehityksessa-tehtavat/">
  ← Palaa edelliselle sivulle
</a>

## 2.3. Lyhyt kirjoitus

## Miten Jekyll-sivustoa voisi automatisoida käyttäen GitHub Actions-toimintoja?

GitHub Actions on pilvipalveluna toimiva jatkuvan integroinnin ja jatkuvan toimittamisen (CI/CD) alusta, jonka avulla voidaan automatisoida rakennus-, testaus- ja käyttöönottoprosessit. Sen avulla voidaan automatisoida Jekyll-kääntöohjelmaa käyttävän sivuston rakennus ja julkaisu. Kun uusia tiedostoja viedään repositoryyn, niin julkaisu tapahtuu automatisoidusti. 

GitHub Actions toimii siten, että määrittelemällä työnkulun voidaan käynnistää automaattisesti sarja toimenpiteitä aina, kun repositoryyn viedään uusia tiedostoja tai tehdään muutoksia. Jekyll-sivuston tapauksessa tämä tarkoittaa, että työkalulla voidaan ajaa koko sivuston rakennusprosessi Jekyll-kääntöohjelmalla ja siirtää lopulliset HTML-tiedostot julkaisuun, esimerkiksi GitHub Pages -palveluun. Työnkulku määritellään YAML-tiedostona GitHub workflows-kansiossa, jossa määritellään tarkasti, milloin ja miten rakennusprosessi suoritetaan.

## CI/CD-putkiston rakenntaminen web-sovellukselle

Verkkosovelluksen CI/CD-putki alkaa versionhallinnalla Git-alustojen, kuten GitHubin, GitLabin tai Bitbucketin avulla, joita käytetään koodimuutosten hallintaan ja automatisoitujen työnkulkujen käynnistämiseen.
Jatkuvan integraation (CI) vaiheessa työkalut, kuten GitHub Actions, GitLab CI/CD, Jenkins tai CircleCI, rakentavat ja testaavat sovelluksen automaattisesti jokaisen koodipäivityksen jälkeen varmistaen vakauden automatisoidun yksikkö- ja integraatiotestauksen avulla.
Lopuksi jatkuva käyttöönotto (CD) automatisoi julkaisuprosessin käyttämällä teknologioita, kuten Docker ja Kubernetes, konttiympäristöissä tai pilvipohjaisia ​​ratkaisuja, kuten AWS CodePipeline, Azure DevOps, Vercel tai Netlify, saumattoman verkkosovelluksen toimituksen takaamiseksi.

Lähteet: 

Pilvipalvelut web-kehityksessä kurssin luentomateriaalit 2025. 

The Codest. CI/CD (jatkuva integrointi/jatkuva käyttöönotto) määritelmä. Luettavissa: https://thecodest.co/fi/sanakirja/ci-cd-jatkuva-integrointi-jatkuva-kayttoonotto/. Luettu 30.10.2025.

Digital.AI. Guide to Building a CI/CD Pipeline. Luettavissa: https://digital.ai/catalyst-blog/building-cicd-pipeline/. Luettu 30.10.2025.









