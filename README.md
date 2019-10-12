# WARNING: This repository is no longer maintained :warning:

> This repository will not be updated. The repository will be kept available in read-only mode.

### ProcessWire 

# Language Translator List


Extends Language Translator Modul.  
Changes view and adds support for other template engines like twig and smarty.  
If you don't use another template engine, you can use this module equally.

Designed for use with ProcessWire 3.x
[http://processwire.com](http://processwire.com)

## Installation

1. Clone the module and place `LanguageTranslatorList` in your site/modules/ directory. 

```
git clone https://github.com/justonestep/processwire-languagetranslatorlist.git your/path/site/modules/LanguageTranslatorList
```

2. Login to ProcessWire admin and click Modules. 
3. Click "Check for new modules".
4. Click "install" next to the new `LanguageTranslatorList ` module. 
  
## Usage

**admin/setup/languages**

In ProcessWire admin go to _admin/setup/languages_.  
Choose a language and click on the button _Translate File_.  
Now you see a dropdown list of all files you don't have translated for the choosen language yet.  

**Notice**: If you use another template engine, you'll get your `.twig`, `.tpl` or `.html` files listed there as well!

Choose a file, click _Translate File_ and translate all phrases you want to.

Below that list is a language switcher, where you can easily switch your language.

![Setup Languages](https://github.com/justonestep/processwire-languagetranslatorlist/blob/master/screens/languages.png)

**admin/setup/language-translator**

In ProcessWire admin go to _admin/setup/language-translator_.  
On the top is a language switcher as well.  
All translated files for the choosen language are listed.  
You can edit the belonging phrases by clicking on the file.  
Furthermore you can add another file to translate by clicking the _Translate another File_ Button.

![Setup Language-Translator](https://github.com/justonestep/processwire-languagetranslatorlist/blob/master/screens/language-translator.png)

## Enable Language Translators for Editors

This module provides a permission called **lang-edit** (you see this permission listed here: ``Admin > Access > Permissions``).

If a specific role should be able to use the Language Translator just go to ``Admin > Access > Roles``, edit the specific role and check **lang-edit**.

The modules will display **only the site translation files**, the core files will be hidden.
