# Search to Pro · Norton 360 (Growth Audit volume 2: Apple Ads keyword flows)

The five ranked ideas from volume 1, plus two versions of Norton 360's onboarding and plan picker side by side: one for people who searched "scam protection" on the App Store, one for people who searched "vpn".

**→ https://bterzic123.github.io/norton-flow-rebuild-v2/**

Public, no login. Opens on the Overview. Add `?open=proto` to land on the prototype, and `&step=paywall` (or `welcome`, `q1`, `q2`, `loader`, `offer`) to open both phones on one screen.

Volume 1: https://bterzic123.github.io/norton-flow-rebuild/

## What is new in volume 2

- **Overview:** an Apple Ads card, a screen-by-keyword comparison, all 39 searches with share of voice, and what happens next.
- **Prototype:** two phones driven by one step bar. Tap through either phone and the other follows.
- **Keyword picker** beside each phone: "scam protection", "security", "antivirus", "norton", "totalav" / "vpn", "wifi security", "nordvpn", "vpn fast".
- **Ideas panel:** for each step, what differs between the two searches, with a potential outcome for each.
- **30-second walkthrough** plays both flows at once. EN / DE / CS, Light / Dark. On a phone, a toggle switches between the two flows.

## What differs by keyword

| Screen | "scam protection" | "vpn" |
| :-- | :-- | :-- |
| Welcome | "Stop scams in your texts, calls and browser" | "A VPN with Norton security built in" |
| What to protect | Scam texts and calls ticked | Public Wi‑Fi ticked |
| Plan picker | Genie Scam Protection first, opens on the plan the answers fit | Secure VPN first, opens on 360 for Mobile |
| Offer on close | 7 days free, scam protection leads | 7 days free, Secure VPN leads |

## Grounding

Every price, rating, plan and feature line comes from Norton's own published material: the US App Store listing, norton.com and Norton's in-app screens. Prices are the euro prices on the in-app screens. Keyword data is from public observation of Norton's Apple Ads in the US (12 September – 11 October 2026), not from the account. Impact ranges are Adapty's expected effect from tests across subscription apps, not measured lift for Norton.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. No build step and no dependencies.
