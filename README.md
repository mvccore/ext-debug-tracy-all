# MvcCore - Extension - Debug - Nette Tracy Adapter - All Panels

[![Latest Stable Version](https://img.shields.io/badge/Stable-v5.3.0-brightgreen.svg?style=plastic)](https://github.com/mvccore/ext-debug-tracy-all/releases)
[![License](https://img.shields.io/badge/License-BSD%203-brightgreen.svg?style=plastic)](https://mvccore.github.io/docs/mvccore/5.0.0/LICENSE.md)
![PHP Version](https://img.shields.io/badge/PHP->=5.4-brightgreen.svg?style=plastic)

MvcCore Debug Extension to replace internal MvcCore variables dumping with Nette Tracy library (`tracy/tracy`) with all implemented debug panels for MvcCore.

## Installation
```shell
composer require mvccore/ext-debug-tracy-all
```

## Example
Add this to `Bootstrap.php` or to very application beginning:
```php
\MvcCore\Application::GetInstance()->SetDebugClass('\\MvcCore\\Ext\\Debugs\\Tracy');
```

## Extensions
- `mvccore/ext-debug-tracy`
- `mvccore/ext-debug-tracy-auth`
- `mvccore/ext-debug-tracy-mvccore`
- `mvccore/ext-debug-tracy-routing`
- `mvccore/ext-debug-tracy-session`

Dependent packages:
- `mvccore/mvccore`
- `mvccore/ext-auth`
- `mvccore/ext-form`
- `tomflidr/tracy`
