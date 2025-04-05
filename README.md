# Week-3-assignment
Week 3 Assignment on CSS

**HTML CODE**
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MUTTON CENTER</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main_header">   
         <h1>MUTTON DEN LIMITED</h1>
    </header>
<section class="content">
    <p>We the Mutton Den Limited are located in Kiambu town opposite Ola oil company and 
        we are excited to give you great and the best services here .YOU'RE ALL WELCOME.Tell a 
        friend to tell a friend .HAPPY MUTTON SHOPPING.
    </p>
    <img src="viazikaraiandchoma.jpg" alt="Sample Image" class="styled-image">
</section>

<footer>Created by Me "Lisia"</footer>
</body>
</html>








**CSS CODE**

#main_header {
    background-color: rgb(224, 28, 28);
}
body{
    background-color: rgb(238, 248, 248);
    margin: 0%;
    padding: 0px;
    color:aliceblue;
}

.styled-image{
    width: 100%;
  border: 4px solid #141414;
  border-radius: 10px;
  margin-top: 20px;

}

.content{
    margin: 30px auto;
  padding: 20px;
  max-width: 600px;
  background-color: #111111;
  border: 2px solid #1b1b1b;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}
footer{
    text-align: center;
  padding: 15px;
  margin-top: 40px;
  background-color: #141313;
  font-size: 14px;
}
