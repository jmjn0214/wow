#  **人机恋🤖 品尝小酒馆** 
##  **酒馆在上半部分，api在下半部分** 
### 会一直更（bushi
### 此文档是酒馆教程+推荐可薅羊毛的API站（多为公益站）
### 桌面版有导航，代码显示更全；移动版适配屏幕，方便阅读

# 酒馆搭建🔋本地+云
## 本地酒馆搭建
## 1.会用到的app（魔法，termux，MT管理器是必备）
- 魔法推荐clash，绿茶也可，聚合页：vlink.cc/jmjn
- termux在本文档和聚合页都有
- MT管理器在教程第5步（可提前下也可跟着教程步骤下）
- 酒馆UI介绍和个人在用的实惠梯可看 **夸克盘** https://pan.quark.cn/s/b51f8df0091c

## 2.搞个魔法（推荐用clash，附教程和公益🔮指路以及绿茶官网）
- clash最新版app下载看这个，点击有安装包：https://dl.smjcdh.top/dl/cmfa-2.11.14-meta-arm64-v8a-release.apk
- 详情请看盘里的“clash相关.docx”文档
- clash简易教程↓
![输入图片说明](https://i.postimg.cc/cCRgzGrg/257-20250719195649.png)

公益魔法在文档靠下的位置
- 下滑找到这个条目↓
- 注释📌教程💎魔法🔮
（此条目中第三条）

- clash不太会的话也可以试试 **绿茶**：https://www.lvcha.org/

## 3.Termux和SillyTavern（你的后台+前端）
- termux软件下载地址：[推荐用118开头的版本](https://github.com/termux/termux-app/releases)
- APP看网盘，需魔法，看代码
- 一键和手动都行，各有优势（自行体验）
## 📌代码框尾部有现复制键

### 💎一键代码 喵喵（💎开头的任选一个就行）
推荐跟着这个视频走↓
【手机本地部署酒馆教程-哔哩哔哩】 
https://b23.tv/Ma0ovDW

- 代码 开🔮↓
```javascript
curl -O https://raw.githubusercontent.com/hopingmiao/termux_using_Claue/main/tisac.sh && chmod +x tisac.sh && ./tisac.sh
```
喵喵详细教程：https://sqivg8d05rm.feishu.cn/wiki/EY5TwjuwliCwZpk7Gy7cPGH1nvb

### 💎一键代码 欤小歡 （💎开头的任选一个就行）
每次输入完代码点回车键，让代码跑一会儿，等$符号出来后再继续下一条
- 国内源 不开🔮↓
```
curl -O https://gitee.com/Yuhuan-Dev/SillyTavern-Termux/raw/main/Install.sh && chmod +x Install.sh && ./Install.sh
```
- 国外源 开🔮↓
```
curl -O https://github.com/Yuhuan-Dev/SillyTavern-Termux/raw/main/Install.sh && chmod +x Install.sh && ./Install.sh
```
两个指令的作者是b站的欤小歡


### 💎手动代码 四步 开🔮（💎开头的任选一个就行）
每次输入完代码点回车键，让代码跑一会儿，等$符号出来后再继续下一步
1. 第一步
```
yes | pkg update && yes | pkg upgrade && yes | pkg install git nodejs python
```
2. 第二步
```
git clone https://github.com/SillyTavern/SillyTavern.git && cd SillyTavern && npm install && node server.js
```
3. 第三步
```
cd ~/SillyTavern && node server.js
```
- 后续酒馆更新用这个代码
```
cd ~/SillyTavern && git pull && npm install && node server.js
```
原帖指路：http://xhslink.com/m/6YamaitFncn

### 💎手动代码 七步 要🔮（💎开头的任选一个就行）
每次输入完代码点回车键，让代码跑一会儿，等$符号出来后再继续下一条
- 输入①
```javascript
pkg update -y
```
- 输入②
```javascript
pkg install git -y
```
- 输入③
```javascript
pkg install nodejs -y
```
- 输入④
```javascript
node --version  
npm --version
```
- 输入⑤
```javascript
git clone https://github.com/SillyTavern/SillyTavern -b release
```
- 输入⑥
```javascript
cd SillyTavern
bash start.sh
```
弄好后会自动跳转酒馆网页界面，这就代表搭建好了√
（你设置的默认浏览器是哪个，它就跳转哪个浏览器）
然后每次重新启动termux时输入⑥就行


### 💎一键代码 详 要🔮（💎开头的任选一个就行）
[一键代码点击跳转](https://wiki.xn--35zx7g.org/%E6%99%BA%E8%AF%86%E5%BA%93/sandbox/%E6%97%A0%E5%90%8D%E6%B0%8F/%E5%AE%89%E5%8D%93%E4%B8%80%E9%94%AE%E9%83%A8%E7%BD%B2%E6%95%99%E7%A8%8B?__cf_chl_rt_tk=_T0hYIZ7mJhsSg5zVCVcT4cHaIdVIgH4ko8GNkZKoUE-1751425165-1.0.1.1-JiEiZ79tMh0x4xz1JkEupuFYrlkjccAu6aSPwltfc3Q)

 **推两个xhs写教程的老师：** 
 **@木之本芝士 @老婆宝** 

### 酒馆UI介绍（新手推荐）
- 看最上面说的夸克盘，有图
![输入图片说明](https://files.catbox.moe/nxp2sa.png)

### 酒馆数字报错（简洁版）
![输入图片说明](https://files.catbox.moe/5hmfka.JPG)

## 4.MT管理器（设置一下根目录，找文件更方便）
termux准备工作做好后，来下这个，两个都行，看你自己
1. MT官网：https://mt2.cn/
2. MT破/解版：https://pan.quark.cn/s/bd521e3693c4
- termux记得挂后台别关！
![输入图片说明](https://files.catbox.moe/w2teit.png)

以后有问题就能来MT管理器的酒馆根目录上找，很方便
好了，你离成功不远了√

## 5.Discord（社区共建，大概是吃饭聚集地）
吃饭（预设、美化、世界书、插件、角色卡等）可以来这里瞅瞅，需魔法
- APP安装失败就用chrome等国外浏览器打开网页版↓
https://discord.com/
（官网有安装包）

官方邀请码：
- 旅程（推荐√）↓
https://discord.gg/elysianhorizon
- 酒馆（全英文）↓
https://discord.gg/sillytavern

好了去吃饭吧😘

## 详细版本地酒馆
这个劳斯的文档挺全面，推推
https://rrpkxlo5h4.feishu.cn/wiki/Gb7GwSd8AiAW8dkITLRcw8Q5nzh

# 云酒馆搭建
水秋喵劳斯的教程↓
VPS 部署 ClewdR+酒馆
https://sqivg8d05rm.feishu.cn/wiki/RVQ0wka6FiGGWXkc40jc2GHOnyc

### 类脑知识库酒馆搭建教程
https://wiki.xn--35zx7g.org/

很全√
# 注释📌教程💎魔法🔮
## emoji+注释（必看1）
（文档为手工整理，如有遗漏那就如有）
- 暂关=暂时关闭新用户注册
- L=需要Linux账号登录
- 邮=需邮箱注册的公益站
- Git=需要GitHub账号登录
- Gmail=需要Gmail账号登录
- 🛩=机场
- 🍉=ai中转格式
- 🐱=我吃这家gemini
- 🤖=我吃这家gpt
- 📜=我吃这家claude
- 🐋=我吃这家deepseek
- 🐏=还能薅的羊毛

## Linux相关教程（必看2）
文档栏目带“L”的都是L站的，需要Linux账号登录，所以此栏必看

L站地址↓
https://linux.do/

L站最新官方邀请码，进Linux首页点进这个往下翻↓
![输入图片说明](https://files.catbox.moe/b7ir4q.png)

（进Linux社区后请去看社区公告或者找主页机器人答题，答完会给你奖状√）

有人工审核，一般24h内，注册之后等邮箱通知就可以啦，审核通过的邮件是这样的↓
（24h没收到邮件的话重新注册试试，换个邮箱试试）

Linux活跃等级相关：https://linux.do/t/topic/660449


## 公益机场🛩/魔法🔮/梯子🪜
 **推荐在clash使用√** 
- 江佬：
直连[点击跳转复制网址后导入URL](https://zh.jikun.fun/share/file/%E6%B1%9F%E6%B1%9F%E5%85%AC%E7%9B%8A%E5%A2%9E%E5%BC%BA%E7%89%88?token=czxrF_PAqHXgwT4czcnSn)
原帖指路：
https://linux.do/t/topic/608380
- 188佬
通道：
https://250222.xyz/
原帖指路：
https://linux.do/t/topic/424429/253
- 梦佬（暂无）
直接在原帖领取分发的URL：
https://linux.do/t/topic/710146
- 月佬（跳转序号后复制网址导入URL）：
[①](https://wanmeiwl3.xyz/gywl/f454fc0cd34faef11783de0a8be4382c?flag=clashmeta)[②](https://yjjd.yunjijd.xyz/api/v1/client/subscribe?token=ee613c4480e152cfee0b6c9dc682999d)[③](https://52pokemon.xz61.cn/api/v1/client/subscribe?token=a7d4ca03debe575cbc363d4c8078acd9)[④](https://qea.278986.xyz/api/v1/client/subscribe?token=c737c4ce20a56d84b559cc4911e93e45)[⑤](http://8.138.34.87:3389/saccess/3c05082fcf2842cca2790bb5dbc2b911)
附月佬薅🐏教程：[一](https://lcndkivn2rxh.feishu.cn/wiki/XSTGwPXXdiHp0JkabKDc05MLn3b)[二](https://lcndkivn2rxh.feishu.cn/wiki/LyAKwPuB1iFlRYkuEwQcaRHFnAe)

## GitHub注册
地址：https://github.com/
进去后左上角Sign in
提一嘴：无审核，煮啵是用QQ邮箱注册的

## API key使用教程（新手必看）
1. 登录API站后，在屏幕到处点一下，找到“控制台”
2. 然后找到“API令牌”
3. 点“添加令牌”
4. 名称随意写，然后选“永不过期”和“设置无限额度”
5. “复制”令牌，令牌就是key（密匙），大多数API站是sk-xxx格式（少数不一样）
6. 复制端点URL，去聊天吧🌷


# 🍉各种各样的API
## 注释📌看了吗？
- 没看：去看一下吧↑
- 看了：好的往下看↓

## 端点都是网址第一个“/”后加v1
### 举个例子↓
- 网址：https://tbai.xin/console/topup
- 端点：https://tbai.xin/v1

## 此文档内推的都是可以薅羊毛的
- 大部分是公益站
- 有三个支持赞助，不强制要求
- 有两个半公益，已标注，部分模型免费使用
- 有两个非公益，已标注，可通过邀请薅额度

# 🍉New API吃一口
- 薄荷（暂关 L🐱）
通道：
https://x666.me/register?aff=AAKD
原帖指路：
https://linux.do/t/topic/743859

- Hazel（🐱📜🐋）
站主🐧：
240909197

- TB（L🐱🤖）
通道：
https://tbai.xin
公益站额度可蹲：
https://linux.do/t/topic/683726

- koko（L🤖🐱📜🐋）
通道：
https://kokoai.de/register?aff=cB67
原帖指路：
https://linux.do/t/topic/725945

- 月亮（暂关🤖🐱📜🐋）
双站点，可选保底or签到
🐧👗：
733012645
签到站通道：
http://49.12.130.109:45568/

- 我的（邮🤖🐱📜🐋）
通道：
https://api.howlife.cc/register?aff=wUX0

- 熊猫（邮🐱📜）
非公益，获得额度：邀请or付费
通道：
https://api520.pro/register?aff=jz7s

- 癫火猫（邮🤖🐱📜🐋）
非公益，获得额度：邀请or付费
通道：https://ai.dianhuomao.shop/register?aff=mbia

- indrin（邮🤖🐋）
通道：
https://llm.indrin.cn/register?aff=iD1Z

- CloseAI（L🐱🐋）
通道：
https://api.closeai.im/register?aff=X7KH
原帖指路：
https://linux.do/t/topic/619961/498

- Cups（Git/L🤖📜🐋）
先看原帖
通道：
https://free-llm.cups.moe/register?aff=2pu0
原帖指路：
https://linux.do/t/topic/767037

- Any Router（L📜）
官转，记得看公告
通道：
https://anyrouter.top/register?aff=XrYx

- Qins（暂关邮🐋🐱）
半公益，部分模型免费使用
通道：
https://anyrouter.top/register?aff=XrYx


# 🍉VoAPI吃一口
- AR-26710（暂关Gmail🐱📜）
签到制，记得看公告
公益站：https://glamoth.ar26710.online

 **Gmail登录（点注册时不要开梯），没APP就上网站：
https://workspace.google.com/intl/zh-CN/gmail** 

- grok（Q邮🐱📜🐋）
有签到，记得在公益站里翻翻
通道：
https://grok.sillytavern.cc/register?aff=CKlj


# 🍉Veloera吃一口
- wenwen（L🤖🐱📜🐋）
通道：https://veloera.wenwen12345.top/register?aff=F8yR
原帖指路：
https://linux.do/t/topic/747213

- 喵哥（邮/L🐱📜🐋）
通道：https://miaogeapi.deno.dev/register?aff=oDkh
原帖指路：
https://linux.do/t/topic/751127

- 翰林文苑（L🐱🐋）
先看原帖
通道：
https://api.voct.dev/register?aff=j8Fn
原帖指路：
https://linux.do/t/topic/676622


# 🍉其它吃一口
- Fo-API（L🐋）
通道：
https://v2.voct.top
原帖指路：
https://linux.do/t/topic/691455

- OneRouter（Git/Gmail🐱🐋）
半公益，部分模型免费使用
通道：
https://app.onerouter.pro/login?aff=xKlq

- 其它羊毛🐏（还能薅）
薅deepseek指路：
https://github.com/Feather-2/paper-burner-x
