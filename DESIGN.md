# Design

## Direction

Biglietto da visita digitale con la spontaneità di un quaderno di laboratorio. Un potenziale cliente legge la pagina sul portatile in uno studio illuminato di giorno: il fondo chiaro mantiene la lettura naturale.

## Color

Strategia restrained: carta chiara, inchiostro caldo e arancio come accento. Colori definiti in OKLCH; niente gradienti o nero e bianco puri.

## Typography

Famiglia sans di sistema per caricamento immediato. Titolo grande, peso forte e spaziatura stretta; corpo arioso e larghezza di lettura contenuta.

## Layout

Pagina unica, intestazione leggera, saluto su due righe con un segno grafico originale a destra, presentazione e lista numerata delle attività. Contatto email in fondo. Su mobile tutti i contenuti seguono una sola colonna.

## Interaction

Link di navigazione ad ancore e contatto mailto. Focus esplicito, hover sobri, nessuna animazione automatica. Il segno grafico decorativo è nascosto alle tecnologie assistive.

## Implementation

HTML statico con Tailwind CSS tramite browser CDN. Nessuna configurazione o dipendenza locale; il caricamento di Tailwind richiede una connessione Internet. Per pubblicazioni con vincoli CSP o senza dipendenze runtime esterne, compilare Tailwind in un foglio CSS locale.
