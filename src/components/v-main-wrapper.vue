<template>

<div class="v-main-wrapper">
   <div class = "navigation">
       <ul>
				<div class="navigation_articles"><li>Статьи</li></div>
				<div class="news"><li>Новости</li></div>
				<div class="biography"><li>Биографии</li></div>
				<div class="documents"><li>Документы</li></div>
				<div class="authors"><li>Авторы</li></div>
		</ul>
        </div>
      
 <div class="articles"><p>Статьи</p></div>
 <div class="container">
<img :src="require('../assets/images/wrapper.png')" alt="img">
  <div class="container_text_1">Ленинский накал: как деревня Кашино стала родиной «лампочки <br> Ильича»</div>
  <div class="container_text_2">Егор Зарианов   7 дек. 2020 • читать 20 мин   </div>
  <div class="container_common_bookmark">
        <div class="container_bookmark"><img :src="require('../assets/images/bookmark_1.png')" alt="img"  @click="showMessageInConsole"></div>
        <div class="container_bookmark"><img :src="require('../assets/images/bookmark_2.png')" alt="img" @click="showMessageInConsole"></div>
        <div class="container_bookmark"><img :src="require('../assets/images/bookmark_3.png')" alt="img" @click="showMessageInConsole"></div>
         <div class="container_bookmark"><img :src="require('../assets/images/social.png')" alt="img" @click="showMessageInConsole"></div>
    </div>
</div>

<div class="inputt">
    <div class="input_img">
<input value = "Все статьи">
<img :src="require('../assets/images/vector.png')" alt="img">
</div>

<div class="input_search">
<img :src="require('../assets/images/vector_1.png')" alt="img">
<input type = "search" value = "Поиск по содержимому">
</div>
</div>



<div class="container_1">
<img :src="require('../assets/images/rectangle_30.png')" alt="img">
<div class="container_1_text_1">Спецпроект</div>
<div class="container_1_text_2">История России по векам</div>
<div class="container_1_text_3">Много изучено документов, много найдено<br> вещественных доказательств… И то, что известно <br> об истории России, легло в основу таблицы,<br> которую мы предлагаем вашему вниманию.</div>
</div>





<div class="card">
    <div class="card_img">
        <img :src="require('../assets/images/img.jpg')" alt="img">
    </div>
    <div class="card_text">
<div class="card_text_p1"><p> О политике нацистов в отношении мирного населения СССР. Выступление <br> Владимира Мединского на форуме «Уроки Нюрнберга» <br>
Часть 3.</p></div>

<div class="card_text_p2"><p>Егор Зарианов  7 дек. 2020 • читать 20 минут </p></div>
<img :src="require('../assets/images/line_35.png')" alt="img">
<div class ="card_text_p3">
<p>Дом правительства, или Дом на набережной, был построен в 1931 году для советской номенклатуры. Как <br> протекала жизнь в квартирах, чем занимались их обитатели и что делали дети, пока их отцы строили <br>коммунизм? В издательстве Corpus вышло монументальное исследование историка Юрия Слёзкина «Дом<br> правительства. Сага о русской революции»</p>
</div>
<div class="ttt">
    <div class="card_text_read"><img :src="require('../assets/images/read.png')" alt="img"> </div>
    <div class="card_text_common_bookmark">
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_1.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_2.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_3.png')" alt="img"></div>
         <div class="card_text_bookmark"><img :src="require('../assets/images/social.png')" alt="img"></div>
    </div>

</div>


</div>

    

</div>

<div class="card">
    <div class="card_img">
        <img :src="require('../assets/images/img_1.jpg')" alt="img">
    </div>
    <div class="card_text">
<div class="card_text_p1"><p> Кромешные реформы: пять фактов из истории опричнины.</p></div>

<div class="card_text_p2"><p>Егор Зарианов  7 дек. 2020 • читать 20 минут </p></div>
<img :src="require('../assets/images/line_35.png')" alt="img">
<div class ="card_text_p3">
<p>Полувековое правление Ивана IV Грозного, ставшего первым русским царем, сопряжено со множеством<br> событий и явлений, до сих пор вызывающих яростные споры и неоднозначные оценки. Начать можно с самой <br> личности Ивана Грозного, которого одни называют полусумасшедшим, а другие — одним из самых <br> просвещенных и гибких умом людей XVI столетия. </p>
</div>
<div class="ttt">
    <div class="card_text_read"><img :src="require('../assets/images/read.png')" alt="img"> </div>
    <div class="card_text_common_bookmark">
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_1.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_2.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_3.png')" alt="img"></div>
         <div class="card_text_bookmark"><img :src="require('../assets/images/social.png')" alt="img"></div>
    </div>

</div>


</div>

    

</div>

<div class="card">
    <div class="card_img">
        <img :src="require('../assets/images/img.jpg')" alt="img">
    </div>
    <div class="card_text">
<div class="card_text_p1"><p> О политике нацистов в отношении мирного населения СССР. Выступление <br> Владимира Мединского на форуме «Уроки Нюрнберга» <br>
Часть 3.</p></div>

<div class="card_text_p2"><p>Егор Зарианов  7 дек. 2020 • читать 20 минут </p></div>
<img :src="require('../assets/images/line_35.png')" alt="img">
<div class ="card_text_p3">
<p>Дом правительства, или Дом на набережной, был построен в 1931 году для советской номенклатуры. Как <br> протекала жизнь в квартирах, чем занимались их обитатели и что делали дети, пока их отцы строили <br>коммунизм? В издательстве Corpus вышло монументальное исследование историка Юрия Слёзкина «Дом<br> правительства. Сага о русской революции»</p>
</div>
<div class="ttt">
    <div class="card_text_read"><img :src="require('../assets/images/read.png')" alt="img"> </div>
    <div class="card_text_common_bookmark">
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_1.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_2.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_3.png')" alt="img"></div>
         <div class="card_text_bookmark"><img :src="require('../assets/images/social.png')" alt="img"></div>
    </div>

</div>


</div>

    

</div>

<div class="card">
    <div class="card_img">
        <img :src="require('../assets/images/img_1.jpg')" alt="img">
    </div>
    <div class="card_text">
<div class="card_text_p1"><p> Кромешные реформы: пять фактов из истории опричнины.</p></div>

<div class="card_text_p2"><p>Егор Зарианов  7 дек. 2020 • читать 20 минут </p></div>
<img :src="require('../assets/images/line_35.png')" alt="img">
<div class ="card_text_p3">
<p>Полувековое правление Ивана IV Грозного, ставшего первым русским царем, сопряжено со множеством<br> событий и явлений, до сих пор вызывающих яростные споры и неоднозначные оценки. Начать можно с самой <br> личности Ивана Грозного, которого одни называют полусумасшедшим, а другие — одним из самых <br> просвещенных и гибких умом людей XVI столетия. </p>
</div>
<div class="ttt">
    <div class="card_text_read"><img :src="require('../assets/images/read.png')" alt="img"> </div>
    <div class="card_text_common_bookmark">
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_1.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_2.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_3.png')" alt="img"></div>
         <div class="card_text_bookmark"><img :src="require('../assets/images/social.png')" alt="img"></div>
    </div>

</div>


</div>

    

</div>

<div class="card">
    <div class="card_img">
        <img :src="require('../assets/images/img.jpg')" alt="img">
    </div>
    <div class="card_text">
<div class="card_text_p1"><p> О политике нацистов в отношении мирного населения СССР. Выступление <br> Владимира Мединского на форуме «Уроки Нюрнберга» <br>
Часть 3.</p></div>

<div class="card_text_p2"><p>Егор Зарианов  7 дек. 2020 • читать 20 минут </p></div>
<img :src="require('../assets/images/line_35.png')" alt="img">
<div class ="card_text_p3">
<p>Дом правительства, или Дом на набережной, был построен в 1931 году для советской номенклатуры. Как <br> протекала жизнь в квартирах, чем занимались их обитатели и что делали дети, пока их отцы строили <br>коммунизм? В издательстве Corpus вышло монументальное исследование историка Юрия Слёзкина «Дом<br> правительства. Сага о русской революции»</p>
</div>
<div class="ttt">
    <div class="card_text_read"><img :src="require('../assets/images/read.png')" alt="img"> </div>
    <div class="card_text_common_bookmark">
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_1.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_2.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_3.png')" alt="img"></div>
         <div class="card_text_bookmark"><img :src="require('../assets/images/social.png')" alt="img"></div>
    </div>

</div>


</div>

    

</div>

<div class="card">
    <div class="card_img">
        <img :src="require('../assets/images/img_1.jpg')" alt="img">
    </div>
    <div class="card_text">
<div class="card_text_p1"><p> Кромешные реформы: пять фактов из истории опричнины.</p></div>

<div class="card_text_p2"><p>Егор Зарианов  7 дек. 2020 • читать 20 минут </p></div>
<img :src="require('../assets/images/line_35.png')" alt="img">
<div class ="card_text_p3">
<p>Полувековое правление Ивана IV Грозного, ставшего первым русским царем, сопряжено со множеством<br> событий и явлений, до сих пор вызывающих яростные споры и неоднозначные оценки. Начать можно с самой <br> личности Ивана Грозного, которого одни называют полусумасшедшим, а другие — одним из самых <br> просвещенных и гибких умом людей XVI столетия. </p>
</div>
<div class="ttt">
    <div class="card_text_read"><img :src="require('../assets/images/read.png')" alt="img"> </div>
    <div class="card_text_common_bookmark">
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_1.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_2.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_3.png')" alt="img"></div>
         <div class="card_text_bookmark"><img :src="require('../assets/images/social.png')" alt="img"></div>
    </div>

</div>


</div>

    

</div>

<div class="card">
    <div class="card_img">
        <img :src="require('../assets/images/img.jpg')" alt="img">
    </div>
    <div class="card_text">
<div class="card_text_p1"><p> О политике нацистов в отношении мирного населения СССР. Выступление <br> Владимира Мединского на форуме «Уроки Нюрнберга» <br>
Часть 3.</p></div>

<div class="card_text_p2"><p>Егор Зарианов  7 дек. 2020 • читать 20 минут </p></div>
<img :src="require('../assets/images/line_35.png')" alt="img">
<div class ="card_text_p3">
<p>Дом правительства, или Дом на набережной, был построен в 1931 году для советской номенклатуры. Как <br> протекала жизнь в квартирах, чем занимались их обитатели и что делали дети, пока их отцы строили <br>коммунизм? В издательстве Corpus вышло монументальное исследование историка Юрия Слёзкина «Дом<br> правительства. Сага о русской революции»</p>
</div>
<div class="ttt">
    <div class="card_text_read"><img :src="require('../assets/images/read.png')" alt="img"> </div>
    <div class="card_text_common_bookmark">
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_1.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_2.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_3.png')" alt="img"></div>
         <div class="card_text_bookmark"><img :src="require('../assets/images/social.png')" alt="img"></div>
    </div>

</div>


</div>

    

</div>

<div class="card">
    <div class="card_img">
        <img :src="require('../assets/images/img_1.jpg')" alt="img">
    </div>
    <div class="card_text">
<div class="card_text_p1"><p> Кромешные реформы: пять фактов из истории опричнины.</p></div>

<div class="card_text_p2"><p>Егор Зарианов  7 дек. 2020 • читать 20 минут </p></div>
<img :src="require('../assets/images/line_35.png')" alt="img">
<div class ="card_text_p3">
<p>Полувековое правление Ивана IV Грозного, ставшего первым русским царем, сопряжено со множеством<br> событий и явлений, до сих пор вызывающих яростные споры и неоднозначные оценки. Начать можно с самой <br> личности Ивана Грозного, которого одни называют полусумасшедшим, а другие — одним из самых <br> просвещенных и гибких умом людей XVI столетия. </p>
</div>
<div class="ttt">
    <div class="card_text_read"><img :src="require('../assets/images/read.png')" alt="img"> </div>
    <div class="card_text_common_bookmark">
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_1.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_2.png')" alt="img"></div>
        <div class="card_text_bookmark"><img :src="require('../assets/images/bookmark_3.png')" alt="img"></div>
         <div class="card_text_bookmark"><img :src="require('../assets/images/social.png')" alt="img"></div>
    </div>

</div>


</div>

    

</div>


<div class="select">
<select>
    <option>XX век</option>
    <option>IX век</option>
    <option>XVIII век</option>
</select>
</div>
<div class = "numbers_page">
       <ul>
				<li class="back_forward">назад</li>
				<li class="numbers_page_one">1</li>
				<li>2</li>
				<li>3</li>
				<li>4</li>
                <li>5</li>
                <li>6</li>
                <li class="back_forward">вперед</li>
		</ul>
        </div>

<div class="download"><p>Загрузить еще</p></div>


 

</div>
</template>




<script>



export default {
    name: 'v-main-wrapper',
    components: {},
  
    props: {},
    data() {
        return {
         
        }
    },
    computed: {},
    methods: {
        showMessageInConsole() {
            console.log('ссылка работает')
        }
    }
}
</script>




<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap');
.v-main-wrapper {
    width: 1920px;
    margin-left: 200px;
    margin-right: 200px;
    
}

.navigation {
    display: flex;
    justify-content: space-around;
   font-family: roboto;
   text-transform: uppercase;
   font-size: 12px;
   line-height: 24px;

    
   
   
}
.navigation ul {
    display: flex;
    list-style: none;
    border: 1px solid #D3DADF;
   margin-top: 176px;
     margin-left: 592px;
     margin-right: 592px;
     background:#D3DADF;
    height: 64px;
   

}
.navigation ul li {
    margin: 0px 48px;
    margin-top: 24px;
   
}
.navigation_articles {
   border-left: 1px solid  #D3DADF;
    color: #37424A;
   font-weight: 900;
    
   
}
.news {

     background: #FFFFFF;
 
}
.biography {
    
     background: #FFFFFF;
   
}
.documents {
    
     background: #FFFFFF;
    
}

.authors {
    border-left: 1px solid  #D3DADF;
    background: #FFFFFF;
    
    
  
}
.articles p{
    margin-left: 208px;
   width: 126px;
   font-family: Clarendon CN BT;
   font-size: 48px;
   font-weight: bold;

}
.container {
  width: 100%;
  position: relative;
  //font-size: 20px;
}

.container_text_1 {
  position: absolute;
  top: 60%;
  left: 13%;
  color: #FFFFFF;
  text-align: left;
  font-family: Clarendon CN BT;
  font-size: 40px;
  line-height: 48px;
}

.container_text_2{
  position: absolute;
  top: 85%;
  left: 13%;
  color: #FFFFFF;
  text-align: left;
}
.container_common_bookmark {
    display: flex;
    justify-content: space-between;
    position: absolute;
    top: 85%;
    left: 70%;
}
.container_bookmark {
    margin-right: 10px;
}
.container_1 {
  width: 352px;
  height: 352px;
  position: relative;
  text-align: left;
  color:#FFFFFF;
 
  position: absolute;
  top: 1065px;
  left: 1570px;
}
.container_1_text_1 {
  position: absolute;
  top: 30px;
  left: 24px;
  text-align: left;
  font-family: roboto;
  font-size: 12px;
  line-height: 16px;
  text-transform: uppercase;
  font-weight: 900;
}
.container_1_text_2 {
  position: absolute;
  top: 60px;
  left: 24px;
  text-align: left;
  font-family: Clarendon CN BT;
  font-size: 35px;
  font-weight: 700;
  

}
.container_1_text_3 {
  position: absolute;
  top: 170px;
  left: 24px;
  text-align: left;
  font-size: 12px;
}
.input_img {
    border: 1px solid #D3DADF;
    width: 480px;
    height: 64px;
    font-size: 14px;
    font-weight: 400;
    line-height: 24px;
    color: #37424A;
    font-family: roboto;
}
.input_img input{ 
border: none;
outline: none; 
-webkit-appearance: none; 
vertical-align: middle; 
margin-right: 250px;
margin-top: 24px;
}
.input_img img{ 
margin-top: 20px;
}

.input_search {
    border: 1px solid #D3DADF;
    width: 608px;
    height: 64px;
    font-family: roboto;
  
    
}
.input_search input{
width: 200px;
border: none;
outline: none; 
-webkit-appearance: none; 
vertical-align: middle; 
color: #A8B5BE;
font-size: 16px;
margin-right: 250px;
}
.input_search img {
    margin-right: 30px;
    margin-top: 20px;
}

.inputt {
    display: flex;
    justify-content: space-between;
    width: 1120px;
    margin-left: 208px;
    margin-top: 68px;
}
.card_text_bookmark {
    margin-right: 10px;
}


.card {
    border: 1px solid #D3DADF;
    display: flex;
    margin-top: 40px;
    width: 1120px;
    height: 352px;
    margin-left: 208px;
}
.card p {
    text-align: left;
   
}
.card_text_p1 {
font-family: clarendon cn bt;
font-size: 24px;
line-height: 32px;
font-weight: bold;
}
.card_text_p1 p {
    margin: 20px 0;
}
.card_text_p2 {
font-family: roboto;
font-size: 14px;
line-height: 24px;
}
.card_text_p3 {
font-family: roboto;
font-size: 14px;
line-height: 24px;
}
.card img {
    margin: 10px 10px;
}
.ttt {
    display: flex;
    justify-content: space-between;
}

.card_text_common_bookmark {
    display: flex;
    justify-content: space-between;
   
}
.card_text_bookmark {
    margin-right: 10px;
}
.select {
    position: absolute;
    top: 1500px;
    left: 1570px;
    
}
.select select {
    width: 350px;
    height: 40px;
    
}
.numbers_page {
    display: flex;
    justify-content: space-around;
   font-family: roboto;
   font-weight: 900;
   text-transform: uppercase;
   font-size: 16px;
   line-height: 24px;
   width: 1120px;
  
   margin-left: 208px; 
}
.numbers_page ul {
    display: flex;
    list-style: none;
    border: 1px solid  #D3DADF;
    width: 100%;
    height: 72px;
   
   
   

}
.numbers_page ul li {
   

border-right: 1px solid #D3DADF;
width: 100%;
height: 49px;
padding-top: 24px;

  
}
.back_forward {
    width: 100px;
    
} 
.numbers_page_one {
    background: #D3DADF;
}
.download {
    border: 1px solid #D3DADF;
    width: 1120px;
    height: 72px;
    margin-left: 208px;
    font-family: roboto;
    font-size: 12px;
    line-height: 16px;
    color: #37424A;
    font-weight: 900;
}
.download p {
    margin-top: 25px;
}




</style>