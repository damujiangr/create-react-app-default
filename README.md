# create-react-app-default
react脚手架初始化的默认工程
> 使用yarn 代替 npm
### 步骤
1. 添加Sass支持
> yarn add node-sass --dev 
```$xslt
"scripts": {
+    "build-css": "node-sass src/ -o src/",
+    "watch-css": "yarn run build-css && node-sass src/ -o src/ --watch --recursive"
```