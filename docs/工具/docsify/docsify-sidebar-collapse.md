![docsify](../../img/工具/docsify/docsify.jpg)

# docsify侧边栏折叠

docsify官网没有提供侧边栏折叠功能，可以通过配置第三方插件的方式实现。

**插件**：[docsify-sidebar-collapse](https://github.com/iPeng6/docsify-sidebar-collapse)

展示效果：

![docsify](../../img/工具/docsify/docsify-sidebar-collapse.gif)

**开启目录**

自定义侧边栏开启目录功能，设置subMaxLevel，根据标题实现内容折叠。

![docsify](../../img/工具/docsify/side_catalog.gif)

```markdown
// js配置
window.$docsify = {
  //...
  subMaxLevel: 2
}

// _sidebar.md
* 前言

	* [介绍](/preface)
	* [使用基础](/use-base.md)

// use-base.md
## 主界面
## 菜单栏
## 工具栏
## 侧边栏
## 图谱区
## 状态栏
```

docsify相比gitbook虽较小众，优势也有不少，简单轻量，推荐使用。

[docsify](https://docsify.js.org/#/)

