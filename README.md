# module2-solution
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment 2</title>
</head>
<style>
    div {
        text-align: center;
    }
    
    .div1,
    .div2,
    .div3 {
        margin: 1.5%;
        display: inline-block;
        width: 30%;
    }
    
    .div1 {
        background-color: red;
    }
    
    .div2 {
        background-color: green;
    }
    
    .div3 {
        background-color: blue;
    }
    
    body {
        background-color: blanchedalmond;
    }
    
    h1 {
        text-align: center;
    }
    
    @media only screen and (max-width: 810px) {
        body {
            background-color: hotpink;
        }
        .div1,
        .div2,
        .div3 {
            margin: 3%;
            display: inline-block;
            width: 40%;
        }
    }
    
    @media only screen and (max-width: 500px) {
        body {
            background-color: lightblue;
            margin: 2%;
        }
        .div1,
        .div2,
        .div3 {
            margin: 1.5%;
            display: block;
            width: 97%;
        }
    }
</style>

<body>
    <h1>OUR MENU</h1>
    <div class="container">
        <div class="div1">
            <h2>Sushi</h2>
            <p class="column">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute
                irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
        <div class="div2">
            <h2>Beef</h2>
            <p class="column">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute
                irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>

        <div class="div3">
            <h2>Chicken</h2>
            <p class="column">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute
                irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
    </div>


</body>

</html>

