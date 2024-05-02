The purpose of this repo is to get slim to be a standalone application that lives outside of
website. I wanted the app to be easily installable on any webserver. Then you would simply run the app from whatever sub directory you wanted within your website.

In this example, I have a skeleton Slim PHP app that is a vanilla install from [Odan's Slim Skeleton](https://github.com/odan/slim4-skeleton). It's a submodule installed into the `slimapp` directory. After you clone this, you should run `composer install` in order to install the packages for it.

The `docroot` directory is the folder of a simple Apache website. I would like my slimapp routes to all be accessible via the `/api/index.php` file.

In this basic example, navgating to `/api` should result in the default `Welcome!` message.
