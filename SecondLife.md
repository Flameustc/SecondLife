## 准备工作

加入 Second Life 以前，你需要准备：

- 一台配置不是太差的电脑
- 足够的网络流量

## 首次登录游戏

1. 去官网注册账号 [Second Life](https://secondlife.com/)，如果验证码刷不出来请挂梯子，除了这一步以外都可以直连。
2. 下载客户端
    - [Firestorm](https://www.firestormviewer.org/os/)
        - 优点：最常用的客户端，功能最齐全，性能优化做的最好，不知道选什么客户端的话选它就好了
        - 缺点：没有官中，实在是不想看到英文的话就选下面两个吧，只不过用中文界面有小概率会遇到意料之外的麻烦……
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

### 性能优化

Preferences - Graphics - General - Quality and speed
    
可以使用拖动条快速调整，越往左速度越快，越往右画面越好。也可以手动逐项调整，建议可以适当调低的选项包括：

- 降低绘制范围（Draw distance）
- 降低最大复杂度（Maximum complexity）的同时，勾选总是完整显示好友（World - Always show Friends fully）
- 人多拥挤的地方也可以只显示好友（World - show Friends only）

### 按需求修改（新手可以先跳过本节）

- 使用WASD移动

    Preferences - Move & View - Movement - Pressing letter keys affects movement

- 解除镜头限制

    Preferences - Move & View - View - Disable camera constraints

- 显示未加载完毕的角色

    Preferences - Graphics - Rendering - Show avatars that haven't finished loading

- 显示复杂度

    Preferences - General - Show avatar complexity

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
    - 使用客户端的前进/后退功能
- 接受其他玩家的TP邀请，TP到对方身边（tplure）
- 双击远处的地面进行TP (tplocal)
- 点击远处可以sit的道具进行TP (sittp)

关于传送点

先下线然后选择从你的家重新上线是另一种全局移动的方式，它不算是任何一种TP，也不受任何RLV的限制。


### 查看地图

保存当前地点的地标（landmark）

![保存地标](https://flameshare.azureedge.net/second-life/img/save-landmark.jpg)

注意：地标中虽然保存了详细的位置信息，但是很多地方限制了传送入口，无论你在哪里保存地标都只会传送到指定位置，无法精确定位到特定地点。

把当前地点设定为家（home）

![设定为家](https://flameshare.azureedge.net/second-life/img/set-home.jpg)


### 和其他玩家互动

了解玩家的名字构成

- 旧用户名（legacy name）：形如 LoginName Resident，是你注册游戏时填写的名字加上 Resident 后缀，保持大小写，不能重名。
- 新用户名（username）：形如 loginname，在旧用户名的基础上删除了 Resident 后缀，统一为小写，不能重名。
- 昵称（display name）：用户自己取的昵称，可以使用任何字符，两次修改之间至少要间隔一周，可以重名。
- 群称号（group title）：当前激活的群组中，用户可以根据自己所在的用户组，自行选定一个称号进行展示，也可以选择none不展示任何群称号。
- 全局唯一标识符（UUID）：形如 xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx，可以在用户的 Profile 里面找到，是游戏自动为每个用户生成的唯一ID。

和其他玩家的互动方式一览

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

**注意：本章中列出的所有图标均以Firestorm为例，在不同客户端中可能会有较大差异**

### 物品类别

SL中的任何物品，当它静静的躺在物品栏里的时候，它就像是你硬盘上的一个文件一样，你可以对它们进行移动复制粘贴建立快捷方式，又或者是通过私聊等方式分享给你的朋友，但是在这个状态下它们并不会对游戏本身产生任何直接影响。
一个物品只有当你用**正确的方式**打开它时，才能发挥它的作用。SL中这种**物品的正确打开方式**有如下几种：

- 使用SL自带的功能打开，这种一般是SL预先定义好的物品类型，比如用**传送到指定地点**打开**地标**，用**聊天快捷键**打开**手势**，用**游戏自带的文本浏览器**打开**记事卡**等等。

    所有SL预定义的物品类型可以在 [SL官方wiki](https://wiki.secondlife.com/wiki/Inventory) 上找到对应的说明，一个物品的类别可以根据它在物品栏中显示的图标加以判断，不同的客户端显示的图标可能有所区别。

- 把物品穿戴在身上，这种也称为**可穿戴物品**   
- 把物品生成在地上，这种也称为**可生成物品**
- 作为资源文件被其他物品读取和使用

可以穿戴在身上的物品又可以进一步分为两种：
- 预定义类型的可穿戴物品，如眼睛、皮肤、衬衫、裤子、鞋子等，在物品栏中分别以不同的图标显示，每个类型只能穿戴一件，穿戴后在物品名后面显示 ***(worn)***。

    ![预定义物品](https://flameshare.azureedge.net/second-life/img/wearable-worn.jpg)

- 非预定义类型的可穿戴物品，可以是任何东西，在物品栏中显示为通用物品（object），穿戴时需要指定穿戴的位置，穿戴后在物品名后面显示 ***(worn on xxx)***。

    ![非预定义物品](https://flameshare.azureedge.net/second-life/img/attachment-worn.jpg)

总的来说，SL预定义的那些可穿戴物品的类型中，只有头部数据（图标为头发），身体数据（图标为人头），脚部数据（图标为鞋子），皮肤（图标为小人）等少数几个有用，其他大部分类型在捏人的过程中均会被效果更好灵活性更强的通用物品所替代。注意这里说的不是旧物品被新物品替代，而是整个物品类型都弃之不用。因此本文后续提到**可穿戴物品**一词时，在没有特别说明的前提下，指的都是**可以穿戴在身上的通用物品**。

因为可穿戴物品都是通用物品，所以没有硬性的类别划分，不过依照功能来划分，还是可以列出一些相对比较重要的：

- Mesh身体
    - head
    - body
    - genital
- HUD
    没有游戏中的模型，只提供屏幕上互动界面的物品，一般被称为HUD。
- Alpha
    用来隐藏其他物品模型。
- AO
    Animation Override，用来改变人物的默认动作，如站姿、坐姿、走路姿势等。
- RLV Relay
    详见 [RLV](#RLV) 一节。

当一个通用物品被**穿戴**或者被**生成**时，一方面该物品成为了游戏中真实存在的物体，3D模型得到渲染，并且获得了相应的碰撞体积和物理效果；另一方面，该物品的内容（content）得到加载，同时内嵌的脚本也得到运行，从而产生各种各种的效果。前面已经说过了可穿戴物品，接下来聊一下可生成物品。

最常见的可生成物品就是在商店购物时获得的盒子（BOX），这类物品的唯一目的就是把一堆物品打包，方便发送和接收，但就像前面说的，盒子中的内容（content）只有当它被**穿戴**或者被**生成**时才能得到加载。因此盒子也可以大致分为两种，一种是穿戴在身上后，内嵌的自解包脚本就会自动触发，把内容发送到用户的物品栏里；另一种则没有这样的脚本，需要用户自己把盒子生成在地面上，然后打开盒子取出其中的物品。

最后我们看一下两个基础的物品类别：目录和链接。它们的定义和行为和windows中的目录和链接基本完全一样。其中物品栏中有一些系统预定义的目录，可以在 [SL官方wiki](https://wiki.secondlife.com/wiki/Inventory) 上找到对应的说明。除了默认的目录以外，另一个非常重要的目录是 #RLV 目录，详见 [RLV](#RLV) 一节。

### 物品操作

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

### 可穿戴物品

在SL早期版本中，人物纸娃娃系统有总共38个槽位（attachment point），每个槽位只能穿戴一件物品，因此可穿戴物品的最大数量就是38个。后来SL版本更新，允许多个物品穿戴到同一个槽位上，但是可穿戴的数量上限并没有变，仍然是最大38个物品。再后来SL引入了新的骨骼模型bento，槽位增加到47个，但是可穿戴物品的数量上限仍然是38个。

- 穿戴（wear）/ 添加（add）
    每个可穿戴物品会有一个指定的默认槽位，当你选择穿戴（wear）时，这个物品会穿戴到指定的槽位，并且脱下同一槽位中所有其他的物品；当你选择添加（add）时，这个物品会穿戴到指定的槽位，但是不会影响到同一槽位中的其他物品。因此仅当你很清楚该槽位上当前穿戴的所有物品，并且确实想要替换掉它们的时候才应该使用穿戴（wear），否则一律使用添加（add）。
- 脱下（detach）
- 触摸（touch）
- 编辑（edit）
- 加入套装（outfit）

穿戴物品的限制：不超过38个attachment

### 可生成物品

- 生成（rez）/ 收起（take）
- 打开（open）
- 触摸（touch）
- 坐下（sit）/ 站起（stand）
- 购买（pay）
- 身体接触

生成物品的限制：物品的Land Impact（LI）总和不能超过区域总承载能力（Land Capacity）。作为参考，一般大陆上的区域，其承载能力为每1024平方米351。

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
- 身体变形了
