```
modpack.zip/
    pack.json
    overrides/
        options.txt
        config/
            mymod.config
        mods/
            embedded-mod.jar

    server-overrides/
        server-options.txt
        config/
            world-gen.config
        mods/
            embedded-mod.jar
```
You define your modpack metadata in the `pack.json`. Optionally, you can override some config and stuff using the `overrides` and `server-overrides` folders.
If there is no `server-overrides` folder, the `overrides` folder will be used for both the client and the server.