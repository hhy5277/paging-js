# 指引

> 使用一个组件或模块之前，应当知道它能解决的问题是什么，不能解决的问题是什么。使用的最佳实践是什么？


分页生成在 Web 开发中非常常见，市面上也存在很多用于生成分页的分页函数。但都难以做到**完全自定义界面**。

> 这里的完全自定义界面指的是分页生成的 HTML 不限制为 `<li class="paging-item">` 或 `<a class="paging-item">`

Paging 提供了一套基于模板渲染的分页生成方案，不限编程语言不限模板引擎类型。基于模板引擎实现的分页可以做到 **完全自定义界面**

其他语言实现方式请访问： [paging](https://github.com/onface/paging)

<!--
示例：

`button.react` 实现了按钮常见的视觉风格，实心、空心、虚线、禁用、加载中、按钮组、图标按钮。默认提供了三种尺寸。

但是不同项目的按钮视觉风格都不一样，不可能项目中直接使用 `button.react` 提供的样式。所以 `button.react` 提供了自定义样式的方式。通过修改格式清晰的 `less` 文件改变视觉风格。只需要修改几个变量，就可以与使用者项目中的按钮样式一致。

并且提供了优雅的 API，使用者不需要重新设计调用按钮的 API。常见的按钮类型 `button.react` 都已考虑到。

-->
