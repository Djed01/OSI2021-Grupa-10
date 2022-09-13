# OSI2021-Grupa-10
### Projektni zadatak iz *Osnova softverskog inženjerstva*

Projekat se sastoji od:

1. definisanje zahtjeva i izrada prateće dokumentacije,
2. dizajn sistema,
3. implementacija sistema,
4. testiranje softvera,
5. isporuka softvera, dokumentacije i korisničkog uputstva.

TEMA PROJEKTNOG ZADATKA:

Implementirati jednostavnu aplikaciju za rad aerodroma. Radnici treba da imaju mogućnost prijave na sistem unosom korisničkog imena i lozinke, a podaci o registrovanim korisnicima se čuvaju u binarnoj datoteci u sklopu aplikacije.

Kada se prijave na sistem, korisnici mogu koristiti različite opcije, u zavisnosti od vrste naloga koje imaju. Potrebno je realizovati četiri vrste korisničkih naloga: operater, kontrolor, šef i administrator.

Nalog za operatere omogućava da se pregledaju sve dobijene rezervacije letova od klijenata. Ovaj dio se može pojednostaviti tako što će se rezervacije nalaziti u nekom folderu, pri čemu ih program automatski čita i prikazuje u aplikaciji (spisak), a operater može otvoriti neku rezervaciju i zatim je odobriti ili otkazati. Validnost podataka (postojanje leta i slobodnih mjesta) se radi automatski i operater vidi rezultat tih provjera. Operater može vidjeti spisak svih odobrenih i odbijenih rezervacija. Fajlovi za rezervaciju se kreiraju ručno izvan ovog sistema. Ime i prezime operatera se čuva u svakoj obrađenoj rezervaciji.

Nalog za kontolore omogućava kreiranje novih letova, pravljenje rasporeda letova (u sklopu kreiranja), mijenjanje statusa leta (sletio, poletio, leti), pregled informacija o svakom letu (od - do, vrijeme, opis, broj mjesta, broj trenutno slobodnih mjesta) i otkazivanje leta. Svi podaci se čuvaju u tekstualnim fajlovima na fajl sistemu. Prilikom otkazivanja leta sve rezervacije za taj let se automatski brišu.

Nalog za šefove omogućava pregled izvještaja o završenim letovima na dnevnom, sedmičnom i mjesečnom nivou. Pored toga, šefovi vide i sve rezervacije, ali ih ne mogu mijenjati.

Naloge svih zaposlenih kreiraju/brišu administratori. Nalozi se mogu privremeno suspendovati, pri čemu se ne brišu već se korisnici ne mogu prijaviti na sistem. U sistemu postoje najviše 2 administratora i 3 šefa.

Grupa 10:

Gordan Letić

Novica Tepić

Darijo Prerad

Siniša Radeta

Zoran Jeftenić
