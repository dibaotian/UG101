### 酱瓜IOT小程序(零售版)运营商使用手册

#### 运营商登录

运营商登录使用运营商专用小程序,扫描下方二维码，或者在微信搜索“酱瓜IOT”即可打开小程序

![](https://upload-images.jianshu.io/upload_images/11115937-6329fb3dcd767eb6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


用户打开小程序会进入登录页面，可以选择使用两种方式登录

![](https://upload-images.jianshu.io/upload_images/11115937-4e80bcfdd63713d4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

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


点击每个设备对应的设置按钮用户可以查询该设备的工作参数并且对这些参数进行远程设置或修订，具体可设置/查询的设备工作参数如下图

![](https://upload-images.jianshu.io/upload_images/11115937-7e4d08ba9f825f0a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


3. 水温设置

用户设置设备冷水和热水的范围，设备会将其热水水箱和冷水水箱的温度控制在设定范围之内

![](https://upload-images.jianshu.io/upload_images/11115937-514e690eded1d337.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4. 配方设置

用户可以设置粉料和水量的配比关系，根据售卖杯子的容量，以及设定的口味等灵活调节水和料的量以及配比关系，达到最佳组合

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

8. 数据采集 

数据采集功能打开，设备会回向后台发送设备的打杯数据，后台通过智能报表统计机器人统计当日用户名下设备的数据信息并通过邮件的方式自动将数据发送给用户，开关关闭后，设备将不再上报数据，同时统计报表机器人将不在进行统计和邮件发送工作

![](https://upload-images.jianshu.io/upload_images/11115937-7e4baba8f1df3c7d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

9. 地理位置

用户可以通过点击设置->地理位置按钮来获取设备的位置信息，支持地图显示和任意比例缩放

![](https://upload-images.jianshu.io/upload_images/11115937-7b646946b4f97171.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

10. 关联维护人

运营商可以为每个设备指定对应的设备维护人员， 由设备维护人员到达现场来完成补水，补料，检查和清洗操作。

用户点击关联维护人按钮，弹出关联维护人操作对话框

![](https://upload-images.jianshu.io/upload_images/11115937-c75a11c157d85780.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

如果在维护人员ID输入框中显示为NA或空白，则表明该设备没有指定的维护人

可以使用两种方式为当前设备指派（或者修改更新）维护人
     1） 点击绿色扫描按钮，扫描维护人员身份二维码完成关联（维护人员可以在账户小程序下，用户信息页面点击生成身份二维码扫描）
     2） 直接在维护人员ID 输入框中输入维护人员的账户ID（电子邮件地址形式）

点击提交按钮完成指派设定，设定完成后维护人员可以通过运维版小程序登录对该设备进行管理维护操作

同样，供应商可以删除维护人员ID对话框中的用户名，然后点击提交，来解除该设备对当前维护人员的授权，解除授权后，该设备将从维护人员小程序设备列表中消失，扫描该设备也将会显示没有授权

11. 设备清洗

前端设备支持设备自清洁功能，在小程序上点击设备清洗确认按钮，设备会启动自清洗程序，这个功能会有水排出设备，需要有人员在现场操作

12. 供水桶容量设置
前端设备可以检测设备当前用水情况，需要用户配合对设备供水筒的容量进行标定，标定值以毫升ml为单位，设定范围在100-20000ml之间，例如通常五加仑桶标准容积18.9L，可以设置为18900ml

![](https://upload-images.jianshu.io/upload_images/11115937-4759287c01291473.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


13. 设备注销

当用户不再管理该设备，点击注销设备可以解除用户和设备之间的绑定关系，注销后该设备将不在显示在设备状态列表当中，用户和设备的注册管理关系完全取消，设备在注销后才可以被注册到其他账号下，请注意解除绑定后，该设备售卖的金额将不会再转账到用户帐户

14. 设备搜索

设备管理支持按照UUID进行设备搜索，搜索时用户不必输入全部15位UUID，系统支持按照任意长度尾数的匹配完成结果输出，例如用户可以输入后两位数58，系统会列出所有尾数为58的设备

![](https://upload-images.jianshu.io/upload_images/11115937-6a4f61f2278491eb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


##### 存料管理分页

前端售卖设备会自动记录当前的本机库存，设备上每种商品都会有独立的库存记录，设备每售卖一单，库存都会自动更新，用户可以在存货管理页面实时获取每个设备每种商品的的库存情况

根据用户设置的设备供水桶容量，前端设备会自动计算当前设备的用水存量比例，每售卖一单，水存量会自动更新，用户可以在存货管理页面实时获取每个设备的用水存量信息

库存信息主要包括设备的UUID，设备的用户标识，设备销售商品种类数目，每种商品的名称以及该商品的存货比例，当设备上商品的存货比例低于15%时该商品的存料指示条会显示黄色，售罄时显示灰色，用水存量会显示成黄色，用尽状态为灰色

![](https://upload-images.jianshu.io/upload_images/11115937-ab686e81dab639e9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


1. 货存量和水存量消息通知

当设备上某个商品的存货低于15%时，系统会向用户发送补货通知，当设备上商品的存货为0%时，系统会向用户发送售罄通知，同时在商品售卖页面显示售罄，顾客将无法购买该商品。

当设备上当前设备水存量低于15%时，系统会想用户发送水存量第，请尽快补水通知，当设备上的水存量为0%时，系统会向用户发送水存量用尽信息

![](https://upload-images.jianshu.io/upload_images/11115937-e647b112e276227d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 货存量和水存量设置/复位

当用户收到补货通知或者售罄通知，对设备的库存进行补货，补货完成后，可以在小程序上根据补货的比例对库存进行重新设置，点击复位按钮，拉动比例条上的旋钮调整存量到合适位置，点击完成，等待五秒左右，配置会被同步到设备

![](https://upload-images.jianshu.io/upload_images/11115937-a3e45f64bab04b2a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

同样，当用户对设备进行补水后，可以在小程序上根据补冲水量的比例及对水存量进行重新设置，设置方法和存料相同

![](https://upload-images.jianshu.io/upload_images/11115937-f1b822ab5489d2b4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

需要注意，当前水量设定对话框会显示当先供水桶的容量，请检查容量是否和当前使用的水桶一致，如果供水桶的容量发生变化，请在供水同容量设置中进行更新

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

用户可以在设备管理页面使用扫一扫功能扫描前端设备的二维码，完成设备的注册，设备基本信息获取，以及设备参数装订和设备注销等功能

![](https://upload-images.jianshu.io/upload_images/11115937-133eab6832c5aa50.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 设备注册

当运营商新拿到设备时，需要将设备注册到账户下才能进行设置管理，运营商可以将设备开机，扫描设备上的二维码，小程序会弹出询问页面，询问是否要注册该设备，点击确认即可注册成功

2. 设备信息查询

如果是该运营商名下注册的设备，运营商扫描二维码后会显示设备的基本信息，包括用户ID，设备UUID，设备激活时间（注册时间），当前状态，售卖商品种类，信道类型，信道信号质量，销售配额等

![](https://upload-images.jianshu.io/upload_images/11115937-ab0c8855ebee5bc1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


3. 设备管理（参数查询/设置）

点击设置按钮可以进入设备的设置菜单，设置方法和设备管理页面的设置方法相同（只支持设备处与在线状态下进行设置）

![](https://upload-images.jianshu.io/upload_images/11115937-8aeaedb57528fadd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 用户信息

用户信息页面显示当前登录用户的基本信息，其中报告当前用户的角色，登录帐号，支付宝账号（用于进行支付宝转账），微信账号（用于微信转账），转账费率，注册日期等

![](https://upload-images.jianshu.io/upload_images/11115937-ddb13f038bfd9cc6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


1. 账号和密码修改

如果用户使用微信授权登录的账户，在用户信息页面支持修改密码

2. 修改支付宝账号

如果是使用微信授权登录的账户，在用户信息页面支持修支付宝账号

3. 退出小程序

用户可以在此页面退出小程序，回到登录页面，能够更换其他用户登录

酱瓜IOT感谢您的使用
