<h1 class="center">CMSZ001的网站</h1>
<hr>

>**可按快捷键Ctrl+F搜索内容**

<hr>

<div class="demo-theme-preview">
  <a data-theme="vue">vue.css</a>
  <a data-theme="buble">buble.css</a>
  <a data-theme="dark">dark.css</a>
  <a data-theme="pure">pure.css</a>
</div>
<style>
  .demo-theme-preview a {
    padding-right: 10px;
  }

  .demo-theme-preview a:hover {
    cursor: pointer;
    text-decoration: underline;
  }
</style>

<script>
  var preview = Docsify.dom.find('.demo-theme-preview');
  var themes = Docsify.dom.findAll('[rel="stylesheet"]');

  preview.onclick = function (e) {
    var title = e.target.getAttribute('data-theme')

    themes.forEach(function (theme) {
      theme.disabled = theme.title !== title
    });
  };
</script>
<hr>

* #### **网页** ####
	* [百度](https://www.baidu.com)
	* [必应](https://bing.com)
	* [Android In React（安卓网页版）](https://android.blueedge.me)
	* [中小学教材电子版](https://jc.pep.com.cn/)

<hr>

* #### **文件下载** ####
	* [下载源文件](https://github.com/CMSZ001/cmsz001.github.io/archive/refs/heads/main.zip)
