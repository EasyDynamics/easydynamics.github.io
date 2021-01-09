# Guide to Easy Dynamics GitHub repositories

The guide to Easy Dynamics GitHub repositories is a [GitHub Pages](https://pages.github.com/) project that helps visitors and contributors 
navigate the software projects at Easy Dynamics. This readme is primarily to orient contributors for this repository. If you are a visitor 
or contributor at Easy Dynamics please visit the published version of this guide at [easydynamics.github.io](https://easydynamics.github.io/) 
to get further details about procedures and any other  to get started.

## Pre-requisites
- [Ruby](https://www.ruby-lang.org/en/downloads/) version 2.4.0 or higher.
- [RubyGems](https://rubygems.org/pages/download) this might already be included in the Ruby download based what you downloaded and installed.
- [Jekyll](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll#creating-a-repository-for-your-site)  see step 7 onwards.
- [Visual Studio Code](https://code.visualstudio.com/Download) preferred but not required for conducting development in an IDE.

## Development
This project is a Jekyll site, that use a [remote theme](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll) from Just the Docs and is hosted on GitHub Pages. The pages are primarily developed in Markdown and customization to the themes and layouts are done with SCSS and HTML. Most of the high level configuration can be found in [`_config.yml`](_config.yml) and is a mix of configuration from Jekyll and Just the Docs. To learn more about how to create and organize content refer to [Jekyll Docs](https://jekyllrb.com/docs/pages/). If you want to customize the layout and theme, refer to appropriate section under [Just the Docs - Customization](https://pmarsceill.github.io/just-the-docs/docs/customization/).

## Testing Locally
To test locally you can use serve up the files using
```
$ bundle exec jekyll serve --watch
```
If the server is running you can visit http://localhost:4000 to see what it looks like. With the `--watch` flag you can make changes to the content and
it will live reload the changes, without having to stop the server.

## Contributing
If you observe an issue on [easydynamics.github.io](https://easydynamics.github.io/), see if it's related to any of the [existing ones](https://github.com/EasyDynamics/easydynamics.github.io/issues) and join the conversation. If not, open a new issue and describe it for us. If you want to submit a change, open an issue first and then submit a pull request associated with the issue accordingly. Last but not least please follow [GitHub Community Guidelines](https://docs.github.com/en/free-pro-team@latest/github/site-policy/github-community-guidelines).