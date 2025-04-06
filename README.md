# 📚 Sphinx Documentation Site

This repository contains a documentation site powered by [Sphinx](https://www.sphinx-doc.org/) and deployed to **GitHub Pages**. It supports local preview and automated deployment via GitHub Actions.

This is just for my sphinx learning purpose.

---

## 📦 Requirements

Make sure you have Python and pip installed. Then install the dependencies:

```bash
pip install -r requirements.txt
```

Also install ghp-import (used for deployment):
```bash
pip install ghp-import
```

## Building the Docs
To build the HTML documentation locally:

```bash
cd docs
make html
```

The output will be generated inside:
```bash
docs/_build/html
```

## Preview Locally
To view the site in your browser before deploying:

```bash
cd docs/_build/html
open index.html
```




