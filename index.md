# AlimadeM2 引擎主页

引擎网址: ALIMADE.GITHUB.IO

<b>联系我们:</b>  :wave:

- QQ交流群 ① 群: <i>168509341</i>

> 注意：验证请写明来意，Q龄不满一年一律不加！！！

## 引擎 & 登录器下载

### 引擎服务端下载

- 2024-08-18 <i>1.3.2</i> :fire: - 下载地址：[蓝奏云(密码:dgea)](https://wwyh.lanzouw.com/iQmep27pwj6h)
  - 爆率格式/外挂控制
- 2024-07-28 <i>1.3.1</i> - 下载地址：[蓝奏云(密码:7524)](https://wwl.lanzouw.com/iWx1P25sma7a)
  - 脚本变量/合区工具/日志服务
- 2024-07-14 <i>1.3.0</i> - 下载地址：[蓝奏云(密码:7bv4)](https://wwl.lanzouw.com/igL5p24g751g)
  - 封挂网关/属性突破
- 2024-06-29 <i>1.2.0</i> - 下载地址：<i>过时, 请下载最新版...</i>
  - 血量突破
- 2024-06-16 - 下载地址：<i>过时, 请下载最新版...</i>
- 2024-06-10 - 下载地址：<i>过时, 请下载最新版...</i>

### 万能登录器下载(内置及时雨)

- 2024-11-18 :fire: - 下载地址: [蓝奏云](https://wwyh.lanzouw.com/itYgR2gnmiwj)
- 2024-07-14 - 下载地址：<i>过时, 请下载最新版...</i>
  - 属性突破/黑夜系统

### 内挂登录器下载

- :running: 正在努力推进中...

### 三端登录器下载

- :running: 正在努力推进中...

## 引擎更新日志


- <b>2024-08-18</b> :fire:

01. 扩展爆率格式兼容GeeM2/GomM2爆率设置
02. 修复用户自定义命令HeroM2兼容
03. 优化游戏速度控制&增加"游戏速度->外挂"触发@UsePlugin
04. 修复@CallInputStringX HeroM2脚本兼容
05. 修复摇骰子PlayDice HeroM2协议兼容
06. 新增ThrowItem兼容HeroM2并扩展支持捡取时间,如:ThrowItem 3 330 330 10 回城卷 5 10(秒)
07. 修复AutoRunRobot执行ThrowItem异常(缺少地图环境)
08. 优化全局捡物逻辑确保ThrowItem脚本逻辑保持一致
09. 禁止刺杀吸血吸蓝,只允许近身攻击触发
10. 调整"在线人物->人物属性"金币/元宝最大上限到21亿
11. 修复ChangeModeEx的消息提示并支持S变量传参
12. 修复HitMon的S0变量,要求被攻击者为玩家人物
13. 修复<$MONKILLER> HeroM2变量兼容
14. 修复SetRankLevelName封号脚本的S变量兼容 
15. 修复GetRandomText HeroM2脚本兼容
16. 修复CheckHumInRange HeroM2脚本兼容
17. 修复GetOppositeHumName HeroM2脚本兼容
18. 修复GetUserItemName HeroM2脚本兼容
19. 修复CheckMapSameMonCount HeroM2脚本兼容
20. 修复CheckRangeMonCountEx HeroM2脚本兼容
21. 修复CheckOffline HeroM2脚本兼容
22. 修复GoldCount HeroM2脚本兼容
23. 支持ChangeDressEffect HeroM2脚本兼容
24. 修复刺杀一刀打出两刀导致双倍攻击问题
25. 支持CheckHumBag HeroM2脚本兼容

- <b>2024-07-28</b>

1. 提供引擎自带的数据合并工具，简称：合区工具
2. 修复 BDE 转 Access 数据类型不兼容的问题
3. 修复 ChangeModeEx 的 HP/MP 不生效问题
4. 支持 S0.GameGold + 100 脚本变量控制杀人者元宝奖励
5. 增加 HeroM2 的其他控制 & 脱机设置的界面(功能持续迭代中)
6. 修改 IPLocal 插件与 M2Server 的数据交互方式增强稳定性
7. 修复 AutoTakeOnItem 脚本与 HeroM2 兼容
8. 修复 LogDataServer 无法查看日志的问题
9. 修复封号显示问题 & 修复游戏速度调节无法保存
10. 修复若干代码中的小问题并进一步提高其稳定性

- <b>2024-07-14</b>

1. 修复 IPLocal 插件，每版引擎包提供且禁止跨版本混用
2. 修复 RepairAll 脚本并完成立刻反馈给到客户端
3. 修复在线排行版 HeroM2 兼容 - 直接利用 Npc 对话进行的实现
4. 突破 42 亿属性值，该功能尚在实验中，理论 21 亿更为稳定
5. 修复刺杀也能触发 QFunction 的 HitMon 脚本
6. 引擎进行整体正式化更名为 AlimadeM2
7. 适配新 IP 服客户端内核支持血量与属性的突破
8. GameCenter 支持自动缩放管理子窗口更加便捷
9. 提供额外的封挂网关 RunGateX，直接覆盖原有的，注意只能和 AlimadeM2 兼容
10. 修复若干代码中的小问题并进一步提高其稳定性

- <b>2024-06-29</b>

1. GameCenter 支持窗口嵌入
2. 支持使用 Access 数据库并提供 BDE 专 Access 配套工具
3. 修复 StdModeFunc 物品触发
4. 修复脚本时间变量 HOUR/MINUTE/SECOND
5. GameCenter 支持数据清理
6. 支持血量突破 42 亿 HP/MP ，旧万能登陆器依然显示 65535，阿里美德登陆器支持直接显示，客户端版本号必须要大于等于 20240629 才可以 - 实验性功能，使用前请进行数据清理
7. 修复吸蓝装备取下依然还可以吸的问题
8. 修复 AddSKill 技能等级不生效的问题
9. 增加 Mapinfo.txt 路由信息和爆率文件格式的错误提示


- <b>2024-06-16</b>

1. 登录锁定支持两种模式（超时/强退)
2. 支持 HITMON 和 CheckHitMonName 命令
3. 支持足球类 120 怪物的被攻击是否移动开关
4. 吸蓝支持，武器 AniCount 238 首饰 Shape: 236-238
5. 支持 ChangeModeEx 脚本
6. 解决多玩家场景下人物在门点坐标不同步的问题
7. 解决 MapEvent 任意触发和 HeroM2 的格式兼容
8. 解决 OpenWebSite , CheckLuckyPoint, TakeEx 等通用

- <b>2024-06-10</b>

1. 修复 BDE 的三件套读取支持: StdItems/Magic/Monster
2. 优化与升级代码并支持最新版的编译器
3. 关闭代码编译优化选项确保兼容性