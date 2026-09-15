# Nightshade Black — GitHub Pages

A static HTML website. No installation or build command is required.

## Publish on GitHub Pages

1. Create a GitHub repository, or open the repository you want to use.
2. Unzip `nightshade-black-github.zip` on your computer.
3. Upload the extracted files and the entire `assets` folder to the repository's top level. `index.html` must be directly in the repository root, not inside another folder. Upload the extracted contents, not the ZIP itself.
4. Commit the files to the `main` branch.
5. Open **Settings → Pages** in the repository.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Select **main** and **/ (root)**, then click **Save**.
8. Wait for GitHub to finish publishing. The Pages settings screen will show your website link.

If your file picker hides `.nojekyll`, create it in GitHub using **Add file → Create new file**. It is an empty file that tells GitHub to serve this site directly.

The usual project website address is `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`. Use the exact address shown in Pages settings.

## Files

```text
index.html
style.css
.nojekyll
.gitignore
README.md
assets/
  backdrop.png
  reference.png
```

All stylesheet and image links are relative, so the site works under a repository subdirectory and on a custom domain. No Sites credentials, hosting configuration, or local server are needed.

## Editing

- Edit `index.html` for page text, navigation, and FAQ answers.
- Edit `style.css` for colors, typography, spacing, and responsive styles.
- Keep both images in `assets`. The card images use positioned portions of `reference.png`.
- The membership button currently opens a preview notice. Connect a real enrollment destination before accepting memberships.
- Journal and Shop currently link to sections of this single-page preview. Social symbols are decorative, not connected profile links.
- FAQ answers are draft copy; review them before launch.

## Official GitHub instructions

- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
