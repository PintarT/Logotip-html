# Volkswagen – spletna stran in SVG logotip

Preprosta spletna stran, navdihnjena z vizualno podobo znamke Volkswagen. Projekt vsebuje osnovno HTML-stran in samostojno datoteko z vektorskim logotipom, katerega oblike so narisane s kubičnimi Bézierjevimi krivuljami.

> Projekt je ljubiteljski oziroma učni prikaz in ni uradna spletna stran Volkswagna. Volkswagen in njegov logotip sta zaščiteni znamki.

## Vsebina projekta

- `logotip-html/indeks.html` – osnovna HTML-stran z naslovom »Volkswagen«.
- `volkswagenPath.svg` – SVG-risba logotipa. Krivulje so zapisane z ukazom `C` za kubično Bézierjevo krivuljo v podatkih SVG `path`.

## Zagon

Projekt ne potrebuje namestitve ali dodatnih knjižnic. Odpri datoteko `logotip-html/indeks.html` v spletnem brskalniku.

Če želiš prikazati SVG na strani, ga lahko na primer vključiš tako:

```html
<img src="../volkswagenPath.svg" alt="Vektorski logotip Volkswagen">
```

Pot je relativna glede na datoteko `logotip-html/indeks.html`.

## Tehnologije

- HTML
- SVG
- Kubične Bézierjeve krivulje (`C` v SVG `path`)

## Opomba o Bézierjevih krivuljah

SVG uporablja ukaze za risanje poti; v tej datoteki je `C` ukaz za kubično Bézierjevo krivuljo. To ni JavaScriptova metoda `CanvasRenderingContext2D.bezierCurveTo()`, čeprav oba načina opisujeta kubične Bézierjeve krivulje.
