This is a custom Jekyll theme for Public Data Lab websites.

At the moment it supports only one-page websites compose by three sections:

* Cover image
* Introduction text
* Other texts.

(yes, it's veryveryvery simple).

# Install and live preview

It is base on the Jeckyll software.

To install it on a mac, follow these steps.

### 1. Clone locally this repository

If you're not used to GitHub, we strongly suggest to use [GitHub Desktop](https://desktop.github.com/).

Open the GitHub repository page.

Click on `Clone or Download` green button.

Click on `Open in Desktop`

GitHub Dekstop should open, follow the process throught the interface keeping the default options. 

### 2. Install jekyll

Follow [these instructions to install jekyll on your computer](https://jekyllrb.com/docs/installation/).

### 3. Local preview

To have a preview on your computer, open the terminal, browse to the website folder and then run the command`jeckyll serve`.

Done! Now open in any browser the url http://localhost:4000/.

# Edit the page contents

To edit the webiste content, just modify the `index.md` file.

In there you can use the [Markdown language](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to define the structure of contents.

We suggest to use [Typora](https://typora.io/) to edit the markdown.

All the content before the `<!--more-->` tag will be rendered as introduction.

All the content after the `<!--more-->`tag will be rendered as paragraph text.

# Edit metadata

Other that the contents, you can define the metadata (e.g. webpage title, theme colours, etc).

If you want to edit these details, modify the `_config.yml` file.