# Code Refactor Starter Code
##Changes made
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title




Added figure and figcaption
Added alt text to images, removed closing image tag
Changed footer to h4 instead of h2
Changed Title to Horiseon


12/3-
added ID elements back in
Did moving list-style-type: none; to  .header div ul li do the right thing?


    .header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
    
}

.header h1 {
    display: inline-block;
    font-size: 48px;
}

.header h1 .seo {
    color: #d9dcd6;
}

.header div {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}