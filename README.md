# MBO Tech Academy — onepager

Herontwerp van de wervingssite voor het MBO4 Mechatronica leerwerktraject bij Trioworld (Apeldoorn).

## Structuur
```
index.html      volledige pagina (HTML + CSS + JS in één bestand)
assets/         video's (testimonials, campagnevideo, hero-loop)
```
Foto's staan als base64 ingebakken in index.html, dus er zijn geen losse image-bestanden nodig.

## Lokaal bekijken
Open `index.html` gewoon in een browser. De video's in `assets/` moeten in dezelfde mapstructuur blijven staan, anders spelen ze niet af.

## Live zetten
Dit is een statische site: geen build-stap, geen server-side code. Vercel (of GitHub Pages) kan de repo direct serveren.

Huidig plan: hosten op `nieuw.mbotechacademy.com` als reviewomgeving, later verhuizen naar het hoofddomein zodra Gino akkoord geeft.

## Bijwerken
- **Handmatig:** vervang `index.html` via "Upload files" op GitHub. Vercel deployt automatisch binnen een halve minuut.
- **Met Claude Code:** koppel deze repo en geef feedback in gewone taal, Claude past de HTML aan en pusht.

## Openstaand
- WhatsApp/telefoonnummer van Sarah moet nog in de CTA's ("App met Sarah")
- Plekken-teller in de hero-badge ("Nog maar twee plekken beschikbaar!") moet actueel gehouden worden
