# OpenBiz Drupal Distribution

## Tests

```
composer validate ./profiles/openbiz/composer.json --no-check-all --ansi
phpunit --configuration ./core --group openbiz
```