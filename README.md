# Site Nav Test Drive

## Why you need it

- Try out new navigation with usability tests in realtime on a working site.
- Validate card sorts and tree jacks with qualitative research.
- Work out thorny information architecture issues before your team starts coding.

## How it works
1. Define your new navigation labels with links to the current site.
1. Enter the address of your current site.
1. Enter the address of your current site.

You now have a working navigation component layered on top of the current site that testers can use to experience the current content in a new way!

## How to…

### Speak GitHub

GitHub uses some different language to describe things and actions you're probably already familiar with. See this handy [GitHub Glossary](https://github.com/Bixal/methods/wiki/GitHub-glossary) if you're not sure about some of the terms used in these instructions.

### Make your own copy of the repository

1. If you don't have one, [create a GitHub account](https://github.com/signup).
1. On the `Code` tab of the repository homepage, press the `Use this template` button.
1. Finish creating your copy of the repository.

### Go live using GitHub Pages

GitHub Pages will compile and host your site automatically. Enable this feature first so you can see your changes in the browser without having to run the site locally.

> **Note: It takes a few seconds to a minutes to go live, so the first time you go to the site, you may see a "404: Page Not Found" error. After it's live, you should see any changes you make to the `main` branch at the Pages URL, usually within a few seconds.**

1. Go to the `Settings` tab.
1. Go to `Pages` in the side navigation.
1. In the `Source` section, set the branch to `main` and press Save.

> *Tip*: Copy the Pages URL and add it to your repository About section for easy access. The About section is on in the sidebar of the repository homepage. To edit it, click the gear icon. You can also see the log of publishing activity by pressing the `Environments` link in the sidebar on the repository homepage.

### Configure settings

You'll need to change a few settings in the config file for your site to work properly.

#### Project site settings

1. Go to the [_config.yml](_config.yml) in your repository.
1. Press the `Edit this file` button (pencil icon).
1. Make changes to following settings:
    - `title`: The title of the site that shows up in the browser tab and on the homepage.
    - `description`: The description that shows up on the homepage and also the meta description for search engine optimization.
    - `baseurl`: *This needs to match the name of your repository for internal links to work.*
1. Save your changes by pressing the `Commit changes` button.

#### Test site settings

1. Go to the [_config.yml](_config.yml) file in your repository.
1. Press the `Edit this file` button (pencil icon).
1. Make changes to following settings:
    - `test-site`: The URL of the site you want to test.
    - `test-site-name`: The name of the site you want to appear in the header section.
    - `nav-offset`: The amount of offsite needed to cover the test site nav with the new nav.
    - `brand-color`: The primary brand color to match the new nav with the test site.
1. Save your changes by pressing the `Commit changes` button.

### Edit navigation content

1. Go to the [index.md](index.md) file in your repository.
1. Press the `Edit this file` button (pencil icon).
1. Change the nav titles and subnav titles and urls as needed.
    - Be sure to maintain the existing indents and spacing.
    - Use full URLs (starting with "https") and keep them in quotes.
1. Save your changes by pressing the `Commit changes` button.

## Team

This project was built by the Rapid Response Team at Bixal: [Philip Levy](https://github.com/pglevy), [Brianna Naolu](https://github.com/bnaolu), and [Kayla Chumley](https://github.com/kbchumley).

## Credit and license
This project was created using the [GitHub Pages gem for Jekyll](https://github.com/github/pages-gem) and a hosted version of the [U.S. Web Design System](https://github.com/uswds/uswds) on [CDNJS](https://cdnjs.com/).

This project is licensed under [The Unlicense](https://github.com/Bixal/uswds-template/blob/main/LICENSE), which allows everything and promises nothing. 🌊
