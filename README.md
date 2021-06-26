# Laravel Persian Slugify

generate slugs for persian strings, just with 1 helper!

---

## Installation
Install via composer:

```composer require amirvahedix\laravel-persian-slugify```

## Usage
just use ```slugify()``` helper anywhere you want in your project:

```php
slugify('اسلاگ فارسی در لاراول!');
// اسلاگ-فارسی-در-لاراول

slugify('Laravel Persian Slug!');
// laravel-persian-slug
```

## Options
```slugify()``` helper has 4 arguments:

- ```str``` => the string you want convert to slug

- ```delimiter``` => delimiter between words (default: ```-```) 

- ```lowercase``` => converts all characters to lowercase if it is ``true`` (default: ``true``) 

- ```limit``` => limit characters to make slug (default: ``null`` *no limit*)
