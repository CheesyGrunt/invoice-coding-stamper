# Invoice Coding Stamper

Soldiers' Angels tool for stamping accounting coding onto an invoice PDF before it goes to SharePoint.

- One self-contained page (`index.html`) with pdf-lib inlined. No build step, no server.
- The invoice is stamped entirely in the browser. Nothing is uploaded anywhere.
- Hosted on Render as a static site (publish path `.`), auto-deploys from `main`.

To update: replace `index.html` and commit to `main`. Render redeploys on its own.
