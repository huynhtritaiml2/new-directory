# 1. Text, bold, italic, link to word  
It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)
# 1.1 Headers

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
# 1.2 Emphasis
*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also be bold__

_You **can** combine them_

# 2. Lists 
# 2.1 Ordered
Sometimes you want numbered lists: 
> NOTE: we use "Triple Space" f

1. One
   1. 1.1
      1. 1.1.1
         1. 1.1.1.1
   1. 1.2
      1. 1.2.1
      1. 1.2.2
2. Two
3. Three

example:
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   
   
# 2.2 Unordered
Sometimes you want bullet points:

* Start a line with a star
* Profit!

Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this

Example: 
* Item 1
* Item 2
  * Item 2a
  * Item 2b
    - Item 2b.1
    - Item 2b.2
      
# 3. Image 
If you want to embed images, this is how you do it:

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

Example: 

![GitHub Logo](/images/logo.png)
Format: ![Alt Text](https://www.google.com/search?q=git+logo&client=ubuntu&hs=98X&sxsrf=ALeKk011w0sg5axT-C1y_RuBL0-ZQlpAmw:1603270831170&source=lnms&tbm=isch&sa=X&ved=2ahUKEwi_kvuiqcXsAhUvyosBHR0aBdgQ_AUoAXoECAMQAw&biw=1280&bih=617#imgrc=ZddH2hVhNNICvM)

# 4. Links
http://github.com - automatic!
[GitHub](http://github.com)

# 5. Blockquotes

# Structured documents

Sometimes it's useful to have different levels of headings to structure your documents. Start lines with a `#` to create headings. Multiple `##` in a row denote smaller heading sizes.

### This is a third-tier heading

You can use one `#` all the way up to `######` six for different heading sizes.

If you'd like to quote someone, use the > character before the line:

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

Exampel:

As Kanye West said:

> We're living the future so
> the present is our past.

# 6. Code
There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

GitHub also supports something called code fencing, which allows for multiple lines without indentation:

```
if (isAwesome){
  return true
}
```

And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome){
  return true
}
```
You can also simply indent your code by four spaces:

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    
Here’s an example of Python code without syntax highlighting:

def foo():
    if not bar:
        return True

Example: 
Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```



# 6.1 Inline code
I think you should use an
`<addr>` element here instead.

# 7. Task Lists
GitHub supports many extras in Markdown that help you reference and link to people. If you ever want to direct a comment at someone, you can prefix their name with an @ symbol: Hey @kneath — love your sweater!

But I have to admit, tasks lists are my favorite:

- [x] This is a complete item
- [ ] This is an incomplete item

When you include a task list in the first comment of an Issue, you will see a helpful progress bar in your list of issues. It works in Pull Requests, too!

And, of course emoji!


Example:

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

# 8. Tables:
You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

# 9. SHA references ???????????????????????????// :)) Fucking :rofl: :rofl: :rofl:

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

# 9.1 Issue references within a repository ????????????????????????/ Donot Working :joy: :joy: :joy:

Any number that refers to an Issue or Pull Request will be automatically converted into a link.

#1
mojombo#1
mojombo/github-flavored-markdown#1

# 10. Username @mentions
Typing an `@` symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

# 11. Automatic linking for URLs
Any URL (like `http://www.github.com/`) will be automatically converted into a clickable link.

# 12. Strikethroughth
If we use `~~` this and  `~~` 

Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

# 13. Emoji

GitHub supports [emoji!](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax#using-emoji)

To see a list of every image we support, check out the [Emoji Cheat Sheet.](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
