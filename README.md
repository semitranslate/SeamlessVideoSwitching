## 视频无缝切换 Seamless video switching
### 作用描述
用于在网页上无缝切换多个透明视频，不再出现闪烁或跳帧，背景也不会穿帮。
<br>Used for seamless switching between multiple transparent videos on a web page, with no more flickering, frame skipping, or background exposure issues.

[Demo](https://semitranslate.github.io/SeamlessVideoSwitching/)

### 无缝视频切换 (v1+v2=v3)
仅使用一个组合视频文件 (v3)，通过控制其播放区间来实现静态部分 (v1) 和动态部分 (v2) 之间的绝对无缝切换。
#### 操作说明：
1. 准备一个名为 <code>v3.webm</code> 的视频文件 (即您的 v3)。
2. 在下方的 JavaScript 代码中，将 <code>STATIC_DURATION</code> 的值设置为您的静态部分 (v1) 的准确时长（秒）。
3. 鼠标未进入容器区域，视频的v1部分循环播放。
4. 鼠标进入容器区域，视频从当前帧往后循环播放视频。