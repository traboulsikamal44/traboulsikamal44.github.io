# Serenza — public pages

Public GitHub Pages site for Serenza, a trading name of Wycliffe Partners Limited
(registered in England and Wales, company number 17268600).

## gemstone-cascade/

The public web pages for **Gemstone Rhapsody**:

| File | Purpose |
|---|---|
| `index.html` | Marketing landing page. This is the **Marketing URL** filed in App Store Connect — if it 404s, a reviewer sees a broken link. |
| `privacy-policy.html` | The **Privacy Policy URL** filed in App Store Connect. |
| `terms.html` | Terms & Conditions. |
| `support.html` | The **Support URL** filed in App Store Connect. |

**Do not move or rename these files.** The iOS app and the App Store listing
point at these exact URLs.

## Naming

Two names, two jobs, and they are not interchangeable:

- **Serenza** — the studio byline. "Developed and published by Serenza."
- **Wycliffe Partners Limited** — the legal entity. Copyright, licence grant,
  liability, registered office.

Every legal page carries the tie: *Serenza is a trading name of Wycliffe
Partners Limited.* "Ludicrous Studio" was a working-directory folder name and
appears nowhere.

## Keeping this in step with the app

The private `gemstone-cascade` repo holds the app. When page copy changes for a
reason that also touches the app — a policy change, an entity change, a claim
about what purchases do — **change both**, and treat this repo as what the
public actually sees.

Nothing here is served from the private repo. **Editing there changes nothing a
visitor sees until it is committed here.** That drift is what left this site
serving July content five weeks after it changed.
