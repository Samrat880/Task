index_for_github.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center>
        <h1>Index page</h1>
        <table border="1">
            <tr>
                <th colspan="2">HTML task</th>
            </tr>
            <tr>
                <th>Task Number</th>
                <th>Link</th>
            </tr>
            
            <tr>
                <td>Task1</td>
                <td><a href="./Task1.html">Link1</a></td>
            </tr>
            <tr>
                <td>Task2</td>
                <td><a href="./Task2.html">Link2</a></td>
            </tr>
            <tr>
                <td>Task3</td>
                <td><a href="./Task3.html">Link3</a></td>
            </tr>
            <tr>
                <td>Task4</td>
                <td><a href="./Task4.html">Link4</a></td>
            </tr>
            <tr>
                <td>Task5</td>
                <td><a href="./Task5.html">Link5</a></td>
            </tr>

            <tr>
                <th colspan="2">CSS task</th>
            </tr>
            <tr>
                <th>Task Number</th>
                <th>Link</th>
            </tr>
            
            <tr>
                <td>CSSTask1</td>
                <td><a href="./CSSTask1.html">Link1</a></td>
            </tr>
            <tr>
                <td>CSSTask2</td>
                <td><a href="./CSSTask2.html">Link2</a></td>
            </tr>
            <tr>
                <td>CSSTask3</td>
                <td><a href="./CSSTask3.html">Link3</a></td>
            </tr>
            <tr>
                <td>CSSTask4</td>
                <td><a href="./CSSTask4.html">Link4</a></td>
            </tr>
            <tr>
                <td>CSSTask5</td>
                <td><a href="./CSSTask5.html">Link5</a></td>
            </tr>
            <tr>
                <td>CSSTask6</td>
                <td><a href="./CSSTask6.html">Link6</a></td>
            </tr>
            <tr>
                <td>CSSTask7</td>
                <td><a href="./CSSTask7.html">Link7</a></td>
            </tr>
        </table>
    </center>
</body>
</html>








<!DOCTYPE html>
<html>
<head>
<style>
table, th, td {
    border: 1px solid black;
  background-color:lightblue;
  border-radius:  10px;
}
</style>
</head>

<body>
    <h1>Task 1</h1>
    <center>
<table style="width:50%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>
</center>
</body>
</html>












<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Task 5</title>

    <style>
        .c1
        {
            width:175px;
            margin-left:3px;
            list-style-type: none;
            padding-left:5px;
            padding-top: 5px;
            padding-right: 5px;
            border: 1px solid black;
        }
        .c3,#id1
        {
            font-size: 20px;
            display: block;
            text-decoration: none;
            padding:10px;
            background-color: skyblue;
            color: blue;

        }
        .c3:hover
        {
            background-color: orange;
            color: white;
        }
        #id1
        {
            background-color: orange;
            color: white;
        }
        .c2
        {
            margin-left:3px;
            list-style-type: none;
            padding:0;       
            background-color:lightgrey;
            overflow: auto;
        }
        
        .c4,#id2
        {
            font-size: 20px;
            text-decoration: none;
            color: blue;
            background-color:lightgrey;
            display:block;
            padding:15px;
        }
        .c4:hover
        {
            background-color: gray;
            color: white;
        }
        #id2
        {
            background-color: gray;
            color: white;
        }
        .c5
        {
            float: left;
            border-right:1px solid blue;
        }
    </style>
</head>
<body>
    
    <h1>Horizontal Navigation Bar</h1>

    <ul class="c2">
        <li class="c5"><a href="https://www.w3schools.com/" target="_blank" id="id2">Home</a></li>
        <li class="c5"><a href="https://www.w3schools.com/java/default.asp" target="_blank" class="c4">Java</a></li>
        <li class="c5"><a href="https://www.w3schools.com/html/default.asp" target="_blank" class="c4">HTML</a></li>
        <li class="c5"><a href="https://www.w3schools.com/css/default.asp" target="_blank" class="c4">CSS</a></li>
    </ul>
    
    <br>

    <h1>Vertical Navigation Bar</h1>

    <ul class="c1">
        <li><a href="https://www.w3schools.com/" target="_blank" id="id1">Home</a></li>
        <li><a href="https://www.w3schools.com/java/default.asp" target="_blank" class="c3">Java</a></li>
        <li><a href="https://www.w3schools.com/css/default.asp" target="_blank" class="c3">CSS</a></li>
        <li><a href="https://www.w3schools.com/html/default.asp" target="_blank" class="c3">HTML</a></li>
        <li><a href="https://www.w3schools.com/bootstrap/bootstrap_ver.asp" target="_blank" class="c3">Bootstrap</a></li>
    </ul>

</body>
</html>







<!DOCTYPE html>
<html>
<head>
<style>
#customers {
  font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  border-collapse: collapse;
  width: 60%;
  font-weight: 500;
}

#customers td, #customers th {
  padding: 10px;
}

#customers tr:nth-child(even){background-color: #f2f2f2;}

#customers tr:hover {background-color: #ddd;}

#customers th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #04AA6D;
  color: white;
}
</style>
</head>
<body>

<h1>CSS TASK 3</h1>

<center>

<table id="customers">
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Berglunds snabbköp</td>
    <td>Christina Berglund</td>
    <td>Sweden</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
  <tr>
    <td>Ernst Handel</td>
    <td>Roland Mendel</td>
    <td>Austria</td>
  </tr>
  <tr>
    <td>Island Trading</td>
    <td>Helen Bennett</td>
    <td>UK</td>
  </tr>
  <tr>
    <td>Königlich Essen</td>
    <td>Philip Cramer</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Laughing Bacchus Winecellars</td>
    <td>Yoshi Tannamuri</td>
    <td>Canada</td>
  </tr>
  <tr>
    <td>Magazzini Alimentari Riuniti</td>
    <td>Giovanni Rovelli</td>
    <td>Italy</td>
  </tr>
</table>

</center>

</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        #myside a
        {
            position: absolute;
            left: -80px;
            transition: 0.3s;
            padding: 15px;
            width: 100px;
            text-decoration: none;
            font-size: 20px;
            color: white;
            border-radius: 0 5px 5px 0;
        }
        #myside a:hover 
        {
            left: 0;
        }
        #home {
            top: 120px;
            background-color: #04AA6D;
        }

        #html {
            top: 180px;
            background-color: #2196F3;
        }

        #css {
            top: 240px;
            background-color: #f44336;
        }

        #java {
            top: 300px;
            background-color: #555
        }
    </style>
</head>
<body>
        <h1>CSS TASK 4</h1>
        <div id="myside" class="sidenav">
            <a href="#" id="home">Home</a>
            <a href="#" id="html">HTML</a>
            <a href="#" id="css">CSS</a>
            <a href="#" id="java">Java</a>
        </div>
        <div class="content" style="margin-left:150px;">
            <h1>Hoverable Sidenav Buttons</h1>
            <p>Hover over the buttons in the left side navigation to open them.</p>
        </div>
</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            padding-left: 11em;
            font-family: Georgia, "Times New Roman",Times, serif;
            color: purple;
            background-color: #d8da3d
        }
        h1 {font-family: Helvetica, Geneva, Arial,SunSans-Regular, sans-serif;}
        .list
        {
            list-style-type: none;
            padding: 0;
            margin: 0;
            position: absolute;
            top: 2em;
            left:1em;
            width:9em
        }
        li{
            background: white;
            margin: 0.5em 0;
            padding: 0.3em;
            border-right: 1em solid black
        }
        a
        {
            color:blue;
            text-decoration: none;
        }
        a:hover,#home {color: purple;}
        #i1
        {
            margin-top: 1em;
            padding-top: 1em;
            border-top: thin dotted;
        }
    </style>
</head>
<body>
        <ul class="list">
            <li><a href="#" id="home">Home page</a></li>
            <li><a href="#" id="musings">Musings</a></li>
            <li><a href="#" id="town">My town</a></li>
            <li><a href="#" id="link">Links</a></li>
        </ul>

        <h1>My first styled page</h1>
        <p>Welcome to my styled page!</p>
        <p>It lacks images, but at least it has style. And it has links, even if they don't go anywhere...</p>
        <p>There should be more here, but I don't know what yet.</p>
        
        <address id="i1">Made 5 April 2004<br>by myself</address>
    
</body>
</html>


<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
  body 
  {
    font-family: Arial, Helvetica, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;}
  form 
  {
    border: 3px solid #f1f1f1;
    width: 60%;
  }

  input[type=text], input[type=password] {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0;
    display: inline-block;
    border: 1px solid #ccc;
    box-sizing: border-box;
  }

  button {
    background-color: #04AA6D;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    cursor: pointer;
    width: 100%;
  }

  button:hover {
    opacity: 0.8;
  }

  .cancelbtn {
    width: auto;
    padding: 10px 18px;
    background-color: #f44336;
  }

  .imgcontainer {
    text-align: center;
    margin: 24px 0 12px 0;
  }

  img.avatar {
    width: 20%;
    border-radius: 50%;
  }

  .container {
    padding: 16px;
  }

  span.psw {
    float: right;
    padding-top: 16px;
  }
</style>
</head>
<body>

<h2>Login Form</h2>

<form class="c2">
  <div class="imgcontainer">
    <img src="img_avatar2.png" alt="Avatar" class="avatar">
  </div>

  <div class="container">
    <label for="uname"><b>Username</b></label>
    <input type="text" placeholder="Enter Username" name="uname" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>
        
    <button type="submit">Login</button>
    <label>
      <input type="checkbox" checked="checked" name="remember"> Remember me
    </label>
  </div>

  <div class="container" style="background-color:#f1f1f1">
    <button type="button" class="cancelbtn">Cancel</button>
    <span class="psw">Forgot <a href="#">password?</a></span>
  </div>
</form>
</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {  margin: 0 }

        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            background-color:rgb(169,30,81,0.8);
        }

        .registartion-form {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 600px;
            color: rgb(255, 255, 255);
            font-size: 18px;
            font-family: sans-serif;
            background-color: hsl(341, 47%, 43%);
            padding: 20px;
        }

        .registartion-form input,
        .registartion-form select,
        .registartion-form textarea {
            border: none;
            padding: 5px;
            margin-top: 10px;
            font-family: sans-serif;
        }

        .registartion-form .submit {
            width: 100%;
            padding: 8px 0;
            font-size: 20px;
            color: rgb(44, 44, 44);
            background-color: #ffffff;
            border-radius: 5px;
        }

        .registartion-form .submit:hover {
            box-shadow: 3px 3px 6px rgb(255, 214, 176);
        }
    </style>
</head>

<body>
    <div class="container">
        <form name="registration" class="registartion-form">
          <table>
            <tr>
              <td><label for="name">Name:</label></td>
              <td><input type="text" name="name" id="name" placeholder="your name"></td>
            </tr>
            <tr>
              <td><label for="email">Email:</label></td>
              <td><input type="text" name="email" id="email" placeholder="your email"></td>
            </tr>
            <tr>
              <td><label for="password">Password:</label></td>
              <td><input type="password" name="password" id="password"></td>
            </tr>
            <tr>
              <td><label for="phoneNumber">Phone Number:</label></td>
              <td><input type="number" name="phoneNumber" id="phoneNumber"></td>
            </tr>
            <tr>
              <td><label for="gender">Gender:</label></td>
              <td>Male: <input type="radio" name="gender" value="male">
                Female: <input type="radio" name="gender" value="female">
                Other: <input type="radio" name="gender" value="other"></td>
            </tr>
            <tr>
              <td><label for="language">language</label></td>
              <td>
                <select name="language" id="language">
                  <option value="">Select language</option>
                  <option value="English">English</option>
                  <option value="Spanish">Spanish</option>
                  <option value="Hindi">Hindi</option>
                  <option value="Arabic">Arabic</option>
                  <option value="Russian">Russian</option>
                </select>
              </td>
            </tr>
            <tr>
              <td><label for="zipcode">Zip Code:</label></td>
              <td><input type="number" name="zipcode" id="zipcode"></td>
            </tr>
            <tr>
              <td><label for="about">About:</label></td>
              <td><textarea name="about" id="about" placeholder="Write about yourself..."></textarea></td>
            </tr>
            <tr>
              <td colspan="2"><input type="submit" class="submit" value="Register" /></td>
            </tr>
          </table>
        </form>
      </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>link</title>
</head>
<body>
    <h3>Click any of the following links</h3>
    <a href="Task3.html"> Open in Self</a>
    <a href="index_for_github.html"> Open in parent</a>
    <a href="https://www.google.com/"> Open Google</a>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Create a Registration Form</title>

    <style>
        #register-form{
            width: 300px;
            background-color: white;
            padding:25px ;
            margin-left: auto;
            margin-right: auto;
        }

        .input-lable{
            margin: 0;
            margin-bottom: 4px;
            margin-top: 12px ;
        }

        .input-item{
          width: 100%;  
        }

        #term-check{
            margin-top: 12px;
            margin-bottom: 18px ;
        }
    </style>
</head>
<body style="background-color: lightblue;">

    <h1 style="text-align: center;">Registration</h1>
    <form action="" id="register-form">
        <div>
            <p class="input-lable">full name: </p>
            <input class="input-item" type="text" name="full name" placeholder="Full Name" autofocus required>
        </div>

        <div>
            <p class="input-lable">Email: </p>
            <input class="input-item" type="email" name="email" required>
        </div>

        <div>
            <p class="input-lable"> Age: </p>
            <input class="input-item" type="number" name="Age" min="10" max="25">
        </div>

        <div>
            <p class="input-lable"> password: </p>
            <input class="input-item" type="password" name="password" required maxlength="8">
        </div>

        <div>
            <p class="input-lable"> confirm password: </p>
            <input class="input-item" type="password" name="confirm password" required maxlength="8">
        </div>

        <div>
            <p class="input-lable">Gender: </p>
            <input type="radio" name="male" value="male">
            male </input>

            <input type="radio" name="female" value="female">
            Female </input>

            <input type="radio" name="other" value="other">
            other </input>

        </div>

        <div>
            <p class="input-lable">Security Question </p>

            <select class="input-item" name="Security-question" id="">
                <option value="first-pet-name"> What was your first pet name</option>
                <option value="first-job"> What was your first pet first-job</option>
                <option value="nickname"> What is your nickname</option>

            </select>
        </div>

        <div>
            <textarea class="input-item" name="answer" id="" cols="30" rows="10"></textarea>
        </div>

        <div>
            <input id="term-check" type="checkbox" name="term_conditions" value="accept"> I agree to accept term_conditions
        </div>

        <input type="Submit" value="Register">
    </form>
    
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Forms - input Types</title>
</head>
<body>
    <form action="">
        <!--        Text Input-->
        <h5>Full Name 
        <input type="text" name="Full Name" placeholder="Full Name" >
        </h5>
        <h5>Username
        <input type="text" name="Username" placeholder="Username">
        </h5>
        <h5> Gender 
            <select name="Gender" id="">
                <option value="Male"> male</option>
                <option value="Female"> Female</option>
                <option value="Other"> Other</option>
            </select></h4>

        <h5>password :
        <input type="password" name="password" placeholder="password" required maxlength="8" >
        </h5>
        <h5 >confirm password: 
            <input  type="password" name="confirm password" placeholder="password" required maxlength="8"></h5>
        <h5>date 
        <input type="date" name="date" max="1999-01-01">
        <input type="date" name=" enddate" min="2010-01-01"> </h5>

        <br>
        <input type="file" name="image">
    </form>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Practice table</title>

    <style>
        table{
            width: 600px;
            text-align: left;
            background-color: white ;
            margin: auto;
        }

table, td,th {border: 1px solid black;border-collapse:collapse ;padding: 8px;text-align: left;
            line-height: 1.3;
        }

        th{
            background-color: rgb(92, 225, 201);
        }
    .lable{
        font-weight: 600;
    }
    </style>
</head>
<body>
    <table>
        <tr><th colspan="3"> Invoice #1234ABC </th>
            <th> 28 july 2023</th>
        </tr>

        <tr>
            <td colspan="2">
                <span class="lable">Pay To:</span><br/>
                Company Name Here Inc.<br/>
                5 Main Street<br/>
                Anytown USA
            </td>

            <td colspan="2">
                <span class="lable">Customer :</span><br/>
                John Doe<br/>
                7 Elm Streeet<br/>
                Somewhere Canada
            </td>
        </tr>

        <tr>
            <th>Name/Description</th>
            <th>Qty.</th>
            <th>MRP</th>
            <th>Amount</th>
        </tr>

        <tr>
            <td>Biryani</td>
            <td>3</td>
            <td>400</td>
            <td>1200</td>
        </tr>

        <tr>
            <td>Chocolate Shake</td>
            <td>3</td>
            <td>200</td>
            <td>600</td>
        </tr>

        <tr>
            <th colspan="3">Subtotal</th>
            <td>1470</td>
        </tr>

        <tr>
            <th colspan="2">Tax</th>
            <td>10%</td>
            <td>180</td>
        </tr>

        <tr>
            <th colspan="3" style="text-align: left;">Total Amount:</th>
            <td>1620</td>
        </tr>
    </table>
</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>order and unorder list</title>
</head>
<body>
    <h1>List can be nested( list inside list) </h1>

    <!-- circle style  -->
    <ul style="list-style-type: circle, color #000 ;">
        <li>Coffee</li>
        <li>Tea</li>
        <dd style="list-style-type: circle;">
           <li>Green tea</li>
           <li>Black tea</li>
        </dd>
        <li>Milk</li>
    </ul>
</body>
</html>
