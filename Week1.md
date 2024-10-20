## Week 1
<details>
  <summary>Sisällysluettelo Viikko 1 </summary>
  <ol>
    <li><a href="#Question 1:">Question 1</a></li>
    <li><a href="#Answer 1:">Answer 1:</a></li>
    <li><a href="#Question 2:">Question 2</a></li>
    <li><a href="#Answer 2:">Answer 2:</a></li>
        <li><a href="#Question 3:">Question 3</a></li>
    <li><a href="#Answer 3:">Answer 3:</a></li>
        <li><a href="#Question 4:">Question 4</a></li>
    <li><a href="#Answer 4:">Answer 4:</a></li>
        <li><a href="#Question 5:">Question 5</a></li>
    <li><a href="#Answer 5:">Answer 5:</a></li>
        <li><a href="#Question 6:">Question 6</a></li>
    <li><a href="#Answer 6:">Answer 6:</a></li>
  </ol>
</details>

## Question 1:
Describe following commands and concepts: 
<ul>
<li>man, apropos</li>
<li>man date</li>
<li>ls</li>
<li>ls --help</li>
<li>date</li>
<li>date --help</li>
<li>cd</li>
<li>cd -</li>
<li>cd ..</li>
<li>ls -lat</li>
<li>ls -s aaaa*</li>
<li>pwd</li>
<li>chown</li>
<li>chmod</li>
<li>chgrp</li>
<li>chmod 644 file</li>
<li>chmod g+x myfile</li>
<li>rm</li>
<li>rm -r mydoc</li>
<li>cp primary secondary</li>
<li>mv file2 file1</li>
<li>mkdir mydata</li>
<li>rmdir mydata</li>
<li>more, less</li>
<li>file</li>
<li>stat</li>
<li>df</li>
<li>ln</li>
<li>which, whereis</li>
<li>find</li>
<li>touch</li>
<li>touch mynewfile</li>
<li>cp /tmp/test.txt ~/temp/</li>
</ul>


## Answer 1:
<ul>
<li>man, apropos</li> <b>apropos</b> - etsii manuaaleista  avainsanalla liittyviä tiedostoja ja viittauksia. <br>
<b>man</b> - Avaa ohjelmisto tai pakettiin liittyvän dokumentaation, jossa on kerrottu tietyn ohjelman taikka paketin käyttötarkoitus, toiminnallisuudet, kommennot, riippuvuudet, optiot, sekä lyhyt kuvaus. 
<li>man date</li> - Avaa date pienohjelman lyhyeen dokumentaation , jossa kerrostaan date peinohjelman, käyttötarkoitus, ominaisuudet, esimerkit, lisenssit ja tekijänoikeudet. 

<li>ls</li> - Oletuksena listaa nykyisessä kanssiossa olevat tiedostot, sekä kansiot. Kykenee näyttämään, myös piilotetut tiedostot tai kansiot, kansion tai tietoston luku- ja kirjoitusoikeudet, sekä kansion tai tiedoston omistajan ja ryhmän.
<li>ls --help</li> Avaa ls-pienoisohjelman lyhyeet käyttöohjeet, kuten miten tätä pienohjelmaa voi käyttää, millä parametrejä  voi esimerkiksi käyttää, jotta saisi vaikka listauksen tietyn näköisenä, vaikka kokojärjestyksessä. Esimerkiksi ls -a listaa nykyisen kansion kaikki tiedostot, mukaan lukien pisteellä merkityt "piilotettut" tiedostot ja kansiot. 
<li>date</li> Käynistää pienoisohjelman Date, joka tulostaa komenntorivin näytölle palvelimen nykyisen päivämäärän ja ajan, sekä aikavyöhykkeen. (Sun Oct 20 06:30:24 PM EEST 2024)
<li>date --help</li> Listaa Date pienohjelman ohjeet, miten tätä pienohjelmaa ajetaan, esimerkiksi jos haluaa päivämäärän näkyvän tietyssä muodossa. 
<li>cd</li> Kyseinen pienohjelma mahdollistaa liikkumisen tietojärjestelmässä kansiosta toiseen, kirjoittamalla esimerkiksi <b>cd /etc/nginx</b> Pääsemme siirtymään Nginx-verkkopalvelimen tiedostoihin. 
<li>cd -</li> Kyseisellä kommenolla pääsemme kätevästi hyppäämään tietojärjestelmän juuripolulle, eli / 
<li>cd ..</li> Kyseisellä komennolla pääsemme hyppäämään tiedostopolun mukaisesti yhden kansion taakseppäin. Eli jos olemme polulla /etc/nginx, niin cd .. komennoilla siirymme kansioon /etc/ 
<li>ls -lat</li> Listaa aktiivisen kansionsisällä, eli missä juuri olemme kaikki kansiot, tiedostot ja näyttää samalla luku ja -kirjoitusoikeudet, sekä kansion/tiedoston omistajan ja ryhmän. Lisäksi muokkauspäivän.
<li>ls -s aaaa*</li> Komento etsii ja listaa kaikki tiedostot joiden nimissä on aaaa
<li>pwd</li> komento kertoo nykyisen sijantimme tietojärjestelmässä. Esim. /home/oamk
<li>chown</li> Komento mahdollistaa tiedoston tai kansion omistajan ja/tai ryhmän asettamista, sekä vaihtoa. Esim. chown oamk:aomk /home/oamk/.aaaa
<li>chmod</li> Tällä komennolla voimme määrittää kirjoitus- ja lukuoikeudet tiedostolle ja kansiolle, sekä tarvittaessa myös alikansioille ja tiedoistoille. esim chmod 777 -R /home/oamk/* asettaa kaikille tiedostoille ja kansioille täydet kirjoitus ja luku oikeudet.
<li>chgrp</li> Tällä komennolla voimme vaihtaa/asettaa kansioille tai/ja tiedoistoille tietyn ryhmän. 
<li>chmod 644 file</li> Asettaa tiedostolle nimellä file, kaikille käyttäjille lukuoikeuden ja omistajalle kirjoitusoikeuden, ilman suoritusoikeuksia. 
<li>chmod g+x myfile</li> Antaa tietylle ryhmälle suoritusoikeudet myfile tiedostoon
<li>rm</li> Komento poistoa varten. 
<li>rm -r mydoc</li> Komento poistaa kansion mydoc
<li>cp primary secondary</li>Kopiointi komento, cp lahde_mitakopioidaan minne_kopioidaan
<li>mv file2 file1</li>Mv, eli ns. liikutus komento. Tässä tapauksessa on kuitenkin kyse file2 uudelleen nimeämisestä file1:ksi.
<li>mkdir mydata</li> Komento luo kansion nimellä mydata
<li>rmdir mydata</li> Komento tuhoaa/deletoi kansion nimellä mydata
<li>more, less</li> More ja less ovat komentoja, jotka ovat tarkoitettu helpottamaa työskentelyä komentorivillä, kun tehtävänä on lukea tiedostoje, kuten logeja. More komento avaa tiedoston ja pilkkoo sen ns. sivuihin, jolloin välilyöntiä painamalla pystyy lukemaan tiedostoa kokonaa. Less on hieman kehittyneempi ja mahdollistaa liikkumisen nuolinäppäimillä eteen ja taaksepäin, sekä löytyy haku, joka toimii hakusanoilla. /avainsana etsii valitusta kohdasta eteenpäin ja ?avainsana valitusta kohdasta taaksepäin. 
<li>file</li> auttaa tunnistamaan tiedoston tyypin, koon ja muodon. 
<li>stat</li> Komento yksityiskohtaisempaan tiedoston näyttämiseen, kun halutaan katsoa tiedostoa, sen tyyppiä, kokoja, nimeä, tyyppiä, käyttöoikeuksia, tiedoston viimeisin käyttö tai muutospäivämäärä.
<li>df</li>Komneto joka raportoi kuinka paljon levytilaa on käytettävissä. Pelkkä df listaa kaikki levyasemat, lohkot, kuten /dev, /run, /, /opt jne ja näyttää niiden varauksen ja vapaan tallennustilan biteissä. 
<li>ln</li> Komento jolla voidaan luoda linkitys kahden tiedoston tai kansion välillä. Linkkejä voi olla kovia, sekä symbolisia. 
<li>which, whereis</li>which ja whereis käytetään ohjelmien, sekä komentojen sijainnin selvittämiseen.  Which etsii komennon sijainin käyttäen PATH-ympäristömuuttujaa, kun taas whereis etsii ohjelman binääritiedostoa, manuaaleja, ja lähdekoodi tiedostoja. 
<li>find</li> Hakukomento, jolla voi etsiä käyttöjärjestelmästä mitä vaan. Tällä komennolla voi tehdä hakurajauksia, nimellä hakuja, tyypillä hakuja, kokohakuja jne. Toisin sanoin Linux käyttäjän parasystävä. 
<li>touch</li> Komentoa käytetään tyhjientiedostojen lumiseen, tai olemassa olevien tiedostojen aikaleimojen virkistämiseksi. 
<li>touch mynewfile</li>Luo tyhjäntiedoston nimeltään mynewfile tai jos tiedosto on olemassa päivitää tämän aikaleiman. 
<li>cp /tmp/test.txt ~/temp/</li> Komento kopioi tmp kansiosta test.txt tiedoston ja vie sen kirjautuneen käyttäjän kotikansioon, temp-kansioon. Jos kotikansion temp kansiota ei ole, niin komento epäonnistuu. 
</ul>



## Question 3:
What is the difference between Linux kernel and GNU/Linux distribution?

<li>Answer 3:</li>
Linux kernel on käyttöjärjestelmän ydinosa, joka hallitsee laitteiston ja ohjelmiston välistä kommunikaatiota. Vastaa resurseista, kuten muistista, prosessorista ja laitteiston hallinnasta ja ohjeuksesta. 

GNU/Linux distribution, eli GNU/linux jakelu. On kokonaisuus, eli käyttöjärjestelmä, joka sisältää kernelin, eli ytimen ja nipun ohjelmia, jotka yhdessä muodostavat kokonaisuuden, eli käyttöjärjestelmän. Näitä voi olla tuhansia erillaisia, kuten kaikille tuttu Ubuntu käyttöjärjestelmä. Jokainen voi käytönnössä luoda oman käyttöjärjestelmän, joka sisältää itselleen tarvittavia ohjelmia ja työkaluja ja hyödyntää olemassa olevaa Kernel ydintä. 


## Question 4:
Name some very common Linux distributions

<li>Answer 4:</li>
Tunnetuimat ovat: Ubuntu, Debian, Fedora, CentOS , Arch linux. 

## Question 5:
What is GPLv2/v3 license? And BSD style license?

<li>Answer 5:</li>
GPLv2 - lisenssi Julkaistu vuonna 1991, mahdollistaa ohjelmiston vapaan käytön, muokkauksen ja jaon. Edellyttää, että, kaikki mitä tehdään on julkaisutu aluperuin GLPv2- lisenssillä myös julkaistaan jatkossa samalla lisenssillä, eli lisenssiä ei voi lennosta muutaa. Lähdekoodi on pidettävä matkalla mukana. 
GPLv3 - lisenssi julkaistu vuonna 2007, Sisältää hieman selkeämmän ehdot verrattuna aikasempaan versioon. Parantaa oikeuksia ja antaa enemmän suojaa ohjelmiston vapaalle jaolle. Kuka tahansa voi kopioida, muokata, käyttää ja käyttää omissa jakeluissa.  
BSD tyylinen lisenssi