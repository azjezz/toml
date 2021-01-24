# TOML

![Unit tests status](https://github.com/azjezz/toml/workflows/unit%20tests/badge.svg?branch=develop)
![Static analysis status](https://github.com/azjezz/toml/workflows/static%20analysis/badge.svg?branch=develop)
![Security analysis status](https://github.com/azjezz/toml/workflows/security%20analysis/badge.svg?branch=develop)
![Coding standards status](https://github.com/azjezz/toml/workflows/coding%20standards/badge.svg?branch=develop)
[![Coverage Status](https://coveralls.io/repos/github/azjezz/toml/badge.svg?branch=develop)](https://coveralls.io/github/azjezz/toml?branch=develop)
[![Type Coverage](https://shepherd.dev/github/azjezz/toml/coverage.svg)](https://shepherd.dev/github/azjezz/toml)
[![Total Downloads](https://poser.pugx.org/azjezz/toml/d/total.svg)](https://packagist.org/packages/azjezz/toml)
[![Latest Stable Version](https://poser.pugx.org/azjezz/toml/v/stable.svg)](https://packagist.org/packages/azjezz/toml)
[![License](https://poser.pugx.org/azjezz/toml/license.svg)](https://packagist.org/packages/azjezz/toml)

A TOML ( Tom's Obvious, Minimal Language ) parser implementation for data serialization and deserialization in PHP.

## Example

```php
<?php

declare(strict_types=1);

$file = 'path/to/config.toml';
$configuration = ...
```

## Installation

Supported installation method is via [composer](https://getcomposer.org):

```console
$ composer require azjezz/toml
```

## License

The MIT License (MIT). Please see [`LICENSE`](./LICENSE) for more information.
