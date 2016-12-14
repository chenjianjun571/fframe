# fframe
前端框架 react+redux+webpack

## 查看本地安装模块的版本号
npm ls redux-thunk
## 查看该模块的详细信息
npm info redux-thunk

# 安装webpack工具
npm install webpack --save-dev
# 安装样式文件的加载器,用于webpack打包模块里面使用
npm install style-loader css-loader postcss-loader jsx-loader --save-dev
# 安装html生成器插件
npm install html-webpack-plugin --save-dev
# 安装webpack开发服务器
npm install webpack-dev-server --save-dev
# 安装babel-core核心模块和babel-loader
npm install babel-loader babel-core --save-dev
# 安装 减少打包的时候重复代码，以上要注意是放在dev还是非dev上！
npm install babel-plugin-transform-runtime babel-runtime --save-dev
# 安装ES6,ES7和react支持
npm install babel-preset-es2015 babel-preset-stage-0 babel-preset-react --save-dev
# 安装热模块替换插件,主要用于开发环境,安装好以后在.babelrc文件里面配置
npm install babel-preset-react-hmre react-hot-loader --save-dev
# 安装babel的编译插件,安装好以后在.babelrc文件里面配置
npm install babel-plugin-transform-object-rest-spread --save-dev
# 安装静态代码检查工具
npm install eslint eslint-loader --save-dev
npm install eslint-config-airbnb eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react --save-dev
# 安装eslint的加载器
npm install babel-eslint --save-dev

# 安装 Polyfilla是一个英国产品,在美国称之为Spackling Paste(译者注:刮墙的,在中国称为腻子).
#      记住这一点就行:把旧的浏览器想象成为一面有了裂缝的墙.这些[polyfills]会帮助我们把这面墙的裂缝抹平
npm install babel-polyfill --save
# 安装react和react-dom
npm install react react-dom --save
# 安装isomorphic-fetch,让低版本浏览器支持fetch
npm install isomorphic-fetch --save
# 安装redux
npm install redux react-redux redux-thunk --save
# 安装lodash
npm install lodash --save







# https://github.com/xcatliu/react-ie8 要支持IE8必须使用react@15.x.x以下的版本
npm install --save es5-shim console-polyfill
# 主要是解决es3的保留字在es3环境下的正确使用,解决IE8下面的问题
# 保留字的使用做了es3兼容
# 解决es3的保留字在es3环境下的正确使用，default是暴露最多的问题，因为大家都在写export default xx
npm install es3ify-loader --save-dev


