# Guide to Easy Dynamics GitHub repositories

The guide to Easy Dynamics GitHub repositories is a [GitHub Pages](https://pages.github.com/) project that helps visitors and contributors 
navigate software projects at Easy Dynamics. The purpose of this readme is to orient contributors of **this repository**. If you're new to software development at Easy Dynamics, please visit the published version of this guide at [easydynamics.github.io](https://easydynamics.github.io/) 
to learn more about the procedures and how to get started with contributing.

## Pre-requisites
- [Ruby](https://www.ruby-lang.org/en/downloads/) version 2.4.0 or higher.
- [RubyGems](https://rubygems.org/pages/download) this might already be included in the Ruby download based what you downloaded and installed.
- [Jekyll](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll#creating-a-repository-for-your-site)  see step 7 onwards.
- [Visual Studio Code](https://code.visualstudio.com/Download) preferred but not required for conducting development in an IDE.

## Development
This project is a Jekyll site that uses a [remote theme](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll) from [Just the Docs](https://pmarsceill.github.io/just-the-docs/), and is hosted on [GitHub Pages](https://pages.github.com/). The pages are primarily developed in Markdown and proceessed via [kramdown](https://kramdown.gettalong.org/). Customization to the themes and layouts are done with [SCSS](https://sass-lang.com/documentation/syntax#scss) and HTML. Most of the high level configuration can be found in [`_config.yml`](_config.yml) and is a mix of configuration from Jekyll and Just the Docs. To learn more about how to create and organize content refer to [Jekyll Docs](https://jekyllrb.com/docs/pages/). To customize the layout and theme, refer to the appropriate section under [Just the Docs - Customization](https://pmarsceill.github.io/just-the-docs/docs/customization/).

## Testing Locally
Test the site locally by running the following command:
```
$ bundle exec jekyll serve --watch
```
Once the server is up and running, visit http://localhost:4000 in a browser to validate the layout and content. The `--watch` flag allows you to change  content without having to stop and restart the server (live reload).

## Contributing
If you notice a bug or want to report an issue with [easydynamics.github.io](https://easydynamics.github.io/), see if it's related to any of the [existing ones](https://github.com/EasyDynamics/easydynamics.github.io/issues) and join the conversation. If not, open a new issue and describe it for us. If you want to fix minor bugs or issues, feel free to open a pull request with the appropriate changes. For broader topics, start a conversation on an issue and build consensus with the maintainers before creating a pull request. Last but not least, please follow [GitHub Community Guidelines](https://docs.github.com/en/free-pro-team@latest/github/site-policy/github-community-guidelines).
