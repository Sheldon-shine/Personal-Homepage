# Xiangdong Wen · Academic Homepage

This repository contains the Jekyll academic homepage configured from the supplied CV and based on the [academic-homepage template](https://github.com/luost26/academic-homepage).

## Update profile content

- `_data/profile.yml`: profile, education, skills, credentials, and honors
- `_publications/`: one Markdown file per publication; edit author role and publication status in its front matter
- `_data/navigation.yml`: site navigation
- `_data/display.yml`: homepage sections and footer

The CV does not list named research projects, paper DOIs, or publication links, so these have not been invented. The telephone number and sample portrait are excluded. The email address is shown because the owner requested it.

## Publish with GitHub Pages

The workflow in `.github/workflows/pages.yml` builds the Jekyll site and deploys it to GitHub Pages. In repository settings, choose **Settings → Pages → Build and deployment → GitHub Actions**. After the first successful workflow, the site is available at `https://sheldon-shine.github.io/Personal-Homepage/`.
