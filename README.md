demo
====

##autoComplete

名称：邮箱补全 + 上下翻动

用法：$.AutoComplete('#email')

##passwordStrength

名称：密码强度显示

用法：new PasswordStrength('pass','passStrength')

说明：第一个参数是密码输入框的 id，第二个参数是密码强度的 id

##setHome

名称：设为首页

用法：setHome(this,window.location);

##addFavorite

名称：收藏本站

用法：addFavorite(this);

说明：1.第一个参数必须，指代触发事件对象，一般为 this；
2.第二个参数是对象，可选项。对象有两个属性 title 和 url（两个属性都是可选项）。