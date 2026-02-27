# Hypnotized

You found the repo. That's not the same as solving it.

Start with the card. Follow the spiral.

## Deploy

1. Fork this repo
2. Enable GitHub Pages (Settings → Pages → Branch: `main`, folder: `/`)
3. Update the hex payload in `print/entry-card.html` with your Pages URL
4. Print the card

```bash
echo -n "https://<you>.github.io/secretcon-hypnotized/" | xxd -p | tr -d '\n'
```

Split into 16-char chunks. Replace the 7 `EXFIL_DATA` lines.

## Stack

Pure HTML, CSS, vanilla JS. No frameworks. No build tools. Static files only.

## Credits

popsh3llz
