# my_first_webpge
I have made a lil' first ever website
<br>
//html<br>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY PRACTISEt</title>
</head>
<link rel="stylesheet" href="style.css">
<link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.8.0/fonts/remixicon.css"
    rel="stylesheet"
/>
<font-family: monument extended></font-family:>
<body>
    <div id="main">
        <div id="sub-div">
            <div >
                <i class="ri-menu-unfold-3-line"></i>
                <button id="menu">Menu</button>
            </div>
            <div id="sprituality">
                <h2>Spirituality</h2>
            </div>
            <div>
                <button id="login">Login</button>
                <button id="signup">Sign Up</button>    
            </div>
        </div>
    <h1 id="text">MEDITATION</h1>
    <h5 id="btm-left">peace of mind</h5>
    </div>
 <img src="https://plus.unsplash.com/premium_vector-1683141200616-a7c1c8566b6c?q=80&w=675&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
    alt="meditation image" id="m1">
    <img src="https://plus.unsplash.com/premium_vector-1689096683189-99c135c4f20b?w=352&dpr=2&h=367&auto=format&fit=crop&q=60&ixlib=rb-4.1.0"
    alt="meditation image" id="m2">
    <img src="https://plus.unsplash.com/premium_vector-1683141200616-a7c1c8566b6c?q=80&w=675&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
    alt="meditation image" id="m3">
    <img src="https://plus.unsplash.com/premium_vector-1722926950860-10f2cc4d94e1?q=80&w=880&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
    alt="meditation image" id="m4">
    <img src="https://plus.unsplash.com/premium_vector-1708543744973-795d3d9de3b3?q=80&w=737&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
    alt="meditation image" id="m5">

</body>
</html>
//css
*{
    margin:0;
    padding:0;
    box-sizing: border-box;
    background-color: rgb(232, 151, 232);
}
html,body{
    height: 100%;
    width: 100%;
    font-family: monument extended, sans-serif;
   
}
#sub-div{
    display: flex;
    justify-content: space-between;
    padding: 0px 40px;
}
#sub-div i{
    border: 1.5px solid rgb(0, 0, 0);
    border-radius: 30px;
}
#menu{
    border: 1.5px solid rgb(0, 0, 0);
    margin-top: 20px;
    color: white;
    border-radius: 50px;
    padding: 7px 8px;
    cursor: pointer;
    
}
#menu:hover{
    background-color: rgb(232, 44, 147);
}
#buttons{
    display: flex;
    justify-content: space-between;

}
#login{
    font-size: 16px;
    margin-top: 20px;
    border: 1.5px solid rgb(0, 0, 0);
    color: white;
    border-radius: 30px;
    padding: 7px 8px;
    cursor: pointer;
}
#login:hover{
    background-color: rgb(232, 44, 147);
}
#signup{
    font-size: 16px;
    margin-top: 20px;
    border: 1.5px solid rgb(0, 0, 0);
    color: white;
    border-radius: 50px;
    padding: 7px 8px;
    cursor: pointer;
}
#signup:hover{
    background-color:rgb(232, 44, 147);
}
#sprituality{
    display: flex;
    margin-top: 20px;
    font-weight: 600;
    color: black;
    justify-self: center;
    align-self: center;
    height: 60px;
    text-transform: uppercase;
}

#text{
    font-size: 250px;
    text-transform: uppercase;
    position:absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 100%;
    text-align: center;
}
img{
    position: absolute;
    top: 50%;
    left: 50%;
    object-fit: cover;
    height: 200px;
    width: 200px;
    border-radius: 50px;
    transform: translate(-50%, -50%);
    height: 350px;
    width: 250px;
}
#m1{
    transform: translate(-50%, -50%) rotate(-40deg);
}
#m2{
     transform: translate(-50%, -50%) rotate(-30deg);
}
#m3{
    transform: translate(-50%, -50%) rotate(-20deg);
}
#m4{
    transform: translate(-50%, -50%) rotate(-10deg);
}
#btm-left{
    position: absolute;
    bottom: 20px;
    left: 20px;
    font-size: 17px;
}
