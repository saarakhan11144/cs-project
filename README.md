# cs-project
<!Doctype html> 
<html> 
<head> 
<title> FORM </title> 
</head> 
<body> 
<h1 align="center"><u> Register </u></h1> 
<form> 
<fieldset> 
<legend> Enter your personal details </legend> 
<lable> First Name </label> 
<input type="text" placeholder="Enter your first name" required> <br> <br> 
<lable> Last Name </label> 
<input type="text" placeholder="Enter your last name" required> <br> <br> 
<lable> Email id </label> 
<input type="email" placeholder="@gmail.com" required> <br> <br> 
<lable>D.O.B</label> 
<input type="text" placeholder="DD/MM/YYYY" required> <br><br>
    <label for="country">Country:</label>
    <select id="country" name="country">
        <option value="" disabled selected> Select Your Country </option>
        <option>United States</option>
        <option>Canada</option>
        <option>United Kingdom</option>
        <option>Australia</option>
        <option>India</option>
        <option>Germany</option>
        <option>France</option>
        <option>Japan</option>
        <option>Brazil</option>
        <option>China</option>
    </select>
<br><br>
<lable> Gender:</label> 
<input type="radio" name="gender"> Male 
<input type="radio" name="gender"> Female <br> <br> 
<lable> Password </label> 
<input type="password" required> <br> <br> 
<button>SUBMIT </button> 
</fieldset> 
</form> 
</body> 
</html>
