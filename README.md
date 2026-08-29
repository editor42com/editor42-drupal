# Editor42 for Drupal

> **Looking for the Drupal module?** It is
> [drupal.org/project/editor42](https://www.drupal.org/project/editor42). This repository is not
> the module itself, but a dependency of it: the editor library the module loads.

The ready-to-use build of [Editor42](https://editor42.com), the free WYSIWYG HTML editor under the
MIT license, packaged as a Drupal library. It holds the same files as the Composer package
`editor42/editor42` and the npm package `editor42`, version for version.

You don't install it yourself. The Drupal module `drupal/editor42` requires it, so

    composer require drupal/editor42

also puts the editor into `web/libraries/editor42`, where the module loads it from.

Outside Drupal, use `editor42/editor42`.

## License

MIT, see `license.txt`. The third-party code bundled with the editor is listed in `notices.txt`.
