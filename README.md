







<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet"  href="http://rawgit.com/monika-w/myPortfolio/stylesheet/style.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.0/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>

<body>
<!-- navbar starts here-->
<nav class="navbar navbar-default">
    <div class="container-fluid">
        <div class="navbar-header">
            <a class="navbar-brand" href="#">Portofolio</a>
        </div>
        <ul class="nav navbar-nav">
            <li class="active"><a href="#">Home</a></li>
            <li><a href="#About">About</a></li>
            <li><a href="#Gallery">Gallery</a></li>
            <li><a href="#Contact">Contact</a></li>
        </ul>
    </div>
</nav>
<!-- navBar ends here-->


<div id="About" class="container-fluid">
    <div class="jumbotron first">

        <h1 class="text-center">Yiyuan Weng</h1>
        <div class="row">
            <div class="col-md-8">
                <h3><small>Front-End Developer and UX/UI designer</small></h3>
                <h3><small>Graphic Designer</small></h3>
                <h3><small>Java Developer</small></h3>
            </div>
            <div class="col-md-4">
                <img class="img-responsive img-circle" alt="Yiyuan Weng" src="https://scontent.fgye3-1.fna.fbcdn.net/v/t31.0-8/q83/s960x960/17359349_615480405324938_4886515232810041245_o.jpg?oh=9950432591b737f2edae5ac76d313a17&amp;oe=595FDAA3">
            </div>
        </div>
        <p>Front-End Developer and UX/UI designer, with practical experience in project management, branding strategy, and creative direction; devoted to functional programming and information architecture.</p>
    </div>
</div><!-- About information ends here -->



<div class="container-fluid">
    <div id="Gallery" class="jumbotron second">

        <h1 class="text-center">Portfolio</h1>
        <div class="row">
            <div class="col-md-4">
                 <img class="img-responsive img-circle" alt="Example 1" src="">
            </div>
            <div class="col-md-4">
                <img class="img-responsive img-circle" alt="Example 2" src="">
            </div>
            <div class="col-md-4">
                <img class="img-responsive img-circle" alt="Example 3" src="">
            </div>
        </div>
        <p>Front-End Developer and UX/UI designer, with practical experience in project management, branding strategy, and creative direction; devoted to functional programming and information architecture.</p>
    </div>
</div><!-- Gallery ends here -->



<div id="About" class="container-fluid">
    <div class="jumbotron third">

        <h1 class="text-center">Contact me</h1>
        <div class="row">
            <div class="col-md-8">
                <h3><small>Front-End Developer and UX/UI designer</small></h3>
                <h3><small>Graphic Designer</small></h3>
                <h3><small>Java Developer</small></h3>
            </div>
            <div class="col-md-4">

              <p id="Contact">Want to get in touch with me? Send me an email I'll respond to you as soon as possible! </p>
            </div>
        </div>
                    
        <p><i class="fa fa-facebook-square" id="fbicon"></i> Follow <a href="https://www.facebook.com/Mon1kaMona" target="_blank"> me </a> for web design &amp; development articles, opinions and links</p>
    </div>
</div><!-- Contact information ends here -->
</body>

</html>
