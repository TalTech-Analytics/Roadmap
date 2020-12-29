# Roadmap

# Acronyms
DAG - Directed acyclic graph

## Probleemid
* Puudub ülevaade ülesannetest
* Puudub ülevaade tudengitest
* Aine väljund pole struktureeritud
* Tagasiside käsitsi töötlemine on ajamahukas
* Abiõpetajate peale läheb liiga palju resursse (raha ja aeg/managneerimine)
* Ülesanded pole tihtipeale kasutajasõbralikud - Vigased testid/mall/ülesande tekst

## Lahendus
### Puudub ülevaade ülesannetest
* [ ] Oskari lõputöö - koondab ülesanded ühte kohta ning see võimaldab taaskasutada ülesandeid ning kasutada välist linki (tema baasi id ref) antud süsteemis. 
* [ ] Teemad/võtmesõnad (saab manuaalselt panna) (Nice to have - Tekstikaeve asja saab kasutada valideerimiseks)
* [ ] Tavo lõputöö - Raskuse indikaator/ajakulu ühikutes semestri peale (esmakursuslasel keskmiselt 5h)
* [ ] Moodle koondaruanne - see ära siduda oskari lõputööga, mis omakorda ära siduda tavo lõputööga ning kokku saab terviku
* [ ] AreteUI'st tõmmata seotud informatsioon
* [ ] Oskari lõputöö raames see informatsioon ka näidatakse UI's
* [ ] See informatsioon kajastub ka Charonis - seal tabelid ja vaated korda teha ning lisada graafikuid
* [ ] Paralleelselt alamtesteriga jooksutada [sonarqube](https://www.sonarqube.org/) ning see info lisada AreteResponseDTO'sse
* [ ] Agregeeritud info:
  * Parmate punktide jaotus. Aritmeetiline keskmine, mediaan ära märkida graafikul, kus on telg 0p -> max punktid (joondiagramm)
  * Commit'ide aja jaotus graafiliselt (joondiagramm)
  * Kulutatud koguaeg ning aeg keskmise/mediaani tudengi peale + enim aega kulutanud tudengid (eraldi rida + tabel kõikide ülesannetega)
  * Stiilivigade + SonarQube vigade jaotus (tulpdiagramm)
  * Info, et kui paljudel on punkte rohkem kui .25, .5, .75 max punktidest, paljudel on stiil korrast ära parimal tulemusel, paljudel on kaitsmata (eraldi rida + tabel kõikide ülesannetega)
  * Tudengi tagasiside ülesandele
   * Läbi aegade tagasiside ülesandele
   * Selle semestri tagasiside ülesandele
    * Kas oli liiga raske
    * Kas meeldis
    * ...

### Puudub ülevaade tudengitest
* [ ] Personaalne ülevaade tudengist, et mis tippe ta on läbinud programmeerimise DAG'il
* [ ] Tudengi tagasiside analüüsimine - millest sai aru ning millest ei saanud aru - kuidas nad tunnevad ennast
* [ ] Kuidas tal ülesande raames läheb - AreteUI info + Agregeeritud Tavo lõputöö
  * Kulutatud aeg tundides
  * Commit'ide arv
  * Stiilivigade arv + SonarQube
  * Võrdlus keskmise tudengiga
  * Lõppinfo:
   * Testi punktide arv
   * Stiilipunktide arv
   * Kaitsmise punktide arv

### Aine väljund pole struktureeritud
* [ ] Koostada programmeerimise DAG, kus on erinevate ainete erinevad harud ning tippudele on eeldus, et sinna saada
* [ ] Aine raames ära märkida tipud, mida tudeng peaks läbima - osad tipud panna ka eksamile näiteks
* [ ] Tudengite DAG'ide kokkuvõte - kui paljud tudengid oskavad mida + keskmise tudengi DAG

### Tagasiside käsitsi töötlemine on ajamahukas
* Puudub ülesanne ülesandest - Tudengi tagasiside ülesandele
* Puudub ülevaade tudengitest - Tudengi tagasiside analüüsimine - millest sai aru ning millest ei saanud aru - kuidas nad tunnevad ennast

### Abiõpetajate peale läheb liiga palju resursse (raha ja aeg/managneerimine)
* Koodi analüsaator/SonarQube aitab leida põhivigu
* Ülesannete taaskasutamine
* Automaatsed kaitsmise punktid koodi analüsaatori tulemuse põhjal
* Kaitsmise punktid saab quiz'ile vastates (Tehniliselt keeruline teostada)
* Suuremad ülesanded - 4 ülesannet kokku - igal ülesandel 4 osa - kaitseb kogu ülesannet koos

### Ülesanded pole tihtipeale kasutajasõbralikud - Vigased testid/mall/ülesande tekst
* [ ] Tekstianalüsaatoriga analüüsida mallide kvantitatiivseid mõõtlemid (raskus, formaalsus, loetavus, tihedus)
* Tudengi tagasiside analüüsimine
  * [ ] Tekkivad küsimused eraldada - tabel küsimustest
  * Lisada küsimus - puudujäägid
* Ülesannete taaskasutamine
