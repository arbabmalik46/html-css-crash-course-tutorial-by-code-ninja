# html-css-crash-course-tutorial-by-code-ninja
This is a simple html/css crash course repo by The Net Ninja



## Classes and ID property declaration
.error //class level property <br/>
{ <br/>
    color: red; <br/>
} <br/> 
p{    /* This is tag level declaration*/ <br/>
    color: azure; <br/>
}<br/>
p.error{ /*tag and class level property declaration*/ <br/>
    color: red; <br/>
}<br/>
p.success{ <br/>
    color: green; <br/>
}<br/>
p.feedback.success{ /*multi class level declaration*/ <br/>
    margin: 20px; <br/>
    border:2px solid grey; <br/>
}<br/>
#content{                   /*id attribute is used to */ <br/>
    border: 2px dashed pink; <br/>
    padding: 20px; <br/>
    background-color: aqua; <br/>
}<br/>
div#content{                /*ID property is used alongside tag property*/ <br/>
    border: 2px dashed pink; <br/>
    padding: 20px; <br/>
    background-color: aqua; <br/>
}<br/>
div p{   //parent child tag property to give some styling <br/>
    color: blueviolet;<br/>
}<br/>
div .error{ //parent and class attribute used<br/>
    color: blueviolet;<br/>
}<br/>
a[href] //tag and attribute related styling<br/>
{<br/>
    color: yellowgreen;<br/>
}<br/>
a[href="www.google.com"]//tag and attribute spicified also called as attribute selector<br/>
{<br/>
    color: brown;<br/>
}<br/>
*= -> includes <br/>
$= -> ends<br/>


## inheritance in css
div{<br/>
    border: 2px dashed pink;<br/>
    padding: 20px;<br/>
    background-color: aqua;<br/>
    margin: 20px; <br/>
}<br/>
<br/>
p{<br/>
    border: inheritance;<br/>
    padding: inheritance;<br/>
}<br/>

## HTML Semantic Tags
<main>
- main content of the page, usually contains other elements like header or footer <br/>
for the main page content of a page, unique to that page.<br/>
<section>
- section is used for grouping similar contents together on your web pages,<br/>
like navigation menus, sidebars etc., it can be nested inside another element such as div <br/>
defines a certain section of a webpage (e.g. blog list, contact info) <br/>
<article>
defines a bit of content which makes up an article (e.g. a blog post)
- defines an article within a website and should contain all related information about this topic <br/>
(e.g. news articles). It's often displayed in its own box with additional
details e.g. author name, date published etc.. <br/>
<aside>
defines some content related to something else (e.g. similar blogs)
- aside tag specifies some text which will appear outside the flow of normal document
layout but still remain associated with the rest of the document <br/>
<header>
defines header of your website - contains the nav, title etc
<footer>
for the footer of a website
<header>, <footer>,<nav> - these tags are not visible by default when you
view source code
or inspect elements.<br/>