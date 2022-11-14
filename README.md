# Group-Chat-Microservice
**Opis projekta**

U okviru projektnog zadatka realizovana je tema servisa grupnog četa, ideja projekta 
jeste da korisnik može da komunicira sa jednim ili više drugih korisnika putem kreiranja čet 
soba. Korisnik takođe može da izlista i pridruži se bilo kojoj javnoj čet sobi u kojoj se već ne 
nalazi. Za izradu korišćen je jednostavan html/css/js frontend za bolji prikaz funkcionalnosti. 
Biblioteka SignalR za live obradu poruka bez potrebe refreshovanja stranice.
Group Chat Service
Ovaj mikroservis omogućava direktnu komunikaciju između dva ili više korisnika putem soba. 
Korisnik ima mogućnost da kreira javnu ili privatnu sobu. U javnu sobu može ući bilo koji 
korisnik, a u privatnu samo korisnik kom je izabran od strane pošiljaoca. Nakon ulaska u javnu 
sobu korisnik ima uvid u sve poruke u toj sobi pre njegovog ulaska. Svaki korisnik može da 
otvori listu ostalih korisnika ovog servisa kako bi inicirao čet u privatnoj sobi.
