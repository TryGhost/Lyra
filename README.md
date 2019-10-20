# Hydra

A paid-members publication for Ghost

&nbsp;

<p>This theme includes a custom <code>routes.yaml</code> file which needs to be uploaded inside Ghost Admin, under <code>Labs > Custom Routes</code></p>
<p>Once you've uploaded the custom routes file to Ghost Admin, these instructions will automatically disappear - and all of your signup/signin routes will work with the included template files in this theme.</p>
<p>If you need help, check out the <a href="https://ghost.org/docs/members/">Ghost members documentation</a> or chat with other Ghost users on <a href="https://forum.ghost.org">Ghost forum</a>.</p>


# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
$ yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
yarn zip
```

# PostCSS Features Used

- Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major versions of every browser.
- Variables - Simple pure CSS variables
- [Color Function](https://github.com/postcss/postcss-color-function)


# Copyright & License

Copyright (c) 2013-2019 Ghost Foundation - Released under the [MIT license](LICENSE).
