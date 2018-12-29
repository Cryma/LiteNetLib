# LiteNetLib 

Unity Package Manager compatible version of [RevenantX/LiteNetLib](https://github.com/RevenantX/LiteNetLib).

# Usage

As git packages are not yet supported in the Package Manager GUI you'll have to reference it yourself via `manifest.json`, located under `<project path>/Packages/manifest.json`.

Simply add this package as a new dependency using the syntax shown below.
```js
"de.cryma.litenetlib": "https://github.com/Cryma/LiteNetLib.git"
```

After restarting Unity the package can be used.

**Important:** If you use Assembly Definitions, don't forget to add `de.cryma.litenetlib.Runtime` as a reference.
