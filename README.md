# html.shlok
<!DOCTYPE html>
<html lang="en" data-bs-theme="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up Web Page</title> <link rel="preconnect" href="https://fonts.gstatic.com">
   
    <style media="screen">
        *,
        *:before,
        *:after{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        body{
            background-color: #171524;
        }
        .background{
            height: 260px;
            width: 250px;
            position: absolute;
            transform: (-50%,-50%);
            left: 55%;
            top: 45%;
        }
        .background .shape{
            height: 200px;
            width: 200px;
            position: absolute;
            border-radius: 50%;
        }
        .shape:first-child{
            background: linear-gradient(
                #1a5a5ad8,
                #207fbe
            );
            left: -400px;
            top: -330px;
        }
        .shape:last-child{
            background: linear-gradient(
                to right,
                #ccda0db4,
                #1a5a1dd8
            );
           right: 10px;
           bottom: -150px;
        }
        form{
            height: 520px;
            width: 400px;
            background-color: rgba(12, 15, 153, 0.568);
            position: absolute;
            transform:translate(-50%,-50%);
            top: 50%;
            left: 50%;
            border-radius: 10px;
            backdrop-filter: blur(10px);
            border: 2px solid rgba(12, 14, 153, 0.212);
            box-shadow: 0 0 40px rgba(166, 153, 179, 0.832);
            padding: 50px 35px;
        }
        form *{
            font-family: 'Poppins',sans-serif;
            color: #ffffff;
            letter-spacing: 0.5px;
            outline: none;
            border: none;
        }
        form h3{
            font-size: 32px;
            font-weight: 500;
            line-height: 42px;
            text-align: center;
        }
        label{
            display: block;
            margin-top: 30px;
            font-size: 16px;
            font-weight: 500;
        }
        input{
            display: block;
            height: 50px;
            width: 100%;
            background-color: rgba(124, 141, 236, 0.423);
            border-radius: 3px;
            padding: 0 10px;
            margin-top: 8px;
            font-size: 14px;
            font-weight: 200;
        }
        ::placeholder{
            color:#e6e5e5
        }
        button{
            margin-top: 50px;
            width: 100%;
            background-color: hsla(9, 92%, 48%, 0.847);
            color: #ffffff;
            padding: 12px 0;
            font-size: 20px;
            font-weight: 600;
            border-radius: 5px;
            cursor: pointer;
        }
        /*.media{
            display: flex;
            margin-top: 25px;
            justify-content:space-around;
            
        }
        .media div{
            background: rgba(46, 38, 38, 0.404);
            width: 150px;
            border-radius: 3px;
            padding: 6px 10px 10px 5px;
            background-color: rgba(255,255,255,0.27);
            color: #eaf0fb;
            text-align: center;
        }
        .media div:hover{
            background-color: rgba(255,255,255,0.47);
        }
        .media .fb {
            margin-left: 25px;
        }
        .media .i {
            margin-right: 4px;
        }*/
    </style>
</head>

       <div class="background">
        <div class="shape"></div>
        <div class="shape"></div> 
       </div>   
    <form>

        <h3>Login Here</h3>

        <label for="username">Username</label>
        <input type="text" placeholder="Email or Phone No." id="username">
        <label for="password">Password</label>
        <input type="password" placeholder="Password" id="password">
        <button>Log In</button>
       <!--<div class="media"></div>
            <div class="go"><i class="fab fa-google"></i>Google</div>
            <div class="go"><i class="fab fa-facebook"></i>Facebook</div>
        </div>-->

</body>
</html>
