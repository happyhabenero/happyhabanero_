# 🌶️ Happy Habanero Research website

A beginner-friendly static GitHub Pages research portfolio.

## Publish it

1. Sign into GitHub as `happyhabanero_`.
2. Create a **public** repository named **`happyhabanero_.github.io`** (exactly).
3. Choose **Add file → Upload files**, and upload the **contents of this folder** (not the enclosing folder). Make sure `index.html` is at the repository root. For many files, GitHub Desktop or Git is easier than browser upload.
4. Commit the files to the `main` branch.
5. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then **Save**.
6. After deployment, open `https://happyhabanero_.github.io/`. It may take a few minutes.

## Update content

- Home: edit `index.html`.
- Project list: edit `projects/index.html`.
- New project: copy `projects/groundwater-example.html`, rename, edit, and link it from `projects/index.html`.
- Figures: add a PNG/SVG in `figures/`, then add an image card to `figures/index.html`.
- Visual styling: edit `assets/style.css`.
- Mascot: replace `assets/habanero.png`.
- Every saved commit provides a versioned record; push/commit changes to trigger redeployment.

## Important

This starter includes a **synthetic example chart**, not real hydrogeology data. Never upload DOE-restricted or unapproved data or unpublished findings. GitHub Pages is a public website; a private repository is not a guarantee of private site access. Git commit history does not itself determine authorship or ownership.

## Troubleshooting

If links or images fail, check that the repository name exactly matches the username and that the site is published at the root URL. GitHub usernames can contain underscores, and the Pages URL should preserve the underscore.
