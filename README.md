<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport"
		content="width=device-width,
						initial-scale=1.0">
	<title>GeeksforGeeks</title>
	<link rel="stylesheet"
		href="style.css">
</head>

<body>
	<header>
		<h1 class="heading">GeeksforGeeks</h1>
		<h3 class="title">Sliding Login & Registration Form</h3>
	</header>
	<div class="container">
		<!-- upper button section to select
			the login or signup form -->
		<div class="slider"></div>
		<div class="btn">
			<button class="login">Login</button>
			<button class="signup">Signup</button>
		</div>
		<!-- Form section that contains the
			login and the signup form -->
		<div class="form-section">
			<!-- login form -->
			<div class="login-box">
				<input type="email"
					class="email ele"
					placeholder="youremail@email.com">
				<input type="password"
					class="password ele"
					placeholder="password">
				<button class="clkbtn">Login</button>
			</div>
			<!-- signup form -->
			<div class="signup-box">
				<input type="text"
					class="name ele"
					placeholder="Enter your name">
				<input type="email"
					class="email ele"
					placeholder="youremail@email.com">
				<input type="password"
					class="password ele"
					placeholder="password">
				<input type="password"
					class="password ele"
					placeholder="Confirm password">
				<button class="clkbtn">Signup</button>
			</div>
		</div>
	</div>
	<script src="index.js"></script>
</body>
</html>
