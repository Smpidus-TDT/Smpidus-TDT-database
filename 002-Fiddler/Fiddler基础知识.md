Fiddler是一个HTTP协议的调试代理工具（基于Windows系统的专用代理服务器软件）。它能够记录并检查所有的电脑和互联网的HTTP通讯，设置断点，查看所有的“进出”Fiddler的数据。

**1.Fiddler的工作原理**

Fiddler作为一种代理服务器软件，其核心就是作为代理服务器。
几乎所有使用网络协议的程序都支持代理服务器，因此Fiddler几乎适用于所有应用。作为系统代理，当启动Fiddler来捕获请求和响应时，Fiddler会自动注册为Windows Internet（WinInet）网络服务代理。这样，所有的来自微软互联网服务（WinInet）的HTTP请求在到达目标Web服务器的之前都会经过Fiddler。同样的，所有的HTTP响应都会在返回客户端之前流经Fiddler。
Internet Explorer《--》WinINET《--》Fiddler《-|-》Web Server