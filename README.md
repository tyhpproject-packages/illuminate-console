<!-- tyhp-readme:start -->
# tyhpdef/illuminate-console

Tyhp type definitions for `illuminate/console` `13.32.0`.

```bash
composer require --dev tyhpdef/illuminate-console:13.32.0
```

This is a metapackage. Composer also installs `tyhpdef/illuminate-console-impl` (type files).
Require **this** name, not `tyhpdef/illuminate-console-impl`.

See https://tyhplang.com.

## Maintain `illuminate/console`? Ship the types yourself

If you are a Packagist maintainer of `illuminate/console`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/illuminate-console-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `illuminate/console` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/illuminate-console": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `illuminate/console` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `illuminate/console` with a real constraint,
   `"replace": { "tyhpdef/illuminate-console": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `illuminate/console` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/illuminate-console` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
