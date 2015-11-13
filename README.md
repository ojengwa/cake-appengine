# CakePHP Application Skeleton

[![Build Status](https://api.travis-ci.org/cakephp/app.png)](https://travis-ci.org/cakephp/app)
[![License](https://poser.pugx.org/cakephp/app/license.svg)](https://packagist.org/packages/cakephp/app)

A skeleton for creating Google App Engine applications with [CakePHP](http://cakephp.org) 3.x.

The framework source code can be found here: [cakephp/cakephp](https://github.com/cakephp/cakephp).

## Installation

1. Download [Composer](http://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Run `php composer.phar create-project --prefer-dist inits/cake-appengine [app_name]`.

If Composer is installed globally, run
```bash
composer create-project --prefer-dist inits/cake-appengine [app_name]
```

You should now be able to visit the path to where you installed the app and see
the setup traffic lights.

## Configuration
1. Edit `app.yaml` and replace PROJECT_ID and PROJECT_VERSION with the correct values.

2. Read and edit `config/app.php` and setup the 'Datasources' and any other configuration relevant for your application.
