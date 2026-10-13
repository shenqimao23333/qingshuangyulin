# 一纸榆林

原生 HTML / CSS / JavaScript / SVG 竖屏互动叙事游戏。

## 使用
将 dist 目录整体上传到任意静态网站托管服务；网站入口为 index.html。
本地调试可在 dist 运行 `npx serve .`。游戏保存进度依赖浏览器 localStorage。

## 内容
序章折纸与路径剪刻、边塞剪刻、窑洞窗花拼贴、秧歌拼绸与跟拍、声音纸带互动、终章纹样拼合，以及个人 PNG 海报和横版图导出。
声音使用 Web Audio 合成音色，非传统唢呐曲目实录；旁白使用设备中文语音合成，浏览器支持情况可能不同。

## 文件
- dist/index.html：入口
- dist/style.css：手机布局与纸艺视觉
- dist/app.js：章节内容、交互引擎、进度与导出
- dist/landscape.png：使用内置 imagegen 生成的纸艺主视觉

## 文化来源
- https://ich.unesco.org/en/RL/chinese-paper-cut-00219
- https://yl.gov.cn/mlyl/zjyl/fjms/202009/t20200928_18048.html
- https://www.ihchina.cn/project_details/12520.html

文化场景为艺术化创作。浏览器完整流程及真机触摸尚未完成验证，发布被环境审批阻断。
