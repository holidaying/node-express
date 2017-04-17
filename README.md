* node搭建服务器环境
 * 利用express来搭建服务 npm install -g express
```
npm install -g express
```
 * 建立项目
```
express project
``` 
 * 建立项目并install,执行npm start
```
cd project,npm install,npm start
``` 
 * 安装ejs修改解析的模板
```
npm install ejs
修改app文件把jade修改成html解析模板
var ejs = require('ejs'); app.engine('html', ejs.__express);app.set('view engine', 'html');
``` 
  * 把你的代码放到views里面，启动浏览器访问：http://localhost:3000/
![Paste_Image.png](https://user-gold-cdn.xitu.io/2017/4/17/8fa5921e763150ac95eade6382a6f372)
