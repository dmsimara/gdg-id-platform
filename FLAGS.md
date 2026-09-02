# FLAGS

Improvement register for this repository. Documentation handover only - do not treat Open rows as bugs fixed in the docs PR.

Status: **Open** (actionable later) or **Accepted** (known limitation).


| ID | Severity | Finding | Evidence | Suggested next step | Status |
| --- | --- | --- | --- | --- | --- |
| F1 | Low | README clone URL still points at ``SauceCode01/gdg-id-platform`` while origin is ``gdg-pup-webdev/gdg-id-platform``. | README Getting Started | Update clone URL to the org remote. | Open |
| F2 | Low | About-page contributor LinkedIn URLs may drift from the 2026 roster. | ``src/app/about/page.tsx`` credits | When editing credits next, reconcile to roster; do not mass-edit app code in docs handover. | Accepted |
| F3 | Medium | Product depends on Firebase, Google Sheets, Gmail API, and (deploy path) Supabase secrets. | README env section, docs/DEPLOY.md | Maintain a single env inventory (names only) shared between README and DEPLOY. | Open |