# Heerlen Roleplay · APV

Een statische, responsive APV-website met de branding van Heerlen Roleplay. De website staat in `dist/` en heeft geen buildstap of backend nodig. Upload de inhoud van `dist/` naar je webhosting of GitHub Pages.

## Inhoud en onderhoud

- `dist/content.js`: alle 65 APV-artikelen (1–62, plus 1A, 2A en 3A), 8 algemene regels, 9 Discord-regels en beide belangrijke mededelingen, plus 11 rijen in de strafcategorieëntabel.
- `dist/app.js`: zoeken, onderwerpen, strafcategoriefilter, bladwijzers, artikellinks, thema en navigatie.
- `dist/style.css`: kleuren, layout en responsive/print-stijlen.
- `dist/heerlen-logo.png`: het aangeleverde logo, ongewijzigd.
- Discord: https://discord.gg/heerlenrp

Artikelen worden bewaard in de lokale opslag van de browser. Ze worden niet tussen apparaten gesynchroniseerd. Afdrukken / PDF gebruikt het afdrukvenster van de browser en neemt de huidige sectie en filters mee.

## Herkomst

De regelteksten komen uit `index.html` van https://github.com/GillesVGB/apv.amsterdamroleplay, opgehaald op 11 oktober 2026. Verwijzingen naar Amsterdam Roleplay zijn vervangen door Heerlen Roleplay. De regelinhoud, artikelnummers en sancties zijn verder behouden. De oude Amsterdam-uitnodigingslinks zijn vervangen door de door de gebruiker opgegeven Heerlen-link. Onderwerpen zijn toegevoegd als navigatiehulp.

De brontekst bevat verschillende strafduren in de categorieëntabel en in afzonderlijke artikelen. Bijvoorbeeld: categorie 3 is in de tabel 50 taken, maar artikel 6 vermeldt een ban van 24–72 uur. Ook noemt artikel 27 alleen Nederlands, terwijl de algemene communicatieregel Nederlands en Engels toestaat. Deze verschillen zijn niet stilzwijgend aangepast; het bestuur kan ze inhoudelijk oplossen in `content.js`.

## Lokaal openen

Open `dist/index.html` rechtstreeks in een browser, of serveer `dist/` met een statische webserver. Er zijn geen npm-afhankelijkheden. De optionele Google Fonts hebben lokale systeemfonts als fallback.

