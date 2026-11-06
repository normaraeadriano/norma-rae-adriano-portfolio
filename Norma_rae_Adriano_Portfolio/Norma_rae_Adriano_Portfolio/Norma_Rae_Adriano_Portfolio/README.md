# Norma Rae Adriano — Portfolio Website

## Files
- `index.html` — responsive portfolio website.
- `assets/` — resume, certificate, work samples, workstation image, and optimized display images.

## Preview locally
Open `index.html` in a modern browser. All website assets are stored in the `assets` folder, so keep that folder beside `index.html`.

## Publish with GitHub Pages
1. Sign in to GitHub and open your portfolio repository (or create a new public repository).
2. Upload **all contents** of this folder: `index.html`, the `assets` folder, and this README. Do not upload only the ZIP file.
3. Commit the files to the `main` branch.
4. Open the repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then click **Save**.
7. Wait for GitHub Pages to finish publishing. The live URL will appear in Settings → Pages.

## Update the portfolio later
- Edit `index.html` to update text, experience, links, and sections.
- To replace a work sample, upload the new file into `assets/` and update its link in `index.html`. Keep filenames exact (or change the matching link).
- To add an Excel sample, upload the `.xlsx` file to `assets/`, then add a link like `<a href="assets/your-file.xlsx" download>Download Excel sample</a>` in the relevant work-sample card.
- To replace the profile placeholder, add your headshot as `assets/profile-photo.jpg`, then replace the `<div class="portrait">NR</div>` element with `<img class="portrait-photo" src="assets/profile-photo.jpg" alt="Norma Rae Adriano">` and add `.portrait-photo{width:100%;height:280px;object-fit:cover;border-radius:9px}` to the CSS.
- To replace the resume, upload the new PDF as `assets/resume.pdf` so the existing download link continues to work.

## Move to another host
Upload the entire folder, preserving the `assets` subfolder, to any static hosting provider that supports HTML, CSS, and JavaScript (for example Netlify, Cloudflare Pages, or standard web hosting). Set `index.html` as the site entry page.

## Accuracy notes
The content is based on the supplied resume and portfolio ZIP. No unverified metrics or achievements have been added. Some roles overlap in the source resume; dates have been retained as supplied. The ZIP did not contain a separate professional headshot, so the website uses an initials placeholder until one is provided.
