# GitHub Profile README 使用与恢复指南

## 这是如何生效的

GitHub 会把公开同名仓库 `WayneZ01/WayneZ01` 根目录中的 `README.md` 显示在个人主页 Overview 顶部。它不会替换 GitHub 自带的仓库、贡献记录、成就或置顶项目，只是在这些默认内容上方增加一个个人介绍区域。

## 日常修改

1. 打开 `https://github.com/WayneZ01/WayneZ01`。
2. 编辑 `README.md` 修改文字、链接和项目。
3. `assets/profile-hero.png` 是顶部视觉图。
4. `assets/avatar.png` 是制作头图时使用的头像快照；更换 GitHub 头像后，如需同步头图，需要重新生成一次头图。
5. 提交后刷新个人主页即可看到结果，GitHub 图片缓存偶尔需要几分钟更新。

## 恢复 GitHub 默认主页

最简单且可恢复的方法：

1. 在仓库中把 `README.md` 重命名为 `PROFILE_BACKUP.md`，或者删除 `README.md`。
2. 刷新 `https://github.com/WayneZ01`，自定义介绍区域会消失，主页恢复默认布局。
3. 以后想重新启用时，再把备份文件改回 `README.md`。

另一个方法是把 `WayneZ01/WayneZ01` 仓库改为 Private；同名仓库不再公开后，Profile README 也不会显示。重新改为 Public 即可恢复。

不建议为了恢复默认而删除整个仓库。保留仓库或改名备份，可以利用 Git 历史随时找回所有版本。

## 完全删除

如确实不再需要，可在仓库的 `Settings → General → Danger Zone → Delete this repository` 删除。删除仓库后个人主页立即回到 GitHub 默认状态，但仓库历史也会一并删除。

