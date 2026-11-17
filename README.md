# NorthStar Cloud & Network Solutions website

A small static website: plain HTML and one CSS file, with no build step, no scripts, no trackers, and no contact form. The planned address is `northstar.jubriladams.com` (see the `CNAME` file).

This branch is a draft for review. It has not been deployed.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Home |
| `services.html` | Services, planned or offered status, scope and fees statement |
| `about.html` | Purpose, principles, how requests are handled |
| `approach.html` | Working method, skills and training, learning labs |
| `contact.html` | Current contact method (call and WhatsApp, same number) |
| `styles.css` | Shared styles, light and dark mode |
| `assets/` | Logo files (`northstar-logo.svg`, `northstar-mark.svg`) |
| `robots.txt`, `sitemap.xml` | Search engine files for the planned address |
| `CNAME` | Existing file naming the planned custom domain |

## Preview locally

1. Download or clone this branch.
2. Open `index.html` in a browser. All links are relative, so the pages work straight from the folder.
3. Or run a local server from the folder: `python3 -m http.server 8000`, then visit `http://localhost:8000`.

## Deploy (do these only when you are ready)

1. Review the confirmation list below and confirm or leave out each item.
2. Merge the `site-update` branch into `main`. Note that if GitHub Pages is already set to deploy from `main`, merging publishes the site.
3. In the repository, open Settings, then Pages. Set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Confirm the custom domain `northstar.jubriladams.com` is set, then tick Enforce HTTPS once the certificate is ready.
5. In DNS, add a `CNAME` record for `northstar` pointing to `Jubriladams78.github.io`. Do this only when you decide to go live.

## How to edit

Edit the HTML files directly. To mark a planned service as offered, change its `Planned` label to `Offered` on `services.html` and on its card in `index.html`, and change the "Planned focus" heading in its section on `services.html` to "What this includes". Also revisit the Home page introduction and the page descriptions, which currently say IT support and troubleshooting is the only current offering.

To add customer types or a remote support statement after you confirm them, add a short section to `services.html`. Nothing about either is published now.

## Still awaiting your confirmation

None of these appear on the site. Each is left out until you confirm it.

- Customer types (the audience).
- Remote support availability.
- Which planned services are ready to offer: network setup and support, Azure and AWS cloud support, Linux and Windows system administration, Linux server administration, Windows Server and identity administration.
- Business hours.
- Pricing approach and rates. The site says only that scope, timing, and fees are discussed and agreed before work begins.
- Any guarantees, response times, supported systems, or emergency coverage.
- Whether to keep a phone number as the contact method, or add a separate business number or email later. The site calls the number a current contact method and does not describe it as a separate business line.
- Whether to keep the planned address, which contains a personal name and so links the brand to the owner's domain.

## Privacy and accuracy rules this site follows

- No personal email, home address, résumé, LinkedIn, or personal GitHub profile.
- The only personal details shown are the contact phone number and "Based in the Greater Chicago Area".
- Coursework, simulations, bootcamp work, and home labs are labeled as learning examples, never as client work.
- No testimonials, client logos, case studies, guarantees, response times, partnerships, years of experience, or registration details.
- A warning on the Services and Contact pages tells visitors not to send passwords, account numbers, or private files in a first message.
