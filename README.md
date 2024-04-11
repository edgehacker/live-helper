<div align="center">
<br/>
<img src="https://livehelper.willwaking.com/img/icon.0f219fdf.jpg" width="300"/>
<br/>
<br/>
<p>
兼容大部分主流平台、模块化设计、可视化编写流程的直播互动助手<br/>
由 Node.js、Vue3、Electron 提供强大驱动
</p>
<br/>
<p>
当前兼容平台：
<strong>抖音</strong> ·
<strong>BiliBili</strong> ·
<strong>快手视频</strong> ·
<strong>TikTok</strong> ·
<strong>淘宝直播</strong> ·
<strong>AcFun</strong> ·
<strong>斗鱼</strong> ·
<strong>支付宝直播</strong> ·
<strong>微信视频号</strong>
</p>
<br/>
</div>

### 功能支持

- [x] 并发安全异步式任务
- [x] 多平台多事件捕获、捕获起止控制、实时弹幕礼物日志、直播间代理设置（TikTok需要代理）
- [x] 基于自定义正则表达式的弹幕匹配
- [x] 带优先级的多个任务队列、队列起止控制
- [x] 可视化任务触发流程设置、直播间事件模拟、实时任务运行调试、调试沙箱
- [x] 任意屏幕位置、可中断可重叠、支持层级设置的图像放映、视频放映、自定义DOM放映
- [x] 拖拽式可视化悬浮提示（文字、图像、iframe自定义网页）
- [x] 基于串口的硬件控制
- [x] 鼠标键盘动作录制、键鼠动作驱动级重播、3D游戏人物镜头控制
- [x] 带情绪设置支持的阿里语音合成
- [x] 事件 Api、资源 Api、动画显示控制 Api
- [x] 模块化高自定义任务、多任务并发、带判断读写的可编程任务树
- [x] 公会账号模式（可多地登录及拉取云端设置数据，但需要二级密码才能修改云端设置数据）
- [x] 定时任务
- [x] 代理分销
- [x] 多场景创建支持，玩法独立设置，多设备同时在线且各自启用不同场景（仅限公会模式）
- [x] Ai语音合成
- [x] 声音克隆

### 图像 / 视频 / 音频媒体节点

|节点类型|图像动画|视频动画|音频节点|元素动画|
|--|:-:|:-:|:-:|:-:|
|文件位置|本地 / 网络|本地/网络|本地 / 网络 / 合成|本地 / 网络|
|可重复堆叠|√|√|√|√|
|堆叠层级控制|√|√|无层级|√|
|批量移除|√|√|√|√|
|指定移除|√|√|√|√|
|自定义显示位置|√|√|无位置|√|
|自定义显示宽高|√|√|无宽高|√|
|自定义播放时间|√|√|√|√|
|并发同时播放|√|√|√|√|
|投入队列排队播放|√|√|√|√|
|CSS动画|√|√|无动画|√|

### 功能节点说明

|节点类型|是否支持|描述|
|--|:-:|:-:|
|硬件控制|√|基于串口，可自由开发|
|键鼠模拟|√|驱动级录制重播|
|语音合成|√|自定义情绪、发言人等|
|直播间回复消息|√|支持多个变量|
|网络请求|√|支持多个变量，方便开发|
|写用户值|√|覆盖 / 追加 / 累和|
|写变量值|√|覆盖 / 追加 / 累和动态刷新悬浮提示|
|改先前任务优先级|√|可实现礼物插队|
|锁定账户|√|使电脑"息屏"|
|结束进程|√|结束游戏整蛊|
|随机节点|√|可自定义相对概率|
|并行节点|√|使后续多个任务同时执行|
|数值判断|√|实现更复杂的效果|
|倍数判断|√|支持多个变量|
|文本判断|√||

### 程序界面速览

![1](https://github.com/edgehacker/live-helper/assets/157565442/abda05b2-3864-4bb9-bef5-5f60b7c53e7c)

![2](https://github.com/edgehacker/live-helper/assets/157565442/6b5c46a2-321d-4421-8c1b-4c24b93d622e)

![3](https://github.com/edgehacker/live-helper/assets/157565442/ec36f86b-0f70-4155-a024-14822c39c396)

![4](https://github.com/edgehacker/live-helper/assets/157565442/c4459cc3-f7a8-4044-85da-fd5133263408)

![5](https://github.com/edgehacker/live-helper/assets/157565442/6079f9f0-0057-4d11-a18a-3341b7165545)

![6](https://github.com/edgehacker/live-helper/assets/157565442/6e26dbb5-46e8-4839-a85b-b3ac515b6c1c)

![7](https://github.com/edgehacker/live-helper/assets/157565442/9b1b8c25-3da1-4b6a-b54c-6769fcdee9bd)

![8](https://github.com/edgehacker/live-helper/assets/157565442/e2472402-8a2c-43f7-8b8f-1aac6cd42987)

![9](https://github.com/edgehacker/live-helper/assets/157565442/8bf9b30e-95c3-4679-8919-0a140799692c)

![10](https://github.com/edgehacker/live-helper/assets/157565442/f1b500fd-d901-41fa-9d6e-624b668c2eca)

![11](https://github.com/edgehacker/live-helper/assets/157565442/7278f308-9529-4e66-8013-51fb9f3324f0)

![12](https://github.com/edgehacker/live-helper/assets/157565442/e958e9b6-64bb-423e-a7c0-6f2ebada562e)

![13](https://github.com/edgehacker/live-helper/assets/157565442/ee62f866-d198-4865-8ba9-bf06846b0e5c)

![14](https://github.com/edgehacker/live-helper/assets/157565442/64ffb315-1906-43ec-b98b-8f723399ffdc)
