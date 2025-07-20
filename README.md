<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Billing Address Form</title>
</head>
<body>

  <h1>Billing Address</h1>

  <form action="#" method="post">

    <!-- Text -->
    <label for="fullname">Full Name:</label><br>
    <input type="text" id="fullname" name="fullname" required><br><br>

    <!-- Email -->
    <label for="email">Email Address:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <!-- Password -->
    <label for="password">Account Password:</label><br>
    <input type="password" id="password" name="password" required><br><br>

    <!-- Number -->
    <label for="streetnumber">Street Number:</label><br>
    <input type="number" id="streetnumber" name="streetnumber"><br><br>

    <!-- Radio -->
    <p>Billing Type:</p>
    <input type="radio" id="personal" name="billingtype" value="personal" checked>
    <label for="personal">Personal</label><br>
    <input type="radio" id="business" name="billingtype" value="business">
    <label for="business">Business</label><br><br>

    <!-- Checkbox -->
    <input type="checkbox" id="sameasshipping" name="sameasshipping">
    <label for="sameasshipping">Same as Shipping Address</label><br><br>

    <!-- Date -->
    <label for="duedate">Payment Due Date:</label><br>
    <input type="date" id="duedate" name="duedate"><br><br>

    <!-- Range -->
    <label for="paymentrange">Payment Amount Range:</label><br>
    <input type="range" id="paymentrange" name="paymentrange" min="0" max="1000"><br><br>

    <!-- File -->
    <label for="uploadid">Upload ID Proof:</label><br>
    <input type="file" id="uploadid" name="uploadid"><br><br>

    <input type="submit" value="Submit">

  </form>

</body>
</html>
