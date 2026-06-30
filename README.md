# yamato-security.github.io

The landing page for the **Yamato Security** GitHub organization, served at
<https://yamato-security.github.io/>.

This is a GitHub *organization site*: GitHub publishes the root of the
`main` branch of the repo named `yamato-security.github.io` to
`https://yamato-security.github.io/`. Each project keeps its own docs at
`https://yamato-security.github.io/<project>/` (project Pages), and this page
links to them.

## Edit
It's a single self-contained `index.html` (inline CSS, no build step). Edit it
and push to `main` — GitHub Pages redeploys automatically. `.nojekyll` disables
Jekyll processing so the file is served as-is.

## Deploy / settings
Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*,
Branch = `main` / `/ (root)`.
