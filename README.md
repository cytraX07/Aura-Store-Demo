# AURA — Store Prototype Demo

Mobile-first e-commerce UI prototype for **Affan Raza** (Affan Web), featuring
instant WhatsApp ordering and responsive design.

## Live demo

Open the live site in any browser (mobile or desktop):

**👉 https://cytrax07.github.io/Aura-Store-Demo/**

> ⚠️ The link is live as soon as GitHub Pages is enabled (one-time, 30 seconds —
> see below). It is generated from this branch, so the demo you see here is served
> straight from this repo.

### Enable the live link (one-time, by repo owner)

The Pages site could not be turned on from the automation token (403 — integration
lacks Pages permission). Enable it once from the repo UI:

1. https://github.com/cytraX07/Aura-Store-Demo/settings/pages
2. **Source**: Deploy from a branch
3. **Branch**: `arena/16c5ae11-aura-store-demo` · **Folder**: `/ (root)`
4. **Save** — GitHub builds the site in ~1 minute and the client link activates.

It needs no internet connection beyond this link — it is a single self-contained
`index.html` (inline CSS/JS, images embedded), so the demo works exactly the
same for the client.

## What's inside

| File | Description |
| --- | --- |
| `index.html` | The clickable store demo — product listing, live search, filters, cart with free-shipping bar, validated checkout and WhatsApp ordering. |
| `01_Proposal_and_Scope_Shopify_Store.docx` | Full proposal: scope, 5 phases, timeline, USD 700 budget break-up, milestones. |
| `README_FIRST.txt` | Client-facing package guide: what's inside, how to explore the demo. |
| `preview/` | 5 quick preview screenshots (mobile home / listing / cart / checkout / desktop home). |

## How the client should use it

1. Open the live link on a phone and on a laptop.
2. Try the product listing (search, filters, sort, quick view).
3. Build a cart, watch the free-shipping progress bar, then complete the checkout.
4. Use the WhatsApp button (bottom right) — the order message is pre-filled with items and total.
5. Use the "Demo settings" link in the footer to preview the WhatsApp message with your own number.

> ⚠️ Demo mode only — no real payment is taken and no order is stored. Product
> names, prices, images and the WhatsApp number are placeholders.

## Local preview (optional)

Open `index.html` in any browser, or serve the folder:

```bash
npx serve .        # or: python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Source

Package received from the designer's Drive package
`AURA_Shopify_Store_Affan_Raza_Package.zip` (22 Nov 2026).
