# About [Badge Factor](www.badgefactor.com)
Badge Factor is a "glue" plugin which brings together functionalities of BadgeOS, Gravity Forms and Advanced Custom Fields in a coherent, autonomous open badge issuing and backpacking solution.

## Features

* Improved WordPress structure based on [Bedrock](https://roots.io/bedrock/)
* Basic theme based on [Sage](https://roots.io/sage/)
* Easy installation through [Composer](https://getcomposer.org/)
* Helps create and manage Badges, Badge Pages & Assessment Forms
* Generates customizable Evidence in PDF format

## Requirements

* PHP >= 7.0
* Composer - [Install](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx)
* Gravity Forms - [Purchase](http://www.gravityforms.com/purchase-gravity-forms/)
* Gravity Forms User Registration - [Purchase](http://www.gravityforms.com/add-ons/quiz/)

## License Information

Digital Pygmalion licenses Badge Factor to you under the terms of the [X11 License](https://fr.wikipedia.org/wiki/Licence_MIT#Mod.C3.A8le_de_la_licence_X11).

## Installation

1. Install [WP-CLI](http://wp-cli.org/)
2. Clone the present repository.
3. Copy the file .env.example to .env, and edit its content to configure the database and WordPress.
4. Install [Gravity Forms](http://www.gravityforms.com/) (>= v1.9)
5. At the root of the project, do 
```bash
$ composer install
$ wp db create
$ wp core install [necessary parameters]
$ wp plugin activate --all
$ wp theme activate badge-factor-theme
```
6. Setup the required information in the Settings > Badge Factor menu.
7. Visit the Badge Factor menu to add Badges.


## Bugs & Feature Requests

Please open an [Issue](https://github.com/DigitalPygmalion/badge-factor/issues) to report any bugs or feature requests concerning Badge Factor. Bugs or feature requests concerning other dependency plugins must be submitted to their respective communities.

## Contributing

The Badge Factor team is always looking for contributors!
