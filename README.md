<!-- This is the index file # # sba307htmlcss
In this assignment, I built my own three page website using html and css. -->

<!DOCTYPE html>
<html lang="en">

<head>
  <title>Former JET Digital Repository</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Bootstrap stylesheets-->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>

  <style>
    /* I found the CSS code from W3C to format the navigation bar and the body page.  I prefere simple, gray tones for the audience.*/
  </style>
  <style>
    .fakeimg {
      height: 200px;
      background: #aaa;
    }
  </style>

</head>

<body>

  <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
    <a class="navbar-brand" href="#">Home </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="collapsibleNavbar">
      <ul class="navbar-nav">
        </li>
        <li class="nav-item">
          <a class="nav-link" href="SBA_HTML_CSSwebsite/AboutMe.html">About Me</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="SBA_HTML_CSSwebsite/Professional.html">Professional</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Tickets</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Statistics</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Global Settings</a>
        </li>
      </ul>
    </div>
  </nav>


  <div class="jumbotron text-center" style="margin-bottom:0">
    <h3>Welcome to the Admin and User Page for Former JET Digital Repository</h3>
  </div>

  <!-- Bootstrap  the dropdown boxes-->

  <style>
    .bordered-column {
      border: 2px solid #000;
      padding: 15px;
    }
  </style>
  </head>

  <body>
    <div class="container">
      <div class="row">
        <div class="col-md-6 bordered-column">
          <h2>MANAGE RESOURCES</h2>
          <div class="dropdown">
            <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1"
              data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              Resources
            </button>
            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
              <a class="dropdown-item" href="#">Items</a>
              <a class="dropdown-item" href="#">Item Sets</a>
              <a class="dropdown-item" href="#">Vocabularies</a>
              <a class="dropdown-item" href="#">Resource Templates</a>
              <a class="dropdown-item" href="#">API</a>
            </div>
          </div>
        </div>
        <div class="col-md-6 bordered-column">
          <h2>USER MANAGEMENT</h2>
          <div class="dropdown">
            <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1"
              data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              USERS
            </button>
            <div class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
              <a class="dropdown-item" href="#">Users</a>
              <a class="dropdown-item" href="#">Modules</a>
              <a class="dropdown-item" href="#">Roles</a>
              <a class="dropdown-item" href="#">Settings</a>
              <a class="dropdown-item" href="#">Assets</a>
            </div>
          </div>
        </div>

        <div class="col-md-6 bordered-column">

          <div class="container">
            <div class="row">
              <div class="col-md-6 bordered-column">
                <h2>USER Console</h2>
                <div class="dropdown">
                  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1"
                    data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    User Information
                  </button>
                  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                    <a class="dropdown-item" href="#">User settings</a>
                    <a class="dropdown-item" href="#">Password</a>
                    <a class="dropdown-item" href="#">API Keys</a>
                  </div>
                </div>
              </div>

  </body>

</html>

