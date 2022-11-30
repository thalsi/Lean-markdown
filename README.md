# Markdown
- Markdown is a open-scoure markup language
- Plain text that converts to a Rich HTML document

## File Extension
- .markdown
- .md
- .mkd
- .mkdown
- .text
- .mdown

## Cheat Sheet
1. Basic Syntax
2. Extended Syntax
  
## 1.Basic Syntax

1. Heading
      # Title
      ## Title
      ### Title
      #### Title
      ##### Title
      ###### Title

2. Bold

      **Bold text**

3. Italic

      *Italic text*
      _Italic text_

4. Blockquote
  
  > "I am a superman. i can do anything.." 

5. Ordered List
    1. One
    2. Two
    3. Three
        1. One
        2. Two

6. Unordered List
    - One
       - a
       - b
    - Two
    - Three
    
    * One
    * Two
    * Three
    
    + One
    + Two
    + Three

7. Code
  `var str = "javascprit";`
  `console.log(str);`
  
  
  `` this is javascprit `console.log(str);` it is a debug tool``

8. Horizontal Rule
---


9. Link
-Goolge click link [google](https://www.google.com)

- Formatting Links below:-
- Google link **[Click Google](https://www.google.com)**
- Google link *[Click Google](https://www.google.com)*
- Section link [`Cheat sheet`](#cheat-sheet)


10. Image
![alt text](login-bg.png)


11. URLs and Email Addresses

<https://www.markdownguide.org>

<fake@example.com>


## 2.Extended Syntax
These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

1. Table

  | ID | Title |
  | --- | ---- |
  | 1 | Annu |
  | 2 | Tinu |

2. Fenced Code Block
  ```
  {
    "id":"1",
    "name:"Manu"
  }
  ```
3. Footnote

   Here a sentace with footnote. [^1] [^2]
    
   [^1]: This is a footernote.
   [^2]: This is a footernote example. 

### 4.My Great Heading {#custom-id}

5. Definition List

    First Term
    : This is the definition of the first term.

    Second Term
    : This is one definition of the second term.
    : This is another definition of the second term.

6. Strikethrough
  ~~ delete this line ~~
  
7. Task List
    - [x] Task one do it.
    - [ ] Task two do it.
    - [ ] Task three do it.

8. Emoji
   - That is so funny! :joy:  
   - [Emoji is here](https://emojipedia.org/)
 
9. Highlight
    - This is ==highlight== 

10. Subscript
      H~2~o
      
11. Superscript 
      x^2^
