### 初始化安装

```text
yarn create react-app test
cd test
yarn add electron --dev

yarn add electron-is-dev
yarn add concurrently --dev
yarn add wait-on --dev
yarn add electron-rebuild --dev
yarn electron-rebuild -f -w sqlite3

```

###调试环境
yarn dev




##打包
```text
> 先用webpack打包React应用到`build`目录下
>> yarn react-scripts build 
>
> 再用eletron-builder打包Electron应用
>> yarn eletron-builder
```
 
##clone init
yarn install
