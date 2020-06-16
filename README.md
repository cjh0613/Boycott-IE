# Boycott-IE
## English
When an IE browser (including a browser using the IE kernel) accesses a website, it will automatically jump to the browser upgrade prompt page.

It is detected to use IE browser, and it will automatically jump to the prompt page after judging the language

### Instructions:
Add between the <head></head> of the webpage source code:
```html
<script>if (/*@cc_on!@*/false || (!!window.MSInputMethodContext && !!document.documentMode)){var lang = navigator.language||navigator.userLanguage;lang = lang.substr(0, 2);if(lang == 'zh'){window.location.href="https://cjh0613.github.io/Boycott-IE/upgrade-your-browser/zh-cn.html";}
 else{window.location.href="https://cjh0613.github.io/Boycott-IE/upgrade-your-browser/en.html"}}</script>
```

## 中文
当IE浏览器（包括使用IE内核的浏览器）访问网站的时候将自动跳转到浏览器升级提示页面。

检测到使用IE浏览器，
判断语言后自动跳转到提示页面

### 使用方法：

在网页源代码`<head></head>`间添加：
```html
<script>if (/*@cc_on!@*/false || (!!window.MSInputMethodContext && !!document.documentMode)){var lang = navigator.language||navigator.userLanguage;lang = lang.substr(0, 2);if(lang == 'zh'){window.location.href="https://cjh0613.github.io/Boycott-IE/upgrade-your-browser/zh-cn.html";}
 else{window.location.href="https://cjh0613.github.io/Boycott-IE/upgrade-your-browser/en.html"}}</script>
```

 看到这个https://support.dmeng.net/upgrade-your-browser.html
 
 但是没有英文界面，也在此基础上添加了其他功能
