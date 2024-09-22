# CRM-2
Spec for modpack loading

## File structure
Modpack zip files should follow the following structure:

```
my_modpack.zip/
    pack.json
    overrides/
        config/
            mymod.cfg
        options.txt
        mods/
            mymod.jar
```

The overrides folder is optional and allows including files in the zip.

## pack.json Structure
See the lastest revison in [spec/](https://github.com/CRModders/CRM-2/tree/main/spec)

## Example
A modpack using all of CRM-2 is here: https://www.crmm.tech/modpack/cosmic-fixes/version/LCY8rNJkP-3BYZVZ3Q
