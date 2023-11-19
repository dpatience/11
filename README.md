<html>
	<head>
		<title> DP11 </title>
  <h1> Sign up Form </h1>
		<body>
			<form>
	
				<tr>
    				<br>
					<td>
						Name:
					</td>
					<td>
						<input type="text" placeholder="Name">
					</td>	
				</br>
					
				</tr>
				<tr><br>
					<td>
						Email:
					</td>
					<td>
						<input type="email" Placeholder="Email">
					</td>
				</tr>
				<tr><br>
					<td>
						Password:
					</td>
					<td>
						<input type="password" placeholder="Password">
					</td>
				</tr>
				<tr><br>
					<td>
					Gender:	
					</td>
					<td>
						<input type="radio" name="gender" >Male
						<input type="radio" name="gender" >Female
					</td>
				</tr>
<tr>
	<input type="submit" value="Submit" name="Submit">
</tr>
			</form>
   
		</body>
	</head>
</html>
<form action="/login" method="post">
<label for="email">Email Address:</label>
<input type="text" id="email" name="email" required><br><br>
<label for="password">Password:</label>
<input type="password" id="password" name="password" required><br><br>
<button type="submit">Login</button>
</form>
