# IT'sOnboarding website

A one-page sales site for the Microsoft 365 onboarding guide. Everything is in `index.html`.

## Editing from your phone
1. Open this repository on github.com in your phone's browser.
2. Tap `index.html`, then tap the pencil icon (✏️) to edit.
3. Change the text inside the `SITE = { ... }` section near the top of the file. Only change the words between the "quote marks".
4. Tap **Commit changes**. The live site updates in about a minute.

## Where to paste the Shopify Buy Button
Search the file for `PASTE SHOPIFY`. You'll find two spots, one near the top price box and one in the final section. Paste the embed code on the empty line between `↓↓↓ paste below ↓↓↓` and `↑↑↑ paste above ↑↑↑`. The plain "Buy now" button in that spot then hides itself.

Simpler option: put your Shopify product or checkout link in `shopifyLink` in the `SITE` section. Every Buy button will then use it.

## Publishing with GitHub Pages (free)
1. On github.com open this repository and go to **Settings → Pages**.
2. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then tap **Save**.
3. After 1 to 2 minutes your site is live at `https://<your-username>.github.io/<repo-name>/`.
4. Optional: add your own domain under **Settings → Pages → Custom domain**.

Note: free GitHub Pages needs the repository to be **public**.
