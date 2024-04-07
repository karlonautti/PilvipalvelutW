# Viikon 2 tehtävät

## 1. Miten Jekyll sivustoa voisi automatisoida käyttäen GitHub Actions-toimintoja?

GitHub Actions -toiminto tarjoaa tehokkaan ja monipuolisen tavan automatisoida Jekyll-sivston kehitys- ja julkaisuprosessi, mikä säästää aikaa ja varmistaa sivuston laadun ja luotettavuuden.

Ensinnäkin, toimintoa voi käyttää automatisoimaan sivuston rakentamisen aina kun sivulle tehdään uusia muutoksia versionhallintaan, kuten juuri GitHubiin. Tällä varmistetaan että sivusto on aina päivitetty uusimpaan versioon.

Toisekseen GitHub Actions -toimintoa voidaan käyttää testien suorittamiseen ja virheiden havaitsemiseen koodissasi. Voidaan määritellä erilaisia testejä, esimerkiksi varmistamaan, että sivusto näyttää oikealta selaimessa tai että kaikki linkit toimivat oikein. Näin pystyt varmistamaan laadun ja vähentämään virheiden määrää sivustolla.

## 2. Millaisilla kehitystyökaluilla ja -tekniikoilla saataisiin CI/CD-putkisto rakennettua web-sovellukselle?

CI/CD-putkisto (Continuous Integration / Continuous Deployment) on tärkeä osa modernia ohjelmistokehitystä, ja sen avulla voidaan automatisoida koodin testaus, integrointi ja julkaisu. CI/CD-putkiston rakentamiseen web-sovellukselle on olemassa monia erilaisia kehitystyökaluja ja -tekniikoita. Ensinnäkin, suosittu valinta on käyttää pilvipalveluita, kuten AWS (Amazon Web Services), Azure tai Google Cloud Platform, jotka tarjoavat laajan valikoiman palveluita CI/CD-putken rakentamiseen ja hallintaan.

Kehitystyökalujen osalta yleisiä valintoja ovat Jenkins, Travis CI ja CircleCI sekä GitHub Actions, jotka tarjoavat helppokäyttöisiä ja joustavia työkaluja CI/CD-putken hallintaan ja konfigurointiin. Jenkins on avoimen lähdekoodin CI/CD-työkalu, kun taas Travis CI ja CircleCI ovat pilvipohjaisia CI/CD-palveluja.

Tekniikoista yleinen lähestymistapa on käyttää konttiteknologiaa, kuten Dockeria, CI/CD-putken rakentamisessa. Docker mahdollistaa sovellusten pakkaamisen ja jakamisen yhtenäisinä kontteina, mikä helpottaa sovellusten siirrettävyyttä ja ympäristöjen hallintaa eri vaiheissa CI/CD-prosessia.

Lisäksi infrastruktuurin koodaustyökalut, kuten Ansible, Puppet ja Terraform, tarjoavat tehokkaita työkaluja infrastruktuurin automatisointiin ja hallintaan, mikä auttaa toteuttamaan CI/CD-putken skaalautuvasti ja luotettavasti.

Yhteenvetona, valinnat kehitystyökaluista ja -tekniikoista riippuvat projektin tarpeista ja vaatimuksista, mutta pilvipalvelut, CI/CD-työkalut ja konttiteknologia ovat yleisiä valintoja CI/CD-putken rakentamisessa web-sovelluksille.
