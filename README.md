html, body {
	width: 100%;
	height: 100%;
	background: url(header.jpg) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

h1 {
	color: #e2dbdb;
	font-size: 2rem;
}

.buffer {
	height: 210px;
}

hr {
	border-color: #F05F44;
	border-width: 2.5px;
	max-width: 65px;
}

.btn {
	font-weight: 650;
	border-radius: 700px;
	text-transform: uppercase;
}

.btn-warning {
	background-color: #F05F44;
	border-color: #F05F44;
}

.btn-warning:hover {
	background-color: #ee4b08;
	border-color: #ee4b08;
	border-width: 4px;

}

.btn-xl {
	padding: 1rem 2rem; 
}
<!DOCTYPE html>
<html>
<head>
	<title>Starter Page</title>

	 <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    	<!-- Bootstrap CSS file from CDN -->
      <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">

    <!-- Personal stylesheet -->
    <link rel="stylesheet" type="text/css" href="Landingpage.css">
</head>
<body>
	<div class="container d-flex align-items-center h-100 col-12">
		<div class="row col-12">
			<header class="text-center col-12">
				<h1 class="text-uppercase"><strong>the biggest startup event of the year</strong></h1>
			</header>
			<div class="buffer"></div>
			<section class="text-center col-12">
				<hr>
				<a href="https://mailchi.mp/db48718b1d0c/obregon"><button class="text-uppercase btn btn-warning btn-xl">find out more</button></a>
			</section>
		</div>
	</div>
</body>
</html>
