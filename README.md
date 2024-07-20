# sand-box-lading-page
 pagina simples
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-decoration: none;
  list-style: none;
  font-family: "Urbanist", sans-serif;

}


.conteiner{
  width: 1330px;
margin: 0 auto;
}

nav{
 
  display: flex;
  justify-content: space-between;
  align-items: center;
height: 8vh;
}

nav .navbar{
   display: none; 
  border: none;
  background-color: transparent;
}
.nav-list{
  display: flex;
  align-items: center;
}

.nav-list .li-img{
  display: flex;

 margin-left: 40px;
 font-weight: bold;
}
.li-img a{
  display: flex;
  gap: 4px;
  align-items: center;
  font-size: 15px;
}
.li-img .btn-contatos{
  width: 90px;
  padding: 15px;
  border-radius:50px;
  outline: none;
  border: none;
 font-weight: bold;
 color: #fff;
 background-color: #5eb9f0;
 transition: 1.3s;
 box-shadow: rgba(94, 185, 240) 0px 30px 60px -12px, rgba(10, 149, 235, 0.082) 0px 18px 36px -18px;
 }
 .li-img .btn-contatos:hover{
  transform: scale(1.1);
 }

/* inicio do estio da main */

section{
  display: flex;
  margin-top: 120px;
  align-items: center;
}

article h2{
  font-size: 54px;
  margin-left: 110px;
  width:500px;
margin: 150px 0 30px 110px; 
}
h2 mark{
  background-color: #fff;
  color: #5eb9f0;
}
article p{
  text-align: center;
  font-size: 22px;
  color:rgb(96,105,123);
margin: 0 10%;
}
 article .btn-iniciar{
  margin: 20px 23% 0 ;
  width: 100px;
  padding: 10px;
  border-radius:50px;
  outline: none;
  border: none;
 font-weight: bold;
 color: #fff;
 cursor: pointer;
 background-color: rgb(94, 185, 240);
 transition: 1.3s;
 box-shadow: rgba(94, 185, 240) 0px 30px 60px -12px, rgb(10, 148, 235) 0px 18px 36px -18px;
 }
 article .btn-iniciar:hover{
  transform: scale(1.1);
 }

section img{
  width: 100%;
}
span{
  display: flex;
  justify-content: center;
  margin: 90px 0 0 0;
}
.conteiner-img .ul-img{
display: flex;
justify-content: space-around;

width: 100%;
}

  .logo-marcas{
  width:130px;
  
}



