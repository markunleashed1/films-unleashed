# Films Unleashed — personal beta prototype

A responsive, installable Progressive Web App (PWA) prototype for the proposed Geeks Unleashed film discovery spin-off.

## Included
- Mobile-first home screen and navigation
- Interactive one-film recommendation flow (mood, time, discovery dial)
- Essential, international and independent list previews
- Film festival discovery concept and official BFI link
- Manifest, icon and basic offline fallback

## Important limitations
- The prototype uses a small hardcoded film catalogue. It does **not** query or update the private Google Sheet.
- Watched counts are a labelled snapshot. Film selections are not yet verified against live user history.
- No live festival schedules, ticket availability, authentication or ticket purchase integration.
- Never embed the Google service account JSON or TMDb API token in client-side code.

## Try locally
Serve this directory over HTTP (service workers do not work from file://): `python -m http.server 8000` then visit http://localhost:8000.

## Next
Secure authenticated backend, per-user data model, TMDb metadata, import/sync, real recommendations, and verified festival screening links.
