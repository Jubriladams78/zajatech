# ZajaTech Solutions website

Static website (HTML and CSS, no JavaScript, no forms, no trackers) for ZajaTech Solutions.

## Files
- `index.html`, `services.html`, `about.html`, `approach.html`, `contact.html`: the five pages
- `styles.css`: all styling (navy, teal, gold; light and dark mode)
- `assets/zajatech-mark.svg`: the Z mark used in the header (editable SVG)
- `assets/zajatech-logo.svg`: full logo lockup used on the home page (editable SVG)
- `assets/zajatech-favicon.svg`: browser tab icon
- `robots.txt`
- `CNAME`: custom domain file for GitHub Pages. It still holds the old `northstar.jubriladams.com` value on purpose. Do not edit it until zajatech.com is ready.

## Preview locally
Open `index.html` in a browser, or run `python3 -m http.server 8000` and visit http://localhost:8000.

## Deployment
Unchanged. This work lives on the `site-update` branch. Nothing deploys until it is merged into `main`.

## Connecting zajatech.com (not done yet)
1. Buy or confirm ownership of zajatech.com.
2. At the DNS provider, add the GitHub Pages records: A records 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; optional AAAA records 2606:50c0:8000::153 through 2606:50c0:8003::153; and a CNAME for `www` pointing to `Jubriladams78.github.io`. Use DNS only (not proxied) while GitHub issues the certificate.
3. Change the `CNAME` file to `zajatech.com`, merge `site-update` into `main`, and set the custom domain under Settings, Pages.
4. Turn on Enforce HTTPS once the certificate is issued.
5. Then add canonical and og:url tags and a sitemap, which were left out because the domain is not live.
6. Remove the old northstar.jubriladams.com DNS record.
7. Optional: rename this repository from `northstar` to match the new brand.

## Details still to confirm (not shown on the site)
Hours, pricing approach, response times and guarantees, supported systems and limits, contractor screening, a business email address, a separate business phone, and customer evidence.

## Privacy rules
No personal name, home address, personal email, résumé, LinkedIn, or personal GitHub on the site. Labs are learning examples, never client work.
