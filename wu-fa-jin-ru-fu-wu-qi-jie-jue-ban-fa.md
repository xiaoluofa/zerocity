# 无法进入服务器解决办法

## **情况一，无效会话**

该提示说明你正版验证没有通过，目前正版验证有时候会被墙

解决方法一：选择使用加速器进行尝试

解决方法二：修改host

文件路径为 C:\Windows\System32\drivers\etc

打开host文件，鼠标右键选择打开方式，选择记事本即可

在文件最下面添加，然后保存

```
13.107.246.31 authserver.mojang.com #UHE_
13.107.246.31 resources.download.minecraft.net #UHE_
13.107.246.31 libraries.minecraft.net #UHE_
13.107.246.31 launcher.mojang.com #UHE_
13.107.246.31 launchermeta.mojang.com #UHE_
13.107.246.31 sessionserver.mojang.com #UHE_
13.107.246.31 api.minecraftservices.com #UHE_
13.107.246.31 textures.minecraft.net #UHE_
13.107.246.31 redstone-launcher.mojang.com #UHE_
13.107.246.31 api.mojang.com #UHE_
```

[<mark style="color:green;">刷新dns</mark>](https://zhuanlan.zhihu.com/p/476257556)<mark style="color:green;">或者重启电脑生效</mark>\ <mark style="color:green;">电脑小白推荐直接重启</mark>

## **情况二，以前可以进突然不行了？或者玩着玩着就掉了**

把你我的世界文件全删了！！！重新下载

或者建个新文件夹，重新下载原版

## 情况三如图

重新启动游戏，此问题是正版验证失败导致的或修改host

<figure><img src="https://s2.loli.net/2024/01/04/HFSlZ73vL2G1N4A.png" alt=""><figcaption></figcaption></figure>
