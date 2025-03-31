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
- Ensure semantic correctness.

Happy Coding! 💻✨


<!DOCTYPE html>
<html>
<head>
    <title>Advanced HTML5 Elements</title>
</head>
<body>

    <h2>Ordered List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
    </ol>
    <h2>External Image</h2>
    <img src="https://www.pexels.com/photos/31103901/pexels-photo-31103901/free-photo-of-city-waterfront-view-with-iconic-bridge.jpeg" alt="Sample Image from Pexels" width="400">

    <h2>Contact List</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Macharia</td>
            <td>Kiambu</td>
            <td>+2547456789</td>
            <td>johnmacharia@gmail.com</td>
        </tr>
        <tr>
            <td>Jane Wanjiru</td>
            <td>Limuru</td>
            <td>+254798954321</td>
            <td>janewanjiru@gmail.com</td>
        </tr>
        <tr>
            <td>Michael Mukuria</td>
            <td>Chuka</td>
            <td>+254674885786</td>
            <td>michaelmukuria@gmail.com</td>
        </tr>
        <tr>
            <td>Emily Gathoni</td>
            <td>Muguga</td>
            <td>+2546778899</td>
            <td>emilygathoni@gmail.com</td>
        </tr>
    </table>


    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>
        
        <label>Gender:</label>
        <input type="radio" name="gender" value="male"> Male
        <input type="radio" name="gender" value="female"> Female<br><br>
        
        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="USA">USA</option>
            <option value="UK">UK</option>
            <option value="Canada">Canada</option>
        </select><br><br>
        
        <label>Interests:</label>
        <input type="checkbox" name="interest" value="sports"> Sports
        <input type="checkbox" name="interest" value="music"> Music
        <input type="checkbox" name="interest" value="travel"> Travel<br><br>
        
        <input type="submit" value="Register">
    </form>
</body>
</html>


