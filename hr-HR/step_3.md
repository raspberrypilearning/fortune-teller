## Donošenje odluke

Donosimo vaš mikro: bit za donošenje odluke nasumičnim odabirom broja (`0` za 'Ne' i `1` za 'Da').

+ Dodajte novi `na gumbu Pritisnuti` događaj u svoj kôd.

![screenshot](images/fortune-on-a-pressed.png)

+ Kreirajmo novu varijablu za pohranjivanje odgovora. Kliknite "Varijable", a zatim kliknite "Uradi varijablu".

![screenshot](images/fortune-variables.png)

+ Imenujte novu varijablu koja se zove `odgovor`.

![screenshot](images/fortune-answer.png)

+ Povucite blok `skupa` iz varijable u svoj gumb `on Pritisnite pritisnuti` blok i odaberite varijablu `odgovora`.

![snimka zaslona](images/fortune-set.png)

Kao što vidite, `do` u bloku znači da možete postaviti odgovor na prikaz.

+ Kliknite „Math” i povucite `pokupiti slučajan` blok nakon `kako bi`:

![screenshot](images/fortune-random.png)

+ Recite slučajnom bloku da odaberete broj između 0 i 1. Ovako bi tvoj kôd trebao izgledati:

![screenshot](images/fortune-random-1.png)

+ Zatim želite prikazati riječ `No` na mikro: malo samo `ako` `odgovor` 0.

Da biste to učinili, povucite `ako` blok na dnu `na tipku A pritisne` događaj:

![screenshot](images/fortune-if.png)

+ Zatim povucite blok `=` kao uvjet u `ako je`:

![screenshot](images/fortune-equals.png)

+ Povucite varijablu `odgovor` na lijevu stranu bloka `ako`.

![screenshot](images/fortune-if-finished.png)

+ Bilo koji kôd unutar `ako je` blok pokrenut će se samo ako je `odgovora` 0. Kako je `Ne`, dodamo blok `prikazivanja`.

![screenshot](images/fortune-no.png)

+ Testiraj svoj kôd. 
    + Ponekad će `odgovor` biti 0, a mikro: bit treba reći „Ne“.
    + Ponekad `odgovor` će biti 1, a ništa se neće dogoditi!