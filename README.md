# electronworkshop.com.au

Electron Workshop Main Website

This is using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/getting-started/), a utility to create documentation website from markdown files.

## Quick Start

Here's how you can get started locally by first running these commands

1. **Build the website:**

   Run `make build` to compile the website into HTML files that you can view in your web browser.

2. **Serve the website:**

   Run `make serve` to start a local web server and open the website in your default browser.

3. **Clean build artifacts:**

   Run `make clean` to remove any generated files from the `website` directory.

4. **Add a new post to blog**

   Run `./util/createPost.py` to add a new blog post

### Dev Note

The make script internally also setup a virtual enviroment which would install the required mkdocs and mkdocs-material plugins plus a few other useful plugins for this website. 

```bash
pip install virtualenv
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
