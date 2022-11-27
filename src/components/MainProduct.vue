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
<div id="viewport">
  <!-- Sidebar -->
  <div id="sidebar">
      <p>Тип события</p>
    <ul class="nav side">
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
           ГАЗ
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
            ТЕПЛО   
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
               ВОДА
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
              ЭЛЕКТРИЧЕСТВО
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
           ОТОПЛЕНИЕ
        </a>
      </li>
      
     
     
    </ul>
    <p>Район</p>
    <ul class="nav side">
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
            <i></i>  Тирасполь
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
            <i></i> Бендеры 
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
            <i></i>     Слободзея
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
            <i></i>   Дубосары
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
          <i></i>  Григориополь
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
          <i></i> Рыбница
        </a>
      </li>
     
     
    </ul>
    <p>Дата события</p>
    <ul class="nav side">
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
            <i></i>  Неделя
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
            <i></i>Пол года  
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
            <i></i>   Текущий год 
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
            <i></i>  Прошлый год
        </a>
      </li>
      <li>
        <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
        <a href="#">
          <i></i> Период
        </a>
      </li>
      <li>
        <input class="input" type="date" id="defaultCheck1">
      </li>
      <button type="button"  class=" op btn btn-primary">Поиск</button>
    </ul>
    
  </div>
  <!-- Content -->
  <div id="content">
   
    <div class="container-fluid">
      <input type="text" placeholder="Введите запрос" class="inp">
      <button type="button"  class="btn btn-primary">Поиск</button>
    </div>
    <h3 >Предстоящие отключения по вашему городу адресам:</h3>
    <div class="card" style="width: 60rem; height: 15em;">
  <img src="../assets/car.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Отключение горячей воды</h5>
    <h6>4 августа с 8-00 до 17-00г. Тирасполь, ул. Юности, д. 56</h6>
    <p class="sse">В связи с ремонтными работами</p>
    <p class="sso">
      ГУП "Водоснабжение и водоотведение"
    </p>
  </div>
</div>
<div class="card" style="width: 60rem; height: 15em;">
  <img src="../assets/temp.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Отключение электричества</h5>
    <h6>4 августа с 8-00 до 17-00г. Тирасполь, ул. Юности, д. 56</h6>
    <p class="sse">В связи с ремонтными работами</p>
    <p class="sso">
      ГУП "ЕРЭС"
    </p>
  </div>
</div>
<div class="card" style="width: 60rem; height: 15em;">
  <img src="../assets/gaz.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Отключение газа</h5>
    <h6>4 августа с 8-00 до 17-00г. Тирасполь, ул. Юности, д. 56</h6>
    <p class="sse">В связи с ремонтными работами</p>
    <p class="sso">
      ООО «Тираспольтрансгаз-Приднестровье»
    </p>
  </div>
</div>
<div class="card" style="width: 60rem; height: 15em;">
  <img src="../assets/voter.png" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Отключение горячей воды</h5>
    <h6>4 августа с 8-00 до 17-00г. Тирасполь, ул. Юности, д. 56</h6>
    <p class="sse">В связи с ремонтными работами</p>
    <p class="sso">
      ГУП "Водоснабжение и водоотведение"
    </p>
  </div>
</div>
  </div>
  
</div>



<p class="text-center text-muted loks">©ГИС "ОПОВЕЩЕНИЕ", 2022</p>



        
</template>
<script>
export default{

}
</script>
<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.2/font/bootstrap-icons.css");
@media  (max-width: 425px){
  .card{
    width: 30em;
  }
}
.loks{
  border-top: 1px solid #44444473;
  margin-top: 5em;
}
.sso{
  padding-top: 3em;
  padding-left: 35em;
}
.sse{
  padding-left: 0;
}
h6{
 width: 250px;
}
.card-img-top{
  width: 50px;
  height: 50px;
}
.card{
  margin-top: 2em;
display: flex;
flex-direction: row;
margin-left: 2em;

background: #FFFFFF;
border-bottom: 2px solid #52E8B0;
box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.1), inset 1px 1px 1px rgba(0, 0, 0, 0.05);
border-radius: 10px;
}
.card:hover{
  box-shadow: 15px 15px 10px rgba(0, 0, 0, 0.1), inset 1px 1px 1px rgba(0, 0, 0, 0.05);
  transition: 0.5s ease-in;
}
.content{
  background-color: #F8F8F8;
}
.op{
  margin-top: 1em;
}
h3{
  padding-left: 1em;
  padding-top: 1em;
}
p{
    padding-left: 2em;
}
.btn{
    background: linear-gradient(180deg, #C7FFEA 2.08%, #52E8B0 100%);
box-shadow: 3px 3px 3px rgba(0, 0, 0, 0.1);
border-radius: 5px;

font-family: 'Inter';
font-style: normal;
font-weight: 300;
font-size: 14px;
line-height: 17px;
/* identical to box height */

text-align: center;

color: #000000;
width: 180px;
}
.navbar-right{
    padding-top: 0;
}
.inp{
    background: #FFFFFF;
border-bottom: 2px solid #52E8B0;
box-shadow: inset 2px 2px 2px rgba(0, 0, 0, 0.1);
border-radius: 10px;
width: 838px;
}
.img-thumbnail{
    border: none;
}
.nav{
    display: flex;
    justify-content: space-between;
}
.nav-link:hover{
  color: #31efecdd;
  transition: 0.6s ease-in;
}
.nav-link{
  text-decoration: none;
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

#content {
  width: 100%;
  position: relative;
  margin-right: 0;
}
.container-fluid{
    display: flex;
  gap: 2em;
}
/* Sidebar Styles */

#sidebar {
  z-index: 1000;
  position: fixed;
  left: 250px;
  width: 250px;
  height: 100%;
  margin-left: -250px;
  overflow-y: auto;
  background: inherit;
  -webkit-transition: all 0.5s ease;
  -moz-transition: all 0.5s ease;
  -o-transition: all 0.5s ease;
  transition: all 0.5s ease;
}

#sidebar header {

  font-size: 20px;
  line-height: 52px;
  text-align: center;
}

#sidebar header a {
  color: #fff;
  display: block;
  text-decoration: none;
}

#sidebar header a:hover {
  color: rgb(84, 82, 82);
}



#sidebar .nav a{
  background: none;

  color: #080808;
  font-size: 14px;
  padding: 16px 24px;
}

#sidebar .nav a:hover{
  background: none;
  color: #00ffd5;
}

#sidebar .nav a i{
  margin-right: 16px;
}
a{
    text-decoration: none;
}
.side{
    flex-direction: column;
    margin-left: 2em;
}
</style>