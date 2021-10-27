<!DOCTYPE html>
<html lang="en">
<head>
  <title>Home Page</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <style>
  .fakeimg {
    
    background: #aaa;
  }
  #store
{
    overflow:hidden;
}

  </style>
</head>
<body>


<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#">clothes store</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li><a href="#">Male</a></li>
        <li><a href="#">Female</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <h2>Clothes store</h2>
      <div class="fakeimg" id="store"><img src="cloths store.jfif" alt="Not found"></div>
      <br>
      <ul class="nav nav-pills nav-stacked">
        <li class="active"><a href="#">Male</a></li>
        <li><a href="#">Female</a></li>
        
      </ul>
      <hr class="hidden-sm hidden-md hidden-lg">
    </div>
    <div class="col-sm-8">
      <h2>Male clothes</h2>
      <div class="fakeimg" id="malecloths"><img src="male cloths.jfif" alt="Not found"></div>
      <br>
      <br>
      <h2>Female clothes</h2>
      <div class="fakeimg"><img src="female cloths.jpg" alt="Not Found">
      </div>
     
    </div>
  </div>
</div>



</body>
</html>
