CSS BASIC
### Index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 40px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:white;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:rgb(243, 226, 226);
        
        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{

        background-color:black;
        height: 30px;
        bottom: 0;
        width: 100%;
        color: white;
        position: absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(44, 11, 71);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:rgb(238, 197, 197);
        }
        .line{
            position: absolute;
            top:43%;
        color:  black;
            width:100%;
            size:5px;
        }
        .coform {
            background-color: rgb(236, 226, 207);
            top:43%;
        }
        .coform form{
            position: absolute;
            top:45%;
        }
        .coform form h3{
            font-size:30px;
        }
        .coform form input{
            margin-left: 10px;
            width:500px;
            height:25px;
        }
        .coform form textarea{
            margin-left: 5px;
        }
        .coform form button{
            position: absolute;
            background-color: rgb(240, 219, 192);
            color:black;
            border-radius: 20%;
            margin-left: 10px;
        }
        #submit{
            left:0px;
            width:20%;
        }
        
        #ci{
            font-size: 30px;
            margin-left: 40px;
        }
        .info{
            position:absolute;
            top:44.2%;
            font-size: 20px;
            background-color: rgba(0, 0, 0, 0.781);
            padding:70px 250px 95px 147px ;
            margin-left: 840px;
            color: rgb(221, 209, 209);
            border: 4px;
            border-color: rgb(224, 224, 213);
            border-style: solid;
        }
        .coform form{
            background-color:rgba(137, 48, 48, 0.781) ;
            color: rgb(91, 151, 204);
            top:44.3%;
            margin-left: 20px;
            padding:0px 282px 50px 0px;
            border: 4px;
            border-color: thistle;
            border-style: solid;
        }
        .u{
            text-align: center;
            font-size: larger;
        }
    </style>
    </head>
    <body>
        <header>
            <h2>SMARTO</h2>
            </header>
            <nav class="navbar">
            
            <ul>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="exstayre.html">Home</a></li>
            </ul>
            </nav>
            <div class="search"><input type="text" placeholder="Enter to Search">
                <button>Search</button></div>
                
                <div class="coform">
                    <form>
                      <h3>&nbsp;Contact Us</h3>
                      <input type="text" placeholder="Your Name"><br><br>
                      <input type="text" placeholder="Your Email"><br><br>
                      <textarea rows="12" cols="66" ></textarea><br>
                      <button id="submit">Submit</button>
                    </form>
                </div>
        <div class="info">
            <h3 id="ci" >Contact Information</h3><br0>
            <b>Address: </b>17 ,Kundrathur main road,Porur, Chennai, Tamil Nadu<br><br>
            <b>Email: </b>massbarath17002@gmail.com<br><br>
            <b>Phone: </b>9500496619
        </div>
       
    </div>
                <footer class="u">
                    Designed and Developed by Barath&copy;2024
                    </footer>
                   
    </body>
    </html>
```
### exstayre.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Myfirstwebsite</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        h1 {
            color: black;
            font-size: 45px;
            font-family: 'Times New Roman', Times, serif;
            position: absolute;
            top: 35%;
        }

        body {
            background-color: rgb(193, 174, 143);
            margin: 0;
           
}
        

        .navbar ul {
            list-style-type: none;
            background-color: rgb(255, 255, 255);

        }

        .navbar a {
            color: rgb(152, 82, 82);
            text-decoration: none;
            padding: 25px;
            display: flex;
            text-align: left;
            position: relative;
            font-size: 20px;
            top: -95px;

        }

        .navbar a:hover {
            background-color:powderblue;
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: black;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 55px;
            background-color: white;
            margin-left: 10px;
            
        }

        footer {

            background-color: black;
            height: 30px;
            bottom: 0;
            width: 100%;
            color: white;
            position: absolute;

        }

        header {
            background-color: white;
            height: 10vh;
            width: 100%;
            color: white;
        }

        header h2 {
            position: absolute;
            color: black;
            margin-top: 10px;
            margin-left: 10px;
        }

        .first,
        .second,
        .third {
            font-size: 50px;
            margin-left: 2px;
        }

        .second {
            color:rgb(188, 144, 144);
            text-align: center;
        }

        .third {
            text-align: center;
        }
        .first{
            margin-left:5px;
        }
        .search input,
        button {
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color: rgb(186, 165, 138);
        }

        .d {
            position: absolute;
            top: 65%;
            font-size: 20px;
        }

        .search input {
            width: 18%;
            height: 30px;

        }

        .search button,
        .d button {
            color: white;
            background-color:rgb(216, 205, 197);
            padding: 5px;
            text-align: center;
        }

        .d button {

            margin-right: 500px;
            padding: 20px 30px 20px 30px;
            border-radius: 30px;
            border-color: none;
        }

        #joinus:hover {
            cursor: pointer;
            color: rgb(121, 173, 155);
            background-color:rgb(244, 232, 210);
        }

        .login form {
            position: absolute;
            right: 100px;
            top: 30%;
            margin: 20px;
            box-sizing: border-box;
            border-color: rgb(205, 185, 158);
            background-color:rgba(59, 47, 47, 0.781);
            padding: 80px 80px 200px 80px;
        }

        .login form button {
            background-color:rgb(189, 171, 156);
            margin-right: 50px;
            color: white;
            padding: 10px 35px 10px 35px;
            font-size: 15px;
            border-radius: 15%;
            width: 60%;
        }

        .login form h3 {
            color: rgb(186, 151, 151);
            position: absolute;
            top: 0%;
            padding: 5px 30px 5px 30px;
            background-color: rgb(42, 117, 117);
            text-align: center;
            margin-left: 18px;


        }

        .login form input {
            height: 35px;
            border: none;
            border-bottom: 2px solid rgb(35, 92, 110);
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            font-size: 15px;
            background: transparent;
        }

        .login ::placeholder {
            color: white;
            opacity: 1;
        }

        .login form h4 {
            position: absolute;
            top: 55%;
            color: white;
            margin-left: 25px;
        }

        .login form .Signup {
            position: absolute;
            top: 70%;
            color: white;
            margin-left: 35px;
        }

        .login form .Signup b a {
            text-decoration: none;
            color: rgb(25, 102, 127);
            margin-left: 20px;
        }

        .login form h5 {
            position: absolute;
            top: 73%;
            color: white;
            margin-left: 65px;
        }

        .login form .image {
            position: absolute;
            top: 85%;
            margin-left: 40px;

        }

        .d p {
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        .t{
            text-align: center;
            font-size: larger;
        }
        .d{
            margin-left: 10px;
            color:rgb(165, 185, 132);
        }

    </style>
</head>

<body>
    <header>
        <h2>SMARTO</h2>
    </header>
    <nav class="navbar" >

        <ul>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="exstayre.html">Home</a></li>
        </ul>
    </nav>
    <div class="search"><input type="text" placeholder="Enter to Search">
        <button>Search</button>
    </div>
    <h1 align="top">
        <div class="first">Learn to Code!!
            </div>
        <div class="second">Connecting Coders, Building Better Tomorrow.</div>
    </h1>
    <div class="d">
        <p> &nbsp;The zenith of coding websites lies not only in the lines of code but in the vibrant tapestry of a community<br>&nbsp;passionately innovating and evolving.</p>
        <button id="joinus">Join Us</button>
    </div>
    <div class="login">
        <form>
            <h3>Login Here</h3>
            <input type="text" placeholder="Username or Email"><br><br>
            <input type="password" placeholder="Password"><br><br><br>
            <button>Login</button>
            
            <div class="Signup"><b><a href="">Sign up</a></b> here</div>
            <h5>Login with</h5>
            <div class="image">
                <a href="" style="padding-right: 25px; color: rgb(38, 133, 217);"><i class="bi bi-google"></i></a>
                <a href="" style="padding-right: 25px; color: rgb(12, 57, 96);"><i class="bi bi-facebook"></i></a>
                <a href="" style="padding-right: 20px; color: rgb(86, 147, 201);"><i class="bi bi-twitter"></i></a>
            </div>
            
        </form>
    </div>
    <footer class="t">
        Designed and Developed by Barath,2024
    </footer>

</body>
</html>
```
### people.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 30px;
        font-family:'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:rgb(203, 143, 45);
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color: white;        
        }
        .navbar a{
         color:rgb(0, 0, 0);
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:rgb(184, 67, 25);
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color:rgb(230, 209, 209);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:rgb(187, 130, 130);
        }
        .small
        {
           width:190px;
           height:190px;
           margin:10px
        }
        .border{
        border-width:2px;
        border-color:black;
        border-style:solid;
        border-radius:50%;
        }
        .cirpic{
            position:absolute;
            top:35%;
            margin-left: 70px;
            
        }
        .text{
            position:absolute;
            top:55%;
            margin-left:35px;
            font-size:20px;
            
        }
        .text2{
            position:absolute;
            top:60%;
            margin-left:58px;
            font-size:20px;
        }
        .class{
            text-align: center;
            font-size: larger;
        }
    
    </style>
</head>
<body>
    <header>
        <h2>ELITE</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="products.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="exstayre.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
        <div class="cirpic">
            <img class="small border" src="founder  " width="500px">
            <img class="small border" src="co founder" width="500px" >
            <img class="small border" src="ceo" width="500px">
            <img class="small border" src="director" width="500px">
            <img class="small border" src="manager" width="500px">
            
            
        </div>
        <div class ="text">
            <table cellpadding="70">
                <tr class="head">
                    <th>JOHN</th>
                    <th>STEVE</th>
                    <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;JOSEPH</th>
                    <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HARISH</th>
                    <th>&nbsp;&nbsp;&nbsp;DINESH</th>
                </tr>
            </table>
        </div>
        <div class="text2">
            <table cellpadding="68">
                <tr>
                    <td>FOUNDER</td>
                    <td>CO-FOUNDER</td>
                    <td>CEO</td>
                    <td>DIRECTOR</td>
                    <td>MANAGER</td>
                    
                </tr>
            </table>
        </div>
      
            <footer class="class">
                Designed and Developed by Barath,2024
                </footer>
               
</body>
</html>
```
### products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 45px;
        font-family:'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:rgb(246, 240, 229);
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:rgb(237, 230, 230);
        
        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:rgb(68, 68, 6);
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{
        background-color:black;
        height:30px;
        bottom: 0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(114, 154, 33);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .contain{
                position: absolute;
                top:12%;
                width:1240px;
                height:750px;
                margin-left: 90px;
               margin-top: 28px;
                background-color:rgb(201, 176, 137);
                font-size: larger;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                
                
                }
                .contain p b{
                    font-size: 30px;
                    padding-left: 45px;
                }
                .contain p{
                    font-size: 18px;
                    padding-left: 10px;
                    padding:5px 20px 0px 15px ;
                    
                }
                .contain img{
                   margin-top: 10px;
                   padding-left: 10px;
                   padding:20px 20px 0px 20px;
                }
                .m{
                    text-align: center;
                    font-size: large;
                }

    </style>
</head>
<body>
    <header>
        <h2>SMARTO</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="products.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="exstayre.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
            <div class="contain">
                <table >
                    <tr>
                        <td><img src="web" height="200px" width="200px">
                            <p><b>WEBDESIGN&nbsp;</b><br>
                                
                               
                
                        </p></td>
                        <td><img src="js" height="200px" width="200px"><br>
                            <p><b>JAVASCRIPT&nbsp;</b><br>
                                
                                
                        </p></td>
                        <td><img src="python" height="200px" width="200px"><br>
                            <p><b>PYTHON <br>
                        
                        </p></td>
                        <td><img src="java" height="200px" width="200px"><br>
                            <p><b>JAVA</b><br>
                               
                                
                        </p></td>
                        <td><img src="c++" height="200px" width="200px"><br>
                            <p><b>C/C++</b><br>
                                
                                
                        </p></td>  
                    </tr>
                    <tr>
                        
                        </p></td>  

                    </tr>
                </table>
            </div>
            <footer class="m">
                Designed and Developed by Barath,2024
                </footer>
               
</body>
</html>
```
### Output:
![Screenshot 2024-07-06 211953](https://github.com/Barath0271/css-basic/assets/135820464/6590de18-2b90-4b0e-bc17-2dfb9677a77e)
![Screenshot 2024-07-06 212755](https://github.com/Barath0271/css-basic/assets/135820464/b14c4018-6424-4299-9f6a-8fdc0096ec1f)
![Screenshot 2024-07-06 211252](https://github.com/Barath0271/css-basic/assets/135820464/02a5c87b-d1c5-4601-8bb8-71c6dea048c7)
