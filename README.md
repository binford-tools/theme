# Binford® Tools: Theme 

Provides common frontend customizations for [Binford® Tools][1].

## Intro

A custom [Magento 2 theme][2] that [inherits][3] from Magento’s Luma theme.

## How to install 

Add the [custom repository][4] to your [root package][5].  

```json
{
    "repositories":
    {
        "binford-tools.github.io": 
        {
            "type": "composer",
            "url":  "https://binford-tools.github.io/composer/"        
        }
    }
}
```

[Require the package][6] via Composer.

```sh
$ composer require binford-tools/theme ^1.0
```

[Update the project][7] via Magento’s CLI.

```sh 
$ magento setup:upgrade
```

## How to update

[Update the package][8] via Composer.

```sh
$ composer update binford-tools/theme
```

[Update the project][7] via Magento’s CLI.

```sh 
$ magento setup:upgrade
```

## We’re hiring!

We’re currently looking for passionate ~~masochists~~ **PHP & Magento developers** to join our e-commerce team **in Munich**. Sounds interesting? Just drop me a line via [j.scherbl@techdivision.com][9].

[1]: https://github.com/binford-tools
[2]: https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-overview.html
[3]: https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-inherit.html
[4]: https://github.com/binford-tools/composer
[5]: https://getcomposer.org/doc/04-schema.md#root-package 
[6]: https://getcomposer.org/doc/03-cli.md#require 
[7]: https://devdocs.magento.com/guides/v2.3/install-gde/install/cli/install-cli-subcommands-db-upgr.html
[8]: https://getcomposer.org/doc/03-cli.md#update-u
[9]: mailto:j.scherbl@techdivision.com
