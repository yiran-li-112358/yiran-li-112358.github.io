# PhD Personal Website (Jekyll + GitHub Pages)

## Quick Start
1. Rename this repo to `yourusername.github.io` (user site) OR keep any repo name for a project site.
2. Replace values in `_config.yml` with your info.
3. Add a headshot to `assets/img/headshot.jpg` (recommended 512×512).
4. Drop your PDF CV into `assets/cv/YourName_CV.pdf` and update `cv.md`.
5. Commit and push to GitHub.
6. In the GitHub repository: **Settings → Pages** and set source to the **default branch** (or enable the provided Actions workflow).

## Local Preview
- Install Ruby and Bundler, then run:
```bash
bundle install
bundle exec jekyll serve
```
- Open http://localhost:4000
