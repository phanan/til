# TIL

The source code for [my TIL site](https://til.phanan.net), powered by [Hugo](https://gohugo.io/) using [After Dark](https://comfusion.github.io/after-dark/) theme.

## Installation

1. Install Hugo
1. Install After Dark version 1.6.1 by copying the theme into `themes/after-dark` (the site was configured for this version and I'm just too lazy to upgrade)

## Development

1. Create a new post with `hugo new post/<post-name>.md`. Generally I'd use the date as the post name, so `hugo new post/27-01-17.md`.
1. Edit the post at will: `vi content/post/27-01-17.md`
1. Generate the content with `hugo --theme=after-dark`
1. Run the server with `hugo server`


## Deploy

1. Commit all changes
1. Run the deploy script: `bash _scripts/publish_toghpages.sh`
