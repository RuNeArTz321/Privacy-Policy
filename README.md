# Coding Ibex — website

Public site for Coding Ibex, hosting the studio landing page and the privacy policy
required by the Google Play Console.

## Pages

| File | Purpose |
|---|---|
| `index.html` | Studio landing page |
| `privacy-policy.html` | Privacy policy for our games (STAX, `com.codeibex.stax`) |
| `style.css` | Shared styles. All artwork is inline SVG — no image files to host. |

Plain static HTML/CSS. No build step, no dependencies. Open `index.html` locally to preview.

## Hosting

Served with GitHub Pages from the `main` branch, root folder.

Live URLs:

- Home: `https://runeartz321.github.io/Privacy-Policy/`
- Privacy policy: `https://runeartz321.github.io/Privacy-Policy/privacy-policy.html`

The privacy policy URL is the one submitted to the Google Play Console
(App content → Privacy policy).

## Updating

Edit the HTML and push to `main` — GitHub Pages redeploys automatically, usually within a minute.
Remember to update the "Last updated" date at the top of `privacy-policy.html` whenever the
policy changes.
