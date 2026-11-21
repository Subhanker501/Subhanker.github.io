# Academic website — Suman Mandal

A responsive, minimalist academic homepage for GitHub Pages. No frameworks, dependencies, or build tools required.

## Publish it

1. Sign in at https://github.com.
2. Create a **public** repository called `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your GitHub username).
3. In the repository, choose **Add file → Upload files**. Upload `index.html` and `favicon.svg` from this folder. `README.md` is optional. The two site files must be at repository **root**, not inside an `academic-website` folder.
4. Choose **Commit changes** (to `main`).
5. Navigate to **Settings → Pages → Build and deployment**. Set **Source** to `Deploy from a branch`; branch `main`; folder `/ (root)`; **Save**.
6. After GitHub publishes your site, open `https://YOUR-USERNAME.github.io/`.

Reference: https://docs.github.com/en/pages/quickstart

## Personalize before sharing publicly

- **Profile photograph:** Put `profile.jpg` in repository root and replace the `SM` initials in the `.avatar` div with `<img src="profile.jpg" alt="Portrait of Suman Mandal">` (the HTML includes a comment showing this).
- **Publications:** In `index.html`, replace or remove the two clearly marked sample entries. Confirm author order, article title, volume, page/article number and DOI using publisher records. Replace the temporary `href="#publications"` with a real DOI URL.
- **CV:** Upload a PDF named `cv.pdf` in repository root. In `index.html`, replace the CV placeholder paragraph with `<a class="action" href="cv.pdf" target="_blank" rel="noopener">Download CV (PDF)</a>`.
- **Contact/profile links:** Replace email and Scholar/ORCID/GitHub placeholders with real details and HTML `<a>` tags.
- **Research:** Adjust summaries and affiliation to match your current bio.

## Updates

Open your repository, click `index.html` → pencil icon **Edit this file** → make your changes → **Commit changes**. GitHub Pages will republish after the commit.

## Common problems

- **404:** Verify the exact repository name, `index.html` at repository root, and Pages branch/folder settings. Check the repository **Actions** tab for deployment status.
- **Image or CV missing:** Filenames and letter case must match exactly; upload files to repository root.
- **No styling:** Make sure you uploaded the provided full `index.html` without deleting its `<style>` section.
- **Security/privacy:** GitHub Pages is publicly accessible; avoid posting personal addresses or unpublished research you do not intend to share.
