# Bakhtawar — Portfolio Website

A static, multi-page student portfolio built with HTML, CSS and a small amount of vanilla JavaScript. It is designed for GitHub Pages and does not need a build tool, package manager, database or server.

## Included files

```text
bakhtawar-portfolio-ready/
├── index.html
├── project-student-hub.html
├── 404.html
├── robots.txt
├── sitemap.xml
├── .nojekyll
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── assets/
    ├── favicon.svg
    ├── social-preview.svg
    ├── social-preview.png
    ├── student-hub-dashboard.svg
    └── student-hub-welcome.svg
```

## Publish to the existing GitHub repository

1. Download and extract the ZIP on your computer.
2. Open the extracted `bakhtawar-portfolio-ready` folder.
3. Open your GitHub repository: <https://github.com/b92727077-cpu/bakhtawar-portfolio>.
4. Choose **Add file → Upload files**.
5. Open the extracted folder on your computer and select **all files and folders inside it**. Do not upload the ZIP itself, and do not upload only the outer folder.
6. Drag the selected contents into the GitHub upload area. Make sure `index.html` appears at the top level of the repository, not inside another nested folder.
7. Scroll down and choose **Commit changes**.
8. Keep GitHub Pages set to **Deploy from a branch → main → /(root)**. A new commit should trigger a fresh Pages deployment.
9. Open the repository's **Actions** tab and check the latest `pages build and deployment` run. A green check means the deployment completed.

The live site should remain at:

<https://b92727077-cpu.github.io/bakhtawar-portfolio/>

## Preview locally

Double-click `index.html` to preview the home page in a browser. Open `project-student-hub.html` to preview the project case study. Some hosted fonts require an internet connection; system fonts are used as fallbacks.

## Personal details and privacy

- The public contact method is the GitHub profile link. No phone number, home address, school name, personal email or private account details are included.
- If you later choose to publish a professional email address, add it deliberately to the Contact section in `index.html`.
- Only one social profile is linked because GitHub is the only profile URL currently confirmed.
- Skills are described as foundations, practice or exploration. Update their wording only when there is practical evidence to support a stronger claim.

## About the Student Hub preview

The two Student Hub images are **illustrative reconstructions** based on the project's public HTML source. They are not direct browser screenshots. Replace them with real captures from the live Student Hub when available. The case study distinguishes repository files and source-code evidence from workflows that still need live testing.

## Editing content

- Home page, About, Skills, Learning and Contact: edit `index.html`.
- Student Hub case study: edit `project-student-hub.html`.
- Colours, spacing, typography and responsive layout: edit `css/styles.css`.
- Mobile navigation and footer year: edit `js/main.js`.
- Browser tab icon and social-share card: edit the SVG files in `assets/`.

## Technical notes

- Semantic HTML landmarks, labelled navigation, a skip link and visible keyboard focus styles are included.
- Responsive layouts support desktop, tablet and mobile widths.
- Motion is kept minimal and reduced-motion preferences are respected.
- SEO metadata, descriptive page titles, Open Graph metadata, a sitemap and `robots.txt` are included.
- All internal paths are relative, so the site works under the GitHub Pages project path.
