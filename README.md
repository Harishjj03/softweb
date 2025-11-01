# Ex.07 Restuarant Website
## Date:01/11/2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
```
Restaurant.html:
<html>
    
<head>
<link rel="stylesheet" href="style.css">

</head>
<body>

<div class="header">

<h1>The Hungry Hub</h1>
</div>
<div class="bar">
 <a href="Restaurant.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration </a>
        <a href="Contact us.html">Contact</a>
</div>





</body>




</html>

```

```
Menu.html:
 <!DOCTYPE html>
<html lang="en">
<head>
  
  <title>Menu - The Hungry Hub</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body class="menu-page">
  <nav>
    <ul>
      <li><a href="Restaurant.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="Administration.html">Administration</a></li>
      <li><a href="Contact us.html">Contact</a></li>
    </ul>
  </nav>
  <h1 class="page-title">Our Indian Specials</h1>
  <div class="menu-grid">
    <div class="menu-item"><img src="cb1.png" alt="Biryani"><p>Hyderabadi Dum Biryani</p></div>
    <div class="menu-item"><img src="bc.png" alt="Butter Chicken"><p>Butter Chicken</p></div>
        <div class="menu-item"><img src="cc.png" alt="Chettinad Chicken"><p>Chettinad Chicken</p></div>
    <div class="menu-item"><img src="fc.png" alt="Fish Curry"><p>Fish Curry</p></div>
    <div class="menu-item"><img src="c65.png" alt="Chicken 65"><p>Chicken 65</p></div>
    <div class="menu-item"><img src="tc.png" alt="Tandoori Chicken"><p>Tandoori Chicken</p></div>

    <div class="menu-item"><img src="pp.png" alt="Palak Paneer"><p>Palak Paneer</p></div>
    <div class="menu-item"><img src="ch.png" alt="Carrot Halwa"><p>Carrot Halwa</p></div>
    <div class="menu-item"><img src="bh.png" alt="Bread Halwa"><p>Bread Halwa</p></div>
    <div class="menu-item"><img src="rm.png" alt="Rasmalai"><p>Rasmalai</p></div>
    <div class="menu-item"><img src="gj.png" alt="Gulab Jamun"><p>Gulab Jamun</p></div>
    <div class="menu-item"><img src="rp.png" alt="Chaat"><p>Chennai Street Chaat</p></div>
  </div>
</body>
</html>

```

```
Administration.html:
<!DOCTYPE html>
<html lang="en">
<head>
  
  <title>Our Team</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body class="admin-page">
  <nav>
    <ul>
       <li><a href="Restaurant.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="Administration.html">Administration</a></li>
      <li><a href="Contact us.html">Contact</a></li>
    </ul>
  </nav>
  <section class="team-section">
  <h2 style="text-align: center; color: white ;">Meet Our Team</h2>
  <div class="team-grid">
    <div class="team-member">
      <img src="1.png" alt="HARISH">
      <h3>HARISH - Restaurant Manager</h3>
    </div>
    <div class="team-member">
      <img src="2.png" alt="VINOLIA">
      <h3>VINOLIA - Head Chef</h3>
    </div>
    
    <div class="team-member">
      <img src="3.jpeg" alt="NAVEEN">
      <h3>NAVEEN - Sous Chef</h3>
    </div>
    <div class="team-member">
      <img src="4.png" alt="PRADEEP">
      <h3>PRADEEP - Lead Server</h3>
    </div>
    <div class="team-member">
        <img src="ajay.jpg" alt="AJAY">
        <h3> AJAY - Chai Expert</h3>
      </div>
      <div class="team-member">
        <img src="Recep.jpg" alt="DEVA">
        <h3>DEVA - Receptionist</h3>
      </div>

    </div>
  </div>
</section>

</body>
</html>

```
```
Contact us.html:
<!DOCTYPE html>
<html lang="en">
<head>
 
  <title>Contact Us</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body class="contact-page">
  <nav>
    <ul>
      <li><a href="Restaurant.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="Administration.html">Administration</a></li>
      <li><a href="Contact us.html">Contact</a></li>
    </ul>
  </nav>

  <div class="contact-container">
    <div class="contact-info">
      <h1>Get in Touch</h1>
      <p><i class="fas fa-map-marker-alt"></i> 123 Flavor Street, Food City, FC 45678</p>
      <p><i class="fas fa-phone-alt"></i> +1 (234) 567-8901</p>
      <p><i class="fas fa-envelope"></i> info@restaurant.com</p>
    </div>

    <div class="contact-form">
      <h2>Send Us a Message</h2>
      <form>
        <input type="text" placeholder="Your Name" required />
        <input type="email" placeholder="Your Email" required />
        <textarea rows="5" placeholder="Your Message"></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </div>
</body>
</html>

```
```
Style.css:
*{
    margin: 0px;
    padding: 0px;
}




body{
    background-image: url("luxury-bar-illuminated-by-modern-lighting-equipment-generated-by-ai.jpg");

  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  
    
}
.wel{
  text-align: center;
  margin: 20%;
  font-weight: bolder;
  font-size: larger;
  color: white;
  
}



.menu-page{
  background-image: url("vegetables-set-left-black-slate.jpg");
}

.header{

    text-align: center;
 color: #FFF8DC;
    font-size: 2rem;
    font-weight: bold;
    margin-top: 5px;
}
.bar{
     background-color: rgba(0, 0, 0, 0.5);
    margin-top: 20px;
    text-align: center;
    padding: 0.5rem 0;
    
}
.bar a{
      color:white;
            text-decoration: none;
            margin:32px;
            font-size: 1.1rem;
}
.bar a:hover{
  font-size: medium;
 background-color:rgb(227, 76, 17);
 padding: 10px;
  border-radius: 100px;
  box-shadow: 0 0 30px rgb(227, 76, 17), 0 0 30px rgb(227, 76, 17), 0 0 30px rgb(227, 76, 17);
color: rgb(19, 19, 18);
}





/* ===== menu.css ===== */


nav {
  background:rgba(0, 0, 0, 0.5);
  padding: 15px;
  text-align: center;
  transition: color 0.3s ease;

  
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline-block;
  margin: 0 15px;
}
nav ul li a:hover{
  font-size: medium;
 background-color:gold;
 padding: 10px;
  border-radius: 100px;
  box-shadow: 0 0 30px gold, 0 0 30px gold, 0 0 30px gold;
color: rgb(19, 19, 18);

}

nav ul li a {
  color: #f5f2f2;
  text-decoration: none;
  font-weight: bold;
}
.menu-page nav ul li a:hover{
 font-size: medium;
 background-color:#001F3F;
 padding: 10px;
  border-radius: 100px;
  box-shadow: 0 0 30px #001F3F, 0 0 10px #f7f9fa, 0 0 30px #001F3F;
color: rgb(245, 245, 244);


}








.page-title{
  text-align: center;
  margin: 20px;
  font-weight: bold;
  font-size: xx-large;
  color: yellow;
  letter-spacing: 2px;
}


.menu-grid, .team-grid {
   display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
  justify-items: center;
  padding: 50px 10%;
}
.menu-item:hover {
  transform: translateY(-8px);
  box-shadow: 0 30px 30px rgba(255,215,0,0.4);
}



.menu-item, .team-member {
  background: rgba(0, 0, 0, 0.4);
  backdrop-filter: blur(8px);
  border: 1px solid rgba(255,255,255,0.2);
  border-radius: 15px;
  text-align: center;
  padding: 20px;
  width: 250px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.menu-item img, .team-member img {
   background: rgba(0, 0, 0, 0.4);
  backdrop-filter: blur(8px);
  border: 1px solid rgba(255,255,255,0.2);
  border-radius: 15px;
  text-align: center;
  padding:3px;
  width: 200px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.menu-item p, .team-member h3 {
  color: gold;
  font-weight: 500;
  padding-top: px;
}

.team-section h2 {
  color: #f2c94c;
}

/*About.css */
.admin-page{
  background-image: url("broken-bio-cardboard-fork-copy-space.jpg");
}

.team-member:hover{
   transform: translateY(-8px);
  box-shadow: 0 10px 20px rgba(255,215,0,0.4);
}

nav ul li a:hover{
  font-size: medium;
 background-color:gold;
 padding: 10px;
  border-radius: 100px;
  box-shadow: 0 0 30px gold, 0 0 30px gold, 0 0 30px gold;
color: rgb(19, 19, 18);

}
.team-section h2 {
  color: #f2c94c;
  font-weight: bolder;
  margin-top: 20px;
}


/*contact.css*/
body.contact-page {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: url('admin.jpg') no-repeat center center fixed;
  background-size: cover;
  color: white;
}

.contact-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: flex-start;
  background-color: rgba(0, 0, 0, 0.6);
  padding: 50px 20px;
  min-height: 100vh;
}

.contact-info, .contact-form {
  flex: 1 1 300px;
  margin: 20px;
}

.contact-info h1 {
  color: #f2c94c;
  margin-bottom: 20px;
}

.contact-info p {
  font-size: 16px;
  margin: 10px 0;
}

.contact-form form {
  display: flex;
  flex-direction: column;
}

.contact-form input,
.contact-form textarea {
  padding: 12px;
  border: none;
  border-radius: 6px;
  margin-bottom: 15px;
  font-size: 16px;
}

.contact-form button {
  background-color: #f2c94c;
  border: none;
  padding: 12px;
  border-radius: 6px;
  font-size: 16px;
  color: #333;
}

.contact-page nav ul li a:hover{
font-size: medium;
 background-color:#000000;
 padding: 10px;
  border-radius: 100px;
  box-shadow: 0 0 30px #f1f2f3, 0 0 10px #f7f9fa, 0 0 30px #e6e7e8;
color: rgb(245, 245, 244);
}






```

## OUTPUT:
![alt text](<Screenshot 2025-11-01 143447.png>)
![alt text](<Screenshot 2025-11-01 143457.png>)
![alt text](<Screenshot 2025-11-01 143510.png>)
![alt text](<Screenshot 2025-11-01 143520.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
