# Kotitehtävä 1: Linuxin asennus

### Tehtävänanto
I.	Linuxin asennus virtuaalikoneeseen.

### Käyttämäni systeemi
Lenovo IdeaPad Slim 5:

Prosessori: 13th Gen Intel Core i5

Keskusmuisti: 16 GB LPDDR5-5200MHz

Näytönohjain: Integrated Graphics

Käyttäjäjärjestelmä: Windows 11

### Debianin lataus
Ensimmäisellä luennolla latasin koneelleni jo valmiiksi Debianin osoitteesta https://www.debian.org/, tarkemmin tästä latauslinkistä https://cdimage.debian.org/debian-cd/current-live/amd64/iso-hybrid/debian-live-12.1.0-amd64-xfce.iso . Tiedoston koko on 2,9 GB, ja latauksessa meni n. 5 minuuttia. Latasin .iso tiedoston, sillä se riittää virtuaalikoneeseen asentamiseen. 
![image](https://github.com/16cats/h1/assets/97065659/25e1b7aa-ecd2-4357-b17c-7b61022be8a3)


### Asennus
Käytössäni oleva virtuaalikone on Oracle VM VirtualBox. 
Loin uuden virtuaakoneen, johon laitoin yllämainitun .iso-tiedoston ja klikkasin ‘’Skip Unattended Installation’’. Seuraavaksi annoin perusmuistia 4096 MB sekä 4 prosessoria. Loin uuden Virtual Hard Diskin, jolle annoin 40 GB. Finish.

![image](https://github.com/16cats/h1/assets/97065659/589afed1-9bf4-453d-9900-2d814e1b1fd8)

Menin Liveboottiin, ja aloitin latauksen. Sieltä valitsin kieleksi American English, laitoin aikavyöhykkeeksi Europe/Helsinki, ja näppäimistön suomeksi. Aloitin latauksen. 

(..Aikani loppui tässä läksyn palautuksen kanssa, pahoittelut! Dokumentoin loput tehtävästä kuitenkin vielä.) 

Latauksessa meni 8 minuuttia, ja sen päädyttyä kirjauduin sisään ja aloitin koneen päivityksen. 
sudo apt-get update
sudo apt-get -y dist-upgrade

![image](https://github.com/16cats/h1/assets/97065659/428c4dfa-4350-4c43-ab85-e66689899979)

Valmis!

## Lähteet
https://terokarvinen.com/2006/raportin-kirjoittaminen-4/
