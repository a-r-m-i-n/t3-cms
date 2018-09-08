# t3/cms

**Meta package for Composer/Packagist.**

Extended [typo3/minimal](https://packagist.org/packages/typo3/minimal) meta package, 
including [typo3_console](https://packagist.org/packages/helhum/typo3-console).


## Packages

The following packages are **required**:

- typo3/minimal
- typo3/cms-cli
- typo3/cms-fluid-styled-content
- typo3/cms-rte-ckeditor *(for 8.7 and higher)*
- typo3/cms-belog
- typo3/cms-beuser
- typo3/cms-info
- typo3/cms-info-pagetsconfig *(for 7.6 and 8.7 only)*
- typo3/cms-lowlevel
- typo3/cms-setup
- typo3/cms-tstemplate
- helhum/typo3-console


## Installation

Just add **t3/cms** as requirement to your composer.json. The following
versions are available:

- `^9.0` / `dev-master`
- `^8.7` / `8.0`
- `^7.6` / `7.0`

**Example:**
```
$ composer require t3/cms:"^8.7"  
```
