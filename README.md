# THU2023Summer_FrontEnd_CelestialMotion
THU Web front-end course team assignment in 2023 

using threejs

由于在html中使用type="module"引入js会产生跨域问题（该问题是由于同源策略产生的，建一个本地服务器就可以解决，但是这次项目只需要前端，不需要服务器，所以我没有建）

故需要以下两种解决方案之一

1、
在vscode中下载live server插件，在vscode视图中右键单击index.html文件，选择open with live server打开。

2、
找到chrome.exe的目录文件夹，打开cmd，输入chrome.exe --disable-web-security --user-data-dir=D:\MyChromeUserData打开chrome，得到一个关闭了同源策略的chrome页面，
再打开本地index.html。此举会在D盘中产生一个存放chrome用户信息的MyChromeUserData文件夹。

为了便于观察，以地球公转轨道为基

月球公转轨道放大了40倍

太阳直径放大了29倍

地球直径放大了1252倍

月球直径放大了2297倍

