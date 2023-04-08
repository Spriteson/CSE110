# Markdown
This site was the markdown page [Markdown Pages](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

## Heading
I can use `#` or `##` or `###` for heading
```
# A first-level heading 
## A second-level heading
### A third-level heading
```

# A first-level heading 
## A second-level heading
### A third-level heading

## Styling
**Bold** `** **` or `__ __`

*Italic*  `* *` or `_ _`

~~Strikethrough~~ `~~ ~~`

**Bold and nested _italic_** use `** **` and `_ _`

***All bold and italic*** use `*** ***`

<sub>This is a subscript text</sub>  use`<sub>` and `</sub>`

<sup>This is a superscript text</sup> sup and /sup on <>

## Quoting text
Quoted text is indented, with a different type color.
I can quote text with a `>`.
> Text that is a quote

## Quoting code
I can use ``` on the top and the end to quote a code. 
or ```Command```+```E```
or ` between text

## External Links
I can create an inline link by wrapping link text in brackets `[ ]` , and then wrapping the URL in parentheses `( )`.or `commnd` + `K`

I can also create a Markdown hyperlink by highlighting the text and using the keyboard shortcut `Command`+`V`

`This site was built using [GitHub Pages](https://pages.github.com/).`
This site was built using [GitHub Pages](https://pages.github.com/).

## Section links
I can link directly to a section in a rendered file by hovering over the section heading to expos.
Use [] and (#)
`[Styling](#Styling)`
[Styling](#Styling) 

## Relative links
I can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.
`[Contribution guidelines for this project](docs/CONTRIBUTING.md)`

## Image
I can display an image by adding `!` and wrapping the alt text in `[ ]`. Alt text is a short text equivalent of the information in the image. Then, wrap the link for the image in parentheses `()`.

`![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)`

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

## Ordered and Unordered Lists
I can make an unordered list by preceding one or more lines of text with `-`, `*`, or `+`.
I can also use `1.`, `2.`, and `3.`
I can also use nested list and use indent `Tab`
```
1. First list item
   - First nested list item
     - Second nested list item
```
1. First list item
   - First nested list item
     - Second nested list item

 I could add a nested list item under the list item 100. use `␣␣␣␣␣-␣` before the nested list content `First nested`

 ```
 1.   First list item
      - First nested list item
 ```

 1.   First list item
      - First nested list item

## Task lists
I can create a task list, preface list items with a hyphen and space followed by [ ]. To mark a task as complete, use [x].

```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

If a task list item description begins with a parenthesis, you'll need to escape it with `\`:

`- [ ] \(Optional) Open a followup issue`
