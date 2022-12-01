# PAYMENT-FORM
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PAYMENT FORM</title>
</head>
<body>
    <form action="">
        <h1>Payment Form</h1>
        <h2>Contact info</h2>
        <p>Required feilds are followed by *</p>
        <p>Name: * <input type="text" name="name" required></p>
        <fieldset>
            <legend>gender</legend>
            <p>Male <input type="radio" name="gender" id="male" required> <br> Female <input type="radio" name="gender" id="female" required> <br> Other <input type="radio" name="gender" id="others" required></p>
        </fieldset>
        <p>Address: *<textarea name="address" id="ddress" cols="100" rows="7" required></textarea></p> 
        <p>
            email:* <input type="email" name="email" id="email" required>
        </p>
        <p>pincode:* <input type="number" name="pincode" id="pincode" required></p>
        <br>
        <br>
        <h2>Payment Details </h2>
        <p>
            CARD TYPE: *
            <select name="card_type" id="card_type">
                <option value="" >--Select Card Type--</option>
                <option value="Visa">Visa</option>
                <option value="Rupay">Rupay</option>
                <option value="Master Card">Master_Card</option>
            </select>
        </p>
        <p>
            Card Number: *<input type="number" name="card_number" id="card_number" required>
        </p>
        <p>Expiration Date: * <input type="date" name="exp_date" id="exp_date" required>
        </p>
        <p>CVV: * <input type="password" name="cvv" id="cvv" required></p>
        <p><input type="submit" value="Pay Now"></p>
    </form>
</body>
</html>
