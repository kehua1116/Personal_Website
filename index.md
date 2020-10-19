<!DOCTYPE html>
<html>
   <head>
      <title>Lucy's website</title>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <!-- 引入 Bootstrap -->
      <link href="bootstrap/css/bootstrap.min.css" rel="stylesheet">
      <!-- jQuery (Bootstrap 的 JavaScript 插件需要引入 jQuery) -->
      <script src="https://code.jquery.com/jquery.js"></script>
      <script src="bootstrap/js/bootstrap.min.js"></script>


      <link rel="stylesheet" type="text/css" href="background.css">
      <link href="assets/css/font-awesome.css" rel="stylesheet">
      <link href="assets/css/docs.css" rel="stylesheet" >
      <link href="assets/css/bootstrap-social.css" rel="stylesheet" >
      <link href="assets/css/carousel.css" rel="stylesheet">

 

   </head>
   <body>
<!-- Navigation Bar Section----------------------------------------------------------------------->
      <div class="navbar-wrapper">
         <div class="container">
          <nav class="navbar navbar-inverse">
             <div class="container-fluid">
              <div class="navbar-header">
                <a class="navbar-brand">Lucy Wang</a>
              </div>
               <div class="collapse navbar-collapse" id="myNavbar">
                 <ul class="nav navbar-nav">
                   <li class="active"><a href="#main" id = "nav_bar">About Me</a></li>
                   <li><a href="#whatImgoodat" id = "nav_bar" >What I'm Good At</a></li>
                   <li><a href="#skills" id = "nav_bar">Skills</a></li>
                   <li><a href="#hobbies" id = "nav_bar">Hobbies</a></li>
                   <li><a href="#contact" id = "nav_bar">Contact</a></li>
                 </ul>
               </div>
             </div>
          </nav>
        </div>
      </div>



<!-- Carousel Section----------------------------------------------------------------------->
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner" role="listbox">

        <div class="item active">
          <img class="first-slide" src="images/lucy5.jpg" alt="First slide">
          <div class="container">
            <div class="carousel-caption">
              <div class="col-md-6 col-md-push-6">
              <h1>My Name is Lucy</h1>
              <p>I am an undergraduate junior studing computer science and statistics at UC Berkeley. </p>
              <p><a class="btn btn-lg btn-primary" href="#contact" role="button">Contact Me</a></p>
              </div>
            </div>
          </div>
        </div>

        <div class="item">
          <img class="second-slide" src="images/gugong.jpg" alt="Second slide">
          <div class="container">
            <div class="carousel-caption">
              <div class="col-md-6 col-md-push-6">
              <h1>I'm a Practical Problem Solver</h1>
              <p>I enjoy building meaningful things through coding and data analyzing. </p>
              <p><a class="btn btn-lg btn-primary" href="#contact" role="button">Contact Me</a></p>
              </div>
            </div>
          </div>
        </div>

        <div class="item">
          <img class="third-slide" src="images/goldengate.jpg" alt="Third slide">
          <div class="container">
            <div class="carousel-caption">
              <div class="col-md-6 col-md-push-6">
              <h1>I am Actively Recruiting</h1>
              <p>I'm currently looking for 2020 summer software development internship, please contact me below! </p>
              <p><a class="btn btn-lg btn-primary" href="#" role="button">Contact Me</a></p>
            </div>
            </div>
          </div>
        </div>
      </div>

      <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>





<!-- About Me Section-------------------------------------------------------------------------- -->
    <div class="container">
        <div id="main">
        <div class="row featurette">
          <div class="row-head"><h1 class="text-center">About Me</h1></div>
          <div class="col-md-7 col-md-push-5">
            <h2 class="featurette-heading">Hi, My name is Lucy</h2>
            <p>I'm currently an undergraduate junior at UC Berkeley studying computer science and statistics. </p>
 
            <p >I’m experienced with software development, and I always deliver high-quality products on a timely schedule. I also have experience in all phases of software development from designing user interfaces to implementing and testing. Moreover, my mathematical maturity also enables me to tackle challenges in a well-rounded way. </p>
 
            <p>I am currently looking for a position that would allow me to create new software and apps with my innovative ideas. I would like to use my experience to efficiently solve problems and create software that is competitive in the market and would benefit the organization. </p>
          </div>
          <div class="col-md-5 col-md-pull-7">
            <img src="images/lucy2.jpg" alt="image">

          </div>
      </div>

      </div>
    </div>
    <br>

<!-- What I'm Good At  Section----------------------------------------------------------------------->
    <div id="whatImgoodat">
      <div class="container" >
        <div class="row featurette">
          <div class="row-head"><h1 class="text-center">What I'm Good At</h1></div>
          <div class="col-md-12">
            <div class="panel-group" id="accordion">


              <div class="col-md-4">
                <div class="panel panel-default">
                  <div class="panel-heading">
                    <h2 class="panel-title">
                      <i class="fa fa-desktop" aria-hidden="true"></i>
                      <a data-toggle="collapse" data-parent="#accordion" 
                         href="#collapse6">
                        Backend Development
                      </a>
                    </h2>
                  </div>
                  <div id="collapse6" class="panel-collapse collapse">
                    <div class="panel-body">
                      <p>I have strong coding skills and ethics. In my software engineering internship, I developed risk analysis features for a contract review platform, which includes
                       <span style="color: #40E0D0">developing, testing, and packaging</span>. I also <span style="color: #40E0D0">developed algorithms</span> to improve the task accuracy by 15%. </p>
                      <p>Some of my projects are: <span style="color: #40E0D0">Building the backend API </span>for a routing application similar to Google Maps. Implementing a tile-based game with 1000+ lines of code in Java. Building a simple C Compiler.</p>
                    </div>
                  </div>
                </div>
              </div>



            <div class="col-md-4">
              <div class="panel panel-default">
                <div class="panel-heading">
                  <h2 class="panel-title">
                    <i class="fa fa-codepen" aria-hidden="true"></i>
                    <a data-toggle="collapse" data-parent="#accordion" 
                       href="#collapse5">
                      Web Development
                    </a>
                  </h2>
                </div>
                <div id="collapse5" class="panel-collapse collapse">
                  <div class="panel-body">
                    <p>I am experienced in <span style="color: #40E0D0">HTML, CSS, Javascript, and Bootstrap</span>, which I used to develop this website. My web development experience also includes designing interface prototype using <span style="color: #40E0D0">AxurePR</span> and implementing website using <span style="color: #40E0D0">Vue and Django</span>. </p>
                  </div>
                </div>
              </div>
            </div>



            <div class="col-md-4">
              <div class="panel panel-default">
                <div class="panel-heading">
                  <h2 class="panel-title">
                    <i class="fa fa-line-chart" aria-hidden="true"></i>
                    <a data-toggle="collapse" data-parent="#accordion" 
                       href="#collapse2">
                      Data Analytics
                    </a>
                  </h2>
                </div>
                <div id="collapse2" class="panel-collapse collapse">
                  <div class="panel-body">
                    <p>I interned at a data science educational startup named HasBrain, in which I conducted <span style="color: #40E0D0">data analysis </span> from UCI open source datasets, and produced resluts as online educational material for students. </p>
                    <p><span style="color: #40E0D0">Technologies: statistical modeling, linear regression, classificaion</span></p>
                  </div>
                </div>
              </div>
            </div>


          </div>
        </div>
      </div>

  
      <div class="row featurette">
        <div class="col-md-12">
            <div class="panel-group" id="accordion">

            <div class="col-md-4">
              <div class="panel panel-default" >
                <div class="panel-heading">
                  <h2 class="panel-title">
                    <i class="fa fa-user" aria-hidden="true"></i>
                    <a data-toggle="collapse" data-parent="#accordion" 
                       href="#collapse1">
                      Leadership
                    </a>
                  </h2>
                </div>
                <div id="collapse1" class="panel-collapse collapse">
                  <div class="panel-body">
                    <p>I was the <span style="color: #40E0D0">director of Career Development Committee</span> in Data Science Society@Berkeley, in which I lead a group of 10 people to organize career workshops and company info sessions biweekly. We also hosted the Berkeley Data Science panel, which is a full-day event and had 200+ attendees.</p>
                  </div>
                </div>
              </div>
            </div>



            <div class="col-md-4">
              <div class="panel panel-default">
                <div class="panel-heading">
                  <h2 class="panel-title">
                    <i class="fa fa-book" aria-hidden="true"></i>
                    <a data-toggle="collapse" data-parent="#accordion" 
                       href="#collapse3">
                      Research
                    </a>
                  </h2>
                </div>
                <div id="collapse3" class="panel-collapse collapse">
                  <div class="panel-body">
                    <p>I worked with UC Berkeley professor Laurel Larsen on data driven appraoches of hydrological forcasting. I applied <span style="color: #40E0D0">transfer entropy analysis</span> to assess timescales of interaction between hydroclimatic variables and streamflow uisng Jupyter Notebook, and performed <span style="color: #40E0D0">data cleaning</span> on 2GB+ time-series data from 20+ hydrological stations. </p>
                    <p><span style="color: #40E0D0">Technologies: Python, Pandas, Numpy, Scikit-learn</span></p>
                  </div>
                </div>
              </div>
            </div>


              
            <div class="col-md-4">
              <div class="panel panel-default">
                <div class="panel-heading">
                  <h2 class="panel-title">
                    <i class="fa fa-globe" aria-hidden="true"></i>
                    <a data-toggle="collapse" data-parent="#accordion" 
                       href="#collapse4">
                      Public Speaking
                    </a>
                  </h2>
                </div>
                <div id="collapse4" class="panel-collapse collapse">
                  <div class="panel-body">
                    <p>I have taken public speaking classes, and I was honored to be the <span style="color: #40E0D0">event moderator</span> at the Berkeley Data Science Panel with 200+ attendees. I have also worked as a <span style="color: #40E0D0">group tutor</span> in Student Learning Center to help students with statistics problems.</p>

                  </div>
                </div>
              </div>
            </div>

            


          </div>
        </div>
      </div>
    </div>
    <br>
  </div>



<!-- Skills Section-------------------------------------------------------------------------- -->
    <div id="skills">
      <div class="container">
        <div class="row-head"><h1 class="text-center">Skills</h1></div>
            <div class="modal-spa">
              <div class="skills"> 
                <div class="col-md-6 bar-grids bargrids-left">
                  <h4> Languages </h4>
                  <h6>Java  <span> 85% </span></h6>
                  <div class="progress">
                    <div class="progress-bar progress-bar-striped active" style="width: 85%">
                    </div>
                  </div>
                  <h6>Python <span> 85% </span></h6>
                  <div class="progress  w3-agile">
                    <div class="progress-bar progress-bar-striped active" style="width: 85%">
                    </div>
                  </div>
                  <h6>C  <span> 65% </span></h6>
                  <div class="progress">
                    <div class="progress-bar progress-bar-striped active" style="width: 65%">
                    </div>
                  </div>
                  <h6>SQL <span>80% </span></h6>
                  <div class="progress  w3-agile">
                    <div class="progress-bar progress-bar-striped active" style="width: 80%">
                    </div>
                  </div>
                  <h6>HTML, CSS, JavaScript <span> 80% </span></h6>
                  <div class="progress  w3-agile prgs-w3agile-last">
                    <div class="progress-bar progress-bar-striped active" style="width: 80%">
                    </div>
                  </div>
                </div> 
                <div class="col-md-6 bar-grids  w3-agile">
                  <h4> Technical Tools</h4>
                  <div class="col-md-4 technicaltools-grid1 grid1">
                    <span class="fa fa-cube"></span>
                    <h5>Django</h5>
                  </div>
                  <div class="col-md-4 technicaltools-grid1 grid2">
                    <span class="fa fa-cloud"></span>
                    <h5>Bootstrap</h5>
                  </div>
                  <div class="col-md-4 technicaltools-grid1 grid3">
                    <span class="fa fa-file-code-o"></span>
                    <h5>Vue</h5>
                  </div>
                  <div class="clearfix"></div>
                  
                  <div class="col-md-4 technicaltools-grid1 grid4">
                    <span class="fa fa-database"></span>
                    <h5>MySQL</h5>
                  </div>
                  <div class="col-md-4 technicaltools-grid1 grid5">
                    <span class="fa fa-git"></span>
                    <h5>Git</h5>
                  </div>
                  <div class="col-md-4 technicaltools-grid1 grid6">
                    <span class="fa fa-cog"></span>
                    <h5>AxureRP</h5>
                  </div>
                  
                  <div class="clearfix"></div>
                  
                </div>
                <div class="clearfix"> </div> 
              </div>
            </div> 
        </div> 

      </div>
    </div>
    <hr class='featurette-divider'>



<!--  Hobby Section ----------------------------------------------------------------------------->

<div id="hobbies">
  <div class="container">
    <div class="row-head"><h1 class="text-center">My Hobbies</h1></div>

      <div class="row">
        <div class="responsive">
          <div class="img-top col-md-5">
            <a target="_blank" href="images/hobby1.jpg">
              <img src="images/hobby1.jpg" alt="Statistics Tutor" >
            </a>
            <div class="desc">My Coworkers From Statistics Tutoring</div>
          </div>
        </div>
     
        <div class="responsive">
          <div class="img-top col-md-5 col-md-push-1">
            <a target="_blank" href="images/hobby2.jpeg">
              <img src="images/hobby2.jpeg" alt="Career Development Comittee" >
            </a>
            <div class="desc">Our Career Development Committee</div>
          </div>
        </div>
      </div>
    
      <div class="row">
        <div class="responsive">
          <div class="img-bot col-md-3">
            <a target="_blank" href="images/hobby5.jpg">
              <img src="images/hobby5.jpg" alt="Biking" >
            </a>
            <div class="desc">Biking around QingHai Lake, China </div>
          </div>
        </div>
     
        <div class="responsive">
          <div class="img-bot col-md-3">
            <a target="_blank" href="images/hobby4.jpg">
              <img src="images/hobby4.jpg" alt="Modrn Dance" >
            </a>
            <div class="desc">Modern Dance Performance</div>
          </div>
        </div>
        <div class="responsive">
          <div class="img-bot col-md-3">
            <a target="_blank" href="images/hobby3.jpg">
              <img src="images/hobby3.jpg" alt="Badminton" >
            </a>
            <div class="desc">Badminton Competition </div>
          </div>
        </div>
      </div>


    </div>
  </div>
  <!-- Contact Section-------------------------------------------------------------------------- -->

    <div id="contact">
      <div class="container">      
          <div class="panel panel-default">
            <div class="panel-head">
              <h1 class="text-center">Contact Me</h1>
            </div>

            <div class="panel-body">
              <div style="padding: 70px; padding-top: 0px">
                <p class="comment-w3">Please feel free to reach out to me if you have any questions, I'd love to share more about my passion and experience in computer science with you! You can also download my <a href="images/Lucy Wang Resume(swe).pdf" download="Lucy Wang Resume(swe).pdf"> resume</a> here. 
                <p><span class="fa fa-envelope"></span> <a href="mailto:wangkehua@berkeley.edu?">
                wangkehua@berkeley.edu</a></p>
                <p><span class="fa fa-phone"></span> (510)-822-1176</p>


                <ul>
                  <li class="social"><a href="https://www.facebook.com/profile.php?id=100005079105392" class="btn btn-social-icon btn-facebook"><span class="fa fa-facebook"></span></a></li>

                  <li class="social"><a href="https://github.com/kehua1116" class="btn btn-social-icon btn-github"><span class="fa fa-github"></span></a></li>

                  <li class="social"><a href="https://www.linkedin.com/in/lucy1116" class="btn btn-social-icon btn-linkedin"><span class="fa fa-linkedin"></span></a></li>
                </ul>
            </div>

            </div>
          </div>
      </div>
    </div>



      <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script>window.jQuery || document.write('<script src="assets/js/vendor/jquery.min.js"><\/script>')</script>
    <script src="bootstrap/js/bootstrap.min.js"></script>
    <!-- Just to make our placeholder images work. Don't actually copy the next line! -->
    <script src="bootstrap/js/holder.min.js"></script>
    <!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
    <script src="bootstrap/js/ie10-viewport-bug-workaround.js"></script>



   </body>
</html>
