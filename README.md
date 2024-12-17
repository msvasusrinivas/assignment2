index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>java assignment</title>
    <style>
        h1 {
            color: rgb(201, 21, 21);
        }
        .div1 {
            text-align: center;
        }
    </style>
</head>
<body>
    1Q) Add some HTML content and change that content on clicking of some button.
    <h1 id="h1">this is the old test</h1>
    <!-- <p id="para1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo voluptatem nihil, non sequi quis dolorem
        magnam voluptate fugit rem tempore? Enim quasi aperiam quidem fugit?</p> -->
    <button onclick="login()">login</button>
    <script>
        function login() {
            document.getElementById('h1').innerHTML = "welcome to the new text";
        }
    </script>
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>input chenge</title>
</head>
<body>
    3Q) Create a HTML from with some input boxes and display the content entered in the input boxes on an alert box or
    on an
    console.
    <form>
        <label for="name"></label>
        <input type="text" id="name" value1="enter your name"><br><br>
        <label for="email"></label>
        <input type="text" id="email" value2="enter your email"><br><br>
        <label for="password"></label>
        <input type="text" id="password" value3="password"><br><br>
        <label for="ph no"></label>
        <input type="text" id="ph no" value4="phone number"><br><br>
        <button onclick="func1()">subimit</button>
    </form>
    <script>
        function func1() {
            let val1 = document.getElementById('name').value;
            let val2 = document.getElementById('email').value;
            let val3 = document.getElementById('password').value;
            let val4 = document.getElementById('ph no').value;
            alert('user entered as' + val1 + 'and' + val2 + 'and' + 'val3' + 'and' + val4);
        }
    </script>
</body>
</html>
‎index.html.html
+13
-30
Original file line number	Diff line number	Diff line change
@@ -4,50 +4,33 @@
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>button styles</title>
    <title>button chenge</title>
    <style>
        .div1 {
            text-align: center;
    </style>
</head>

<body>
    4Q)Create different buttons as shown in figure below. And on clicking each button change the text size,font etc,
    respectively according to the buttons entered.
    2Q) Create a html button and align it on the center of the screen and on clicking that button,change the background
    color of the whole page.

    <p id="head1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis aperiam in rerum repellendus doloremque
        reiciendis sequi numquam laudantium, fugiat beatae!</p>
    <button id="btn2" onclick="func2()">cilck to change text size</button>
    <button id="btn3" onclick="func3()">click to chenge font color</button>
    <button id="btn4" onclick="func4()">click to font style</button>
    <div class="div1">

    <script>
        let var1 = document.getElementById('head1');
        let btn2 = document.getElementById('btn2');
        let btn3 = document.getElementById('btn3');
        let btn4 = document.getElementById('btn4');
        <body id="bod">


            <button onclick="func1()">click</button>
    </div>
    <script>
        function func1() {
            let var1 = document.getElementById('head1');
        }
        function func2() {
            btn2.style.fontSize = "100px";
        }
        function func3() {
            btn3.style.color = "red";
            btn3.style.fontSize = "100px";
            document.getElementById('bod').style.backgroundColor = "red"
        }
        function func4() {
            btn4.style.fontStyle = "italic";
            btn4.style.fontSize = "100px";
        }
    </script>




</body>

</html>
