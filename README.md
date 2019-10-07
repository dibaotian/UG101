# 酱瓜IOT运营版小程序用户手册
## 一. 架构说明
### 角色定义
程序的用户共有三个角色，分别是供应商，分销商（代理商）和运营商，三种角色使用同一个小程序登录，不同角色的用户登录后看到的页面和操作权限不同

![](https://github.com/dibaotian/UG/blob/master/org_arch.png)

#### 供应商
1.能够为分销商创建分组

2.能够查询加入分组的经销商的基本信息

3.能够查询配额记录

4.能够查询配额使用情况

5.能够查询分组内的设备数目和设备在线/离线/故障数目

6.能够查询分组内每个设备的基本信息

#### 分销商（代理商）
1.能够加入厂商设定的分组

2.能够查询厂商为其分配的配额

3.能够查询厂商的配额记录

4.能够为运营商设定分组

5.能够查询加入分组的运营商的基本信息

6.能够在厂商分配的配额限制下为运营商的设备分配配额

7.能够查询运营商的配额使用情况

8.能够查询分配给运营商的配额记录

10. 能够查询分组内运营商设备数目和设备在线/离线/故障数目

11.能够查询分组内运营商设备的基本信息（配方，水温，工作状态，地理位置等）

12.能够配置分组内运行商设备

#### 运营商
1.能够加入分销商设定的分组

2.能够查询分销商为其分配的配额

3.能够查询分销商为其分配配额的记录

4.能够添加/删除设备

5.能够对机器进行基本设定（水温，价格等）

6.能够对机器的基本状态进行查询（工作状态，商品库存比例，配方，水温等）

7.能够微信/支付宝收款

8.能够对机器的销售状态进行查询

## 1. 用户注册
1.用户注册时请打开微信，搜索并关注嘉申电子公众号

![](https://github.com/dibaotian/UG/blob/master/wechat_public.png)

打开公众号页面，点击获取授权

![](https://github.com/dibaotian/UG/blob/master/get_auth.png)

授权通过会显示如下页面

![](https://github.com/dibaotian/UG/blob/master/auth_pass.png)

2.扫描下方小程序二维码，或者搜索酱瓜科技IOT运营版打开小程序

![](https://github.com/dibaotian/UG/blob/master/applet_qr.png)

3.打开小程序,进入用户登录页面，点击最下方的新用户注册，进入获取授权页面

![](https://github.com/dibaotian/UG/blob/master/login_page.png)

4.在获取授权页面，点击授权注册按钮，授权注册后进入用户注册页面

![](https://github.com/dibaotian/UG/blob/master/regist_auth.png)

5.获取授权后进入注册页面，请在注册页面按照角色选取运营商或者供应商，注册信息按照要求填写，填写完成后选择确认完成注册

![](https://github.com/dibaotian/UG/blob/master/regist_page.png)

6.注册成功后页面会跳转到登录页面，此时用户可以通过授权登录或者用户名密码登录

#登录

小程序支持两种登录方式

1. 账户密码登录

用户输入注册时添加的用户名和密码，点击登录按钮进行系统登录

![](https://upload-images.jianshu.io/upload_images/11115937-498df487eda20757.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 微信授权登录

点击微信授权登录按钮，小程序会申请用户授权，授权通过后，系统自动登录

![](https://upload-images.jianshu.io/upload_images/11115937-c1059365384bffb5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)





