# Hrishikesh's Homepage

Built using `hugo-academic` starter template

## Steps

* [Install Hugo](https://gohugo.io/getting-started/installing/)
* Go to "Hugo Academic" [Starter Template](https://github.com/wowchemy/starter-hugo-academic)
* Click on **Use this template** to create a repository `www` (you may choose a different name)
* Clone your repository locally `git clone git@github.com:<your-username>/www.git www`
* `cd www`
* `git submodule update --init --recursive`
* Create an empty repository `<your-username>.github.io` on GitHub, if you haven't already.
    * Note: If you do not have GitHub premium, this must be a public repository in order to use GitHub Pages
    * Set-up the GitHub Pages from repository settings.
* Add the website repository as a submodule,
`git submodule add -f -b master git@github.com:<your-username>/<your-username>.github.io.git public`
* Edit content in the `content` directory
* Test locally, `hugo server`
* Generate public pages, `hugo`. This will generate the static website in the `public/` directory.
* Commit content to the submodule (website repository) first, `cd public`, `git add .` and `git commit -m "Website"`
* Commit content to the base repository, `git add .` and `git commit -m "Content"`

## Reference

Documentation: https://wowchemy.com/docs/

