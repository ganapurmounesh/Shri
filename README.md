<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatibl" content="IE=edge">
        <meta name="viewprt" content="Width=devic-width,initial-scale=1.0">
        <link rel="stylesheet"href="stylesheet.css">
        <title>Document</title>
    </head>
    <body>
        <div class="Container">
        <form action=""method="post">
            <h2>Registation</h2>
            <div class=""content">
                <div class="input-box">
                   <label for="name">Full Name</label>
                   <input type="text" placeholder="Enter Full name" name="name" requirede>
                </div>
                <div class="input-box">
                    <label for="username">User Name</label>
                    <input type="text" placeholder="Enter username" name="uname" requirede>
                </div>
                <div class="input-box">
                    <label for="email">Email</label>
                    <input type="email" placeholder="Enter your valid email address" name="email" requirede>
                </div>
                <div class="input-box">
                    <label for="phone">Phone Number</label>
                    <input type="tel" placeholder="Enter Phone Number" name="phone" requirede>
                </div>
                <div class="input-box">
                    <label for="Password">Password</label>
                    <input type="password" placeholder="Enter new password" name="password" requirede>
                </div>
                <div class="input-box">
                    <label for="confirm-password">confirm password</label>
                    <input type="password" placeholder="confirm your password" name="confirmpassword" requirede>
                </div>            
                <span class="gender-title">Gender</span> 
                <div class="gender-category">
                    <input type="radio" name="gender" id="mele">
                    <lable for="male">Male</lable>
                    <input type="radio" name="gender" id="femele">
                    <lable for="female">Female</lable>
                    <input type="radio" name="gender" id="other">
                    <lable for="other">other</lable>
                </div>   
            </div>
            <tr><td>photo:</td><td> <input type="file" name="photo" size=""></td></tr>
            <div class="alert">
                <p>By clicking sign up,you agree to our<a href="#">Terms,</a> <a href="#">privacy policy</a>and <a 
                    herf="#">cookies policy.</a> You may receive SMS notifications fron us and can opt out at any time.</p>
            </div>
            <div class="button-container">
                <button type="submit">Register</button>
            </div>            
       </form>
    </div>

</body>
</html>
