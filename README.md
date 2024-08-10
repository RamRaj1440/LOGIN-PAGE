// LOGIN-PAGE
Create a user login page using HTML  tags and CSS rules
CareerX - User Login Page
This project is a simple user login page created using HTML and CSS. The page is designed to capture a user's login credentials (username and password) with a clean, modern interface.

Project Structure
The project contains two main files:

index.html - The HTML structure of the login page.
login.css - The CSS file for styling the login page.
Features
Responsive design: The login form is centered on the page and adjusts gracefully for different screen sizes.
User-friendly: Clear labels and placeholders guide the user to enter their credentials.
Aesthetic design: The page uses soft colors and rounded corners for a clean and modern look.
File Overview
index.html
This file contains the HTML code for the login page. The key components are
Title: The page is titled "CAREERX".
Form: The form includes fields for the username and password, with required validation.
Buttons and Links:
A submit button to log in.
A link for users to create an account if they are not registered.


//HTML CODE
<!DOCTYPE html>
<html>

<head>
    <title>CAREERX</title>
    <link rel="stylesheet" href="login.css">
</head>

<body>
    <div class="main">
        <h1>CAREERX</h1>
        <h3>Enter your login credentials</h3>
        <form action="">
            <label for="first">Username:</label>
            <input type="text" id="first" name="first" placeholder="Enter your Username" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your Password" required>

            <div class="wrap">
                <button type="submit" onclick="solve()">Submit</button>
            </div>
        </form>
        <p>Not registered? 
            <a href="#" style="text-decoration: none;">Create an account</a>
        </p>
    </div>
</body>

</html>

//CSS Code

login.css

This file contains the CSS rules that style the login page. The styling includes:

Page Layout: The form is centred on the page with a minimal and clean background.
Form Styling: The form fields and buttons are styled with padding, borders, and colors to enhance usability.
Button Styling: The submit button is prominently displayed with a background color that stands out.


//CSS CODE

/*login.css*/
body {
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: sans-serif;
    line-height: 1.5;
    min-height: 100vh;
    background: #f3f3f3;
    flex-direction: column;
    margin: 0;
}

.main {
    background-color: #fff;
    border-radius: 15px;
    box-shadow: 0 0 20px rgb(0, 0, 0, 0.2);
    padding: 10px 20px;
    transition: transform 0.2s;
    width: 500px;
    text-align: center;
}

h1 {
    color: #af784c;
}

label {
    display: block;
    width: 100%;
    margin-top: 10px;
    margin-bottom: 5px;
    text-align: left;
    color: #555;
    font-weight: bold;
}

input {
    display: block;
    width: 100%;
    margin-bottom: 15px;
    padding: 10px;
    box-sizing: border-box;
    border: 1px solid #ddd;
    border-radius: 5px;
}

button {
    padding: 15px;
    border-radius: 10px;
    margin-top: 15px;
    margin-bottom: 15px;
    border: none;
    color: white;
    cursor: pointer;
    background-color: #7a4caf;
    width: 100%;
    font-size: 16px;
}

.wrap {
    display: flex;
    justify-content: center;
    align-items: center;
}
//How to Run
Clone this repository to your local machine.
Open the index.html file in your web browser.
The login page will be displayed. You can interact with the form and explore its features.
Contribution
Contributions are welcome! Please fork this repository and submit a pull request with your enhancements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

