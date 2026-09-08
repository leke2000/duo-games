# 双人游戏机 · 13合1

手机端双人小游戏合集，单文件 [双人游戏机.html](双人游戏机.html)，无需联网。

## 线上仓库

- **GitHub**: https://github.com/leke2000/duo-games （main 分支）
- 手机直接打开 GitHub Pages 地址即可玩（若未开启 Pages，可在仓库 Settings → Pages 选择 main 分支启用）

## 游戏列表（13款）

- 回合策略：五子棋(9路)、井字棋、2048对决、数字炸弹
- 反应手速：反应对决、手速对决、拔河角力、抢答对决
- 记忆挑战：翻翻乐、记忆数字
- 休闲纸笔：你画我猜、石头剪刀布、幸运转盘

## 改版流程（AI 助手必须遵守）

**每次修改完 `双人游戏机.html`，必须立即 commit 并 push 到 GitHub**，不许留在本地：

```bash
cd "C:\Users\leke\.zcode\workspace\default"
git add "双人游戏机.html"
git commit -m "<简要说明这次改了什么>"
git push
```

- 提交信息用中文一句话说明改动内容
- 改完先本地验证（无 JS 报错、布局无溢出）再提交
- 用户名 leke2000，凭据由 Git Credential Manager 管理，push 无需手动输密码
