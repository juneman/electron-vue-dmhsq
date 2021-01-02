# electron-vue-dmhsq

基于Vue2.x

# 目录说明
```
electron文件夹控制桌面端的运行打包
 其余均为 vue目录
 electron/main.js  桌面应用主程序
 electron/main.js  桌面应用渲染程序
 ```
 

博客地址

[https://blog.csdn.net/qq_42027681/article/details/112077082](https://blog.csdn.net/qq_42027681/article/details/112077082)


最终打包需要删除electron/main.js中的fs模块
如果您只是想打包vue项目成exe 
```
npm run builds
执行完成后
在electron文件夹中
npm run build
```
[github地址](https://github.com/dmhsq/electron-vue-dmhsq)


electron中的 dist和src为测试 不用理会


## 安装依赖
```
npm install
```

### 热开发页面
```
npm run serve
```

### 只打包vue 不打包electron
```
npm run builds
```
### 热开发页面
```
npm run build
执行完成后
开启额外的控制台
cd electron
npm run serve
```

### 热开发electron
```
npm run builds
执行完成后
开启额外的控制台
cd electron
npm run serve
```

### 打包electron应用
```
最终打包需要删除electron/main.js中的fs模块
npm run builds
执行完成后（如果页面已经打包过无需此步）
在electron文件夹中
npm run build
```
