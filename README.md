# GsTYPO3 Base Composer Metapackage

GsTYPO3 Base Composer Metapackage requires some important and useful packages
to setup a secure and standardized TYPO3 CMS instance.

## Requires

The following packages are required by this metapackage:

* [helhum/typo3-secure-web](https://packagist.org/packages/helhum/typo3-secure-web): ^0.2.9
* [roave/security-advisories](https://packagist.org/packages/roave/security-advisories): dev-master
* [typo3-console/composer-auto-commands](https://packagist.org/packages/typo3-console/composer-auto-commands): ^0.3.0
* [typo3/minimal](https://packagist.org/packages/typo3/minimal): ^8.7

## Extras

This package needs some extras in the root composer.json:

```json
    "extra": {
        "typo3/cms": {
            "root-dir": "private",
            "web-dir": "public"
        }
    }
```

For more information see [Configuration](https://packagist.org/packages/helhum/typo3-secure-web#user-content-configuration).

## License

GPL-3.0 or later
