# Project 0: Cameras & Perspective

A photography project exploring the relationship between perspective, focal length/zoom, and the
center of projection, through three exercises: the selfie (wrong vs. right way), architectural
perspective compression, and the dolly zoom.

## Structure

```
.
├── index.html          # the project webpage
├── style.css           # its styling
├── media/              # all photos + the gif (drop your files here, see below)
└── README.md
```

## Adding your photos

Drop your files into `media/` using these exact names (the page is already wired up to them):

| File | Part | Description |
|---|---|---|
| `media/part1-close.jpg` | Part 1 | Close-up selfie, no zoom (the "wrong way") |
| `media/part1-zoomed.jpg` | Part 1 | Same subject from far away, zoomed in to match framing (the "right way") |
| `media/part2-zoomed.jpg` | Part 2 | Building facade, zoomed in from far away (compressed) |
| `media/part2-walked.jpg` | Part 2 | Same facade, walked in close, no zoom (natural depth) |
| `media/part3-dollyzoom.gif` | Part 3 | The dolly zoom animated GIF |

If a file isn't present yet, the page shows a "drop the photo here" placeholder instead of a broken
image, so it's safe to preview before all assets are in place.

You can rename files or edit the `src="media/..."` paths in `index.html` if you'd rather use your
own filenames.

## Previewing locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Publishing with GitHub Pages

1. Create a new repository on GitHub (don't initialize it with a README).
2. Push this repo to it:
   ```bash
   git remote add origin <your-repo-url>
   git branch -M main
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**, set the source to the `main` branch (root), and save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.