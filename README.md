# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- E<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Index Page</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h1>Ordered List with Roman Numerals</h1>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
        <li>Fourth Item</li>
    </ol>

    <!-- External Image -->
    <h2>External Image</h2>
    <img src="https://www.pexels.com/photo/beautiful-landscape-123456/" alt="Beautiful Landscape" width="500">

    <!-- Table of Contacts -->
    <h2>Contact Table</h2>
    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Email</th>
                <th>Mobile</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Doe</td>
                <td>123 Main St</td>
                <td>john.doe@example.com</td>
                <td>+1234567890</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm St</td>
                <td>jane.smith@example.com</td>
                <td>+0987654321</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>789 Oak St</td>
                <td>michael.brown@example.com</td>
                <td>+1122334455</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>321 Pine St</td>
                <td>emily.davis@example.com</td>
                <td>+2233445566</td>
            </tr>
            <tr>
                <td>Chris Wilson</td>
                <td>654 Maple St</td>
                <td>chris.wilson@example.com</td>
                <td>+3344556677</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" required><br><br>

        <label for="mobile">Mobile:</label><br>
        <input type="tel" id="mobile" name="mobile" required><br><br>

        <label for="address">Address:</label><br>
        <textarea id="address" name="address" rows="4" cols="30" required></textarea><br><br>

        <button type="submit">Register</button>
    </form>
</body>
</html>nsure semantic correctness.

Happy Coding! 💻✨
