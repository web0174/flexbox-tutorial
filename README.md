# Tutorial interattivo Flexbox

## Come Funziona Questa Pagina:

### Struttura HTML:

La pagina è divisa in due sezioni principali: un pannello di controllo a sinistra e un'area di visualizzazione a destra.

Il pannello di controllo contiene menu a tendina (<select>) per ogni proprietà Flexbox del contenitore (flex-direction, justify-content, align-items, flex-wrap, e gap).

Sono presenti anche pulsanti per aggiungere o rimuovere dinamicamente elementi dal contenitore, permettendo di testare layout con una, due, tre o più colonne/righe.

## Stile con Tailwind CSS:

La pagina stessa è stilizzata utilizzando Tailwind CSS, incluso tramite CDN per semplicità. Questo rende l'interfaccia pulita e moderna.

Le classi di Tailwind vengono applicate dinamicamente al contenitore del playground tramite JavaScript per riflettere le selezioni dell'utente.

Interattività con JavaScript:

Uno script JavaScript gestisce tutti gli eventi.

Quando modifichi una proprietà Flexbox dai menu a tendina, lo script aggiorna le classi Tailwind del contenitore del playground.

L'area del codice viene aggiornata in tempo reale per mostrare il tag <div> con le classi Tailwind CSS corrispondenti.

I pulsanti "+" e "-" modificano il numero di elementi figli all'interno del contenitore, rigenerando sia la visualizzazione che il codice.

Un pulsante "Copia" consente di copiare facilmente il codice generato.

Questo strumento ti fornirà un ambiente pratico per comprendere a fondo le proprietà di Flexbox e come implementarle rapidamente utilizzando le utility di Tailwind CSS.

#### Credits: Google AI Studio
