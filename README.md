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
