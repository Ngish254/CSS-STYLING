<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emory University LTD</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #004080;
            color: #ffffff;
            text-align: center;
            padding: 20px 0;
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        h2 {
            color: #004080;
        }
        p {
            font-size: 1.1em;
            color: #333;
        }
        form {
            background-color: #ffffff;
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        input[type="tel"] {
            width: calc(100% - 22px);
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            background-color: #004080;
            color: #ffffff;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1em;
        }
        input[type="submit"]:hover {
            background-color: #003366;
        }
        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #004080;
            color: #ffffff;
        }
        td {
            background-color: #ffffff;
        }
        img {
            display: block;
            margin: 20px auto;
            border-radius: 50%;
            border: 3px solid #004080;
        }
        a {
            color: #004080;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Welcome to the Registration Page</h1>
    </header>
    <!-- Heading and Paragraph -->
    <h2>Register Here</h2>
    <p>Please fill out the form below to register.</p>
    <!-- Registration Form -->
    <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required>
        
        <input type="submit" value="Register">   
    </form>    
    <!-- Table displaying user information -->
    <h2>User Information</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Email</th>
            <th>Phone number</th>
        </tr>
        <tr>
            <td>Anne Ngina</td>
            <td>annengina447@gmail.com</td>
            <td>0700111222</td>
        </tr>
    </table>
    <!-- Image -->
    <h2>Profile Picture</h2>
    <img src="profile.jpg" alt="User Profile Picture" width="200" height="200">
    <!-- External Link -->
    <p>Click <a href="https://www.google.com" target="_blank">here</a> to visit Google.</p>
</body>
</html>
