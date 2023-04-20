<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        @font-face {
     font-family: 'S-CoreDream-3Light';
     src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_six@1.2/S-CoreDream-3Light.woff') format('woff');}

        *{padding:0;
        margin: 0;
        text-align: center;
        font-family: 'S-CoreDream-3Light';}

        .section1{background-color: rgb(69, 69, 69);
        padding: 100px;}
        .section1 .container{display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 30px;
        /* border: 1px solid red; */
        }
        .section1 h1{color: steelblue;
        padding-top: 50px;
        font-size: 70px;}
        .section1 h3{color: white;
        padding: 20px;
        font-size: 14px;}
        .section1 .item{
        background-color: white;
        border: 5px double steelblue;
        padding: 30px 20px;
        line-height: 30px;}
        .section1 .a1{font-size: 26px;
        padding-bottom: 20px;
        color: gray;
        text-decoration: underline;}
        .section1 .a2{}
        .section1 .btn{background-color: tomato;
        width: 70px;
        padding: 5px;
        margin: 20px auto 0;}


        .section2{background-color: black;
        color: white;
        padding: 100px;
        }
        .section2 h1{font-size: 70px;
        padding-top: 50px;
        font-weight: 900;}
        .section2 h3{font-size: 14px;
        padding: 20px;}
        .section2 .container{
            /* border: 2px solid red; */
        display: flex;
        gap: 30px;}
        .section2 .item{
        width: 33.3%;    
        border: 2px solid white;
        padding: 30px;}
        .section2 .a1{font-size: 30px;
        padding:10px;
        margin-bottom: 20px;
        color: steelblue;}
        .section2 .btn{background-color: gray;
        width: 70px;
        padding: 5px;
        margin: 20px auto;}

    </style>
</head>
<body>
    <div class="section1">
        <h1>about 유민</h1>
        <h3>우리 금쪽이 유민이는요..</h3>
        <div class="container">
            <div class="item">
                <div class="a1">유민이의 이상형</div>
                <div class="a2">고인우(네이버 웹툰 '인과관계')<br>
                서강준(서프라이즈 소속 배우)</div>
                <div class="btn">+add</div>
            </div>
            <div class="item">
                <div class="a1">유민이의 음식 취향</div>
                <div class="a2">막창(기름지고 술땡겨서)<br>
                새로(나한테 청하 소개시켜주고 새로로 갈탐)</div>
                <div class="btn">+add</div>
            </div>
            <div class="item">
                <div class="a1">유민이의 노래 취향</div>
                <div class="a2">지바노프 'we, 진심'<br>
                아이오보이 '너의 인스타그램, EX'
                </div>
                <div class="btn">+add</div>
            </div>
            <div class="item">
                <div class="a1">유민이의 경력</div>
                <div class="a2">성당유치원 방과후 교사2년<br>
                충대 포차 알바 섭외 1순위 마당발
                </div>
                <div class="btn">+add</div>
            </div>
        </div>
    </div>
<!-- 여기서부터 섹션2 -->
     <div class="section2">
        <h1>with 유민</h1>
        <h3>어쩌다 유민은 나와 친해진 걸까?</h3>
        <div class="container">
            <div class="item">
                <div class="a1"><em>어디서!</em></div>
                <div class="a2">경인여자대학교 유교육과 16학번 A반에서 만났다.</div>
                <div class="btn">+add</div>
            </div>
            <div class="item">
                <div class="a1"><em>어쩌다!</em></div>
                <div class="a2">경성주막 알탕에 자몽에 이슬 마시면서</div>
                <div class="btn">+add</div>
            </div>
            <div class="item">
                <div class="a1"><em>언제부터!</em></div>
                <div class="a2">나 21살 유민 20살때부터 친해짐
                </div>
                <div class="btn">+add</div>
            </div>
        </div>
    </div>
</body>
</html>
