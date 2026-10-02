# laconicman.github.io

User GitHub Pages site — apex host for per-app **privacy** and **support** pages.

- Jekyll + minima + jekyll-polyglot (`ru` default, `en` parallel), same stack
  as `laconicman/articles`. Built by Actions (`bundle exec jekyll build`),
  not the jekyll-build-pages action — polyglot isn't on the Pages allowlist.
- Pages follow `apps/<app>/<page>.<lang>.md` → `/apps/<app>/<page>.<lang>/`.
- Add an app: `apps/<app>/index.md` + `index.en.md`, then `privacy`/`support`
  in both languages; link them in `apps/index.md`.

Deploys from `main` via `.github/workflows/jekyll.yml`.
