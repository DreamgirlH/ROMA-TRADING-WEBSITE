# ROMA-TRADING-WEBSITE
Website of Roma Trading
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>ROMA TRADING</title>
    <link rel='stylesheet' type='text/css' href='https://d33wubrfki0l68.cloudfront.net/css/0b028e4d50e048a0a447b2586bee0322bbc83b8e/css/bootstrap.min.css'/>
    <link rel='stylesheet' href='https://d33wubrfki0l68.cloudfront.net/bundles/99883b204e25d3e0cbf8dec558bc96caa65c34b2.css'/>
    

    <style>
        .navBar{
           background-color:  lightblue; 
        }

        .setSize {
            width: 100%;
            height: 650px;
        }

        #input {
            
            text-align: center;
        }
        .a{
            
            position: absolute;
            display: inline-block;
            top: 40%;
            left:30%;

        }

a:link {
    color: green; 
    background-color: transparent; 
    text-decoration: none;
}

a:visited {
    color: darkblue
    background-color: transparent;
    text-decoration: none;
}

a:hover {
    color: red;
    background-color: transparent;
    text-decoration: underline;
}

a:active {
    color: yellow;
    background-color: transparent;
    text-decoration: underline;
}
    </style>

</head>

<body>
    <!--start of main content-->
    <div id="mainDiv">
        <!--start of nav div-->
        <div class="navBar navbar-fixed-top ">
            <div id="navLeft">
                <h1 id="navBarText"> <span class="logo">R</span>OMA<span class="logo">T</span>RADING</h1>
            </div>
            <div id="navRight" class="navbar-text">

                <ul>
                    <li><a href='/'>Home</a></li>
                    <li class="dropdown"><a href="#">Prducts</a>
                     <div class="dropdown-content">
    <a href='/linked/stationery'>stationery</a><br> <br>
    <a href='/linked/nursery products'>nursery products</a><br> <br>
    
  </div></li>
                   
                    <li class="dropdown"><a href="#">Information</a>
                    <div class="dropdown-content">
    <a href='/linked/contactus'>Contact Us</a><br> <br>
    <a href='/linked/aboutus'>About</a><br> <br>
   
                    <li><a href="blog.html">Blog</a></li>
                    <li><a href="cart.html">Cart</a></li>
                </ul>

            </div>
        </div>
        <!--end of nav div-->
        <!--SLider start-->
        <div id="input">



        </div>
        <!--slider end-->
        
<!--<div class="a">
     <i class="fa fa-chevron-left" onClick="showPrevious();" aria-hidden="true"></i>
     </div>
-->


 <div style="height:100px;float:right;position: relative;bottom: 280px;" onclick="imgChange()"> <i class="fa fa-chevron-right fa-3x" aria-hidden="true"></i> </div>
      
           
         <div style="height:100px;float:left;position: relative;bottom: 280px;" onclick="forPrevious()">   <i class="fa fa-chevron-left fa-3x" aria-hidden="true"></i></div>
        <!--<input type="button" value="Click For next" onclick="imgChange()" style="float:right;position: relative;
    /* top: -122px; */
    bottom: 354px;">
        <input type="button" value="Click For previous" onclick="forPrevious()" style="float:left;position: relative;
    /* top: -122px; */
    bottom: 354px;">-->
        <!--<button value ="click here" onclick="imgChange()"> Click here</button>-->
        
        <!--body text-->
        <div class="textSection">
            <div class="text">
                <h2>Best Stationery</h2>

                <p> 
                    Each letter written on business stationery is a personal emissary from one office to another. Corporate stationery influences the impression formed in the mind of the recipient, not only about the individual sender, 
                    but also about the company he or she represents.          
                    </p>
            </div>
        </div>
        <!--body text end-->
        <br> <br> <br> <div class="forGap" style="margin-top: 124px;">
        <hr style="width: 93%;margin: 34px auto;">
        <br> <br>
        <h3>FEATURED PRODUCTS </h3> <hr> </div>
        <!--items section start-->
        <div id = "itemSec">
            
         <a href='/linked/classictan' id='classicTan'>   <div class="d1 d2" id="tan1"> <img src ="1.jpg"  height= "530px" width="100%" alt="">
                <br>
                <span class="productDetails">Pens – blue, black, red.
                    Highlighter.
                    Permanent marker (Texta / Sharpie)
                    Pencil and pencil sharpener.
                    Colored pencils.
                    Colored pens.
                    Colored markers.
                    Eraser. <br>CLASSIC MATERIAL <br>$230.00
                </span>
            </div> </a>
            
            


         <a href='/linked/oakladder' id='oakLadder'>  <div class="d1 d3">  <img src="2.jpg" alt="" height="426px" width="100%">
                <br>
                <span class="productDetails">CLASSIC MATERIAL<br>PRINTING MACHINE<br><s>$820.00</s> $750.00</span>
            </div> </a> 

          <a href='/linked/lapsmirr' id='lapsMirror'>  <div class="d1 d4">  <img src="3.jpg" height="357px" width="100%"> 
                <br>
                <span class="productDetails">CLASSIC MATERIAL<br>SPORTS<br>$1,250.00</span>
            </div>
            </a>

<!-- wnd row -->



       <a href='/linked/boxdraw' id='boxDwar'>    <div class="d1 d5" id="tan1"> <img src="4.jpg"  height= "150px" width="100%" alt="">
                <br>
                <span class="productDetails">CLASSIC MATERIAL<br>ART AND CRAFT MATERIAL<br>$1,630.00</span>
            </div>
            </a> 
            


         <a href='/linked/boxlegtable' id='boxLegTable'>  <div class="d1 d6"> 
                 <img src="6.jpg" alt="" height="306px" width="100%">
                <br>
                <span class="productDetails">CLASSIC MATERIAL<br><br>$3,080.00</span>
            </div> </a> 

          <a href='/linked/coffeetable' id='coffee'>  <div class="d1 d7"> 
                 <img src ="7.jpg" height="357px" width="100%"> 
                <br>
                <span class="productDetails">CLASSIC MATERIAL<br>TELEPHONES SETS<br>
$1,045.00</span>
            </div></a>

          <a href='/linked/classicblack' id='classicBlack'> <div class="d1 d8">  
                <img src="5.jpg" height="357px" width="100%"> 
                <br>
                <span class="productDetails">CLASSIC MATERIAL<br>DECORATION PRODUCTS<br>$170.00</span>
            </div></a> 
          <a href='/linked/stool' id='stool'>   <div class="d1 d9">  
                <img src="8.jpg" height="357px" width="100%"> 
                <br>
                <span class="productDetails">CLASSIC MATERIAL<br>SAFETY TOOLS BOX FOR KIDS<br>$355.00</span>
            </div></a>
          <a href='/linked/bed' id='bed'>  <div class="d1 d10">  
                <img src="9.jpg" height="357px" width="100%"> 
                <br>
                <span class="productDetails">CLASSIC MATERIAL<br>TOYS<br>$2,300.00</span>
            </div></a> 


             </div>
            
                <!--items section end-->
                <hr> <br> 
                <!--another nav start-->
                <div id="downNavsection">
                <div id="navDown"> 

    <ul>
                    <li><a href='/'>Home</a></li>
                     <li class="dropdown1"><a href="#">Prducts</a>
                     <div class="dropdown-content1">
    <a href='/linked/stationery'>stationery</a><br> <br>
    <a href='/linked/nursery products'>nursery products</a><br> <br>
    
  </div></li>
                   
                  <li class="dropdown1"><a href="#">Information</a>
                    <div class="dropdown-content1">
    <a href="#">Contact Us</a><br> <br>
    <a href="#">About</a><br> <br>
                    <li><a href='/linked/blog'>Blog</a></li>
                    <li><a href="cart.html">Cart</a></li>
                </ul>
                </div><!--another nav end-->
           <!--down left nav start-->     <div id="downLeft"> 
               <ul>
                   <li><a href="#"><i class="fa fa-twitter fa-1x" aria-hidden="true"></i> </a></li>
                   <li><a href="#"> <i class="fa fa-facebook-official fa-1x " aria-hidden="true"></i></a></li>
                   <li><a href="#"> <i class="fa fa-pinterest-square fa-1x" aria-hidden="true"></i></a></li>
                   <li><a href="#"> <i class="fa fa-instagram fa-1x" aria-hidden="true"></i></a></li>
                  
               </ul>
               
                 </div> <!--down left nav end-->  
                 </div>


                 <hr>
                 <br> 
                 <div id="lastSection">

                 <div class="cs"> <h3 class="aa"> JOIN OUR MAILING LIST</h3>
    <br> <p class="aa"> We promise to send only good things.   </p>
<br>

 <p class="aa">Email Address</p>
 <div id="mailSec">
    <input type="email" id="fname" name="firstname"  size="25" placeholder="Your emial..">
<input type="submit" value=">" id="submitted"> </div>
 </div>

<div class="cs" >
    <p>419 Suite Street,</p> <br>
<p>Karachi, ABCINIA LINE</p><br>
<p>PAKISTAN</p><br>
<p>03022456677</p><br> <br>
     </div>

                
                 </div><br><br><br>
<div id="footer"> 

    <p>© 2018 ROMA TRADING </p>
    <br>
    <p>ROMA TRADING theme by DEVELOPER, powered by DREAMGIRL.</p>
</div>
     
      
    </div>
            <!--end of main content-->

</body>
<script>
    images = ['1.jpg', '2.jpg', '3.jpg'];
    var totalImages = images.length;
    var next = true;
    var current = 0;
    imgChange()
    function imgChange() {
        !next ? current += 2 : false;
        if (current >= totalImages)
            current = 0;
        {

            document.getElementById('input').innerHTML = "<img src='" + images[current] + "'class='setSize'/>"
            next = true
            current++;
        }

    }
    function forPrevious() {
        next ? current -= 2 : false;
        if (current < 0) {
            current = totalImages - 1;
        }

        document.getElementById('input').innerHTML = "<img src='" + images[current] + "'class='setSize'/>";
        next = false;
        --current;


    }
    setInterval(function () {
        forPrevious();
    }, 6000)
   


    
</script>


</html>
