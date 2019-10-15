## 酱瓜IOT运营版分销商使用手册

### 分销商

分销商小程序包含分组管理，设备管理，配额记录和用户信息四个页面

分销商上游关联供应商，加入供应商分组，接受供应商配额，一个分销商只能加入一个供应商分组，下游关联运营商，创建运营商分组，向加入分组的运营商的设备发放配额，并且可以管理设置运营商名下的设备，一个分销商分组只能关联一个运营商，当分销商没有关联供应商时，其不能创建运营商分组，也不能关联运营商

#### 分组管理

分销商登录后会进入分组管理页面，在这里用户可以创建/删除/运营商分组，为每个分组关联运营商，同时查询每个运营商分组的状态

运营商状态显示运营商加入的分组名称，运营商账户，运营商联系电话，运营商名下的设备总数，运营商名下设备的在线，离线和故障个数以及分组的创建时间

![](https://upload-images.jianshu.io/upload_images/11115937-f7be709155b2dba4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 创建运营商分组

点击页面右下角绿色方框十字按钮

![](https://upload-images.jianshu.io/upload_images/11115937-3abeadf307aa6356.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

弹出创建供应商分组对话框，输入分组名称(分组名称最好不要超过6个字符)，点击提交按钮即可创建

![](https://upload-images.jianshu.io/upload_images/11115937-2239116317f1531a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

分组创建后，页面上可以获得基本的分组信息

![](https://upload-images.jianshu.io/upload_images/11115937-7971165452a433b8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 扫描绑定运营商

分组创建后，如上图显示，运营商对应的字段为未绑定状态

用户可以点击分组设置按钮调出分组设置菜单，点击扫描绑定按钮

![](https://upload-images.jianshu.io/upload_images/11115937-f5f1a36e1d5b20be.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


联系分销商，请分销商提供其身份二维码(分销商在其用户信息页面，点击生成身份二维码按钮即可生成)

扫描二维码即可完成绑定

![](https://upload-images.jianshu.io/upload_images/11115937-191b855a556f5307.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

绑定后，供应商对应字段会显示绑定供应商账号

![](https://upload-images.jianshu.io/upload_images/11115937-b7afca2558885311.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 解除绑定

在分组已经绑定运营商的状态下，分销商可以对分组关联的运营商解除绑定，解除后分组内的配额会继续保留，被解除绑定的运营商管理的机器将不在会出现在设备管理列表中，一个运营商只能加入一个分销商分组

设置时选定要配额的分组，点击其对应的分组设置按钮，弹出设置菜单，选择解除绑定

![](https://upload-images.jianshu.io/upload_images/11115937-af4f9b322081de68.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

在解除绑定后该运营商可以关联新的分销商分组，新绑定的供应商设备可以继续使用分组内原有的配额

4. 删除分组

供应商可以删除分组，这时分组的配额将不在保留，绑定的分销商也将会被取消和分组的绑定关系

设置时选定要配额的分组，点击其对应的分组设置按钮，弹出设置菜单，选择删除分组

![](https://upload-images.jianshu.io/upload_images/11115937-5fa5088416a554b7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5. 分组查询
分组支持按照分组名称进行搜索，搜索框位于页面上方，输入分组名称，点击搜索按钮，下方即可显示要搜索的分组

![](https://upload-images.jianshu.io/upload_images/11115937-a5772dead255ba49.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 设备管理

分销商可以在设备管理页面查看当前供应商分配的剩余额度，查看关联在其各个分组上的运营商账户下注册的所有设备状态以及基本信息

![](https://upload-images.jianshu.io/upload_images/11115937-0d5c3644fdaeab84.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

分销商可以对设备的工作参数进行查询和装订，分销商点击设置按钮选择，调出设备设置菜单，对配额，配方水温，设备标注信息进行设定，也可以启动设备清洗功能，查询设备所处的地理位置

![](https://upload-images.jianshu.io/upload_images/11115937-4aacd9ad94e08d93.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 配置设定

分销商小程序支持在当前分销商的额度池中，取出一定数目的配额分配到单个设备，也可以将单个设备上的额度取出放回额度池内，此功能只能在设备在线情况下使用

在设备配额菜单点击配额设定，调起配额设定对话框

![](https://upload-images.jianshu.io/upload_images/11115937-dc71633bfd9479e8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

分销商可以选择：

充值--从分销商额度池中向设备分配配额，此时充值的的数目不能大于额度池中剩余额度

减值--从设备中取出配额放回到分销商额度池中，测试减值的数目不能大于设备当前的剩余额度

设定完成后点击提交，配额会被自动在分销商额度池和设备上更新

2. 配方设置

在设备配额菜单点击配方设置，分销商可以设置设备每个商品粉料和水量的配比关系，根据售卖杯子的容量，以及当地人群的口味等灵活调节水和料的量以及配比关系，达到最佳组合

![](https://upload-images.jianshu.io/upload_images/11115937-127acf90b8dc8b4a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 水温设置

在设备配额菜单点击水温设置，会调出水温设置对话框，水温设定范围在1度到95度之间，分为冷水温度范围和热水温度范围，用户设分别设置最低温度和最高温度，设备会将其热水水箱和冷水水箱的温度控制在设定范围之内

![](https://upload-images.jianshu.io/upload_images/11115937-537c297cfc610e22.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4. 设备清洗

前端设备支持设备自清洁功能，在设备配额菜单上点击设备清洗确认按钮，设备会启动自清洗程序，这个功能启动后，设备会有水排出，需要有人员在现场操作

5. 设备标注

为了方便管理，支持对用户对设备进行自定义标记命名，在设备配额菜单点击用户信息，在对话框内输入设备的自定义标记信息，点击提交即可完成标注

![](https://upload-images.jianshu.io/upload_images/11115937-196c5b04f7e81ab2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

6. 地理位置

前端设备支持LBS定位功能，在设备配额菜单点击用户信息可以获取设备的位置信息，支持地图显示和任意比例缩放

![](https://upload-images.jianshu.io/upload_images/11115937-7b646946b4f97171.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

8. 设备搜索

设备管理支持按照UUID进行设备搜索，搜索时用户不必输入全部15位UUID，系统支持按照任意长度尾数的匹配完成结果输出，例如用户可以输入后两位数13，系统会列出所有尾数为13的设备

![](https://upload-images.jianshu.io/upload_images/11115937-731de026ba87c388.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 配额记录

小程序登录后，点击最下面标签栏上的配额记录按钮，即可进入运营商配额记录页面

![](https://upload-images.jianshu.io/upload_images/11115937-49414569341dfd05.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

配额记录页面详细记录各当前运营商闯关的各个分组每一次配额变更，每条记录包括分组名称，额度变更具体数值，额度是增加或减少, 额度变更操作人，执行变更操作人的角色（黄衣小人代表分销商，绿衣小人代表供应商），以及配额变更涉及到的设备UUID

配额记录支持按设备UUID查询，在屏幕上方的搜索框输入UUID，搜索时用户不必输入全部15位UUID，系统支持按照任意长度尾数的匹配完成结果输出即可按照时间顺序列出分组内所有的配额变更情况

### 用户信息

用户信息页面显示当前登录用户的基本信息，其中报告当前用户的角色，登录帐号，联系电话，注册日期，当前配额，配额状态（正常/锁定），

运营版小程序还会包干当前分销商对应的供应商的信息，包括对应供应商账号，加入的供应商分组名称以及供应商电话，同时还有生成身份二维码功能

![](https://upload-images.jianshu.io/upload_images/11115937-1a29da42296e7294.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

1. 账号和密码修改

如果是使用微信授权登录的账户，在用户信息页面支持修改密码

2. 快速关联供应商

分销商点击生成身份二维码按钮生成身份二维码，将二维码出示给供应商进行扫描，可以快速加入供应商的分组

3. 退出小程序

用户可以在此页面退出小程序，回到登录页面，能够更换其他用户登录

4. 快速拨打供应商电话

点击页面上的电话号码可以直接拨打电话给供应商
