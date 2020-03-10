# Binford® Tools: Module 

A template for custom [Magento 2 modules][1].

## How to install 

Add the [custom repository][2] to your [root package][3].  

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

[Require the package][4] via Composer.

```sh
$ composer require binford-tools/module ^1.0
```

[Enable the module][5] via Magento’s CLI.

```sh 
$ magento module:enable Binford_Module
```

[Update the project][6] via Magento’s CLI.

```sh 
$ magento setup:upgrade
$ magento setup:di:compile
```

## How to update

[Update the package][7] via Composer.

```sh
$ composer update binford-tools/module
```

[Update the project][6] via Magento’s CLI.

```sh 
$ magento setup:upgrade
$ magento setup:di:compile
```

## How to test

The module includes [PHPStan][8] for static code analysis, and covers all relevant classes with [unit tests][9].

[Install dependencies][10] via Composer.

```sh
$ composer install
```
[Run the tests][11] via Composer.

```sh
$ composer test
```

## We’re hiring!

We’re currently looking for passionate ~~masochists~~ **PHP & Magento developers** to join our e-commerce team **in Munich**. Sounds interesting? Just drop me a line via [j.scherbl@techdivision.com][12].

 [1]: https://devdocs.magento.com/guides/v2.3/architecture/archi_perspectives/components/modules/mod_intro.html
 [2]: https://github.com/binford-tools/composer
 [3]: https://getcomposer.org/doc/04-schema.md#root-package
 [4]: https://getcomposer.org/doc/03-cli.md#require
 [5]: https://devdocs.magento.com/guides/v2.3/install-gde/install/cli/install-cli-subcommands-enable.html#instgde-cli-subcommands-enable-disable 
 [6]: https://devdocs.magento.com/guides/v2.3/install-gde/install/cli/install-cli-subcommands-db-upgr.html
 [7]: https://getcomposer.org/doc/03-cli.md#update-u
 [8]: https://github.com/phpstan/phpstan
 [9]: https://phpunit.de
[10]: https://getcomposer.org/doc/03-cli.md#install-i
[11]: https://getcomposer.org/doc/articles/scripts.md#writing-custom-commands
[12]: mailto:j.scherbl@techdivision.com
