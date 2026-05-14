Index.html

\<\!DOCTYPE html\>  
\<html lang\="en"\>  
\<head\>  
    \<meta charset\="UTF-8"\>  
    \<meta name\="viewport" content\="width=device-width, initial-scale=1.0"\>  
    \<title\>Document\</title\>  
    \<link rel\="stylesheet" href\="style.css"\>  
\</head\>  
\<body\>  
    \<div class\="bg-container"\>  
        \<h1 class\="heading"\>SPICE MAGIC\</h1\>  
        \<h1 class\="heading"\>Taste the magic where every bite feels magical\</h1\>  
    \</div\>  
    \<h1 class\="menu"\>Menu Highlight's\</h1\>  
    \<div class\="cards-container"\>  
        \<div class\="card"\>  
            \<img  class\="image" src\="https://www.licious.in/blog/wp-content/uploads/2022/06/chicken-hyderabadi-biryani-01.jpg"\>  
            \<h1 class\="title"\>Chicken Dum briyani\</h1\>  
            \<h1 class\="price"\>Price:414rs\</h1\>  
            \<button class\="btn"\>Add to cart\</button\>  
        \</div\>  
        \<div class\="card"\>  
            \<img  class\="image" src\="https://saffronice.com/cdn/shop/articles/Prawn\_biryani\_fda99ee1-137b-4ce0-ad51-dabb40db5b23.jpg?v=1766447221"\>  
            \<h1 class\="title"\>Prawns briyani\</h1\>  
            \<h1 class\="price"\>Price:529rs\</h1\>  
            \<button class\="btn"\>Add to cart\</button\>  
        \</div\>  
        \<div class\="card"\>  
            \<img  class\="image" src\="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSYb8tkae3h8UTD1neARRFuCVNlleM2mtDzCg\&usqp=CAU"\>  
            \<h1 class\="title"\>Spice magic briyani\</h1\>  
            \<h1 class\="price"\>Price:621rs\</h1\>  
            \<button class\="btn"\>Add to cart\</button\>  
        \</div\>  
        \<div class\="card"\>  
            \<img  class\="image" src\="https://www.indianveggiedelight.com/wp-content/uploads/2019/09/mushroom-biryani-featured.jpg"\>  
            \<h1 class\="title"\>Mushroom briyani\</h1\>  
            \<h1 class\="price"\>Price:356rs\</h1\>  
            \<button class\="btn"\>Add to cart\</button\>  
        \</div\>  
    \</div\>  
\</body\>  
\</html\>

Style.css

.bg-container{  
    background-image: url("https://t3.ftcdn.net/jpg/07/58/26/62/360\_F\_758266271\_yksdY7RLYIIY6jofjJorjylEDOvgcuze.jpg");  
    width:100%;  
    height: 50vh;  
    background-size: cover;  
    padding-top: 30px;  
}

.heading{  
    color:rgb(249, 248, 248);  
    font-size: 36px;  
    font-weight: 600;  
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;  
    text-align: center;

}

.menu{  
    color:purple;  
    font-size: 40px;  
    font-weight: 600;  
    text-align: center;  
    font-family: cursive;  
}

.cards-container{  
    width: 100%;  
    height: 60vh;  
    background-color: white;  
    display: flex;  
    justify-content: space-evenly;  
    padding-top: 50px;  
}

.card{  
    width:300px;  
    height: 400px;  
    background-color: white;  
    display: flex;  
    flex-direction: column;  
    align-items: center;  
    box-shadow: 0px 0px 8px 1px black;  
    border-radius: 30px;  
}

.image{  
    width:100%;  
    height:50%;  
    margin-bottom: 10px;  
}

.title{  
    color:black;  
    font-size: 28px;  
    font-weight: 600;  
    font-family: sans-serif;  
}

.price{  
    color:black;  
    font-size: 24px;  
    font-weight: 600;  
    font-family: sans-serif;  
}

.btn{  
    background-color: aquamarine;  
    color: black;  
    width: 130px;  
    height: 35px;  
    font-size: 20px;  
    border: none;  
    border-radius: 50px;  
    cursor: pointer;  
}

