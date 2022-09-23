# Eccentrist

Eccentrist is designed to be a powerful, lightweight theme for [Hugo](https://gohugo.io). It's built using Tailwind CSS with a clean and minimalist design that prioritises to your content.

🌏 [Demo site](https://mrglitchbyte.github.io/eccentrist/)  
📑 [Theme documentation](https://mrglitchbyte.github.io/eccentrist/docs/)  
🐛 [Bug reports & issues](https://github.com/mrglitchbyte/eccentrist/issues)  
💡 [Questions & feature requests](https://github.com/mrglitchbyte/eccentrist/discussions)

![Screenshot](https://raw.githubusercontent.com/mrglitchbyte/eccentrist/stable/images/screenshot.png)

## Features

-   Fully responsive layout built with Tailwind CSS 3.0
-   Multiple colour schemes (or fully customise your own)
-   Dark mode (forced on/off or auto-switching with user toggle)
-   Highly customisable configuration
-   Multiple homepage layouts
-   Flexible with any content types, taxonomies and menus
-   Multilingual content support inlcuding support for RTL languages
-   Ability to link to posts on third-party websites
-   Client-side site search powered by Fuse.js
-   Diagrams and visualisations using Mermaid
-   Charts using Chart.js
-   Mathematical notation using KaTeX
-   SVG icons from FontAwesome 6
-   Automatic image resizing using Hugo Pipes
-   Heading anchors, Tables of Contents, Code copy, Buttons, Badges and more
-   HTML and Emoji support in articles 🎉
-   SEO friendly with links for sharing to social media
-   Fathom Analytics and Google Analytics support
-   RSS feeds, Favicons and comments support
-   Advanced customisation using simple Tailwind colour definitions and styles
-   Optimised for performance and accessibility with perfect Lighthouse scores
-   Fully documented with regular updates

* * *

## Documentation

Eccentrist has [extensive documentation](https://mrglitchbyte.github.io/eccentrist/docs/) that covers all aspects of the theme. Be sure to [read the docs](https://mrglitchbyte.github.io/eccentrist/docs/) to learn more about how to use the theme and its features.

* * *

## Installation

Eccentrist supports several installation methods - as a Hugo Module (easiest), a git submodule, or as a completely manual install.

Detailed instructions for each method can be found in the [Installation](https://mrglitchbyte.github.io/eccentrist/docs/installation) docs. You should consult the documentation for the simplest setup experience. Below is a quick start guide using Hugo modules if you're already confident installing Hugo themes.

### Quick start using Hugo

> **Note:** Ensure you have **Go** and **Hugo** installed, and that you have created a new Hugo project before proceeding.

1.  From your project directory, initialise Hugo Modules:

    ```shell
    hugo mod init github.com/<username>/<repo-name>
    ```

2.  Create `config/_default/module.toml` and add the following:

    ```toml
    [[imports]]
    path = "github.com/mrglitchbyte/eccentrist/v2"
    ```

3.  Start your server using `hugo server` and the theme will be downloaded automatically.

4.  In the root folder of your website, delete the `config.toml` file that was generated by Hugo. Copy the `*.toml` config files from the theme into your `config/_default/` folder.

    > **Note:** Do not overwrite the `module.toml` file you created above!

    You will find these theme config files in the Hugo cache directory, or [download a copy](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/mrglitchbyte/eccentrist/tree/stable/config/_default) from GitHub.

5.  Follow the [Getting Started](https://mrglitchbyte.github.io/eccentrist/docs/getting-started/) instructions to configure your website.

### Installing theme updates

As new releases are posted, you can update the theme using Hugo. Simply run `hugo mod get -u` from your project directory and the theme will automatically update to the latest release.

Detailed [update instructions](https://mrglitchbyte.github.io/eccentrist/docs/installation/#installing-updates) are available in the docs.

* * *

## Contributing

Eccentrist is expected to evolve over time. I intend to keep adding features and making changes as required.

Feel free to get in touch with any issues or suggestions for new features you'd like to see.

-   🐛 **Bug reports & issues:** Use [GitHub Issues](https://github.com/mrglitchbyte/eccentrist/issues)
-   💡 **Ideas for new features:** Open a discussion on [GitHub Discussions](https://github.com/mrglitchbyte/eccentrist/discussions)
-   🙋‍♀️ **General questions:** Head to [GitHub Discussions](https://github.com/mrglitchbyte/eccentrist/discussions)

If you're able to fix a bug or implement a new feature, I welcome PRs for this purpose. Learn more in the [contributing guidelines](https://github.com/mrglitchbyte/eccentrist/blob/dev/CONTRIBUTING.md).
