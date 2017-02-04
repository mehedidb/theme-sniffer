# NS Theme Check

Theme Check plugin using sniffs. `WordPress-Theme` standard is used from [WPTRT/WordPress-Coding-Standards](https://github.com/WPTRT/WordPress-Coding-Standards).

## Installing

### Option 1: Easy

* Download [zip file](https://github.com/ernilambar/ns-theme-check/releases/download/0.1.2/ns-theme-check.0.1.2.zip). [Note: Please use this distribution plugin zip. Github provided zip will not work.]
* Install this as you normally install a WordPress plugin
* Activate plugin

### Option 2: Nerdy

* Clone this repo under `wp-content/plugins/`
* Run `composer install`
* Activate plugin

## Using

* Go to `Appearance` -> `NS Theme Check`
* Select theme from the dropdown
* Click `GO`

## Options

* `Hide Warning` - Enable this to hide warnings.
* `Raw Output` - Enable this to display sniff report in plaintext format. Suitable to copy/paste report to trac ticket.