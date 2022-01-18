octype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-info">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Shopify</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Products</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">About us</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Contact us</a>
              </li>
              
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>

      <main class="container">

        <h3 class="text-center my-3">Redmi 11 Pro</h3>

        <div class="row">
            <div class="col-md-6 text-center">
                <img src="./images/redmi.jpg" width="400" height="400" style="object-fit: cover;" />
            </div>

            <div class="col-md-6">
              
              <h3>Redmi 11 Pro</h3>
              <p class="text-info">₹. 17,999 /-</p>
              <p>Category: Mobile</p>
              <p>The Redmi Note 11T 5G Price: ₹19,999 Experience the Next Gen Racer The Redmi Note 11T 5G often referred to as the Next Gen Racer. </p>

              <button class="btn btn-outline-success" onclick="show()">Add to cart</button>
            </div>
        </div>

        <h3 class="mt-5">Mobile Specifications:</h3>
        <table class="table table-bordered table-striped">
          <thead>
            <tr>
              <th scope="col">Title</th>
              <th scope="col">Specs</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th scope="row">Name</th>
              <td>Redmi 11</td>
            </tr>

            <tr>
              <th scope="row">Ram</th>
              <td>8 Gb</td>
            </tr>

            <tr>
              <th scope="row">Memory</th>
              <td>128 GB</td>
            </tr>
            
            <tr>
              <th scope="row">CPU</th>
              <td>Snapgragon 765</td>
            </tr>

          </tbody>
        </table>

      </main>

      <div class="position-fixed bottom-0 end-0 p-3" style="z-index: 11">
        <div id="myToastEl" class="toast hide" role="alert" aria-live="assertive" aria-atomic="true">
          <div class="toast-header">
            
            <strong class="me-auto">Product Added</strong>
            <small>Now</small>
            <button type="button" class="btn-close" data-bs-dismiss="toast" aria-label="Close"></button>
          </div>
          <div class="toast-body">
            <img src="./images/redmi.jpg" width="25" height="25" class="rounded me-2" alt="..."> Product is added to cart.
          </div>
        </div>
      </div>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <script>
      var myToastEl = document.getElementById('myToastEl')
      var myToast = bootstrap.Toast.getOrCreateInstance(myToastEl)

      function show(){
        myToast.show();

      }
    </script>
    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->
  </body>
</html>
