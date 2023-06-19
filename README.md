# html-css-crash-course-tutorial-by-code-ninja
This is a simple html/css crash course repo by The Net Ninja



##Classes and ID property declaration
.error //class level property
{
    color: red;
}
p{    /* This is tag level declaration*/
    color: azure;
}
p.error{ /*tag and class level property declaration*/
    color: red;
}
p.success{
    color: green;
}
p.feedback.success{ /*multi class level declaration*/
    margin: 20px;
    border:2px solid grey;
}
#content{                   /*id attribute is used to */
    border: 2px dashed pink;
    padding: 20px;
    background-color: aqua;
}
div#content{                /*ID property is used alongside tag property*/
    border: 2px dashed pink;
    padding: 20px;
    background-color: aqua;
}
div p{   //parent child tag property to give some styling
    color: blueviolet;
}
div .error{ //parent and class attribute used
    color: blueviolet;
}
a[href] //tag and attribute related styling
{
    color: yellowgreen;
}
a[href="www.google.com"]//tag and attribute spicified also called as attribute selector
{
    color: brown;
}
*= -> includes
$= -> ends


##inheritance in css
div{
    border: 2px dashed pink;
    padding: 20px;
    background-color: aqua;
    margin: 20px; 
}

p{
    border: inheritance;
    padding: inheritance;
}
