# demo

*罗列了一些常用效果的 demo。*

## demo 列表

- [autoComplete](https://github.com/zhuyujia/demo/tree/master/autoComplete)
	- **名称：** 邮箱补全 + 上下翻动
	- **使用方法：** $.AutoComplete(id)
	- **参数说明：** 输入文本的 id
- [passwordStrength](https://github.com/zhuyujia/demo/tree/master/passwordStrength)
	- **名称：** 密码强度显示
	- **使用方法：** new PasswordStrength(passwordID,strengthID)
	- **参数说明：**
		- 第一个参数是密码输入框的 id
		- 第二个参数是密码强度的 id
- [setHome](https://github.com/zhuyujia/demo/tree/master/setHome)
	- **名称：** 设为首页
	- **使用方法：** setHome(this,window.location)
	- **参数说明：**
		- 第一个参数是触发事件的对象，一般为 this
		- 第二个参数是设为首页的 url 地址
- [addFavorite](https://github.com/zhuyujia/demo/tree/master/addFavorite)
	- **名称：** 收藏本站
	- **使用方法：** addFavorite(this)
	- **参数说明：**
		- 第一个参数必须，指代触发事件的对象，一般为 this
		- 第二个参数是对象，可选项。对象有两个属性 title 和 url（两个属性都是可选项）
- [flip](https://github.com/zhuyujia/demo/tree/master/flip)
	- **名称：** 基于 jquery 的翻牌效果
	- **使用方法：** $('selector').flip(opts)