---
title: Electronic Lab books in markdown
tags: presentation
slideOptions:
  theme: dark
  transition: 'fade'
spotlight:
    enabled: true
progress: true
---

<style>
.reveal {
  font-size: 18px;
}
</style>

<!-- <style> ul { list-style-type: none; } </style> -->

# Electronic Lab books in markdown

Marcelo Nollmann
*version 11/01/2022*

---

# Critical issues when considering electronic labooks


1. Easy to use<!-- .element: class="fragment" -->

2. Sharing with others<!-- .element: class="fragment" -->

3. Backup<!-- .element: class="fragment" -->

4. **Revision history**<!-- .element: class="fragment" -->

6. **Long-term format compatibility!**<!-- .element: class="fragment" -->

---

# Local word processor (word, openoffice)

- Everyone knows how to use it<!-- .element: class="fragment" -->
- but it is not always easy to use when you have to write a 200 pages document with figures! <!-- .element: class="fragment" -->
- Difficult to share<!-- .element: class="fragment" -->
- No revision history<!-- .element: class="fragment" -->
- Format is propietary<!-- .element: class="fragment" -->
- **No long-term format compatibility**<!-- .element: class="fragment" -->

---

# Online word processor (google docs)

<img src="https://i.imgur.com/DwDCQX6.png" width="600"/>

- Easy to use, BUT hard to handle in large volumes<!-- .element: class="fragment" -->
- Easy to share<!-- .element: class="fragment" -->
- Has revision history<!-- .element: class="fragment" -->
- Format is propietary<!-- .element: class="fragment" -->
- Stored in cloud!<!-- .element: class="fragment" -->
- No long-term format compatibility<!-- .element: class="fragment" -->

---

# Propietary tool (INSERM tool)

- Easy to share<!-- .element: class="fragment" -->
- Easy to use??<!-- .element: class="fragment" -->
- No revision history<!-- .element: class="fragment" -->
- Format is propietary<!-- .element: class="fragment" -->
- No long-term format compatibility<!-- .element: class="fragment" -->
- What happens when the company running it goes under? How do you retrieve the 5-years of data stored in a database format?<!-- .element: class="fragment" -->
- Usually their solution is PDFs!<!-- .element: class="fragment" -->

---

# Markdown 

<img src="https://i.imgur.com/z2HUP5r.png" width="500"/>

- Easy to use--> requires very basic programming skills<!-- .element: class="fragment" -->
- Easy to share:<!-- .element: class="fragment" -->
    -  ownCloud, <!-- .element: class="fragment" -->
    -  hackMD online, <!-- .element: class="fragment" -->
    -  HedgeDoc hosted locally!<!-- .element: class="fragment" -->
- Revision history using git<!-- .element: class="fragment" -->
- Format is open!<!-- .element: class="fragment" -->
- **Offers long-term format compatibility as it relies on pure text**<!-- .element: class="fragment" -->

---

# Markdown cloud-hosted server

Semi-commercial solution hosted online: [hackmd.io
](https://hackmd.io)
![](https://i.imgur.com/n0pXp3M.png)


But you can also use on-line editors such as (Dillinger)[https://dillinger.io/] or [StackEdit](https://stackedit.io/app#).


---

# Markdown self-hosted server: Hedge-doc

Open-source self-hosted: https://hedgedoc.org/

![](https://i.imgur.com/hIYH2C6.png)

---

# Markdown client: obsidian

Open-source markdown client: [obsidian.md](https://obsidian.md/)

![](https://i.imgur.com/7pdCx2g.png)

---

# Introduction to Markdown

There are many applications that support Markdown. I use [Typora](https://www.typora.io/#linux), or [Haroopad](http://pad.haroopress.com/) or [Atom](https://atom.io/) for **offline** editing (my favorite).

![](https://i.imgur.com/OCNyPmi.png)

---

# Writing text in markdown

### Headers

To write headers of sections you just use '#'. For instance:


```markdown
# header 1
```
# header

```markdown
## header 2
```
## header 2

```markdown
### header 3

... you get the idea
```
### header 3

---

# Emphasis

This is even easier. For example

```markdown
**bold**
*italic*
==highlight==
9^th^
H~2~O
```

will appear as

**bold**, *italic*, ==highlight==, 9^th^, H~2~O

---

# Lists

List are done by just using '-' For instance, the following

``` markdown
- [ ] work item 1
    - [x] sub item 1
    - [ ] sub item 2
- work item 2
```
will appear as

- [ ] work item 1
    - [x] sub item 1
    - [ ] sub item 2
- [ ] work item 2

---

# Lists

An ordered list

```markdown
1. item 1
2. item 2
3. item 3
4. item 4
4. etc
```

 will look like:

1. item 1
2. item 2
3. item 3
4. item 4
5. etc


---

# Images


You can insert the image by typing

```
![](https://i.imgur.com/h7P1MWD.jpg)
```

and it will appear as:

![](https://i.imgur.com/h7P1MWD.jpg)


You can also add images from the internet by replacing the filename with a link.

Make sure you always use relative links! If you don't know what these are, ask around!

---

# Tables


|  | Equipment | fjdfd |
| - | -|  -|
| **as**| sds|  sdsd|
| **sdsdsdsds**| sdsdsdsdsds| 1111| 

Tables 1are easy, for instance, do

```markdown
| strains | Date | Procedence|
| --------|------|----------|
|sdsdnk| 20-09-76| Cozzlab|
| pyt233| 19-01-81| SherrattLab|
```

will appear as:

| strains | Date | Procedence|
| --------|------|----------|
|sdsdnk| 20-09-76| Cozzlab|
| pyt233| 19-01-81| SherrattLab|

and so on.

---


# Conversion

Markdown documents can be easily converted to word, html, latex, pdf using [pandoc](https://pandoc.org/MANUAL.html).



