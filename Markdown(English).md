# MarkDown Grammar


## Headings

o create a heading, add one to six `#` symbols before your heading text. The number of # you use will determine the size of the heading.

```
# The largest heading
## The second largest heading
###### The smallest heading
```


![](https://help.github.com/assets/images/help/writing/headings-rendered.png)


## Styling text

You can indicate emphasis with bold, italic, or strikethrough text.

| Style | Syntax | Keyboard shortcut | Example | Output |
| --- | --- | --- | --- | --- |
| Bold | `** **` or `__ __` | command/control + b | `**This is bold text**` | **This is bold text** |
| Italic | `* *` or `_ _` | command/control + i | `*This text is italicized*` | *This text is italicized* |
| Strikethrough | `~~ ~~` |  | `~~This was mistaken text~~` | ~~This was mistaken text~~ |
| Bold and italic | `** **` or `_ _` |  | `**This text is _extremely_ important**` | **This text is _extremely_ important** |

**Node: At least three dashes, `:---` means left-aligned, `:---:` means centered, `---:` means right-aligned**


## Quoting text  

You can quote text with a `>`.

```
In the words of Abraham Lincoln:

> Pardon my French
```


![](https://help.github.com/assets/images/help/writing/quoted-text-rendered.png)


## Quoting code

You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted.

``Use `git status` to list all new or modified files that haven't yet been committed.``


Use `git status` to list all new or modified files that haven't yet been committed.


To format code or text into its own distinct block, use triple backticks.

```
Some basic Git commands are:
\```
git status
git add
git commit
\```
```


![](https://help.github.com/assets/images/help/writing/code-block-rendered.png)

**Node: Please remove `\` where you copy this**


## Links

You can create an inline link by wrapping link text in brackets `[ ]`, and then wrapping the URL in parentheses `( )`. You can also use the keyboard shortcut command + k to create a link.

`This site was built using [GitHub Pages](https://pages.github.com/).`


![](https://help.github.com/assets/images/help/writing/link-rendered.png)


## Lists

You can make a list by preceding one or more lines of text with `-` or `*`.

```
- George Washington
- John Adams
- Thomas Jefferson
```


![](https://help.github.com/assets/images/help/writing/unordered-list-rendered.png)

To order your list, precede each line with a number.

```
1. James Madison
2. James Monroe
3. John Quincy Adams
```


![](https://help.github.com/assets/images/help/writing/ordered-list-rendered.png)

You can create nested lists by indenting lines by two spaces.

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


## Task lists

You can create task lists by prefacing list items with `[ ]`. To mark a task as complete, use `[x]`.

Task lists render with checkboxes in all comments and Markdown files. Select or unselect the checkboxes to mark them as complete or incomplete.

```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
```


![](https://help.github.com/assets/images/help/writing/task-list-rendered.png)


## Mentioning users and teams

You can mention a user or team on GitHub by typing `@` plus their username or team name to bring their attention to an issue or pull request.

`@github/support What do you think about these updates?`


![](https://help.github.com/assets/images/help/writing/mention-rendered.png)


## Using emoji

You can add emoji to your writing by typing `:EMOJICODE:`.

`@octocat :+1: This PR looks great - it's ready to merge! :shipit:`


![](https://help.github.com/assets/images/help/writing/emoji-rendered.png)

For a full list of available emoji and codes, check out [emoji-cheat-sheet.com.](http://emoji-cheat-sheet.com/)。


## Paragraphs and line breaks

You can create a new paragraph by leaving a blank line between lines of text.


## Ignoring Markdown formatting

You can tell GitHub to ignore (or escape) Markdown formatting by using `\` before the Markdown character.

`Let's rename \*our-new-project\* to \*our-old-project\*.`


![](https://help.github.com/assets/images/help/writing/escaped-character-rendered.png)

For more information, see Daring Fireball's "[Markdown Syntax](https://daringfireball.net/projects/markdown/syntax#backslash)"。

Further reading
[About writing and formatting on GitHub](https://help.github.com/articles/about-writing-and-formatting-on-github/)
[Working with advanced formatting](https://help.github.com/articles/working-with-advanced-formatting/)
[Mastering Markdown](https://guides.github.com/features/mastering-markdown
[Markdown Tutorial](http://www.markdowntutorial.com/)
[original text](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
