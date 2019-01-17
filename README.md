# delete-sourcemap-webpack-plugin

delete source map url and files after uploaded to anywhere

```javascript
// webpack.config.js
const DeleteSourceMapWebpackPlugin = require('delete-sourcemap-webpack-plugin')

module.exports = {
    // ...
    plugins: [
        new DeleteSourceMapWebpackPlugin()
    ],
    // ...
}
```