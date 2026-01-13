# bilibili-
教大家如何在bilibili绕过登录弹窗
首先,下载uBlock origin
配图如下啊<img width="418" height="648" alt="image" src="https://github.com/user-attachments/assets/7a09f1ee-f854-4d29-9d08-81f6bed2586a" />
在设置->自定义中设置如下
www.bilibili.com##html,body:style(filter:none!important)
www.bilibili.com##video:style(filter:none!important)
www.bilibili.com##.bpx-player-container:style(filter:none!important)
www.bilibili.com##.bili-player-video-wrap:style(filter:none!important)
www.bilibili.com##.bili-mini-mask
www.bilibili.com##.unlogin-popover
实例:<img width="1300" height="725" alt="image" src="https://github.com/user-attachments/assets/e30bd8a6-d266-4e00-9068-194dd1a0145c" />
,其次,下载adblock或者任意广告拦截
右键弹窗,选择区域,设置屏蔽即可
