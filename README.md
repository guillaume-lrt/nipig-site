
# Project Website for NIPIG: Neural Implicit Avatar Conditioned on Human Pose, Identity and Gender

This repository contains a static website (inspired by `nerfies.github.io`) for the paper **NIPIG: Neural Implicit Avatar Conditioned on Human Pose, Identity and Gender**.

## What's new in this version
- **Authors** shown under the title with **ORCID links** and **affiliation asterisks**.
- **Updated abstract** (as provided).
- **Interactive sliders** only (storyboard + image grid removed). Sliders styled similar to nerfies.
- **Method & Results** sections with **clearly named placeholders** and source hints (video timestamps or paper figure numbers).

## Quick start
Open `index.html` in a browser.

## Authors & Affiliations
Edit the author list / ORCID IDs in `index.html` (search for the `authors_block` in the markup).  
Affiliation symbols used:
* `*` InterDigital  
* `†` Inria  
* `‡` University Rennes  
* `§` CNRS  
* `¶` IRISA

## Teaser video
The site now embeds the YouTube teaser: https://youtu.be/iEeQa2NuFwg

## Sliders (Identity & Pose)
- Identity stops: `id1`, `id075`, `id050`, `id025`, `id0`.
- Poses: `pose0`..`pose5` (edit `poseLevels` in the script if you change this).
- The displayed image path is `assets/img/grid/{identity}_{pose}.png`. Provide images for each combination you want to support.

> Tip: keep image sizes consistent (e.g., 640×800). PNG recommended.

## Method & Results assets
Each subsection includes a **placeholder** named exactly as suggested in the caption, e.g. `assets/img/identity_interp.gif`.  
Replace the placeholder with your exported asset. The caption tells you where to take it from:
- `source: video, 03:00–03:08` — export a short loop from the provided video
- `source: paper, Figure 4` — crop or export from the paper figure

## Deploy to GitHub Pages
1. Create a repo and commit this folder at repo root.
2. Enable *GitHub Pages* (branch: `main`, folder: `/ (root)`).
3. Your site will publish shortly.

##