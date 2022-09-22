# HTMLGeneralForm

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Registration form</title>
</head>
<body>
     <form>
     	<div>
     		<label for = "first name">First name:</label>
     		<input type="text" id="first name" name="first name" placeholder="first name " required>
     	</div>

     	<br>

     	<div>
     		<label for = "last name">Last name:</label>
     		<input type="text" id="last name" name="last name" placeholder="last name" required>
     	</div>

     	<br>

     	<div>
     		<label for = "Password">Password:</label>
     		<input type="Password" id="Password" name="Password" minlength="8" maxlength="15" required>
     	</div>
     	
     	<br>

     	<div>
     		<label for = "email">email:</label>
     		<input type="email" id="email" name="email" placeholder="email123@gmail.com" required>
     	</div>

     	<br>

     	<div>
     		<label for = "phone no">Phone no:</label>
     		<input type="phone no" id="phone no" name="phone no" placeholder="(+91) 0123456789"  required>
     	</div>

     	<br>

     	<div>
     		<label for = "Birth date">Birth date:</label>
     		<input type="date" id="Birth date" name="Birth date" required>
     	</div>

     	<br>

     	<div>
     		<label for="Gender"> Gender:</label>

     		<label for="Male">Male</label>
     		<input type="radio" id="Male"  name="Gender" value="Male">

     		<label for="Female">Female</label>
     		<input type="radio" id="Female" name="Gender" value="Female">

     		<label for="Prefer no to say">Prefer no to say</label>
     		<input type="radio" id="Prefer no to say" name="Gender" value="Prefer no to say">
     	</div>

     	<br>

     	<div>
     		<label for="agree to Terms & Condition">agree to Terms & Condition</label>
     		<input type="checkbox" id="agree to Terms & Condition" name="agree to Terms & Condition" required>
     	</div>

     	<br>

     	<div>
     		<input type="reset">
     	</div>

     	<br>

     	<div>
     		<input type="Submit">
     	</div>
     </form>
</body>
</html>
