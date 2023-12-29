# 无法进入服务器解决办法

情况一，无效会话

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
