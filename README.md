
# META‑Sig: Microbiome Metabolite Signatures

The human microbiome is increasingly recognized as a key contributor to cancer initiation, progression, and response to therapy across multiple malignancies. Microbiome‑derived metabolites, small molecules produced as intermediates or end‑products of microbial metabolism, represent major modes of interaction between the microbiome and the host. However, in tumor tissues characterized by low microbial biomass and host‑dominated metabolite backgrounds, directly distinguishing tumor‑derived from microbiome‑derived metabolites remains challenging. This limitation has historically hindered mechanistic insight into microbial contributions within the tumor microenvironment.

This repository documents META‑Sig, a computational pipeline designed to attribute metabolites to microbial origin in gastric cancer tissues, enabling systematic identification of microbiome‑associated metabolite signatures in tumor samples.

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
