# Proyecto HTML-Forms

```HTML
<!DOCTYPE html>
<html lang="en">
	<head>
		<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" />
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<script src="https://kit.fontawesome.com/4a79e87318.js" crossorigin="anonymous"></script>
		<title>Document</title>
	</head>

	<body>
		<div class="container">
			<form class="row g-3">
				<!-- Inicio Encabezado -->
				<div class="bg-light border">
					<h1>Payment for example</h1>
				</div>
				<!-- Fin Encabezado -->

				<!-- Inicio Centro -->
				<div class="border my-0 py-3">
					<!-- Inicio Alerta -->
					<div class="alert alert-danger" role="alert">Some fields are missing.</div>
					<!-- Fin Alerta -->
					<!-- Inicio Row -->
					<div class="row py-2">
						<!-- Inicio Input Card -->
						<div class="col-5">
							<label for="inputAddress2" class="form-label">Card#</label>
							<input type="text" class="form-control" id="inputAddress2" placeholder="##############" />
						</div>
						<!-- Fin Input Card -->
						<!-- Inicio Input CVC -->
						<div class="col-3">
							<label for="inputAddress2" class="form-label">CVC#</label>
							<input type="text" class="form-control" id="inputAddress2" placeholder="000" />
						</div>
						<!-- Fin Input CVC -->
						<!-- Inicio Input Amount -->
						<div class="col-4">
							<label for="inputAddress2" class="form-label">Amount</label>
							<input type="text" class="form-control" id="inputAddress2" placeholder="Amount" />
						</div>
						<!-- Fin Input Amount -->
					</div>
					<!-- Fin Row -->
					<!-- Inicio Row -->
					<div class="row py-2">
						<!-- Inicio Input First Name -->
						<div class="col-6">
							<label for="inputAddress2" class="form-label">First Name</label>
							<input type="text" class="form-control" id="inputAddress2" />
						</div>
						<!-- Fin Input First Name -->
						<!-- Inicio Input Last Name -->
						<div class="col-6">
							<label for="inputAddress2" class="form-label">Last Name</label>
							<input type="text" class="form-control" id="inputAddress2" />
						</div>
						<!-- Fin Input Last Name -->
					</div>
					<!-- Fin Row -->
					<!-- Inicio Row -->
					<div class="row py-2">
						<!-- Inicio Input City -->
						<div class="col-4">
							<label for="inputCity" class="form-label">City</label>
							<input type="text" class="form-control" id="inputCity" />
						</div>
						<!-- Fin Input City -->
						<!-- Inicio Desplegable State -->
						<div class="col-4">
							<label for="inputState" class="form-label">State</label>
							<select id="inputState" class="form-select">
								<option selected>Choose...</option>
								<option>...</option>
							</select>
						</div>
						<!-- Fin Desplegable State -->
						<!-- Inicio Input Postal Code -->
						<div class="col-4">
							<label for="inputAddress" class="form-label">Postal Code</label>
							<input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St" />
						</div>
						<!-- Fin Input Postal Code -->
					</div>
					<!-- Fin Row -->
					<!-- Inicio Row -->
					<div class="row justify-content-between py-2">
						<div class="col-auto">
							<label for="exampleInputEmail1" class="form-label">We accept:</label>
							<!-- Inicio Radio -->
							<div class="bg-secondary rounded p-2">
								<div class="form-check form-check-inline">
									<input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio1" value="option1" />
									<label class="form-check-label text-white" for="inlineRadio1"><i class="fa-brands fa-cc-mastercard"></i></label>
								</div>
								<div class="form-check form-check-inline">
									<input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio2" value="option2" />
									<label class="form-check-label text-white" for="inlineRadio2"><i class="fa-brands fa-cc-visa"></i></label>
								</div>
								<div class="form-check form-check-inline">
									<input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option1" />
									<label class="form-check-label text-white" for="inlineRadio1"><i class="fa-brands fa-cc-diners-club"></i></label>
								</div>
								<div class="form-check form-check-inline">
									<input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio4" value="option2" />
									<label class="form-check-label text-white" for="inlineRadio2"><i class="fa-brands fa-cc-amex"></i></label>
								</div>
							</div>
						</div>
						<!-- Fin Radio -->
						<!-- Inicio Mensaje -->
						<div class="col-6">
							<label for="exampleInputEmail1" class="form-label">Message</label>
							<div class="form-floating">
								<textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea"></textarea>
								<label for="floatingTextarea"></label>
								<div id="emailHelp" class="form-text">Add any notes here.</div>
							</div>
						</div>
						<!-- Fin Mensaje -->
					</div>
					<!-- Fin Row -->
				</div>
				<!-- Fin Centro -->
				<!-- Inicio Pie -->
				<div class="border bg-light my-0 justify-content-end d-flex py-3">
					<div class="col-auto">
						<button type="submit" class="btn btn-light border">Cancel</button>
						<button type="submit" class="btn btn-primary border">Send</button>
					</div>
				</div>
				<!-- Fin Pie -->
			</form>
		</div>
		<script
			src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"
			integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p"
			crossorigin="anonymous"
		></script>
		<script
			src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js"
			integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF"
			crossorigin="anonymous"
		></script>
	</body>
</html>

```
