# WealthLens — Client Risk Profiling Website

A GitHub Pages-ready static website for a Wealth Management academic project.

## Scope

Phase 1 only:

**Questionnaire → Scoring Engine → Risk Analysis → Visualization**

The site does **not** provide asset allocation, security selection, mutual-fund recommendations or portfolio construction.

## Files

- `index.html` — website structure and screens
- `styles.css` — premium dark/private-banking visual system
- `app.js` — questionnaire, local-state persistence, scoring and results dashboard

## Run locally

Open `index.html` in a browser, or use VS Code Live Server.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `styles.css`, `app.js`, and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Save. GitHub will publish the static site.

## Important academic note

The questionnaire follows the redesigned project framework based on the professor-provided sample. The exact scoring weights and cut-offs are intentionally centralized in `app.js` so they can be reviewed and finalized before pilot testing.

The current implementation is an academic prototype and should not be represented as a SEBI-approved or psychometrically validated risk-profiling instrument.
