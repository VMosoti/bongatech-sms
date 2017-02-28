# BongaTech SMS

[![Latest Stable Version](https://poser.pugx.org/vmosoti/bongatech-sms/v/stable)](https://packagist.org/packages/vmosoti/bongatech-sms)
[![Latest Unstable Version](https://poser.pugx.org/vmosoti/bongatech-sms/v/unstable)](https://packagist.org/packages/vmosoti/bongatech-sms)
[![Build Status](https://travis-ci.org/VMosoti/bongatech-sms.svg?branch=master)](https://travis-ci.org/VMosoti/bongatech-sms)
[![StyleCI](https://styleci.io/repos/83431204/shield?branch=master)](https://styleci.io/repos/83431204)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/598f97e6-bb46-4883-ae19-29820926b081/mini.png)](https://insight.sensiolabs.com/projects/598f97e6-bb46-4883-ae19-29820926b081)
[![Total Downloads](https://poser.pugx.org/vmosoti/bongatech-sms/downloads)](https://packagist.org/packages/vmosoti/bongatech-sms)
[![License](https://poser.pugx.org/vmosoti/bongatech-sms/license)](https://packagist.org/packages/vmosoti/bongatech-sms)


This is a PHP client library to be used with BongaTech's SMS API [See Bonga Tech's Website for more](http://bongatech.co.ke)

## Installation

You can install the package via composer:

``` bash
composer require vmosoti/bongatech-sms
```

## Usage

``` php
$sms = new VMosoti\BongaTech\SMS();
echo $sms->send('+254722123456', 'This is a Message');
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email vincent@vmosoti.com instead of using the issue tracker.

## Credits

- [Vincent Mosoti](https://github.com/vmosoti)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.