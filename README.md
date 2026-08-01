# Cercle de Voix — landing page

French landing page for Voix Essence's **Cercle de Voix** (Montréal, Plateau
Mont-Royal). Deliberately separate from the Spanish quiz project (`VEAquiz`) —
different language, different audience, different funnel. Nothing is shared.

- Live: https://cercle.veacademy.studio
- Product: 12 séances, 12 people max per cohort, Centre Soha, 961 rue Rachel Est
- Price: 3 × 132 $ CAD + taxes (Circle checkout)
- Waitlist: locked cohort buttons -> Formspree form `maqrgbrl` -> Kit
  (Convertkit plugin) -> sequence "Cercle de Voix — liste d'attente (FR)"

## Editing seat counts

`SLOTS` near the bottom of `index.html`. Bump `taken`, flip `locked`, commit.
Both cohort pickers re-render from it.

## Meta pixel events

- `Cercle_LPV` — landing page view (campaign optimisation)
- `Cercle_PaywallClick` — paywall button clicks
- `SeatLocked_Click` — locked cohort tapped (demand signal)
- Standard: `PageView`, `ViewContent`, `InitiateCheckout`
