# 25th.co

Source for the public website of [The 25th Company](https://25th.co), a user experience and product design studio based in Perth, Australia.

It's a static site (plain HTML and CSS, no build step) served with GitHub Pages.

## Layout

| File | Purpose |
| --- | --- |
| `index.html` | The single-page site |
| `main.css` | Styles |
| `snow-leopard-400.png` | Header logo |
| `signature.png` | Signature image in the About section |

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploying

In the GitHub repo, go to **Settings → Pages**, set the source to **Deploy from a branch**, and choose `main` / `(root)`. Every push to `main` publishes the site.

To serve it at 25th.co, add a `CNAME` file containing `25th.co`, set the custom domain in the same Pages settings, and update the DNS records at the domain registrar.
