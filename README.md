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

## 登录

小程序支持两种登录方式

1. 账户密码登录

用户输入注册时添加的用户名和密码，点击登录按钮进行系统登录

![](https://upload-images.jianshu.io/upload_images/11115937-498df487eda20757.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 微信授权登录

点击微信授权登录按钮，小程序会申请用户授权，授权通过后，系统自动登录(此方式只适用于当前已登录的微信账户登录，如果当前微信用户账户没有通过公众号授权，登录将会失败）

![](https://upload-images.jianshu.io/upload_images/11115937-c1059365384bffb5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 修改密码和支付宝收款帐号

小程序允许在微信授权登录状态下修改登录密码和支付宝收款帐号

登录后请进入用户信息页面，点击修改密码或者修改支付宝账号按钮进行修改

![](https://upload-images.jianshu.io/upload_images/11115937-039d0fc9f9e9e6ad.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 小程序使用

### 供应商

供应商小程序包含分组管理，设备管理，配额记录和用户信息四个页面

#### 分组管理

供应商登录后会进入分组管理页面，在这里用户可以创建/删除/锁定供应商分组，为每个分组关联分销商，为每个供应商分组分配配额，同时查询每个分组的状态

供应商可以查看到每个分组内关联的分销商其所管理的设备的的总数目，以及设备的在线,离线和故障数目

![](https://upload-images.jianshu.io/upload_images/11115937-dfdc2f428eebe472.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 创建分组

点击页面右下角绿色十字按钮

![](https://upload-images.jianshu.io/upload_images/11115937-d02255dd85d25582.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

弹出创建供应商分组对话框，输入分组名称(分组名称最好不要超过6个字符)，点击提交按钮

![](https://upload-images.jianshu.io/upload_images/11115937-eb955dcda65af9ff.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

分组创建后，页面上可以获得基本的分组信息

![](https://upload-images.jianshu.io/upload_images/11115937-936b7924175cd63b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 绑定分销商

分组创建后，如上图显示，分销商对应的字段为未绑定状态

用户可以点击分组设置调出分组设置菜单，点击扫描绑定按钮

![](https://upload-images.jianshu.io/upload_images/11115937-b16eeefc743ba720.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

联系分销商，请分销商提供其身份二维码(分销商在其用户信息页面，点击生成身份二维码按钮即可生成)

扫描二维码即可完成绑定

![](https://upload-images.jianshu.io/upload_images/11115937-191b855a556f5307.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

绑定后，分销商对应字段会显示绑定分销商账号

![](https://upload-images.jianshu.io/upload_images/11115937-a95b5e023ec0c27e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 配额设置

供应商可以为其创建的每个分组配置配额,分销商可以将分配给其分组的配额分配给分销商管理的运营商设备

设置时选定要配额的分组，点击其对应的分组设置按钮，弹出设置菜单，选择配额设置

![](https://upload-images.jianshu.io/upload_images/11115937-a775d8be50484e85.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

点击配额设置后，会弹出配额输入对话框，配额可以在当前额度基础上增加，也可以减少，设置完成后点击提交即可完成分组配额设定

![](https://upload-images.jianshu.io/upload_images/11115937-4a314fb364d72c36.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

设定完成后，页面会自动更新，这时可以检查对应配额字段，查看配额是否设置成功

![](https://upload-images.jianshu.io/upload_images/11115937-c41aa00a174c3fcf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 锁定/解锁分组

供应商可以对每个配额分组进行锁定，被锁定的分组，配额会被保留，但是其对应的分销商不能使用分组内的已有配额，供应商也不能对分组的配额进行增加或者减少，供应商不能解除对分组和分销商的绑定关系

设置时选定要配额的分组，点击其对应的分组设置按钮，弹出设置菜单，选择锁定分组

![](https://upload-images.jianshu.io/upload_images/11115937-ee670c3c67296e74.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

弹出对话框，选择确认

![](https://upload-images.jianshu.io/upload_images/11115937-c49e903fd40c7722.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

设定完成后，页面会自动更新，这时可以检查对应分组当前状态字段，查看设置是否成功

![](https://upload-images.jianshu.io/upload_images/11115937-ceef6c482caaf9ad.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

在锁定状态下，供应商可以对分组进行解锁，点击解锁按钮，确认即可

![](https://upload-images.jianshu.io/upload_images/11115937-8d8bcb3ce7a63f7e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 解除绑定

在分组已经绑定分销商的状态下，供应商可以对分组关联的分销商解除绑定，解除后分组内的配额会继续保留，被解除绑定的分销商将不能继续使用分组内的剩余配额

设置时选定要配额的分组，点击其对应的分组设置按钮，弹出设置菜单，选择解除绑定

![](https://upload-images.jianshu.io/upload_images/11115937-2ee24c40745bbc54.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

供应商可以在解除绑定后关联新的分销商，新绑定的分销商可以继续使用分组内原有的配额

4. 删除分组

供应商可以删除分组，这时分组的配额将不在保留，绑定的分销商也将会被取消和分组的绑定关系

设置时选定要配额的分组，点击其对应的分组设置按钮，弹出设置菜单，选择删除分组

![](https://upload-images.jianshu.io/upload_images/11115937-bd82654f6cc767b0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4. 分组查询
分组支持按照分组名称进行搜索，搜索框位于页面上方，输入分组名称，点击搜索按钮，下方即可显示要搜索的分组

![](https://upload-images.jianshu.io/upload_images/11115937-a9fc1668a3771d3f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 设备管理

小程序登录后，点击最下面标签栏上的设备管理按钮，即可进入供应商设备管理页面

![](https://upload-images.jianshu.io/upload_images/11115937-1766f0c371bcb144.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

在设备管理页面，用户可以查询到每个设备的UUID,设备所属的分组名称，设备所属的分销商，已经设备工作状态

1.用户可以通过点击设置按钮打开对应菜单对设备基本参数例如水量，粉量，温度等进行装订和设置的查询，

2.用户可以通过点击设置->地理位置按钮来获取设备的位置信息，支持地图显示和任意比例缩放

![](https://upload-images.jianshu.io/upload_images/11115937-7b646946b4f97171.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3.为了方便管理，支持对用户对设备进行自定义标记命名

用户可以通过点击设置->用户信息按钮调起标记输入对话框，在对话框内输入设备的自定义标记信息

![](https://upload-images.jianshu.io/upload_images/11115937-196c5b04f7e81ab2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

标记信息设置完成后会显示在每个设备对应的设备标注字段

![](https://upload-images.jianshu.io/upload_images/11115937-ac9a1470694c0eae.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5.设备信息支持按分组名称查询

在屏幕最上方的搜索框输入分组名称，点击搜索按钮即可列出分组内所有设备

![](https://upload-images.jianshu.io/upload_images/11115937-ba07ddfcc7e9dd1f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 配额记录

小程序登录后，点击最下面标签栏上的配额记录按钮，即可进入供应商配额记录页面

![](https://upload-images.jianshu.io/upload_images/11115937-ba07ddfcc7e9dd1f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

配额记录页面详细记录各个分组每一次配额的变更，每条记录包括分组名称，额度变更具体数值，额度是增加或减少, 额度变更操作人，执行变更操作人的角色（黄衣小人代表分销商，绿衣小人代表供应商）

配额记录支持按分组名称查询，在屏幕上方的搜索框输入分组名称并点击搜索按钮即可按照时间顺序列出分组内所有的配额变更情况

### 用户信息

小程序登录后，点击最下面标签栏上的用户信息按钮，即可进入供应商用户信息页面

![](https://upload-images.jianshu.io/upload_images/11115937-cacaa9b530943e71.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

用户信息页面会显示用户的角色，用户账号，电话号码，注册日期等

使用微信授权登录的用户能够在该页面调出修改密码对话框修改账户登录密码

用户可以在用户信息页面退出小程序返回到登录页面


### 运营商

供应商小程序包含设备管理，销售数据，设备维护和用户信息四个功能页面

#### 设备管理

运营商登录后会进入设备管理页面，设备管理页面包含设备状态，存料管理，配额管理，四个分页

![](https://upload-images.jianshu.io/upload_images/11115937-72d6a9e13deeab0d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##### 设备状态分页

用户可以看设备的统计信息，包括设备总数，在线数目和故障数目

用户可以看到账户下所有注册设备状态

UUID为整个系统中设备的唯一标识号，状态显示设备的工作状态，是否离线，是否故障类型等等，设置按钮会根据状态的不同显示不同的颜色，绿色标示正常，灰色标示离线，红色表示故障

点击设置按钮用户可以在移动端随时查询设备的工作参数并且对这些参数进行远程设置或修订

![](https://upload-images.jianshu.io/upload_images/11115937-ea6306fba9e4539a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


具体的工作参数包括水温，用户设置设备冷水和热水的范围，设备会将其热水水箱和冷水水箱的温度控制在设定范围之内

![](https://upload-images.jianshu.io/upload_images/11115937-514e690eded1d337.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

配方设置，用户可以设置粉料和水量的配比关系，根据售卖杯子的容量，以及当地人群的口味等灵活调节水和料的量以及配比关系，达到最佳组合

![](https://upload-images.jianshu.io/upload_images/11115937-c1dec266c696dc41.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

售卖页面设定（名称/图片/价格）

前端设备支持无人自动售卖，同时支持微信和支付宝支付，前端设备上有一个动态加密的二维码，顾客可以使用微信或者支付宝的扫一扫功能扫描该二维码，顾客扫码后会app上会显示一个售卖页面，页面上展示商品的图片,名称和价格，顾客可以根据喜好点击喜欢的商品付款购买，用户可以在小程序上自定义这个售卖页面，设定商品展示数量，价格，名称，对应图片以及价格

![](https://upload-images.jianshu.io/upload_images/11115937-0858ed00e48d273f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

价格设置，用户可以自主设定每一种商品的价格，顾客扫码购买时，页面会显示对应的价格，顾客付款也会按照设定的价格支付，价格设定范围在0.01-999.98元之间，精确到分，其中如果价格设定为999.99元，那么商品不会出现在售卖列表之中，当顾客扫码打开购买页面时，不会显示对应的商品

![](https://upload-images.jianshu.io/upload_images/11115937-4dd8cd04cbff94ec.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

页面设置，用户可以设定售卖页面上的商品名称以及对应的展示图片，其中名称可以手工输入，图片设定可以点击图片按钮从系统的图片库中选取

![](https://upload-images.jianshu.io/upload_images/11115937-7a288b882c9c504a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

设备标注

为了方便管理，支持对用户对设备进行自定义标记命名，在对话框内输入设备的自定义标记信息

![](https://upload-images.jianshu.io/upload_images/11115937-196c5b04f7e81ab2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

标记信息设置完成后会显示在每个设备对应的设备标注字段

设备清洗

支持设备自清洁功能，点击设备清洗确认按钮，设备会启动自清洗程序，这个功能会有水排出设备，需要有人员在现场操作

设备注销

当用户不再管理该设备，点积注销设备可以解除用户和设备之间的绑定关系，注销后该设备将不在显示在设备状态列表当中，用户和设备的注册管理关系完全取消，设备在注销后才可以被注册到其他账号下


酱瓜科技感谢您的使用

