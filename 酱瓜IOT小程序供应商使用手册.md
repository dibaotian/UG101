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
