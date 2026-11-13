# Repository file map

This repository is a browser-captured copy of the De-Truth / Detruth Agency website. The files are intentionally kept at the repository root for now: the published page references its stylesheet by a relative root path, and moving runtime files without rewriting and testing every reference could break the page.

## Published website

| File | Role |
|---|---|
| `index.html` | GitHub Pages entry page. Contains the captured page markup and content. |
| `index-CyLSP_bQ.css` | Main stylesheet linked by `index.html`. Keep beside `index.html`. |
| `404.html` | GitHub Pages custom not-found page. Keep at the root so GitHub Pages can recognize it. |

## Captured source and reference files

| File | Role |
|---|---|
| `Shopify Developer & Ecommerce Website Designer _ Detruth.html` | Separately saved browser copy of the original page; retained as a reference, not the published entry point. |
| `html.txt` | HTML capture/reference copy. |
| `README.md` | Repository overview and navigation to this file map. |

## Supporting downloaded resources

| File | Observed role |
|---|---|
| `css2` | Downloaded Google Fonts stylesheet. |
| `element.js` | Google Translate-related script. |
| `m=el_main` | Google Translate-related script resource. |
| `m=el_main_css` | Google Translate-related stylesheet resource. |
| `events.270c78a44fc53e7b.js` | Lovable event/analytics SDK resource. It is retained unchanged; this inventory does not assert that the published HTML loads it. |
| `index-k_GjUUSv.js` | Large JavaScript asset present in the repository. Its contents were not returned by the repository file reader, so its runtime role and whether it is referenced by the page remain unverified. Do not delete it based only on this inventory. |
| `.nojekyll` | Tells GitHub Pages not to run Jekyll processing on the published files. |

## Safety notes

- No HTML, CSS, JavaScript, text, image, or design content was edited as part of this organization.
- No files were moved, renamed, or deleted. This preserves the current root-relative references and GitHub Pages conventions.
- The current `index.html` references `./index-CyLSP_bQ.css` and the Google Fonts stylesheet. Its inspected markup does not reference the other downloaded resources by local filename.
- The separately saved HTML capture refers to a companion `_files` directory in its own markup; that directory is not present in the current repository listing. Treat that saved capture as a reference copy unless its companion assets are recovered.
- This is a captured page, not a verified restoration of the original Lovable project source. The visual markup and stylesheet are present, but the original editable project structure and complete interactive runtime have not been established by this inventory.
- Before any future folder moves or cleanup, check all HTML, CSS, and JavaScript references and compare the deployed page. Preserve the existing appearance and behavior.
