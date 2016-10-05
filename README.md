# gitbook-plugin-addcssjs
<p>
  <a href="https://www.npmjs.com/package/gitbook-plugin-addcssjs"><img src="https://img.shields.io/npm/dt/gitbook-plugin-addcssjs.svg" alt="Downloads"></a>
</p>
Plugin for gitbook for adding external css and js files to the git book.

## How to use
- Add addcssjs plugin to your book.json:


    "plugins": [
      "addcssjs"
    ]
- Add plugin configuration specifying css and js files to include:


    "pluginsConfig": {
      "addcssjs": {
        "js": ["js/custom.js"],
        "css": ["css/custom.css"]
      }
    }
