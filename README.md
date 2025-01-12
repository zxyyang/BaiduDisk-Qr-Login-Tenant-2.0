# 火星--百度网盘扫码登录系统
### 百度网盘扫码登录系统，远程扫码，多租户版本，在线修改密码，在线提下线设备，自动接码，自动过验证，自动更新Cookie.....
*关键词：* 百度网盘扫码登录系统，远程登录系统，共享账号系统，多租户
#
#
### 演示网站：
> 🌐地址（国内）：https://bd1.zxyang.cn/login
### 管理员帐号 admin 密码 admin123 （方便他人操作，请不要随便删除）

#### 支持租用、私有部署、源码、定开

#### 服务器推荐：https://www.007idc.cn/aff/GVGFOKTS



### 功能过多，无法一一介绍，文档更新也不及时，时刻在更新迭代，


 联系作者：fifteenyang@qq.com（备注百度网盘扫码2.0）
 
<img width="200" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/36e9abe7-0f3f-4bb4-b9af-693529bd5d59">



# 更新日志
## 2025-01-12
1. 所有选择框支持快速搜索，优化联动
   <img width="748" alt="image" src="https://github.com/user-attachments/assets/79fb186a-e2e2-45da-937c-08eff90ea00c" />

   <img width="779" alt="image" src="https://github.com/user-attachments/assets/b1375984-3d70-44dd-806b-eb90f63365ce" />
2. 修改展示昵称为账号（避免有的账号没有昵称不好查询）
 <img width="1324" alt="image" src="https://github.com/user-attachments/assets/7f4a666e-de64-40cf-aaf9-7c10c15197e0" />
   

   


## 2025-01-08
1. 更新导出自动格式
   <img width="953" alt="image" src="https://github.com/user-attachments/assets/3b493a9e-0290-4685-98f7-8c4454f5d4c6" />
2. 更新批量充值+自动切换二维码充值
<img width="599" alt="image" src="https://github.com/user-attachments/assets/f2934264-1e34-49ab-8753-d5570c7ca52b" />
<img width="895" alt="image" src="https://github.com/user-attachments/assets/eab4ebfb-70d6-44b4-aa3e-62e683636561" />
3. 其他定制功能更新


## 2025-01-02
1. 升级网盘会员充值接口
2. 升级代理缓存功能
3. 添加卡密类型（平均分配，不验证模式）主要是为了非网盘业务使用，生成的卡密里面平均分配账号，并且不限制登录是否为网盘会员等，只要ck在线即可，但是依然受在线设备数量限制。
4. 平均分配规则（按照绑定卡密数量最少开始一个一个分配，如果生成卡密没有绑定账号，就从分组最少的5个中随机选择一个）
<img width="1103" alt="image" src="https://github.com/user-attachments/assets/6edab1d8-80ec-4aa9-879b-cbc2d6aeef5d" />
<img width="1063" alt="image" src="https://github.com/user-attachments/assets/4c342838-1c92-4f3e-bbf7-aa13f6b5c9e6" />



## 2024-12-29
UI升级，正式命名
<img width="1680" alt="image" src="https://github.com/user-attachments/assets/5a84d3b2-9aaa-46ed-8dbf-6a86fa19e878" />
<img width="1675" alt="image" src="https://github.com/user-attachments/assets/019bd195-baad-496e-b4f0-755c9a013d56" />


## 2024-12-27
1. 同步百度更新，刷新cookie功能更新
2. 升级全部接口cookie参数获取
3. 调整性能优化
4. 纯时间套餐没有使用次数会报错问题修复
5. 扫码代理ip缓存，同时请求扫码人数非常多情况下代理ip无法处理问题（优化自动处理策略，并发不高情况下使用缓存代理策略，并发高情况下最多等待5秒处理时间，超时则自动获取新代理，保证扫码超时问题）


## 2024-12-20
1. 导入账号txt文件
2. 导入账号数量放开
3. 支持outlook邮箱
4. 自动解除封控
5. 数据库性能优化调整
6. 并发调整优化
7. 查询数据库数据缓存（大部分功能不受影响，缓存最多20秒）
8. 代理缓存（扫码登录功能代理多次使用，20内最多使用4次）


## 2024-12-11
1. 强制登录自动过登录限制
   <img width="923" alt="image" src="https://github.com/user-attachments/assets/8fb5773b-b6aa-42e3-b0ea-f32642d29393">

2. 限制百度网盘扫码登录（开启则只能百度网盘二维码扫描登录）
3. 更新卡密限制ip/城市 （开启，限制一个卡密只能登录同一个二维码城市，或者同一个ip使用，建议只开城市，或者同时开启，城市限制的二维码的位置，ip是打开扫描的）
   <img width="346" alt="image" src="https://github.com/user-attachments/assets/fa2dcf69-f8fe-4d98-ae04-52469e0b3c83">
4. 添加批量过风控
   <img width="1097" alt="image" src="https://github.com/user-attachments/assets/e33ed165-c6c4-4c4d-9526-f0e40ac68ad6">

5. 导入账号限制取消
6. 卡密生成限制取消
7. 提高并发最高到20
8. 批量修改账号状态或者账号分组
   <img width="615" alt="image" src="https://github.com/user-attachments/assets/7cb40b61-5027-4114-bafc-66db626194d3">
<img width="812" alt="image" src="https://github.com/user-attachments/assets/c68db39a-588a-4861-abe9-f50c95d1d449">

9. 批量修改卡密功能
    <img width="995" alt="image" src="https://github.com/user-attachments/assets/cb393ab2-cac9-43ab-a943-93cb58c2bff2">

10. 下载导出功能修复，修复下载少一个的问题和excle下载报错
10. 优化已知的一些bug
11. 启动优化
12. 提高扫码登录账号验证数量10->20


## 更新时间 2024-11-23
1. 修改密码更新
2. 邮箱更新
3. 百度更新踢设备限制

## 更新时间 2024-11-21
1. 优化一大波 分配算法，提升5倍的速度 压缩分配算法精准度 并且速度压缩到1秒左右
2. 调整服务器性能配置
3. 添加大量操作的资源占用问题
4. 代理IP第一次获取的不可用则自动取第二次（可能会增加请求的时间，但是保证可用性）

## 更新时间 2024-11-20
1. 修复优化分配时候强制判断设备在线数量，超过则换号
2. 修改分配算的账号（每次最多检测15个号，10个没有使用或者使用最少，5个随机号）

## 更新时间 2024-11-18
1. 强制获取拖拽二维码的登录地址
2. 记录日志优化
3. 登录限制只能登录百度网盘二维码（其他百度产品类型不支持）
4. 优化提示代理报错

## 更新时间： 2024-11-15
1. 后台管理员添加清空租户所有信息功能
2. 后台管理员添加 自动设置账号刷新任务功能
3. 后台管理员添加 查询租户账号数量和卡密数量功能
<img width="1502" alt="image" src="https://github.com/user-attachments/assets/30cdf3f9-441e-4907-b57a-889f0ecf77b2">
4. 重写使用日志页面，添加更多信息，支持搜索
<img width="1699" alt="image" src="https://github.com/user-attachments/assets/e06acc0d-b28d-44f6-89fc-65ef6ec48a79">
5. 重写换号逻辑也走最少原则


## 更新时间：2024-11-11
1. 批量强制登录功能
  <img width="863" alt="image" src="https://github.com/user-attachments/assets/583f1879-3ad3-49b1-b019-8aad5230823d">
3. 代理去掉重复使用
3.扫码标题修改
4.代理出错不使用本机IP直接报错 
5.修改一次导入账号上线避免超时
6.继续优化分配算法，添加扫码登录时候实时查询账号的cookie是否可用+会员和封号情况，保证账号可用，不可用分组内换账号，持续保证账号的可用量，没有分配查找可用只找最新导入的3个检测，都不可用就失败（避免账号过多一直寻找消耗性能，接口超时），如果使用过（查询使用频率最低的账号的前三检测是否可用，如果不可用就结束本次）（解决账号突然cookie出问题 定时刷新刷新不到，但是扫码可能时间会多一点）刷新页面后 之前检测过不可用的账号不再重复检测
7.重写账号分配算法
8.解决几个前端显示问题
9.添加后台设置补充设置分配账号的登录设备限制
<img width="1123" alt="image" src="https://github.com/user-attachments/assets/15492814-6123-45c8-982d-44352072d842">
10.系统设置，租户添加套餐标识，去广告设置，添加了账号数量限制，卡密限制
   <img width="1408" alt="image" src="https://github.com/user-attachments/assets/a9a0ddf5-65cc-42d8-bad6-40853cfc0701">



##更新时间 2024-11-1
1. 封号状态检测
2. 封号后不在分配账号
   <img width="1475" alt="image" src="https://github.com/user-attachments/assets/1c830652-effe-40d2-8cb0-f2020b7bedf9">
3. 封号结束后自动解除（定时任务，可能存在延迟）
4. 更新账号自动会更新封号情况
5. 检测风控状态，风控不分配，解除恢复（显示风控状态，是否已经验证，预计解除时间）
   <img width="515" alt="image" src="https://github.com/user-attachments/assets/f0943076-a123-4c1e-8d3d-8c9946197b73">
6. 添加手机改密码接口（基本百分百改成功）
   <img width="480" alt="image" src="https://github.com/user-attachments/assets/dc3e0c28-e7ae-4232-bd4c-18eaec5ba485">
   <img width="864" alt="image" src="https://github.com/user-attachments/assets/31773d90-82a9-45c1-b346-b5830e1c7206">
7. 界面优化功能
    <img width="1713" alt="image" src="https://github.com/user-attachments/assets/e9df33c8-2ff2-474e-ad3c-ffe69e877c9d">
8. 强制登录 更新cookie权限
9. 自动更新Cookie 升级
10. 更新账号状态，正常-正常使用正常分配 不启用不分配（非会员或者有封号，风控情况，不参与分配）异常（cookie有问题）

##更新时间 2024-10-29
1. 掉线强制登录功能
<img width="1493" alt="image" src="https://github.com/user-attachments/assets/e3d8af3c-842c-4305-a474-a74eb87b6f83">

2. 优化自动代理访问问题
3. 修复代理扫描任务
4. 添加系统版本号
<img width="735" alt="image" src="https://github.com/user-attachments/assets/f19c8e74-482d-4f00-9291-28b3a7309fbf">

5. 删除网盘文件，目前是清空文件
<img width="1044" alt="image" src="https://github.com/user-attachments/assets/86907aa8-72d8-4d8f-b6ba-45e647efe4ce">

6. 更新读取邮件功能（提高识别准确率，邮箱商问题没有办法）

7. 添加账号显示绑定卡密数量
<img width="699" alt="image" src="https://github.com/user-attachments/assets/77daab05-653a-4dbc-bf10-d5d293b22ebe">

8. 优化提设备，获取信息，更新等接口
9. 自动识别登录有效设备，超过8个不在分配，防止风控
10. 其他功能优化，接口优化等。。。。




##更新时间 2024-10-24
1. 代理功能更新添加自动获取api方式，分割符用空格或者换行 ，
<img width="545" alt="image" src="https://github.com/user-attachments/assets/647794cf-d141-4482-890d-f1f06448ccbf">
2. 添加了测试ip是否可用功能
<img width="1452" alt="image" src="https://github.com/user-attachments/assets/86006a8c-11fd-4ee2-b258-54c0d78f122f">
3. ip添加了多次重试和轮换策略，优先使用api提取 提取三次如果都失败就单ip随机获取，所以尽量不要配置太多不可用的ip 忽然会卡




## 更新时间 2024-10-16
1. 添加扫码入库账号 （可以入库同行链接）
2. 添加手机验证码入库账号
 <img width="604" alt="image" src="https://github.com/user-attachments/assets/4318fb37-da2c-476e-b571-f880bc7777fd">

   <img width="1004" alt="image" src="https://github.com/user-attachments/assets/ab3c1dc0-436a-4f86-87cb-0f65c7ab479b">

4. 优化自动踢下线功能，分组添加控制时间 同一个时间段内不重复踢设备
5. 所有发送验证码添加代理ip，防止频繁操作
6. 添加新模版
7. <img width="757" alt="image" src="https://github.com/user-attachments/assets/f8bf162a-d270-4433-87c3-0f085e0d8666">
<img width="379" alt="image" src="https://github.com/user-attachments/assets/562478e8-90ab-4b0d-a2b9-1f63272d5868">



## 更新时间2024-10-11
1. ⚠️扫码界面添加自动过风控（解决下图问题）取消接码（史诗级更新防止别人改密码，开关分组配置可控，限制5分钟1个ip只能点一次）
   ![image](https://github.com/user-attachments/assets/b5ca4186-ecce-442b-bf09-819c95ef989c)

   <img width="751" alt="image" src="https://github.com/user-attachments/assets/e59769d2-737f-4c3e-b45b-3ab4e5560796">
2. 账号位置添加自动过风控验证
   <img width="285" alt="image" src="https://github.com/user-attachments/assets/3046dcd0-ed93-4c19-a5ef-4d0a6697f65f">
3. 扫码界面自动过风控验证
   
4. 账号位置添加获取邮箱验证码功能
   <img width="1130" alt="image" src="https://github.com/user-attachments/assets/a041b35e-fb9a-475e-bc05-0ea742bd8a3a">
5. 自动生成卡密 成功后返回一个列表 打开可以复制弹窗
   <img width="928" alt="image" src="https://github.com/user-attachments/assets/f72738e1-9a74-460d-9699-c4253855f2f7">
6. 优化套餐填写的校验
7. 拖拽二维码登录
8. 添加新扫码模版
    <img width="629" alt="image" src="https://github.com/user-attachments/assets/24a4a42b-a24d-4520-b58d-435602cf51a2">
    ![image](https://github.com/user-attachments/assets/7841933c-3d87-43df-9e92-a24ab7de3c67)
    ![image](https://github.com/user-attachments/assets/0c72b3ca-7b92-40aa-8637-94fdcf475651)
9. 其余优化，和前端 调整


##更新时间 2024-10-16
1. 添加扫码入库账号 （可以入库同行链接）
   <img width="539" alt="image" src="https://github.com/user-attachments/assets/e09795e2-e41c-4070-aa3a-5df7a83731b1">

2. 添加手机验证码入库账号
   <img width="528" alt="image" src="https://github.com/user-attachments/assets/edba9302-a41a-4a21-b554-35db201a8752">

3. 优化自动踢下线功能，分组添加控制时间 同一个时间段内不重复踢设备

##更新时间： 2024-10-06
1. 修复系统操作下载问题
2. 优化UI显示简洁
3. 修复租户管理等部分前端分页失效

## 更新时间 2024-10-05
1. 账号管理界面优化
2.更新百度刷新cookie接口，解决刷新账号掉线问题

## 更新时间 2024-10-05
1. 自动踢设备功能
2. 优化卡密过期规则（使用时计算+定时推算）
3. 添加踢设备排队记录（自动踢设备记录）
4. 添加导出简单卡密功能
5.修复导出文件错误问题
6.其余算法和功能简单优化
<img width="1674" alt="image" src="https://github.com/user-attachments/assets/8a5f014d-d668-42ef-a6fa-d52bcdfafb0a">


## 更新时间 2024-09-30
1. 卡密有过期的自动提出卡密有效期间登录的设备
2. 添加踢出记录页面
   ![image](https://github.com/user-attachments/assets/fdc43340-8bf5-49ce-9803-3cf1af9e3c6f)

4. 到期仍然显示过期提示
5. 卡密到期立马失效卡密
6. 修复卡密状态问题bug
7. 定时扫描过期卡密
![image](https://github.com/user-attachments/assets/f56d5447-511f-4cc6-bd2c-26eab2a9bd95)

## 更新时间 2024-9-27
1. 导入账号，更新账号，获取设备，自动上报设备COOKIE
2. 强制修改本地设备信息，防设备被踢
3. 添加COOKIE识别本设备
4. 算法添加自动上报解锁🔓，自动重试上报设备ID，邮箱验证算法检测
   <img width="1382" alt="image" src="https://github.com/user-attachments/assets/48c21693-1004-4519-b801-1226bf7fe5e0">

## 更新时间 2024-9-23
>1. 设备管理（自动获取设备管理需要的COOkie）
   <img width="1473" alt="image" src="https://github.com/user-attachments/assets/e1e84220-86e2-4c1a-aa5d-8a6ce6765b61">

>2在线提下线（自动过验证，自动更新Cookie）
   <img width="1372" alt="image" src="https://github.com/user-attachments/assets/4b5cea85-dca0-4577-8f88-ea8c8e125806">
   <img width="1373" alt="image" src="https://github.com/user-attachments/assets/28c1a113-6d43-4ff2-b050-544573ec6c19">

>3.新增，导入，更新，定时更新COOKIE
   <img width="1516" alt="image" src="https://github.com/user-attachments/assets/257c3247-3790-4f65-bdfc-afabe2016724">

## 更新时间 2024-9-19
1. 快捷导入账号（多模式）
<img width="1381" alt="image" src="https://github.com/user-attachments/assets/720fa10e-8bff-4727-9048-166825fe6d0f">
<img width="841" alt="image" src="https://github.com/user-attachments/assets/55d3ef1c-77d1-4e8c-be81-5559e73f6b78">

2. 快速导出 复制账号，导出txt
   <img width="1431" alt="image" src="https://github.com/user-attachments/assets/0cac26a8-dbfc-4a94-8ad4-bc81499e3f27">
  
3. 在线手动修改密码
   <img width="1473" alt="image" src="https://github.com/user-attachments/assets/c81e9501-2a86-41fb-b4e5-b1373e36b125">
   <img width="542" alt="image" src="https://github.com/user-attachments/assets/06ef6229-ba55-4b9e-9815-f892e9418c7a">
   <img width="593" alt="image" src="https://github.com/user-attachments/assets/cb6cba4b-1b00-4933-9247-2dd69418edd9">


4.  在线自动修改密码（需要邮箱接码）
   <img width="548" alt="image" src="https://github.com/user-attachments/assets/ef98b26d-1823-4fd9-9413-eee269e34ac0">

5. 全自动批量修改密码（需要邮箱接码）
    <img width="886" alt="image" src="https://github.com/user-attachments/assets/76b61f0d-b87e-49d7-935a-8b999b667c06">
<img width="882" alt="image" src="https://github.com/user-attachments/assets/f60ccb73-2b42-4d77-b7a1-da68ca5ea742">

6. 配置代理（修改密码ip上限）
    配合修改密码限制账号数量使用！
     <img width="1710" alt="image" src="https://github.com/user-attachments/assets/1da3e374-1f96-4aaf-830a-1e0d8b51069b">
7. 清理无效卡密
 <img width="1521" alt="image" src="https://github.com/user-attachments/assets/97caf19e-7214-4985-a9e5-6b4aa461ff47">

     

## 更新时间2024-0827
1. 性能优化，提升访问速度
## 更新时间2024-0802
   1. 添加在线充值新用户会员活动（支持购买月卡/购买季卡）（⚠️注意：百度直接授权活动价格可能会变动） 同步更新租户使用一次扣一积分
      ![image](https://github.com/user-attachments/assets/ef364b4c-e136-4df6-a0e7-30ab370ef16c)
      <img width="894" alt="image" src="https://github.com/user-attachments/assets/14bbf018-eabc-4a0a-b848-53fe5904be66">
      <img width="910" alt="image" src="https://github.com/user-attachments/assets/9f8e1aeb-3412-4d18-934e-3ef155a12695">

   3. 升级更新用户信息（以前的接口存在5分钟延迟），现在秒更新用户会员状态（过期时间可能仍然有几分钟延迟）
      <img width="331" alt="image" src="https://github.com/user-attachments/assets/c3302fad-5152-4539-b597-9e3df73d3657">

   4. 添加单个账号更新状态
         <img width="606" alt="image" src="https://github.com/user-attachments/assets/0bf6e1c0-9ee1-459c-a6cd-031e7430c33c">
   5. 升级分配账号算法
   6. 支持账号分组配置-是否运行用户可自助接码功能，如果关闭则对应分组的账号卡密没有接码按钮
      <img width="949" alt="image" src="https://github.com/user-attachments/assets/3626d70a-f51d-4fab-a6e8-f19fac65e502">
      <img width="816" alt="image" src="https://github.com/user-attachments/assets/7bf66c46-f0ba-48f2-bb49-8987f5595fc0">
      <img width="775" alt="image" src="https://github.com/user-attachments/assets/a1c2b1c0-ad43-4185-b0a0-94a26f0075b9">




## 更新时间2024-7-25
   1. 账号和卡密按照最新排序
   2. 更新账号更新（提示登录无效就是cookie信息不全建议拿个全一点的ck）
   3. ### 升级扫码登录，解决市面上账号有的cookie无法登录问题，或登录要验证问题，强制登录策略
## 更新时间2024-7-19
   1. 更新自动保持登录，解决掉线问题，测试一周无掉线账号
## 更新时间 2024-07-09
## 更新自动更新账号状态，自动更新账号的COOKIE（解决现在百度升级不断掉线问题）
   1. 需要注意这个更新是按照租户来的，需要给多个租户就要配置多个记录
   2. 参数：主的租户ID是：00000000，设置： disk.updateAccount('00000000')
   3. 这个比较消耗性能 且账号多的话是一个个更新比较慢，建议不要频率太高
   4. <img width="851" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/21d2ee48-4322-4082-86ee-10eb92ee9ae5">
   5. 表达柿 表示的就是，多久执行一次，自行百度或者用界面设置：
   6. <img width="858" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/6145d09c-3d78-439d-8d1a-a7dfee698e9c">


   5. <img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/4c4e588d-9ee7-47e3-8227-f285b88501fe">
   
## 更新时间 2024-07-02
   1. 添加自动吧账号分到某个分组（主要处理快过期的账号，可以自动把他们放到某个分组方便特殊处理或者，免费分享，吸引流量）
   2. 参数是（多少小时算临期，临期分到哪个分组）例如：disk.checkAcc2GroupId(24,116) 代表：会员过期少于24小时的自动放到116这个分组ID的分组下
   3. <img width="873" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/1b358467-0352-4422-9fe0-c2d8b85b897c">


## 更新时间 2024-06-29
 1. 添加验证码时间避免时间不匹配
    <img width="939" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/72eaa321-cb57-427d-b0c3-66fc330f8c53">

## 更新时间：2024-06-28
   1. 添加新功能，邮箱验证获取
   2. 解决上号需要验证码验证风控问题
   3. 限制单ip只能5秒获取1次
   4. 安全问题，邮箱验证吗去除修改密码等安全性验证吗
   5. 支持市面常用邮箱21+outlook （额外支持几乎所有邮箱类型）
   6. 优化cookie的校验修正规则
      <img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/20bb7e5b-ad82-492b-b64c-b53c12b1dfbe">

   支持的邮箱列表：
   | 邮箱服务   | 中文名字         | 邮箱地址       |
|------------|------------------|----------------|
| GMAIL      | 谷歌邮箱         | `gmail.com`    |
| OUTLOOK    | 微软邮箱         | `outlook.com`  |
| YAHOO      | 雅虎邮箱         | `yahoo.com`    |
| ICLOUD     | 苹果邮箱         | `icloud.com`   |
| QQ         | QQ邮箱           | `qq.com`       |
| 163        | 网易163邮箱      | `163.com`      |
| HOTMAIL    | Hotmail邮箱      | `hotmail.com`  |
| AOL        | AOL邮箱          | `aol.com`      |
| YANDEX     | Yandex邮箱       | `yandex.com`   |
| ZOHO       | Zoho邮箱         | `zoho.com`     |
| GMX        | GMX邮箱          | `gmx.com`      |
| MAIL.COM   | Mail.com邮箱     | `mail.com`     |
| PROTONMAIL | ProtonMail邮箱   | `protonmail.com`|
| TUTANOTA   | Tutanota邮箱     | `tutanota.com` |
| FASTMAIL   | FastMail邮箱     | `fastmail.com` |
| SINA       | 新浪邮箱         | `sina.com`     |
| 126        | 网易126邮箱      | `126.com`      |
| REDIFFMAIL | Rediffmail邮箱   | `rediffmail.com`|
| LYCOS      | Lycos邮箱        | `lycos.com`    |
| HUSHMAIL   | Hushmail邮箱     | `hushmail.com` |
| RUNBOX     | Runbox邮箱       | `runbox.com`   |
| BLUEMAIL   | BlueMail邮箱     | `bluemail.com` |
| ZIMBRA     | Zimbra邮箱       | `zimbra.com`   |
| MAIL.RU    | Mail.ru邮箱      | `mail.ru`      |
| INBOX      | Inbox邮箱        | `inbox.com`    |
| LAVABIT    | Lavabit邮箱      | `lavabit.com`  |
| POSTEO     | Posteo邮箱       | `posteo.de`    |
| KOLAB NOW  | Kolab Now邮箱    | `kolabnow.com` |
| STARTMAIL  | StartMail邮箱    | `startmail.com`|
| DISROOT    | Disroot邮箱      | `disroot.org`  |
| OPENMAILBOX| OpenMailbox邮箱  | `openmailbox.org`|
| VFEMAIL    | VFEmail邮箱      | `vfemail.net`  |
| COUNTERMAIL| CounterMail邮箱  | `countermail.com`|
| MAILFENCE  | Mailfence邮箱    | `mailfence.com`|
| LUXSCI     | LuxSci邮箱       | `luxsci.com`   |
| RISEUP     | Riseup邮箱       | `riseup.net`   |
| NEOMAILBOX | Neomailbox邮箱   | `neomailbox.com`|
| THEXYZ     | Thexyz邮箱       | `thexyz.com`   |
| MIGADU     | Migadu邮箱       | `migadu.com`   |
| POLARISMAIL| Polarismail邮箱  | `polarismail.com`|
| ALIYUN     | 阿里云邮箱       | `aliyun.com`   |
| 21CN       | 21CN邮箱         | `21cn.com`     |


## 更新时间： 2024-6-20 
   1. 更新风控规则，强行过风控算法，防止频繁

## 特色功能
## 1. 多模版支持（可后台设置多套扫码模版）
<img width="1038" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/1968af43-9713-4b7f-ae2f-9e6b60e2281f">
<img width="1039" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/03becdbb-16af-4640-8689-7aa58ecd7405">
## 2.自助换号功能（发布的卡密可以设置可以换号的次数，账号出问题用户可以自助换号）新加地址上传扫码，更快更便捷
<img width="985" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/b5221710-e39f-40b5-8da0-ce52cf0383d0">

## 广告位（可以提供给商户自己合作推广）支持图片，链接，跳转等
<img width="997" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/d8885ddb-8116-4077-9ea3-8d4cf205bee2">

## 多状态管理（账号不足、卡密过期、将单独提示，并且有位置可以设置公告，方便用户通过过期的页面进来快速去购买）
<img width="1713" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/ca5b7f45-8702-4a61-b050-8708be5a1c8a">
<img width="1712" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/4776db4d-d7ce-415d-9eff-99b6dba3ed81">

## 多租户（可以出租本系统，按照生成卡密或者时间进行收费，所有数据全部隔离，相当于别人可以找你不用部署直接购买使用你的系统，但是互相不影响，并且有独立的域名等，每张卡密都可以抽成）
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/879490f8-b5b2-4551-a57d-41176b512303">
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/9a23bbb9-785d-46cc-b168-5983f5db91c1">

## 租户积分卡充值 自助核销（卡密的形式购买续费，核销）
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/1565f48a-066f-48c9-9acd-c6be91453d02">
<img width="1477" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/5b711acd-4756-4fed-8c9b-18ab27c48080">

## 算法和自动话部分 
1. 批量导入导出 对接发卡网 （实现所有操作批量话，账号管理一体，自动入分组、生成分组、拉取信息）
2. 自动换号，自动获取账号会员情况 （卡密绑定账号分组，启用时按照算法分配账号，如果账号出问题，自动换可用的账号，保障分组内所有账号不会有账号有的用的多有的用的少）
3. 自动检测账号是否异常 （自动从百度获取账号信息，检测cookie是否有问题，检测账号会员情况、获取账号信息，方便管理）
4. 自动平均化分配账号 （分配账号按照算法，保证账号都是被平均使用）
5. 记录追踪 （所有操作、使用情况记录）
6. 临期账号自动引流池功能（设置一时间，距离这个时间到期的账号，进入到某一个分组，这个分组的卡密可以作为引流使用，最大化利用快过期账号，并且账号会自动分配，一张卡密多个账号随便切换）
   <img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/13b40bfa-d698-44fa-807d-ab5e86411b29">



### 主要特性：
- **完全响应式布局**: 支持电脑、平板、手机等所有主流设备。
- **多套扫码模板**: 支持多种扫码模板，可根据不同需求进行后台设置。
- **自助换号功能**: 用户遇到账号问题时，可以自行更换账号，支持限定换号次数。
- **广告位配置**: 可设定广告位，支持图片、链接等多种形式，便于商业推广。
- **多状态管理**: 系统会对账号短缺或卡密过期进行提示，并允许设置相关公告，增强用户体验。
- **多租户运营**: 支持多租户使用，各租户数据隔离，拥有独立的域名和管理界面。

### 核心业务功能：
- **积分卡充值与自助核销**: 租户可通过购买积分卡来续费及管理账户。
- **账号与卡密管理**: 具备账号的批量导入导出、分组管理以及卡密的生成和维护。

### 技术特点：
- **强大的一键生成功能**: 包括控制器、模型、视图、菜单等，提高开发效率。
- **支持多数据源**: 简单配置即可实现切换不同的数据源。
- **完善的XSS防范及脚本过滤**: 彻底杜绝XSS攻击，保证系统安全。
- **Maven多项目依赖管理**: 采用模块及插件分项目，尽量松耦合，方便模块升级、增减模块。
- **国际化支持**: 同时支持服务端及客户端的国际化。
- **完善的日志记录体系**: 通过简单注解即可实现操作和异常日志的记录。

### 计划新增功能：
- 自动踢设备下线、自动修改密码等功能，以提高账号安全性和管理便利性。

### 技术选型：
1. **系统环境**
   - Java EE 8
   - Servlet 3.0
   - Apache Maven 3
2. **主框架**
   - Spring Boot 2.2.x
   - Spring Framework 5.2.x
   - Apache Shiro 1.7
3. **持久层**
   - Apache MyBatis 3.5.x
   - Hibernate Validation 6.0.x
   - Alibaba Druid 1.2.x
4. **视图层**
   - Bootstrap 3.3.7
   - Thymeleaf 3.0.x

### 内置功能：
- **用户管理**: 配置系统用户。
- **部门管理**: 配置组织机构，支持数据权限。
- **岗位管理**: 配置用户职务。
- **菜单管理**: 配置系统菜单及权限。
- **角色管理**: 角色权限分配及数据范围设置。
- **字典管理**: 维护固定数据。
- **参数管理**: 动态配置常用参数。
- **通知公告**: 信息发布维护。
- **操作日志**: 记录和查询操作及异常信息。
- **登录日志**: 记录查询登录及异常。
- **在线用户**: 监控活跃用户状态。
- **定时任务**: 在线任务调度及结果日志。
- **代码生成**: 生成前后端代码，支持下载。
- **系统接口**: 自动生成api接口文档。
- **服务监控**: 监视CPU、内存、磁盘等信息。
- **缓存监控**: 操作系统缓存。
- **在线构建器**: 生成HTML代码。
- **连接池监视**: 监视数据库连接池状态。

本系统适用于需大规模管理百度网盘账号的企业或商户，提供全面工具以优化账号管理和用户体验。




## 基础功能展示
### 登录页 
1. 管理员、各种角色、租户统一登录页面
2. 验证码可设置是否开启
<img width="1711" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/6a27baa4-74ad-4edf-b60a-1802aafded92">

### 首页
1. 上部分展示租户信息
2. 积分（租户每生成一张卡密需要消耗积分）无积分需要充值否则无法使用
3. 租户过期时间（过期时间内）
4. 租户自定义域名（该租户的卡密使用可通过专属域名消费使用）
5. 快速充值（租户充值积分，一次充值自动续费过期时间1年）
6. 下班部分 数据统计（待完成）
<img width="1716" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/1d461120-2d18-4ce4-96c0-0d9fb585638d">
<img width="1519" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/f24ffb28-c74d-4de8-8fa9-c68648f69d0a">
<img width="1504" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/54a833f4-c752-4d93-9e1d-cd1f0458d12a">


### 租户管理
1. 全量管理控制用户
2. 租户的密码只能充值不能查看
<img width="1716" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/7149d59c-26b2-429d-8d3e-47a60b8a8c5b">
<img width="1716" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/ea1a8e37-d558-4ea4-9741-30801f6b6928">

### 积分卡管理
1. 可单张自定义、也可批量生成卡密
2. 自动生成卡密不需要填写卡号，自动生成卡号
3. 面额和积分1比1充值，但是具体价值多少钱自己决定，一般一积分1毛钱
4. 全程记录使用者信息
<img width="1716" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/70be1a20-28e7-4279-a482-3b6f5442daec">
<img width="1483" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/1934bdf4-849d-4141-90f1-5a6bd6c3f0c2">
<img width="1496" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/86ef2211-cd40-4024-b504-ea904656e754">

### 网盘账号管理
1. 批量导入、模版化导入、导出、自动更新检测账号功能
2. 分组管理
3. 账号导入功能，自动化，导入自动获取账号信息，可以指定分配账号导入到哪个已经有的分组，自动创建分组、自动按照导入时间生成账号分组
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/08d2477e-3d89-4344-8940-d40dcbf57c56">
<img width="1510" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/ecde2d2d-b5b6-4168-b60f-66c2d9eeadef">
<img width="1453" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/6fc5a728-f31e-4dad-bc6e-68b9d0473e04">
<img width="1231" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/1a7b1c61-6bd4-4e70-94f8-0107d524739f">
<img width="1335" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/d290ef9e-78f9-4d75-8c19-ea26010827b2">

### 账号分组
1. 账号分组管理账号和卡密管理
2. 自定义的账池，可以配合自动功能，实现快过期的账号自动加入，使用该分组生成卡密可以作为免费使用，用作引流
3. 分组概念避免账号单个出问题
<img width="1716" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/5686621b-363d-41a2-a435-5b384a4f3d78">
<img width="1716" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/ba44e9a1-ad88-493c-a4df-473cbb6b159d">

### 套餐管理
1.多种类型的套餐配置
<img width="1716" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/3839b42c-e8ad-4a86-9349-08f5efbe3409">

### 卡密管理
1. 卡密基础管理
2. 导入自定义卡密导入
3. 导出功能，配合发卡网块度导入（按照租户的绑定的域名进行发卡）
4. 一键复制功能
5. 批量生成卡密（按照账号分组和套餐快速生成多张卡密）
6. ⚠注意：生成的卡密是无状态的，没有使用之间不受账号套餐分组等变动而改变，理论就是就算没有号了这个卡密也不受影响未来有号自动
7. 卡密的使用策略，当卡密第一次使用时候，自动从账号分组中获取一个账号（获取有算法加持，简答规则就是：优先使用为使用的并且可用的账号，如果都使用了，选择使用频率最小的账号，保证每个账号使用频次平均）
8. 自动换号功能（如果用户使用期间内，分组内某个账号有问题，或会员到期，自动从分组按照上面策略重新获取卡密，如果未过期则不会换号）
9. 自动检测账号状态，保证卡密使用期间，不会出现很多客服问题
10. 卡密自动过期
<img width="1716" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/ec17d081-11ad-4dca-93c7-dc105c0c82eb">
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/f2f271ab-f0ee-4c15-90a7-dee83c5699dd">
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/31b106ba-f5d8-4bae-8756-127579ef857e">
<img width="1120" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/f14d5e98-982a-472b-a41c-d1d515af0e8b">

### 使用记录
1.记录用户 的换号、登录等操作记录
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/8eaf7295-a678-4ee0-a4d0-b82d094d0544">

### 设置功能
1. 扫码模版的选择，多套模版扫码界面选择，不同功能
2. 公告、广告的设置、html格式
3. 售后教程的设置
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/d0cf682f-d137-4f9d-a350-42a3a9077d4b">

### 角色、权限、表单等系统管理功能
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/9af9d722-3447-4e72-978d-26c99a055cfc">
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/fea24a5e-e7a9-4770-8e29-7c28dfdbb861">
<img width="1715" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/6ddb34e2-48d8-4a82-96c6-7dc8bbd12778">



# 文档更新不及时， 其余功能请看更新日志！



















