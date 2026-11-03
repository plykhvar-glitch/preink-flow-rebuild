# Growth Audit — PreInk: AI Tattoo Generator (Ink AI)

**Live:** https://plykhvar-glitch.github.io/preink-flow-rebuild/

Five ranked ideas, plus a clickable prototype of PreInk's iOS onboarding and paywall rebuilt in Ink AI's own design. Only the order of the screens changed, not the art direction. Prepared by Adapty, November 2026.

## The five ideas

| # | Idea | Screen | Potential outcome |
| :-- | :-- | :-- | :-- |
| 01 | Let them type their idea before the paywall | Your idea → Style | CR +10–20% |
| 02 | Put their own tattoo on the paywall | Paywall | CR +15–20% |
| 03 | Ask about tracking after they buy | Welcome → Try On | CR +10–15% |
| 04 | Show your 4.4 stars next to the price | Paywall | CR +10–15% |
| 05 | Offer one week when they close | Offer on close | ARPU +10–15% |

## Grounding

Every price, rating, review, style and image comes from PreInk's own published material:

- **The in-app screens:** Lifetime $34.99 ("Pay once use 4ever"), 1 Week $6.99 ("Cancel anytime"), "Unlimited Generations · ∞ Generations · No Ads · No Watermark", "Get 4 tattoos per generation", the prompt card, the loader and every slide.
- **The App Store listing:** 4.4 from 2.4K ratings, and Mykee202's review, quoted word for word.
- **reface.ai/preink:** the style names and the style artwork.

The prototype cannot run your generator, so it shows your published sample for the chosen style. Light mode is our approximation; the app ships dark only.

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for PreInk.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to land on the prototype.
