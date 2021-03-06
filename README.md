#### 编写目的

为了更好理解此系统原型的功能，对系统从概要设计到详细设计进行一个说明。

#### 项目目标

在这个人工智能时代，我们对生活方式的最优化有了一个重新考量，人工智能产品方便了我们生活的方方面面，手机人脸解锁，摄像头人脸识别逃犯，或者是街边的刷脸消费已经快节奏的进入到我们的生活。为此，我们的智能门禁系统也跟随着时代的潮流上线，志在解决传统开门的不便利或者不安全，数据不可视，将门禁作为一个安全的，乐趣化的智能产品进入平常百姓的生活，让广大群众也能感受到人工智能的魅力。

#### 实体关系图

1、一个产品可能有多个组，一个组可能会在多个产品里面；

2、一个门禁上可能有多个产品，一个产品只能在一个门禁上面；

3、一个门禁上可能有多个前端设备，一个前端设备只可以在一个门禁上；

4、一个产品上可能有多个前端设备，一个前端设备只能在一个产品上；

5、一个前端设备对应一个显示设备，一个显示设备只能显示一个前端设备上的信息；

6、一个产品盒子只有一种主题，一个主题可以给多个盒子设置

![img](https://github.com/CheerQY/vdin.version2/blob/master/rn.png)

#### 系统架构图

大致可分为产品管理、分组管理、记录显示、设置管理、个人中心；

![img](https://github.com/CheerQY/vdin.version2/blob/master/total.png)

由于详细结构功能过于繁多，现在将最重要的产品部分展示一下

![img](https://github.com/CheerQY/vdin.version2/blob/master/product.png)



#### 原型地址

云平台：https://cheerqy.github.io/vdin.version2

![img](https://github.com/CheerQY/vdin.version2/blob/master/GIF.gif)
app：https://modao.cc/app/9e8681f1cb999b4be9f6c02976bcfe15711de642
![img](https://github.com/CheerQY/vdin.version2/blob/master/GIF-app.gif)
