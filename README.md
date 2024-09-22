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
