# hub_sync

使用 [Yikun](https://github.com/Yikun) 大佬的 [hub-mirror-action](https://github.com/Yikun/hub-mirror-action) 将 github 上的仓库同步到 gitee 

注意以下问题：

- 支持私有仓库，需要使用[ssh方式](https://github.com/Yikun/hub-mirror-action/issues/38#issuecomment-1094041277)clone
- 企业版github --> 企业版gitee，原来 private 到了后发现成为 public 了，需要使用dst_visibility 分支，详情查看 [PR#160](https://github.com/Yikun/hub-mirror-action/pull/160)  


## 鸣谢

- [Hub Mirror Action](https://github.com/Yikun/hub-mirror-action#hub-mirror-action)
- [hub-mirror](https://github.com/yi-Xu-0100/hub-mirror)
