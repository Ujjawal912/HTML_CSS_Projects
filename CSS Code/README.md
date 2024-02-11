# upgrad-sd-2.0-css
### CSS Introduction
**Learner Outcome** : Understand about the course and also able to understand the project we will create in the course
 - Course Introduction (what will be the architecture of the course, what all technologies we will learn for creating the website)
 - Project Demo : Overview of the project and high level discussion of the various functionalities of website
 - Projects for demonstration
    - A landing page of a website with different sections like About us, Our  team, Contact us
### Getting familiar with HTML & CSS Tools 
**Learner Outcome** : Get the rationale behind using the CSS with HTML for creating the website.

  - Introduction to the CSS.
  - Linkage of CSS to the HTML.
  - Explanation of the CSS selectors along with live coding example
  - Explanation of the CSS classes and IDs and their usage in the styling the website.
  - Explanation of Margin And Padding
  - What is CSS Box Model and its usage in the designing the website

### Repository walk through
CSS topics delivery are divided in stages. Each stage has been made into a branch *(stage-x)* stage-1, stage-2 and so on. Find the link to each branch below with the details of topic covered in each stage. 

  - [stage-1]
    -  Introduction to the CSS
        - CSS Syntax and Usage
          -  ```selector { property: value;  }```
          -  Inline Style: ``` <body style="property: value"> </body> ```
          -  Internal CSS ```<head> <style> selector { property: value } </style></head>```
          -  External Stylesheet ```<link rel="stylesheet" href="./style.css">```
        -  Targetting html element ``` body{ background: lightgrey }```
     
  - [stage-2]
    - Box Model 
        - Margin
        - Border
        - Padding
        - width and height
    - Targetting Elements using IDs and Classes
        - ```#id{ property: value }```
        - ```.class{ property: value } ```

 - [stage-3]
    - Postion Property
        - ``` selector{ position: static;} ```
        - Other properties ``` Fixed, Relative, Absolute, Sticky```
        - Introduction to flexbox
        - Introduction to Media queries([Link](https://www.w3schools.com/css/css_rwd_mediaqueries.asp))

- [stage-4]
    - CSS3 specific properties and functionality
        - Border Radius: ```border-radius: 4px;```
        - Box-shadow Ex: ```box-shadow: 1px 1px 3px #292929;```
        - Text-Shadow Ex: ``` h1 { text-shadow: 0 1px 0 white; }```
        - Attribute Selector ```selector[attribute="value"] { background-color: yellow;} ```
        - Multiple Backgrounds ``` selector{ background: url(image/path.jpg) 0 0 no-repeat, url(image/path.jpg) 50% 0 no-repeat,}```

**Note** The HTML code is taken from the [HTML-track] and using the same HTML code, we are going to build on the CSS concepts

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [stage-1]: <https://github.com/PT2309/upgrad-sd-2-css/tree/stage-1>
   [stage-2]: <https://github.com/PT2309/upgrad-sd-2-css/tree/stage-2>
   [stage-3]: <https://github.com/PT2309/upgrad-sd-2-css/tree/stage-3>
   [stage-4]: <https://github.com/PT2309/upgrad-sd-2-css/tree/stage-4>
   [HTML-track]: <https://github.com/PT2309/upgrad-sd-2.0-html>