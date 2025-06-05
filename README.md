# docs-to-pdf

support convert docusaurus website to pdf.

docs-to-pdf support convert docusaurus website to pdf using sphinx, myst plugin and other custom plugins.

- support html table
- support link in table
- support tabitem

## quick start

### install docsaurus and create website

create docusaurus website according to [offical guide](https://docusaurus.io/docs),such as:

```shell
(base) ➜  docs-to-pdf git:(main) ✗ npx create-docusaurus@latest website classic
Need to install the following packages:
  create-docusaurus@3.8.0
Ok to proceed? (y) y
✔ Which language do you want to use? › JavaScript
[INFO] Creating new Docusaurus project...
[INFO] Installing dependencies with npm...
[SUCCESS] Created website.
[INFO] Inside that directory, you can run several commands:

  `npm start`
    Starts the development server.

  `npm run build`
    Bundles your website into static files for production.

  `npm run serve`
    Serves the built website locally.

  `npm run deploy`
    Publishes the website to GitHub pages.

We recommend that you begin by typing:

  `cd website`
  `npm start`

Happy building awesome websites!

```

### install sphinx and init project

Install sphinx accroding to [offical guide](https://www.sphinx-doc.org/en/master/usage/installation.html).

Then execute command:

```shell
sphinx-quickstart
```
