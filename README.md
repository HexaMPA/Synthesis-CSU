# 合成大中南——（synthesis-csu）

**声明，本项目仅帮助大家学习技术及娱乐，切勿将修改后的网站大规模传播及商用，以避免侵权！**

#### 介绍

最近合成大西瓜这一款小游戏在网上火爆出来，由于合成WHU给了我们灵感，因此我们对于源代码进行了一定的修改最后得到这个版本的合成大中南。

#### 源代码来源
源代码来源于BilibiliUP主，[程序员鱼皮](https://space.bilibili.com/12890453)  

详细教程：[魔改和上线你的合成大西瓜，最全教程！](https://mp.weixin.qq.com/s/H9VR1MWn-9bKSC_1l_MkJw)

视频教程：[全网最贴心的魔改合成大西瓜教程，从修改到发布！](https://www.bilibili.com/video/BV1Vy4y1n7KW/)


#### 使用教程

##### 1.本地启动

1. 安装 serve 工具：

   ```bash
   npm i -g serve
   ```

2. 进入 daxigua 目录，运行 serve：

   ```bash
   serve
   ```

3. 打开浏览器访问 localhost:5000 即可！

##### 2.网络启动

​	打开浏览器访问以下网址：[合成大中南](https://synthesis-csu.vercel.app)

#### 问题及解决

1. 无法安装 serve？

   答：如果报找不到 npm，请先安装 npm。

   如果安装中卡住，试着按下键盘（可能假死），还不行的话先用 npm 安装 cnpm（国内镜像，比较快）：

   ```bash
   npm install cnpm -g --registry=https://registry.npm.taobao.org 
   ```

   再执行 `cnpm i -g serve`。

2. Vercel 网址被微信拦截怎么办？

   答：可以把网址复制到浏览器打开，也可以申请一个域名，在 Vercel 和服务提供商配置域名解析。
   Vercel 基本是海外的服务器，无需备案。

3. 怎么在电脑上浏览网页游戏？

   答：在浏览器中，按 F12 打开开发者工具，点击像手机一样的图标即可。

#### 注意事项

1.  合成大中南灵感来源为合成WHU；
2.  知新馆辅学义工团队进行立项，参与问题解决；
3.  里面有三处惊喜，可以找找。

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request
