1. hash配置：
    1. 文件名使用`[name].[contenthash].css`,`[name].[contenthash].js`方式，可以在文件名上直接附着md5
    2. HtmlWebpackPlugin的配置中使用`hash: true`可以在html引入的资源中加上`?md5`的方法，更优雅