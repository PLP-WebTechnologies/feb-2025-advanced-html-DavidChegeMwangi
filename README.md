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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Page</title>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My Web Page</h1>
    </header>
    
    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <!-- Main Content -->
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>This is a simple HTML page for learning purposes.</p>
        </section>
        
        <section id="about">
            <h2>About</h2>
            <p>This page was created by a junior developer learning HTML.</p>
        </section>
        
        <!-- Ordered List with Roman Numerals -->
        <section>
            <h2>Ordered List</h2>
            <ol type="I">
                <li>First Item</li>
                <li>Second Item</li>
                <li>Third Item</li>
            </ol>
        </section>
        
        <!-- External Image from Pexels -->
        <section>
            <h2>Image</h2>
            <img src="https://images.pexels.com/photos/1234567/example.jpg" alt="Example from Pexels" width="500">
        </section>
        
        <!-- Table of Contacts -->
        <section>
            <h2>Contact List</h2>
            <table border="1">
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
                <tr>
                    <td>John Doe</td>
                    <td>123 Main St</td>
                    <td>+123456789</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Elm St</td>
                    <td>+987654321</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>Michael Brown</td>
                    <td>789 Oak St</td>
                    <td>+112233445</td>
                    <td>michael@example.com</td>
                </tr>
                <tr>
                    <td>Sarah Johnson</td>
                    <td>321 Pine St</td>
                    <td>+556677889</td>
                    <td>sarah@example.com</td>
                </tr>
                <tr>
                    <td>David White</td>
                    <td>654 Cedar St</td>
                    <td>+998877665</td>
                    <td>david@example.com</td>
                </tr>
            </table>
        </section>
        
        <!-- Registration Form -->
        <section>
            <h2>Registration Form</h2>
            <form action="#" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required><br>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required><br>
                
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Enter your password" required><br>
                
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required><br>
                
                <label for="gender">Gender:</label>
                <input type="radio" id="male" name="gender" value="male"> Male
                <input type="radio" id="female" name="gender" value="female"> Female
                <input type="radio" id="other" name="gender" value="other"> Other<br>
                
                <label for="country">Country:</label>
                <select id="country" name="country">
                    <option value="kenya">Kenya</option>
                    <option value="usa">USA</option>
                    <option value="uk">UK</option>
                </select><br>
                
                <label>Interests:</label>
                <input type="checkbox" name="interests" value="coding"> Coding
                <input type="checkbox" name="interests" value="sports"> Sports
                <input type="checkbox" name="interests" value="music"> Music<br>
                
                <button type="submit">Register</button>
            </form>
        </section>
    </main>
    
    <!-- Footer -->
    <footer>
        <p>Contact us at: example@email.com</p>
    </footer>
</body>
</html>

