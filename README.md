# iOS版Shadowrocket 完美重签 无需付费 无需越狱~ 
### 越狱手机砸壳工具 详见<https://github.com/AloneMonkey/frida-ios-dump>
### 砸壳教程<https://github.com/we11cheng/WCStudy/blob/master/frida-ios-dump.md>
### dumpdecrypted砸壳<https://github.com/we11cheng/WCStudy/blob/master/dumpdecrypted%20%E5%AF%BC%E5%87%BA%E5%A4%B4%E6%96%87%E4%BB%B6.md>
### Clutch砸壳<https://github.com/we11cheng/WCStudy/blob/master/Clutch%E7%A0%B8%E5%A3%B3(%E8%8F%9C%E9%B8%A1%E7%89%88).md>
### 其他砸壳收集请戳<https://github.com/we11cheng/WCCrackedCollect>

## 本repo使用方法如下:

#### 1、安装MonkeyDev(如已安装，跳过)

- 安装最新的theos

```
sudo git clone --recursive https://github.com/theos/theos.git /opt/theos
```

- 安装ldid(如安装theos过程安装了ldid，跳过)

```
brew install ldid
```

- 指定的Xcode

```
sudo xcode-select -s /Applications/Xcode.app
```

- 执行安装命令

```
sudo /bin/sh -c "$(curl -fsSL https://raw.githubusercontent.com/AloneMonkey/MonkeyDev/master/bin/md-install)"
```

- 更新

```
sudo /bin/sh -c "$(curl -fsSL https://raw.githubusercontent.com/AloneMonkey/MonkeyDev/master/bin/md-update)"
```

- 卸载

```
sudo /bin/sh -c "$(curl -fsSL https://raw.githubusercontent.com/AloneMonkey/MonkeyDev/master/bin/md-uninstall)"
```

#### 2、运行工程

- 打开工程 WCShadowrocket.xcodeproj 
- 选择证书：自动配置证书即可（相信大家都是没有问题的）。
- 选择设备(不可选择模拟器，且仅支持64位设备)运行。
- 本次测试机iphone6s 10.3.3 xcode 9.2（其他机型自己尝试）。

## 版权及免责声明

- iOS逆向实践，不可使用于商业和个人其他意图。一切问题均由个人承担，与本人无关。
- 感谢MonkeyDev的作者庆总<https://github.com/AloneMonkey/MonkeyDev>。
- 如内容对您的权利造成了影响，请[issues](https://github.com/we11cheng/WCShadowrocket/issues), 我会在第一时间进行删除。

## 效果截图，七牛云图床挂了，找不到原图了。╮(╯_╰)╭
## 2018-6-26 新增ssr节点订阅模式(免费)。
- 参考<https://tool.ssrshare.xyz/tool/free_ssr>
- 如何订阅
- 打开shadowrocket 首页，点击右上角+号。模式选择Subscribe
- URL部分输入以下三个地址（一个或多选，多选表示订阅多个）

```
实时订阅链接,为防止滥用，24小时自动更改一次密码(key) 所有(golbal)可用订阅:
https://tool.ssrshare.xyz/tool/api/getGolSub?key=1529942400_8_xuo
实时订阅链接,为防止滥用，24小时自动更改一次密码(key) 中国(CN)可用订阅:
https://tool.ssrshare.xyz/tool/api/getCnSub?key=1529942400_8_xuo
非实时订阅链接（无密码）:
https://raw.githubusercontent.com/ImLaoD/sub/master/ssrshare.com
```
- 点击完成，就能发现节点列表新增了我们订阅节点信息。选择一个可以的连接即可。

#### 最后一个订阅地址是开源的(托管在git)。[查看作者repo](https://github.com/ImLaoD/sub)

## 2018-7-17 更新
#### 添加了Capabilities下Person VPN Network Extensions 帮助<https://github.com/we11cheng/WCStudy/blob/master/iOS%20Widget%20Extensions%E8%AF%81%E4%B9%A6%E9%85%8D%E7%BD%AE.md>

![](https://github.com/we11cheng/WCImageHost/raw/master/WX20180717-102431.png)

### 添加节点的时候，遇到问题，还没解决..求大佬们一起解决它..

```
CoreData: annotation:  Failed to load optimized model at path '/var/containers/Bundle/Application/9D19C752-5139-426B-815E-2A68B632352F/WCShadowrocket.app/Shadowrocket.momd/Shadowrocket 7.omo'
*** Terminating app due to uncaught exception 'NSFileHandleOperationException', reason: '*** -[NSConcreteFileHandle seekToFileOffset:]: Bad file descriptor'
```

![](https://github.com/we11cheng/WCImageHost/raw/master/WX20180717-102320.png)


## 2018-7-26 更新几个ssr订阅(部分已失效)
- 逗比根据地 <http://ss-ssshare.7e14.starter-us-west-2.openshiftapps.com/subscribe>
- 香港节点 <https://wepn.hk/link/idFgpbMYQQxvHjuK?mu=0>
- loremwalker <https://prom-php.herokuapp.com/cloudfra_ssr.txt>
- lpss共享1 <https://raw.githubusercontent.com/forpw2009/lpss2009/master/ssr/lpssr> lpss共享2 <https://raw.githubusercontent.com/forpw2009/lpss2009/master/v2ray/ssrr>作者github主页<https://github.com/forpw2009>
- Heroku <https://isspy.herokuapp.com/subscribe>

### 2018-8-21 App Engine欠费关闭，改用Heroku部署，项目主页地址 <https://isspy.herokuapp.com/> ss/ssr订阅地址 <https://isspy.herokuapp.com/subscribe>



#### 再来几个网上白嫖的订阅地址(有点靠谱)
```
https://git.io/autossr_recent
https://git.io/autossr_stable
https://git.io/autossr_online
```
#### 添加规则，详见<https://github.com/lhie1/Rules>，自行选择使用，更多规则<https://github.com/h2y/Shadowrocket-ADBlock-Rules>

## 华丽的分割线

点右上角的 Star 可以领红包，不信你试试。重签付费应用就是这么容易，感谢MonkeyDev作者。

## 最新更新 2021-04-15
### 分享一个自己搭建的搬瓦工CN2节点(ss)，流量有限，且用且珍惜。
#### 2021-04-15更新，白嫖继续，更新不及时/被墙可以关注我的公众号联系到我(彼岸情报分享)

二维码

![](https://gitee.com/he11oworld/picBed/raw/master/%E4%BA%8C%E7%BB%B4%E7%A0%81%E5%9B%BE%E7%89%87_4%E6%9C%8815%E6%97%A513%E6%97%B653%E5%88%8642%E7%A7%92.png)

文本

```
ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpxYXp3c3hlZGNAMTk4LjE4MS4zNS4xNDM6MTAwMDg#%23%E5%B0%8F%E7%A8%8B%E5%BA%8F:%E6%AF%8F%E6%97%A5%E5%A4%96%E5%8D%96%E8%81%94%E7%9B%9F
```

分享一个自己搭建的外卖领券小程序，欢迎大家学习交流

![](https://gitee.com/he11oworld/picBed/raw/master/20210410212801.png)


