# Web前端精髓

前端与移动开发 The front-end development [博客|Hexo](https://wuxianqiang.github.io/) [博客|CSDN](http://blog.csdn.net/wu_xianqiang) [博客|博客园](http://www.cnblogs.com/wuxianqiang/) [知乎|专栏](https://zhuanlan.zhihu.com/webqianduan)

## 目录

### 知识大全

1. [GitHub秘籍](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.zh-cn.md#markdown-%E6%96%87%E4%BB%B6%E8%AF%AD%E6%B3%95%E9%AB%98%E4%BA%AE)
2. [七天学会NodeJS](http://nqdeng.github.io/7-days-nodejs/)
3. [构建单页Web应用](https://github.com/xufei/blog/issues/5)

### 知识分析

1. `for-in` 循环再遍历的时候，默认的话可以把自己私有的和它所属类的原型上拓展的方法都可以变量到，但是一般情况下只要遍历私有的属性，解决方法：
```js
for (var key in object) {
    if (object.hasOwnProperty(key)) {
        
    }
}
```

> 支持作者请点击右上角的Star按钮
