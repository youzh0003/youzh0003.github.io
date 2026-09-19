# youzh0003.github.io

Developer homepage for **yzyy** — small, focused Android apps.

Served by GitHub Pages at <https://youzh0003.github.io/> (Settings → Pages →
Deploy from branch `main` / root). This is the URL used in the **Website**
field of every app's Play Console store listing.

## Layout

| Path | What it is |
|---|---|
| `index.html` | The whole homepage. Single file, inline CSS, no JS, no build step. |
| `404.html` | Not-found page; links back home. |
| `icons/<key>.png` | 192×192 app icon, composited from that app's own adaptive-launcher layers in its repo (never downloaded from Play). |
| `icons/favicon.svg` | Site favicon. |
| `robots.txt`, `sitemap.xml` | Crawling. Allow all. |
| `docs/screenshots/` | Reference renders of the page; not linked from the site. |
| `.nojekyll` | Serve the files verbatim — no Jekyll processing. |

Privacy policies live in a separate repo, `youzh0003/privacy-policy`, served at
<https://youzh0003.github.io/privacy-policy/>. This repo only links to them.

## Adding an app

Add one `<li class="card">` to the grid in `index.html`, keeping the list in
alphabetical order by title, and drop a 192×192 icon in `icons/`. Use the app's
**listed** Play title and its Play short description verbatim — this page must
never claim something the store listing does not.

Contact: yzyapps99@gmail.com
