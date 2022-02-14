

# Praktični dio završnog ispita iz predmeta “Web programiranje I"
 
 

## Zadatak 

### Kreirati jednostavnu web stranicu za igru „Kamenčići“. Pravila igre su sljedeća:

* Na raspolaganju je hrpa kamenčića.
* Igru igraju dva igrača.
* Svaki igrač u svom potezu bira koliko će kamenčića baciti u vodu.
* U svakom potezu, igrač mora baciti bar jedan kamenčić, te ne smije baciti više od pola kamenčića (dakle, smije uzeti pola, ali ne više).
* Gubi igrač koji ostane bez poteza. Igrač ostaje bez poteza kada na hrpi ostane tačno jedan kamenčić. <br>

### Stranica se sastoji od:

* jednostavnog tekstualnog prikaza broja kamenčića koji su na raspolaganju 
* input polja za unos broja kamenčića koje igrač želi skloniti sa hrpe 
* dugmića kojim igrač potvrđuje potez 
* tekstualnog prikaza koji igrač je na potezu
 

### Detaljnije specifikacije, tok igre i napomene. 

* Svi elementi na stranici su centrirani. Input polje i dugmić se nalaze u jednoj liniji.
* Padding i margine za svaki element na stranici su podešene na 10px.
* Početni broj kamenčića je slučajan prirodan broj između 10 i 25.
* Nakon unosa svakog poteza, mijenja se tekstualni prikaz o broju kamenčića, te podatak o tome koji igrač je na potezu.
* U slučaju neispravnog unosa, javlja se JavaScript alert sa prikladnom porukom.
* Na kraju igre, čitava stranica mijenja boju podloge, input polje i dugmić se blokiraju, te se umjesto broja kamenčića, prikazuje poruka o pobjedniku. Osim toga, u Bootstrap alertu se prikazuje lista svih poteza koji su vodili kraju partije. 


## Preview


https://user-images.githubusercontent.com/59321839/153957027-8563238e-0086-4ef2-a908-3244754eb89e.mp4




