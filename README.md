# Inside Bach’s Fugue — GitHub Pages package (Guided v0.12, packaging v0.13)

**Start:** open `index.html` for Guided Exploration. `research.html` contains manual selection and advanced controls. This is a *static site*; it needs no server, build tools, or third-party dependencies.

## Files

- `index.html` — guided tutorial and automatic discovery of six candidate melodic-shape families.
- `research.html` — optional manual-selection research interface.
- `score_data.js` — score-derived notes, rhythm, five voices and voice colors.
- `discovery_families.js` — computed candidate families.
- `CREDITS_AND_RIGHTS.md` — attribution, publication conditions, and methodological limitations.
- `.nojekyll` — GitHub Pages convenience marker.

## Publish to GitHub Pages

1. Confirm that the permission for the score-derived data covers hosting and redistribution through a public GitHub repository (and the edition rights are clear).
2. Create a **new** public repository, `CMRM-Inside-Bachs-Fugue`.
3. Upload **the contents** of this package to the repository root; commit them.
4. Under **Settings → Pages**, choose **Deploy from a branch**, `main`, `/(root)` and save.
5. Open `https://augusto-sarti.github.io/CMRM-Inside-Bachs-Fugue/` and test both Guided and Research views.

## Book integration

Do **not** replace Chapter 7's local-file link with the proposed public URL until GitHub Pages is live and verified. This release does not change Working 28 or any existing GitHub project.

## Research caution

The candidate families are shape similarities, not confirmed fugue-subject/countersubject annotations. This distinction must remain explicit in educational use.
