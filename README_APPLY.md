# Shijia Xu — Academic Pages customization overlay

This folder is designed to be copied **on top of a fresh fork/template copy** of
`academicpages/academicpages.github.io`.

The content follows the current Academic Pages / Minimal Mistakes conventions for:
- site-wide author settings in `_config.yml`;
- header links in `_data/navigation.yml`;
- Markdown pages under `_pages`;
- publication entries under `_publications`;
- author avatar under `images/`.

The English homepage style is intentionally concise and academic, inspired by the
organization and tone of Zhaoxin Fan's homepage (About me → News → research → publications),
while all biographical and research content comes from the supplied LaTeX CV.

## Apply it

1. Create/fork a fresh Academic Pages repository named `YOUR_GITHUB_USERNAME.github.io`.
2. Delete the template's sample files in `_publications/` so they do not appear beside your papers.
3. Copy the contents of this overlay into the repository root, allowing files to overwrite.
4. In `_config.yml`, replace **every** `YOUR_GITHUB_USERNAME` placeholder.
5. Optional: add your Google Scholar, ORCID, GitHub and other profile links in `_config.yml`.
6. Commit and push. GitHub Pages will rebuild the site.

## Main customized files

- `_config.yml` — name, bio, institution, email, avatar, publication categories.
- `_data/navigation.yml` — Home / Publications / Projects / CV.
- `_pages/about.md` — homepage.
- `_pages/publications.html` — publication list, ordered without inventing exact publication dates.
- `_pages/projects.md` — project experience.
- `_pages/cv.md` — web CV converted from the LaTeX CV.
- `_publications/*.md` — seven publication records.
- `images/new_xsj.jpg` — profile photo.

## Privacy note

The public website includes the email address from the CV, but intentionally does **not** publish the phone number. If you want the phone number public as well, add it manually to the CV page.

## Source consistency note

The supplied LaTeX uses **“M.S. Candidate”** in the header and **“M.E. Candidate”** in the detailed education section. The public homepage/sidebar therefore uses the neutral phrase **“Master's candidate”**, while the web CV preserves **“M.E. Candidate”** from the education entry.
