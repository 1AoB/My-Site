fork过来的仓库没有Issues菜单栏

但是可以有如下解决办法,来打开issues:

如果你 fork 的仓库是公开的并且没有禁用 Issues，你可以自己启用 Issues 功能。在 GitHub 仓库的 Settings（设置）页面中，找到 Issues 选项，确保 Issues 功能是启用的。

具体步骤：

1.打开你 fork 的 GitHub 仓库。

2.进入 Settings（仓库设置）页面。

3.在左侧的 Features 部分，确保 Issues 选项被勾选启用。

4.如果启用了 Issues，通常可以在每篇博客文章下方创建一个新的 issue 作为评论。


Server:    https://app.netlify.com/


```js
还不知道在哪里补充一下内容:
我估计是在这里:
https://github.com/1AoB/My-Site/blob/master/layouts/partials/footer/footer.html

<script src="https://utteranc.es/client.js"
        repo="1AoB/My-Site"
        issue-term="pathname"
        theme="github-dark"
        crossorigin="anonymous"
        async>
</script>
```
![image](https://github.com/user-attachments/assets/4e756cbe-9ef2-42a5-82af-79d033ce1bec)


https://utteranc.es/ 确实还不错,但是官方提供的例子只可以发消息却不可以回复消息,
最后选择了 https://giscus.app/zh-CN ,这个既可以发消息还可以回复消息!

![image](https://github.com/user-attachments/assets/4e814a07-e323-41c6-9be3-5bf2b5d06e92)

------------------------------------------------

![image](https://user-images.githubusercontent.com/5889006/190859441-141b5f81-8483-40d2-bd96-ebf85616a46d.png)


# Hugo Theme Stack

<img align="right" width="150" alt="logo" src="https://user-images.githubusercontent.com/5889006/190859553-5b229b4f-c476-4cbd-928f-890f5265ca4c.png">

Card-style Hugo theme designed for bloggers.

## Quickstart

Use this template: [CaiJimmy/hugo-theme-stack-starter](https://github.com/CaiJimmy/hugo-theme-stack-starter)

## Demo

* Starter template demo: [demo.stack.jimmycai.com](https://demo.stack.jimmycai.com)
* Dev build: [dev.stack.jimmycai.com](https://dev.stack.jimmycai.com)

## Documentation

Visit [stack.jimmycai.com](https://stack.jimmycai.com)

## Copyright

**Licensed under the GNU General Public License v3.0**

Please do not remove the "*Theme Stack designed by Jimmy*" text and link.

If you want to port this theme to another blogging platform, please let me know🙏.
