# Wendy Ondigo - AI & Machine Learning Portfolio

Personal portfolio for public AI/ML coursework and independent prototypes.

**Website:** https://ondigowendy.github.io/

## Editing

Edit `index.html`. The site is one responsive HTML page with inline CSS, SVG,
portrait, and consent-management JavaScript. There are no external fonts,
package dependencies, or build step.

## Optional Google Analytics

GA4 uses the public Measurement ID `G-9HECLKGLBY`. This is a direct Google tag
installation, not the separate Google Tag Manager container.

The Google script loads only on `ondigowendy.github.io` after explicit opt-in.
Declining on a first visit makes no Google Analytics requests. A first-party
local-storage preference remembers the visitor's choice. The footer provides a
privacy notice and Analytics preferences control. Withdrawing consent disables
collection, expires accessible GA cookies, and reloads to unload the tag when
the new preference can be saved. If browser storage is blocked, the choice is
limited to the current page and the banner explains that limitation.

Analytics storage is allowed only after consent. Advertising storage,
advertising personalization, and Google signals are disabled in this site's
configuration. Do not send names, email addresses, or account identities.

Page views are configured once per consented page load. GitHub/LinkedIn/project
links emit `portfolio_link_click` with `link_url`, `link_domain`, `link_category`,
and `project_name`. Custom click URLs omit query strings and fragments.
GA4 enhanced measurement may separately report generic `click` events; filter
on `portfolio_link_click` when counting these custom interactions.

To see category/project breakdowns in GA4 explorations, register event-scoped
custom dimensions for `link_category` and `project_name`. Use Realtime after
allowing analytics to confirm delivery to your property; blockers and declined
consent intentionally reduce measured traffic. This site is not a way to
identify who viewed a GitHub or LinkedIn profile.

## Public content

Project descriptions distinguish coursework from independent prototypes and link
to the source notebooks or repository. Keep claims tied to that source, and keep
limitations visible. Do not add private datasets, credentials, employer-internal
material, or private application documents.

## Featured sources

- [PGPAIML-UTA](https://github.com/OndigoWendy/PGPAIML-UTA):
  Medical Reference RAG, Bank Customer Churn, EasyVisa Classification,
  Personal Loan Uptake, and FoodHub Order Analysis.
- [commcare-sql-pipeline](https://github.com/OndigoWendy/commcare-sql-pipeline):
  a synthetic-data pipeline prototype, not yet validated against live CommCare.

The medical RAG notebook is educational, not medical advice or a clinical tool.
No predictive model on this site is presented as a production decision system.

## Hosting

GitHub Pages publishes the root of the `main` branch.
Push changes to that branch to update the website. `.nojekyll` keeps the site
as plain static HTML.

Public contact links are limited to GitHub and LinkedIn.
