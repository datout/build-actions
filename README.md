-2023年2月6号

- cd openwrt && make menuconfig

新版编译仓库：https://github.com/281677160/autobuild

老版编译仓库：https://github.com/281677160/build-actions

新版本地一键编译：https://github.com/281677160/bendi

懒写说明了，自己摸索吧，Lienol大的源码是随缘的今天能编译明天或者就不可以了，后天又或者可以

过段时间会把autobuild更新至build-actions仓库的


---
---


<details>
<summary>🆙点击查看更新说明</summary>
<br>

2022年10月22号，修复定时触发启动编译失败问题，修复提示nodejs.12需要升级成nodejs.16的问题

2022年10月9号，因为上游Lienol大佬删除了22.03源码，我这里也就把22.03改成他的21.02源码了，编译脚本的ubuntu也从20.04改成22.04


2022年7月28号，编译时候在diy-part.sh文件里面可以对OpenClash代码进行分支选择，可选master或者dev分支，选错或者不选就默认使用master分支


2022年7月6号16点，去除重复插件


2022年4月27号修改
  
1、把 build/openwrt_amlogic/diy-part.sh 里面的晶晨打包组合的路径修改过了，请及时更新

2、把编译的时候不想要的固件或者文件的删除方法修改过了，注意diy-part.sh的代码路径也修改过了，要及时更新，新删除方法请到《[`删除不想要的固件或者文件`](https://github.com/danshui-git/shuoming/blob/master/%E5%9B%BA%E4%BB%B6%E6%96%87%E4%BB%B6%E5%A4%B9%E6%95%B4%E7%90%86.md)》查看说明

<br />
</details>


---
<details>
<summary>🆘点击查看编译教程</summary>
<br>

## [`github编译教程`](https://github.com/danshui-git/shuoming#readme)

---
#### [`本地Ubuntu一键编译`](https://github.com/281677160/bendi)
#### [`本地一键提取.config然后在云编译脚本使用`](https://github.com/danshui-git/shuoming/blob/master/yijianconfig.md)

<br />
</details>


---
 ### 鸣谢！
 感谢以下各位大佬（排名无分先后）<br />
 
 [`coolsnowwolf`](https://github.com/coolsnowwolf/lede/tree/master)
 [`Lienol`](https://github.com/Lienol/openwrt/tree/21.02)
 [`immortalwrt`](https://github.com/immortalwrt/immortalwrt)
 [`P3TERX`](https://github.com/P3TERX/Actions-OpenWrt)
 [`Hyy2001X`](https://github.com/Hyy2001X/AutoBuild-Actions)
 [`dhxh`](https://github.com/dhxh/Openwrt-Build)
 [`ophub`](https://github.com/ophub/amlogic-s9xxx-openwrt)
 [`nicholas-opensource`](https://github.com/nicholas-opensource/OpenWrt-Autobuild)
 [`hx210`](#/README.md)
 [`hyird`](#/README.md)
 [`World Peace`](#/README.md)
 [`klever1988`](https://github.com/klever1988/cachewrtbuild)
 [`actions`](https://github.com/actions/upload-artifact)
 [`svenstaro`](https://github.com/svenstaro/upload-release-action)
