# Svelte

a [Slim Framework](http://www.slimframework.com/) boilerplate.

## Installation

First, Install [Composer](https://getcomposer.org):

```bash
$ curl -sS https://getcomposer.org/installer | php
```
Next, clone the repo:

```bash
$ git clone https://github.com/stursby/svelte.git && cd svelte
```
Install packages via Composer:

```bash
$ php composer.phar install
```

## Adding packages

You can find packages on [packagist.org](https://packagist.org/).
To add packages, edit the `composer.json` file and run the following:

```bash
$ php composer.phar update
```

## Run a server

To see Svelte in action, you can boot up a local server using the following:

```bash
$ php -S localhost:8000
```

Now, visit `http://localhost:8000/` in your browser.

## Database

Svelte uses [Idiorm](http://j4mie.github.io/idiormandparis/) ORM to setup and query a Database. You can read more about Idiorm [here](http://idiorm.readthedocs.org/en/latest/index.html).

## License

Svelte is licensed [MIT](http://opensource.org/licenses/MIT)

* * *

Copyright (c) 2014 Charlie Hield
