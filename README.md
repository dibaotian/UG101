## 架构说明和角色定义

运营平台的管理用户共有三个角色，分别是供应商，分销商（代理商）和运营商，三种角色使用同一个小程序登录，不同角色的用户登录后看到的页面和操作权限不同

![](https://upload-images.jianshu.io/upload_images/11115937-26e670fa2735cef2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

平台可以管理很多前端设备，前端设备可以提供商品零售服务，服务的对象为客户

客户可以使用手机（微信/支付宝）扫码支付的方式购买商品，或者使用传统支付方式，然后通过设备面板上的人机接口按键来选择商品。


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

## 用户注册

1. 用户注册时请打开微信，搜索并关注嘉申电子微信公众号

![](https://upload-images.jianshu.io/upload_images/11115937-84ed728fc1cc62d0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

进入公众号，点击最下方的获取授权按钮

![](https://upload-images.jianshu.io/upload_images/11115937-8e9efdef1b82bccd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

授权通过会显示如下页面，说明授权成功，此时请关闭授权结果页面

![](https://upload-images.jianshu.io/upload_images/11115937-a012ecad23680ec9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 使用微信扫描下方小程序二维码，或者搜索酱瓜科技IOT运营版并打开小程序

![](https://upload-images.jianshu.io/upload_images/11115937-7b612b3873e7a136.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 打开小程序,进入用户登录页面，点击最下方的新用户注册，进入获取授权页面

![](https://upload-images.jianshu.io/upload_images/11115937-fb504aafb72ac39a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4. 在获取授权页面，点击授权注册按钮，授权注册后进入用户注册页面

![](https://upload-images.jianshu.io/upload_images/11115937-fe212de64d948008.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5. 获取授权后进入注册页面，请在注册页面按照角色选取运营商或者供应商，注册信息按照要求填写。

用户名请使用邮常用箱名(请在键盘英文状态下输入，中间不要有空格)

小程序管理的微信账号会自动生成不可修改

用户支付宝账号请务必正确填写（否则会导致支付宝转账到该账户失败）

填写完成后选择确认完成注册

![](https://upload-images.jianshu.io/upload_images/11115937-5344bd05eadcb027.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

6.注册成功后页面会跳转到登录页面，此时用户可以通过授权登录或者用户名密码登录

##登录

小程序支持两种登录方式，在登录页面，用户可以选择使用两种方式登录

![](https://upload-images.jianshu.io/upload_images/11115937-d53de95bd81866e9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 账户密码登录（传统登录）

用户输入注册时添加的用户名和密码，点击登录按钮进行系统登录（这种方式不受当前登录微信账户的限制）

![](https://upload-images.jianshu.io/upload_images/11115937-498df487eda20757.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 微信授权登录（快速登录）

点击微信授权登录按钮，小程序会申请用户授权，授权通过后，系统自动登录(此方式只适用于当前已登录的微信账户登录，如果当前微信用户账户没有通过公众号授权，登录将会失败）

![](https://upload-images.jianshu.io/upload_images/11115937-c1059365384bffb5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 修改密码和支付宝收款帐号

小程序允许在微信授权登录状态下修改登录密码和支付宝收款帐号

登录后请进入用户信息页面，点击修改密码或者修改支付宝账号按钮进行修改

![](https://upload-images.jianshu.io/upload_images/11115937-039d0fc9f9e9e6ad.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)





## 小程序使用

### 供应商

供应商小程序包含分组管理，设备管理，配额记录和用户信息四个页面

供应商可以有多个账户，所有供应商账户都能看到其他供应商账户所创建的分组和分组信息，并且能够管理所有分组内的设备，但是供应商不能删除其他供应商创建的分组，分组只能由创建该分组的供应商账户删除


####分组管理

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

4. 解除绑定

在分组已经绑定分销商的状态下，供应商可以对分组关联的分销商解除绑定，解除后分组内的配额会继续保留，被解除绑定的分销商将不能继续使用分组内的剩余配额

设置时选定要配额的分组，点击其对应的分组设置按钮，弹出设置菜单，选择解除绑定

![](https://upload-images.jianshu.io/upload_images/11115937-2ee24c40745bbc54.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

供应商可以在解除绑定后关联新的分销商，新绑定的分销商可以继续使用分组内原有的配额

5. 删除分组

供应商可以删除分组，这时分组的配额将不在保留，绑定的分销商也将会被取消和分组的绑定关系

设置时选定要配额的分组，点击其对应的分组设置按钮，弹出设置菜单，选择删除分组

![](https://upload-images.jianshu.io/upload_images/11115937-bd82654f6cc767b0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

6. 分组查询
分组支持按照分组名称进行搜索，搜索框位于页面上方，输入分组名称，点击搜索按钮，下方即可显示要搜索的分组

![](https://upload-images.jianshu.io/upload_images/11115937-a9fc1668a3771d3f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 设备管理

小程序登录后，点击最下面标签栏上的设备管理按钮，即可进入供应商设备管理页面

![](https://upload-images.jianshu.io/upload_images/11115937-1766f0c371bcb144.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

在设备管理页面，用户可以查询到每个设备的UUID,设备所属的分组名称，设备所属的分销商，已经设备工作状态

1. 设备参数设定 

用户可以通过点击设置按钮打开对应菜单对设备基本参数例如水量，粉量，温度等进行装订和设置的查询，

2. 地理位置查询 

用户可以通过点击设置->地理位置按钮来获取设备的位置信息，支持地图显示和任意比例缩放

![](https://upload-images.jianshu.io/upload_images/11115937-7b646946b4f97171.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 自定义设备标识 

为了方便管理，支持对用户对设备进行自定义标记命名

用户可以通过点击设置->用户信息按钮调起标记输入对话框，在对话框内输入设备的自定义标记信息

![](https://upload-images.jianshu.io/upload_images/11115937-196c5b04f7e81ab2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

标记信息设置完成后会显示在每个设备对应的设备标注字段

![](https://upload-images.jianshu.io/upload_images/11115937-ac9a1470694c0eae.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5.设备信息支持按分组名称查询

在屏幕最上方的搜索框输入分组名称，点击搜索按钮即可列出分组内所有设备

![](https://upload-images.jianshu.io/upload_images/11115937-ba07ddfcc7e9dd1f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 配额记录

小程序登录后，点击最下面标签栏上的配额记录按钮，即可进入供应商配额记录页面

![](https://upload-images.jianshu.io/upload_images/11115937-49414569341dfd05.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


配额记录页面详细记录各个分组每一次配额的变更，每条记录包括分组名称，额度变更具体数值，额度是增加或减少, 额度变更操作人，执行变更操作人的角色（黄衣小人代表分销商，绿衣小人代表供应商）

配额记录支持按分组名称查询，在屏幕上方的搜索框输入分组名称并点击搜索按钮即可按照时间顺序列出分组内所有的配额变更情况

### 用户信息

小程序登录后，点击最下面标签栏上的用户信息按钮，即可进入供应商用户信息页面

![](https://upload-images.jianshu.io/upload_images/11115937-cacaa9b530943e71.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

用户信息页面会显示用户的角色，用户账号，电话号码，注册日期等

使用微信授权登录的用户能够在该页面调出修改密码对话框修改账户登录密码

用户可以在用户信息页面退出小程序返回到登录页面


### 运营商

#### 用户登录

用户打开小程序会进入登录页面，可以选择使用两种方式登录

![](https://upload-images.jianshu.io/upload_images/11115937-d53de95bd81866e9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 传统登录，输入用户名和密码点击登录按钮登录（这种方式不受当前登录微信账户的限制，在任何移动端都可以登录）

2. 快速登录，点击微信授权登录按钮，向小程序授权获得当前微信账号的信息进行快速登录 (快速登录的用户只能是当前已登录的微信用户，如果当前微信用户账户没有通过公众号授权，登录将会失败）

用户登录后，供应商小程序包含设备管理，销售数据，设备维护和用户信息四个功能页面

#### 设备管理

运营商登录后会进入设备管理页面，设备管理页面包含设备状态，存料管理，配额管理，四个分页

![](https://upload-images.jianshu.io/upload_images/11115937-72d6a9e13deeab0d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##### 设备状态分页

在设备状态页面用户可以查看设备的统计信息和基本状态，点击设置按钮用户可以在移动端随时查询设备的工作参数并且对这些参数进行远程设置或修订

1. 统计信息显示

如上图，统计信息包括当前账户下注册的设备总数，在线数目和故障数目

2. 状态显示
显示该账户下所有注册设备状态，其中UUID是系统中设备的唯一标识号，状态显示设备的工作状态包括在线/离线，故障类型（缺水，加水超时，加热超时等等）等等，设置按钮会根据状态的不同显示不同的颜色，绿色标示正常，灰色标示离线，红色表示故障


点击每个设备的设置按钮用户可以查询该设备的工作参数并且对这些参数进行远程设置或修订，具体的工作参数如下图

![](https://upload-images.jianshu.io/upload_images/11115937-ea6306fba9e4539a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 水温设置

用户设置设备冷水和热水的范围，设备会将其热水水箱和冷水水箱的温度控制在设定范围之内

![](https://upload-images.jianshu.io/upload_images/11115937-514e690eded1d337.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4. 配方设置

用户可以设置粉料和水量的配比关系，根据售卖杯子的容量，以及当地人群的口味等灵活调节水和料的量以及配比关系，达到最佳组合

![](https://upload-images.jianshu.io/upload_images/11115937-c1dec266c696dc41.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

售卖页面设定（名称/图片/价格）

前端设备支持无人自动售卖，同时支持微信和支付宝支付，前端设备上有一个动态加密的二维码，顾客可以使用微信或者支付宝的扫一扫功能扫描该二维码，顾客扫码后会app上会显示一个售卖页面，页面上展示商品的图片,名称和价格，顾客可以根据喜好点击喜欢的商品付款购买，用户可以在小程序上自定义这个售卖页面，设定商品展示数量，价格，名称，对应图片以及价格

![](https://upload-images.jianshu.io/upload_images/11115937-0858ed00e48d273f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5. 价格设置

用户可以自主设定每一种商品的价格，顾客扫码购买时，页面会显示对应的价格，顾客付款也会按照设定的价格支付，价格设定范围在0.01-999.98元之间，精确到分，其中如果价格设定为999.99元，那么商品不会出现在售卖列表之中，当顾客扫码打开购买页面时，不会显示对应的商品

![](https://upload-images.jianshu.io/upload_images/11115937-4dd8cd04cbff94ec.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

6. 页面设置

用户可以设定售卖页面上的商品名称以及对应的展示图片，其中名称可以手工输入，图片设定可以点击图片按钮从系统的图片库中选取

![](https://upload-images.jianshu.io/upload_images/11115937-7a288b882c9c504a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

7. 设备标注

为了方便管理，支持对用户对设备进行自定义标记命名，在对话框内输入设备的自定义标记信息

![](https://upload-images.jianshu.io/upload_images/11115937-196c5b04f7e81ab2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

标记信息设置完成后会显示在每个设备对应的设备标注字段

8. 地理位置

用户可以通过点击设置->地理位置按钮来获取设备的位置信息，支持地图显示和任意比例缩放

![](https://upload-images.jianshu.io/upload_images/11115937-7b646946b4f97171.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

9. 设备清洗

前端设备支持设备自清洁功能，在小程序上点击设备清洗确认按钮，设备会启动自清洗程序，这个功能会有水排出设备，需要有人员在现场操作

10. 设备注销

当用户不再管理该设备，点击注销设备可以解除用户和设备之间的绑定关系，注销后该设备将不在显示在设备状态列表当中，用户和设备的注册管理关系完全取消，设备在注销后才可以被注册到其他账号下，请注意解除绑定后，该设备售卖的金额将不会再转账到用户帐户

8. 设备搜索

设备管理支持按照UUID进行设备搜索，搜索时用户不必输入全部15位UUID，系统支持按照任意长度尾数的匹配完成结果输出，例如用户可以输入后两位数58，系统会列出所有尾数为58的设备

![](https://upload-images.jianshu.io/upload_images/11115937-6a4f61f2278491eb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


##### 存料管理分页

前端售卖设备会自动记录当前的本机库存，设备上每种商品都会有独立的库存记录，设备每售卖一单，库存都会自动更新，用户可以在存货管理页面实时获取每个设备每种商品的的库存情况

库存信息主要包括设备的UUID，设备的用户标识，设备销售商品种类数目，每种商品的名称以及该商品的存货比例，当设备上商品的存货比例低于15%时该商品的存料指示条会显示黄色，售罄时显示灰色

![](https://upload-images.jianshu.io/upload_images/11115937-ce1c30ab85d9ad4f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 存货消息通知

当设备上某个商品的存货低于15%时，系统会向用户发送补货通知，当设备上商品的存货为0%时，系统会向用户发送售罄通知，同时在商品售卖页面显示售罄，顾客将无法购买该商品

![](https://upload-images.jianshu.io/upload_images/11115937-e647b112e276227d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 存货设置/复位

当用户收到补货通知或者售罄通知，对设备的库存进行补货，补货完成后，可以在小程序上根据补货的比例对库存进行重新设置，点击复位按钮，拉动比例条上的旋钮调整存量到合适位置点击完成即可

![](https://upload-images.jianshu.io/upload_images/11115937-a3e45f64bab04b2a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 设备搜索

存料管理支持按照UUID对设备进行搜索，搜索时用户不必输入全部15位UUID，系统支持按照任意长度尾数的匹配完成结果输出

##### 配额管理分页

用户可以通过配额方式来控制设备的使用，配额约束的是设备的使用次数，设备在完成每次售卖后会自动减少一个配额，设备配额达到0后，在得到新的配额之前处于锁定状态，用户在配额管理页面可以查询设备配额

![](https://upload-images.jianshu.io/upload_images/11115937-8bcc202a767d7135.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 设备配额

用户以点击配额管理页面的设设置按钮对设备进行配额，配额可以设定增加也可以设定减少

2. 设备搜索

同样，配额管理页面支持按照UUID对设备进行搜索，搜索时用户不必输入全部15位UUID，系统支持按照任意长度尾数的匹配完成结果输出

##### 流量额度分页

流量额度分页记录了当前设备每个月的数据流量消耗情况和数据服务到期时间

![](https://upload-images.jianshu.io/upload_images/11115937-e07604d6d2434253.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 销售数据

销售数据页面包含销售记录，退款处理，以及销售统计三个分页，用户可以在销售记录分页看到当天每笔的销售情况，退款处理页面可以看到每笔记录的详细信息和资金状态，可以对付款未发货的单据进行退款处理，销售统计分页会显示当天销售数据的统计信息

##### 销售记录分页

销售记录分页显示当天用户名下所有设备的每笔销售信息，包括设备ID,金额，交易时间和交易通道（微信或支付宝）

![](https://upload-images.jianshu.io/upload_images/11115937-7da8f99547673aa8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 销售记录按天查询

点击点击上方的日期，可以调 起日期选择栏，选定后点击搜索

![](https://upload-images.jianshu.io/upload_images/11115937-d692291336ab764a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 销售记录按支付类型查询

点击上方支付类型，可以调起选择框，选择支付类型，选定后点击搜索

![](https://upload-images.jianshu.io/upload_images/11115937-de1d73326d48ddcd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 销售记录按UUID查询
使用UUID查询时，用户不必输入全部15位UUID，系统支持按照任意长度尾数的匹配完成结果输出

![](https://upload-images.jianshu.io/upload_images/11115937-e7c13e6ed3f9afd1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

系统同时支持上述几个条件混合在一起搜索

##### 退款处理分页

退款处理页面用户可以看到每笔记录的详细信息和资金状态以及发货状态，资金状态有三种，已支付，已退款，已转账。 发货状态包括已经发货和未发货，对于已付款未发货的订单，运营商可以在这个页面对顾客进行退款

![](https://upload-images.jianshu.io/upload_images/11115937-7806097b23e58636.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

当订单处于资金已支付但是未发货状态（这种情况属于异常情况），订单上会出现退款按钮，用户可以点击退款按钮对顾客按照订单进行退款，退款会按照原先用户的支付通道原额返还给客户，请注意，退款只能在当天进行，每天晚上12：00系统会向运营商发起转账，转账后资金状态会变成已转账，这时无法向顾客退款

##### 销售统计分页

销售统计分页会显示当天的销售统计信息，包括微信/支付宝的订单笔数，收款总金额，退款订单笔数，退款总金额

![](https://upload-images.jianshu.io/upload_images/11115937-8b921d8f332eab48.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 销售统计支持按天查询
点击选择日期后的日期会调起日期选择菜单，设定日期后页面会显示当天的数据统计

![](https://upload-images.jianshu.io/upload_images/11115937-a0b85207d74791f4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 设备维护

用户可以在设备维护页面使用扫一扫功能扫描前端设备的二维码，完成设备的注册，设备基本信息获取，以及设备参数装订和设备注销等功能

![](https://upload-images.jianshu.io/upload_images/11115937-4669d3851451812f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 设备注册

当运营商新拿到设备时，需要将设备注册到账户下才能进行设置管理，运营商可以将设备开机，扫描设备上的二维码，小程序会弹出询问页面，询问是否要注册该设备，点击确认即可注册成功

2. 设备信息查询

如果是该运营商名下注册的设备，运营商扫描二维码后会显示设备的基本信息，包括用户ID，设备UUID，设备激活时间（注册时间），当前状态，售卖商品种类，信道类型，信道信号质量，销售配额等

![](https://upload-images.jianshu.io/upload_images/11115937-9fca3b11442a8f19.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 设备管理（参数查询/设置）

点击设置按钮可以进入设备的设置菜单，设置方法和设备管理页面的设置方法相同（只支持设备处与在线状态下进行设置）

![](https://upload-images.jianshu.io/upload_images/11115937-8aeaedb57528fadd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 用户信息

用户信息页面显示当前登录用户的基本信息，其中报告当前用户的角色，登录帐号，支付宝账号（用于进行支付宝转账），微信账号（用于微信转账），转账费率

运营版小程序还会包干当前运营商对应的分销商的信息，包括对应分销商账号，加入的分销商分组名称以及分销商电话，同时还有生成身份二维码功能

![](https://upload-images.jianshu.io/upload_images/11115937-ded716f753c584d3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 账号和密码修改

如果是使用微信授权登录的账户，在用户信息页面支持修改密码和修改支付宝账号

2. 快速关联分销商

运营商点击生成身份二维码按钮生成身份二维码，将二维码出示给分销商进行扫描，可以快速加入分销商的分组

3. 退出小程序

用户可以在此页面退出小程序，回到登录页面，能够更换其他用户登录

4. 快速拨打运营商电话

点击页面上的电话号码可以直接拨打电话给运营商和分销商














酱瓜科技感谢您的使用
