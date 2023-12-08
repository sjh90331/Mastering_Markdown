# Basics of Markdown

## Headers
Headers are used to create titles and subtitles. You can create a header by using the `#` symbol followed by a space and the header text. The number of `#` symbols indicates the header level. 
For example, `# Header 1`, `## Header 2`, `### Header 3`.
# This is H1 Heading
## This is H2 Heading
### This is H3 Heading

## Emphasis
You can emphasize text by making it bold or italic. Use `*` or `_` for italics (for example, `*italic*` or `_italic_`) and `**` or `__` for bold (for example, `**bold**` or `__bold__`). You can also combine them to create bold and italic text (for example, `**_bold and italic_**`).

## Lists
You can create unordered lists using `*`, `-`, or `+` and ordered lists using numbers followed by a period. For example: 

* Item 1
* Item 2
* Item 3

or

1. Item 1
2. Item 2
3. Item 3


## Links
You can create links using the format `link text`. For example, `GitHub` will create a link to GitHub.

## Images
Images are similar to links but they include a `!` at the beginning. The format is `!alt text`. The alt text will be displayed if the image cannot be loaded.

## Code and Syntax Highlighting
You can create inline code by wrapping the text in backticks (\`). For example, \`code\`. You can create code blocks by wrapping the text in triple backticks (```). If you specify a language after the opening backticks, it will also provide syntax highlighting.

So let's say I want to share code about Fizzbuzz. For example,
```
for i in range (1, 101) :
    if i % 3==0 and i % 5 == 0 :
        print ("fizzbuzz")
    elif i % 3 == 0 :
        print ("fizz")
    elif i % 5 == 0 :
        print ("buzz")
    else : 
        print(i)
```
Just like this, you can create Code syntax by using (''')

## Blockquotes
You can create blockquotes using the `>` symbol. For example, `> This is a blockquote.`

Back to [README](https://github.com/sjh90331/Mastering_Markdown/blob/main/README.md)https://github.com/sjh90331/Mastering_Markdown/blob/main/README.md | Next: Advanced
