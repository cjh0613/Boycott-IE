# Boycott-IE
## English
When an IE browser (including a browser using the IE kernel) accesses a website, it will automatically jump to the browser upgrade prompt page.

It is detected to use IE browser, and it will automatically jump to the prompt page after judging the language

### Instructions:
Add between the `<head></head>` of the webpage source code:
```html
<script src="https://cjh0613.github.io/Boycott-IE/2/boycott-ie.js"></script>
```
Welcome to submit versions in other languages by PR.

The latest code is stored in the "/2" directory, web pages are stored in different folders according to language， and the code in the root directory is for backward compatibility. Please note when you pull request

## 中文
当IE浏览器（包括使用IE内核的浏览器）访问网站的时候将自动跳转到浏览器升级提示页面。

检测到使用IE浏览器，
判断语言后自动跳转到提示页面

### 使用方法：

在网页源代码`<head></head>`间添加（尽量靠前）：
```html
<script src="https://cjh0613.github.io/Boycott-IE/2/boycott-ie.js"></script>
```
最新的代码存放在“/2”目录，网页按照语言存储在不同文件夹，根目录下的代码是为了向下兼容。您pull request 时请注意

 看到这个https://support.dmeng.net/upgrade-your-browser.html
 
 但是没有英文界面，于是开发此多语言版本，欢迎各位PR
