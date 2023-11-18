<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Developer-Portfolio</title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
body{
    background-color: #0a0213;
    color: rgb(241, 238, 238);
}

nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 50px;
    background-color: #2e0650ea;
}
 
nav ul{
    display: flex;
    justify-content: center;
}

nav ul li{
    margin: 0px 23px;
    color: #ece0e0;
}
nav ul li a{
    text-decoration: none;
    color: #ece0e0;
}
nav ul li a:hover{
    color: #3ab622;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

 .left{
   /* // margin: 10px -263px 10px 10px; */
   background-color: #380e0e;
   font-size: 2rem;

} 
 .right{
    /* margin: -360px 10px 10px 10px; */
    background-color: #2e0650ea;
} 

.firstsection{
    display: flex;
    justify-content: space-around;
    margin: 80px 0;
}

.firstsection > div{
   width: 30%;
}
.leftsec{
    /* background-color: red; */
    font-size: 2rem;
    /* margin: 70px 0; */
    width: 50%;

}
.rightsec{
    /* background-color: red; */
    width: 80%;
    margin: 38px 0;
}
.rightsec img{
    width: 80%;
    margin: -60px 60px;
}

.purple{
    color: #3ab622;
}
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="left">Siam's Portfolio</div>
            <div class="right">
                <ul>
                    
                    <li><a href="/">Home</a></li>
                    <li><a href="/">Adress</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section class="firstsection">
            <div class="leftsec">
             <div>SIAM IS HERE</div>
            <span id="element"></span>
        </div>
            <div class="rightsec">
                <img src="bg.png" alt="">
            </div>
        </section>
    </main>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
          strings: ['Hi, my name is <span class="purple">Siam</span>','i am a coding apprentice','I am from BSFMSTU','Dept. of Mathematics'],
          typeSpeed: 50,
        });
      </script>
</body>
</html>
