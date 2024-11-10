# Public SAM XL Documentations

This repository hosts and deploys SAM XL public documentations on (sam-xl.github.io)(https://sam-xl.github.io/). 
Github Action and Github Page are integrated for minimal effort in managing contents. 
User only need add and modify makrdown files to update the webpage.

## Create a new page
1. Add a `.md` file in `docs` directory
1. Update navigation tree in `mkdocs.yml` under `nav: ` key.
1. Push changes and Github Action will handle the rest

## Update content of a page
1. Update `.md` file in `docs` directory 
1. Push changes and Github Action will handle the rest

## Advanced Features
Mkdocs support advanced documentation features, such as Latex, Code Block, Diagram, Emoji, Buttons, etc. Refer https://squidfunk.github.io/mkdocs-material/reference for more details.

