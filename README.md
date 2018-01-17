README

目录结构 参考[Vuex](https://vuex.vuejs.org/zh-cn/structure.html) 

```shell
├── dist                       // 构建后文件 
├── build                      // 构建相关 
├── config                     // 配置相关
├── src                        // 源代码相关
│   ├── api                    // 所有请求
│   ├── assets                 // 主题 字体等静态资源 公共的style等
│   ├── components             // 全局公用组件
│   ├── directive              // 全局指令
│   ├── filtres                // 全局filter
│   ├── mock                   // mock虚拟数据
│   ├── router                 // 路由
│   ├── store                  // 全局store管理
│   ├── pages                  // 各页面相关
│   ├── styles                 // 全局css样式
│   ├── App.vue                // 入口页面
│   └── main.js                // 入口 加载组件 初始化等
├── .gitignore                 // git 忽略项
├── favicon.ico                // favicon图标
├── index.html                 // html模板
└── package.json               // package.json

```
运行
```git
npm start
```
编译
```git
npm run build
```


