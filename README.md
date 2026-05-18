# injeel-it-d-o-o.github.io

Legal pages and support center for the **UKP Quiz** mobile app, published by **Injeel IT d.o.o.**

The main company site lives at [injeel-it.hr](https://injeel-it.hr); this repo only hosts the documents Apple requires for App Store submission.

## Live URLs

- https://injeel-it-d-o-o.github.io/
- https://injeel-it-d-o-o.github.io/privacy and `/privacy.hr`
- https://injeel-it-d-o-o.github.io/terms and `/terms.hr`
- https://injeel-it-d-o-o.github.io/support and `/support.hr`
- https://injeel-it-d-o-o.github.io/help and `/help.hr`

These URLs go into App Store Connect under:

- **App Privacy → Privacy Policy URL** → `/privacy`
- **App Information → Privacy Policy URL** (per locale) → `/privacy` for English, `/privacy.hr` for Croatian
- **Subscription → Terms of Use URL** → `/terms`
- **Support URL** → `/support`

## How it works

This is a GitHub Pages organization site (the `<org>.github.io` repo on the [Injeel-IT-d-o-o](https://github.com/Injeel-IT-d-o-o) org). Both `.html` and `.md` versions of each page are committed; GitHub Pages serves the `.html` files when present and Jekyll renders the `.md` files for clean URLs.

No custom domain is configured. If Injeel IT later wants the legal pages on `injeel-it.hr` directly (e.g. as a `legal.injeel-it.hr` subdomain), the steps are documented in `docs/plans/app store submission/legal/README.md` in the PubQuiz repo.

## Editing

When updating any document:

1. Update **all four** related files (English MD + HTML, Croatian MD + HTML).
2. Update the "Last updated" date at the top of every changed file.
3. Commit and push; the live site updates within a minute or two.

## Operator

Injeel IT d.o.o.
Pete Poljanice 5, 10040 Zagreb, Croatia
OIB: 55064630991, VAT: HR55064630991
support@injeel-it.hr · privacy@injeel-it.hr
