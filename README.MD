# Convert php-array to UUID string


## Installation
```
composer require xakepehok/array-to-uuid-helper
```

## Usage
```php
<?php
$data = [
    "hello" => "world",
    "nested" => [
        "value_1" => 1,
        "value_2" => 2,
    ],
];


// Print "13e6457d-e400-4ca3-86d0-c50624604a02"
echo \XAKEPEHOK\ArrayToUuidHelper\ArrayToUuidHelper::generate($fields);
```