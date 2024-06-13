# demo
this is my first git repository
<br>
Author - MR.SOLO
<br>
amazone clone html file
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazone</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="navbar">
            <div class="nav-logo border">
                <div class="logo"></div>

            </div>

            <div class="nav-adress border">
                <p class="add-first">Deliver to</p>
                <div class="add-icon">
                    <i class="fa-solid fa-location-dot"></i>
                    <p class="add-second">Indai</p>
                </div>
            </div>

        <div class="nav-search">
            <select class="search-selet">
                <option>All</option>
            </select>
                <input placeholder="search Amazone" class="search-input">
                <div class="search-icon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
        </div>
        <div class="nav-singin border">
            <p><span>Hello,sing in</span></p>
            <p class="nav-second">Account & Lists</p>
        </div>

        <div class="nav-returns border">
            <p><span>Returns</span></p>
            <p class="nav-second">& Orders</p>
        </div>

        <div class="nav-cart border">
            <i class="fa-solid fa-cart-shopping"></i>
            Cart
        </div>
        </div>

        <div class="panel">
            <div class="panel-all">
                <i class="fa-solid fa-bars"></i>
                ALL
            </div>
            <div class="panel-ops">
                <p>Today`s Deal</p>
                <p>Customer Service</p>
                <p>Registry</p>
                <p>Gift Cards</p>
                <p>Sell</p>
            </div>
            <div class="panel-deals">
                Shop in electronics
            </div>
        </div>
    </header>
    <div class="hero-section">
        <div class="hero-msg">
            <p>You are on amazon.com. You can also shop on Amazon India for millions of products with fast local delivery. <a>Click here to go to amazon.in</a></p>
        </div>
    </div>

    <div class="shop-section">
        <div class="box1 box">
           <div class="box-content"> <h2>Toys under $25</h2>
            <div class="box-img" style="background-image: url(toys.jpg);"></div>
            <pr>see more</pr>
           </div>
        </div>
        <div class="box2 box"><div class="box-content"> <h2>Shop deals in Fashion</h2>
            <div class="box-img" style="background-image: url(clothes2.jpg);"></div>
            <pr>see more</pr>
           </div></div>
        <div class="box3 box"><div class="box-content"> <h2>Refresh your space</h2>
            <div class="box-img" style="background-image: url(space1.jpg);"></div>
            <pr>see more</pr>
           </div></div>
        <div class="box4 box"><div class="box-content"> <h2>Deals in PCs</h2>
            <div class="box-img" style="background-image: url(pc1.jpg);"></div>
            <pr>see more</pr>
           </div>
        </div>
        
         
    </div>

    <footer>
        <div class="foot-panel1">
            Back to top
        </div>
        <div class="foot-panel2">
            <u>
                <pr>Get to Know Us</pr> <u>
                    <pr>Get to Know Us</pr>
                    <a>Careers</a>
                    <a>Blog</a>
                    <a>About Amazon</a>
                     <a>Investor Relations</a>
                      <a>Amazon Devices</a>
                       <a>Amazon Science</a>
                </u>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                 <a>Investor Relations</a>
                  <a>Amazon Devices</a>
                   <a>Amazon Science</a>
            </u>
            <u>
                <pr>Get to Know Us</pr>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                 <a>Investor Relations</a>
                  <a>Amazon Devices</a>
                   <a>Amazon Science</a>
            </u>
            <u>
                <pr>Get to Know Us</pr>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                 <a>Investor Relations</a>
                  <a>Amazon Devices</a>
                   <a>Amazon Science</a>
            </u>
            <u>
                <pr>Get to Know Us</pr>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                 <a>Investor Relations</a>
                  <a>Amazon Devices</a>
                   <a>Amazon Science</a>
            </u>
           
        </div>
    </footer>

   
</body>
</html>


<br>


style.css file

{
    margin: 0;
    font-family: arial;
    border: border-box;
}

.navbar{
    height: 60px;
    background-color: #0f1111;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}

.nav-logo{
    height: 50px;
    width: 100px;
}

.logo{
    background-image: url(amazone\ logo\ 1.jpg);
    background-size: cover;
    height: 50px;
    width: 100%;
}

.border{
    border: 1.5px solid transparent;
}

.border:hover{

    border: 1.5px solid white;
}


/**box2**/

.add-first{
    color: #cccccc;
    font-size: 0.80rem;
    margin-left: 15px;

}

.add-second{
    font-size: 1rem;
    margin-left: 4px;

}

.add-icon{
    display: flex;
    align-items: center;
    
}

/**box3**/
.nav-search{
    display: flex;
    justify-content: space-evenly;
    background-color: pink;
    width: 620px;
    height: 40px;
    border-radius: 4px;
}

.search-selet{
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;
}

.search-input{
    width: 100%;
    font-size: 1rem;
    border: none;
}

.search-icon{
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: #febd68;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    color: #0f1111;
}
.nav-search:hover {
    border: 2px solid orange;
}

/**  box4  **/
span{
    font-size: 0.7rem;

}
.nav-second{
    font-size: 0.85rem;
    font-weight: 700;
}

/** box5  **/

.nav-cart i{
    font-size: 30px;

}

.nav-cart {
    font-size: 0.85rem;
    font-weight: 700;
}

/** panle **/

.panel {
    height: 40px;
    background-color: #222f3d;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;

}

.panel-ops p {
    display: inline;
    margin-left: 15px;
}

.panel-ops{
    width: 70%;
    font-size: 0.85rem;
}

.panel-deals{
    font-size: 0.9rem;
    font-weight: 700;
}


/** hero section **/

.hero-section{
    background-image: url(amazone\ hero.jpg);
    background-color: cover;
    height: 350px;
    display: flex;
    justify-content: center;
    align-items: flex-end;

}

.hero-msg {
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: .85rem;
    width: 80%;
    margin-bottom: 20px;

}
    
  

.hero-msg a { 
    color: #007185;

}


/** shop-section **/

.shop-section{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    background-color: #e2e7e6;
}


.box{
    border: 2px solid black;
    height: 400px;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px;
    margin-top: 15px;
}

.box-img{
    height: 300px;
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;
}

.box-content{
    margin-left: 1rem;
    margin-right: 1rem;
}

.box-content p{
    color: #007185;
}

/** footer **/
footer{
    margin-top: 15px;
}

.foot-panel1{
    background-color: #37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.5rem;
}

.foot-panel2{
    background-color: #222f3d;
    color: white;
    height: 500px;
    display: flex;
    justify-content: space-evenly;
}

ul a {
    display: block;
}


