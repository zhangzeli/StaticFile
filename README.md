# StaticFile

[参考资料](https://blog.csdn.net/qq_36910987/article/details/89562291)

相信用过github的道友，应该遇到过github加载很慢，甚至打不开的情状。现在，好用的jsDelivr就用上场了，可免费提供CDN加速了，可谓是前端的良心神器之一

jsDelivr 是一个免费、开源的加速CDN公共服务，托管了许多大大小小的项目，可加速访问托管的项目目录或图片资源。如果你想加载github某个仓库中的某张图片，

可以通过jsDelivr来访问加载的。另外打开仓库目录，使用jsDelivr打开目录， 打开的目录页面也是简单实用的；

# 使用方法

## github

>https://cdn.jsdelivr.net/gh/用户名称/仓库名称@版本号/目录

```

//加载资源(版本号不填的话，默认引用最新
https://cdn.jsdelivr.net/gh/murenziwei/images/draw/01.png
//打开目录（后面的"/"是必要的，不然的话，打不开）
https://cdn.jsdelivr.net/gh/murenziwei/images/
```

## 二、访问npm的用法

```
https://cdn.jsdelivr.net/npm/包名@版本号/目录
//加载资源
https://cdn.jsdelivr.net/npm/lw_firewords@1.0.3/index.js
//打开目录（后面的"/"是必要的，不然的话，打不开）
https://cdn.jsdelivr.net/npm/lw_firewords/
```