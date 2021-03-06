``` # Heading 1 ```
# Mastering Markdown: *A Cheatsheet*

``` ## Heading 2 ```
## Heading 2: *Comes with a hard rule.*
``` ### Heading 3 ```
### Heading 3: *From There, Some*
```#### Heading 4 ```
#### Heading 4: *Nice*
``` ##### Heading 5 ```
##### Heading 5: *And Increasingly Subtle*
``` ###### Heading 6 ```
###### Heading 6: *Subheads*

``` A newline creates a new paragraph in Github. Other parsers take 2. ```
This is a paragraph. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

## Inline Styles: *Bold, Italic, Strikethrough*

``` *Italic* _Italic_ ```
*Italic* _Italic_

``` **Bold** __Bold__ ```
**Bold** __Bold__

``` ~~Strikethrough~~ ```
~~Strikethrough~~

## Links: *Hyperlink & Table of Contents*

``` <http://google.com> ```
<http://google.com>

``` [http://google.com](http://google.com) ```
[http://google.com](http://google.com)

In-document links (HTML is *parsed normally* in Markdown):
```Link Text: <a href="#top">Top</a>```
```Target: <a name="top"></a>```

<a href="#top">Top</a>
<a name="top">Target</a>

## Images: *With Tooltips, Alt Text and as Links*

```![alt text](http://url.com "Hover for tooltip text.")```

![Alt text](http://unsplash.it/500/300?random "Neat, huh?")

```[![Alt text](http://unsplash.it/500/500?image=1012 "Hover for tooltip.")](http://google.com)```
[![Alt text](http://unsplash.it/500/500?image=1012 "How peaceful.")](http://google.com)


## HTML Renders Normally: *Yo Dawg...*
<h4>This is HTML Markup, <br><span style="color:red"> And HTML Styled With Inline CSS.<span></h4>


## Unordered Lists

``` + List Item 1 ``` <br>
``` + List Item 1 ``` <br>
``` (tab) - List Item 2 ``` <br>
``` (tab) - List Item 2 ``` <br>
``` (tab)(tab) * &double; List Item 3 ``` <br>
``` (tab)(tab) * &double; List Item 3 ``` <br>

* List Item
* List Item
    * Nested List Item
    * Nested List Item
        * Nested Nested List Item
        * Nested Nested List Item

## Ordered Lists: *Note the Auto Increment*
``` 1. List Item 1 ``` <br>
``` 1. List Item 2 ``` <br>
``` 1. List Item 3 ``` <br>


1. List Item 1
1. List Item 2
1. List Item 3

## Horizontal Rules

``` --- ```

---

## Block Quotes  

``` > This, friends,<br> ```<br>
``` > is an emminently quotable<br> ```<br>
``` > "blockquote" you can share.```<br>

> This, friends,<br>
> is an emminently quotable<br>
> "blockquote" you can share.
>
> **- Importantus Thinkerus**

## Code Snippets

``` (Surround with triple backticks for inline code.) ```

    ```

    <?php
        echo "Or use opening tags and closing tags. " +
        "Or, check that your parser can auto-detect your syntax of choice.";
            if ($hope > 9000){
                echo "What, nine, thousand?!"
            };
    ?>

    // Javascript
    let x = 4;
    const idiom = "It's not what you know...";
    console.log("And knowing is half the battle!");

    # Showing a version control diff. This doesn't render
    # correctly in Github it seems, but could be useful if
    # you're using a different Markdown parser.

    ```diff
    + added line;
    - deleted line;
      normal line;
    ```
    ```

## Tables

```

|Table Heading|Table Heading|Table Heading|
|:------------|:-----------:|------------:|
|Table Cell   |Table Cell   |Table Cell   |
|Left Align   |Center Align |Right Align  |
|Table Cell   |Table Cell   |Table Cell   |
```

|Table Heading|Table Heading|Table Heading|
|:------------|:-----------:|------------:|
|Table Cell   |Table Cell   |Table Cell   |
|Left Align   |Center Align |Right Align  |
|Table Cell   |Table Cell   |Table Cell   |


## Checklists: *To Do or Not To Do...*

``` - [ ] To Do 1 ``` <br>
``` - [x] To Do 2 ``` <br>
``` - [ ] To Do 3 ``` <br>

- [ ] To Do 1
- [x] Finish Markdown Cheat Sheet.
- [ ] Code all the things!
