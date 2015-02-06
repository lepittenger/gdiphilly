# gdiphilly
Repo for GDIPhilly.com

## Installation

This is a jekyll website. In order to make changes to the site you will need to have jekyll set up and available via the command line.
See development docs at [http://jekyllrb.com/](http://jekyllrb.com/).


## Publishing to Github Pages

In order to make new changes live, you first must re-build the Jekyll site, then push the `_site` folder to the `gh-pages` branch.

### Building new files to the static content

When you add a new post or page, or change the styles or templates, you must re-build the static content so the site can pick it up.
Read more [here](http://jekyllrb.com/docs/usage/):  

From the command line (with Jekyll installed) type:
`jekyll build`


## Pushing the `_site` folder to `gh-pages`

In order to push just a subdirectory to the `gh-pages` branch, use this command:

```
git subtree push --prefix _site origin gh-pages
```

## Adding new pages and posts

- [Jekyll Guide to creating new Posts](http://jekyllrb.com/docs/posts/)
- [Jekyll Guide to creating new Pages](http://jekyllrb.com/docs/pages/)
