# Sea More Expeditions — published site

This repository contains the rendered static website in `site/`. [GitHub Actions](.github/workflows/publish.yml) checks out the [Next.js source repository](https://github.com/Evoolo/seamore-website), builds it for the `/seamore/` project path, commits the generated pages here, and deploys them to [GitHub Pages](https://evoolo.github.io/seamore/).

Source commits trigger the action automatically; it can also be run from the Actions tab and checks the source daily as a fallback. `.source-commit` records the source revision used for the latest render. Edit the site in `seamore-website`; generated files in this repository will be replaced by the next build.
