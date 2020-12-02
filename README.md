# 邓清

## 重点

- 工作经验一年半
- 期望薪资12k-15k，现在9k
- 身份证年龄20
- 中专学历
- 成人大专在读，2022.3毕业

## 个人信息

- 手机号：15917033340
- 微信：15917033340
- 邮箱：1247748612@qq.com
- github：[https://github.com/1247748612](https://github.com/1247748612)

[工作经历](https://www.notion.so/0480a6185dab4499985bcd68188ed376)

## 项目合集

[工作项目](https://www.notion.so/164d15c02b2c4eb89287a00b0d30b51f)

[实践项目](https://www.notion.so/5f42800bb8b549c5b4ec4d7d5a52ab77)

## 其他实践或非项目实践

1. 刚学编程时，是写python爬虫的。写了大概很多python代码
2. 有整过jenkins和drone自动化部署，还有其他的忘了。
    1. jenkins太庞大了，起初我用本地电脑，性能较好带的动，然后用阿里云的学生服务器，部署到一半直接挂了。
    2. drone的话，简洁，ui也不错。依赖服务器，需要域名。我部署的时候感觉很忙，可能也要好一点的性能。
3. docker，我基本上拿来部署项目，和跑一些脚本，因为他可以自动重启。也曾试过用vscode打开remote-container然后打开docker容器来跑项目，让我叹为观止。
4. 也在接触flutter，重心还是想放在前端上。
5. vscode重度使用，装了一百多个插件。知道各种骚操作和常用插件的使用。如用vscode连ssh
6. 忘了

## 掌握技能

1. 熟练使用vue全家桶，基本掌握angular开发和react开发
2. 掌握node的nest后端框架
3. 熟练使用python编写爬虫
4. 会使用mongodb和redis数据库
5. 掌握chrome各种调试能
6. 熟练使用docker部署项目。
7. 熟练使用git管理项目，了解git-flow大致流程
8. 会使用webpack搭建项目架构和项目优化
9. 小程序会使用原生开发，和各类框架开发，如mpx、melgao、uniapp、wepy
10. css预处理则会使用scss。
11. 熟悉ci/cd流程

## 个人总结

工作中高效完成分配下来的任务，并积极学习技术。把掌握的东西，运用在工作上。了解工作上的痛点，并写工具提高效率。

工作外的时间，从掘金、知乎、b站、github中学习技术，并动手实践。并带到项目上提高工作效率。提供个人水平。

## 心路历程

大概是16年接触编程的吧，那时候是中专第二年。最开始是接触易语言，听人说不太行，然后就去学c语言，看的是黑马的视频，不知道是不是我找的视频不对，是从c++开始学的。学的挺费劲的，然后查资料看别人说，然后就重学c语言。把c语言基础过完了，也不知道能干啥。不知道啥原因就跑去学java了，后面对android感兴趣就学android了，学的更费劲了，api也太长了吧记不住。到后面看论坛看别人说python爬虫挺牛逼的，也简单，就学python了，这时候已经是中专要实习了，不过我没去。对比之前学的语言来说，python是最简单的了。然后也运气好，加入了一个写代码的群，接了很多python的单子，提高了python的技术。后面在华立技师读书，加入了本科的社团，也颓废了一段时间没怎么学东西。临近高技快毕业。感觉python找不到工作，得感觉学门技术。对比之后，感觉前端最好学了，就学了前端，因为自己有其他语言的基础，加上之前写爬虫，对html、js有些了解。学的就更轻松了。其实后面深入我感觉还是挺难的，经过一年多的技术积累，然后到现在，估摸着认真学前端应该就最多两年吧。建基础模板非常的繁琐，和没必要。如果能直接把基础页面功能做了，之后的项目套用开发岂不是更快吗。本项目，先后使用 vue 和 angular 加上后端 nestjs 实现过。本打算继续使用 react 实现一套，采用的 umi，但多次尝试，达不到我想要的效果就放弃了。

### **基于 vue**

> 和房必应的后台非常相似，但去除了许多不必要的包，也没有采用 avue 来解决页面的 crud。而是参考 avue，采用 elementui 开发了一套简单版的 avue。但它也是高可服用的，因为是自己开发的，有了迭代的便利。[项目预览](https://www.dengqing.net/vue-admin/#/login?redirect=%2Fhome)

- 技术栈（都采用 typescript 开发）：
- 前端：vue 全家桶，element-ui，tinymce，mavon。
- 后端：nestjs，mongodb，redis
- 功能点：
- 前端：基于 rbac 权限模型设计，根据权限标识符权限精确到按钮级别。动态配置路由及在线用户踢出等。
- 后端：基于权限标识符，针对用户，对应等标识符，做到接口级别的权限判断，就算是跑接口也会返回 401，超级权限用户则随意访问任意接口。
- 页面：系统级页面包含，用户管理、角色管理、菜单管理、字典管理、在线用户管理和日志管理
- 实现难点：针对接口级别的权限判断，后面参考了各种解决方案，了解到了 rbac 权限模型的方式，根据权限标识符去做拦截，才实现的。

### **基于 angular**

> 这个项目目的是为了上手 angular，了解各类框架的不同。angular 和 nestjs 有着非常相似的开发模式，依赖注入。并且两个框架都支持 rxjs。rxjs 大大减少了要封装的代码。如 debounce 和 throttle。我采用的是 ng-alain 进行二次开发。大大的减少了开发周期。[项目预览](https://1247748612.github.io/angular-alain-admin/#)

- 开发周期：一个星期
- 技术栈
- 前端：angular 全家桶，typescript
- 后端：沿用了基于 vue 的后端
- 功能点：
    - 前端：所有功能点都已经被 ng-alain 封装好了。我只需要在用到到时候，依赖注入即可。在 angular 里并没有动态配置路由的方式（或许我没看见）动态路由也不好做懒加载。采用的方式是在 angular 里定义好路由，使用路由守卫做路由拦截，达到了一样的效果。
- 后端：改动了菜单的配置，根据 ng-alain 重新设计菜单表。
- 实现难点：
- 没有像 vue 和 react 一样的 props 多层传递的好方案。
- 在做动态菜单那块时，我一直在寻找和 vue 类似的解决方案，最好实在没找到后采用了路由守卫的方式来做。每个路由都有一个守卫，这则增加了大量的不必要的代码
- 其他的难点已忘记

## chexiu-cli脚手架

> 起初是好奇脚手架怎么实现的，顺便想完整用webpack搭建一个vue+ts的项目出来，巩固webpack基础。 然后实现了此项目。[github地址](https://github.com/1247748612/chexiu-cli)

项目命令

- publish
    - 自动化把打包后的build文件推送到build分支并打下tag，这个命令是根据公司的部署方式而实现的。
- create
    - 创建基于webpack5搭建的vue项目。分ts和js版，用命令区分

webpack搭建出来的项目，包括postcss、babel、scss、eslint等等插件。详情看项目的templates文件夹

## ts-axios库

> 项目是看着[https://coding.imooc.com/class/330.html](https://coding.imooc.com/class/330.html) 这个视频完整实现了一遍，并升级了rollup的插件和typescript，还配置了babel，eslint等等。最重要的是，实现了小程序的适配器，适配了原生的微信小程序和uniapp。> [github地址](https://github.com/1247748612/ts-axios)、[npm地址](https://www.npmjs.com/package/@dengqing/mp-axios)

小程序的适配器原理其实就是用的wx.request，并且axios官方库提供了一个配置参数adapter，可自己实现适配器。我是把适配器实现在核心里面了，不需要在外面配置了。

项目未完全经过jest测试，只测了一个文件，没空整了。

## 个人简历项目 （旧的，未更新简历）

> 采用 mdnice 编写好简历，用 gatsby 去展示，github pages 部署 [预览地址](https://1247748612.github.io/resume/)

- 技术栈： gatsby、markdown
- 功能点：使用 gatsby 插件 gatsby-transformer-remark 将简历.md 转为 html 渲染成页面
- 页面：简历页、404 页
- 项目状态： 正常运行中

---

## 其他实践或非项目实践

1. 刚学编程时，是写python爬虫的。写了大概很多python代码
2. 有整过jenkins和drone自动化部署，还有其他的忘了。
    1. jenkins太庞大了，起初我用本地电脑，性能较好带的动，然后用阿里云的学生服务器，部署到一半直接挂了。
    2. drone的话，简洁，ui也不错。依赖服务器，需要域名。我部署的时候感觉很忙，可能也要好一点的性能。
3. docker，我基本上拿来部署项目，和跑一些脚本，因为他可以自动重启。也曾试过用vscode打开remote-container然后打开docker容器来跑项目，让我叹为观止。
4. 也在接触flutter，重心还是想放在前端上。
5. vscode重度使用，装了一百多个插件。知道各种骚操作和常用插件的使用。如用vscode连ssh
6. 忘了

## 掌握技能

1. 熟练使用vue全家桶，基本掌握angular开发和react开发
2. 掌握node的nest后端框架
3. 熟练使用python编写爬虫
4. 会使用mongodb和redis数据库
5. 掌握chrome各种调试能
6. 熟练使用docker部署项目。
7. 熟练使用git管理项目，了解git-flow大致流程
8. 会使用webpack搭建项目架构和项目优化
9. 小程序会使用原生开发，和各类框架开发，如mpx、melgao、uniapp、wepy
10. css预处理则会使用scss。
11. 熟悉ci/cd流程

## 个人总结

工作中高效完成分配下来的任务，并积极学习技术。把掌握的东西，运用在工作上。了解工作上的痛点，并写工具提高效率。

工作外的时间，从掘金、知乎、b站、github中学习技术，并动手实践。并带到项目上提高工作效率。提供个人水平。

## 心路历程

大概是16年接触编程的吧，那时候是中专第二年。最开始是接触易语言，听人说不太行，然后就去学c语言，看的是黑马的视频，不知道是不是我找的视频不对，是从c++开始学的。学的挺费劲的，然后查资料看别人说，然后就重学c语言。把c语言基础过完了，也不知道能干啥。不知道啥原因就跑去学java了，后面对android感兴趣就学android了，学的更费劲了，api也太长了吧记不住。到后面看论坛看别人说python爬虫挺牛逼的，也简单，就学python了，这时候已经是中专要实习了，不过我没去。对比之前学的语言来说，python是最简单的了。然后也运气好，加入了一个写代码的群，接了很多python的单子，提高了python的技术。后面在华立技师读书，加入了本科的社团，也颓废了一段时间没怎么学东西。临近高技快毕业。感觉python找不到工作，得感觉学门技术。对比之后，感觉前端最好学了，就学了前端，因为自己有其他语言的基础，加上之前写爬虫，对html、js有些了解。学的就更轻松了。其实后面深入我感觉还是挺难的，经过一年多的技术积累，然后到现在，估摸着认真学前端应该就最多两年吧。
