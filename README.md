# Suroor Aldhalemi — Professional Portfolio

Static, responsive portfolio website based on `Suroor_Aldhalemi_Targeted_Resume_2pages.pdf`.

## Local preview

```bash
cd suroor-portfolio
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Important before publishing

- Obtain Suroor's approval for public use of her name, work history, email, and downloadable resume.
- Verify that both roles listed as Present are still current.
- Confirm the Purdue University & IBM certificate completion status.
- Verify all metrics with the resume owner.
- The PDF includes contact details. Remove the PDF or redact those details if she doesn't want them public.
- Add a real LinkedIn URL only after confirming it; no placeholder URL is published.

## Deploy with GitHub Pages

1. Create a new public GitHub repository, e.g. `suroor-portfolio`.
2. Commit and push these files to `main`.
3. In repository Settings > Pages, select Deploy from a branch, `main` and `/(root)`.
4. Site URL: `https://YOUR-GITHUB-USERNAME.github.io/suroor-portfolio/`.

This is a static site. No build step or paid hosting is necessary.

## GitHub Actions deployment (included)

The `.github/workflows/deploy.yml` file automatically deploys changes pushed to `main`.
After pushing the project, open **Settings → Pages → Build and deployment → Source: GitHub Actions**.
Check the **Actions** tab for deployment status. Publishing makes site and PDF publicly accessible.
