<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>Eat & Joy</title> 
    <style>* { 
     margin: 0; 
     padding: 0;  
     box-sizing: border-box;    
    }    
    body { 
    background-color: #e5533c;
     font-family: Arial, sans-serif;    
     color: #333;     
     line-height: 1.6;    
    }
    .container {     
     width: 90%;     
     max-width: 1200px;    
     margin: auto;     
    } 
    header {     
     background-color: #333;    
     color: #b82222;     
     padding: 15px 0;     
     position: fixed;     
     width: 100%;     
     top: 0;     
     z-index: 10;    
    }    
    header .logo {    
     font-size: 1.8em;    
     margin-left: 20px;  
     display: inline-block;    
    }
    header nav ul {     
     list-style: none;     
     float: right;    
     margin-right: 20px; 
    } 
    header nav ul li {     
     display: inline;     
     margin-left: 20px;     
    } 
    header nav ul li a {     
     color:  #fff;     
     text-decoration: none;     
     font-size: 1.1em;     
    }   
     header nav ul li a:hover {     
     color: #ff6347;     
    }     
    .hero {     
     background-color: #e5533c;
      no-repeat center center/cover;     
     color: #0b0b0b;     
     height: 80vh;     
     text-align: center;    
     padding-top: 150px; 
    
    }   
    .hero h2 {     
     font-size: 3em;     
    } 
    .hero p {     
     font-size: 1.5em;    
     margin: 10px 0;     
    } 
    .btn {     
        display: inline-block;     
     padding: 10px 20px; 
     background-color: #ff6347;     
     color: #fff;     
     text-decoration: none;     
     border-radius: 5px;    
    } 
    .btn:hover {     
     background-color:   #e5533c;     
    }
    .about {     
     padding: 60px 0; 
     background-color:  #e5533c;
     text-align: center;     
    } 
    .about h2 {     
     font-size: 2.5em;     
     margin-bottom: 20px;    
    }    
    .menu {     
     padding: 60px 0;    
     text-align: center;    
    }  
    .menu h2 {     
     font-size: 2.5em;    
     margin-bottom: 20px;    
    } 
    .menu-items {     
     display: flex;    
     flex-wrap: wrap;    
     justify-content: space-around;    
    } 
    .menu-item {
     width: 30%;    
     background: #f9f9f9;    
     padding: 20px;     
     margin: 10px; 
     border-radius: 5px; 
     text-align: left; 
    } 
    .menu-item h3 { 
     color: #ff6347; 
     font-size: 1.8em; 
    }
    .menu-item p { 
     margin: 10px 0; 
    } 
    .menu-item span { 
     font-weight: bold; 
    }    
    .testimonials { 
     padding: 60px 0; 
     background-color:#e5533c; 
     text-align: center; 
    } 
    .testimonials h2 { 
     font-size: 2.5em; 
     margin-bottom: 20px; 
   }   
     .testimonial { 
     margin: 20px auto; 
     max-width: 600px; 
     font-style: italic; 
    }  
    .contact { 
     padding: 60px 0; 
     text-align: center; 
    } 
    .contact form { 
     max-width: 600px; 
     margin: auto; 
    } 
    .contact input, .contact textarea { 
     width: 100%; 
     padding: 10px; 
     margin: 10px 0; 
     border: 1px solid #ccc; 
     border-radius: 5px; 
    } 
    .contact button { 
     width: 100%; 
     padding: 10px; 
     background-color: #ff6347; 
     color: #fff; 
     border: none; 
     border-radius: 5px; 
     cursor: pointer; 
    } 
    .contact button:hover { 
     background-color: #e5533c; 
    } 
    footer { 
     background-color: #333; 
     color: #fff; 
     text-align: center; 
     padding: 20px 0; 
     margin-top: 20px; 
    }</style> 
</head> 
<body> 
    <header>
        <div class="container"> 
            <h1 class="logo" >Eat & Joy</h1> 
            <nav> 
                <ul> 
                    <li><a href="#home">Home</a></li> 
                    <li><a href="#about">About</a></li> 
                    <li><a href="#menu">Menu</a></li> 
                    <li><a href="#testimonials">Testimonials</a></li> 
                    <li><a href="#contact">Contact</a></li> 
                </ul> 
            </nav> 
        </div> 
    </header> 
    <section id="home" class="hero"> 
        <div class="container"> 
            <h2>Welcome to Restaurant </h2> 
            <p>Experience the best dining experience</p> 
            <a href="#menu" class="btn">See Our Menu</a> 
        </div> 
    </section> 
    <section id="about" class="about"> 
            <div class="container"> 
            <h2>About Us</h2> 
            <p> has been serving delicious meals  over a longtime. We use only the freshest ingredients to prepare mouth-watering dishes.</p> 
        </div> 
    </section> 
    <section id="menu" class="menu">
        <div class="container"> 
            <h2>Our Menu</h2> 
            <div class="menu-items"> 
            <div class="menu-item"> 
                    <h3>Grilled Chicken</h3> 
                    <img src="https://wallpapercave.com/wp/wp4692292.jpg" alt="" height="200" width="300" >
                    <br> 
                    <p>Juicy grilled chicken served with seasonal vegetables</p> 
                    Rs.795 
                </div> 
                <div class="menu-item"> 
                    <h3>Pasta Alfredo</h3>
                    <img src="https://c4.wallpaperflare.com/wallpaper/346/714/528/pasta-4k-high-resolution-wallpaper-preview.jpg" alt="" height="200" width="300"                     <br> 
                    <p>Classic Alfredo sauce with fresh pasta</p> 
                    <br> 
                    Rs.200
                </div> 
                <div class="menu-item"> 
                    <h3>Caesar Salad</h3> 
                    <img src="https://wallpapercave.com/wp/wp3131414.jpg" alt="" height="200" width="300" >
                    <br> 
                    <p>Crisp romaine lettuce, croutons, and Parmesan cheese</p> 
                    Rs.370 
                </div> 
                <div class="menu-item"> 
                    <h3>Shawarma</h3> 
                    <img src="https://img.freepik.com/premium-photo/big-shawarma-kebab-fried-fire-street-food-sandwich-gyro-fresh-roll-lavash-pita-bread-chicken-beef-shawarma-3d-illustration_86390-9693.jpg?w=740" alt="" height="200" width="300" >
                    <br> 
                    <p>Tasty shawarma with different vegetables</p> 
                    Rs.220
                </div> 
                <div class="menu-item"> 
                    <h3>KFC Chicken</h3> 
                    <img src="https://wallpapercave.com/wp/wp9888493.jpg" alt="" height="200" width="300" >
                    <br> 
                    <p>crispy KFC with sauce</p> 
                    Rs.350 
                </div> 
                <div class="menu-item"> 
                    <h3>Spring Rolls</h3> 
                    <img src="https://wallpaperaccess.com/full/6905828.jpg" alt="" height="200" width="300" >
                    <br> 
                    <p>delicious spring rolls</p> 
                    Rs.129
                </div> 
                <div class="menu-item"> 
                    <h3>Pizza</h3> 
                    <img src="https://images7.alphacoders.com/596/thumb-1920-596343.jpg" alt="" height="200" width="300" >
                    <br> 
                    <p>"crispy crust,heavenly bites"</p> 
                    Rs.499
                </div> 
                <div class="menu-item"> 
                    <h3>Burger</h3>
                    <img src="https://static.vecteezy.com/system/resources/previews/030/683/548/non_2x/burgers-high-quality-4k-hdr-free-photo.jpg" alt="" height="200" width="300" >
                    <br> 
                    <p>"Juicy mouth-watering Burger"</p> 
                    Rs.399
                </div> 
                <div class="menu-item"> 
                    <h3>Pav Bhaji</h3> 
                    <img src="https://img.freepik.com/premium-photo/cheese-pav-bhaji-recipe-is-street-food-bhajipav-recipe-with-addition-cheese_466689-86301.jpg?w=1480" alt="" height="200" width="300" >
                    <br> 
                    <p>"spiced mixture of mashed vegetables"</p> 
                    Rs.149
                </div> 
                <div class="menu-item">
                    <h3>Fried fish curry</h3> 
                    <img src="https://1.bp.blogspot.com/-dmr7TvaMJ7c/WRyLh1RZjlI/AAAAAAAAIF4/uPHo3WFtctE8ZS34-s0mkRyNRkU-2-SzgCLcB/s1600/0000000000000000000000A%2B%25281%2529.jpg" alt="" height="200" width="300" >
                    <br> 
                    <p>"Spicy fish slices"</p> 
                    Rs.199
                </div>
                <div class="menu-item"> 
                    <h3>Sandwhich</h3> 
                    <img src="https://img.freepik.com/premium-photo/ultra-realistic-4k-sandwich-white-background-8k-hd_899449-64757.jpg" alt="" height="200" width="300" >
                    <br> 
                    <p>"Tasty Tastyyy sandwich"</p> 
                    Rs.149
                </div> 
                <div class="menu-item"> 
                    <h3>apricot delight</h3> 
                    <img src="https://img.freepik.com/premium-photo/delicious-neapolitan-flan-recipe_1016086-2948.jpg" alt="" height="200" width="300" >
                    <br> 
                    <p>"Light your night with this delicious desert"</p> 
                    Rs.299
                </div> 
            </div> 
        </div> 
    </section> 
    <section id="testimonials" class="testimonials"> 
        <div class="container"> 
            <h2>What Our Customers Say</h2> 
            <div class="testimonial"> 
                <p>"The best dining experience I've ever had!" - Nani</p> 
            </div> 
            <div class="testimonial"> 
                <p>"Delicious food and amazing ambiance." - Pawan Kalyan</p> 
            </div> 
            <div class="testimonial"> 
                <p>"Highly recommended!" - John Cena</p> 
            </div> 
        </div> 
    </section> 
    <section id="contact" class="contact"> 
        <div class="container"> 
            <h2>Contact Us</h2> 
            <form> 
                <input type="text" placeholder="Your Name" required> 
                <input type="email" placeholder="Your Email" required> 
                <textarea placeholder="Your Message" required></textarea> 
                <button type="submit" class="btn">Send Message</button> 
            </form> 
        </div> 
    </section> 
    <footer> 
        <p> Eat & Joy.Experence the best dining.</p> 
    </footer>
</body> 
</html>
