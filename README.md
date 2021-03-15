# Actions after cloning

- Make sure you have ruby installed. Install bundler.
- Make sure you have installed the page dependencies (`bundle install`)

# Run page locally

`bundle exec jekyll serve --watch`

# Publishing the website

``` bash
./gh-pages-deploy.sh
```

## Initial Repo Set-Up

This is just a documentation of the steps after `git init`, no need to perform these commands for publishing the website.

This sets up a branch "gh-pages" which is not related to the contents of the 
master branch. Using `git worktree` (see gh-pages-deploy.sh), the contents of 
the _site folder can be committed to this branch.

``` bash
git checkout --orphan gh-pages
git reset --hard
git commit --allow-empty -m "Init"
git checkout master
```
