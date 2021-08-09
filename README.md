# Hrishikesh's Homepage

Built using `hugo-academic` starter template

## Steps

* Go to "Hugo Academic" [Starter Template](https://github.com/wowchemy/starter-hugo-academic)
* Click on **Use this template** to create a repository `www` (you may choose a different name)
* Clone your repository locally `git clone git@github.com:<your-username>/www.git www`
* `cd www`
* `git submodule update --init --recursive`
* Create an empty repository `<your-username>.github.io` on GitHub, if you haven't already.
* `git submodule add -f -b master git@github.com:<your-username>/<your-username>.github.io.git public`
* Edit content in the `content` directory
* Test locally, `hugo server`
* Generate public pages, `hugo`
* Commit content to the base repository, `git add .` and `git commit -m "Content"`
* Commit content to the public repository, `cd public`, `git add .` and `git commit -m "Website"`

## Reference

Documentation: https://wowchemy.com/docs/

