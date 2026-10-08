# After-Hours Support

Compact static guide for deciding what a website chatbot can answer while staff are away and who handles the rest. One content page, clearly fictional conversation examples and an editable Markdown coverage plan. Author: Alex Rostovtsev.

## Local preview

From this folder: `python -m http.server 4195 --bind 127.0.0.1 --directory public`.

Open http://127.0.0.1:4195/. There is no framework, build step, JavaScript, form, analytics or external asset request. The local heading font retains its OFL licence.

## Publication

Proposed host: Railway. Dockerfile serves public/ with Caddy; PORT comes from the hosting environment, defaulting to 8080. /health responds with 200. Missing files use 404.html with the original error status. No SPA fallback is configured.

Production is not published. Canonical URL, og:url, an absolute sitemap and its robots reference await Railway's actual assigned hostname. Do not invent the origin or buy a plan automatically. See ../NEXT-PUBLICATIONS.md for the approved subject and reduced scope.

Existing outbound destinations are retained as ordinary direct HTML anchors. Product links outside the core support topic are grouped in a clearly separate resources section. No visible BLURSOR branding appears in the copy.

Edit index.html, styles.css and resources/coverage-plan.md directly. Keep example coverage assumptions visible and distinguish a request from a completed action.
