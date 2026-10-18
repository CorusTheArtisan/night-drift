# 首都高 Night Drift

东京首都高夜间漂移网页游戏，A GAME BY Corus Z。

**在线游玩：** https://corustheartisan.github.io/night-drift/

## 玩法

车会自动加速。按住屏幕左半边或右半边转向，一直按着就会甩尾漂移，漂移越久倍率越高；贴着路人车高速超过能得分并获得氮气加速。追尾三次结束。电脑用 ← → 或 A D，空格暂停。

## 说明

整个游戏是一个 `index.html`（three.js r128 + Web Audio 实时合成音乐），不需要构建。推送到 `main` 或 `claude/game-upload-deploy-77f8xg` 分支后，`.github/workflows/pages.yml` 会自动发布到 GitHub Pages。
