# Mímir

A WordPress skeleton installation template with WP CLI integration for modern Wordpress development

## Installation

Initial scripts only required for initial project creation:

```bash
composer create-project eleven-miles/mimir my-project
cd my-project
```

The project creation script will ask you a series of questions around how you want to configure your WordPress project, including database credentials, site URL, and more which will be automatically added to a `.env` file for you.

If using the default theme `eleven-miles/erebus`, this script will also handle the initial namespacing replacements for you based on the files outlined in the `theme.config.json` file.

You can then add plugins to your project as needed (ACF PRO currently needs to be installed manually), and then proceed to switch to the theme directory in order to install and run the front-end build process.
