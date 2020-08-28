# docusaurus-plugin-plausible

[![npm package](https://flat.badgen.net/npm/v/docusaurus.plugin-plausible)](https://badgen.net/npm/v/docusaurus-plugin-plausible)

A Docusaurus plugin for [Plausible](https://plausible.io/) analytics. Inspired by [gatsby-plugin-plausible](https://github.com/Aquilio/gatsby-plugin-plausible).

---

- [Install](#install)
- [Options](#options)
- [License](#license)

## Install

1. Install `docusaurus-plugin-plausible`

  `npm install --save docusaurus-plugin-plausible`

2. Add plugin to `docusaurus.config.js`

  ```javascript
  module.exports = {
    ...
    plugins: [
      [
        path.resolve(__dirname, '../docusaurus-plugin-plausible'),
        {
          domain,
        },
      ]
    ],
  };
  ```

### Options

 * `domain` (required) - The domain added in Plausible
 * `customDomain` - A custom domain if configured in Plausible
 * `excludePaths` - An array of paths to exclude when sending page view events

## License

[Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)