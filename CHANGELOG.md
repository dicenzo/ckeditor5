Changelog
=========

## [11.0.1](https://github.com/ckeditor/ckeditor5/compare/v11.0.0...v11.0.1) (2018-07-18)

Internal changes only (updated dependencies, documentation, etc.).


## [11.0.0](https://github.com/ckeditor/ckeditor5/compare/v10.1.0...v11.0.0) (2018-07-18)

### Release notes

This is a major releases that introduces two new plugins ([autosave](https://docs.ckeditor.com/ckeditor5/latest/builds/guides/integration/saving-data.html) and [block toolbar](https://docs.ckeditor.com/ckeditor5/latest/features/blocktoolbar.html)), many smaller features, dozens of bug fixes and a couple of infrastructure changes (an upgrade to `webpack@4` and simplified structure of build repositories). Additionally, the `Editor#element` property was renamed to `Editor#sourceElement` and the `Editor#updateElement()` method was renamed to `Editor#updateSourceElement()`.

If you maintain a [custom build of CKEditor 5](https://docs.ckeditor.com/ckeditor5/latest/builds/guides/development/custom-builds.html) or [integrate CKEditor 5 from source](https://docs.ckeditor.com/ckeditor5/latest/builds/guides/integration/advanced-setup.html#scenario-2-building-from-source), we recommend reading the [migration guide](https://github.com/ckeditor/ckeditor5/issues/1136).

Blog post is coming soon...

### Dependencies

New packages:

* [@ckeditor/ckeditor5-autosave](https://www.npmjs.com/package/@ckeditor/ckeditor5-autosave): [v10.0.0](https://github.com/ckeditor/ckeditor5-autosave/releases/tag/v10.0.0)

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-build-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-balloon): v10.1.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-build-balloon/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v10.1.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-build-decoupled-document](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-decoupled-document): v10.1.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-build-decoupled-document/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-build-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-inline): v10.1.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-build-inline/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v10.1.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-core/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-editor-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-balloon): v10.0.1 => [v11.0.0](https://github.com/ckeditor/ckeditor5-editor-balloon/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v10.0.1 => [v11.0.0](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v10.0.2 => [v11.0.0](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): v10.0.1 => [v11.0.0](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v10.1.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v10.0.1 => [v11.0.0](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v11.0.0)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v10.1.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v11.0.0)

Minor releases:

* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v10.1.0 => [v10.2.0](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v10.2.0)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v10.1.0 => [v10.2.0](https://github.com/ckeditor/ckeditor5-image/releases/tag/v10.2.0)
* [@ckeditor/ckeditor5-table](https://www.npmjs.com/package/@ckeditor/ckeditor5-table): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-table/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v10.1.0 => [v10.2.0](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v10.2.0)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v10.1.0 => [v10.2.0](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v10.2.0)

Patch releases (bug fixes, internal changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-cloud-services](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloud-services): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-cloud-services/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v10.1.0 => [v10.1.1](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v10.1.1)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v10.1.0 => [v10.1.1](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v10.1.1)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-font/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v10.0.2 => [v10.0.3](https://github.com/ckeditor/ckeditor5-link/releases/tag/v10.0.3)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v11.0.0 => [v11.0.1](https://github.com/ckeditor/ckeditor5-list/releases/tag/v11.0.1)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v10.0.2)

### Features

Besides new features introduced by the dependencies, this version also introduces the following features:

* Introduced the [`@ckeditor/ckeditor5-autosave`](https://www.npmjs.com/package/@ckeditor/ckeditor5-autosave) package. ([bac9671](https://github.com/ckeditor/ckeditor5/commit/bac9671))

### Other changes

* Updated `webpack` to version 4. ([7390460](https://github.com/ckeditor/ckeditor5/commit/7390460))

### BREAKING CHANGES

If you maintain a custom build or integrate CKEditor 5 from source, we recommend reading the [migration guide](https://github.com/ckeditor/ckeditor5/issues/1136). Closes [ckeditor/ckeditor5#1038](https://github.com/ckeditor/ckeditor5/issues/1038).

* CKEditor 5 environment was updated to use `webpack@4`. `webpack@4` introduced major changes in its configuration and plugin system. CKEditor 5 tools and build configuration were updated to work with `webpack@4` and will not work with `webpack@3`.
* The structure of build repositories was changed. The `build-config.js` files were removed and the build configuration is now kept only in the `src/ckeditor.js` files.


## [10.1.0](https://github.com/ckeditor/ckeditor5/compare/v10.0.1...v10.1.0) (2018-06-21)

This is a minor release that introduces many bug fixes and new features. Most notable ones are the table plugin and support for inserting soft breaks with <kbd>Shift</kbd>+<kbd>Enter</kbd>.

You can read more in the [blog post](https://ckeditor.com/blog/CKEditor-5-v10.1.0-released/).

### Dependencies

New packages:

* [@ckeditor/ckeditor5-table](https://www.npmjs.com/package/@ckeditor/ckeditor5-table): [v10.0.0](https://github.com/ckeditor/ckeditor5-table/releases/tag/v10.0.0)

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v10.0.0 => [v11.0.0](https://github.com/ckeditor/ckeditor5-list/releases/tag/v11.0.0)

Minor releases:

* [@ckeditor/ckeditor5-build-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-balloon): v10.0.1 => [v10.1.0](https://github.com/ckeditor/ckeditor5-build-balloon/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v10.0.1 => [v10.1.0](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-build-decoupled-document](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-decoupled-document): v10.0.1 => [v10.1.0](https://github.com/ckeditor/ckeditor5-build-decoupled-document/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-build-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-inline): v10.0.1 => [v10.1.0](https://github.com/ckeditor/ckeditor5-build-inline/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-core/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-image/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v10.1.0)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v10.0.0 => [v10.1.0](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v10.1.0)

Patch releases (bug fixes, internal changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-cloud-services](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloud-services): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-cloud-services/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-editor-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-balloon): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-editor-balloon/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-font/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v10.0.1 => [v10.0.2](https://github.com/ckeditor/ckeditor5-link/releases/tag/v10.0.2)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v10.0.1)

### Features

Besides new features introduced by the dependencies, this version also introduces the following features:

* Introduced the `@ckeditor/ckeditor5-table` package. ([e4b9a72](https://github.com/ckeditor/ckeditor5/commit/e4b9a72))

### Bug fixes

Besides changes in the dependencies, this version also contains the following bug fixes:

* The editor buttons in the document editor guide should not wrap to the next line. Closes [#1077](https://github.com/ckeditor/ckeditor5/issues/1077). ([61c6ad6](https://github.com/ckeditor/ckeditor5/commit/61c6ad6))
* The table dropdown in the document editor snippet should not be cut off. Closes [#1069](https://github.com/ckeditor/ckeditor5/issues/1069). ([bed8e70](https://github.com/ckeditor/ckeditor5/commit/bed8e70))


## [10.0.1](https://github.com/ckeditor/ckeditor5/compare/v10.0.0...v10.0.1) (2018-05-22)

## Release notes

We would like to announce the release of CKEditor 5 v10.0.1 that contains a security fix for the [Link package](http://npmjs.com/package/@ckeditor/ckeditor5-link), so an upgrade is highly recommended for all CKEditor 5 installations that include it. Additionally, this release fixes an issue with the decoupled editor that blocked enabling real-time collaboration in this editor.

You can read more in the [blog post](https://ckeditor.com/blog/CKEditor-5-v10.0.1-released/).

### Dependencies

Patch releases (bug fixes, internal changes):

* [@ckeditor/ckeditor5-build-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-balloon): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-build-balloon/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-build-decoupled-document](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-decoupled-document): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-build-decoupled-document/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-build-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-inline): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-build-inline/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v10.0.1)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v10.0.0 => [v10.0.1](https://github.com/ckeditor/ckeditor5-link/releases/tag/v10.0.1)


## [10.0.0](https://github.com/ckeditor/ckeditor5/compare/v1.0.0-beta.4...v10.0.0) (2018-04-25)

### Release notes

The first stable release of CKEditor 5 🎉🎉🎉

You can read a summary blog post here: https://ckeditor.com/blog/CKEditor-5-v10.0.0-the-future-of-rich-text-editing-looks-stable/.

PS. We decided to skip version numbers lower than v5.0.0 to avoid collisions with [CKEditor 3-4](http://github.com/ckeditor/ckeditor-dev).

### BREAKING CHANGES

* The license under which CKEditor 5 is released has been changed from a triple GPL, LGPL and MPL license to a GPL2+ only. See [ckeditor/ckeditor5#991](https://github.com/ckeditor/ckeditor5/issues/991) for more information.

### Dependencies

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-build-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-balloon): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-build-balloon/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-build-decoupled-document](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-decoupled-document): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-build-decoupled-document/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-build-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-inline): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-build-inline/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-cloud-services](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloud-services): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-cloud-services/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-core/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-editor-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-balloon): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-editor-balloon/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-font/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-image/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-link/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-list/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v10.0.0)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v1.0.0-beta.4 => [v10.0.0](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v10.0.0)


## [1.0.0-beta.4](https://github.com/ckeditor/ckeditor5/compare/v1.0.0-beta.2...v1.0.0-beta.4) (2018-04-19)

### Release notes

This is a minor release that mainly focuses on stabilizing the [two-step caret movement around links](https://docs.ckeditor.com/ckeditor5/latest/builds/guides/whats-new.html#caret-movement-around-links).

A breaking change was introduced in the [document editor build](https://docs.ckeditor.com/ckeditor5/latest/builds/guides/overview.html#document-editor) – refer to its [changelog](https://github.com/ckeditor/ckeditor5-build-decoupled-document/releases/tag/v1.0.0-beta.4) for more information.

Finally, two new plugins were introduced – [`ParagraphButtonUI`](https://docs.ckeditor.com/ckeditor5/latest/api/module_paragraph_paragraphbuttonui-ParagraphButtonUI.html) and [`HeadingButtonsUI`](https://docs.ckeditor.com/ckeditor5/latest/api/module_heading_headingbuttonsui-HeadingButtonsUI.html) which make it possible to replace the `headings` dropdown with separate buttons for each heading level.

PS. The `1.0.0-beta.3` version number was skipped in order to align the project version number which diverged from builds version numbers

### Dependencies

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-build-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-balloon): v1.0.0-beta.3 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-build-balloon/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v1.0.0-beta.3 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-build-decoupled-document](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-decoupled-document): v1.0.0-beta.3 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-build-decoupled-document/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-build-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-inline): v1.0.0-beta.3 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-build-inline/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-cloud-services](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloud-services): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-cloud-services/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-core/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-editor-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-balloon): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-editor-balloon/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-font/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-image/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-link/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-list/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v1.0.0-beta.4)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v1.0.0-beta.2 => [v1.0.0-beta.4](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v1.0.0-beta.4)


## [1.0.0-beta.2](https://github.com/ckeditor/ckeditor5/compare/v1.0.0-beta.1...v1.0.0-beta.2) (2018-04-10)

### Dependencies

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-build-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-balloon): v1.0.0-beta.1 => [v1.0.0-beta.3](https://github.com/ckeditor/ckeditor5-build-balloon/releases/tag/v1.0.0-beta.3)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v1.0.0-beta.1 => [v1.0.0-beta.3](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v1.0.0-beta.3)
* [@ckeditor/ckeditor5-build-decoupled-document](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-decoupled-document): v1.0.0-beta.1 => [v1.0.0-beta.3](https://github.com/ckeditor/ckeditor5-build-decoupled-document/releases/tag/v1.0.0-beta.3)
* [@ckeditor/ckeditor5-build-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-inline): v1.0.0-beta.1 => [v1.0.0-beta.3](https://github.com/ckeditor/ckeditor5-build-inline/releases/tag/v1.0.0-beta.3)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-cloud-services](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloud-services): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-cloud-services/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-core/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-editor-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-balloon): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-editor-balloon/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-font/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-image/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-link/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-list/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v1.0.0-beta.2)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v1.0.0-beta.1 => [v1.0.0-beta.2](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v1.0.0-beta.2)

### Other changes

* `@ckeditor/ckeditor5-cloudservices` was renamed to `@ckeditor/ckeditor5-cloud-services` and `@ckeditor/ckeditor-cloudservices-core` to `@ckeditor/ckeditor-cloud-services-core`. ([65380a0](https://github.com/ckeditor/ckeditor5/commit/65380a0))


## [1.0.0-beta.1](https://github.com/ckeditor/ckeditor5/compare/v1.0.0-alpha.2...v1.0.0-beta.1) (2018-03-15)

### Dependencies

New packages:

* [@ckeditor/ckeditor5-alignment](https://www.npmjs.com/package/@ckeditor/ckeditor5-alignment): [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-alignment/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-build-decoupled-document](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-decoupled-document): [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-build-decoupled-document/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-editor-decoupled](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-decoupled): [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-editor-decoupled/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-font](https://www.npmjs.com/package/@ckeditor/ckeditor5-font): [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-font/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-highlight](https://www.npmjs.com/package/@ckeditor/ckeditor5-highlight): [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-highlight/releases/tag/v1.0.0-beta.1)

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-build-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-balloon): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-build-balloon/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-build-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-inline): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-build-inline/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-cloudservices](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloudservices): v1.0.0-alpha.1 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-cloudservices/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-core/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-editor-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-balloon): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-editor-balloon/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-image/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-link/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-list/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v1.0.0-beta.1)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v1.0.0-alpha.2 => [v1.0.0-beta.1](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v1.0.0-beta.1)


## [1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5.git/compare/v1.0.0-alpha.1...v1.0.0-alpha.2) (2017-11-14)

### Dependencies

New packages:

* [@ckeditor/ckeditor5-cloudservices](https://www.npmjs.com/package/@ckeditor/ckeditor5-cloudservices): [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-cloudservices/releases/tag/v1.0.0-alpha.1)

Major releases (contain breaking changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-build-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-balloon): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-build-balloon/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-build-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-inline): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-build-inline/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-core/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-editor-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-balloon): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-editor-balloon/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-image/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-link/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-list/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v1.0.0-alpha.2)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v1.0.0-alpha.1 => [v1.0.0-alpha.2](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v1.0.0-alpha.2)

### Bug fixes

Besides changes in the dependencies, this version also contains the following bug fixes:

* Brought back `@ckeditor/ckeditor5-editor-classic` which got mistakenly removed from the main `package.json` just before the release. Closes [#585](https://github.com/ckeditor/ckeditor5/issues/585). ([c2d246b](https://github.com/ckeditor/ckeditor5/commit/c2d246b))


## [1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5/compare/v0.11.0...v1.0.0-alpha.1) (2017-10-03)

New packages:

* [@ckeditor/ckeditor5-easy-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-easy-image): [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-easy-image/releases/tag/v1.0.0-alpha.1)

Major releases (possible breaking changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v0.1.1 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v0.1.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v0.9.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v0.2.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-build-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-balloon): v0.1.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-build-balloon/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v0.3.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-build-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-inline): v0.1.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-build-inline/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v0.7.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v0.9.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-core/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-editor-balloon](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-balloon): v0.1.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-editor-balloon/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v0.8.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): v0.2.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v0.11.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v0.10.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-essentials](https://www.npmjs.com/package/@ckeditor/ckeditor5-essentials): v0.3.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-essentials/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v0.10.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v0.7.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-image/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v0.8.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-link/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v0.7.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-list/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v0.4.4 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v0.9.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v0.9.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v0.10.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v0.10.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v0.9.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v0.2.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v0.10.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v1.0.0-alpha.1)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v0.2.0 => [v1.0.0-alpha.1](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v1.0.0-alpha.1)

BREAKING CHANGES:

Besides breaking changes introduced in the dependencies, the following breaking changes were introduced:

* The `@ckeditor/ckeditor5-build-balloon-toolbar` package was renamed to `@ckeditor/ckeditor5-build-balloon`.
* The `@ckeditor/ckeditor5-editor-balloon-toolbar` package was renamed to `@ckeditor/ckeditor5-editor-balloon`.
* The `@ckeditor/ckeditor5-presets` package was renamed to `@ckeditor/ckeditor5-essentials` and the `Article` preset plugin was made a development util. See [ckeditor/ckeditor5-essentials#1](https://github.com/ckeditor/ckeditor5-presets/issues/1).


## [0.11.0](https://github.com/ckeditor/ckeditor5/compare/v0.10.0...v0.11.0) (2017-09-03)

New packages:

* [@ckeditor/ckeditor5-build-balloon-toolbar](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-balloon-toolbar): [v0.1.0](https://github.com/ckeditor/ckeditor5-build-balloon-toolbar/releases/tag/v0.1.0)
* [@ckeditor/ckeditor5-build-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-inline): [v0.1.0](https://github.com/ckeditor/ckeditor5-build-inline/releases/tag/v0.1.0)
* [@ckeditor/ckeditor5-editor-balloon-toolbar](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-balloon-toolbar): [v0.1.0](https://github.com/ckeditor/ckeditor5-editor-balloon-toolbar/releases/tag/v0.1.0)

Minor releases (possible breaking changes):

* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v0.5.1 => [v0.6.0](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v0.6.0)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v0.8.1 => [v0.9.0](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v0.9.0)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v0.1.1 => [v0.2.0](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v0.2.0)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v0.2.0 => [v0.3.0](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v0.3.0)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v0.6.0 => [v0.7.0](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v0.7.0)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v0.8.1 => [v0.9.0](https://github.com/ckeditor/ckeditor5-core/releases/tag/v0.9.0)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v0.7.3 => [v0.8.0](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): v0.1.1 => [v0.2.0](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v0.2.0)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v0.10.0 => [v0.11.0](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v0.11.0)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v0.9.1 => [v0.10.0](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v0.10.0)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v0.9.1 => [v0.10.0](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v0.10.0)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v0.6.0 => [v0.7.0](https://github.com/ckeditor/ckeditor5-image/releases/tag/v0.7.0)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v0.7.0 => [v0.8.0](https://github.com/ckeditor/ckeditor5-link/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v0.6.1 => [v0.7.0](https://github.com/ckeditor/ckeditor5-list/releases/tag/v0.7.0)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v0.8.0 => [v0.9.0](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v0.9.0)
* [@ckeditor/ckeditor5-presets](https://www.npmjs.com/package/@ckeditor/ckeditor5-presets): v0.2.2 => [v0.3.0](https://github.com/ckeditor/ckeditor5-presets/releases/tag/v0.3.0)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v0.8.0 => [v0.9.0](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v0.9.0)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v0.9.1 => [v0.10.0](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v0.10.0)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v0.9.0 => [v0.10.0](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v0.10.0)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v0.8.1 => [v0.9.0](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v0.9.0)
* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): v0.1.0 => [v0.2.0](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v0.2.0)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v0.9.1 => [v0.10.0](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v0.10.0)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v0.1.1 => [v0.2.0](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v0.2.0)

Patch releases (bug fixes, internal changes):

* [@ckeditor/ckeditor5-adapter-ckfinder](https://www.npmjs.com/package/@ckeditor/ckeditor5-adapter-ckfinder): v0.1.0 => [v0.1.1](https://github.com/ckeditor/ckeditor5-adapter-ckfinder/releases/tag/v0.1.1)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v0.4.3 => [v0.4.4](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v0.4.4)


## [0.10.0](https://github.com/ckeditor/ckeditor5/compare/v0.9.0...v0.10.0) (2017-05-07)

New packages:

* [@ckeditor/ckeditor5-upload](https://www.npmjs.com/package/@ckeditor/ckeditor5-upload): [v0.1.0](https://github.com/ckeditor/ckeditor5-upload/releases/tag/v0.1.0)

Minor releases (possible breaking changes):

* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): v0.1.1 => [v0.2.0](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v0.2.0)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v0.5.0 => [v0.6.0](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v0.6.0)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v0.9.0 => [v0.10.0](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v0.10.0)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v0.5.0 => [v0.6.0](https://github.com/ckeditor/ckeditor5-image/releases/tag/v0.6.0)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v0.6.0 => [v0.7.0](https://github.com/ckeditor/ckeditor5-link/releases/tag/v0.7.0)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v0.7.0 => [v0.8.0](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v0.7.0 => [v0.8.0](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v0.8.0 => [v0.9.0](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v0.9.0)

Patch releases (bug fixes, internal changes):

* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v0.5.0 => [v0.5.1](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v0.5.1)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v0.8.0 => [v0.8.1](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v0.8.1)
* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): v0.1.0 => [v0.1.1](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v0.1.1)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v0.8.0 => [v0.8.1](https://github.com/ckeditor/ckeditor5-core/releases/tag/v0.8.1)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v0.7.2 => [v0.7.3](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v0.7.3)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): v0.1.0 => [v0.1.1](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v0.1.1)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v0.9.0 => [v0.9.1](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v0.9.1)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v0.9.0 => [v0.9.1](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v0.9.1)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v0.6.0 => [v0.6.1](https://github.com/ckeditor/ckeditor5-list/releases/tag/v0.6.1)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v0.4.2 => [v0.4.3](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v0.4.3)
* [@ckeditor/ckeditor5-presets](https://www.npmjs.com/package/@ckeditor/ckeditor5-presets): v0.2.1 => [v0.2.2](https://github.com/ckeditor/ckeditor5-presets/releases/tag/v0.2.2)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v0.9.0 => [v0.9.1](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v0.9.1)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v0.8.0 => [v0.8.1](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v0.8.1)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v0.9.0 => [v0.9.1](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v0.9.1)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): v0.1.0 => [v0.1.1](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v0.1.1)


## [0.9.0](https://github.com/ckeditor/ckeditor5/compare/v0.8.0...v0.9.0) (2017-04-05)

New packages:

* [@ckeditor/ckeditor5-block-quote](https://www.npmjs.com/package/@ckeditor/ckeditor5-block-quote): [v0.1.0](https://github.com/ckeditor/ckeditor5-block-quote/releases/tag/v0.1.0)
* [@ckeditor/ckeditor5-build-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic): [v0.1.0](https://github.com/ckeditor/ckeditor5-build-classic/releases/tag/v0.1.0)
* [@ckeditor/ckeditor5-editor-inline](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-inline): [v0.1.0](https://github.com/ckeditor/ckeditor5-editor-inline/releases/tag/v0.1.0)
* [@ckeditor/ckeditor5-widget](https://www.npmjs.com/package/@ckeditor/ckeditor5-widget): [v0.1.0](https://github.com/ckeditor/ckeditor5-widget/releases/tag/v0.1.0)

Minor releases (possible breaking changes):

* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v0.4.1 => [v0.5.0](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v0.5.0)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v0.7.1 => [v0.8.0](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v0.4.1 => [v0.5.0](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v0.5.0)
* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v0.7.0 => [v0.8.0](https://github.com/ckeditor/ckeditor5-core/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v0.8.0 => [v0.9.0](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v0.9.0)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v0.8.0 => [v0.9.0](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v0.9.0)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v0.8.0 => [v0.9.0](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v0.9.0)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v0.4.0 => [v0.5.0](https://github.com/ckeditor/ckeditor5-image/releases/tag/v0.5.0)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v0.5.1 => [v0.6.0](https://github.com/ckeditor/ckeditor5-link/releases/tag/v0.6.0)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v0.5.1 => [v0.6.0](https://github.com/ckeditor/ckeditor5-list/releases/tag/v0.6.0)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v0.6.1 => [v0.7.0](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v0.7.0)
* [@ckeditor/ckeditor5-presets](https://www.npmjs.com/package/@ckeditor/ckeditor5-presets): v0.1.1 => [v0.2.0](https://github.com/ckeditor/ckeditor5-presets/releases/tag/v0.2.0)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v0.6.1 => [v0.7.0](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v0.7.0)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v0.8.0 => [v0.9.0](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v0.9.0)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v0.7.1 => [v0.8.0](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v0.7.1 => [v0.8.0](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v0.8.0 => [v0.9.0](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v0.9.0)

Patch releases (bug fixes, internal changes):

* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v0.7.1 => [v0.7.2](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v0.7.2)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v0.4.1 => [v0.4.2](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v0.4.2)


## [0.8.0](https://github.com/ckeditor/ckeditor5/compare/v0.7.0...v0.8.0) (2017-03-06)

New packages:

* [@ckeditor/ckeditor5-presets](https://www.npmjs.com/package/@ckeditor/ckeditor5-presets): [v0.1.1](https://github.com/ckeditor/ckeditor5-presets/releases/tag/v0.1.1)

Minor releases (possible breaking changes):

* [@ckeditor/ckeditor5-core](https://www.npmjs.com/package/@ckeditor/ckeditor5-core): v0.6.0 => [v0.7.0](https://github.com/ckeditor/ckeditor5-core/releases/tag/v0.7.0)
* [@ckeditor/ckeditor5-engine](https://www.npmjs.com/package/@ckeditor/ckeditor5-engine): v0.7.0 => [v0.8.0](https://github.com/ckeditor/ckeditor5-engine/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-enter](https://www.npmjs.com/package/@ckeditor/ckeditor5-enter): v0.7.0 => [v0.8.0](https://github.com/ckeditor/ckeditor5-enter/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-heading](https://www.npmjs.com/package/@ckeditor/ckeditor5-heading): v0.7.0 => [v0.8.0](https://github.com/ckeditor/ckeditor5-heading/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-image](https://www.npmjs.com/package/@ckeditor/ckeditor5-image): v0.3.0 => [v0.4.0](https://github.com/ckeditor/ckeditor5-image/releases/tag/v0.4.0)
* [@ckeditor/ckeditor5-typing](https://www.npmjs.com/package/@ckeditor/ckeditor5-typing): v0.7.0 => [v0.8.0](https://github.com/ckeditor/ckeditor5-typing/releases/tag/v0.8.0)
* [@ckeditor/ckeditor5-utils](https://www.npmjs.com/package/@ckeditor/ckeditor5-utils): v0.7.0 => [v0.8.0](https://github.com/ckeditor/ckeditor5-utils/releases/tag/v0.8.0)

Patch releases (bug fixes, internal changes):

* [@ckeditor/ckeditor5-autoformat](https://www.npmjs.com/package/@ckeditor/ckeditor5-autoformat): v0.4.0 => [v0.4.1](https://github.com/ckeditor/ckeditor5-autoformat/releases/tag/v0.4.1)
* [@ckeditor/ckeditor5-basic-styles](https://www.npmjs.com/package/@ckeditor/ckeditor5-basic-styles): v0.7.0 => [v0.7.1](https://github.com/ckeditor/ckeditor5-basic-styles/releases/tag/v0.7.1)
* [@ckeditor/ckeditor5-clipboard](https://www.npmjs.com/package/@ckeditor/ckeditor5-clipboard): v0.4.0 => [v0.4.1](https://github.com/ckeditor/ckeditor5-clipboard/releases/tag/v0.4.1)
* [@ckeditor/ckeditor5-editor-classic](https://www.npmjs.com/package/@ckeditor/ckeditor5-editor-classic): v0.7.0 => [v0.7.1](https://github.com/ckeditor/ckeditor5-editor-classic/releases/tag/v0.7.1)
* [@ckeditor/ckeditor5-link](https://www.npmjs.com/package/@ckeditor/ckeditor5-link): v0.5.0 => [v0.5.1](https://github.com/ckeditor/ckeditor5-link/releases/tag/v0.5.1)
* [@ckeditor/ckeditor5-list](https://www.npmjs.com/package/@ckeditor/ckeditor5-list): v0.5.0 => [v0.5.1](https://github.com/ckeditor/ckeditor5-list/releases/tag/v0.5.1)
* [@ckeditor/ckeditor5-markdown-gfm](https://www.npmjs.com/package/@ckeditor/ckeditor5-markdown-gfm): v0.4.0 => [v0.4.1](https://github.com/ckeditor/ckeditor5-markdown-gfm/releases/tag/v0.4.1)
* [@ckeditor/ckeditor5-paragraph](https://www.npmjs.com/package/@ckeditor/ckeditor5-paragraph): v0.6.0 => [v0.6.1](https://github.com/ckeditor/ckeditor5-paragraph/releases/tag/v0.6.1)
* [@ckeditor/ckeditor5-theme-lark](https://www.npmjs.com/package/@ckeditor/ckeditor5-theme-lark): v0.6.0 => [v0.6.1](https://github.com/ckeditor/ckeditor5-theme-lark/releases/tag/v0.6.1)
* [@ckeditor/ckeditor5-ui](https://www.npmjs.com/package/@ckeditor/ckeditor5-ui): v0.7.0 => [v0.7.1](https://github.com/ckeditor/ckeditor5-ui/releases/tag/v0.7.1)
* [@ckeditor/ckeditor5-undo](https://www.npmjs.com/package/@ckeditor/ckeditor5-undo): v0.7.0 => [v0.7.1](https://github.com/ckeditor/ckeditor5-undo/releases/tag/v0.7.1)
