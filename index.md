<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>An Amazin style</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.1/css/all.css" integrity="sha384-gfdkjb5BdAXd+lj+gudLWI+BXq4IuLW5IT+brZEZsLFm++aCMlF1V92rMkPaX4PP" crossorigin="anonymous">
    <link rel="stylesheet" href="css/style.css" type="text/css" />
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Oswald&display=swap" rel="stylesheet">
</head>
<body>

    <nav class="navbar <!--navbar-expand-lg--> navbar-dark f-nav">
        <button class="navbar-toggler f-burger" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div>
            <a class="f-brand d-none d-md-block" href="index.html"><span style="font-size:xx-large"><i class="fas fa-camera-retro"></i> Photos</span><span style="font-size:large">.co.uk</span>
            </a>
        </div>
            <form class="form-inline my-2 my-lg-0 d-none d-md-block">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-light my-2 my-sm-0" type="submit">Search</button>
            </form>
        <div class="f-menu">
            <ul class="list-inline mt-1 mt-md-0">
                <li class="list-inline-item active"><a class="nav-link f-menu-list" href="link.html"><i class="fas fa-door-open f-icons">
                    </i><span class="d-none d-lg-inline"> Hello</span><br><span class="f-menu-sml d-none d-lg-inline">Sign-in</span></a></li>
                <li class="list-inline-item"><a class="nav-link f-menu-list" href="link.html"><i class="fas fa-wallet f-icons">
                    </i><span class="d-none d-lg-inline"> Orders</span><br><span class="f-menu-sml d-none d-lg-inline">& History</span></a></li>
                <li class="list-inline-item"><a class="nav-link f-menu-list" href="link.html"><i class="fas fa-shopping-cart f-icons">
                    </i><span class="d-none d-lg-inline"> Basket</span><br><span class="f-menu-sml d-none d-lg-inline">0 items</span></a></li>
            </ul>
        </div>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav mr-auto mt-2 mt-lg-0 ">
                <li class="nav-item ">
                    <a class="nav-link" href="link.html">
                        <span class="f-nav-item">Sign-in</span><span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="link.html" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        <span class="f-nav-item">Products</span></a>
                    <div class="dropdown-menu f-btn" aria-labelledby="navbarDropdownMenuLink">
                        <a class="dropdown-item" href="link.html">Prints</a>
                        <a class="dropdown-item" href="link.html">Canvases</a>
                        <a class="dropdown-item" href="link.html">Digital</a>
                    </div>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="link.html">
                        <span class="f-nav-item">Gallery</span></a>
                </li>
            </ul>
            <form class="form-inline my-2 my-lg-0 d-block d-xl-none">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-light my-2 my-sm-0" type="submit">Search</button>
            </form>
        </div>
    </nav>

    <div class="f-hero-container"> 
        <div class="f-intro">
            <p>Prints, Canvases, Digital,  ...
            </p>
        </div>

        <div class="row f-prints-container container-fluid">
            <div class="col-6 col-lg-3 f-prints">
                <h5 class="f-prints-image-header">Prints</h5>
                <a href="prints.html"><img class="f-prints-image" src="images/Orchids.JPG" title="orchids" /></a>
            </div>
            <div class="col-6 col-lg-3 f-prints">
                <h5 class="f-prints-image-header">Canvases</h5>
                <a href="prints.html"><img class="f-prints-image" src="images/FarmShop.jpeg" title="farm shop" /></a>
            </div>
            <div class="col-6 col-lg-3 f-prints">
                <h5 class="f-prints-image-header">Digital</h5>
                <a href="prints.html"><img class="f-prints-image" src="images/SharkFinRock.JPG" title="shark fin rock" /></a>
            </div>
            <div class="col-6 col-lg-3 f-prints">
                <h5 class="f-prints-image-header">Try</h5>
                <a href="prints.html"><img class="f-prints-image" src="images/Poppies.JPG" title="poppies" /></a>
            </div>
        </div>

    </div>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous">
    </script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous">
    </script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous">
    </script>

</body>
</html>