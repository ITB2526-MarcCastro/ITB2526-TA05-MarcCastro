· Pàgina personal — README

Aquest repositori conté la pàgina web personal (portafolis / projectes).

· Resum

Web estàtica amb HTML, CSS i JavaScript.
Mode fosc forçat per defecte.
Barra arrossegable per tornar a dalt.
Joc de partícules (punts i línies) amb efecte de brillant i color groc.
Formulari de contacte amb validació bàsica.
Pàgina de detall de projecte (PW2.html) amb reproducció de vídeo des d'URL extern (YouTube / Google Drive / mp4).3
· Estructura de fitxers

index.html — pàgina d'inici (si existeix).
llistat.html — llistat de projectes.
contacte.html — pàgina de contacte amb formulari.
PW2.html — pàgina de detall de projecte (vídeo + imatges).
style.css — full d'estils principal.
script.js — JavaScript amb funcionalitats:
barra draggable (volver arriba),
partícules visuals,
validació de formulari,
temporitzador de temps a la pàgina.
Mitjans opcionals: Gravedad.mov, Manzana.png, Newton.png.
· Gestionar el vídeo del projecte (PW2.html) S'ha inclòs un script a PW2.html que detecta la URL i:

Inserta un iframe per a YouTube.
Inserta l'iframe de preview per a Google Drive.
Inserta un <video controls> per a enllaços MP4/WebM i afegeix un botó per obrir-lo en nova pestanya.
· Estils i colors principals

Groc per punts/partícules i llistats: #ffd100.
Vermell d'accent i botons: #ff3b3b.
El botó "Enviar missatge" del formulari ja està estilitzat en vermell a style.css.
· Formulari de contacte

Validació client bàsica inclosa:
Nom no buit.
Correu amb format bàsic.
Actualment el formulari fa action="#" (no envia a servidor). Per enviar dades realment s'ha d'integrar amb:
Formspree, Netlify Forms, o un endpoint propi (s'adaptarà action o s'afegirà fetch() al script.js).