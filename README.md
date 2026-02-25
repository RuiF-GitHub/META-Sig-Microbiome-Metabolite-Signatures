
# META‑Sig: Microbiome Metabolite Signatures — Website

This repository contains a GitHub Pages site (Just the Docs theme) documenting **META‑Sig**, a pipeline to attribute metabolites to microbial origin and derive microbiome metabolite signatures.

## Quick deploy
1. Create a repo on GitHub named `META-Sig-Microbiome-Metabolite-Signatures`.
2. Copy all files in this folder to the repository root and commit.
3. Go to **Settings → Pages**:
   - Source: *Deploy from a branch*
   - Branch: `main` and folder `/ (root)`
4. Save and wait 1–2 minutes. Your site will be live at `https://<username>.github.io/META-Sig-Microbiome-Metabolite-Signatures/`.

Update `_config.yml` `aux_links`, and set `url`/`baseurl` for canonical links.

## Structure
- `_config.yml` — site configuration
- `index.md` — homepage
- `getting-started.md`, `workflow.md`, `results.md`, `reproducibility.md`, `references.md`, `about.md`
- `methods/` — preprocessing, attribution, validation pages
- `assets/` — images (replace `pipeline.png` with your diagram)

## License
MIT (see `LICENSE`).
