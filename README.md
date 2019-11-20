<p align="center"><img src="https://avatars3.githubusercontent.com/u/45311177?s=200&v=4"></p>

<p align="center">
<a href="https://travis-ci.org/nuxed/inflector"><img src="https://travis-ci.org/nuxed/inflector.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/nuxed/inflector"><img src="https://poser.pugx.org/nuxed/inflector/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/nuxed/inflector"><img src="https://poser.pugx.org/nuxed/inflector/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/nuxed/inflector"><img src="https://poser.pugx.org/nuxed/inflector/license.svg" alt="License"></a>
</p>

# Nuxed Inflector

The Nuxed Inflector component converts words between their singular and plural forms (English only)

### Installation

This package can be installed with [Composer](https://getcomposer.org).

```console
$ composer require nuxed/inflector
```

### Example

```hack
use namespace Nuxed\Inflector;

<<__EntryPoint>>
async function main(): Awaitable<void> {
  $singular = Inflector\Inflector::singularize('children');
  // > vec['child']

  $plural = Inflector\Inflector::pluralize('bacterium');
  // > vec['bacteria']
}
```

---

### Security

For information on reporting security vulnerabilities in Nuxed, see [SECURITY.md](SECURITY.md).

---

### License

Nuxed is open-sourced software licensed under the MIT-licensed.
