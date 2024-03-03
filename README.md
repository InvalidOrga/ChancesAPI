# ChancesAPI in PHP

## Installing
```shell
$ composer require austriannoah/chancesapi
```

or just adding this to your ``composer.json``

```json
{
    "require": {
        "austriannoah/chancesapi": "dev-main"
    }
}
```

# Usage
```php
    Chances::chance("fifty-fifty", function () {
        // use this for success
    }, function () {
        // use this for failure
});
```

# Support
- [ ] Discord
- [ ] Forum
