# BaiduDisk-Qr-Login-Tenant-2.0
### 百度网盘扫码登录，远程扫码，多租户版本
*关键词：* 百度网盘扫码登录系统，远程登录系统，共享账号系统，多租户


## 服务器推荐：https://www.007idc.cn/aff/GVGFOKTS

# 功能过多，无法一一介绍，文档更新也不及时，时刻在更新迭代，
## 了解更多：
 联系作者：fifteenyang@qq.com（2k左右能接受在添加！备注百度网盘扫码2.0）

<img width="200" alt="image" src="https://github.com/zxyyang/BaiduDisk-Qr-Login-Tenant-2.0/assets/50910542/36e9abe7-0f3f-4bb4-b9af-693529bd5d59">







# 更新日志
## 更新时间2024-0827
1. 性能优化，提升访问速度
## 更新时间2024-0802
   1. 添加在线充值新用户会员活动（支持购买月卡/购买季卡） 同步更新租户使用一次扣一积分
      <img width="894" alt="image" src="https://github.com/user-attachments/assets/14bbf018-eabc-4a0a-b848-53fe5904be66">
      <img width="910" alt="image" src="https://github.com/user-attachments/assets/9f8e1aeb-3412-4d18-934e-3ef155a12695">

   2. 升级更新用户信息（以前的接口存在5分钟延迟），现在秒更新用户会员状态（过期时间可能仍然有几分钟延迟）
      <img width="331" alt="image" src="https://github.com/user-attachments/assets/c3302fad-5152-4539-b597-9e3df73d3657">

   3. 添加单个账号更新状态
         <img width="606" alt="image" src="https://github.com/user-attachments/assets/0bf6e1c0-9ee1-459c-a6cd-031e7430c33c">
   4. 升级分配账号算法
   5. 支持账号分组配置-是否运行用户可自助接码功能，如果关闭则对应分组的账号卡密没有接码按钮
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



















