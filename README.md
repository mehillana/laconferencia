# La Conferència

L'actualitat política desmuntada amb Etienne González.

Webcòmic satíric en català pensat per publicar-se de manera senzilla a **GitHub Pages**, amb capçalera amb `portada.jpg`, navegació tira a tira, peu amb `copyright.png` i nomenclatura ja preparada per als pròxims 25 còmics.

## Descripció curta per a GitHub Pages

> **La Conferència** — L'actualitat política desmuntada amb Etienne González. Webcòmic satíric en català amb lector tira a tira i llista preparada per a 35 còmics.

## De què va la web

La pàgina (`index.html`) funciona sense dependències complexes ni servidors:
- **Inici (`portada.jpg`)**: mostra la portada a dalt de tot, seguida del títol, els botons *Anterior* i *Següent* (i les fletxes del teclat) i el comptador de tires.
- **Lector minimalista**: mostra el títol de la tira i la imatge sola, sense marcs ni adorns. Si un fitxer encara no s'ha pujat al repositori, mostra el nom del fitxer en text pla.
- **Peu (`copyright.png`)**: tanca la pàgina amb la imatge de copyright i llicència *Etiennev1Atribució-DefinitivamentAtribucióFideuà* (amb text de llicència de reserva si falta la imatge).

## De què va cada tira (1 a 10)

1. **En campanya** (`Ilustración.jpg`) — La sensació de saturació constant d'eslògans i dies de campanya electoral que es superposen fins a fer preguntar quan s'acaba tot plegat.
2. **Publicitat (massa) convincent** (`Ilustración2.jpg`) — Un mapa d'eslògans polítics genèrics i prefabricats («el canvi necessari», «la força de la gent», «és sentit comú», «Catalunya al centre»...) desmuntats amb ironia.
3. **Rufián no és més guapo que Etienne González** (`Ilustración3.jpg`) — Una sortida de to purament estètica i absurdament competitiva comparant la imatge de Gabriel Rufián amb la del propi Etienne González.
4. **Sí, definitivament ÉS el consumisme** (`Ilustración4.jpg`) — Paròdia del cinisme electoral i del soroll de consignes en què el vot es redueix a qui pagui el Suchard negre, entremig de crits i tòpics encreuats.
5. **Processos i processos** (`Ilustración5.jpg`) — Ironia sobre la lentitud judicial i els llargs anys de processos polítics vinculats a l'1-O i l'amnistia de Carles Puigdemont.
6. **Vaga general!** (`Ilustración6.jpg`) — Una classe sobre els motius d'una vaga general il·lustrada amb un tren de Rodalies, barrejant la crítica al servei amb el contrast de qui ha aconseguit arribar-hi.
7. **Institut d'Estudis Merdes** (`Ilustración7.jpg`) — Un fals diccionari polític que «tradueix» el que diuen els polítics («ho estudiarem», «mesura històrica i revolucionària», «ajudes als serveis públics», «més autonomia») pel seu significat real segons la tira.
8. **Aquest Google podria no ser Google** (`Ilustración8.jpg`) — Una pàgina de resultats de cerca paròdica i caòtica sobre «Espanya» i «Catalunya», plena de comentaris sarcàstics, mapes, vídeos i «coses a fer» com trobar pis o treballar més que els burros.
9. **Carnestoltes** (`Ilustración9.jpg`) — Una disfressa de Carnestoltes de «polític corrupte» que provoca l'espant de Queco.
10. **Nàusees** (`Ilustración10.jpg`) — L'empatx i les nàusees provocades per l'acumulació de cartells, anuncis, convocatòries i continguts generats amb IA a les xarxes i als carrers.

## Fitxers del repositori

* `index.html`
* `portada.jpg`
* `copyright.png`
* `Ilustración.jpg` (Tira 1)
* `Ilustración2.jpg` (Tira 2)
* `Ilustración3.jpg` (Tira 3)
* `Ilustración4.jpg` (Tira 4)
* `Ilustración5.jpg` (Tira 5)
* `Ilustración6.jpg` (Tira 6)
* `Ilustración7.jpg` (Tira 7)
* `Ilustración8.jpg` (Tira 8)
* `Ilustración9.jpg` (Tira 9)
* `Ilustración10.jpg` (Tira 10)

### Pròxims 25 còmics (noms de fitxers reservats a `index.html`)

De la tira 11 a la tira 35, els fitxers ja estan preparats a l'array `FILENAMES` de `index.html` amb aquests noms:
* `Ilustración11.jpg` a `Ilustración35.jpg`

## Publicar a GitHub Pages

1. Puja `index.html`, `portada.jpg`, `copyright.png` i les imatges `Ilustración*.jpg` a l'arrel del repositori a GitHub.
2. Ves a **Settings > Pages**.
3. A **Build and deployment**, selecciona la branca principal (`main`) i la carpeta `/ (root)` i desa els canvis.
4. Quan vagis fent noves tires, puja els fitxers `Ilustración11.jpg`, `Ilustración12.jpg`, etc., i, si vols, posa'ls un títol a l'objecte `KNOWN_TITLES` dins de `index.html`.
