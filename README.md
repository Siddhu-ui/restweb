# Ex.07 Restaurant Website
## Date:16/12/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
'''
home.html
<html>
    <head>

<title> PIRATE RESTAURANT </title>
        <style>

            body {
                margin: 0;
                font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
                line-height: 1.6;
                color: rgba(226, 43, 43, 0.54);
                box-sizing: border-box;
            }

            *,*::before,*::after {
                box-sizing: inherit;
            }

            header {
                background:rgb(5, 85, 24);
                color: #333;
                padding: 15px 40px;
                display: flex;
                align-items: center;
                justify-content: space-between;
                box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            }

            header img {
                height: 60px;
        }
        
        header nav a {
            text-decoration: none;
            color: #f9f9f9;
            font-weight: bold;
            margin: 0 10px;
            transition: color 0.3s ease;
        }
        header nav a:hover {
            color: #22cbff40;
        }

        .contact-banner {
            display: flex;
            align-items: center;
            justify-content: center;
            background: url('ambiace.jpg') no-repeat center center/cover;
            color: rgb(155, 185, 226);
            height: 300px;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.8);
        }
        .contact-banner h1 {
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: 2.5rem;
            color: #f9f9f9;
        }

        .contact-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 30px 15px;
            background: #f9f9f9;
            gap: 20px;
        }

        .contact-details, .contact-form {
            flex: 1;
            max-width: 500px;
            margin: 10px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .contact-details h2, .contact-form h2 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #1f1714;
            text-align: center;
        }
        .contact-details p {
            margin: 10px 0;
            font-size: 1rem;
            color: #555;
        }

        .contact-details img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
        }
        .contact-form textarea {
            height: 100px;
        }

        .contact-form button {
            width: 100%;
            padding: 10px;
            background: #ff222200;
            color: white;
            font-size: 1.1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .contact-form button:hover {
            background: #551805;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #ff5722;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ffdd57;
        }

        @media (max-width: 768px) {
            .contact-details, .contact-form {
                max-width: 100%;
            }

            .contact-banner h1 {
                font-size: 2rem;
            }
        }

        </style>
       
    </head>
    <body>
        <header>
            <img src="leo.webp" alt="">
            <nav>
                <a href="home.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="reservation.html">Reservations</a>
                <a href="contact.html">Contact</a>
                <a href="admin.html">Administration</a>
    
            </nav>
        </header>
        <div class="banner">
            <div class="banner-content">
                <h1>Welcome to PIRATE's Life..!</h1>
                <p>Experience the finest flavors and a cozy ambiance at Olive Garden. We serve happiness on a plate!</p>
                <a href="#features">Explore Now</a>
            </div>
        </div>
    
        <section id="features" class="features">
            <div class="feature">
                <img src="food2.jpg" alt="Fresh Ingredients">
                <h3>Fresh Ingredients</h3>
                <p>We source only the freshest and most organic ingredients to create our dishes.</p>
            </div>
            <div class="feature">
                <img src="ambiace.jpg" alt="Cozy Ambiance">
                <h3>Cozy Ambiance</h3>
                <p>Enjoy your meals in a warm, welcoming, and beautifully designed space.</p>
            </div>
            <div class="feature">
                <img src="comingsoon.jpeg" alt="Easy Reservations">
                <h3>Easy Reservations</h3>
                <p>Book your table in seconds and guarantee yourself an unforgettable experience.</p>
       
           
            </div>
        </selection>
        <footer>
            <p>&copy; 2024 OLIVE GARDEN. All rights reserved. | <a href="#">Privacy Policy</a></p>
        </footer>
    </body>

    
</html>
admin.html


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pirate's life - Menu</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #054c04;
            color: #fff;
            padding: 10px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header nav a {
            text-decoration: none;
            color: #f9f9f9;
            font-weight: bold;
            margin: 0 10px;
            transition: color 0.3s ease;
        }

        header nav a:hover {
            color: #ffdd57;
        }

        header h1 {
            font-size: 1.5rem;
        }

        .menu-container {
            padding: 20px;
            background: #f9f9f9;
            text-align: center;
        }

        .menu-container h1 {
            font-size: 2rem;
            color: #054c04;
            margin-bottom: 15px;
        }

        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }

        .menu-item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
        }

        .menu-item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .menu-item:hover {
            transform: scale(1.05);
        }

        .menu-details {
            padding: 10px;
        }

        .menu-details h3 {
            font-size: 1.2rem;
            color: #054c04;
            margin-bottom: 8px;
        }

        .menu-details p {
            font-size: 0.9rem;
            color: #555;
            margin-bottom: 10px;
        }

        .menu-details .price {
            font-weight: bold;
            font-size: 1rem;
            color: #ff5722;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 10px;
        }

        footer a {
            color: #ff5722;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ffdd57;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.2rem;
            }

            .menu-items {
                flex-direction: column;
                gap: 20px;
            }

            .menu-item {
                width: 100%;
            }

            header nav a {
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>BLACK PEARL</h1>
        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="reservation.html">Reservations</a>
            <a href="contact.html">contact</a>
            <a href="admin.html">Administration</a>
        </nav>
    </header>

    <div class="menu-container">
        <h1>Our Menu</h1>
        <div class="menu-items">
            <div class="menu-item">
                <img src="menu start.webp" alt="Spaghetti">
                <div class="menu-details">
                    <h3>Special Platter</h3>
                   <p>A delightful medley of our finest offerings, this platter showcases the heart of our kitchen.</p>
                    <p class="price">₹250/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="pizza.png" alt="Pizza">
                <div class="menu-details">
                    <h3>Margherita Pizza</h3>
                    <p>Wood-fired pizza topped with fresh basil, tomatoes, and mozzarella.</p>
                    <p class="price">₹350/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="cheesymess.png" alt="Lasagna">
                <div class="menu-details">
                    <h3>Cheesy Lasagna</h3>
                    <p>Layered lasagna with a creamy blend of cheese and savory sauce.</p>
                    <p class="price">₹250/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="special.avif" alt="Salad">
                <div class="menu-details">
                    <h3>panner tikka</h3>
                    <p>an Indian dish made from chunks of paneer/ chhena marinated in spices and grilled in a tandoor.</p>
                    <p class="price">₹280/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="biryani.avif" alt="risotto">
                <div class="menu-details">
                    <h3>biryani</h3>
                    <p>Creamy risotto with fresh mushrooms and Parmesan cheese.</p>
                    <p class="price">₹250/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="tiramusu.jpg" alt="Tiramisu">
                <div class="menu-details">
                    <h3>Tiramisu</h3>
                    <p>A classic Italian dessert made with mascarpone and espresso-soaked ladyfingers.</p>
                    <p class="price">₹180/-</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 FOODIE..!. All rights reserved. | <a href="home.html">Back to Home</a></p>
    </footer>

</body>
</html>

menu.html


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pirate's life - Menu</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #054c04;
            color: #fff;
            padding: 10px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header nav a {
            text-decoration: none;
            color: #f9f9f9;
            font-weight: bold;
            margin: 0 10px;
            transition: color 0.3s ease;
        }

        header nav a:hover {
            color: #ffdd57;
        }

        header h1 {
            font-size: 1.5rem;
        }

        .menu-container {
            padding: 20px;
            background: #f9f9f9;
            text-align: center;
        }

        .menu-container h1 {
            font-size: 2rem;
            color: #054c04;
            margin-bottom: 15px;
        }

        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }

        .menu-item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
        }

        .menu-item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .menu-item:hover {
            transform: scale(1.05);
        }

        .menu-details {
            padding: 10px;
        }

        .menu-details h3 {
            font-size: 1.2rem;
            color: #054c04;
            margin-bottom: 8px;
        }

        .menu-details p {
            font-size: 0.9rem;
            color: #555;
            margin-bottom: 10px;
        }

        .menu-details .price {
            font-weight: bold;
            font-size: 1rem;
            color: #ff5722;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 10px;
        }

        footer a {
            color: #ff5722;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ffdd57;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.2rem;
            }

            .menu-items {
                flex-direction: column;
                gap: 20px;
            }

            .menu-item {
                width: 100%;
            }

            header nav a {
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>BLACK PEARL</h1>
        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="reservation.html">Reservations</a>
            <a href="contact.html">contact</a>
            <a href="admin.html">Administration</a>
        </nav>
    </header>

    <div class="menu-container">
        <h1>Our Menu</h1>
        <div class="menu-items">
            <div class="menu-item">
                <img src="menu start.webp" alt="Spaghetti">
                <div class="menu-details">
                    <h3>Special Platter</h3>
                   <p>A delightful medley of our finest offerings, this platter showcases the heart of our kitchen.</p>
                    <p class="price">₹250/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="pizza.png" alt="Pizza">
                <div class="menu-details">
                    <h3>Margherita Pizza</h3>
                    <p>Wood-fired pizza topped with fresh basil, tomatoes, and mozzarella.</p>
                    <p class="price">₹350/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="cheesymess.png" alt="Lasagna">
                <div class="menu-details">
                    <h3>Cheesy Lasagna</h3>
                    <p>Layered lasagna with a creamy blend of cheese and savory sauce.</p>
                    <p class="price">₹250/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="special.avif" alt="Salad">
                <div class="menu-details">
                    <h3>panner tikka</h3>
                    <p>an Indian dish made from chunks of paneer/ chhena marinated in spices and grilled in a tandoor.</p>
                    <p class="price">₹280/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="biryani.avif" alt="risotto">
                <div class="menu-details">
                    <h3>biryani</h3>
                    <p>Creamy risotto with fresh mushrooms and Parmesan cheese.</p>
                    <p class="price">₹250/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="tiramusu.jpg" alt="Tiramisu">
                <div class="menu-details">
                    <h3>Tiramisu</h3>
                    <p>A classic Italian dessert made with mascarpone and espresso-soaked ladyfingers.</p>
                    <p class="price">₹180/-</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 FOODIE..!. All rights reserved. | <a href="home.html">Back to Home</a></p>
    </footer>

</body>
</html>

resevation.html




<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodie..! - Reservations</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #054c04;
            color: #fff;
            padding: 10px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header img {
            height: 40px;
        }

        header nav a {
            text-decoration: none;
            color: #f9f9f9;
            font-weight: bold;
            margin: 0 10px;
            transition: color 0.3s ease;
        }

        header nav a:hover {
            color: #ff5722;
        }

        .reservation-banner {
            display: flex;
            align-items: center;
            justify-content: center;
            background: url('Green Wateroclor Leaf Linktree Background.png') no-repeat center center/cover;
            height: 300px;
            text-align: center;
            color: white;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.8);
        }

        .reservation-banner h1 {
            font-size: 3rem;
            margin: 0;
            color: #333;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }

        .reservation-form {
            display: flex;
            justify-content: center;
            padding: 20px;
            background: #f9f9f9;
        }

        .form-container {
            background: rgb(131, 226, 221);
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            width: 100%;
            max-width: 500px;
        }

        .form-container h2 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #054c04;
            text-align: center;
        }

        .form-container label {
            display: block;
            margin: 10px 0 5px;
            font-weight: bold;
        }

        .form-container input, .form-container select, .form-container textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
        }

        .form-container button {
            width: 100%;
            padding: 10px;
            background: #ff5722;
            color: white;
            font-size: 1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .form-container button:hover {
            background: #e64a19;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 10px;
        }

        footer a {
            color: #ff5722;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ffdd57;
        }

        @media (max-width: 768px) {
            header img {
                height: 30px;
            }

            .reservation-banner h1 {
                font-size: 1.5rem;
            }

            .form-container {
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="olivegarden-logo.png" alt="Olive Garden Logo">
        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="reservation.html">Reservations</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Administration</a>
        </nav>
    </header>

    <div class="reservation-banner">
        <img src="">
        <h1>Reserve Your Table Today!</h1>
    </div>

    <section class="reservation-form">
        <div class="form-container">
            <h2>Make a Reservation</h2>
            <form action="/submit-reservation" method="POST">
                <label for="name">Full Name</label>
                <input type="text" id="name" name="name" placeholder="Enter your full name" required>

                <label for="email">Email Address</label>
                <input type="email" id="email" name="email" placeholder="Enter your email address" required>

                <label for="phone">Phone Number</label>
                <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>

                <label for="date">Reservation Date</label>
                <input type="date" id="date" name="date" required>

                <label for="time">Reservation Time</label>
                <input type="time" id="time" name="time" required>

                <label for="guests">Number of DINEINS</label>
                <select id="guests" name="guests" required>
                    <option value="1">1</option>
                    <option value="2">2</option>
                    <option value="3">3</option>
                    <option value="4">4</option>
                    <option value="5">5</option>
                    <option value="6">6</option>
                    <option value="7">7</option>
                    <option value="8">8</option>
                    <option value="9">9</option>
                    <option value="10">10</option>
                </select>

                <label for="message">Special Requests</label>
                <textarea id="message" name="message" placeholder="Any special requests or dietary preferences?" rows="4"></textarea>

                <button type="submit">Reserve Now</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 OLIVE GARDEN. All rights reserved. | <a href="#">Privacy Policy</a></p>
    </footer>

</body>
</html>

contact.html

<html>
    <head>

<title> PIRATE RESTAURANT </title>
        <style>

            body {
                margin: 0;
                font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
                line-height: 1.6;
                color: blueviolet;
                box-sizing: border-box;
            }

            *,*::before,*::after {
                box-sizing: inherit;
            }

            header {
                background: aquamarine;
                color: #333;
                padding: 15px 40px;
                display: flex;
                align-items: center;
                justify-content: space-between;
                box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            }

            header img {
                height: 60px;
        }
        
        header nav a {
            text-decoration: none;
            color: #f9f9f9;
            font-weight: bold;
            margin: 0 10px;
            transition: color 0.3s ease;
        }
        header nav a:hover {
            color: #ff5722;
        }

        .contact-banner {
            display: flex;
            align-items: center;
            justify-content: center;
            background: url('ambiace.jpg') no-repeat center center/cover;
            color: rgb(155, 216, 226);
            height: 300px;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.8);
        }
        .contact-banner h1 {
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: 2.5rem;
            color: #f9f9f9;
        }

        .contact-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 30px 15px;
            background: #f9f9f9;
            gap: 20px;
        }

        .contact-details, .contact-form {
            flex: 1;
            max-width: 500px;
            margin: 10px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .contact-details h2, .contact-form h2 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #1f1714;
            text-align: center;
        }
        .contact-details p {
            margin: 10px 0;
            font-size: 1rem;
            color: #555;
        }

        .contact-details img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
        }
        .contact-form textarea {
            height: 100px;
        }

        .contact-form button {
            width: 100%;
            padding: 10px;
            background: #ff5722;
            color: white;
            font-size: 1.1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .contact-form button:hover {
            background: #e64a19;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #ff5722;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ffdd57;
        }

        @media (max-width: 768px) {
            .contact-details, .contact-form {
                max-width: 100%;
            }

            .contact-banner h1 {
                font-size: 2rem;
            }
        }

        </style>
       
    </head>
    <body>
        <header>
            <img src="" alt="">
            <nav>
                <a href="home.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="reservation.html">Reservations</a>
                <a href="contact.html">Contact</a>
                <a href="admin.html">Administration</a>
    
            </nav>
        </header>

        <div class="contact-banner">

        </div>
        <selection class="contact-section">
            <div class="contact-details">
                <h2>Hand's On</h2>
                <img src="Screenshot 2024-12-15 100556.png" alt="Contact Us"
                <p><strong> Adress:</strong> 3 2 1 Pirate's Life,chennai,kolathur,tamilnadu</p>
                <p><strong>Phone:</strong> +91 8015061628</p>
                <p><strong>Email:</strong> contact@sasi.com</p>
                <p><strong>Hours:</strong> Mon-Sun: 10 AM - 10 PM</p>
            </div>

            <div class="contact-form">
                <h2>Send Us a Message</h2>
                <form action="/submit-contact" method="POST">
                    <label for="name">Full Name</label>
                    <input type="text" id="name" name="name" placeholder="Enter your full name" required>
    
                    <label for="email">Email Address</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email address" required>
    
                    <label for="message">Message</label>
                    <textarea id="message" name="message" placeholder="Your message" required></textarea>
    
                    <button type="submit">Send Message</button>
                </form>
            </div>
        </selection>
        <footer>
            <p>&copy; 2024 OLIVE GARDEN. All rights reserved. | <a href="#">Privacy Policy</a></p>
        </footer>
    </body>

    
</html>

admin.html



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OLIVE GARDEN - Administration</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #054c04;
            color: #fff;
            padding: 10px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header nav a {
            text-decoration: none;
            color: #f9f9f9;
            font-weight: bold;
            margin: 0 10px;
            transition: color 0.3s ease;
        }

        header nav a:hover {
            color: #ffdd57;
        }

        header h1 {
            font-size: 1.5rem;
        }

        .admin-container {
            padding: 20px;
            background: #86c4cc;
            text-align: center;
        }

        .admin-container h1 {
            font-size: 2rem;
            color: #054c04;
            margin-bottom: 20px;
        }

        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .admin-item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 300px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }

        .admin-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .admin-item:hover {
            transform: scale(1.05);
        }

        .admin-details {
            padding: 15px;
        }

        .admin-details h3 {
            font-size: 1.2rem;
            color: #054c04;
            margin-bottom: 8px;
        }

        .admin-details p {
            font-size: 0.9rem;
            color: #555;
            margin-bottom: 10px;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 10px;
        }

        footer a {
            color: #ff5722;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ffdd57;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.2rem;
            }

            .admin-items {
                flex-direction: column;
                gap: 20px;
            }

            .admin-item {
                width: 100%;
            }

            header nav a {
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>PIRATRE'S DINE!</h1>
        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="reservation.html">Reservations</a>
            <a href="contact.html">Contact</a>
            <a href="admin.html">Administration</a>
        </nav>
    </header>

    <div class="admin-container">
        <h1>Our Leadership Team</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="harshatmehta.avif" alt="CEO">
                <div class="admin-details">
                    <h3>Harshat mehta</h3>
                    <p>CEO - Leading  with a vision of excellence and innovation in hospitality.</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="leo.webp" alt="Manager">
                <div class="admin-details">
                    <h3>LEO DAS</h3>
                    <p>Manager - Ensures smooth operations and a great dining experience for all guests.</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="gordonramsey.jpg" alt="Master Chef">
                <div class="admin-details">
                    <h3>GORDON RAMSEY</h3>
                    <p>Master Chef - Brings authentic Italian flavors to every dish served.</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="venkateshbatt.avif" alt="Assistant Managing Director">
                <div class="admin-details">
                    <h3>VENKATESH BHATT</h3>
                    <p>Assistant Managing Director - Supporting the team with strategy and execution excellence.</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 OLIVE GARDEN. All rights reserved. | <a href="home.html">Back to Home</a></p>
    </footer>

</body>
</html>



'''

## OUTPUT:

![alt text](<Screenshot 2024-12-15 122644.png>)
![alt text](<Screenshot 2024-12-15 122720.png>)
![alt text](<Screenshot 2024-12-15 122742.png>)
![alt text](<Screenshot 2024-12-15 122756.png>)
![alt text](<Screenshot 2024-12-15 122809.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
