# [github-wiki.github.io](https://github-wiki.github.io/)
Unofficial Wiki about GitHub usage
* auto-gen TOC:
{:toc}

# Automatically Generated Table of Contents
* [Insert automatically generated table of contents TOC on rendered markdown files like README.md](https://github.com/isaacs/github/issues/215)

## GitHub Pages (Markdown)
**GitHub Pages use a different Markdown as repository viewer!**

### [Automatic TOC in github-flavoured-markdown](https://stackoverflow.com/questions/9721944/automatic-toc-in-github-flavoured-markdown)
>GitHub Pages (which is basically a wrapper for Jekyll) [appears to use][] [kramdown][], which implements all of [Maruku][], and [therefore] has support for an automatically generated table of contents via atoc attribute:

[appears to use]: https://github.com/jekyll/jekyll/blob/master/lib/jekyll.rb#L29 "jekyll/jekyll"
[kramdown]: https://kramdown.gettalong.org/parser/kramdown.html
[Maruku]: https://github.com/bhollis/maruku/blob/master/docs/markdown_syntax.md "bhollis/maruku"
[therefore]: https://github.com/bhollis/maruku/blob/master/docs/math.md "See source code for this page"
```md
* auto-gen TOC:
{:toc}
```

## Inside GitHub (AsciiDoc)
* Issue 215, [comment 336328746](https://github.com/isaacs/github/issues/215#issuecomment-336328746)
* [AsciiDoc](https://en.wikipedia.org/wiki/AsciiDoc "Wikipedia")
* [AsciiDoc cheatsheet](http://powerman.name/doc/asciidoc)

# Markups
* https://github.com/github/markup

## GitHub Flavored Markdown (GFM)
* https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown

# Inline HTML
* [*Which inline html styles does GitHub markdown accept?*](https://stackoverflow.com/questions/44831505/which-inline-html-styles-does-github-markdown-accept "stackoverflow")
* https://github.com/jch/html-pipeline/blob/master/lib/html/pipeline/sanitization_filter.rb

# GitHub pages
* [*Customizing GitHub Pages*](https://help.github.com/categories/customizing-github-pages/ "GitHub Help")

## Kramdown
* [*Quick Reference*](https://kramdown.gettalong.org/quickref.html)
* [*kramdown Syntax*](https://kramdown.gettalong.org/syntax.html)
* [Markdown Kramdown Tips & Tricks](https://about.gitlab.com/2016/07/19/markdown-kramdown-tips-and-tricks/)

[![ruby-kramdown @Debian][]](https://tracker.debian.org/pkg/ruby-kramdown) <!--- or with css: img[alt=...] { width: 9%; } -->

[ruby-kramdown @Debian]: https://qa.debian.org/cgi-bin/popcon-png?packages=ruby-kramdown&show_installed=on&date_fmt=%25Y
{: width="9%"}

### Lint
* See [Setting up your GitHub Pages site locally with Jekyll](#setting-up-your-github-pages-site-locally-with-jekyll)
* markdownlint / [markdownlint](https://github.com/markdownlint/markdownlint)
* DavidAnson / [markdownlint](https://github.com/DavidAnson/markdownlint)
* https://www.npmjs.com/package/markdown-lint

## Jekyll
* [*Using Jekyll as a static site generator with GitHub Pages*](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/ "GitHub Help")

### Setting up your GitHub Pages site locally with Jekyll
* [*Setting up your GitHub Pages site locally with Jekyll*](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/ "GitHub Help")

### Configuring Jekyll \_config.yml
* [*Configuring Jekyll*](https://help.github.com/articles/configuring-jekyll/ "GitHub Help")
* [*Configuring Jekyll plugins*](https://help.github.com/articles/configuring-jekyll-plugins/ "GitHub Help")
* [*Updating your Markdown processor to kramdown*](https://help.github.com/articles/updating-your-markdown-processor-to-kramdown/ "GitHub Help")
* [\_config.yml](https://google.com/search?q=_config.yml)

## Modifying an old branch and propagating changes to more recent ones
* [*Merging a pull request on GitHub*](https://help.github.com/articles/merging-a-pull-request/#merging-a-pull-request-on-github)
* [*About Git rebase*](https://help.github.com/articles/about-git-rebase/)
* [*About pull request merges*](https://help.github.com/articles/about-pull-request-merges/)
* [*Rebase and merge your pull request commits*](https://help.github.com/articles/about-pull-request-merges/#rebase-and-merge-your-pull-request-commits)

# See also
* [travis-util.github.io](https://travis-util.github.io/)
