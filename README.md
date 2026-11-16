# Academic homepage template

A single-file homepage for a computational materials scientist. No build tools, no Jekyll themes: just `index.html`.

## Put it online with GitHub Pages

1. Create a new public repository named exactly `<your-username>.github.io`.
2. Upload `index.html` (and this README) to the repository root.
3. Go to **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute or two, your site is live at `https://<your-username>.github.io`.

Using a project repository instead (e.g. `homepage`) also works; the site will be at `https://<your-username>.github.io/homepage/`.

## Customize

Search `index.html` for `EDIT` to find every spot to change.

- **Photo:** add `images/profile.jpg` and replace the `JD` placeholder div with
  `<img class="portrait" src="images/profile.jpg" alt="Your Name">`.
- **CV:** add `files/cv.pdf`.
- **Publications:** copy an `<li>` block per paper; wrap your own name in `<span class="me">`.
- **Colors and fonts:** change the variables at the top of the `<style>` block (`--accent`, `--serif`, `--sans`). Dark mode values are right below them.
- **Lattice graphic:** purely decorative; delete the `<figure class="lattice-wrap">` block to remove it.

## Optional

- **Custom domain:** add it under Settings → Pages and create a DNS CNAME record pointing to `<your-username>.github.io`.
- **Sections:** each `<section>` is independent; delete or duplicate as needed (and update the nav links).
