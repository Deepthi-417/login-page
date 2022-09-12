html code for login page
<!DOCTYPE html>   
<html>   
<head>  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<title> Login Page </title>  
<style>   
Body {  
  font-family: Calibri, Helvetica, sans-serif;  
  background-image: url("imageee.jpg.jpg");
  background: position -400px 0px;            
  background-repeat:no-repeat;
            background-attachment: fixed;
            background-size:fixed;
            background-size:cover;
            background-position: fixed;
}  
button {   
       background-color: navy;   
       width: 100%;  
        color: orange;   
        padding: 15px;   
        margin: 10px 0px;   
        border: none;   
        cursor: pointer;   
         }   
 form {   
        border: 1px solid navy;
        border: spacing 0px; 
        mask-border:padding 0px;
    }   
 input[type=text], input[type=password] {   
        width: 100%;   
        margin: 10px 0;  
        padding: 12px 20px;   
        display: inline-block;   
        border: 2px solid green;   
        box-sizing: border-box;   
    }  
 button:hover {   
        opacity: 0.7;   
    }   
  .cancelbtn {   
        width:100%;   
        padding: 10px 15px;  
        margin: 10px 0px;  
    }   
        
     
 .container {   
    text-align:left;
        padding: 10px;   
        width:100%;
        background-color:rgba(0,0,0,0.5);
        width:25%;
        font-size:20px;
        border: radius 5px;
        border:1px soid rgba(225,255,255,0.3);
        box-shadow: 2px 2px 15px
        rgba(0,0,0,0,3);
        color:#fff;
        position:absolute;
        top: 50%;
        left:50%;
        transform: translate(-50%,-50%);

 }
 label{
    font-family:sans-serif;
 }
 .h1{
    text-align: center;
}
</style>   
</head>    
<body>    

    <form>  
        <div class="container"> 
            <h1 style="color:black;">Login</h1>  

            <div class="d-flex justify-content-centre">
                <div style="flex-grow: 4;"></div>
    <label>Username</label>   
           <input type="text" placeholder="Enter Username" name="username" required>  
        <label>Password</label>
            <input type="password" placeholder="Enter Password" name="password" required>   
            <button type="submit">Login</button>   
           <input type="checkbox" checked="checked"> Remember me   
            <button type="button" class="cancelbtn"> Cancel</button>   
            Forgot <a href="#"> password? </a>  
        </div>   
    </form>     
    <div input="search-btn">Looking for anything else?!....</div>

</body>     
</html>
//reference from youtube 
