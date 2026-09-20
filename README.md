# AIDX Lab — simple one-page site

The whole website is **one file: `index.html`**. There is nothing to install and
nothing to run.

## How to change the website (the easy way)

1. Go to the repository on GitHub and click **`index.html`**.
2. Click the **pencil icon** (top right) to edit it.
3. Change the words you want.
4. Scroll down and click **Commit changes**.
5. Wait about a minute. The live site updates by itself.

That last step is done by GitHub Actions — the file
`.github/workflows/deploy.yml`. You can watch it run under the **Actions** tab.
A green tick means the site is live with your change.

## Common edits

| To change | What to do |
|---|---|
| Any text | Find it in `index.html` and type over it |
| Add a research area or a person | Copy a whole `<div class="card"> … </div>` block, paste it below, change the words |
| Colours | Edit the lines at the top under `COLOURS`, e.g. `--red: #7b1e2b;` |
| Remove the orange prototype bar | Delete the block marked `PROTOTYPE NOTICE` |
| Page title in the browser tab | The `<title>` line near the top |

## Editing on your Mac instead

Open `index.html` with TextEdit (turn on
*Settings → Open and Save → Display HTML files as HTML code* first), save, and
double-click the file to see it in your browser.

## Still to do before this is public

- [ ] Replace the placeholder names, and the research and people text
- [ ] Fill in the two grey rows under "What we ask for"
- [ ] Add the real email address and street address
- [ ] Paste ACU's official Acknowledgement of Country into the footer
- [ ] Delete the prototype notice
