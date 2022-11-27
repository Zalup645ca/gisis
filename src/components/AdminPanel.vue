<template>
   <header>
  <nav class="nav">
    <ul class="nav">
  <li class="nav-item">
    <a class="nav-link active" aria-current="page" href="#"> <img class="img-thumbnail" src="../assets/Group35.png" alt=""></a>
  </li>
    </ul>
 <ul class="nav justify-content-end">
  <li class="nav-item">
    <a class="nav-link active"  href="#">Главная </a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Новости</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Все события</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#"><i class="bi bi-search"></i></a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#"><i class="bi bi-envelope"></i></a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#"><i class="bi bi-person-circle"></i></a>
  </li>
</ul>
</nav>
</header>
<div class="container">
    <div class="content">
        <div class="card" style="width: 80rem;">
  <img src="../assets/image2.png" class="card-img" alt="...">
  <div class="card-body">
    <h5 class="card-title">Петров Игорь Иванович</h5>
    <p class="card-text">15 июля 1956 г</p>
    <p class="card-text">+373-777-45-875</p>
    <h5>Оповещения</h5>
    <div class="com">
    <a href="#" class="ash">Получать СМС-оповещения</a>
    <a href="#"  class="btn btn-primary teleg" >Подключить Telegram-бот</a>
</div>

  </div>
</div>
    </div>
    <div class="content-duo-card">
    <h5 class="adres">Мои адреса</h5>
    <div class="card-duo">
        <div class="card ah" style="width: 35rem;">
  <div class="card-body sg">
   
    <p class="card-text">г. Бендеры
 ул. Суворова д.32, кв. 14</p>
    <a href="#" class="card-link"><i class="bi bi-pencil-square"></i></a>
  </div>
</div>
<div class="card ah" style="width: 35rem;">
  <div class="card-body sg">
   
    <p class="card-text">г. Бендеры
 ул. Суворова д.32, кв. 14</p>
    <a href="#" class="card-link"><i class="bi bi-pencil-square"></i></a>
  </div>
</div>
    </div>
</div>
</div>


<p class="text-center text-muted loks">©ГИС "ОПОВЕЩЕНИЕ", 2022</p>
</template>
<script>

</script>

<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.2/font/bootstrap-icons.css");

@media  (max-width:425px){
.card{
    display:contents;
    width: 15em;
    gap: none;
}
.card-img{
    width: 18em;
}
.com{
    gap: 1em;
}
.ah{
    width: 10em;
}
.sg{
    display: none;
}
.card-duo{
    display:contents ;
    gap: 2em;
}
}
.ah{
    background: #FFFFFF;
border-bottom: 2px solid #52E8B0;
box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.1), inset 1px 1px 1px 1px rgba(0, 0, 0, 0.05);
border-radius: 10px;
margin-left: 2em;
margin-top: 2em;
}
.sg{
    display: flex;
    gap: 22em;
}
.card{
    display: flex;
    align-items: center;
    flex-direction: row;
    gap: 5em;
    border: none;
}
.card-duo{
    display: flex;
    gap: 3em;
}
.adres{
    padding-top: 1em;
    padding-left: 1em;
}
.content-duo-card{
    background: #F8F8F8;
border-radius: 10px;
height: 359px;
margin-top: 1em;

}
.teleg{
    font-family: 'Inter';
font-style: normal;
font-weight: 300;
font-size: 14px;
line-height: 17px;
/* identical to box height */

text-align: center;

color: #000000;
background: linear-gradient(360deg, #C7FFEA -35.56%, #FCFCFC 143.33%);
box-shadow: 3px 3px 3px rgba(0, 0, 0, 0.1);
border-radius: 5px;
}
.com{
    display: flex;
    gap: 3em;
}
.ash{
 
 color: #444444;
}
.card-img{
    width: 15%;
    padding-left: 2em;
    margin-top: 0;
}
.nav{
    display: flex;
    justify-content: space-between;
}
.img-thumbnail{
    border: none;
}
li{
  color: #444444;
}
.nav-link {
  color: #444444;
}
body{
    background: #fff;
}
#viewport {
    margin-top: 2em;
  padding-left: 250px;
  -webkit-transition: all 0.5s ease;
  -moz-transition: all 0.5s ease;
  -o-transition: all 0.5s ease;
  transition: all 0.5s ease;
}
.nav-link:hover{
  color: #31efecdd;
  transition: 0.6s ease-in;
}
.nav-link{
  text-decoration: none;
}
</style>