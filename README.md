# kalijbr.github.io
<!DOCTYPE html>
<html>
<head>
	<title>Data Entry Form</title>
</head>
<body>
	<h1>Data Entry Form</h1>
	<form>
		<label for="name">Name:</label>
		<input type="text" id="name" name="name" required><br><br>
		
		<label for="email">Email:</label>
		<input type="email" id="email" name="email" required><br><br>
		
		<label for="phone">Phone:</label>
		<input type="tel" id="phone" name="phone" required><br><br>
		
		<label for="address">Address:</label>
		<textarea id="address" name="address" rows="5" cols="30"></textarea><br><br>
		
		<label for="gender">Gender:</label>
		<input type="radio" id="male" name="gender" value="male">
		<label for="male">Male</label>
		<input type="radio" id="female" name="gender" value="female">
		<label for="female">Female</label><br><br>
		
		<label for="birthday">Birthday:</label>
		<input type="date" id="birthday" name="birthday" required><br><br>
		
		<input type="submit" value="Submit">
	</form>
</body>
</html>
