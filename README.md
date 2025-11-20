# Tanmatsu "Ballz demo" project

This minimal demo shows how to build an app for Tanmatsu using the [PAX graphics](https://github.com/robotman2412/pax-graphics/tree/release/1.1.1/docs) library.

It is based in the [Template app](https://github.com/Nicolai-Electronics/tanmatsu-template)

This is supposed to run in RGB888 (24 bit per pixel) mode, but this needs some extra step in the build process, because we are using a couple of patched libraries to make that work:

After running "make prepare", you also need to run "make prepare_rgb888"

## License

The contents of this repository may be considered in the public domain or [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0) licensed at your disposal.

