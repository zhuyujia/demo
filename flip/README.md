# 基于 jquery 的翻牌效果

**使用方法：** $('selector').flip(opts)

**参数说明：**

- direction：翻转方向，总共有 4 个值（tb、bt、lr、rl），默认 tb
- content：设置翻转后容器内显示的内容，可以是文本，可以是 html，甚至可以是 jquery 对象
- color：设置翻转后容器的背景色
- speed：设置翻转速度，值越小速度就越快
- onBefore：设置翻转前需要执行的内容
- onAnimation：设置翻转到一半的时候需要执行的内容
- onEnd：设置翻转完成后需要执行的内容