# WebDevelopment Using Reactjs

+ Frontend Technologies
    + Html5
    + CSS3
    + Bootstrap4.6
    + Javacript
    + ReactJs

+ Backend Technologies

    + Php
    + Java
    + Python
        - Flask
        - Django
    + Nodejs

+ Module (file) ---> Package --> Library ---> Framework
+ Databases

    - Mysql
    - Oracle
    - Sqlite
    - PostgresSQL
    - MongoDB
    - Firebase

+ Version Control System (Source code management)
+ It is a system to track the history of a file or folder
    - Distrubuted VCS
        - Git,Mercurial
    - Central (Remote) VCS
        - Github, Bitbucket

+ SCM
    + Add project content to git
    + commit with message
    + push the data into github

+ Git
    - Untracked Area
    - Staging (tracked) Area
    - Commit Area


+ Webdesigning
+ Webdevelopment


### HTML
+ Hyper Text Markup Language
+ Elements
+ `.htm` or `.html`
+ Semantic Elements
    - header
    - nav
    - article
    - section
    - aside
    - footer
    - table
    - form
+ Block Level Elements
    - aside
    - article
    - h1 to h6
    - div
    - footer
    - header
    - nav

+ Inline Elements

    - input
    - label
    - button
    - img
    - a
    - sup
    - sub
    - i
    - sapn
    
+ `ul` or `ol`

##### Practice
+ figure
+ span
+ audio
+ article
+ section
+ aside

+ form elemnts
    - input
    - label
    - button
    - textarea

# CSS
+ Cascading Style Sheets

### Syntax

```
selector {
    <!-- declaration block -->
    property:value
}
```

+ Types of CSS
    - Inline CSS
    - Internal CSS
    - External CSS

#### Selectors

+ Basic selectors
    - Universal selector (*)
    - By element name
    - Grouping selector (element1,element2...)
    - Class selector (.className)
    - Id selector (#Idname)
    
+ combinators
    - Descendant selector (space )
    - Child combinator (>)
    - Adjacent sibling selector (+)
    - General sibling selector (~)

+ Pseudo class selector 
    
    ```
    selector :pseudo-class{
        css code
    }
    ```
    - link
    - visited
    - hover
    - active
+ Pseudo element selector
```
    selector ::pseudo-element{
        css code
    }
```

+ atrribute selector

```
a[attribute]{
    property:value
}
```
##### Position
    - Documentflow
        - margin
    - Position context
        - static
        - relative
        - absolute
        - fixed
        - sticky

##### Display
    - none
    - inline
    - block
    - inline-block
##### BoxModal

- content
- padding
- border
- margin

##### Flexbox

+ display
    - flex
+ flex-wrap
+ flex-direction
+ flex-flow
+ justify-content
+ align-items
+ align-content
+ flex-grow 


+ input type
    - range
    - datetime
- meter
- progress
- Datalist
- audio 
- video

### Media Queries

+ `@media` rule
```
@media screen and (max-width:320px) and (min-width:200px)
{
<!-- css styles -->
}
```

+ Extra small devices
`@media only screen and (max-width:600px){
 css code
}
`
+ small devices
`@media only screen and (min-width:600px){
 css code
}
`
+ Medium devices

`@media only screen and (min-width:768px){
 css code
}
`
+ Large devices
`@media only screen and (min-width:992px){
 css code
}
`
+ Extra large devices
`@media only screen and (min-width:1200px){
 css code
}
`

# Bootstrap
+ CSS framework

+ indexpage

    + nav
    <!-- + content -->
    + content1
    + footer

##### color classes

+ primary 
+ secondary 
+ info  
+ success 
+ warning
+ danger
+ dark
+ white
+ light


+ backgroundcolor,text,button,alert
+ bg-primary
+ text-white
+ btn-primary

+ Margin & Padding in bootstrap

+ mt-* (0 to 5) 1rem=16px (m- margin)
    + 0 - 0rem
    + 1 - 0.25rem (4px)
    + 2 - 0.5rem (8px)
    + 3 - 1rem (16px)
    + 4 - 1.5rem (24px)
    + 5 - 3rem   (48px)
+ pb-4

+ Cards
+ Modals
+ Table

