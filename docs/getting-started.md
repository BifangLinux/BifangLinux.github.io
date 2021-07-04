## 使用方法



#### 使用Gitee或者Github

先将源地址写入/etc/pacman.conf：国内用户推荐使用Gitee上的：

```yaml
[coolapk-linux]
SigLevel = Optional TrustAll
Server = https://alexander-huang.gitee.io/coolapk-linux/$repo/$arch
Server = https://alexander-huang.gitee.io/coolapk-linux/$repo/any
```
当然，~~如果你能顺畅访问Github~~，你也可以用**Fastgit，一个面向GitHub的反向代理，直接连接GitHub**：

```yaml
[coolapk-linux]
SigLevel = Optional TrustAll
Server = https://raw.fastgit.org/CoolapkLinux/coolapk-linux/master/$repo/$arch
Server = https://raw.fastgit.org/CoolapkLinux/coolapk-linux/master/$repo/any
```

为了关爱强迫症患者，我们把32位的包单独存放在coolapk-linux32，可以按需使用。

然后执行：

```shell
sudo pacman -Syy
```



#### 使用测试中的软件源

这个源的原理是用one manager提取onedrive的直链。由于onedrive网速不稳定，且需要打包脚本的大量适配，此源仍在测试中。之后我们会使用阿里云盘代替onedrive。

<font color=#ff7c70 size=4 face="noto-sans">警告：使用过程中可能出现下载速度缓慢、断流、404等情况！</font>

挂在heroku上的：https://repo.oganesson.top/

```
[coolapk-linux]
SigLevel = Optional TrustAll
Server = https://repo.oganesson.top/arch-repo/$arch
Server = https://repo.oganesson.top/arch-repo/any
```

挂在华为云函数上的：https://057fb7ebc01644f6b90e26a76bbb9ad8.apig.cn-east-3.huaweicloudapis.com/

emmm，后者多半会被放弃。所以不提供配置方法。