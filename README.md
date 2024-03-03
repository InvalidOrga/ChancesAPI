# ChancesAPI in PHP

## Installing
```shell
$ composer require austriannoah/chancesapi
```

# Usage
```php
    Chances::chance("fifty-fifty", function () {
        // use this for success
    }, function () {
        // use this for failure
});
```
