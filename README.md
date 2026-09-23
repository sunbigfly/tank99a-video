# 坦克 99A 视频播放页

纯静态网页，部署在 GitHub Pages。`media/tank99a.mp4` 使用 H.264 视频和 AAC 音频，移动端打开页面后点击播放器即可观看。

## 文件

- `index.html`、`styles.css`：播放页源码。
- `media/tank99a.mp4`：适合浏览器播放的压缩版视频，约 16.4 MiB。
- `media/poster.jpg`：视频封面。
- `share-qr.png`：指向播放页的二维码，可直接发给用户扫码。

原始 MP4 的音轨为 `ipcm`，部分浏览器无法播放。压缩版保留原视频画面，使用同目录的原始 MP3 作为音轨重新编码。原文件未修改。

## 地址

- 播放页：<https://sunbigfly.github.io/tank99a-video/>
- 视频文件：<https://sunbigfly.github.io/tank99a-video/media/tank99a.mp4>
- jsDelivr 转换地址：<https://cdn.jsdelivr.net/gh/sunbigfly/tank99a-video@main/media/tank99a.mp4>

二维码应指向播放页地址。GitHub Pages 和 jsDelivr 在中国大陆的访问情况取决于用户网络，无法保证长期可达。
