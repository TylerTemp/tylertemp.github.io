---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

*   姓名: 黄铃
*   生年: 1995
*   工作: 9年
*   期望职位: Unity 游戏高级开发 (上海 base)
*   教育&证书: 上海理工大学（统招一本）；英语专业8级证书
*   微信: `QQ735506335`; 电话: [13220114946](tel:13220114946); 邮箱: [huang.exe@qq.com](mailto:huang.exe@qq.com)

-------------------------

## 核心能力 ##

1.  技术总监，主程，项目从立项带到上线经历，带过团队
2.  技术架构能力和数据处理能力。得益于之前的服务端经历，可以对游戏项目进行技术构架选型和构建。
3.  熟悉 Unity 游戏引擎，熟悉常见业务需求应当使用的最优方案，熟悉引擎的许多坑。
4.  实现过多维多队列消费逻辑，技能配合和相互影响（类似元素反映）逻辑等复杂业务
5.  开源人，创建并持续维护 Unity 编辑器插件 [github.com/TylerTemp/SaintsField](https://github.com/TylerTemp/SaintsField/) 已获 stars: [![repo-stars](https://img.shields.io/github/stars/TylerTemp/SaintsField)](https://github.com/TylerTemp/SaintsField/)
    <a href="https://github.com/TylerTemp" target="_blank"><img src="images/contributions.png" style="max-width:100%"/></a>


## 项目经验 ##

### 游戏果酱 GameJam: 《传说中的纸片公主》 ###

<video poster="images/a-strange-adventure-poster.png" autoplay muted loop width="300px" height="auto" style="max-width: 100%; float: right">
    <source src="images/a-strange-adventure-video.mp4" type="video/mp4" />
</video>

6名小伙伴一起参与的 TapTap 聚光灯活动，3周中的业余时间完成游戏开发，安卓+PC端，[taptap.cn/app/725464](https://www.taptap.cn/app/725464)

玩家可以操控、切换角色进行攻击，跳跃，互动，解密，解任务。配合一个小故事，将都市人的疲惫和希望展现出来。

1.  实现对话系统，配合对话系统的场景切换、对话选择等
2.  配合美术绑定 Spine 骨骼和动画
3.  制作纸片公主的施法 Spine 动画
4.  接入 Spine 到游戏的流程中
5.  PC+移动端适配
6.  应 TapTap 要求，原生 Java + Android Studio 实现隐私条款弹窗

### Unity 主程，2023年5月-至今 / 北京震宇翱翔文化创意有限公司 ###

#### 1.  《山河旅探》/辅程 ####


<a href="https://www.taptap.cn/app/219381" target="_blank"><img src="./images/shlt.png" width=200px height="auto" style="float: right"/></a>

项目中后期参与，TapTap地址: [taptap.cn/app/219381](https://www.taptap.cn/app/219381)


1.  处理平台打包问题，处理调试打包环境
2.  发现并指出项目中的删当问题，并向团队指出。（该问题因计算机原子操作导致，但因项目负责人听不懂原子，不接受意见，导致修改方向错误，该问题到现在依旧存在。）
3.  处理部分性能优化处理和代码性能问题

#### 2.  《我在地府打麻将》/主程 ####

<a href="https://store.steampowered.com/app/3444020/__Demonic_Mahjong/?l=schinese" target="_blank"><img src="images/majiang.jpg" width=200px height="auto" style="float: right" /></a>

麻将+肉鸽，从立项到上线，负责项目整体构架、技术选型、解决方案和程序进度推进。

Steam: [store.steampowered.com/app/3444020/__Demonic_Mahjong](https://store.steampowered.com/app/3444020/__Demonic_Mahjong/?l=schinese)

1.  Builder Pattern: Boss AI 构架设计
2.  Designer Pattern + FP + Side Effect Hook: 玩家小丑牌构架设计
3.  抽象并处理复杂业务业务，定义和规范接口与数据流，代码构架目前支持实习生级别程序也参与小丑牌等功能的编写填充
4.  使用 Burst 优化和牌算法，比 C# 版算法提升10倍计算性能，不使用协程的情况下不阻塞主线程
5.  Tail Recursion 实现麻将全番型计算
6.  Addressable 实现资源按需加载/卸载和热更
7.  I2 Localization 实现多语言切换
8.  对接并接入美术、特效，并制定相关规范
9.  编写对应 Editor 工具供程序、策划使用

### Unity 技术总监，2019年10月-2023年5月（3.5年） / 独立游戏团队 Bobo Studio（创业团队） ###

#### 《Groobo》音游 ####

<a href="https://groobo.comes.today" target="_blank"><img src="images/groobo.png" height=300px width="auto" style="float: right" /></a>

创新式音游，中重度游戏。iOS海外区: [apps.apple.com/app/id1552831622](https://apps.apple.com/app/id1552831622)，Google Play: [play.google.com/store/apps/details?id=studio.bobo.grooverpg](https://play.google.com/store/apps/details?id=studio.bobo.grooverpg) 。

玩家通过点击消灭不同轨道的怪物，并积攒魔力，释放技能以影响怪物，冻结动态生成源（降低难度）来破关。人物可成长解锁多个技能来组合，人物之间也能配合过关。

团队人数10人，负责管理团队，负责项目的技术推进。

* 自研音游引擎：
    * 制作谱面师打点工具，解析并落地为 ScriptableObject 对象
    * 基于音频的怪物驱动：读取Audio Sample，实时反推计算怪物时间并 Lerp 。处理音乐卡顿、手机掉帧时的正常卡拍
    * 怪物的动态变化：读取 pattern 配置并配置随机，让同一关卡重入有变化（区别传统音游）
    * 怪物生成点和运动轨迹分离：基于队列的取样反推，实现音游的传统下落式和创新折线式无缝切换（大量状态位管理）
* Wwise 深度集成：
    * 移动端极低延迟音频播放，处理用户端其它弹窗声音（通知、电话铃等）干扰当前音频流问题
    * 不同音乐无延迟实时切换（状态、触发、事件、复合轨道等能力）
    * 音乐库动态加载，音乐库 CDN 远程下载（DLC）
* 复杂业务层面：
    业务对实时变化要求非常高，导致无法按照传统音游模式开发。实现以下核心技术难点
    * **3维消费队列**：实现事实音乐remix和切换，并在切换前后不重不漏拍
    * **递归逆推**：音游无法使用物理系统（卡拍不准），故通过素体计算，关卡启动时递归所有怪物生成，规划路径防止怪物碰撞重叠
    * **元素反应**: 复杂状态机，角色技能/怪物元素的相互反应和影响实现
* 游戏引擎层面：
    * 通过Unity `Canvas`、`Layout`等，实现了对手机，Pad，刘海屏的全兼容自动适配
    * 手机多手指触控支持( `Touch` 组件)，处理点击、双击，防止点击事件被不同组件重复使用等
    * UnityWebRequest+Promise，处理网络请求，校验防止重复使用单一兑换码（服务端也是我负责实现，语言: Elixir）
    * 使用 `Obj-C`/`Java` 代码实现原生 IAP，使用插件接入 SDK
    * 通过 `Avatar Mask`， `Animation Layer`，实现3D角色的上下半身相互独立或覆盖动画控制
    * 使用 XCode 开发 iOS 原生插件，处理 Facebook SDK 与 Unity Deeplink 功能冲突
    * 其它很多业务开发和问题处理
* 沟通层面:
    * 经常性与策划沟通，以落地需求，确认需求边界
    * 与3D、特效沟通，落地需求、规格、什么能做什么不可以。（因为没有主美）
    * 与程序分配任务，沟通确认需求、时间
    * 与翻译（外国人）沟通项目英文翻译，配合首轮翻译，并参与四轮校对和五轮终校

#### 《打豆豆》 ####

<video poster="images/hand.png" height=300px width="auto" autoplay muted loop style="max-width: 100%; float: right">
    <source src="images/hand.mp4" type="video/mp4" />
</video>

节奏游戏。屏幕下一堆小球按节奏变大变小，看准时机点击小球后，小球飞上去攻击。

1. 使用 `meshCollier` 处理不规则对象的堆叠
2. 处理刚体抖动问题
3. 处理运动计算（掉落，攻击等；`DoTween`等插件）
4. 对接 Spine 动画并在程序中调用

#### 《跳一跳节奏版》 ####

一个按节奏的跳一跳3D小游戏。玩家按节奏点击屏幕后，角色类似“跳一跳”游戏一样从一个平台跳跃到另一个平台。（轻度，未上线）

1. 使用抛物线函数计算跳跃路径、路径长度、时间、速度（音游无法使用物理系统因为无法卡点，故手动计算）
2. 跳跃控制和镜头平滑跟随(`Lerp`等)

#### 《Groove Pad》 ####

<img src="images/groovepad.png" width=180px height="auto" style="float: right" />

启用、禁用不同的音乐chunk，允许玩家自行创作音乐。

1.  音乐 BPM 对齐切换
2.  Wwise 效果器处理，音色等参数随玩家调控变换
3.  音乐配置存档和载入

#### 《神说动次打次》 ####

一个单轨道音游，打Boss和防御Boss的3D游戏（轻度，未上线）。

1. 粒子系统的碰撞检测处理、回调
2. 粒子系统的预热处理
3. 射线检测定位等处理
4. 音乐卡点处理，同步音乐、玩家操作和屏幕反馈

### 2017.6-2019.7(2年)/主程/北京趣味谷科技有限公司  ###

游戏公司，Unity & Cocos Creator，游戏开发。团队人数8人，负责管理团队，负责项目的技术推进

#### 1. 《进击的炮娘》/主程 ####

<img src="images/jjdpn.jpg" width=150px height="auto" style="float: right" />

已上架海外 Google Play ，国内微信小游戏（因游戏备案原因停服）。类似于呆呆打僵尸，敌人往下走后，角色站桩射击。武器可以合成，角色可以使用技能攻击、减速或回推敌人。

1. 游戏开发
2. 计算怪物移动，处理子弹射击轨迹保证打到怪物身上
3. 处理武器合成逻辑，接入对应特效和音效
4. 安卓 SDK 接入（广告SDK，打点SDK，Facebook登陆SDK），通过Java代码实现跟Cocos通讯

#### 2. 棋牌游戏-麻将（掌悦游戏）/辅程 ####

已上线。多人传统地方麻将PVP游戏，房卡收费模式。

1. 部分游戏开发工作，界面UI处理
2. 负责服务端对接

### 辅程，2016.5-2017.6(1年)/北京海纳春秋科技有限公司  ###

互联网公司，负责开发 AdExchange + DSP 服务端(语言: Elixir, erlang)和后台Web端（BootStrap, Kibana）。服务端响应在100ms级别
