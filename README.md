# Weekend nel Tigullio

Landing page statica per un weekend tra trekking e relax. Non richiede build o dipendenze; il gate-gioco iniziale usa JavaScript. Per copiarla su GitHub Pages, mantieni `index.html` e la cartella `assets/` nella stessa struttura.

## Ingresso-gioco

La schermata iniziale chiede una password e apre la proposta solo con una di queste tre stringhe esatte: `Francesca`, `francesca`, `FRANCESCA`. Il controllo è client-side, pensato come piccolo gioco e non come protezione di contenuti: il codice e le password si possono leggere nel sorgente e GitHub Pages resta pubblico. JavaScript deve essere attivo nel browser. La schermata non salva l’accesso, quindi ricompare a ogni ricarica.

## Indicizzazione e accesso

`index.html` invia ai crawler i meta tag `noindex,nofollow` (oltre a `noarchive`, `nosnippet` e `noimageindex`). Sono direttive ai motori di ricerca, non una password né una garanzia assoluta contro l’indicizzazione; GitHub Pages rende il sito pubblicamente raggiungibile tramite il suo URL.

## Crediti fotografici

- `assets/santa-margherita.jpg`: **Andrzej Otrębski**, Wikimedia Commons, [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
- `assets/rapallo-castello.jpg`: **Dapa19**, Wikimedia Commons, [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); immagine ridimensionata per il web.
- `assets/zoagli-panorama.jpg`: **patano**, Wikimedia Commons, [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/); immagine ridimensionata per il web.

La pagina contiene i crediti e i link alle fonti e alle licenze; mantienili se redistribuisci le immagini.

## Mappa

La mappa della tappa è incorporata da Google My Maps in un iframe e viene caricata quando il visitatore raggiunge la sezione. La sua visualizzazione dipende anche dalle impostazioni di condivisione della mappa e dalla disponibilità del servizio Google.
