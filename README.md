<h3>字符拼接类错误：</h3>
(1)js函数不调用 Uncaught SyntaxError: missing ) after argument list</br>
 onclick函数参数问题，参数是String时要用**转义符**（尤其是在跟ajax一起用时）
```js
 out.println("<span id='"+value+"' onclick='showContent("+ptostr+")'><font color='green'>" + value + "</font></span>");
 html.append('<td><a href="#" onclick=\"searchPlus(\''+allcontent+'\');return false;\"></a></td>');
 ```
