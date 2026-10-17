MEATBAG — meatbag.best
======================

STRUTTURA CARTELLA

  index.html          il sito
  404.html            pagina di errore
  favicon.svg         icona scheda
  robots.txt          istruzioni per Google
  sitemap.xml         mappa per Google
  CNAME               dominio (una riga: meatbag.best)
  .nojekyll           file vuoto, serve a GitHub Pages
  assets/
    hero.png          (opzionale, copre l'SVG)
    face.png
    g1.png
    g2.png
    g3.png
    g4.png

Le immagini in assets sono OPZIONALI: se non ci sono,
il sito mostra le illustrazioni SVG già dentro il file.
Se ci sono, le foto coprono l'SVG.


AGGIORNARE IL CONTRATTO IL GIORNO DEL LANCIO

1. apri index.html
2. cerca:   var CA = "";
3. incolla l'indirizzo tra le virgolette:
      var CA = "IL_TUO_INDIRIZZO_QUI";
4. salva, carica su GitHub
5. GitHub Pages impiega circa 1 minuto

Il campo passa da "non ancora" all'indirizzo
e il pulsante copia si attiva da solo.


CAMBIARE LA DATA DEL LANCIO

cerca:   var LAUNCH = "2026-10-20T15:30:00+01:00";
formato: AAAA-MM-GGThh:mm:ss+01:00   (+01:00 = ora UK estiva)


AGGIUNGERE UNA LINGUA

apri index.html, cerca:   var I18N={
ogni blocco (en, it, es...) è una lingua.
copia un blocco intero, rinominalo, traduci i valori.
poi aggiungi la sigla all'array LANGS.


BACKUP

tieni sempre una copia di index.html sul Mac.
se qualcosa si rompe, rimetti quella e sei tornato in un secondo.
