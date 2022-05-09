# Web应用设计 #

## 用户交互 ##
**1.注册页面**：页面简约大方，没有冗余的信息，突出了关键信息；提供了信息验证，用户输入了非法信息会给出提示
![](https://github.com/nswsnb/Web_Engineering_2022/blob/default/task6/picture/Image1.png)

**2.登录页面**：登录界面美观，主题信息鲜明，在登录页面也提供了注册页面的接口，方便新用户的使用
![](https://github.com/nswsnb/Web_Engineering_2022/blob/default/task6/picture/Image2.png)

## 网页布局形式 ##
**采用T形布局**：页面顶部放置网站标题以及有关用户购物信息的导航栏，而在网页左侧放置图书分类列表，网页
主要部分用来展示主要信息，如图书具体信息、订单信息、购物车信息等。
![](https://github.com/nswsnb/Web_Engineering_2022/blob/default/task6/picture/2.1.png)

## 导航设计 ##
1.关于用户信息的导航放置在左上角，集成了用户需要的各种操作。
![](https://github.com/nswsnb/Web_Engineering_2022/blob/default/task6/picture/3.1.png)

2.关于图书的分类信息放置在左侧导航栏中，采用从上到下的架构进行分类
![](https://github.com/nswsnb/Web_Engineering_2022/blob/default/task6/picture/3.2.png)

## 信息架构 ##
**采用从上到下的架构模式**：主页作为顶层，有购物车、订单管理、用户信息管理、图书信息展示等主要操作的入口

## 功能设计 ##
**1.图书具体信息**：展示图书图片，作者、出版社、出版时间、价格等图书信息，同时支持购买操作，可以自定义需要购买的数量
![](https://github.com/nswsnb/Web_Engineering_2022/blob/default/task6/picture/5.1.png)

**2.购物车管理**：购物车中展示了加入购物车的所有图书，显示了单价以及购物车总价，支持删除、修改数量、提交 订单等操作。
![](https://github.com/nswsnb/Web_Engineering_2022/blob/default/task6/picture/5.2.png)

**3.订单管理**：订单中展示了待付款的图书支持查看订单信息、取消订单、支付等操作。
![](https://github.com/nswsnb/Web_Engineering_2022/blob/default/task6/picture/5.3.png)