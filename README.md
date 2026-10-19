# 首都高 · Corus Z 的两个网页游戏

两个游戏都在同一个首都高夜景世界里，直接用浏览器打开链接就能玩（电脑和手机都可以）。A GAME BY Corus Z。

| 游戏 | 在线游玩 |
|---|---|
| 首都高 Night Drift（漂移） | https://corustheartisan.github.io/night-drift/ |
| SHUTOKO PULSE（节奏 × 首都高） | https://corustheartisan.github.io/night-drift/pulse/ |

## 首都高 Night Drift

车会自动加速。按住屏幕左半边或右半边转向，一直按着就会甩尾漂移，漂移越久倍率越高；贴着路人车高速超过能得分并获得氮气加速。追尾三次结束。电脑用 ← → 或 A D，空格暂停。

## SHUTOKO PULSE

点屏幕左半边 / 右半边换道，车流按歌曲的节拍生成：车下圆圈满格的一瞬间换道就是 PERFECT，正好卡在鼓点上。间奏里有漂移弯：在粉色光带按住弯道一侧，到金色光带松手。三种难度：简单、普通、NEON DRIVE（路线锁死，平均每秒 3 下）。

- 内置 4 首 Corus 用 Suno 做的歌（She Moves Like Me、Said She、Night Drift、Signal Ghost）和 3 首合成器电台。
- 选完歌和难度后进入车库：四台原创车（紫電 SHIDEN、雷神 RAIJIN GT、疾風 HAYATE、FALKE 9）和六种车漆，外观不同，操控和判定完全一样。
- 收音机顶上的碟口可以放入你自己的 MP3：在浏览器里分析节拍、自动生成赛道，文件只存在你自己的设备上，不会上传，别人也看不到。
- 开始页面的「设置」里可以调音量、节拍延迟（带校准）、画质和特效，并有实时帧率指示。
- 电脑用 ← → 或 A D，空格暂停。

## 说明

两个游戏都是单个 `index.html`（three.js r128 + Web Audio），不需要构建。PULSE 的歌在 `pulse/songs/`。推送到 `main` 或 `claude/game-upload-deploy-77f8xg` 分支后，`.github/workflows/pages.yml` 会自动把两个游戏一起发布到 GitHub Pages。
