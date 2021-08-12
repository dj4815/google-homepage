<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Homepage</title>
    <style>


 .external {
        display: table;
        position: absolute;
        top: 0;
        left: 0;
        height: 100%;
        width: 100%;
 }

 .middle {
        display: table-cell;
        vertical-align: middle;
 }

 .internal {
        margin-left: auto;
        margin-right: auto;
        width: auto;
 }

.topnav {
  overflow: hidden;
}

.topnav a {
  float: left;
  color: #000000;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
 
}

.topnav a:hover {
  text-decoration: underline;
  color: black;
}

.navbar {
  background-color: #ffffff;
  overflow: hidden;
  position: fixed;
  bottom: 0;
  width: 100%;
}

.navbar a {
  float: left;
  display: block;
  color: #000000;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

.navbar a:hover {
  text-decoration: underline;
}

* {
  box-sizing: border-box;
  border-radius: 50px;
}

form.example input[type=text] {
  padding: 10px;
  font-size: 17px;
  border: 1px solid rgb(216, 216, 216);
  width: 50%;
  background: #ffffff;
}


form.example::after {
  content: "";
  clear: both;
  display: table;
}

.button {
  background-color: #f7f7f7; 
  border: none;
  border-radius: 10px;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  color: black;
  display: inline-block;
  font-size: 16px;

}

.button:hover {
  border: 1px solid grey;
}

}
</style>
</head>
<body>

  <div class="topnav">
    <a href="#about">About</a>
    <a href="#store">Store</a>
    <a style ="float: right" href="#images">Images</a>
    <a style ="float: right" href="#gmail">Gmail</a>
  </div> 
      <div class="external">
    <div class="middle">
      <div class="internal">
   <div align="center"><img src="images/google-logo.png" alt="The Google logo">
  
  
    <form align="center" class="example" action="/action_page.php" style="margin:auto;max-width:auto">
      <input type="text" name="search2"></form>
      <form>
      <button class="button">Google Search</button><button class="button">I'm Feeling Yucky</button>
    </form>
</div></div>
       
        <div class="navbar">
          <a href="#advertising">Advertising</a>
          <a href="#business">Business</a>
          <a href="#how-search-works">How Search works</a>
          <a style="float: right" href="#settings">Settings</a>
          <a style="float: right" href="#terms">Terms</a>
          <a style="float: right" href="#privacy">Privacy</a>
        </div>  
</body>
</html>