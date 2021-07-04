## 已有软件

以下名称均为软件包名。

#### 通用

<details>
<summary>chromeos-gtk-theme</summary>

[@vinceluice](https://github.com/vinceliuice)写的仿chromeos gtk主题。

Github：https://github.com/vinceliuice/ChromeOS-theme

</details>

<details>
<summary>debtap</summary>


将deb包转为arch的pkg.tar.zst，虽然我还是更喜欢用dpkg重新打包

建议安装后编辑/usr/bin/debtap，修改如下内容，将源换为ustc以提升debtap -u速率：

```
#替换：http://ftp.debian.org/debian/dists 
https://mirrors.ustc.edu.cn/debian/dists 
#替换：http://archive.ubuntu.com/ubuntu/dists 
https://mirrors.ustc.edu.cn/ubuntu/dists/
```

</details>

<details>
<summary>lazygit</summary>



给像我这种连git stage和git commit都嫌麻烦的懒人用的git客户端。

Github：https://github.com/jesseduffield/lazygit

</details>

<details>
<summary>nautilus-admin</summary>


一个缺了就很难受的nautilus插件，提供右键以管理员身份打开文件。

Github：https://github.com/brunonova/nautilus-admin

</details>

<details>
<summary>yaru-gtk-theme-git</summary>


yaru的gtk主题，带有二十多种颜色꒰⑅•ᴗ•⑅꒱

Github：https://github.com/Jannomag/Yaru-Colors

</details>

<details>
<summary>yaru-icon-theme-git</summary>
yaru的图标主题，和上面的gtk主题配套食用。

Github：https://github.com/Jannomag/Yaru-Colors
</details>

#### x86_64 only

<details>
<summary>flutter-coolapk</summary>


大佬写的酷安flutter版，现由[@xkeyc](https://github.com/xkeyC)大佬维护，虽然功能有些残缺，但是日常刷刷酷安还是可以的。    

Github：https://github.com/Cyenoch/Flutter-Coolapk 				

Github新地址：https://github.com/clinux-co/coolapk_flutter    

</details>

<details>
<summary>netease-music-tui</summary>



另一个网抑云的tui客户端，相比iease-music有很多可圈可点的地方。使用前要先编辑~/.config/netease-music-tui/Settings.toml填入帐号密码，如果没有可以新建。

Github：https://github.com/betta-cyber/netease-music-tui

</details>

<details>
<summary>purewriter</summary>


没错就是纯纯写作！由[@drakeet](https://github.com/PureWriter)大佬编写，[@Liaronce](https://github.com/LiarOnce)大佬编译。需要购买纯纯写作会员才能食用。目前可能有一些功能上的问题。         

Github：https://github.com/PureWriter/desktop             

编译后的版本：https://purewriter.liaronce.com/#/    

</details>

<details>
<summary>top.yzzi.tomato</summary>


[@uzYzzi](https://github.com/uiYzzi)大佬写的简约番茄钟，配合deepinv20桌面食用最佳，gnome和kde在标题栏显示上也许有点点问题。。提醒一下，从terminal启动这个应用直接输入one-tomato。     

Github：https://github.com/uiYzzi/one-tomato      

</details>

<details>
<summary>utools</summary>


你的生产力工具集。

官网：https://u.tools/

AUR：https://aur.archlinux.org/packages/utools/

</details>

#### x86_64 multilib x86

<details>
<summary>mcpelauncher-client</summary>

用来在Linux上运行Minecraft基岩版，通过在Linux上补全bionic有关库的方式运行android版mc。自测性能比Java版强些，但需要找到对应版本的apk（我只能说在某个群里有），而且必须是x86（或者如果你在Play上买了可以登录Google账户来获取）。    

mcpelauncher-client是i386架构，需要打开`[multilib]`并添加`[coolapk-linux32]`。

Github：https://github.com/minecraft-linux/mcpelauncher-manifest

Wiki：https://mcpelauncher.readthedocs.io/en/latest/getting_started.html

现在还算活跃更新的一个fork：https://github.com/ChristopherHX/linux-packaging-scripts/

以后可能会考虑使用后者继续更新。

</details>

#### aarch64 only

<details>
<summary>fakeroot-tcp</summary>


在termux之类的软件上使用的fakeroot（一般的fakeroot无法使用）

</details>



