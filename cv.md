<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8" />
<title> CV Титов Илья </title>
<style type="text/css">
    .font{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    color: black;
    text-decoration: none;
}
a{
    color: black;
    text-decoration: none;
}
a:hover{
    color: cornflowerblue;
    text-decoration: underline;
}
a:active{
    color: rgb(10, 0, 150);
    text-decoration: line-through;
}
.avatar{
 width: 200px;
 border-radius: 28px;
 box-shadow: 4px 4px 14px rgba(0, 0, 0, 0.25);

}
.info p{
    color: rgb(0, 0, 0);
}
.education{
    padding: 15px 5px 15px ;
    background: wheat;
    border: 5px whitesmoke;
    border-style: double;
    border-radius: 30px;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    color: #5a5d61;
}
.education h2{
    text-align: center;
    color: rgb(0, 0, 0);
}
.education li{
    margin-bottom: 20px;
}
.container{
    max-width: 800px;
    margin: auto;
    margin-bottom: 70px;
    margin-top: 70px;
    background-color: rgb(255, 255, 255);
    border-radius: 28px;
    border-style: double;
    border-color: rgb(255, 255, 255);
}
.languages li{
    margin-bottom: 20px;
    color: #5a5d61;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
 .table{ 
width: 100%;
}
.table td{
    padding: 5px;
}
.namings{
    color: black;
}
.intro{
    color: black;
}
.hobbies li{
    margin-bottom: 10px;
}
.contactme h2{
    text-align: center;
}
.contactme input{
    width: 100%;
    box-sizing: border-box;
    border: none;
    border-bottom: gray solid 1px;
    background: transparent;
    color: black;
    padding: 15px 0 10px;
    outline: none;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
.button{
    width: 100px;
    height: 40px;
    border: oldlace solid 2px;
    border-radius: 15px;
    background-color: oldlace;
    margin: auto;
}
</style>
</head>
<body>
    <div class="container">
    <div class="info">
<table cellspacing="15" > 
    <tr>
<td><img src='https://i.ibb.co/hY08Ppv/avatar2.jpg' width="200" alt="Мое фото" class="avatar"></td>
<td>
    <h1>Титов Илья</h1>
<p class="intro">Я родился в <time datetime="4:20 24.02.2001">24 февраля 2001 года в городе Тамбов</p>
<p class="intro"> IT-enthusiast,JavaScript developer,  <strong> Front-end </strong></p>
</td>
</tr>
    </table>
    <nav>
    <a href=https://www.instagram.com/ilyatitov_v/?igshid=1nq1k88ykxp9 target=_blank>Instagram</a>
    | 
    <a href=https://vk.com/itwoshenka target=_blank>Vkontakte</a>
    | 
    <a href=https://t.me/itwoshenka target=_blank>Telegram</a>
    |
    <p>Discord nickname:itwoshenka#5655</p>
    </nav>
</div>
<hr color="black" size="3" >
<div class="education">
<h2 class="educationname">Образование</h2>
<table border='1' class="table">
    <tr class="namings">
        <th>Университет</th>
        <th>Период обучения</th>
        <th>Степень</th>
        <th>Специализация</th>
    </tr>
    <tr>
    <td>МГЛУ</td>
    <td>2017-2022</td>
    <td>Бакалавриат</td>
    <td>Перевод и переводоведение</td>
</tr>
<tr>
    <td>RSchool</td>
    <td>Декабрь 2021-Настоящее время</td>
    <td>Курсы для разработчиков</td>
    <td>JS/Front-end</td>
</tr>
</table>
</div>
<hr color="black" size="1" width="300">
<div class="education">
    <h2>Мои навыки</h2>
<ul class="skills">
    <li>JavaScript</li>
    <li>Git</li>
    <li>CSS3</li>
    <li>HTML5</li>
    <li>Node.js</li>
    <li>React</li>
</ul>
</div>
<hr color="black" size="1" width="300">
<div class="education">
    <h2>Мои хобби</h2>
    <ul class="hobbies">
        <li>Спорт</li>
        <li>Видеоигры</li>
        <li>Моделинг</li>
        <li>Кулинария</li>
        <li>Программирование</li>
        <li><a href="https://t.me/boobaligna" target=_blank>Также я админ телеграм канала с мемами </a></li>
    </ul>
    </div>
    <hr color="black" size="1" width="300">
    <div class="education">
<h2>Мой опыт работы</h2>
<ul class="experience">
<h3><li>Тут будет список своих проектов которые я делал для себя</li></h3>
<li><a href="">Тут будут мои проекты</a></li>
</ul>
</div>
<hr color="black" size="1" width="300">
<div class="education">
<h2>Языки</h2>
<ul class="languages">
    <li>Английский,C1</li>
    <li>Испанский,B1</li>
</ul>
</div>
<hr color="black" size="1" width="300">
<div class="contactme">
<h2>Написать мне</h2>
<form>
    <label for='name'>Ваше имя</label>
    <input type='text' id='name' placeholder="Введите ваше имя...">
    <br>
    <label for='email'>Ваш email</label>
    <input type="text" id='email' placeholder='Введите ваш email...'>
    <br>
    <label for='message'>Ваше сообщение</label>
    <input type="text" id='message' placeholder='Введите ваше сообщение...'>
</div>
    <br>
    <input type="submit" value="Отправить!" class="button">
</form>
</div>
</body>
</html>