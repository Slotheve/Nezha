# openwrt_nezha

哪吒监控 For OpenWRT

**暂时仅支持lua版本**


## 用法

### 编译

将 `src-git nezha https://github.com/Erope/openwrt_nezha` 添加至 `feeds.conf.default` 后执行

./scripts/feeds update -a && ./scripts/feeds install -a

找到luci-app-nezha 选中后编译即可


## 安装IPK包

从Release中下载适合的包后自行安装(仅支持X64 X86和ARM64)


## 致谢

部分代码来自P3TERX <https://p3terx.com> 和 KFERMercer <KFER.Mercer@gmail.com>

源项目为: <https://github.com/naiba/nezha>

非常感谢！

