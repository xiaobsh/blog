每次都要更改蓝奏云分享链接中的 “www.lanzous.com” 为 “ww.lanzous.com” ，麻烦，改 Hosts 有效果，但写个脚本不香么。
## 蓝奏云访问
### 用到的命令和参数
`window.location.href`：当前页面的 URL
`字符串.replace(查找文本, 替换文本)`：字符串文本替换，原字符串对象不改变，返回修改后的字符串。
`var 变量 = XX 类型的值`：声明时赋的值是什么类型，这个变量就是什么类型（人家 Batch 多好，变量不分类型，也不用声明，或者说每次赋值都在声明）。

然后就没了。。。

### 代码

```javascript
// 代码
window.location.href = (window.location.href).replace("://www.lanzous.com/", "://ww.lanzous.com/");

// 分解
var url = window.location.href;
// 以字符串类型声明变量 url ，同时为其赋值为分享链接的 URL 。
url = url.replace("://www.lanzous.com/", "://ww.lanzous.com/");
// 将分享链接中的 “://www.lanzous.com/” 替换为 “://ww.lanzous.com/” 。
window.location.href = url;
// 网页跳转
```




CSDN 的 JavaScript 代码片高亮用 “```JavaScript”不行，

用“```javascript”就行了……还有中文标点符号用全角它不香么。

