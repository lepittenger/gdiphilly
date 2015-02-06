# gdiphilly

Current dev static site is located at:
[http://gdiphilly.github.io/gdiphilly/](http://gdiphilly.github.io/gdiphilly/)

## Installation

This is a jekyll website. In order to make changes to the site you will need to have jekyll set up and available via the command line.
See development docs at [http://jekyllrb.com/](http://jekyllrb.com/).


## Publishing to Github Pages

In order to make new changes live, you first must re-build the Jekyll site, then push your changes to the main `gh-pages` branch.
### Building new files to the static content

When you add a new post or page, or change the styles or templates, you must re-build the static content so the site can pick it up.
Read more [here](http://jekyllrb.com/docs/usage/):  

From the command line (with Jekyll installed) type:
`jekyll build`


## Pushing your changes

Add all your changes:  
`git add --all`

Commit and add a commit message:

`git commit` or `git commit -m 'my commit message'`

Push to the `gh-pages` branch:

`git push -u origin gh-pages`

## Adding new pages and posts

- [Jekyll Guide to creating new Posts](http://jekyllrb.com/docs/posts/)
- [Jekyll Guide to creating new Pages](http://jekyllrb.com/docs/pages/)
