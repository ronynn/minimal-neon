# Jekyll Theme Minimal-Neon

Minimal-Neon is a Jekyll Theme inspired by computer terminals. You can [preview the theme to see what it looks like](https://ronynn.github.io/minimal-neon), or even [use it today](#usage).\*

## Contents

-   [Get Started](#get-started)
-   [Make it yours](#make-it-yours)
-   [Usage](#usage)
-   [Customizing](#customizing)
    -   [Configuration Variables](#configuration-variables)
    -   [Stylesheet](#stylesheet)
    -   [Layouts](#layouts)
-   [Roadmap](#roadmap)
-   [Project Philosophy](#project-philosophy)
-   [Contributing](#contributing)
-   [Author](#author)
-   [License](#license)

## Get started

First, follow the steps in this [Quickstart Guide](https://jekyllrb.com/docs/) if you're starting with Jekyll from scratch. Skip this if you already have an existing jekyll project.

1. [Fork the repository](https://github.com/ronynn/minimal-neon/fork)

2. Clone the repository: `git clone https://github.com/username/minimal-neon`

3. Run `bundle install`

4. Run Jekyll: `jekyll serve -w`

5. Go to http://localhost:4000 for your site.

## Make it yours

1. Edit `_config.yml`, then rerun `jekyll serve -w`

2. Change `about.md` for blog intro

3. For domain settings see [the guide from GitHub](https://help.github.com/articles/setting-up-a-custom-domain-with-pages)

## Usage

To use the minimal-neon theme on github pages:

1. Add the following to your site's `_config.yml`:

    ```yml
    remote_theme: ronynn/minimal-neon
    plugins:
        - jekyll-remote-theme # add this line to the plugins list if you already have one
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```

## Customizing

### Configuration variables

minimal-Neon will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:

    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```

3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

_Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet._

### Layouts

If you'd like to change the theme's HTML layout:

1. For some changes you can add custom files in your local `_includes` folder. The files provided with the themeprovide a starting point and are included by the [original layout template]
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

## Roadmap

See the [open issues](https://github.com/r01nx/minimal-neon/issues) for a list of proposed features (and known issues).

## Project philosophy

The minimal-neon theme is something I always wanted to put together. It gives the futuristic vibe one gets from the movies and yet remains eye pleasing and readable.

The theme structure is intended to make it quick and easy for users to create a website, it provides the user the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout).

## Contributing

Interested in contributing to minimal-neon? I'd love your help. minimal-neon is an open source project.

## Author

[rohan](https://github.com/ronynn)

## License

Open sourced under the [MIT license](LICENSE.md).

<3
