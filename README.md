Yii 2 Basic Project Template
============================

Yii 2 Basic Project Template is a skeleton [Yii 2](http://www.yiiframework.com/)
application best for rapidly creating small projects.

The template contains the basic features including user login/logout and a contact
page. It includes all commonly used configurations that would allow you to focus
on adding new features to your application.

DIRECTORY STRUCTURE
-------------------

      assets/             contains assets definition
      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      helpers/            contains helper functions
      mail/               contains view files for e-mails
      models/             contains model classes
      runtime/            contains files generated during runtime
      tests/              contains various tests for the basic application
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      web/                contains the entry script and Web resources

REQUIREMENTS
------------

The minimum requirement by this project template that your Web server supports PHP 5.4.0.

INSTALLATION
------------

If you do not have [Composer](http://getcomposer.org/), you may install it by following the instructions
at [getcomposer.org](http://getcomposer.org/doc/00-intro.md#installation-nix).

You can then install this project template using the following command:

```bash
$ php composer.phar global require "fxp/composer-asset-plugin:~1.1.1"
$ git clone git@github.com:StrongSquirrel/yii2-dotenv-app.git project_name
$ cd project_name
$ php composer.phar install
```

CONFIGURATION
-------------

Set up env variables in .env file:

```bash
$ cd project_name
$ cp .env.example .env
```

```
DB_DSN=mysql:host=localhost;dbname=yii2basic
DB_USERNAME=root
DB_PASSWORD=
YII_DEBUG=true
YII_ENV=prod
COOKIE_VALIDATION_KEY=
```
