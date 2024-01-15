# GitVersionhallinta

1. (Forkkaa ja) Pullaa tämä repository. (Oikealta yhlhäältä tällä sivulla klikkaa Fork, create fork (omaan githubiisi), kopioi sen kloonauslinkki. Mene gitbashissa valitsemaasi kansioon (~/source/repos/Gitkurssitehtävä/) ja suorita git clone omasta forkkauksestasi saamasi kloonauslinkkisi kanssa.)
2. Luo pullaamaasi Master haaraan oma branch ja nimeä se omalla nimelläsi // git branch ohjeet esim googlaamalla tai  materiaalia lukemalla
3. Lisää muokkaajat tiedostoon oma rivisi, jossa kerrot lempivärisi tai harrastuksesi. Muista laittaa riville myös oma nimesi. // voit käyttää joko nano-editoria tai muistiota
4. Luo kansio ja nimeä se GitHub tunnuksellasi Git Bashissa (mkdir) Kansiot kansioon ja lisää luomaasi kansioon tiedosto peli.txt käyttäen echo käskyä, kirjoita tiedostoon sen pelin nimi, jota viimeksi pelasit //open esimerkki:  
 
      mkdir JenKalliosto  
      cd JenKalliosto  
      echo "Far Cry 6" >> peli.txt
      
5. Lisää muutoksesi Staging Areaan ja suorita Commit
6. Tarkista että lokaali branch on ajan tasalla master branchin kanssa käyttämällä seuraavia komentoja: checkout, fetch, ja pull. Sitten Checkouttaa takaisin omalle branchillesi ja tee merge. Mikäli merge ei jostain syystä git bash -sovelluksessa onnistu voit toteuttaa sen myös omassa Git Hubissasi:

      Git Bashissa, omassa nimikko-branchissasi tee tämä push:
      git push origin [Branchin nimi]
      jonka jälkeen GitHubissa /omassa/ GitVersionhallinta repositoryssäsi tee pull request
      valitse oma branchsisi yhdistettäväksi omaan mainiisi ja suorita merge
      
7. Loggaa GitHub tilillesi ja klikkaa Compare & Pull Request projektin remotesta reposta, ja sitten siellä "Create new pull request".
      
      Jos GitHub ei automaattisesti tarjoa create new pull requestia klikkaa "Compare across forks" ja valitse oma forkkisi
      
8. Pull requestisi tarkistetaan ja lopulta mergetään masteriin.
