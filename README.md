# Word Nickel Counter

A standalone page for counting words from pasted text, uploaded `.txt` / `.md`
files, Wikipedia article URLs, or estimated book word counts from ISBNs. It
calculates one nickel for every 60,000 words, keeps a saved running total in the
cloud, and stores a lightweight shared collection of saved reading items.

## Open Locally

Open `index.html` directly in a browser.

## Use In Google Sites

Google Sites embeds pages by public URL. After GitHub Pages is enabled for this
repo, the page should be available at:

```text
https://pandaturtlefalcon.github.io/monies/
```

Then in Google Sites:

1. Choose **Insert**.
2. Choose **Embed**.
3. Paste the public GitHub Pages URL.
4. Resize the embed box until the counter fits nicely.

## Enable GitHub Pages

In GitHub, open **Settings / Pages**, choose **Deploy from a branch**, then set:

- Branch: `gh-pages`
- Folder: `/ (root)`

## Cloud Sync

The shared saved total and collection sync through Firebase Firestore at:

```text
wordNickelCounter/shared
```

The live text box remains local/private until someone saves or adds an item.
