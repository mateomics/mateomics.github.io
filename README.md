# Personal Academic Website

This repository contains the source code for my personal academic website, built with **Quarto** and hosted via **GitHub Pages**.

**Live site:** https://YourGitHubUserName.github.io

## Overview

The website includes:

* **About** – short academic profile
* **CV** – curriculum vitae and training
* **Projects / Research** – ongoing and past research work
* **Posts / Notes** – short posts on research, tools, or ideas

The site is generated using [Quarto](https://quarto.org/) and automatically deployed through GitHub Pages.

## Repository Structure

```
.
├── _quarto.yml          # Website configuration
├── index.qmd            # Homepage
├── cv.qmd               # Curriculum Vitae
├── posts/               # Blog / research notes
├── files/               # Images, PDFs, assets
├── styles.css           # Custom styling
└── docs/                # Rendered site (published by GitHub Pages)
```

## Updating the Website

To update the website:

1. Edit or add `.qmd` files.
2. Render the site locally:

```
quarto render
```

3. Commit and push the changes:

```
git add .
git commit -m "Update website"
git push
```

GitHub Pages will automatically publish the updated version.

## Built With

* [Quarto](https://quarto.org/)
* [GitHub Pages](https://pages.github.com/)

## License

Content © Mateo Jiménez Sotelo.
Feel free to reuse the structure of this repository if helpful, but please do not reuse personal content without permission.

## Acknowledgments

This website is based on the **Quarto Academic Website Template** developed by Gang He.

Template repository and documentation:
https://github.com/drganghe/quarto-academic-website-template

