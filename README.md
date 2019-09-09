<!DOCTYPE html>


<html>
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Vijay News</title>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="style.css" rel="stylesheet">
    <link href="draft_css.css" rel="stylesheet">
    <style>
    
html {
    overflow-y: scroll;
}
/* Forces a scrollbar when the viewport is larger than the websites content - CSS3 */

@media only screen and (max-width: 600px) {
      }
  
  /* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
     }
  
  /* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
      } 
  
  /* Large devices (laptops/desktops, 992px and up) */
 @media only screen and (min-width: 992px) {
     } 
  
  /* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
      }


body {
    margin: 0;
    padding: 0;
    font-size: 13px;
    font-family: Georgia, "Times New Roman", Times, serif;
    color: black;
    background-color:  ghostwhite;
}

.header {
    padding: 30px;
    font-size: 40px;
    text-align: center;
    background: white;
}

.topr1{
    overflow: hidden;
    background-color: rgb(150, 64, 2);
    color: yellow;
    position: fixed;
    top: 0;
    width: 100%;
    margin: 0 auto;
    
}

.topr2{
    padding: 20px;
    font-size: 40px;
    text-align: center;
    background: white;
}


#navbar {
    overflow: hidden;    
    background-color: antiquewhite;
}

#navbar a {
        float: left;
        display: block;
        color:  darkblue;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
        font-size: 17px;
    }

#navbar a:hover {
            background-color: blue;
            color:  floralwhite;
        }

#navbar a.active {
           background-color: rgb(150, 64, 2);
            color:yellow;
        }










.main {
    padding: 16px;
    width: 1200px;
    margin: auto;
   
   
}

.round1 {
    padding: 10px;
    border: 2px solid red;
    border-radius: 6px;
}




.clear:after {
    content: ".";
    display: block;
    height: 0;
    clear: both;
    visibility: hidden;
    line-height: 0;
}

.clear {
    display: block;
    clear: both;
}

html[xmlns] .clear {
    display: block;
}

* html .clear {
    height: 1%;
}

a {
    outline: none;
    text-decoration: none;
}

code {
    font-weight: normal;
    font-style: normal;
    font-family: Georgia, "Times New Roman", Times, serif;
}

.fl_left {
    float: left;
}

.fl_right {
    float: right;
}

img {
    margin: 0;
    padding: 0;
    border: none;
    line-height: normal;
    vertical-align: middle;
}

.imgholder, .imgl, .imgr {
    padding: 4px;
    border: 1px solid #D6D6D6;
    text-align: center;
}

.imgl {
    float: left;
    margin: 0 15px 15px 0;
    clear: left;
}

.imgr {
    float: right;
    margin: 0 0 15px 15px;
    clear: right;
}

/*----------------------------------------------HTML 5 Overrides-------------------------------------*/

address, article, aside, figcaption, figure, footer, header, nav, section {
    display: block;
    margin: 0;
    padding: 0;
}

q {
    display: block;
    padding: 0 10px 8px 10px;
    color: #979797;
    background-color: #ECECEC;
    font-style: italic;
    line-height: normal;
}

    q:before {
        content: '“ ';
        font-size: 26px;
    }

    q:after {
        content: ' „';
        font-size: 26px;
        line-height: 0;
    }

/* ----------------------------------------------Wrapper-------------------------------------*/

div.wrapper {
    display: block;
    width: 100%;
    margin: 0;
    padding: 0;
    text-align: left;
}

.row1, .row1 a {
    color: #C0BAB6;
    background-color: #333333;
}

.row2 {
    color: #979797;
    background-color: #FFFFFF;
}

    .row2 a {
        color: #FF9900;
        background-color: #FFFFFF;
    }

.row3, .row3 a {
    color: #919191;
    background-color: #232323;
}

/*----------------------------------------------Generalise-------------------------------------*/

#header, #container, #footer {
    display: block;
    width: 960px;
    margin: 0 auto;
}

nav ul {
    margin: 0;
    padding: 0;
    list-style: none;
}

h1, h2, h3, h4, h5, h6 {
    margin: 0;
    padding: 0;
    font-size: 22px;
    font-weight: normal;
    font-style: italic;
    line-height: normal;
}

address {
    font-style: normal;
}

blockquote, q {
    display: block;
    padding: 8px 10px;
    color: #979797;
    background-color: #ECECEC;
    font-style: italic;
    line-height: normal;
}

    blockquote:before, q:before {
        content: '“ ';
        font-size: 26px;
    }

    blockquote:after, q:after {
        content: ' „';
        font-size: 26px;
        line-height: 0;
    }

form, fieldset, legend {
    margin: 0;
    padding: 0;
    border: none;
}

legend {
    display: none;
}

input, textarea, select {
    font-size: 12px;
    font-family: Georgia,"Times New Roman",Times,serif;
}

.one_quarter, .two_quarter, .three_quarter, .four_quarter {
    display: block;
    float: left;
    margin: 0 20px 0 0;
}

.one_quarter {
    max-width: 225px;
}

.two_quarter {
    max-width: 470px;
}

.three_quarter {
    max-width: 715px;
}

.four_quarter {
    max-width: 960px;
    float: none;
    margin-right: 0;
    clear: both;
}

.one_third, .two_third, .three_third {
    display: block;
    float: left;
    margin: 0 30px 0 0;
}

.one_third {
    max-width: 300px;
}

.two_third {
    max-width: 630px;
}

.three_third {
    max-width: 960px;
    float: none;
    margin-right: 0;
    clear: both;
}

.lastbox {
    margin-right: 0;
}


#myImg {
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s;
}

#myImg:hover {
        opacity: 0.7;
    }



.sticky {
    position: fixed;
    top: 35px;
    width: 100%;
}

    .sticky + .content {
        padding-top: 60px;
    }

#navbar {
    overflow: hidden;
    
    background-color: antiquewhite;
}

#navbar a {
        float: left;
        display: block;
        color:  darkblue;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
        font-size: 17px;
    }

#navbar a:hover {
            background-color: blue;
            color:  floralwhite;
        }

#navbar a.active {
           background-color: rgb(150, 64, 2);
            color:yellow;
        }




/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {
    float: left;
    width: 50%;
}

/* Right column */


.meddilecolumn {
    float: left;
    width: 25%;}



.rightcolumn {
    float: left;
    width: 23%;
    padding-left: 5px;
}

/* Fake image */
.fakeimg {
    background-color: #aaa;
    width: 100%;
    padding: 5px;
}

.adfakeimg {
    background-color: #aaa;
    width: 100%;
    padding: 5px;
}

/* Add a card effect for articles */
.card {
    background-color: white;
    padding: 20px;
    margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}

/* Footer */
.footer {
    padding: 20px;
    text-align: center;
    background: #ddd;
    margin-top: 20px;
}



.icon-bar {
    position: fixed;
    top: 30%;
    float: right;
    -webkit-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    transform: translateY(-50%);
  }
  
  .icon-bar a {
    display: block;
    text-align: center;
    padding: 16px;
    transition: all 0.3s ease;
    color: white;
    font-size: 20px;
  }
  
  .icon-bar a:hover {
    background-color: #000;
  }
  
  .facebook {
    background: #3B5998;
    color: white;
  }
  
  .twitter {
    background: #55ACEE;
    color: white;
  }
  
  .google {
    background: #dd4b39;
    color: white;
  }
  
  .linkedin {
    background: #007bb5;
    color: white;
  }
  
  .youtube {
    background: #bb0000;
    color: white;
  }
  
  .content {
    margin-left: 75px;
    font-size: 30px;
  }


  .cards {
    display: flex;
    flex-wrap: wrap;
    align-items: stretch;
  }
  .card {
    flex: 0 0 200px;
    margin: 10px;
    border: 1px solid #ccc;
    box-shadow: 2px 2px 6px 0px  rgba(0,0,0,0.3);
  } 
  .card img {
    max-width: 100%;
  }
  .card .text {
    padding: 0 20px 20px;
  }
  .card .text > button {
    background: gray;
    border: 0;
    color: white;
    padding: 10px;
    width: 100%;
    }


.cardcolumn {
        float: left;
        width: 30%;
        padding: 0 10px;
      }
      
      /* Remove extra left and right margins, due to padding */
.cardrow {margin: 0 -5px;}
      
      /* Clear floats after the columns */
      .cardrow:after {
        content: "";
        display: table;
        clear: both;
      }

      .smalcard{
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
        padding: 16px;
        text-align: center;
        background-color:lemonchiffon;
      }

/* Media image */
      .mobj {

        flex: 0 0 200px;
        margin: 10px;
        border: 1px solid #ccc;
        box-shadow: 2px 2px 6px 0px  rgba(0,0,0,0.3);
        overflow: hidden;
        background:cornsilk;
        padding: 1rem;
        max-width: 20rem;
        
      }
      .mobj img {
        width: 75px;
        height: 75px;
        float: left;
        margin: 0 1rem 0 0;
      }
      .mobj h2 {
        font-weight: 500;
        margin: 0 0 0.5rem 0;
      }
    </style>
</head>
<body>



    <div class="wrapper row1">
        
        <div class="topr1">
                <div id = "header">
                <div class="two_quarter">
                        <h2 aria-flowto="center">Draft News</h2>
                    </div>
            <div class="three_quarter">
            <p>
                <marquee width="100%" direction="left" height="25">
                    This is a sample scrolling text that has scrolls in the upper direction.
                </marquee>
            </p>
        </div>
        

        </div> 
    </div>    
    </div>

    <div class="topr2">
            <h2>Draft News</h2>
            
            
        </div> 
    

    <div id="navbar">
        <a class="active" href="javascript:void(0)">Home</a>
        <a href="javascript:void(0)">Science</a>
        <a href="javascript:void(0)">Technology</a>
        <a href="javascript:void(0)">Social Media</a>
        <a href="javascript:void(0)">Menu1</a>
        <a href="javascript:void(0)">Menu2</a>
        <a href="javascript:void(0)">Menu3</a>
        <a href="javascript:void(0)">Menu4</a>
        <a href="javascript:void(0)">Menu5</a>
        <a href="javascript:void(0)">Menu6</a>
        <a href="javascript:void(0)">Menu7</a>
    </div>


    <div class="icon-bar">
        <a href="#" class="facebook"><i class="fa fa-facebook"></i></a> 
        <a href="#" class="twitter"><i class="fa fa-twitter"></i></a> 
        <a href="#" class="google"><i class="fa fa-google"></i></a> 
        <a href="#" class="linkedin"><i class="fa fa-linkedin"></i></a>
        <a href="#" class="youtube"><i class="fa fa-youtube"></i></a> 
      </div>

    <!--   <div class="content">
            <div class="tab">
                <button class="tablinks active" onclick="openCategory(event, 'cat01')">Science</button>
                <button class="tablinks" onclick="openCategory(event, 'cat02')">Technology</button>
                <button class="tablinks" onclick="openCategory(event, 'cat03')">Social Media</button>
                <button class="tablinks" onclick="openCategory(event, 'cat04')">Car News</button>
                <button class="tablinks" onclick="openCategory(event, 'cat05')">Worldwide</button>
            </div>
        </div>
    -->
    <div class="main">

        <div class="header">
            <h2 class="round1">Advertisment</h2>
        </div>

        <div class="row">
                <div class="meddilecolumn">
                    <div class="mobj">
                            <img src="" alt="">
                            <h2>Sandy Sandwiches</h2>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                          
                    </div>
                    <div class="mobj">
                            <img src="" alt="">
                            <h2>Sandy Sandwiches</h2>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                          
                    </div>
                    <div class="mobj">
                            <img src="" alt="">
                            <h2>Sandy Sandwiches</h2>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                          
                    </div>
                    <div class="card">
                            <h2>Trend News</h2>
                            <div class="fakeimg" style="height:100px;">Image</div>
                            <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
                        </div>
                    <div class="mobj">
                            <img src="" alt="">
                            <h2>Sandy Sandwiches</h2>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                          
                    </div>
                    <div class="mobj">
                            <img src="" alt="">
                            <h2>Sandy Sandwiches</h2>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                          
                    </div>
                    <div class="mobj">
                            <img src="" alt="">
                            <h2>Sandy Sandwiches</h2>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                          
                    </div>
                    <div class="card">
                            <h2>Trend News</h2>
                            <div class="fakeimg" style="height:100px;">Image</div>
                            <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
                        </div>

                        <div class="card">
                                <h2>Trend News</h2>
                                <div class="fakeimg" style="height:100px;">Image</div>
                                <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
                            </div>
                            <div class="mobj">
                                    <img src="" alt="">
                                    <h2>Sandy Sandwiches</h2>
                                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                                  
                            </div>


                </div>
        




        
            <div class="leftcolumn">
                <div class="card">
                    <h2>TITLE HEADING</h2>                    
                    <div class="fakeimg" style="height:200px;">Image</div>
                    <p>Some text..</p>
                    <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
                    <h5>Title description, Dec 7, 2017</h5>
                </div>
                <div class="cardrow">
                    <div class="cardcolumn">
                     <div class="smalcard">
                    <h3>Advertisment</h3>
                    <p>Some text..</p>
                     </div>
                  </div>
            <div class="cardcolumn">
                <div class="smalcard">
                    <h3>Advertisment</h3>
                    <p>Some text..</p>
                </div>
            </div>
                <div class="cardcolumn">
                <div class="smalcard">
                    <h3>Advertisment</h3>
                    <p>Some text..</p>
                </div>
                </div>
                
            </div>

                <div class="card">
                    <h2>TITLE HEADING</h2>                    
                    <div class="fakeimg" style="height:200px;">Image</div>
                    <p>Some text..</p>
                    <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
                    <h5>Title description, Sep 2, 2017</h5>
                </div>

                <div class="cardrow">
                        <div class="cardcolumn">
                         <div class="smalcard">
                        <h3>Advertisment</h3>
                        <p>Some text..</p>
                         </div>
                      </div>
                <div class="cardcolumn">
                    <div class="smalcard">
                        <h3>Advertisment</h3>
                        <p>Some text..</p>
                    </div>
                </div>
                    <div class="cardcolumn">
                    <div class="smalcard">
                        <h3>Advertisment</h3>
                        <p>Some text..</p>
                    </div>
                    </div>
                    

                    
                    
                </div>



                <div class="card">
                    <h2>Advertisment</h2>                    
                    <div class="fakeimg" style="height:200px;">Image</div>
                    
                </div>

                <div class="card">
                        <h2>TITLE HEADING</h2>                    
                        <div class="fakeimg" style="height:200px;">Image</div>
                        <p>Some text..</p>
                        <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
                        <h5>Title description, Sep 2, 2017</h5>
                    </div>

            </div>
            <div class="rightcolumn">
                <div class="card">
                    <h2>Trend News</h2>
                    <div class="fakeimg" style="height:100px;">Image</div>
                    <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
                </div>
                <div class="card">
                    <h3>Popular Post</h3>
                    <div class="fakeimg">Image</div><br>
                    <div class="fakeimg">Image</div><br>
                    <div class="fakeimg">Image</div>
                </div>
                <div class="card">
                    <h3>Advertisment</h3>
                    <p>Some text..</p>
                </div>
                <div class="mobj">
                        <img src="" alt="">
                        <h2>Sandy Sandwiches</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                      
                </div>
                <div class="card">
                        <h2>Trend News</h2>
                        <div class="fakeimg" style="height:100px;">Image</div>
                        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
                    </div>
                    <div class="card">
                            <h2>Trend News</h2>
                            <div class="fakeimg" style="height:100px;">Image</div>
                            <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
                        </div>
                        <div class="mobj">
                                <img src="" alt="">
                                <h2>Sandy Sandwiches</h2>
                                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                              
                        </div>
                        <div class="card">
                                <h2>Trend News</h2>
                                <div class="fakeimg" style="height:100px;">Image</div>
                                <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
                            </div>
                            <div class="mobj">
                                    <img src="" alt="">
                                    <h2>Sandy Sandwiches</h2>
                                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                                  
                            </div>
                            <div class="mobj">
                                    <img src="" alt="">
                                    <h2>Sandy Sandwiches</h2>
                                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                                  
                            </div>
            </div>
        </div>
    </div>
    <div class="footer">
        <h2>Footer</h2>
    </div>







    <script>
        window.onscroll = function () { myFunction() };

        var navbar = document.getElementById("navbar");
        var sticky = navbar.offsetTop;

        function myFunction() {
            if (window.pageYOffset >= sticky) {
                navbar.classList.add("sticky")
            } else {
                navbar.classList.remove("sticky");
            }
        }
    </script>

</body>
</html>
