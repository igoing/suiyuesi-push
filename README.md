# suiyuesi-push
岁月司-简单高效的微信消息推送工具

### 官方网站
[suiyuesi.dlnucloud.com](http://suiyuesi.dlnucloud.com)

### 这是什么
我们常常希望用微信来接收一些消息提醒和通知
- 服务器报警消息
- 天气变化消息
- 软件更新消息
- 特别关注博主的最新动态

关注[岁月司]微信公众号，你就可以从公众号中接收这些消息，实时，免费~

### 如何使用
- 打开网站 [suiyuesi.dlnucloud.com](http://suiyuesi.dlnucloud.com)
- 点击页面最上方的[获取二维码]，扫描二维码并关注[岁月司]（消息会通过这个公众号发送）
- 点击[确认绑定]，会获得一个token（注意保密）
- 请求 http://wx.dlnucloud.com/push?content={content}&token={token} ，将{token}替换为上面获取的token，{content}替换为要发送的内容，就可以在微信上收到消息啦
- PS.如果扫描之后提示二维码已失效，刷新页面再试一次吧

### 交流
你可以通过提交issue的方式，表达你的想法，我们会认真倾听，努力让岁月司变得更好
