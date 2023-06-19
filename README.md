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
