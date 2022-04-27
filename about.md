---
title: About
---

## Usage

To use the minimal-neon theme on github pages:

1. Add the following to your site's `_config.yml`:

    ```yml
    remote_theme: r01nx/minimal-neon
    plugins:
    - jekyll-remote-theme # add this line to the plugins list if you already have one
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```