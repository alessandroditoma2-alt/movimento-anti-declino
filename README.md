# Movimento Anti-Declino — sito

Sito statico pronto per GitHub Pages.

## File
- `index.html` — homepage
- `style.css` — identità visuale MAD
- `charts.js` — grafici Chart.js
- `assets/logo-mad.png` — logo

## Dati presenti
- PIL reale pro capite: Eurostat `sdg_08_10`; il grafico usa 2017–2025 e indicizza le due serie a 2017=100.
- R&S: Eurostat `rd_e_gerdtot`, 2024.
- Laureati 20–34: ISTAT, *Giovani e mercato del lavoro — 2024* (Italia 25,1%; divario UE -11,3 p.p.).
- Produttività: il sito segnala esplicitamente il break nella serie italiana Eurostat `tesem160 / nama_10_lp_ulc`; non viene costruita una falsa serie continua.

Nota: per uso pubblico stabile conviene sostituire il CDN Chart.js con una copia locale e automatizzare l'aggiornamento dei dati via R/JSON.
