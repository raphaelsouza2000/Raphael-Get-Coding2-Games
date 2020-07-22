page 6:computer games

page 8: history of gaming

page 12: how to make an alert pop up in your browser

var aString = "A string is set of words";   (the var is the variable keyword)
var aNumber = 123;   (the semi-colon is the variable value)
var aBoolean = true;  (the equals sign is the assingment operator)

var javascriptIsFun = true;  (the word 'fun' is the variable)
var message = "JavaScript is fun!";
if(javscriptIsFun) {     (the word 'if' is the if statement)
    alert(message);    (the alert is the built-in alert function)
}

page 15: how to use the book

page 16/17: key code skills

page 22: the game build

page 23: the game board - a small example

<!DOCTYPE html>
<html>
    <head>  
        <title>Noughts and Crosses</title>
    </head>
    <body>
        <p>Do you want to play Noughts and Crosses?</p>
        Click here to play!<br/>
    </body>
</html>

page 24: the <div> tag

<body>
    <div>
        <p>Ruby</p>
        <p>Scratch</p>
    </div>
</body>

page 25: using the css

<!DOCTYPE html>
<html>
    <head>
        <title>CSS</title>
        <style>
            .names {
                font-size: 16pt;
                text-align: center;
                background-color: blue;
            }
        </style>
    </head>
    <body>
        <div class="names">
            <p>Ruby</p>
            <p>Scratch</p>
        </div>
    </body>
</html>

page 26: css properties and values

height->sets the height of the HTML element->100px; 100%;
width->sets the width of the HTML element->100px; 100%;
border->gives the HTML element a border->5px solid black;
padding->creates white space around the HTML element->10px;
float->positions the HTML element to the left or right of another element->left;right;none;
clear->specifies which elements can float beside the HTML element and on which side->left;right;both;

page 27: game build 1

page 30: making the game interactive, using javascript

<body>
    <script>
        alert("Get ready for the Hackathon!")
    </script>
</body>

page 31: functions

<body>
    <script>
        function plan() {  ->the plan is the function name, and it is a function of javascript statements that run one after another to peform a certain action
            alert("Get ready for the Hackathon!");
            alert("Learn JavaScript!");
            alert("Code Noughts and Crosses!");
        }
         plan();
    </script>
</body>



