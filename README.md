#创建项目
```javascript
mkdir 201602webpack && cd 201602webpack  创建目录并进入此目录
touch README.md .gitignore  创建两个空文件
npm init -y                   生成项目配置文件package.json
```
> 如果不能在cmd下使用touch命令(创建新的空文件)，则需要把git所在目录配置到环境变量中
C:\Program Files\Git\usr\bin

## 初始化git
```javascript
sh git add -A
sh git commit -m"init"
sh git remote add origin git@github.com:zhufengnodejs/201602webpack.git
sh git push -u origin master
```

##安装webpack
```
$ npm install webpack -g
$ npm install webpack --sav
```

##命令行中使用
```
$   webpack app/index.js build/bundle.js
$   webpack app/index.js build/bundle.js -p -w -d --progress --display-error-details --profile
```
> 把源代码打包成 目标代码


##