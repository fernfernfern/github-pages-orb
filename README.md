# GitHub pages orb

Inspired by [this blog post](http://sangsoonam.github.io/2019/02/08/using-git-worktree-to-deploy-github-pages.html). The GitHub pages orb keeps the source code of your jekyll site and the deployment of that site in two separate branches - `master` and `gh-pages`. This allows your jekyll site to be built in CircleCI rather than GitHub pages. This has a couple of advantages:

1. Use the latest versions of jekyll and its available plugins rather than the limited set allowed by GitHub pages. Such as the `jekyll-paginate-v2` plguin, which allows for paginating collections.

1. Have your compiled jekyll site automatically linted and validated before it deploys. Preventing errors that could break your site or reduce its SEO.

## get started

You can start by [forking the example repo](https://github.com/fernfernfern/github-pages-orb-example) and following the instructions in the Readme.
