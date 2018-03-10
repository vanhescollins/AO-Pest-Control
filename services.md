<html>
<head>
<link href="/css/bootstrap.min.css" rel="stylesheet">
	<link href="/style.css" rel="stylesheet" type="text/css"> 
	<script src="/js/jquery.min.js"></script>
	<script src="/js/bootstrap.min.js"></script>
	<link rel="stylesheet" type="text/css" href="/css/dataTables.bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="/css/datepicker.css">
	<script src="/js/jquery.dataTables.min.js"></script>
	<script src="/js/dataTables.bootstrap.min.js">	</script>
	<script src="/js/bootstrap-checkbox.min.js"></script>
	<script src="/js/bootstrap-datepicker.js"></script>
<style>
.container {
    position: relative;
    width: 100%;
    max-width: 400px;
}

.container img {
    width: 100%;
    height: auto;
}

.container .btn {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    background-color: #555;
    color: white;
    font-size: 16px;
    padding: 12px 24px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    text-align: center;
}

.container .btn:hover {
    background-color: black;
}
</style>
</head>

<body>

<div class="container">
  <h2>Pests That I Treat</h2>
  <p>Click on the buttons below to show the details for pests that I treat</p>
  <button type="button" class="btn btn-info" data-toggle="collapse" data-target="#mice">Mice</button>
  <div id="mice" class="collapse">
	  <h5>Recommended Treatment</h5>
	  <ul>
	  <li>Details of treatment</li>
	  <li>Details of treatment</li>
	  <li>Details of treatment</li>
	  </ul>
	  <h5>Visits/Follow up Details</h5>
	  <ul>
	  <li>Visit/Follow up</li>
	  <li>Visit/Follow up</li>
	  <li>Visit/Follow up</li>
	  </ul>
  </div>
  <button type="button" class="btn btn-info" data-toggle="collapse" data-target="#Fleas">Fleas</button>
  <div id="Fleas" class="collapse">
	  <h5>Recommended Treatment</h5>
	  <ul>
	  <li>Details of treatment</li>
	  <li>Details of treatment</li>
	  <li>Details of treatment</li>
	  </ul>
	  <h5>Visits/Follow up Details</h5>
	  <ul>
	  <li>Visit/Follow up</li>
	  <li>Visit/Follow up</li>
	  <li>Visit/Follow up</li>
	  </ul>
  </div>
</div>
<div class="container">
  <img src="/images/rat1.jpg" alt="Rats" style="width:100%">
  <button type="button" class="btn btn-info" data-toggle="collapse" data-target="#rats">Rats</button>
  <div id="rats" class="collapse">
	  <h5>Recommended Treatment</h5>
	  <ul>
	  <li>Details of treatment</li>
	  <li>Details of treatment</li>
	  <li>Details of treatment</li>
	  </ul>
	  <h5>Visits/Follow up Details</h5>
	  <ul>
	  <li>Visit/Follow up</li>
	  <li>Visit/Follow up</li>
	  <li>Visit/Follow up</li>
	  </ul>
  </div>
</div>
<div class="container">
  <img src="/images/bedbug2.jpg" alt="Bedbug" style="width:100%">
  <button class="btn">Button</button>
</div>
<a href="/AO-Pest-Control/">Back to Home</a><br>
<a href="About">About</a><br>
<a href="services">Services</a><br>
<a href="ContactUs">Contact Us</a><br>

</body>
</html>
