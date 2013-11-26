HdPackagist
===========

Wrapper Module for https://github.com/KnpLabs/packagist-api for ZF2

## Installation

The recommended way to install HdPackagist is through composer:

```json
{
    "require": {
        "hounddog/hd-packagist": "dev-master"
    }
}
```


## Usage

```php
$client = $serviceManager->get('Packagist\Api\Client');
```

Please refer to the documentation on https://github.com/KnpLabs/packagist-api