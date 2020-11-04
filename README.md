# Signup-page
     <!DOCTYPE html>
     <html lang="en" dir="ltr">
     <head>
     <meta charset="utf-8">
    <title>Sign up Page</title>
     </head>
     <body>

    <h1>Course Sign Up Page</h1>
    <form action="thankyou.html" method="get">
      <p>Please Note: First Name, Last Name, Password, and Email are required</p>
      <label for="First Name">First Name:</label>
      <input id="First Name" type="text" name="" placeholder="First Name" required>

      <label for="Last Name">Last Name:</label>
      <input id = "Last Name" type="text" name="" placeholder="Last Name"required>
      <p></p>

      <label for="Email">Email:</label>
      <input id="Email" type="Email" name="" placeholder="name@email.com">

      <label for="Password">Password:</label>
      <input type="password" id="pass" >

      <p>Are you over the age of 18?</p>
      <label for="Yes">Yes:</label>
      <input type="radio" name="Over18" id="yes" value="yesOver">

      <label for="No">No:</label>
      <input type="radio" name="Over18" id="No" value="noOver">

      <p>Do you have a Credit Card or PayPal?</p>
      <select name="Payment">
        <option value="cc">Credit Card</option>
        <option value="pp">Paypal</option>
      </select>

      <p></p>

      <input type="submit" name="" value="Sign Up">

  </form>


  </body>
</html>
