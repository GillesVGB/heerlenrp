# Heerlen Roleplay · APV

Een statische, responsive APV-website met de branding van Heerlen Roleplay. De website staat in `dist/` en heeft geen buildstap of backend nodig. Upload de inhoud van `dist/` naar je webhosting of GitHub Pages.

## Inhoud en onderhoud

- `dist/content.js`: alle 65 APV-artikelen (1–62, plus 1A, 2A en 3A), 8 algemene regels, 9 Discord-regels en beide belangrijke mededelingen, plus 11 rijen in de strafcategorieëntabel.
- `dist/app.js`: zoeken, onderwerpen, strafcategoriefilter, bladwijzers, artikellinks, thema en navigatie.
- `dist/style.css`: kleuren, layout en responsive/print-stijlen.
- `dist/heerlen-logo.png`: het aangeleverde logo, ongewijzigd.
- Discord: https://discord.gg/heerlenrp

Artikelen worden bewaard in de lokale opslag van de browser. Ze worden niet tussen apparaten gesynchroniseerd. Afdrukken / PDF gebruikt het afdrukvenster van de browser en neemt de huidige sectie en filters mee.

## Lokaal openen

Open `dist/index.html` rechtstreeks in een browser, of serveer `dist/` met een statische webserver. Er zijn geen npm-afhankelijkheden. De optionele Google Fonts hebben lokale systeemfonts als fallback.

