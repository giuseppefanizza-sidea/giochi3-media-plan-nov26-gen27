# Piano Media villabebegiokids.it · Novembre 2026 / Gennaio 2027

Deck di presentazione del piano media per Giochi3, 22 slide.

## Il contenuto è cifrato

`index.html` non contiene il deck in chiaro: contiene una pagina di sblocco e il deck
cifrato con **AES-GCM 256 bit**, chiave derivata dalla password con **PBKDF2-SHA256 a
600.000 iterazioni**. La decifratura avviene nel browser di chi conosce la password.
Senza password la pagina restituisce solo dati illeggibili.

La password non è in questo repository e non va mai messa qui. Viaggia separatamente dal link.

## Perché il repository è pubblico

GitHub Pages sul piano gratuito pubblica solo da repository pubblici. La protezione del
contenuto è quindi affidata alla cifratura, non alla visibilità del repository. In più la
pagina è esclusa dai motori di ricerca con `robots.txt` e con il meta tag `noindex`.

## Aggiornare il deck

Il sorgente in chiaro vive nel workspace di agenzia, in
`CLIENTI/GIOCHI3/DIGITAL-STARTUP/01-Media-Strategy/Media-Plan-Nov2026-Gen2027/`.
Dopo ogni modifica il deck va ricifrato e `index.html` sostituito: non basta copiare il
file HTML, perché qui viene pubblicata solo la versione cifrata.
