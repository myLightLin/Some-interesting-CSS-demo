CSS 世界博大精深，写过 css 的都知道，很多时候总是出现一些莫民奇妙的状况，你写的代码最后实现出来跟你预想的完全不同，特别是有时在那里悲催地找原因找了一下午，最后才发现是某个变量某个字符写错而导致，真 skr 惨。今天介绍几个有趣的 css 效果，是从书上看来的，有些可能你以前都没想到这么实现过，可以学习下作者的思路，对你以后写出更好的 css 代码会有帮助。
1. **显示/收缩效果**

这个效果比较常用到，具体效果如下：
![gif动图](http://p81yl6eww.bkt.clouddn.com/18-10-21/76874491.jpg)

2. **正在加载中动画**

在加载网页时经常会用到这个动画，为了缓解图片文字资源未加载时用来过渡，极大地增强了用户体验，效果大致如下：

![正在加载中](http://p81yl6eww.bkt.clouddn.com/18-10-21/45529891.jpg)

3. **css 自行实现小图标**

在日常开发的过程中经常会用到小图标，除了可以去 [阿里图标](http://www.iconfont.cn/) 下载之外，一些较简单的图标可以自己用 css 实现，方法是利用 border 和 background 属性，效果如下：
![宽高扩大了 10 倍显示](http://p81yl6eww.bkt.clouddn.com/18-10-21/99543278.jpg)

4. **border 实现边框**

很多时候会遇到需要有一个上传按钮，点击按钮后上传文件，如下面这样的效果：
![按钮](http://p81yl6eww.bkt.clouddn.com/18-10-21/17392425.jpg)
此时可以用 a 标签来承载，在通过 border 属性来定义虚线框，利用伪元素来定位，使中间的 + 号能水平垂直居中。

5. **纯 css 实现自适应的弹框**

弹框，也就是 dialog ，经常也是在网页中看到，例如有些网页点击登录注册时就会跳出一个弹框来显示登录注册页面，而下面的效果是使用 css 完成的，并且可以自适应，无论窗口的大小，始终能保持水平垂直居中，很好的一个实现方法。
![水平垂直居中弹框](http://p81yl6eww.bkt.clouddn.com/18-10-21/80794477.jpg)

这些 css 效果有些非常实用，建议收藏起来，没准以后会用到，另外，以上的完整代码全都放在 GitHub 上了，点击下方的「阅读原文」可以进去下载，觉得有用点个赞！

> 参考资料
张鑫旭——《 css 世界》

PS：最近 Chrome 70 正式发布了，不得不说，谷歌这波更新的真快，不过我下载体验了一下，整体跟 69 版本没什么大的变化，至于新增的那些画中画、拖拽 API 什么的目前也没用得上什么，感兴趣的直接去 [官网](https://www.google.com/intl/zh-CN_ALL/chrome/) 下载最新的版本就好，目前只有桌面版，移动端版本的还要等些时间。

欢迎关注公众号 「frondev」
