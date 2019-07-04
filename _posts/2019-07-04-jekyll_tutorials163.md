---
layout: post
title: 关于修改css外观的心得
date: 2019-07-04
tags: 平面设计
---

其实修改css并不复杂。可以先跟着老师的这个commit操作
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn00o6qc5bj216802jaa9.jpg)


{% include toc.html %}

## 怎样修改css？
1. 打开notepad++
2. 打开文件_sass/_base.scss, _sass/_sliding-menu.scss, _sass/_tiles.scss和 _sass/_variables.scss
3. 再跟着老师的步骤做相应的修改

- 我的做法是在老师原有的基础上再做一些小改变。现在来讲讲我的心得吧٩(•̤̀ᵕ•̤́๑)

## 网页背景
保留了原本的样式没有变动

## 顶部的选项栏
我把字体分为 未悬停 状态和 悬停 状态。
- 未悬停
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn027u5i16j20gw03fglj.jpg)
- 悬停
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn0257ehydj20ir0463ye.jpg)

- 未悬停的颜色我选择Pantone #595959. 这是我以前做编辑时候常使用的文章字体颜色，它比黑色会更柔和一些，看起来会更舒服一些。
- 悬停的颜色我选择GoldEnrod #DAA520. 因为我的icon是枫叶（这是什么理由(´·ω·`)?），我希望整个网站中带些金色，这样会更和谐些。

修改方法：
- 未悬停时
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn02n80v5rj20ex09uwel.jpg)
- 悬停时
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn02htnfgaj20hd0fiab4.jpg)



## 右边的小盒子
这个小盒子也有悬停和未悬停的状态。
- 未悬停时
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn03nuhyd7j20do09zglu.jpg)
- 颜色是#77889C，使用了透明度让其更美观

- 悬停时
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn0413sfufj20hb0dqwfd.jpg)
- 颜色是GoldEnrod #DAA520

## 滑动菜单
我改动的地方是菜单的背景色，字体悬停时和不悬停时的颜色。
- 背景颜色1
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn09s350zmj20l00gr0tr.jpg)
- 这里我也运用了透明度
- 背景颜色2
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn09u1vndfj20je0f6aao.jpg)
- 标注的地方都要改成你想要的背景色代词
- 字体悬停时的颜色
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn0a46uy27j20g80hu74u.jpg)
- 因为GoldEnrod之前已经指代是什么颜色了，所以只需要填代词
- 字体未悬停时的颜色
![image](https://ws1.sinaimg.cn/large/747b3f6fgy1fn0a8s61jjj20bg08rt8t.jpg)

## 关于这篇心得有一些话想说
- 网页主体颜色我选用了金色、灰色和白色，我认为简约风格的主题色可以提高用户体验。
- 其实我还有一些弄不懂的地方，以上的总结或许还存在着一些问题。希望大家可以给我一些建议，我会虚心接受。( ´·ᴗ·` )

## 小帮助
- 修改的时候，务必注意缩进问题
- 善于使用Chrome inspector
- [配色手册][shouce]
- [RGB颜色值与十六进制颜色码转换工具][tool]
- [颜色对照表][comparisontable]


[shouce]: http://www.uisdc.com/simplest-color-matching-guideline
[tool]: http://www.sioe.cn/yingyong/yanse-rgb-16/
[comparisontable]: http://tool.oschina.net/commons?type=3