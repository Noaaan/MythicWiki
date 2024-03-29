## Mythic Metals Wiki

This repository contains the basis of what the Mythic Metals Wiki is going to be. The [theme used is the same as Wisp Forest, albeit with a handful of changes](https://github.com/Noaaan/mythic-docs-theme), and is also included as a submodule in case you want to serve the site locally.

This Wiki is heavily work-in-progress. There are many details to be ironed out, such as structure, contribution guidelines, and tools for exporting the data from Mythic Metals into a Wiki-friendly format. Maintenance on this will also be somewhat slow, since the main focus right now is to finish the current feature set of Mythic Metals before expensively documenting it. 

### Building and Cloning

If you only want to make small modifications that do no require actually building the site, clone like normal:

`git clone https://github.com/Noaaan/MythicWiki.git`

If you want to make larger contributions, you will have to clone recursively via SSH. This is due to the current setup of the theme requires SSH authentication, and to serve the site locally you need the theme as well.

`git clone git@github.com:Noaaan/MythicWiki.git --recursive`

For building against the theme you need to install MkDocs via Pip (Python). To get started simply run the following:

`pip install mkdocs-material`

`pip install mkdocs-git-revision-date-localized-plugin`

`pip install mkdocs-video`

To serve simply use Mkdocs serve command:

`mkdocs serve`