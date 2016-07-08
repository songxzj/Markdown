# MarkDown 语法


## 标题

创建标题，在标题前增加1到6个 `#`，你使用的 `#` 的个数将确定标题的大小。

```
# The largest heading
## The second largest heading
###### The smallest heading
```


![](https://help.github.com/assets/images/help/writing/headings-rendered.png)


## 文字样式

你可以用粗体，斜体，或者删除线来强调文字。

| 样式 | 语法 | 键盘快捷键 | 例子 | 样例 |
| --- | --- | --- | --- | --- |
| 粗体 | `** **` 或者 `__ __` | command/control + b | `**This is bold text**` | **This is bold text** |
| 斜体 | `* *` 或者 `_ _` | command/control + i | `*This text is italicized*` | *This text is italicized* |
| 删除线 | `~~ ~~` |  | `~~This was mistaken text~~` | ~~This was mistaken text~~ |
| 粗体和斜体 | `** **` 和 `_ _` |  | `**This text is _extremely_ important**` | **This text is _extremely_ important** |

**注： 横线至少三条，`:---` 表示左对齐，`:---:` 表示剧中对齐，`---：`表示右对齐**


## 引用文本  

你可以用 `>` 来引用文本。

```
In the words of Abraham Lincoln:

> Pardon my French
```


![](https://help.github.com/assets/images/help/writing/quoted-text-rendered.png)


## 引用代码

你可以用一对反引号来输出代码或者是命令行，反引号里的将不会被执行。

``Use `git status` to list all new or modified files that haven't yet been committed.``


Use `git status` to list all new or modified files that haven't yet been committed.


引用的代码或命令行要保留原有的格式，用三个反引号。

```
Some basic Git commands are:
\```
git status
git add
git commit
\```
```


![](https://help.github.com/assets/images/help/writing/code-block-rendered.png)

**注意：复制时请把 `\` 去掉**


## 链接

你可以创建一个内置的链接通过在中括号 `[ ]` 里写文本，在小括号 `( )` 里写链接。

`This site was built using [GitHub Pages](https://pages.github.com/).`


![](https://help.github.com/assets/images/help/writing/link-rendered.png)


## 列表

你可以制作一个列表通过在文本前面添加 `-` 或 `*`。

```
- George Washington
- John Adams
- Thomas Jefferson
```


![](https://help.github.com/assets/images/help/writing/unordered-list-rendered.png)

要列表排序，在每一行前面加数字。

```
1. James Madison
2. James Monroe
3. John Quincy Adams
```


![](https://help.github.com/assets/images/help/writing/ordered-list-rendered.png)

你也可以创建嵌套的列表通过两个空格缩进。

```
1. Make my changes
  1. Fix bug
  2. Improve formatting
    * Make the headings bigger
2. Push my commits to GitHub
3. Open a pull request
  * Describe my changes
  * Mention all the members of my team
    * Ask for feedback
```


![](https://help.github.com/assets/images/help/writing/nested-list-rendered.png)


## 任务链表

你可以创建任务列表通过在前面加上 `[ ]`。如果任务完成了，用 `[x]`。

任务列表在所有的Markdown文件和注释都给予了复选框。选择或不选择复选框使得完成或不完成。

```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
```


![](https://help.github.com/assets/images/help/writing/task-list-rendered.png)


## 提到用户和团队

你可以在 GitHub 上提到一个用户和团队通过 `@` 加他们的用户名或者团队名使得他们来关注 issue 或者 pull request。

`@github/support What do you think about these updates?`


![](https://help.github.com/assets/images/help/writing/mention-rendered.png)


## 应用表情符号

你可以在你的文本里通过 `:EMOJICODE:` 添加表情符号。

`@octocat :+1: This PR looks great - it's ready to merge! :shipit:`


![](https://help.github.com/assets/images/help/writing/emoji-rendered.png)

有关可用的表情符号和相关代码的完整列表，请转到 [emoji-cheat-sheet.com.](http://emoji-cheat-sheet.com/)。


## 段落和换行

你可以通过在两段文字之间空一行来创建一个新的段落。


## 忽略 Markdown 转义

你可以告诉 Github 去忽略 Markdown 转义通过在 Markdown 字符前加 `\` 。

`Let's rename \*our-new-project\* to \*our-old-project\*.`


![](https://help.github.com/assets/images/help/writing/escaped-character-rendered.png)

得到更多信息，看 Daring Fireball 的 "[Markdown Syntax](https://daringfireball.net/projects/markdown/syntax#backslash)"。


[github原文](https://help.github.com/categories/writing-on-github/)  
[Markdown 语法说明 (简体中文版)](http://wowubuntu.com/markdown/)  
[献给写作者的 Markdown 新手指南](http://www.jianshu.com/p/q81RER)
