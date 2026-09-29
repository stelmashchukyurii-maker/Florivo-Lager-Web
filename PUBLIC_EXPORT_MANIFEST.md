# FLORIVO LAGER PUBLIC EXPORT MANIFEST

Status: BASELINE CREATED / DEPLOYMENT NOT SWITCHED
Updated: 2026-09-29

Canonical source:
PRIVATE `stelmashchukyurii-maker/Florivo-Lager`

## Exported baseline files
- `.nojekyll`
- `florivo.webmanifest`
- `teknisk-versjonslogg.html`
- `teknisk-versjonslogg-no.html`
- `teknisk-versjonslogg-uk.html`

All five exported legacy-source files were verified exact by Git blob SHA against `Mottak/main`.

## Intentionally withheld
`presentasjon-hovedmeny.html`

Reason:
its current legacy source links directly to internal operational pages:
- Camera
- UT Kontor
- UT Lager
- Scanner Home

It must be reviewed/rewritten before PUBLIC export.

## Pending binary candidates
- `favicon.ico`
- `apple-touch-icon.png`
- `florivo-icon.png`

They remain pending because the current repository-write path used for this bootstrap is text-oriented. Their absence does not block source/governance baseline.

## Forbidden
Never export:
- Android;
- backend/SQL;
- Edge Functions;
- internal/admin warehouse pages;
- internal protocols/governance;
- security audits;
- private data;
- secrets;
- legacy sensitive history.

## Deployment
No production cutover has been authorized by this manifest.
No operational source is intentionally hosted from this repository as part of the baseline.
