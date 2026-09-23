# 坦克 99A 视频播放页

纯静态网页，部署在 GitHub Pages。`media/tank99a.mp4` 使用 H.264 视频和 AAC 音频，移动端打开页面后点击播放器即可观看。

## 文件

- `index.html`、`styles.css`：播放页源码。
- `media/tank99a.mp4`：适合浏览器播放的压缩版视频，约 16.4 MiB。
- `media/poster.jpg`：视频封面。
- `share-qr-jsdmirror.png`：指向 JSDMirror 视频地址的二维码，扫码后使用浏览器自带播放器，当前建议分享此文件。
- `share-qr.png`：指向 GitHub Pages 播放页的二维码。
- `share-qr-video.png`：指向 jsDelivr 视频地址的二维码。

原始 MP4 的音轨为 `ipcm`，部分浏览器无法播放。压缩版保留原视频画面，使用同目录的原始 MP3 作为音轨重新编码。原文件未修改。

## 地址

- 播放页：<https://sunbigfly.github.io/tank99a-video/>
- 视频文件：<https://sunbigfly.github.io/tank99a-video/media/tank99a.mp4>
- JSDMirror 转换地址：<https://cdn.jsdmirror.com/gh/sunbigfly/tank99a-video@main/media/tank99a.mp4>
- jsDelivr 转换地址：<https://cdn.jsdelivr.net/gh/sunbigfly/tank99a-video@main/media/tank99a.mp4>

扫码直达视频可使用 `share-qr-jsdmirror.png`。GitHub Pages、JSDMirror 和 jsDelivr 在中国大陆的访问情况取决于用户网络，均无法保证长期可达。
