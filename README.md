# WEDE-POE
Coverpage.hmtl
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>T&N Butcheries</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Ribbon Navigation Bar (Fixed to the top) -->
  <div class="ribbon">
    <a href="coverpage.html">Homepage</a>
    <a href="about.html">About Us</a>
    <a href="ProductsandServices.html">Products and Services</a>
    <a href="news.html">News</a>
    <a href="contact.html">Contact Us</a>
  </div>

  <!-- Cover Page Content -->
  <div class="cover-container">
    <div class="content">
      <h1>Welcome to T&N Butcheries</h1>
      <p class="slogan">Meeting Your Meaty Needs</p>
      <img src="logo.png" alt="T&N Butcheries Logo"><img sizes="10"> 
    </div>
  </div>
</body>
</html>

About.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us - T&N Butcheries</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navigation Buttons -->
    <div class="nav-buttons">
        <a href="coverpage.html"><button class="nav-btn">Homepage</button></a>
        <a href="about.html"><button class="nav-btn">About Us</button></a>
        <a href="ProductsandServices.html"><button class="nav-btn">Products and Services</button></a>
        <a href="news.html"><button class="nav-btn">News</button></a>
        <a href="contact.html"><button class="nav-btn">Contact Us</button></a>
      </div>

      <!-- Back Button to the Cover Page -->
      <a href="coverpage.html">
        <button class="back-btn">Back to Home</button>
      </a>
    </div>
  <div class="about-container">
    <div class="content">
      <h1>About Us</h1>
      <p>T&N Butcheries CC (close corporation) a BLACK OWED BUSSINES. T&N Butcheries has been running for 26 years, it started in Feburay1998. The business is in Located in Jabulani Soweto. T&N Butcheries is owned by Lephete Mkhabela and Nelisiwe Mkhabela. Two indivuals who have been married for 30 Years and Love their company very much so</p>
      <p><img src="inside.png" alt="T&N Butcheries Logo"><img sizes="8"></p>
      <p></p><img src="outside.png" alt="T&N Butcheries Logo"><img sizes="9"></p>
   </div>
</body>
</html>

css
/* Reset default styles */
* {
    margin: 10;
    padding: 20;
    box-sizing: border-box;
}

/* Apply background color to the entire document */
html {
    height: 100%;  /* Ensure the full viewport height is used */
    background-color: #5c5b5b;  /* Grey background for the entire page */
}

/* General body styles */
body {
    font-family: 'Garamond', serif;  /* Set font to Garamond */
    background-color: #5c5b5b;  /* Light grey background for the entire page */
    color: black;  /* Set text color to black */
    display: flex;
    justify-content: center;
    flex-direction: column;
    height: 100%;
    padding-top: 50px;  /* Ensure content isn't hidden under the ribbon */
}

/* Ribbon Navigation Bar */
.ribbon {
    background-color: #000000;  /* Blue background for the ribbon */
    color: rgb(86, 83, 83);
    padding: 15px 0;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 100;  /* Ensure it's above the content */
    text-align: center;
    border: 3px solid black;  /* Add a black-filled border around the ribbon */
    box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.3);  /* Optional shadow for depth */
}

.ribbon a {
    color:#5c5b5b;  /* White text for links */
    text-decoration: none;  /* Remove underline */
    font-size: 18px;
    padding: 10px 20px;
    margin: 0 15px;
    display: inline-block;  /* Ensure links appear side-by-side */
    transition: background-color 0.3s ease;
}

.ribbon a:hover {
    background-color: #0056b3;  /* Darker blue on hover */
    border-radius: 5px;
}

/* Cover Page Container */
.cover-container {
    margin-top: 80px;  /* Offset to prevent overlap with ribbon */
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100vh;  /* Full height for vertical centering */
    text-align: center;
}

.content img {
    width: 200px;  /* Set logo size */
    height: auto;
    margin-top: 20px;
}

h1 {
    font-size: 4rem;  /* Extra large font size for the welcome text */
    color:aliceblue;
    margin-bottom: 20px;
}

.slogan {
    font-size: 24px;
    font-style: italic;
    color:white;
    margin-bottom: 30px;
}

/* Button Styles for other pages if needed */
.nav-btn, .back-btn {
    padding: 10px 20px;
    font-size: 16px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin: 5px;
}

.nav-btn {
    background-color:#5c5b5b;
    color: white;
}

.nav-btn:hover {
    background-color: #5c5b5b;
}

.back-btn {
    background-color: #5c5b5b;
    color: white;
}

.back-btn:hover {
    background-color: #5c5b5b;
}

Contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - T&N Butcheries</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="contact-container">
    <div class="content">
      <h1>Contact Us</h1>
      <h2>How to Reach Us:</h2>
      <p><strong>Tel:</strong> 011 675 7893</p>
      <p><strong>Call:</strong> 072 568 3672 / 066 835 6131</p>
      <p><strong>Email:</strong> <a href="mailto:T&Nbutcheries@Gmail.com">T&Nbutcheries@Gmail.com</a></p>
      <h2>Business Hours:</h2>
      <p><strong>Mon – Sat:</strong> 8:00am – 7:00pm</p>
      <p><strong>Sun:</strong> 8:00am – 6:00pm</p>
      <p><strong>Public Holidays:</strong> 8:00am – 7:00pm (Hours may differ)</p>
      <h2>Walk-ins:</h2>
      <p>Walk-ins at the store are welcome during business hours, and we look forward to assisting you in person.</p>

      <!-- Navigation Buttons -->
      <div class="nav-buttons">
        <a href="coverpage.html"><button class="nav-btn">Homepage</button></a>
        <a href="about.html"><button class="nav-btn">About Us</button></a>
        <a href="ProductsandServices.html"><button class="nav-btn">Products and Services</button></a>
        <a href="news.html"><button class="nav-btn">News</button></a>
        <a href="contact.html"><button class="nav-btn">Contact Us</button></a>
      </div>

      <!-- Back Button to the Cover Page -->
      <a href="coverpage.html">
        <button class="back-btn">Back to Home</button>
      </a>
    </div>
  </div>
</body>
</html>

News.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>News - T&N Butcheries</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="news-container">
    <div class="content">
      <h1>News and Specials</h1>

      <!-- News and Social Media Information -->
      <p>For the latest news and specials, check out T&N Butcheries’ social media accounts:</p>
      
      <h2>Follow Us on Social Media:</h2>
      <ul>
        <li><strong>Instagram:</strong> <a href="https://www.instagram.com/T&N_Butcheries" target="_blank">@T&N_Butcheries</a></li>
        <li><strong>Facebook:</strong> <a href="https://www.facebook.com/tony.mkhabela.773" target="_blank">T&N Butcheries on Facebook</a></li>
      </ul>

      <!-- Navigation Buttons -->
      <div class="nav-buttons">
        <a href="coverpage.html"><button class="nav-btn">Homepage</button></a>
        <a href="about.html"><button class="nav-btn">About Us</button></a>
        <a href="ProductsandServices.html"><button class="nav-btn">Products and Services</button></a>
        <a href="news.html"><button class="nav-btn">News</button></a>
        <a href="contact.html"><button class="nav-btn">Contact Us</button></a>
      </div>

      <!-- Back Button to the Cover Page -->
      <a href="coverpage.html">
        <button class="back-btn">Back to Home</button>
      </a>
    </div>
  </div>
</body>
</html>
ProductsandService.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products and Services - T&N Butcheries</title>
  <link rel="stylesheet" href="styles.css"> <!-- Ensure correct path to CSS file -->
</head>
<body>
  <div class="products-container">
    <div class="content">
      <h1>Our Products and Services</h1>

      <!-- Products and Services Information -->
      <h2>We Offer the Following Products and Services:</h2>
      <ol>
        <li>Meat being sold</li>
        <li>Cutting Meat</li>
        <li>Buy & Braai</li>
        <li>Drinks sold (has a bottle store as well)</li>
        <li>Order & Delivery</li>
        <li>Order & Collection</li>
      </ol>

      <!-- Navigation Buttons -->
      <div class="nav-buttons">
        <!-- Use anchor tags for proper navigation -->
        <a href="coverpage.html">
          <button class="nav-btn">Homepage</button>
        </a>
        <a href="about.html">
          <button class="nav-btn">About Us</button>
        </a>
        <a href="ProductsandServices.html">
          <button class="nav-btn">Products and Services</button>
        </a>
        <a href="news.html">
          <button class="nav-btn">News</button>
        </a>
        <a href="contact.html">
          <button class="nav-btn">Contact Us</button>
        </a>
      </div>

      <!-- Back Button to the Cover Page -->
      <a href="coverpage.html">
        <button class="back-btn">Back to Home</button>
      </a>
    </div>
  </div>
</body>
</html>



