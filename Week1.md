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

## Question 2

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

## Answer 2

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

<li>chmod 644 file</li> Asettaa tiedostolle nimellä file, kaikille käyttäjille lukuoikeuden ja omistajalle
kirjoitusoikeuden, ilman suoritusoikeuksia.

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

## Question 3

What is the difference between Linux kernel and GNU/Linux distribution?

<li>Answer 3:</li>
Linux kernel on käyttöjärjestelmän ydinosa, joka hallitsee laitteiston ja ohjelmiston välistä kommunikaatiota. Vastaa resurseista, kuten muistista, prosessorista ja laitteiston hallinnasta ja ohjeuksesta.

GNU/Linux distribution, eli GNU/linux jakelu. On kokonaisuus, eli käyttöjärjestelmä, joka sisältää kernelin, eli ytimen ja nipun ohjelmia, jotka yhdessä muodostavat kokonaisuuden, eli käyttöjärjestelmän. Näitä voi olla tuhansia erillaisia, kuten kaikille tuttu Ubuntu käyttöjärjestelmä. Jokainen voi käytönnössä luoda oman käyttöjärjestelmän, joka sisältää itselleen tarvittavia ohjelmia ja työkaluja ja hyödyntää olemassa olevaa Kernel ydintä.

## Question 4

Name some very common Linux distributions

<li>Answer 4:</li>
Tunnetuimat ovat: Ubuntu, Debian, Fedora, CentOS , Arch linux.

## Question 5

What is GPLv2/v3 license? And BSD style license?

<li>Answer 5:</li>
GPLv2 -  (GNU General Public License ) lisenssi  on hyvin tunnettu ja yleisesti käytettävä vapaan lähdekoodin lisenssi.  Joka noudattaa Copyleft(tekijänoikeuskonsepti) lisenssiä.

Copyleft takaa ohjelmiston, taiteen, tai muun luovan työn vapaan käytön, muokkaamisen ja jakamisen, mutta sillä on ehtoja jakelulle. Samat ehdot pitää säilyttää, mitkä olivat alkuperäisessä tuotoksessa, eli vaikka lainaisit ja muokkaisit sitä, niin tulee sinun muokkaamasi tuotoksessa olla käytössä samat GPL- lisenssit ja Copyleft käyttöoikeudet vapaaseen käyttöön.

GPL- sallii teoksen levityksen ja muokkaamisen, kunhan seuraavat ehdot täyttyvät:

• Lisenssiä ei saa muuttaa tai poistaa
  
• Muokkauksista pitää lisätä huomio

• Ohjelman tulee sisältää tieto lisenssistä

• Lähdekoodi pitää tehdä saataville kaikille, joille ohjelma on levitetty

• Johdannaisteokset tulee lisensoida samalla lisenssillä

GPLv3 – lisenssi on uudistettu versio 2 versiosta, mutta uudemmassa versiossa lisenssin ehdot on kirjoitettu lakiteknistä kieltä käyttäen , jotta lisenssiä voisi käyttää kansainvälisesti, sekä yhteensovittaa muiden lisenssien kanssa. 3 versio antaa lisäsuojaa suljettuja järjestelmiä ja patentteja vastaan.
BSD- lisenssi eli vapaan lähdekoodin lisenssi poikkeaa GPL-lisenssistä siten, että antaa vapauden lisenssin vaihdoille, eli ei käytä Copyleft-lisenssiä ja mahdollistaa muokatun tuotoksen uudelleen lisensioinnin.

Lähde(Luettu 21.10.24): <https://www.sofokus.com/fi/blogi/avoin-lahdekoodi/>

Lähde Luettu 21.10.24):  <https://www.gnu.org/licenses/gpl-3.0.html>

## Question 6

What is (operating system) shell?

<li>Answer 6:</li>
Shell on käyttöjärjestelmän (operating system) tarjoama ohjelma, joka toimii rajapintana käyttäjän ja käyttöjärjestelmän ytimessä toimivien palveluiden välillä. Se ottaa vastaan käyttäjän komennot, käsittelee ne ja välittää ne käyttöjärjestelmälle suoritettaviksi. Shell voi olla joko tekstipohjainen tai graafinen.

Tekstipohjainen Shell, eli komentorivipohjainen esiintyy esimerkiksi Linux ja macOS komentoriveillä.
Linuxissa, sekä macOS:ssä käytetään Bashia (Bourne Again Shell) ja Windowsissa Powershelliä.
Tällä voidaan suorittaa komentoja, skriptejä ja hallinnoida järjestelmää käyttäen yksinkertaisia komentoja komentoriviä hyödyntäen.

Graafinen Shell (Graphical User Interface, eli GUI)
Toimii käyttöjärjestelmän graafisen ympäristön kautta, jossa käyttäjä voi kuvakkeita ja valikkoa painamalla käynnistää sovelluksia.
Windowsin käytättäjille tutumpi on Exploler.exe , joka vastaa graafisen rajapinnan tiedostojen hallinnan  ja ohjelmien avaamisesta.

Shellin tehtävät:

- Komentojen käsittely, skriptaus, käyttöjärjestelmän hallinta.

## Question 7

What are case sensitive file names?

<li>Answer 7:</li>
<b>Case sensitive</b> -tiedostonimet tarkoittavat, että tiedostojärjestelmä erottaa isot ja pienet kirjaimet toisistaan tiedostonimissä.
Esimerkiksi "tiedosto.txt" ja "Tiedosto.txt" viittaavat kahteen eri tiedostoon.
Käyttöjärjestelmät, jotka ovat <b>Case sensitive</b> kohtelevat Suuria ja pieniä kirjaimia eri merkkeinä.

## Question 8

Describe common purpose of files and directories in “/home”, “/etc”, “/usr/bin” and “/var”

<li>Answer 8:</li>
<b>/home </b> - Kansiopolussa sijaitsevat Käyttöjärjestelmään luotujen käyttäjien kotihakemistot. Jokaisella käyttäjällä on oletuksena oma alihakemisto, johon käyttäjät voi tallentaa omia tiedostoja. Esimerkiksi <b>/home/juustonaksu</b>

<b>/etc</b> kansio polussa sijaitsee järjestelmän ja asennettujen sovelluksien/pakettien määritys ja konfiguraatio asetukset. 
Esimerkiksi /etc/passwd tiedostossa, löytyy käyttöjärjestelmän käyttäjätietioja ja vaikka /etc/nginx kansiosta (jos asennettu) löytyy Nginx-verkkopalvelimen koskevat konfiguraatio tiedostot. 

<b>/usr/bin</b>
Tässä hakemistossa on käyttäjien suorittamat komennot, sekä ohjelmat, joita ei käytetä järjestelmän käynistysvaiheessa. Esimerkiksi vim, ls ja cp- ohjelmat löytyvät täältä.

<b> /var</b> Tässä hakemistossa sijaitsee muuttuvat tiedostot, joita käyttöjärjestelmä ja sovellukset päivittävät jatkuvasti. Esimerkiksi jos meillä on asennettu Nginx-verkkopalvelin, niin kansiopolussa /var/log löytyy nginx-verkkopalvelimen lokitiedostot. 
Kansiossa /var/run löytyy käynissä olevien ohjelmien PID (prosessin tunnus), eli prosessin tunnisteet.
/var/backup kansiopolussa löytyy yleenssä järjestelmän tekemiä varmuuskopioita, erillaisista asennettuista paketeista. 


<li>Question 9:</li>
What is shell PATH? What is the difference between absolute and relative path?

<li>Answer 9:</li>
<b>Absoluuttinen polku: </b> Absoluuttinen polku antaa tiedoston tai hakemiston täyden osoitteen alkaen juurihakemistosta (/). Se määrittää tiedoston tai hakemiston sijainnin riippumatta nykyisestä työhakemistosta. Esimerkiksi /home/oamk/x-files/repliikit.txt on absoluuttinen polku.

<b>Suhteellinen polku: </b> Suhteellinen polku määrittää tiedoston tai hakemiston sijainnin suhteessa nykyiseen työhakemistoon. Se ei ala juurihakemistosta, vaan nykyisestä hakemistosta. Esimerkiksi, jos nykyinen hakemistosi on /home/oamk , suhteellinen polku tiedostoon file.txt hakemistossa documents olisi x-files/repliikit.txt.

<li>Question 10:</li>
What is the purpose of tilde character (~) for most Linux shells. For example ls ~/

<li>Answer 10:</li>
Linux-kuorissa tildemerkki (~) toimii lyhenteenä, joka viittaa käyttäjän kotihakemistoon. Tämä helpottaa kotihakemiston ja muiden käyttäjien kotihakemistojen käsittelyä ilman koko polun kirjoittamista.
Esimerkiksi komento ls ~/ nykyisen käyttäjän kotihakemiston sisällön. 

Tilda merkkiä, voi myös hyödyntää nykyisen, sekä edellisen työhakemistoon. 

Esimerkiksi näin: ~+ viittaa työhakemistoon, joka vastaa PWD-muuttujaa.

Kun ~- viittaa edellisen työhakemistoon vastaten OLDPWD-muuttujaa.



<li>Question 11:</li>
How do you recognise a hidden file in any common Unix/Linux file systems?

<li>Answer 11:</li>
Unix- ja Linux-tietojärjestelmissä piilotettu tiedostot, sekä hakemistot tunnistaa siitä, että niiden nimi alkaa pisteellä.
Esimerkiksi .bashrc  on piilotettu, jos komentoriviltä syöttää komennon ls kotikansiossa /home/omak, mutta jos syötämme komentoriviin komennon ls -a, niin tämä näyttää meille kotikansiossa olevat myös piilotetut tiedostot ja kansiot. 
Piilotettu kansiot ovat muodoltaan .kansionnimi 


<li>Question 12:</li>
What is the meaning of “piping data between commands”?

<li>Answer 12:</li>
Unix-tyyppisissä käyttöjärjestelmissä putkittaminen tarkoittaa menetelmää, jossa yhden komennon tuloste ohjataan suoraan toisen komennon syötteeksi. Tämä saavutetaan käyttämällä putkioperaattoria (|). Putkittaminen mahdollistaa yksinkertaisten komentojen yhdistämisen monimutkaisiksi tehtäviksi tehokkaasti.

Esimerkiksi analysoidaan ssh-palvelimen lokeja tiedostosta /var/log/auth.log ja selvetään mistä IP-osoitteista on yritetty kirjautua väärällä salasanalla:

grep "Failed password" /var/log/auth.log | awk '{print $(NF-3)}' | sort | uniq -c | sort -nr

-	grep "Failed password" /var/log/auth.log etsii kaikki rivit, joissa esiintyy teksti "Failed password", eli epäonnistuneet kirjautumisyritykset.
-	awk '{print $(NF-3)}' tulostaa jokaisen rivin kolmanneksi viimeisen kentän, joka on epäonnistuneen kirjautumisyrityksen IP-osoite.
-	sort lajittelee IP-osoitteet aakkosjärjestykseen.
-	uniq -c laskee, kuinka monta kertaa kukin IP-osoite esiintyy.
-	sort -nr lajittelee tulokset numeerisesti laskevassa järjestyksessä, jolloin eniten esiintyneet IP-osoitteet näkyvät ensimmäisinä.



<li>Question 13:</li>
What are seti-uid (suid) and set-gid (sgid) bits for file permissions?

<li>Answer 13:</li>
 **Set User ID (SUID)**  ja **Set Group ID (SGID)** ovat erityisiä tiedostojen käyttöoikeusbittejä, jotka muuttavat oletusarvonsa suorituskäyttäytymisen mukaan.
**Set User ID (SUID):**
Kun **SUID**-bitti on asetettu suoritettavalle tiedostolle, käyttäjät voivat suorittaa tiedoston sen omistajan oikeuksilla riippumatta omista käyttöoikeuksistaan. Tämä on hyödyllistä ohjelmille, jotka vaativat korkeampia oikeuksia tiettyjen toimintojen suorittamiseen.
Esimerkki:
passwd-komento, jota käytetään käyttäjien salasanojen vaihtamiseen, on asetettu SUID-bittillä. Tämä mahdollistaa tavallisille käyttäjille omien salasanojensa vaihtamisen, vaikka komento muokkaa järjestelmätiedostoja, joihin normaalisti vain root-käyttäjällä(pääkäyttäjällä) on kirjoitusoikeus.

Set Group ID (SGID):
SGID-bitti toimii eri tavoin riippuen siitä, onko se asetettu tiedostolle vai hakemistolle.
Tiedostoissa käyttäjä pystyy suorittamaan tiedoston, SGID-ryhmään asetetuilla oikeuksilla, vaikka käyttäjän oman oikeudet ei alun perin riittäisi tiedoston suorittamiseen. Eli jos käyttäjä kuuluu ryhmään, joka on asetettu tiedostolle, niin hänellä on saman oikeudet.
Kansioissa logiikka on muuten sama, mutta asettamalla kansiolle tietyn ryhmän, sama sääntö välittyy uusille kansion sillä tapahtuville muutoksille, eli jos luodaan kansio, niin kansio on tällöin saman ryhmän oikeuksien alla. 



<li>Question 14:</li>
What is a “sticky-bit”?

<li>Answer 14:</li>
sticky bit – on käyttöoikeus, joka asetetaan tietyille hakemistoille rajoittamaan tiedostojen muokkausta, uudelleen nimeämistä tai poistamista, kyseisen kansion sisällä.

Sticky bit- oikeudet voi asettaa kansiolle vain tiedoston omistaja, hakemiston omistaja tai Root (järjestelmävalvooja). 

Tätä käytetään mm. /tmp-hakemistossa joka on yleisesti kirjoitettavissa ja jota kaikki käyttäjät käyttävät väliaikaisten tiedostojen tallentamiseen. Asettamalla sticky bit /tmp-hakemistoon varmistetaan, että käyttäjät eivät voi poistaa tai nimetä uudelleen tiedostoja, joita he eivät omista, vaikka heillä olisi kirjoitusoikeudet hakemistoon.

Esimerkkejä Sticky bitistä: 

**chmod +t /polku/hakemistoon**

Vaihtoehtoisesti voi käyttää myös: 

**chmod 1777 /polku/hakemistoon**
Chmodin ensimmäinen luku 1, edustaa Sticky bittiä ja 777 asettaa luku-, kirjoitus- ja suoritusoikeudet kaikille käyttäjille.

ls -ld komennolla voidaan tarkistaa onko hakemistolle asetettu Sticky Bitti.

Esimerkiksi: ls -ld /polku/hakemistoon

Jos sticky bit on asetettu, hakemiston käyttöoikeuksissa näkyy t lopussa, esimerkiksi drwxrwxrw<b>t</b>.




<li>Question 15:</li>
Use manual pages and explain what will command “uname -a” do?

<li>Answer 15:</li>
Komento uname -a näyttää tiedot järjestelmästä yhdistämällä useita yksityiskohtia yhteen tulosteeseen.

uname-komennon manuaalisivun mukaan -a- tai --all-valitsin tulostaa kaikki saatavilla olevat järjestelmätiedot seuraavassa järjestyksessä:

•	Käyttöjärjestelmän nimi (-s): Käyttöjärjestelmän ytimen nimi.

•	Solmun nimi (-n): Koneen verkkonimi (hostname).

•	Ytimen julkaisuversio (-r): Ytimen julkaisuversio.

•	Ytimen versio (-v): Ytimen versio.

•	Koneen laitteiston nimi (-m): Koneen laitteistoarkkitehtuuri.

•	Prosessorityyppi (-p): Prosessorin tyyppi.

•	Laitteistoalusta (-i): Laitteistoalusta.

•	Käyttöjärjestelmä (-o): Käyttöjärjestelmän nimi.

Jos järjestelmä ei pysty määrittämään tiettyjä kenttiä, kuten prosessorintyyppiä, tulee kyseisille kohdille teksti ”unknown”. 


<li>Question 16:</li>
Use manual pages and explain what will command “wc -l” do?

<li>Answer 16:</li>
wc (eng. Print newline, word, and byte counts for each file, eli lyhenne sanoista word count) komento, joka laskee tiedostojen tai standardisyötteen rivien, sanojen ja merkkien määrän. Kun wc-komentoa käytetään -l-valitsimen kanssa, se laskee ainoastaan rivien määrän. wc-komennon manuaalisivun mukaan -l-valitsin tulostaa rivien lukumäärän.

Esimerkiksi, jos halutaan laskea tiedoston sisällä olevien rivien määrä, niin tämä onnistuu seuraavalla komennolla: wc – l esimerkki_tiedosto.txt

Saadaan vastaukseksi 85 esimerkki_tiedosto.txt 


<li>Question 17:</li>
Linux file handling intro: 

    List five largest files in /usr/lib -directory (Tip: Use ls command with proper command line options)
    What is the group for /bin/ls file?
    How do you change file or directory owner and group?
    How do you change file permissions so that file user has all access rights (read, write and execute), group and others have none?
    How do you change file permissions so that file user has read and write access (no execute), group and others have only read access?
    How do you change file permissions so that file user, group and others have only read and execute (no write) access?
    Describe following file permissions and ownership:
    drwxr-x--- 2 teemu root 4096 Jul 2 2002 webalizer
    Create directory “exercise1” under you home directory
    Create empty file (length 0 bytes) “qwerty.txt” to that directory
    Rename directory “exercise1” to “exer2”?
    Change file qwerty.txt file permissions so that only you (the owner) has a read access to it and nothing else
    Create symbolic link to you home directory “this_is_my_link” and make it point to the exer2-directory
    How can you find out your current directory location and PATH? How far (in directories) are you from the file system root (/)?



