# Welcome to git-wiki demo

This is both documentation and [demo](wiki/Demo.md) of git-wiki theme for jekyll.

it's a modular and full featured wiki powered by git, github pages and pull-requests!

It means: 

* Improvements in the cooperative aspect: forks, pull-requests and roles.
* You can customize your wiki as you want with style sheets and even changing the layout.
* No databases! Only static files that can be downloaded in a few seconds.
* Markdown and html mixed together!
* History, revision comparison and everything you need from a wiki platform.
* You can edit your pages with the standard git editor, prose.io (integrated) or any kind of editor you prefer.
* Non-existent wiki page links are "[red](wiki/red.md)"
* Component system with hooks that allows you to totally customize your wiki UI.

You can fork/copy the master branch now and start your wiki in just 1 minute.

**Note:**
You can even include the [official github wiki](https://help.github.com/articles/about-github-wikis/) as a submodule and enable the option in our conf file to use github wiki pages in git-wiki system, but it's an experimental feature and it implies less advantages and greater disadvantages for now.

## Who is using git-wiki

[List of git-wiki installations](wiki/examples.md)

[List of forked repository](https://github.com/Drassil/git-wiki/network/members)


### [share your wiki with us!](wiki/examples.md) and keep the "Power by Git-Wiki" footer link please. It will help both of us!


## Installation instructions

1. Fork or copy [this repository](https://github.com/drassil/git-wiki)

2. copy and rename _config.yml.dist in _config.yml changing settings inside

3. create your index.md in root directory

4. push your changes in your repository, then configure the github pages in your repository settings

5. Your wiki is ready!

**Note:**

We suggest the creation of a /wiki/ subfolder that collects all your .md pages (except index.md)

## Configuration and customization

Read documentation about [Customization HERE](wiki/customize.md)


## Current known limitations

* You can't use the wiki internal link format: [[example]]. Please, use gh-pages links instead: \[example\](example) . It's a known jekyll limitation: <https://jekyllrb.com/docs/templates/>


## Support & Collaboration

You can open a public issue on [github](https://github.com/Drassil/git-wiki/issues) , send a private <a href="mailto:staff-drassil@googlegroups.com">email</a>  or create a PR to improve it.

Thank you!

## Components used

- [jekyll-table-of-contents](https://github.com/ghiculescu/jekyll-table-of-contents)

- [jQuery](https://jquery.com/) for DOM manipulation


[MIT LICENSE](LICENSE)