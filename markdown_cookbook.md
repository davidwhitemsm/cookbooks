# Markdown Cookbook  

**Adapted from [*The Markdown Guide*](https://www.markdownguide.org/book) by Matt Cone**

***

## 01. Headings & Paragraphs

```markdown
<!-- heading syntax -->

# Heading 1  
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6 
```

***
`heading examples`

# Heading 1  

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6  

***

## 02. Emphasis

```markdown
<!-- emphasis syntax -->

**bold**

*italic*

***bold and italic***

~~strikethourgh~~
```

***
`emphasis examples`

**bold**

*italic*

***bold and italic***

~~strikethourgh~~
***

## 03. Horizontal Rules

```markdown
<!-- horizontal rule syntax -->

***
```

`horizontal rule example`
***

## 04. Block Quotes

```markdown
<!-- block quote syntax -->


> single-line block quote  

‎  

> multi-line
> block
> quote   

‎


> multi-line
> block  
> quote with
>
> space    

‎

> multi-line
> block
> quote with
>> nested text within
>>
> the larger block quote
```

***

`block quote examples`

> single-line block quote  

‎

> multi-line
> block
> quote  

‎
> multi-line
> block  
> quote with
>
> space  

‎

> multi-line
> block
> quote with
>> nested text within
>>
> the larger block quote

***

## 05. Code Blocks

### Inline Code

```markdown
<!-- inline code syntax -->
enclose `code` in backticks
```

`inline code example`

enclose `code` in backticks

### Code Fences

```markdown
<!-- code fence syntax -->
 - three backticks (```) followed by the name of the programming language
 - your code snippet
 - three backticks

<!-- If the word or phrase you want to denote as code includes backticks, escape it by enclosing the entire line in double backticks

For example:
``Use `code` in your markdown file.`` -->
```

`code fence example`

```sql
SELECT *
FROM table1
LEFT JOIN table2
ON id.table1 = id.table2
WHERE state = NY
LIMIT 1000
```

***

## 06. Lists

### Ordered Lists

```markdown
<!-- ordered list syntax -->
1. first item
1. second item
1. third item
    1. indented item 1
    1. indented item 2
1. fourth item
```

`ordered list example`

1. first item
1. second item
1. third item
    1. indented item 1
    1. indented item 2
1. fourth item

### Unordered Lists

```markdown
<!-- unordered list syntax -->
- first item
- second item
- third item
    - indented item 1
    - indented item 2
        - double-indented item 1
        - double-indented item 2
- fourth item
<!-- if you need to start an unordered list item with a number followed by a period, you can use backslash (\) to escape the period -->
```

`unordered list example`

- first item
- second item
- third item
    - indented item 1
    - indented item 2
        - double-indented item 1
        - double-indented item 2
- fourth item

### Checklists

```markdown
<!-- checklist syntax -->

- [x] ballot box with check
- [x] ballot box with check
- [ ] ballot box without check
```

`checklist example`

- [x] ballot box with check
- [x] ballot box with check
- [ ] ballot box without check

***

## 07. Tables

***

## 08. Links

```markdown
<!-- link syntax -->
[LINK TEXT](URL "title rendered as tooltip")

or enclose URL or email address in angle brackets <email@domain.com>
```

`link example 1`
[The Huffington Post](https://www.huffpost.com/ "HuffPost - Breaking News, U.S. and World News | HuffPost")

`link example 2`
<arianna@huffingtonpost.com>
***

## 09. Images

### Unlinked Images

```markdown
<!-- unlinked images syntax -->
![alt text rendered as caption](file_path_or_URL "image title")
```

### Linked Images

```markdown
<!-- linked images syntax-->
To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.  

Example:
[![An old rock in the desert](images/shiprock.jpg)](https://en.wikipedia.org/wiki/Shiprock)
```

***

## 10. Footnotes  

***  
