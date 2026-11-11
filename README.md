# LIMEN Brand Kit

Loghi, colori e font di LIMEN, pronti da incollare in qualsiasi sito (Lovable, Webflow, Framer, Carrd, HTML).

Anteprima visiva: apri `index.html`.

## 1. Incolla questo nel `<head>` del sito

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Scanzifarm/limen-brand-kit@main/limen-brand.css">
```

Carica il font Manrope e tutti i colori come variabili CSS. Poi puoi usare:

```html
<section class="limen-dark">
  <h1 class="limen-headline">Gestire l'affitto, <span class="limen-accent">senza caos.</span></h1>
  <a class="limen-button" href="https://limen.rent/validazione-problema">Fai il questionario</a>
</section>
```

Oppure nel tuo CSS: `color: var(--limen-yellow); font-family: var(--limen-font);`

## 2. Loghi

| File | Quando usarlo | Link diretto |
| --- | --- | --- |
| `logos/limen-wordmark-black.svg` | Su sfondi chiari | `https://cdn.jsdelivr.net/gh/Scanzifarm/limen-brand-kit@main/logos/limen-wordmark-black.svg` |
| `logos/limen-wordmark-white.svg` | Su sfondi scuri | `https://cdn.jsdelivr.net/gh/Scanzifarm/limen-brand-kit@main/logos/limen-wordmark-white.svg` |
| `logos/limen-mark-black.svg` | Simbolo "L", su chiaro | `https://cdn.jsdelivr.net/gh/Scanzifarm/limen-brand-kit@main/logos/limen-mark-black.svg` |
| `logos/limen-mark-white.svg` | Simbolo "L", su scuro | `https://cdn.jsdelivr.net/gh/Scanzifarm/limen-brand-kit@main/logos/limen-mark-white.svg` |
| `icons/pwa-icon.svg` / `.png` | Icona app, avatar social | `https://cdn.jsdelivr.net/gh/Scanzifarm/limen-brand-kit@main/icons/pwa-icon-512.png` |
| `icons/favicon.ico` | Favicon | `https://cdn.jsdelivr.net/gh/Scanzifarm/limen-brand-kit@main/icons/favicon.ico` |

```html
<img src="https://cdn.jsdelivr.net/gh/Scanzifarm/limen-brand-kit@main/logos/limen-wordmark-white.svg" alt="LIMEN" height="32">
```

Regole: usa sempre questi file originali (da `limen-connect/public/`). Non riscrivere il logo con un font, non deformarlo, non ricolorarlo con altri colori. Le versioni bianche sono solo l'inversione dei file originali.

## 3. Colori

### Marketing, social, landing

| Variabile | HEX | Uso |
| --- | --- | --- |
| `--limen-black` | `#081011` | Sfondi premium |
| `--limen-yellow` | `#F2C94C` | Headline, hook, CTA |
| `--limen-mint` | `#C8FFDC` | Messaggi positivi, enfasi |
| `--limen-white` | `#FFFFFF` | Testi su scuro |
| `--limen-ink` | `#151515` | Testi su chiaro |
| `--limen-paper` | `#F5F3EB` | Fondo chiaro editoriale (opzionale) |

### App (non mescolare con la palette marketing)

| Variabile | Valore | Uso |
| --- | --- | --- |
| `--limen-app-black` | `#090B0D` | Identità di prodotto |
| `--limen-app-ice` | `#EEF2F4` | Fondi secondari |
| `--limen-app-success` | `oklch(0.72 0.15 160)` | Esito positivo |
| `--limen-app-alert` | `oklch(0.6 0.19 25)` | Ritardi, anomalie |
| `--limen-app-action` | `oklch(0.79 0.16 72)` | Serve agire |
| `--limen-app-verify` | `oklch(0.58 0.05 250)` | Da verificare |
| `--limen-app-protect` | `oklch(0.72 0.12 88)` | Solo LIMEN Protect |

Tutti i valori anche in `tokens.json` (per Figma, Canva o altri tool).

## 4. Font

**Manrope** (Google Fonts, gratuito). Pesi: 400, 500, 600, 700, 800. Headline in 800, testo in 500.

## Da decidere

Le bozze editoriali usano anche un verde scuro (`#163D32` / `#173B2F`). Non è ancora definitivo, quindi non è nel kit.

## Aggiornare

Modifica i file e fai push su `main`. jsDelivr aggiorna la cache entro circa 12 ore; per forzarlo subito visita `https://purge.jsdelivr.net/gh/Scanzifarm/limen-brand-kit@main/limen-brand.css`.
