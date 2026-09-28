# Abhi Nandan — CV

Quality Engineering Leadership | AI-Enabled Engineering | Continuous Delivery

Static CV with clickable profile links and an embedded PDF download.

## Publish

In repository **Settings → Pages → Build and deployment**, set **Source** to
**GitHub Actions**. The Pages workflow publishes changes pushed to `main`.
If needed, run **Deploy CV to GitHub Pages** from the Actions tab.

Expected URL: https://dev2atwork.github.io/abhi-nandan-cv/

## Files

- `index.html`: self-contained CV, including icons and embedded PDF.
- `Abhi_Nandan_CV.pdf`: standalone PDF.
- `.github/workflows/pages.yml`: deployment workflow.

When updating the CV, regenerate both the standalone PDF and the PDF embedded
in the HTML so the download button serves the latest version.
