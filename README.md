# AEPi Kent — Simple Static Website

This site is plain HTML and CSS. It has no framework, package manager, build step, or external editor integration.

## Open on localhost:3000

From this folder, run:

```bash
python3 -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

You can also double-click `index.html`, although running a local server is more reliable.

## Change the Brothers password

Open `index.html`, find this line near the bottom, and replace `change-me`:

```js
const BROTHERS_PASSWORD = "change-me";
```

This is only a lightweight browser-side lock. Do not place confidential documents or private personal data inside a public static website.

## GitHub Pages

Upload every file in this folder to a GitHub repository. In **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
