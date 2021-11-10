<!DOCTYPE html>
    <head>
        <title>高士傑的期中個人網站切</title>
        
            <link rel="stylesheet" href="styleindex.css", />
            

           <style type="text/css">
              @import url('https://fonts.googleapis.com/css2?family=Mochiy+Pop+P+One&display=swap');
              @import url('https://fonts.googleapis.com/css2?family=Karla:wght@300&family=Mochiy+Pop+P+One&display=swap');
              @import url('https://fonts.googleapis.com/css2?family=Karla:wght@300&family=Mochiy+Pop+P+One&family=Uchen&display=swap');
                *{
                    margin: 0;
                    padding: 0;
                    list-style: none;

                }
                html,body{
                    height: 100%;
                }
                body{
                    display: flex;
                    flex-direction: column;
                    align-items: center;

                }

                .bodyBlock{
                    width: 100%;
                    height: 600px;
                    background-color: #ccc;
                    
                    background: 
                    linear-gradient(120deg, #ff1 50%,transparent 50%)center center / 100% 100%,
                    url("https://picsum.photos/1200/600?random=1")right center / auto 100%; 
                    font-family: 'Mochiy Pop P One', sans-serif;
                    
                }
                .contatier{
                    height: 100%; 
                    width: 100%;
                    margin: auto;
                    max-width: 1540px;
                }
                .body-text {
                    height: 100%;
                    display: flex;
                    flex-direction: column;
                    justify-content: center;
                    align-items: flex-start;
                }
                .body-text h1{
                    font-size: 80px;
                    font-weight: 200;
                    padding-bottom: 0.3em;
                    margin-bottom: 0.3em;
                }
                .body-text h1 small{
                    display: block;
                    font-size: 53px;
                    border-bottom: 1px solid #333;
                    font-weight: 100;
                }
                .body-text h2{
                    font-size: 50px;
                    font-weight: 150;
                }
                .body-text p{
                    font-size: 20px;
                    font-weight: 200;
                }
/*  */
                .img-textphoto{
                   width: 100%;
                   display: flex;
                   font-family: 'Karla', sans-serif;
                }
                .img-textphoto .item{
                   width: 25%;
                   position: relative;
                   text-align:center;
                }
                .img-textphoto .item img{
                   width: 100%;
                   vertical-align: middle;
                   display: flex;
                   justify-content: space-around;
                   
                }
                .img-textphoto .item .txt{
                    position: absolute;
                    top: 0;
                    right: 0;
                    left: 0;
                    bottom: 0;
                    padding: 20px;
                    background-color:  rgba(0,0,0,.6);
                    display: flex;
                    justify-content: center;
                    flex-direction: column;
                    opacity: 0;
                    transition: opacity .5s;
                    
                }
                .img-textphoto .item:hover .txt{
                    opacity: 1;
                }
                .img-textphoto .item h2{
                    font-size: 40px;
                    color: #ff0;
                    font-weight: 500;
                    
                }
                .img-textphoto .item h2:after{
                    content:'';
                    display: block;
                    width: 0%;
                    height: 2px;
                    margin: 10px;
                    background-color: #ff0;
                    transition: width .5s .3s;
                }
                .img-textphoto .item:hover h2:after{
                    width: 100%;
                }
                .img-textphoto .item p{
                    font-size: 18px;
                    color: #fff;
                    font-weight: 100;
                }
 /*  */
                .textcard{
                    width: 1200px;
                    font-family: 'Uchen', serif;
                    display: flex;

                }
                .textcard .item{
                    width: 368px;
                    margin: 15px;
                    text-align: center;
                    background-color: #fff;
                    border: 1px solid #ccc;
                    transform: translateY(0px);
                    transition: .5s;
                    display: flex;
                    flex-direction: column;

                }
                .textcard .item img{
                    width: 100%;
                    display: flex;
                    flex-direction: row;
                    vertical-align: middle;
                    justify-content: space-around;
                }
                .textcard .item h2{
                    border-bottom: 1px solid #888;
                    padding-bottom: .3em;
                    margin-bottom: .4em;
                    font-weight: 900;
                    transition: .25s;
                }
                .textcard .item p{
                    line-height: 1.6;
                    font-weight: 400;
                    transition: .25s;
                }
                .textcard .item .txt{
                    padding: 20px;
                    position: relative;
                }
                .textcard .item .txt:before{
                    content: '';
                    position: absolute;
                    width: 0;
                    height: 0;
                    top: 0;
                    left: 0;
                    border-top:50px solid transparent;
                    border-left:184px solid #fff;
                    border-right:184px solid #fff;
                    transform: translateY(-100% );
                }
                .textcard .item:hover{
                    transform: translateY(-50px);
                    
                }
                .textcard .item:hover .txt{
                    background-image:linear-gradient(0deg,#F08076,#feb85d);
                }
                .textcard .item:hover .txt:before
                {
                    border-left:184px solid #feb85d;
                    border-right:184px solid #feb85d;
                }
                .textcard .item:hover h2{
                    color: white;
                    border-bottom-color: white;
                }
                .textcard .item:hover p{
                    color: white;
                }
                
            </style>
    </head>
<!--  -->
<body>
    <div class="bodyBlock"> 
        <div class="contatier">
            <div class="body-text">
                <h1>
                    資工四甲 資訊工程系 
                    <small>
                        1107405020 高士傑
                    </small>
                </h1>
                <h2>
                    區塊
                </h2>
                <p>
                    文字內容填入處
                <br>
                </p>
                

            </div>
        </div>
    </div>

<!--  -->
<div class="textcard">

    <div class="item">
        <img src="https://www.npu.edu.tw/df_ufiles/034/s_r0345895(1).jpg"/>

        <div class="txt">
            
            <h2>教學大樓</h2>
            <p>少到可憐的學生餐廳，為了吃飯排進又小又窄的小七，上著美好的通識課程以及大一英文課程又或是必修零學分英文補救課，在這坐著硬到靠北的連體式桌椅，每周在這度過漫長的兩個小時，浪費你我的青春換來畢業的學分。</p>
        </div>
    </div>
    <div class="item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQomE7QPL_scfcNnHfXKmkg7iwTnFJ0HMMl0g&usqp=CAU"/>

        <div class="txt">
            <h2>測試區域1測試區域1測試區域1測試區域1測試區域1測試區域1</h2>
            <p>測試區域2測試區域2</p>
        </div>
    </div>
    <div class="item">
        <img src="https://www.npu.edu.tw/df_ufiles/034/s_R0345943.jpg"/>
        <div class="txt">
            <h2>測試區域1測試區域1測試區域1測試區域1測試區域1測試區域1</h2>
            <p>測試區域2測試區域2</p>
        </div>
    </div>
</div>

<!--  -->
<div class="img-textphoto">
    <div class="item">
        <img src="https://picsum.photos/500/400?random=20">

        <div class="txt">
            <h2>測試區域1測試區域1</h2>
            <p>測試區域2測試區域2</p>
        </div>
    </div>
    <div class="item">
        <img src="https://picsum.photos/500/400?random=21">

        <div class="txt">
            <h2>測試區域11測試區域11</h2>
            <p>測試區域22測試區域22</p>
        </div>
    </div>
    <div class="item">
        <img src="https://picsum.photos/500/400?random=22">

        <div class="txt">
            <h2>測試區域111測試區域111</h2>
            <p>測試區域222測試區域222</p>
        </div>
    </div>
    <div class="item">
        <img src="https://picsum.photos/500/400?random=23">

        <div class="txt">
            <h2>測試區域1111測試區域1111</h2>
            <p>測試區域2222測試區域2222</p>
        </div>
    </div>
</div>







</body>
</html>
