<template>
    <div class="topnav">
            
            <a href="/">Home</a>
            <a href="/about">About</a>
            <a href="/menu">Exercises</a>
            <a href="/language">Languages</a>
            <a href="#Profile">Profile</a>
            <a href="#Logout">Logout</a>          

    </div>

  
</template>

<script>
  export default {
    name: 'Users',
  }
</script>

<style>

    
    .topnav {
    background-color: white;
    overflow: hidden;
    width:100%;
  }
  
  /* Style the links inside the navigation bar */
  .topnav a {
    float: left;
    color: black;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
    font-family: Futura Hv BT;
    
    
  }
  
  /* Change the color of links on hover */
  .topnav a:hover {
    background-color: #CBE7F8;
    color: black;
  }
  
  /* Add a color to the active/current link */
  .topnav a.active {
    background-color: #CBE7F8;
    color: black;
  }
  input[type=text] {
      width: 130px;
      -webkit-transition: width 0.4s ease-in-out;
      transition: width 0.4s ease-in-out;
    }
    
    /* When the input field gets focus, change its width to 100% */
    input[type=text]:focus {
      width: 100%;
    }
  /* Bordered form */
  form {
      border: 10px solid #f1f1f1;
    }
    
    /* Full-width inputs */
    input[type=text], input[type=password] {
      width: 100%;
      padding: 12px 20px;
      margin: 8px 0;
      display: inline-block;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }
    
    /* Set a style for all buttons */
    button {
      background-color: #008080;
      color: white;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      cursor: pointer;
      width: 100%;
    }
    
    /* Add a hover effect for buttons */
    button:hover {
      opacity: 0.8;
    }
    
    /* Extra style for the cancel button (red) */
    .cancelbtn {
      width: auto;
      padding: 10px 18px;
      background-color: #f44336;
    }
    
    
    
    /* Add padding to containers */
    .container {
      padding: 16px;
      font-family: "Century Gothic";
    }
    
    /* The "Forgot password" text */
    span.psw {
      float: right;
      padding-top: 16px;
    }
    
    /* Change styles for span and cancel button on extra small screens */
    @media screen and (max-width: 300px) {
      span.psw {
        display: block;
        float: none;
      }
      .cancelbtn {
        width: 100%;
      }
    }
</style>