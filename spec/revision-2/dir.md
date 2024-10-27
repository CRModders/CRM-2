```
modpack.zip/
    pack.json

    overrides/
        options.txt
        config/
            mymod.config
        mods/
            embedded-mod.jar

    client-overrides/
        client-options.txt
        config/
            mod.config
        mods/
            embedded-client-mod.jar
    server-overrides/
        server-options.txt
        config/
            world-gen.config
        mods/
            embedded-server-mod.jar
```

You define your modpack metadata in the `pack.json`. \
Optionally you can override config and stuff too. For that you can include either:
- an `overrides` folder inside the zip. The contents of the overrides folder will be copied to the respective in game folders. \
    NOTE: This applies to both the client and the server.

- a `client-overrides` AND/OR a `server-overrides` folder \
    As the name suggests, `client-overrides` folder is used for client side overrides and `server-overrides` is used for server side.