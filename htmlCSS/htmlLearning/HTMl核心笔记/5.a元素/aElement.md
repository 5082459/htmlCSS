# a元素

超链接
## href属性
hyper reference(引用)
1. 跳转地址
2. 跳转到某个锚点（ex:#chapter2）

ex：
```html
(a[href="#chapter$"]>{章节$})*6

((h2[id="chapter$"]>{章节$})+p>lorem100)*6
```

```html
<!-- 回到顶部 -->
a[href="#"]>{回到顶部}
```

id属性：全局属性
3. 功能性链接
- 执行JS代码
```html
<a href="javascript:alert('你好')">弹出你好！</a>
```

- 发送邮件：mailto
```html
<a href="mailto:邮件地址">发送邮件</a>
```

- 拨打电话：tel
```html
<!-- 拨打电话 要求安装拨号软件-->
<a href="tel:13340883549">拨打电话</a>
```

## target属性
表示跳转窗口位置(当前窗口或者新窗口)。
target属性的取值：
- _self:表示在当前窗口打开（默认）
- _blank:新窗口打开

## title属性
全局属性：光标指向链接时显示的提示文字