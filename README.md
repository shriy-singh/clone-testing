# Clone Testing: prototype walkthrough

A recorded walkthrough of the study system built for the M.Sc. thesis *Clone Testing: An Investigation
of Trust and Suspicion in Identity Recognition During Human-Machine Dialogue*
(Bauhaus-Universität Weimar, supervised by Prof. Dr. Benno Stein and Prof. Dr. Maria Wolters).

The live prototype at [thesis-singh.web.webis.de](https://thesis-singh.web.webis.de) is password
protected. This recording needs no login.

## Publish it with GitHub Pages

1. Create a repository, for example `clone-testing`, and make it **public**.
2. Upload `index.html`, `thesis_walkthrough.mp4`, `poster.jpg` and this README to the repository root.
3. Settings > Pages > Build and deployment > Source: **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. Wait about a minute. The site is then at `https://shriy-singh.github.io/<repository-name>/`

Or from a terminal:

```
git init
git add .
git commit -m "Clone Testing prototype walkthrough"
git branch -M main
git remote add origin https://github.com/shriy-singh/clone-testing.git
git push -u origin main
```

Then do step 3 above.

## Files

| File | What it is |
|---|---|
| `index.html` | The page: video player plus an index of what happens when |
| `thesis_walkthrough.mp4` | The recording, 4 min 48 s, 1280x608, 1.5 MB |
| `poster.jpg` | Still frame shown before playback starts |

The recording was cropped to remove the browser frame and compressed from the 4K original.
