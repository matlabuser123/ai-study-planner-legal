# AI Study Planner — legal pages

The public privacy policy, terms of service and account-deletion instructions
for the **AI Study Planner** app (Android package `com.aistudyplanner`).

These files are generated, not written here. The single source of the words is
the app's own `LegalContent` constant, rendered to static HTML by the app
repository's `tool/build_legal_pages.dart`; the app renders the same constant
on its `/privacy`, `/terms` and `/delete-account` routes. Editing the HTML in
this repository changes nothing durable — the next generation overwrites it.

Pages:

- `privacy.html` — Privacy policy
- `terms.html` — Terms of service
- `delete-account.html` — Deleting your account

Sections still awaiting a decision from the publisher are marked on the page
itself (`REQUIRES_PUBLISHER_DECISION`, `REQUIRES_SUPPORT_CONTACT`) rather than
filled in with a guess.

No script runs on these pages, no font or asset is fetched from anywhere, and
nothing here collects anything.
