`wp server`
===========

This is a package that implements the `wp server` command.

It uses the [PHP built-in server](http://php.net/manual/en/features.commandline.webserver.php) to start a development server.

The main advantage is that you don't have to install and configure Nginx or Apache, which can be overkill if you just want to work on a theme or a plugin.

### Requirements

* PHP 5.4 or newer
* WordPress 3.5 or newer

### Installation

First, make sure you have the [package index](http://wp-cli.org/package-index/) configured:

```
cd ~/.wp-cli/
php composer.phar config repositories.wp-cli composer http://wp-cli.org/package-index/
```

Then, just install the package:

```
php composer.phar require wp-cli/server-command=dev-master
```
