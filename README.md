# [single-spa-vue](https://github.com/zou888wei/single-spa-vue)
原生single-spa项目 | single-spa vue | single-spa react，本项目以vue2为基座(my-root)，搭配三个子应用：my-vue2子应用，my-vue3 (TS) 子应用，my-react子应用，此项目用于学习与理解single-spa的使用及与各个框架搭建

整体项目都是基于vue和react框架的脚手架搭建，并且使用pnpm进行依赖管理，如果修改了目录名字，需要删除node_modules重新建立依赖关系，或者自行改成yarn、npm等

框架项目不推荐集成原生html项目，还不如直接用iframe切换，除非也有一个入口js能进行模块化

使用方法：

```cmake
git clone https://github.com/zou888wei/single-spa-vue.git

cd single-spa-vue

pnpm install

pnpm serve

// 各个子项目也可以独立运行查看
// my-vue2: http://localhost:11001
// my-vue3: http://localhost:11002
// my-react: http://localhost:11003
```

## 待完善

```
1. 集成vite-vue、vite-react（vite环境与webpack环境不一致，需要更改基座构建环境来适配）
2. 增加angule
```

## 扩展项目

1. single-spa-webpack5：[single-spa + Module Federation](https://github.com/zou888wei/single-spa-webpack5.git)
2. qiankun-webpack5（待添加）
3. micro-app-demo（待添加）

