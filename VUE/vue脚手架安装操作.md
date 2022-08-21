#vue脚手架搭建

#### 1、查看node、npm版本、vue-cli版本、wepback版本
```
    node -v 
    npm -v
    vue -V
    webpack -v
```
#### 2、安装wepback
```
    npm install --global webpack  简写 npm i -g webpack
```
#### 3、npm安装vue
```
    npm install vue  简写 npm i vue
```
#### 4、npm安装vue-cli
```
    npm install --global @vue-cli  简写 npm i -g vue-cli
    npm install -g @vue/cli-service-global (安装扩展)
```
#### 5、创建vue项目
``` 
    步骤一：
        vue create 项目名 --创建项目
    
    步骤二：
        Please pick a preset: (Use arrow keys)  --请选择预置:(使用方向键)
        Default ([Vue 2] babel, eslint) -- 默认vue2 + babel + eslint
        Default (Vue 3) ([Vue 3] babel, eslint) -- 默认vue3 + babel + eslint
        Manually select features -- 自定义
        
    步骤三：
        ? Please pick a preset: Manually select features -- 选择自定义
        ? Check the features needed for your project: --  选择项目所需的特性:
         ( ) Choose Vue version -- 选择Vue版本
         ( ) Babel -- Babel 是一个 JavaScript 编译器
         ( ) TypeScript -- typescript是javascript超集, 一种强类型的前端语言
         ( ) Progressive Web App (PWA) Support  -- PWA(渐进式网页应用)
         ( ) Router --路由
         ( ) Vuex -- Vuex 是一个专为 Vue.js 应用程序开发的（状态管理模式 + 库）
         ( ) CSS Pre-processors -- css 预处理器
         ( ) Linter / Formatter -- 代码规范
         ( ) Unit Testing -- 单元测试
         ( ) E2E Testing -- E2E测试

    步骤四： ......
```