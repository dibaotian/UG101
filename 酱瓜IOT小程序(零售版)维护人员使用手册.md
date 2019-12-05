### 酱瓜IOT小程序(零售版)维护人员使用手册

#### 维护人员登录

维护人员登录使用维护人员专用小程序,扫描下方二维码，或者在微信搜索酱瓜IOT运维版即可打开小程序

![](https://upload-images.jianshu.io/upload_images/11115937-a4cb174190bbea5b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

用户打开小程序会进入登录页面，可以选择使用两种方式登录

![](https://upload-images.jianshu.io/upload_images/11115937-989f9dc582f2206b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 传统登录，输入用户名和密码点击登录按钮登录（这种方式不受当前登录微信账户的限制，在任何微信账号下都可以登录）

2. 快速登录，点击微信授权登录按钮，向小程序授权获得当前微信账号的信息进行快速登录 (快速登录无需用户名和密码，用户只能是当前已登录的微信用户，如果当前微信用户账户没有通过公众号授权，登录将会失败）

请注意：不同的角色（运营商和维护人员）和不同的需要使用不同的小程序，维护人员只能通过运维版小程序登录，使用运营商小程序登录时会报告如下错误，这时请切换至运维版小程序

![](https://upload-images.jianshu.io/upload_images/11115937-a8e25ac103e19f21.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

用户登录后，供应商小程序包含设备管理，和用户信息两个功能页面

#### 设备管理

维护人员登录后会进入设备管理页面，设备管理页面包含设备状态，存料管理，量个分页

![](https://upload-images.jianshu.io/upload_images/11115937-1bb15288dfe195bf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##### 设备状态分页

在设备状态页面维护人员可以查看设备的基本状态，点击设置按钮维护可以查询设备当前工作参数(水量，位置等）并且对设备进行清洗，加料复位等操作。

1. 状态显示
显示该维护账户所有被指派的维护设备信息，其中UUID是系统中设备的唯一标识号，状态显示设备的工作状态包括在线/离线，故障类型（缺水，加水超时，加热超时等等）等等，设置按钮会根据状态的不同显示不同的颜色，绿色标示正常，灰色标示离线，红色表示故障

点击每个设备对应的设置按钮用户可以查询该设备的工作参数并且对这些参数进行远程设置或修订，具体的工作参数如下图

![](https://upload-images.jianshu.io/upload_images/11115937-7829e45296507027.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 供水桶容量设置
前端设备检测设备当前用水情况，需要用户配合对设备供水筒的容量进行标定，标定值以毫升ml为单位，设定范围在100-20000ml之间，例如通常五加仑桶标准容积18.9L，可以设置为18900ml

![](https://upload-images.jianshu.io/upload_images/11115937-4759287c01291473.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 显示地理位置信息
用户可以通过点击设置->地理位置按钮来获取设备的位置信息，支持地图显示和任意比例缩放

![](https://upload-images.jianshu.io/upload_images/11115937-a24da06b56ecbf16.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4. 设备清洗

维护人员可以在小程序上点击设备清洗确认按钮，对应设备会启动自清洗程序，这个功能会有水排出设备，需要有人员在现场操作

![](https://upload-images.jianshu.io/upload_images/11115937-ffc6bc952833bfa8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5. 存货管理

前端售卖设备会自动记录当前的本机库存，设备上每种商品都会有独立的库存记录，设备每售卖一单，库存都会自动更新，管理人员可以在存货管理对话框内实时获取每个设备每种商品的的库存情况，以及设备的水存量情况

维护人员在进行补货/补水后，需要通过在小程序对库存进行重新设置，点击补货商品对应的复位按钮，拉动比例条上的旋钮调整存量到当前料盒存料对应的比例，点击完成，等待五秒左右，配置会被同步到设备

![](https://upload-images.jianshu.io/upload_images/11115937-a3e45f64bab04b2a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

同样，当用户对设备进行补水后，可以在小程序上根据比例对水存量进行重新设置，设置方法和存料相同

![](https://upload-images.jianshu.io/upload_images/11115937-f1b822ab5489d2b4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

请注意：当前水量设定对话框会显示当先供水桶的容量，请检查容量是否和当前使用的水桶一致，如果供水桶的容量发生变化，请先在供水同容量设置中进行更新

6. 取消关联

维护人员小程序设备状态列表中的设备是由运营商指派的，维护人员可以通过点击取消关联按钮，然后点击移除维护设备确认按钮，自行解除和设备的关联关系。

![](https://upload-images.jianshu.io/upload_images/11115937-37c8374a6266c771.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

注意：取消关联后，维护人员将不再能够配置管理该设备，除非设备运营商重新指派

##### 存料管理分页
存了管理分页同设备状态->存货管理对话框中显示的信息是相同的，方便维护人员对所有设备的状态监控，这个页面会显示所有维护设备的状态，维护人员可以通过上下划动屏幕的方式来检查所有其管理设备的存量状态。

##### 现场快速扫描
小程序提供了快速现场扫描维护的功能，维护人员可以通过点击页面左下角的扫描按钮，调起手机扫描功能

![](https://upload-images.jianshu.io/upload_images/11115937-5e95e6fb75486ea3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

机器前面板液晶屏上显示的二维码是售卖和维护功二码合一的，使用小程序在现场扫描机器前端液晶屏上的二维码，如果设备是被指派给当前维护人员维护的设备，维护人员扫描二维码后会显示设备的基本信息，包括用户ID，设备UUID，设备激活时间（注册时间），当前状态，售卖商品种类，信道类型，信道信号质量，销售配额等

![](https://upload-images.jianshu.io/upload_images/11115937-c209549435e8b564.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


如果设备没有指派给维护人员，系统会显示“当前用户不能管理该设备”，运营人员请联系供应商授权（授权方式请见后面用户信息页面介绍）
![](https://upload-images.jianshu.io/upload_images/11115937-ba04dbdad7e6a8c2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

点击设备信息对话框的设置按钮会调出当前设备的设置按钮，和前面设备状态分页点击设置按钮调出的对话框功能相同，维护人员可以查询该设备的工作参数并且对这些参数进行远程设置或修订

![](https://upload-images.jianshu.io/upload_images/11115937-7829e45296507027.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 用户信息

用户信息页面显示当前登录用户的基本信息，其中报告当前用户的角色，登录帐号，微信账号，和注册日期

![](https://upload-images.jianshu.io/upload_images/11115937-a2258a72a85009db.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 生成身份二维码

身份二维码是维护人员提供给设备运营商的身份标识，设备运营商会同通过扫描二维码的方式将其管理的设备指派给维护人员维护（具体关联方式请见酱瓜IOT（零售版）运营商使用手册）

运营商点击生成身份二维码按钮生成身份二维码，将二维码出示给运营商扫描即可

注意如果是使用帐号和密码方式登录，这种登录模式下用户无法生成身份二维码


2. 账号和密码修改

如果是使用微信授权登录的账户，在用户信息页面支持修改密码，点击修改密码按钮，输入老密码，新密码点击确认即可更新当前用户的密码

注意如果是使用帐号和密码方式登录，这种登录模式下用户无法修改密码


3. 退出小程序

用户可以在此页面退出小程序，回到登录页面，能够更换其他用户登录

酱瓜IOT感谢您的使用
