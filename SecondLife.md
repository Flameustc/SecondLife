## 准备工作

加入 Second Life 以前，你需要准备：

- 一台配置不是太差的电脑
- 足够的网络流量

## 首次登录游戏

1. 去官网注册账号 [Second Life](https://secondlife.com/)，如果验证码刷不出来请挂梯子，除了这一步以外都可以直连。
2. 下载客户端
    - [Firestorm](https://www.firestormviewer.org/os/)
        - 优点：最常用的客户端，功能最齐全，不知道选什么客户端的话选它就好了
        - 缺点：稍稍有些笨重，没有官中，实在是不想看到英文的话就选下面两个吧，只不过用中文界面有小概率会遇到意料之外的麻烦……
    - [Catznip](https://get.catznip.com/downloads)
        - 优点：轻量级，速度快
        - 缺点：部分功能缺失，建议另外安装一个Firestorm用来补漏
    - [Kokua](https://sourceforge.net/projects/kokua.team-purple.p/)
        - 优点：独有的FTRLV模式，完全无助的体验
        - 缺点：有些时候关闭RLV是唯一解决问题的办法，其他人（包括你的主人在内）并不能帮助你
3. 用客户端登录账号

    这一步可能出现的问题

    - 系统时间错误
    
        ![系统时间错误](https://flameshare.azureedge.net/second-life/login_error.jpg)

        手动同步系统时间后，多试几次即可

## 修改客户端配置

（以下均以英文版Firestorm为例）

### 必改

- 内容分级

    Preferences - General - I want to access content rated:

    ![内容分级](https://flameshare.azureedge.net/second-life/content-rate.jpg)
- 打开RLV

    Preferences - Firestorm - Extras - Allow Remote Scripted Viewer Controls (RLVa)
- 打开ALM

    Preferences - Graphics - General - Advanced Lighting Model


### 按需求修改（新手可以先跳过本节）

- 使用WASD移动

    Preferences - Move & View - Movement - Pressing letter keys affects movement

## 基础操作

### 移动

- 走（walk）/ 跑（run）
- 飞行（fly）
- 乘坐载具

### 传送（TP）

TP的类型，括号里是在RLV中对应的关键字

- 使用地标进行TP (tplm)
- 使用坐标进行TP (tploc)
    - 在地址栏输入SLUrl进行TP
    - 游戏内或游戏外点击SLUrl链接进行TP
    - 从世界地图TP
- 接受其他玩家的TP邀请，TP到对方身边（tplure）
- 双击远处的地面进行TP (tplocal)
- 点击远处可以sit的道具进行TP (sittp)

先下线然后选择从你的家重新上线是另一种全局移动的方式，它不算是任何一种TP，也不受任何RLV的限制。


### 查看地图

保存地标

### 和其他玩家互动

玩家的名字构成

- 旧用户名（legacy name）：形如 LoginName Resident，是你注册游戏时填写的名字加上 Resident 后缀，保持大小写，不能重名
- 新用户名（username）：形如 loginname，在旧用户名的基础上删除了 Resident 后缀，统一为小写，不能重名
- 昵称（display name）：用户自己取的昵称，可以使用任何字符，两次修改之间至少要间隔一周，可以重名
- 


- 公开聊天
    - 说话（chat）/ 小声说（whisper）/ 大叫（shout）
- 私聊（IM）
- 群聊（group chat）
- 表情（emote）
- 手势（gesture）
- 推人（push）
- 添加好友
    - 允许对方看到你是否在线
    - 允许对方在大地图上找到你
    - 允许对方修改你的物品
- 查看聊天记录
- 发送/接受TP邀请
- 和对方穿戴的物品互动
    - 上锁（lock）
    - 牵绳（leash）
- 使用其他物品和对方互动
    - 播放单人/多人动作（animation）
    - 使用RLV道具进行捕捉（capture）

### 操作物品

详见 [物品和物品栏](#物品和物品栏) 一节。

## 高级操作（奇技淫巧）

- Ctrl+Alt+T
- Derender
- Edit linked

## 物品和物品栏

### 物品栏

物品栏中的目录图标可以在 [SL官方wiki](https://wiki.secondlife.com/wiki/Inventory) 上找到对应的说明，不同的客户端可能有所区别。
除了默认的目录以外，另一个非常重要的目录是 #RLV 目录，详见 [RLV](#RLV) 一节。

SL默认的物品类别可以在 [SL官方wiki](https://wiki.secondlife.com/wiki/Inventory) 上找到对应的说明。
除了默认的物品类别以外，比较重要的物品类别有：

- Attachment
- BOX
    - 需要rez
    - 自解包
- HUD
- Alpha
- AO
- RLV Relay

使用物品栏过滤器寻找特定物品。

- 物品属性

    - copy

        当一个物品被设置为 (no copy) 的时候，操作会导致物品从以前的地方消失：

        - rez
        - 通过

    - modify

        当一个物品被设置为 (no modify) 的时候，你仍然可以：

        - 移动（move）
        - 旋转（rotate）
        - 修改贴图（texture）
        - 修改贴图参数（比如Glossiness）
        - 重置脚本
        
        你不能：
        - 缩放（strectch）
        - 改变内容（content）

    - transfer
    - rigged

### 可穿戴的物品

- 穿戴（wear）/ 添加（add）
- 脱下（detach）
- 触摸（touch）
- 编辑（edit）
- 加入套装（outfit）

穿戴物品的限制：不超过38个attachment

### 可生成的物品

- 生成（rez）/ 收起（take）
- 打开（open）
- 触摸（touch）
- 坐下（sit）/ 站起（stand）
- 购买（pay）
- 身体接触

生成物品的限制：Land Impact（LI）

## RLV

### 什么是RLV

### 常见的RLV类型

- 限制（restriction）

    禁止玩家进行某些行为，体现为按钮变灰无法使用（比如禁止脱下，detach按钮会变灰不可用），或者是操作无法执行（比如禁止IM，试图发送IM只会得到IM功能被禁用的提示）。

- 混淆

    不禁止玩家进行某些行为，而是改变这些行为产生的效果，比如随机替换玩家聊天内容以模拟口塞的效果。

- 改变（modifier）
    - 移动速度
    - 视角移动范围
    - 触摸范围

### RLV Zone

### RLV常见问题

- 查看RLV限制列表

    RLV关键词可以在 [RLV官方wiki](https://wiki.secondlife.com/wiki/LSL_Protocol/RestrainedLoveAPI) 上找到对应的说明。

## 杂项

- 要不要充会员
- 服务器重启