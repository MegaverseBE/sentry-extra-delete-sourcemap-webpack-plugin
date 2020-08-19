# delete-sourcemap-webpack-plugin

delete source map files after uploaded to sentry or anywhere

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
