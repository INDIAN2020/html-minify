# HTML Minify

This class does not require a CMS like WordPress, but there is a [WordPress version](http://wordpress.org/extend/plugins/wp-html-compression/) available.

## FAQ & Changelog

To minimize maintenance, check out the info at the WordPress plugin page: [http://wordpress.org/extend/plugins/wp-html-compression/](http://wordpress.org/extend/plugins/wp-html-compression/)

## Example Usage

### Inline HTML

```php
<?php require_once 'html-minify.php'; ?>
<html>
…
</html>
```

### External HTML

```php
<?php

require_once 'html-minify.php';

echo file_get_contents('markup.html');

?>
```

## License

This plugin is dual licensed under the MIT and GPL licenses.