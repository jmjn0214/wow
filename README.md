#  **人机恋🤖 品尝小酒馆** 
## 酒馆教程在上半部分
## API站推荐在下半部分
### 都是能薅羊毛的API，作者一分没花（挠头）

# 酒馆搭建🔋本地+云
## 本地酒馆搭建
## 1.会用到的app（魔法，termux，MT管理器是必备）
- 魔法推荐clash，绿茶也可，聚合页：vlink.cc/jmjn
- termux在本文档和聚合页都有
- MT管理器在教程第5步（可提前下也可跟着教程步骤下）



## 2.搞个魔法（推荐用clash，附教程和公益🔮指路以及绿茶官网
### clash安装包：
https://dl.smjcdh.top/dl/cmfa-2.11.14-meta-arm64-v8a-release.apk
- clash简易教程↓
![输入图片说明](https://i.postimg.cc/cCRgzGrg/257-20250719195649.png)

### 公益机场🛩/魔法🔮/梯子🪜
 **推荐在clash使用√** 
- 江佬：
直连[点击跳转，在搜索框复制网址，然后导入URL](https://zh.jikun.fun/share/file/%E6%B1%9F%E6%B1%9F%E5%85%AC%E7%9B%8A%E5%A2%9E%E5%BC%BA%E7%89%88?token=czxrF_PAqHXgwT4czcnSn)
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
[①](https://wanmeiwl3.xyz/gywl/f454fc0cd34faef11783de0a8be4382c?flag=clashmeta) [②](https://yjjd.yunjijd.xyz/api/v1/client/subscribe?token=ee613c4480e152cfee0b6c9dc682999d) [③](https://52pokemon.xz61.cn/api/v1/client/subscribe?token=a7d4ca03debe575cbc363d4c8078acd9) [④](https://qea.278986.xyz/api/v1/client/subscribe?token=c737c4ce20a56d84b559cc4911e93e45) [⑤](http://8.138.34.87:3389/saccess/3c05082fcf2842cca2790bb5dbc2b911)
附月佬薅🐏教程：[一](https://lcndkivn2rxh.feishu.cn/wiki/XSTGwPXXdiHp0JkabKDc05MLn3b) [二](https://lcndkivn2rxh.feishu.cn/wiki/LyAKwPuB1iFlRYkuEwQcaRHFnAe) [三](https://lcndkivn2rxh.feishu.cn/wiki/Q8DBwVl4UizU5dkdX3scrQ7dnMf)

### 绿茶（clash不太会就试试这个）：
https://www.lvcha.org/



## 3.Termux和SillyTavern（你的后台+前端）
- termux软件下载地址：[推荐用118开头的版本](https://github.com/termux/termux-app/releases)
- APP看网盘，需魔法，看代码
- 一键和手动都行，各有优势（自行体验）
## 📌代码框尾部有复制键

### 类脑知识库酒馆搭建教程
https://wiki.xn--35zx7g.org/
很全，手机端，pc端，云端都有√

- 每次输入完代码点回车键，让代码跑一会儿，等$符号出来后再继续下一条

### 💎一键代码 欤歡 （💎开头的任选一个就行）
- 两个指令的作者是b站的欤小歡
[yuhuan代码文档](https://gitee.com/print-yuhuan/SillyTavern-Termux/blob/main/README.md)

### 💎一键代码 喵/ClewdR（💎开头的任选一个就行）
[一键代码点击跳转](https://wiki.xn--35zx7g.org/%E6%99%BA%E8%AF%86%E5%BA%93/sandbox/%E6%97%A0%E5%90%8D%E6%B0%8F/%E5%AE%89%E5%8D%93%E4%B8%80%E9%94%AE%E9%83%A8%E7%BD%B2%E6%95%99%E7%A8%8B?__cf_chl_rt_tk=_T0hYIZ7mJhsSg5zVCVcT4cHaIdVIgH4ko8GNkZKoUE-1751425165-1.0.1.1-JiEiZ79tMh0x4xz1JkEupuFYrlkjccAu6aSPwltfc3Q)

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

### 酒馆数字报错（简洁版）
![输入图片说明](https://files.catbox.moe/5hmfka.JPG)



## 4.MT管理器（设置一下根目录，找文件更方便）
termux准备工作做好后，来下这个，两个都行，看你自己
1. MT官网：https://mt2.cn/
2. MT破/解版：https://pan.quark.cn/s/ce9123d9a1ff
- termux记得挂后台别关！
![输入图片说明](https://files.catbox.moe/w2teit.png)
- 没看到sillytavern文件夹不要慌，不是bug，请在这个里面找找
![](https://i.postimg.cc/Yqdxmc96/267-20250722013131.png)
以后有问题就能来MT管理器的酒馆根目录上找，很方便
好了，你离成功不远了√



## 5.Discord（社区共建，大概是吃饭聚集地）
吃饭（预设、美化、世界书、插件、角色卡等）可以来这里瞅瞅，需魔法
- 用chrome等国外浏览器打开网页版↓
https://discord.com/
（官网有下载入坑）
- 下载失败就用夸克网盘：https://pan.quark.cn/s/a258b94f0f71

官方邀请码：
- 旅程（推荐√）↓
https://discord.gg/elysianhorizon
- 酒馆（全英文）↓
https://discord.gg/sillytavern

好了去吃饭吧😘



# 关于薅gemini官key的羊毛
- 条件：Google账号，开🔮
- 提取key的地址：https://aistudio.google.com/app/apikey
- 关于key的轮询，这里我写了一个教程，有三种轮询：
https://gcnjcayqobfd.feishu.cn/wiki/TMafwyirei4JtxkvonVcQLqgnqg
- 轮询教程，预览图：
![图](https://i.postimg.cc/GprRHSp1/IMG-20250722-021004.jpg)





