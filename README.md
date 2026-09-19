# Sbírka zajímavostí — PWA (frontend)

## Než nahraješ

V `index.html` uprav dva řádky (najdeš je pod komentářem "Uprav před
nahráním"):

```js
const BACKEND_URL = "https://TVUJ-PROJEKT.vercel.app/api/summarize";
const APP_SECRET = "tvoje-heslo-sem";
```

Vlož adresu svého Vercel backendu a stejné heslo, jaké jsi dal do
`APP_SECRET` na Vercelu.

## Nahrání na GitHub Pages

Stejný postup, jaký už znáš z ostatních appek:

1. Nahraj `index.html`, `manifest.json`, `sw.js`, `icon-192.png`,
   `icon-512.png` do GitHub repa.
2. V repu: Settings → Pages → zdroj nastav na hlavní větev.
3. Appku otevři na telefonu na dané adrese a přidej na plochu
   ("Přidat na plochu" / "Nainstalovat appku").

## Jak se používá

- **Sdílení z Instagramu/Facebooku:** v appce IG/FB klikni Sdílet →
  vyber "Sbírka zajímavostí" → appka se otevře a sama video zpracuje.
- **Ruční vložení:** záložka 📥 Přidat → vlož odkaz → Zpracovat.
- **Sbírka:** záložka 🗂️ Sbírka — seznam všech zpracovaných videí s
  body/tipy, hledání, mazání, u chyby tlačítko Zkusit znovu.

Vše se ukládá jen v appce na telefonu (localStorage) — nikam jinam se
neposílá, kromě samotného odkazu, který jde na tvůj backend ke zpracování.
