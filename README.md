# ChatGPT 3.5 单文件版

![](https://lin2025.github.io/img/other-gpt3.5.gif)

## 更新 Updates
- **4月28日** **Add English comments.**
- **4月27日** **新增功能**-**查询OpenAI账号余额** 检测API-Key后，点击[Tokens]查询API账号余额，使用OpenAI官方接口，返回数据包含登记的名字、是否绑卡、总额度、余额、有效期等。代码基于以下两位大佬的项目进行调整实现：@ClarenceDan的[openai-billing](https://github.com/ClarenceDan/openai-billing)、@herobrine19的[openai-billing](https://github.com/herobrine19/openai-billing)，已详细注释，安全透明，数据无泄漏风险。
- **4月26日** 给“检测中“和“发送中“这两按钮状态添加动态效果；页面上不再显示API-Key明码；修正些小错误。
- **4月23日** **重要修复 bug fixes** 修复近期多个国家IP无法访问<kbd>BootCDN</kbd>而导致网页报错的情况（无法加载<kbd>Vue</kbd>与<kbd>Axios</kbd>），已添加<kbd>Unpkg</kbd>CDN线路，<kbd>BootCDN</kbd>挂掉的时候会自动切换到<kbd>Unpkg</kbd>。
- **4月16日** 修改PC端的快捷键，改为回车<kbd>Enter</kbd>发送，并支持多种换行方式。适配中文输入习惯，中文输入状态下，一次回车**确认但不发送**，二次回车**才会发送**。
- ...


## :globe_with_meridians:
A ChatGPT web page is a lightweight single-page chat application that can be deployed statically, with no need for a server.

Download and open the <kbd>index.html</kbd> file, input your OpenAI <kbd>API-Key</kbd> to get started. Functions include: Check <kbd>OpenAI API</kbd> balances, System prompts, Context, Adjustable temperature settings, Undo, Retry, Clear context, Token count, and Export chat history.

> <kbd>先检测API</kbd>_:Check API first_    <kbd><<检测</kbd>_:Check API-key_    <kbd>发送</kbd>_:Send_    <kbd><<写入指令</kbd>_:Save system prompt_    <kbd>Tokens</kbd>_:Token count_    <kbd>Tokens点击查API余额</kbd>_:(Click)_ _Check OpenAI API balances_    <kbd>清空</kbd>_:Clear context_    <kbd>撤销</kbd>_:Undo_    <kbd>重问</kbd>_:Retry_    <kbd>说明</kbd>_:Help_    <kbd>导出对话</kbd>_:Export chat history_  _..., others are in the code comments._ 


## 介绍
 零门槛 10秒就能搞定的GPT3.5 <kbd>模型:gpt-3.5-turbo</kbd> 

> 静态网页 无依赖 无需部署 **仅一个html文件** 打开即用 超级简单

 **在线体验：** [https://lin2025.gitee.io/gpt3.5/](https://lin2025.gitee.io/gpt3.5/) 或 [https://lin2025.github.io/gpt3.5/](https://lin2025.github.io/gpt3.5/)

 **下载方式汇总（含网盘）：** [https://lin2025.gitee.io/#gpt3.5-code](https://lin2025.gitee.io/#gpt3.5-code)


## 功能
 需使用自己的<kbd>API-Key</kbd> / 查询<kbd>OpenAI API</kbd>账号余额 / 上下文记忆 / <kbd>token</kbd>统计 / 撤销问答 / 重新回答 / 清空记忆
 / 可调"创造力·温度"<kbd>temperature</kbd> / 可设置"指令·系统提示词"<kbd>system</kbd> / 可导出"聊天记录·操作记录"
 / 对话框自适应高度
 / 电脑端按回车<kbd>Enter</kbd>发送 支持多种换行方式<kbd>Shift | Ctrl | Cmd</kbd>+<kbd>Enter</kbd>

> 回复是一次返回，非<kbd>Stream</kbd>流式，不存在中断的情况


## 特点
 无门槛 / 便捷 / 一秒复制一个 / 一分钟轻松定制成AI小工具 / 不用担心挤不上官网 / 无需登录 / 无泄漏风险 / 适合轻中度使用场景

> 使用<kbd>记事本</kbd>或<kbd>文本编辑.app</kbd>即可改代码 修改教程已写在代码里 无需懂技术 人人都会改


## 缺点
 使用ChatGPT官方接口 **国内需使用魔法**


## 欢迎交流
 **B站**@[林同学不姓林](https://space.bilibili.com/3493262545389917) **抖音**@[林同学不姓林](https://www.douyin.com/user/MS4wLjABAAAAVBMwb4AQWZt3xkbgvVS4FYCuQ2xzHCU9LgSX4vJz_n76JK62kQGEfHjYjzrOCHs7)

 **提示词导航·分享** [https://lin2025.gitee.io/#zhiling](https://lin2025.gitee.io/#zhiling)

 **林同学的小站（域名跳转Gitee）** [LinTongXue.com](http://LinTongXue.com)
