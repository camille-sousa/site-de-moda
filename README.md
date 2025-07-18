<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>camille vitoria</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-4Q6Gf2aSP4eDXB8Miphtr37CMZZQ5oXLH2yaXMJ2w8e2ZtHTl7GptT4jmndRuHDT" crossorigin="anonymous">
    <!---linking google font for icons-->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@24,400,0,0&icon_names=arrow_forward" />
     
    
  <link rel="stylesheet" href="style.css">

</head>

<body>
   
  <!--Abertura da barra de navegação-->
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">FASHION</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
       </button>
       <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">principal</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">promoção</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              modas
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item"
                  href="https://www.ciamaritima.com.br/?srsltid=AfmBOorLo3aqsZsb_57SN15JDJUeX5Sv2sNZJgm0OBud4ZEIUTmy0QBn">biquínis</a>
              </li>
              <li><a class="dropdown-item" href="https://www.donnacarioca.com.br/">academia</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" aria-disabled="true" href="#">vestidos</a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="digite.." aria-label="digite.." />
          <button class="btn btn-outline-success" type="submit">pesquisar</button>
        </form>
      </div>
    </div>
  </nav>
    <!--fechamento da barra de navegação-->
    <div class="content">
      <div class="slides">
        <input type="radio" name="slide" id="slide1" checked>
        <input type="radio" name="slide" id="slide2">
        <input type="radio" name="slide" id="slide3">
        <input type="radio" name="slide" id="slide4">


        <div class="slide s1">
          <img src="images/image1.jpg" alt="biquínis">
        </div>
         <div class="slide">
           <img src="images/image2.jpg" alt="casual">
        </div>
         <div class="slide">
           <img src="images/image3.jpg" alt="vestidos">
        </div>
         <div class="slide">
           <img src="images/image4.jpg" alt="sport">
        </div>
      </div>

     
      <div class="navigation">
        <label class="bar" for="slide1"></label>
        <label class="bar" for="slide2"></label>
        <label class="bar" for="slide3"></label>
        <label class="bar" for="slide4"></label>
      </div>
    </div>
    

    <!---começo do container-->  
    <div class="container">
   <div class="child">
    <h2 class="meu-titulo">CASUAL</h2>
     <div>
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS484SyQ2ze9jooX_uMh4BOT0Ywc0G6cp83uA&s"
         alt="100px">
       <text type="text">$ 190.20</text>
       <a class="button" href="https://lista.mercadolivre.com.br/conjunto-feminino">comprar</a>
     </div>
   </div>
   <div class="child">
    <h2 class="meu-titulo">BIQUÍNIS</h2>
     <div>
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJrRen9FiPMpCHCIIcR3_LD_bk7hfVi2ezQQ&s"
         alt="200px">
       <text type="text">$ 80.00</text>
       <a class="button"
         href="https://www.ciamaritima.com.br/biquinis?srsltid=AfmBOoqPvETkAepSyrzxooY_f-AXSPNWTrtc8ON1gFfW0mx0l0ajtuDt">comprar</a>
     </div>
   </div>
   <div class="child">
    <h2 class="meu-titulo">VESTIDOS</h2>
     <div>
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR8hRRFXB0VpALaZ6WNGYdXSQlfGPVzI3f77A&s"
         alt="100px">
       <text type="text">$ 550.90</text>
       <a class="button" href="">comprar</a>
     </div>
   </div>
   <div class="child">
    <h2 class="meu-titulo">SPORT</h2>
     <div>
       <img
         src="data:image/jpeg;base64,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"
         alt="100px">
       <text type="text">$ 90.00</text>
       <a class="button"
         href="https://www.ciamaritima.com.br/biquinis?srsltid=AfmBOoqPvETkAepSyrzxooY_f-AXSPNWTrtc8ON1gFfW0mx0l0ajtuDt">comprar</a>
     </div>
   </div>
 </div>
 <!--final do container-->
 <!--começo-->
 <div class="father">
   <h2 class="titulo">PROMOÇÕES</h2>
    <div class="filho">
      <img src="images/image7.jpg" alt="skin care">
    </div>
    <div class="filho">
      <img src="images/image7.jpg" alt="skin care">
    </div>
    <div class="filho">
      <img src="images/image7.jpg" alt="skin care">
    </div>
    
 </div>
 <!---the end-->
  
 <!---começo do container2-->
 <div class="container2">
   <div class="child">
     <div>
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS484SyQ2ze9jooX_uMh4BOT0Ywc0G6cp83uA&s"
         alt="100px">
       <text type="text">$ 190.20</text>
       <a class="button" href="https://lista.mercadolivre.com.br/conjunto-feminino">comprar</a>
     </div>
   </div>
    <div class="child">
     <div>
       <img src="https://m.media-amazon.com/images/I/41fZY3rtQHL._SY1000_.jpg"
         alt="100px">
       <text type="text">$ 190.20</text>
       <a class="button" href="https://lista.mercadolivre.com.br/conjunto-feminino">comprar</a>
     </div>
   </div>
    <div class="child">
     <div>
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS484SyQ2ze9jooX_uMh4BOT0Ywc0G6cp83uA&s"
         alt="100px">
       <text type="text">$ 190.20</text>
       <a class="button" href="https://lista.mercadolivre.com.br/conjunto-feminino">comprar</a>
     </div>
   </div>
    <div class="child">
     <div>
       <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS484SyQ2ze9jooX_uMh4BOT0Ywc0G6cp83uA&s"
         alt="100px">
       <text type="text">$ 190.20</text>
       <a class="button" href="https://lista.mercadolivre.com.br/conjunto-feminino">comprar</a>
     </div>
   </div>
 </div> 
  <!---final do container2-->
  

   
 

    

</body>

</html>




body {
  margin: 0;
  padding:0;
  height: 100vh;
  width: 100vw;
  background: white
}

.content{
     height: 550px;
     width: 950px;
     border-radius: 20px ;
     overflow: hidden;
     position:absolute;
     top: 50%;
     left: 50%;
     transform: translate(-50%, -50%);
}
.navigation{
     position: absolute;
     bottom: 20px;
     left: 50%;
     transform: translate(-50%) ;
     display: flex;
}
.bar{
    width:60px ;
    height: 15px;
    border: 2px solid #fff;
    margin: 6px;
    border-radius: 5px;
    cursor: pointer;
    transition: .4s;
    
}
.bar:hover{
     background-color: #fff;
}
input{
     display: none;
}
.slides{
     display: flex;
     width: 500%;
     height: 100%;
    
}
.slide{
 width: 20%;
 transition: .6s;
 
}
.slide .images {
 width: 100%;
 height: 100%;
 

}
#slide1:checked ~ .s1{
 margin-left: 0;
}
#slide2:checked ~ .s1{
 margin-left: -20%;
}
#slide3:checked ~ .s1{
 margin-left: -40%;
} 
#slide4:checked ~ .s1{
 margin-left: -60%;
}

.meu-titulo {
    color: black;
    font-size: 20px;
    text-align: center;
    margin-top:5px;
    border: 1px solid rgb(6, 6, 6);
    background-color: rgb(90, 90, 88);
  
}

.container{
display: flex;
flex-wrap: wrap;
padding: 80px;
margin-top: 500px;
margin-left: 110px;

}

.child{
width:220px;
height:350px;
border: 1px solid white;
margin: 7px;



}
.child:hover{
    transform: scale(1.05);
    


}
.child div{
    padding: 9px;
    height: 100%;
    background-color: rgb(127, 124, 124);
   
}
.child div img{
margin-bottom: 16px;

}
.button{
width:100px;
height: 50px;
margin-top:10px;
padding: 12px 24px;
font-size: 16px;
background-color: #f09b38;
color: white;
border:1px;
border-radius: 5px;
box-shadow: 0 4px #f4dd77;


}
.titulo{
  text-align: center;
  font-family: Arial, sans-serif;
}


.filho{
  width:400px;
  height:350px;
  margin-top:70px;
  display: flex;
  padding:10px;  

}

.container2{
  display: flex;
  flex-wrap: wrap;
  padding: 80px;
  margin-left: 110px;


}



