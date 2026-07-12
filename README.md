# gomusicdl-lzcapp

## 自动发布

每天 23:00 UTC 检查 `guohuiyuan/go-music-dl` 稳定版本，使用 `docker.1ms.run/guohuiyuan/go-music-dl:<tag>` 代理镜像，构建版本化 GitHub Release Asset，并只发布到喵喵私有商店。
