<!DOCTYPE html>
<html lang="en">
<head>

<title>Pancake House</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">
</head>
<style>

element.style {
    letter-spacing: 4px;
    
   } 
    
    hr { border: 0;
      border-top: 1px solid #eee;
      margin: 20px 0;
      

    }
   
    body {
       
        background-color: rgb(235, 204, 243);
        padding: 300px;
       
       
    }
    

    .navbar {
    
        top: 0;
        position: absolute;
        width: 100%;
        height: 50px;
        float: none;
        margin:0px auto;
        left:0px;
        right:0px;
        z-index: 1;
       
    
    }


     .active {
        background-color: rgb(255, 255, 255);
   
 
    }
   
    
    ul {

     list-style-type: none;
     margin:0;
     padding: 0;
     overflow: hidden;
     background-color: #daf7da;   
 
    }


    li {
      float: left;

    }

     li a{
       display: block;
       color: rgb(0, 0, 0);
       text-align: center;
       font-size: 20px;
       font-family: Arial, Helvetica, sans-serif;
       font-weight: 600;
       padding: 20px 25px;
       text-decoration: none;
       border-right: 1px solid #bbb;
       border-left: 1px solid #bbb;
       
    }

     li a:hover {
        background-color: rgb(229, 188, 188);
    }
   
    @media print {
        h1 {page-break-before: always;}
      }

    h1 {
       text-align: center;
       font-family: 'Dancing Script', cursive;
       font-size: 150px;
       position: absolute;
       bottom: 55%;
       float: top;

    }

    .mySlides {display:none;}

    .mySlides{

     display: block;
     margin-left: auto;
     margin-right: 50px;
     width: 60%;
     height: 40%;
     border-radius: 50%;
     
     
     
    }

   * {
       box-sizing: border-box;
   }

   /*Style inputs */
   input[type=text], select, textarea {
       width: 100%;
       padding: 12px;
       border: 1px solid #ccc;
       margin-top: 6px;
       margin-bottom: 16px;
       resize: vertical;
   }

   input[type=submit] {
      background-color: wheat;
      color: white;
      padding: 12px 20px;
      border: none;
      cursor: pointer;
   }

   input[type=submit]:hover {
       background-color: #000000;

   }

   /* Style the container/contact section */
    .container {
      border-radius: 5px;
      background-color:rgb(235, 204, 243);
      padding: 10px;
    }

   /* Create two columns that float next to eachother */
     .column {
      float: left;
      width: 50%;
      margin-top: 6px;
      padding: 20px;

     } 

   /*Clear floats after the columns */
      .row:after {
        content: "";
        display: table;
        clear: both;
      }

   /* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
      @media screen and (max-width: 600px) {
       .column, input[type=submit] {
          width: 100%;
          margin-top: 0;
         
       }
      }
      
   .about {

    padding-left: 65%;
    font-family: 'Courier New', Courier, monospace;
    font-size: 40px;
    
   }

 
  .img:hover {
    transform: scaleX(-1);
  }
   
   .description {

     font-size: 20px;
     font-family: 'Courier New', Courier, monospace;
     padding-left: 60%;
     height: 300px;
     float: none;
     
   }

   .clearfix {
     overflow: auto;

   }

   .img {

      float: left;
      border-radius: 10px;
      width: 50%; 
      height: 60%;
      
   }

    element.style {
        width: 100%;
    }

    hr {border: 0;
    border-top: 1px solid #eee;
    margin: 20px 0
    }
      div{
          display: block;
      }
        
        .menu {
            
            padding: 12px 24px!important;
            text-align: center!important;
            font-family: "Playfair Display";
            font-size: 40px;
            letter-spacing: 5px;
            font-weight: 600;
            margin: 10px 0;
           
           
            }

        h3 {

        font-family: "Playfair Display";
        letter-spacing: 5px;
        font-weight: 400;
        margin: 10px 0;
        font-size: 25px;
        display: block;
        

       }

        p {

          color: rgb(102, 84, 84)!important;
          display: block;
          

       }

       .waffle {
          border-radius: 10px;
          float: right;
          width: 25%; 
          height: 20%;
          

   }

</style>

<body>
<!-- Navbar (sit on top) -->

<div class="navbar">
    <ul class="active">
        <li style="background-color:rgb(134, 132, 132)"><a href="HomeLink" class="bar-item">Home</a></li>
        <li><a href="MenuLink" class="bar-item">Menu</a></li>
        <li><a href="NewsLink" class="bar-item">News</a></li>
        <li style="float:right"><a href="ContactLink" class="bar-item">Contact</a></li>
        <li style="float:right"><a href="AboutLink" class="bar-item">About</a></li>
      </ul>
    </div>

<br><br>

<!-- Slide Show -->

<div  class="top">
<h1>Pancake house</h1>

<div class="pancakehouse">
  <img class="mySlides" src="https://upload.wikimedia.org/wikipedia/commons/4/43/Blueberry_pancakes_%283%29.jpg" alt="strawberrypancakes">
  <img class="mySlides" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Souffle_Pan_Cake_in_Japan.jpg/1280px-Souffle_Pan_Cake_in_Japan.jpg" alt="japanesepancake">
  <img class="mySlides" src="https://upload.wikimedia.org/wikipedia/commons/3/31/Cheese_blintzes_with_blackberries.jpg" alt="cheesepancake">
 
  </div>

</div>

   <hr>
<!-- About Section -->

     <div class="aboutsection">
        <div class="clearfix">
        <img class="img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8f/Indonesian_chocolate_pancake_with_ice_cream.JPG/1280px-Indonesian_chocolate_pancake_with_ice_cream.JPG" alt="chocolatepancake">
        <h2 class="about">About Pancake House</h2>
        <p class="description">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec ut fermentum odio. Donec elit sapien, ullamcorper sed viverra sed, vehicula id neque. Sed blandit ullamcorper erat, sed interdum elit. Integer ut eleifend neque. Integer elementum hendrerit nulla, id sollicitudin leo tempor a. Quisque mattis lobortis dui eu tincidunt. Sed eu odio sed dui aliquam venenatis in et lacus. Fusce et leo elit.</p>
        </div>
    </div>
       
<hr>

<!-- Menu Section -->

   <div class="menusection">

      <div class="clearfix">

       <h2 class="menu">Our Menu</h2>
         <br>
         <img class="waffle" src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Waffle_with_strawberries_and_confectioner%27s_sugar.jpg/1920px-Waffle_with_strawberries_and_confectioner%27s_sugar.jpg" alt="wafflepancake">

           <h3>French Crêpes</h3>

            <p class="pancake1">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

           <h3>Belgian Waffles</h3>
            <p class="pancake2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

           <h3>Scotch pancakes</h3>
              <p class="pancake3">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

           <h3>Special Pancakes's house</h3>
           <p class="pancake4">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

      </div>

    </div>
<hr>

<!-- Contact Section-->

    <div class="container">

      <div style="text-align:center">
        <h2>Contact Us</h2>
        <p>Swing by for a sweet pancake, or leave us a message:</p>
    </div>
    <div class="row">
     </div>
     <div class="column">
      <form action="/action_page.php">
       <label for="fname">First Name</label>
       <input type="text" id="fname" name="firstname" placeholder="Your name..">
       <label for="lname">Last Name</label>
       <input type="text" id="lname" name="lastname" placeholder="Your last name..">
       <label for="country">Country</label>
       <select id="country" name="country">
         <option value="australia">Australia</option>
         <option value="canada">Canada</option>
         <option value="usa">USA</option>
       </select>
       <label for="subject">Subject</label>
       <textarea id="subject" name="subject" placeholder="Write something.." style="height: 170px"></textarea>
       <input type="submit" value="Submit">
    </form>
     </div>
    </div>
  
<script>
     var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}    
  x[myIndex-1].style.display = "block";  
  setTimeout(carousel, 2000); // Change image every 2 seconds
}

</script>

</body>
</html>
