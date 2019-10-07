# RedesignYourWebPage
<html>
<head>
    <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <link href="https://fonts.googleapis.com/css?family=Playfair+Display:700i&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <style type="text/css">
        body{
            padding:5px;
        }
        .container{
           position:relative;
        }
        .topnav {
            background-color: #333;
           overflow: hidden;
        }
.topnav a {
  float: right;
  display:block;
  color: #f2f2f2;
  text-align: center;
  padding: 20px 16px;
  text-decoration:none;
  font-size: 16px;
    font-family:"playfair Display,serif";
}
.topnav a:hover {
  background-color:lightgrey;
  color: black;
}
.topnav a.active {
  background-color: #816050;
  color: white;
}
.topnav .icon {
  display:none;
}
        #bottom{
            position:absolute;
            color:beige;
            margin:none;
           background-color:#816050;
            position:absolute;
            bottom:0%;
            left:1.3%;
            right:0.45%;
            margin-right:10px;
        
         }
        
        #horizontaleft{
            width:70px;
            height:5px;
            margin-bottom:100px;
            top:10%;
            background-color:white;
            float:left;
            align-self: center;
        }
        
        #horizontalright{
            width:70px;
            height:5px;
            margin-bottom:100px;
            top:10%;
            background-color: white;
            float:right;
            align-self: center;
        }
        #topbar{
            width:5px;
            height:60px;
            background-color:white;
            top:0%;
            bottom:auto;
            margin-left:200px;
        }
        #bottombar{
            position: absolute;
           width:5px;
            height:60px;
            background-color:white;
            top:auto%;
            bottom:-2.3%;
            margin-left:200px;
        }
        #righttext{
            position:absolute;
            color:beige;
            margin:none;
           background-color:#816050;
            align-items:center;
            width:400px;
            bottom: 0%;
            top:0%;
            left:auto;
            right:5%;
            margin-right:100px;
        }
        #lefttext{
            position:absolute;
            color:#816050;
            background-color:white;
            align-items:center;
            width:500px;
            height:500px;
            bottom:0%;
            top:0%;
            right:auto;
            left:8%;
            margin-right: 200px;     
        }
        #topbar1{
             position: absolute;
            width:5px;
            height:60px;
            background-color:#816050;
            top:0%;
            bottom:auto;
            margin-left:200px;
        }
        #bottombar1{
            position: absolute;
           width:5px;
            height:60px;
            background-color:#816050;
            top:auto%;
            bottom:7.1%;
            margin-left:200px;
        }
        #visit{
            position:relative;
            height:78.5%;
            width:93%;
            margin-left:88px;
            top:0%;
            bottom: 0%;
        }
        #hbarleft2{
            position:absolute;
            margin-top:170px;
            float:left;
           width:60px;
            left:0%;
            height:5px;
            background-color:white;
            align-self: center;
        }
        *{
            box-sizing:border-box;
        }
        #genres{
            align-self: relative;
            width:70%;
             height:auto;
            padding:5px;
            margin-bottom:5px;
        }
        #hbarright2{
            position:absolute;
            margin-top:170px;
            position:relative;
            float:right;
            right:-1.4%;
            width:60px;
            height:5px;
            background-color:white;
        
        }
        #hbarleft1{
            position:absolute;
            margin-top:40px;
            float:left;
            width:60px;
            height:5px;
            background-color:#816050;
            align-self: center;
        }
        #hbarright1{
            position:relative;
            margin-top:40px;
            margin-right: 11px;
            float:right;
            width:60px;
            height:5px;
            background-color:#816050;
            align-self: center;
        }
    .text{
            
            color: #816050;
        }
        html{
            scroll-behavior: smooth;
        }
    </style>
</head>
<body>
    <div class="topnav" id="myTopnav">
        <div class="container">
  <a href="#visit">Visit Our Bookstore</a>
        <a href="#Events">Our Events</a>
          <a href="#Genres">Our Genres</a>
         <a href="#Who">Who We Are</a>
        <a href="#Home" class="active">Home</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>
        </div>
        
    <div class="container">
        <section id= "Home">
        <img  style="object-position: absolute" src="https://images.unsplash.com/photo-1481627834876-b7833e8f5570?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=841&q=80"  height="100%" width="100%">
        <div id='bottom'>
            <h1 style="text-align:center;padding-top: 40px; font-size: 70px; font-style:Bold italic; font-family: 'Playfair Display', serif;
">The Barn</h1>
                    <p id='horizontaleft'  > </p>
            <p id='horizontalright'> </p>
            <p style="text-align:center;font-family: 'Lato', sans-serif;letter-spacing: 2px; font-size:130%" >BOOKSTORE  AND PUBLISHING HOUSE</p>
            </div>
        </section>
    </div><br>
        <section id="Who">
      <div class="container scndpage-fluid"> 
          
           <img  src="https://cdn.pixabay.com/photo/2017/04/01/17/41/hangzhou-2194105_1280.jpg" height="100%" width="100%">
    <div id="righttext"> 
        <p id="topbar"> </p>
        <br>
    <br><br>
        <h1 style=" text-align:center;padding-top: 140px;padding-left: 30px;padding-right: 30px; font-size: 300%;font-family: ' Playfair Display',serif;font-style: Bold Italic;font-family: 'Playfair Display', serif;">Who We Are</h1>
        <br>
        <p style="text-align:center;font-family: 'Lato', sans-serif;font-size:100%;padding-left: 40px;padding-right: 40px" >Light house Hammock is an independent bookstore and publisher.You'll find an endless variety of wonderful books from our new ad up-and-coming authors.</p>
        <p id='bottombar'> </p>
              </div>
            </div>
          </section>
     <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    
    
    
    
    <section id="Genres">
     <div class="container-fluid"  style="background-color:#fff;color:beige;margin-left: 180px;width: 1150px;">
        
         
        <div id='top' style="background-color:#fff;color:beige">
            
        <p id="hbarleft1"> </p>
            <p id="hbarright1"> </p>
        <h1 style="text-align: center;padding-top: 20px;padding-left: 82px;color:#816050;font-size: 300%; font-family: 'Playfair Display', serif;">Our Genres</h1><br><br><br>
                   
         </div>
         <div class="container-fluid">
        <div class='row' style=margin-left:88px;>

        <div class='col-sm-4 text'>
            <img id="genres" src="https://cdn.pixabay.com/photo/2017/08/08/20/08/fantasy-2612553_1280.jpg">
            
            <P><b>SCI-FI AND FANTASY</b></P>
    
            <p>Travel through mysterious and marvelous worlds.</p></div>
        <div class='col-sm-4 text'>
             <img id="genres" src="https://cdn.pixabay.com/photo/2014/08/23/23/19/library-425730_1280.jpg">
            <p><b>GENERAL FICTION</b></p>
            <p>Feed your imagination and escape the world for a while.</p></div>
            
         <div class='col-sm-4 text'>
               <img id="genres" src="https://cdn.pixabay.com/photo/2017/06/12/10/55/book-2395134_1280.jpg">
            <p ><b>NONFICTION</b><p>
            <p>Books about our beautiful and amazing world.</p></div>
    </div>
              </div>
         </div>
    </section>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    
      <section id="Events">
     <div class="container"  style="background-color:#816050;color:beige;">
        
         
        <div id='top' style="background-color:#816050;color:beige">
            
        <p id="hbarleft2"> </p>
            <p id="hbarright2"> </p>
        <h1 style="text-align: center;padding-top: 170px;padding-left:55px;color:beige;font-size: 300%; font-family: 'Playfair Display', serif;">Our Events</h1><br><br><br>
                   
         </div>
         <div class="container">
        <div class='row'  style="font-size: 100%;letter-spacing:1px; style=text-align: center;margin:10px;margin-left: 100px;margin-right: 20px;padding-left: 20px;height: 400px;padding-right: 20px">
            
        <div class='col-sm-4'>
            <img id="genres"  class="rounded" alt="Cinque Terre" src="http://www.sugarysweetmachines.com/wp-content/uploads/2011/10/Paige_1.jpg">
            
            <P><b>AUTHOR READINGS</b></P>
            <p>An Annual National Industry Event January 1,2020,9:00a.m. to 5:00p.m. Conference Hall A,National Event Hall</p></div>
        <div class='col-sm-4'>
            <img id="genres" class="rounded" alt="Cinque Terre"  src="https://cdn.pixabay.com/photo/2018/06/17/09/58/book-3480216__340.jpg">
            
            <p><b>NEW BOOK LAUNCH</b></p>
            <p>An Annual National Industry Event January 1,2020,9:00a.m. to 5:00p.m. Conference Hall A,National Event Hall</p></div>
            
         <div class='col-sm-4'>
             <img id="genres" class="rounded"  alt="Cinque Terre" src="https://loudsloth.files.wordpress.com/2017/07/libraries.jpg?w=569&h=380">
             
            <p ><b>STORE RENOVATIONS</b><p>
            <p>An Annual National Industry Event January 1,2020,9:00a.m. to 5:00p.m. Conference Hall A,National Event Hall</p></div>
    </div>
              </div>
         </div>
    </section>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    
    
    
    
    <section id="visit">
               <div class="container scndpage" style="background-color:white;color:#816050;margin-right:162px;"> 
                   
                   <img id="visit" src="https://images.unsplash.com/photo-1481627834876-b7833e8f5570?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=841&q=80" class="visitimage" >
                <div id="lefttext"> 
        <p id="topbar1"> </p>
        <br>
    <br>
        <h1 style=" text-align:center;padding-top: 50px;padding-left:5px;padding-right: 20px;margin-right:70px; font-size: 200%;font-family: ' Playfair Display',serif;font-style: Bold Italic;font-family: 'Playfair Display', serif;">Visit Our Bookstore!</h1><br>
        
                    <p style="text-align:center;font-family: 'Lato', sans-serif;font-size:20%; padding-left: 40px;padding-right: 40px" ></p>
                    <p style="text-align: center; margin-right: 90px;"><b>MAILING ADDRESS</b><br><span>MVP Colony, Visakhapatnam, India</span></p>
                    <p style="text-align: center; margin-right: 90px;"><b>EMAIL ADDRESS</b><br><span>Thebarnstudio@Protonmail.Com</span></p>
                    <p style="text-align: center; margin-right: 90px;"><b>PHONE NUMBER</b><br><span>+91 9573990881</span></p><br>
        <p id='bottombar1'> </p>
         </div>
                   </div>
    </section>
        
    
    
    
    
    
    <div class="container">
        <div class='column' style="font-size: 100%;letter-spacing:1px; style=text-align: center;margin:10px;margin-left: 200px;margin-right: 20px;padding-left: 20px;padding-right: 20px;"></div>
       
                        
    </div>
    <script>
        function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
</script>
        
    
   
    </body>
</html>
