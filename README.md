# EADocsTemplate

### See the generated documentation on [this GitHub Page](https://eaceto.github.io/EADocsTemplate)

This is a GitHub Template for writing documentation for GitHub Pages. I tried to sum up in this template a series of tools / good practices that allows me, and any developer, to make professional documentation easily.

# Getting Started

## Creating a new repository

Create GitHub Repository using this template. For doing this, you can click on the following [link](https://github.com/eaceto/EADocsTemplate/generate), and complete the required information:

* Owner
* Repository name

It is not necessary to **Include all branched**, in fact this template has only **one branch**.

![/docs/home/github-new-repository.png](/docs/home/github-new-repository.png)

Then, setup your GitHub Page configuration to render Pages from **main** branch and **/docs** folder.

![/docs/home/github-pages-setup.png](/docs/home/github-pages-setup.png)

## Integrating into existent one

This is simple as doing a copy/paste of the **docs** folder inside the docs folder or branch your are using when rendering your GitHub Page. Then ensure that GitHub Pages settings are according to your repository configuration.

## Documentation structure

### Side Bar

**_sidebar.md** contains a list of links that will be rendered on the left.

### Navigation Bar

**_navbar.md** contains a list if lints that will be rendered on the upper-right corner.

### Content

The rest of the files included can modified, or even deleted if you want. It's just Markdown! [Docsify](https://docsify.js.org/#/) does the magic.