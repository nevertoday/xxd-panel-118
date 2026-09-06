# Panel 118 运行适配器

每次生成前完整读取 `references/original-prompt/zh-CN.md`，它是唯一创作与审美权威。译文与本适配器都不替代原文。

- 模式：`top-bottom`、`left-right`、`design-only`、`wallpaper-pack`。
- `top-bottom`：仅两个全宽区域，上原图、下石墨插画，严格 50:50。
- `left-right`：仅覆盖原文上下位置，改为两个全高区域，左原图、右插画，严格 50:50；不保留嵌套上下分区或第三带。
- `design-only`：只显示重构插画，原图仅为参考。
- `wallpaper-pack`：手机、iPad、桌面、手表完整设计，明确 `linked` 或 `independent` 及各端尺寸。
- 文字：`prompt`、`exact`、`none`；明确语言。少量文案来自当前图像，不指定字体或标题模板；样张采用英文智能文案。
- 尺寸：`auto`、`source`、常用或自定义比例、准确像素。明确交付要求覆盖原文 3:4 默认比例，不改变石墨美学。
- 输入：单图或隔离目录批量。每份成品从当前原图单轮生成整张画布，不对中间设计二次处理。
