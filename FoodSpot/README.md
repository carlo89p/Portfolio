Food Spot Excercise

---

_CSS code guidelines_

---

@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap");

- {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  font-family: "Poppins", sans-serif;
  scroll-behavior: smooth;
  }

p {
font-weight: 300;
color: #111;
}
section {
padding: 80px;
}

header {
position: fixed;
top: 0;
left: 0;
width: 100%;
z-index: 1;
display: flex;
justify-content: space-between;
align-items: center;
padding: 40px 100px;
}

.logo {
color: #111;
font-weight: bold;
font-size: 2.5em;
text-decoration: none;
}

header .logo span {
color: #ff0157;
}

header .navigation {
display: flex;
position: relative;
}

header .navigation li {
list-style: none;
margin-left: 30px;
}

header .navigation li a {
text-decoration: none;
color: #111;
font-weight: 300;
font-size: 1.5em;
transition: 0.5s;
}

.banner {
width: 100%;
min-height: 100vh;
display: flex;
justify-content: center;
align-items: center;
background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)),
url(https://i.postimg.cc/s29LNR86/bg.jpg);
background-size: cover;
}

.content {
max-width: 900px;
text-align: center;
}

.banner .content h2 {
font-size: 5em;
color: white;
}

.banner .content p {
font-size: 1em;
color: white;
}

.btn {
font-size: 1.5em;
color: white;
background-color: #ff0157;
padding: 10px 30px;
text-decoration: none;
text-transform: uppercase;
letter-spacing: 2px;
transition: 0.5s;
margin-top: 40px;
display: inline-block;
}

.about {
padding: 80px;
}

.row {
display: flex;
justify-content: space-between;
width: 100%;
}

.row .col50 {
width: 48%;
}

.imgbx {
width: 100%;
min-height: 300px;
}

.imgbx img {
width: 100%;
height: 100%;
object-fit: cover;
}

.titleText {
color: #111;
font-size: 2em;
font-weight: 300;
}

.titleText span {
color: #ff0157;
font-weight: 700;
font-size: 1.5em;
}

.menu {
padding: 80px;
}

.title {
width: 100%;
display: flex;
justify-content: center;
align-items: center;
flex-direction: column;
}

.menu-content {
display: flex;
justify-content: center;
flex-wrap: wrap;
margin-top: 40px;
}

.menu-content .box {
width: 340px;
margin: 20px;
border: 15px solid #fff;
box-shadow: 0 5px 35px lightgray;
}

.text {
text-align: center;
padding: 15px 0 5px;
}

.menu-content .box .imgbx {
width: 100%;
height: 300px;
}

.sticky {
background: #fff;
padding: 10px 100px;
box-shadow: 0 5px 20px rgba(0, 0, 0, 0.05);
}

.expert {
padding: 80px;
}
.expert .menu-content .box {
width: 250px;
margin: 30px;
border: 15px solid #fff;
box-shadow: 0 5px 35px rgba(0, 0, 0, 0.08);
}

.testimonial {
background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)),
url(https://i.postimg.cc/k5dZs5jR/bg2.jpg);
background-size: cover;
}

.title {
width: 100%;
display: flex;
justify-content: center;
align-items: center;
flex-direction: column;
}
.white {
color: white;
}

.testimonial .content {
display: flex;
justify-content: center;
flex-wrap: wrap;
margin-top: 40px;
max-width: 100%;
}
.testimonial .content .box {
width: 350px;
margin: 20px;
padding: 40px;
background: white;
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
}

.testimonial .content .box img {
border-radius: 48%;
object-fit: cover;
width: 100%;
height: 100%;
}

.testimonial .content .box .imgbx {
width: 100%;
height: 300px;
}

.text h2 {
margin-top: 20px;
font-size: 1.5em;
color: #ff0157;
font-weight: 600;
}

.text p {
font-style: italic;
}

.contactform {
padding: 75px 50px;
background: #fff;
box-shadow: 0 15px 50px rgba(0, 0, 0, 0.1);
max-width: 500px;
margin-top: 50px;
}

.contactform h3 {
color: #111;
font-size: 1.2em;
margin-bottom: 20px;
font-weight: 500;
}

.contactform .inputbox {
position: relative;
width: 100%;
margin-bottom: 20px;
}

.contactform .inputbox {
position: relative;
width: 100%;
margin-bottom: 20px;
}
.contactform .inputbox input,
.contactform .inputbox textarea {
width: 100%;
border: 1px solid #555;
border-radius: 10px;
padding: 10px;
color: #111;
outline: none;
font-size: 16px;
font-weight: 300;
resize: none;
}

.contactform .inputbox input[type="submit"] {
font-size: 1em;
color: #fff;
background: #ff0157;
display: inline-block;
text-transform: uppercase;
text-decoration: none;
letter-spacing: 2px;
max-width: 100px;
transition: 0.5s;
font-weight: 500;
border: none;
cursor: pointer;
}

.contactus {
background: url(https://i.postimg.cc/4NmrNq7y/bg3.jpg);
background-size: cover;
}

.footer {
background: #ff0157;
width: 100%;
height: 70px;
display: flex;
justify-content: center;
align-items: center;
flex-direction: column;
}

.footer p {
color: #fff;
font-weight: 300;
}

.footer .icons a {
color: #fff;
}

---

_HTML CODE GUIDELINES_

---

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>FoodSpot</title>
    <link rel="stylesheet" href="styles.css" class="stylesheet" />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css"
    />
  </head>
  <body>
    <header class="sticky">
      <a href="#" class="logo">Food<span>Spot</span></a>

      <ul class="navigation">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Menu</a></li>
        <li><a href="#">Expert</a></li>
        <li><a href="#">Testimonials</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </header>

    <section class="banner">
      <div class="content">
        <h2>Always Choose Good</h2>
        <p>
          Lorem ipsum dolor, sit amet eum Quos ipsa ipsum amet eum ullam nulla
          quaerat optio quidem dolores, molestiae libero similique iusto
          inventore aliquam dolorem. Ratione perferendis ipsa culpa sapiente
          totam?
        </p>
        <a href="#" class="btn">Our Menu</a>
      </div>
    </section>

    <section class="about">
      <div class="row">
        <div class="col50">
          <h2 class="titleText"><span>A</span>bout Us</h2>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Iste eius,
            dolorem necessitatibus vel ipsam perspiciatis a? Possimus illo
            voluptas voluptatem natus quasi blanditiis aliquam est, veritatis
            laudantium libero iusto nam consectetur ullam molestiae numquam id,
            voluptates nemo velit totam dicta?
          </p>
          <br />
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea alias
            dolorem quod ratione dicta placeat aut! Neque natus ducimus
            repellat, dignissimos molestias obcaecati explicabo qui fugiat est,
            libero earum autem.
          </p>
        </div>
        <div class="col50">
          <div class="imgbx">
            <img src="https://i.postimg.cc/13F2DFKZ/pizza.jpg" />
          </div>
        </div>
      </div>
    </section>

    <section class="menu">
      <div class="title">
        <h2 class="titleText">Our <span>M</span>enu</h2>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Error, at.
        </p>
      </div>

      <div class="menu-content">
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/sf0N8m6r/burger.jpg" />
          </div>
          <div class="text">
            <h3>Special Burgers</h3>
          </div>
        </div>
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/fLzP4rQw/pizza2.jpg" />
          </div>
          <div class="text">
            <h3>Special Pizzas</h3>
          </div>
        </div>
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/7PBF4wLj/fries.jpg" />
          </div>
          <div class="text">
            <h3>Tasty Fries</h3>
          </div>
        </div>
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/4dWSXQXp/sandwich.jpg" />
          </div>
          <div class="text">
            <h3>Special Sandwichs</h3>
          </div>
        </div>
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/5NTDHgL3/taco.jpg" />
          </div>
          <div class="text">
            <h3>Special Tacos</h3>
          </div>
        </div>
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/3N6fvr4R/cc.jpg" />
          </div>
          <div class="text">
            <h3>Cold Drinks</h3>
          </div>
        </div>
      </div>

      <div class="title">
        <a href="#" class="btn">View All</a>
      </div>
    </section>

    <section class="expert">
      <div class="title">
        <h2 class="titleText">Our Kitchen <span>E</span>xperts</h2>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Error, at.
        </p>
      </div>

      <div class="menu-content">
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/wx0pBDwf/expert1.jpg" />
          </div>
          <div class="text">
            <h3>Expert</h3>
          </div>
        </div>
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/8PYgRNQL/expert2.jpg" />
          </div>
          <div class="text">
            <h3>Expert</h3>
          </div>
        </div>
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/XYySxm4m/expert3.jpg" />
          </div>
          <div class="text">
            <h3>Expert</h3>
          </div>
        </div>
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/hv361bwK/expert4.jpg" />
          </div>
          <div class="text">
            <h3>Expert</h3>
          </div>
        </div>
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/hjsHfq1z/expert5.jpg" />
          </div>
          <div class="text">
            <h3>Expert</h3>
          </div>
        </div>
      </div>
    </section>

    <section class="testimonial">
      <div class="title white">
        <h2 class="titleText white">What they <span>s</span>aid about us</h2>
        <p class="white">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Error, at.
        </p>
      </div>
      <div class="content">
        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/XJ4Rjvd6/cust1.jpg" />
          </div>
          <div class="text">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti
              magnam quisquam temporibus assumenda nobis officia!
            </p>
            <h2>Customer</h2>
          </div>
        </div>

        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/DzkVN6zZ/cust-2.jpg" />
          </div>
          <div class="text">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti
              magnam quisquam temporibus assumenda nobis officia!
            </p>
            <h2>Customer</h2>
          </div>
        </div>

        <div class="box">
          <div class="imgbx">
            <img src="https://i.postimg.cc/s2YFCWBJ/cust3.jpg" />
          </div>
          <div class="text">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti
              magnam quisquam temporibus assumenda nobis officia!
            </p>
            <h2>Customer</h2>
          </div>
        </div>
      </div>
    </section>

    <section class="contactus">
      <div class="title">
        <h2 class="titleText"><span>C</span>ontact Us</h2>
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Error, at.
        </p>
      </div>
      <form action="#" method="POST">
        <div class="contactform">
          <h3>Send Message</h3>
          <div class="inputbox">
            <input type="text" placeholder="Name" required />
          </div>

          <div class="inputbox">
            <input type="email" placeholder="Email" required />
          </div>

          <div class="inputbox">
            <textarea placeholder="Message" required></textarea>
          </div>

          <div class="inputbox">
            <input type="submit" value="Send" />
          </div>
        </div>
      </form>
    </section>

    <div class="footer">
      <p>Design and code by Gururaj</p>
      <div class="icons">
        <a
          href="https://www.linkedin.com/in/gururaj-math-223360255/"
          target="_blank"
          ><i class="bx bxl-linkedin-square"></i
        ></a>
        <a href="https://codepen.io/gururajmath"
          ><i class="bx bxl-codepen" target="_blank"></i
        ></a>
        <a href="https://github.com/Gururaj-Math" target="_blank"
          ><i class="bx bxl-github"></i
        ></a>
      </div>
    </div>

  </body>
</html>

---

Making Sections of disregarded text makes it far easier to copy and paste and design cards with multiple elements that have to look the same.
I think I get the basics now.
