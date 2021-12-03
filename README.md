# October CMS Logout Plugin

Manage backend users session.

## Features

* Manage backend user idleness time
* Sign out backend user after specified time
* Expire session on browser close
* Force single browser session

## Why is this a paid plugin?

Something that is free has little or no perceived value. Users do not commit to free products and only use them until something else looks nice and is free comes along. When I invest my time in the development of a new plugin I commit to supporting and maintaining it. I ask my customers to do the same. I do not make money from this plugin by advertisements, upgrades or additional services like hosting or setup.

Did you know that 30% of your purchase or donation goes to help fund the October Project?

My plugins take many hours to develop (40-120+) and even more hours to document and maintain. My paid plugins have to pay for both this time, and the time I am spending on free plugins and less successful paid plugins. This means that it will take even a successful plugin years to become profitable. Please consider buying an extended license if you want me to continue to maintain these plugins for the very small fee I ask in return or hire me for adding functionality that you feel is missing but valuable.

## Like this plugin?

If you like this plugin, give this plugin a Like or Make donation with [PayPal](https://www.paypal.me/mplodowski).

## My other plugins

Please check my other [plugins](https://octobercms.com/author/Renatio).

## Support

Please use [GitHub Issues Page](https://github.com/mplodowski/logout-plugin-public/issues) to report any issues with plugin.

> Reviews should not be used for getting support, if you need support please use the Plugin support link.

Icon made by [Darius Dan](https://www.flaticon.com/authors/darius-dan) from [www.flaticon.com](https://www.flaticon.com/).

# Documentation

## Installation

There are couple ways to install this plugin.

1. Use `php artisan plugin:install Renatio.Logout` command.
2. Use `composer require renatio/logout-plugin` in project root. When you use this option you must
   run `php artisan october:migrate` after installation.

## Settings

After installation plugin will register backend **User Session** settings position under **Team** tab.

### Session lifetime in minutes

There you can specify session lifetime in minutes. Default is 120 minutes.

### Expire session on browser close

Immediately expire session when the browser closes.

### Force single session

When enabled, backend users cannot sign in to multiple devices at the same time.
