<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Document</title>
</head>
<style>
    *{
        margin: 0;
        padding: 0;
    }

    body{
        background: linear-gradient(to right, red, rgb(79, 79, 226));
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .card{
        width: 300px;
        height: 450px;
        background:  linear-gradient(to top, #3c6e69, #39cf5c);
        border-radius: 10px; 
        text-align: center;
        overflow: hidden;
        font-weight: bold;
        font-family: Arial, Helvetica, sans-serif;
        color: black;
        margin: 0 30px;
    }

    .card_img img{
        width: 160px;
        height: 160px;
        border: 2px solid green ;
        border-radius: 50%;
        transform: translateY(25px);
        transition: 0.5s;
    }

    .card_img img:hover {
        width: 100%;
        height: 100%;
        border-radius: unset;
        border: none;
        transform: unset;
       
    }   

    .card_button button{
        border: none;
        background: black;
        padding: 10px 10px;
        border-radius: 50px;
        width: 140px;
        height: 50px;
        transition: 0.2s;
        color: white;
        text-transform: uppercase;
        font-size: 15px;
    }

    .card_button button:hover{
        background: linear-gradient(to right, #e7461e,#374272);
        color: black;
        font-weight: bold;
        font-family: Arial, Helvetica, sans-serif;
        text-transform: uppercase;
    }

    .card_tittle{
        margin-top: 50px;
    }

    .card_item .i2 i, .i3 i, .i4 i{
        margin-top: 20px;
        margin-left: 35px;
        font-size: 30px; 
    }

    .card_item{
       display: flex;
    }

    .card_item .i1 i{
        margin-top: 20px;
        margin-left: 40px;
        font-size: 30px;
    }
    .card_button{
        margin-top: 30px;
    }
</style>
<body>
    <!-- card1 -->
    <div class="card">
        <div class="card_img">
            <img src="https://manta.edu.vn/wp-content/uploads/2022/12/hinh-anh-nu-sinh-dep-nhat-3-1.jpg" alt="">
        </div>
        <div class="card_tittle">
            <h2>ANH TÚ</h2>
            <span>Front end developer</span>
        </div>
        <div class="card_item">
            <div class="i1">
                <i class="fa-brands fa-facebook"></i>
            </div>
            <div class="i2">
                <i class="fa-brands fa-youtube"></i>
            </div>
            <div class="i3">
                <i class="fa-brands fa-tiktok"></i>
            </div>
            <div class="i4">
                 <i class="fa-brands fa-github"></i>
            </div>
        </div>
        <div class="card_button">
            <button>contact me</button>
        </div>
    </div>
    <!-- card2 -->
    <div class="card">
        <div class="card_img">
            <img src="https://luv.vn/wp-content/uploads/2021/10/gai-xinh-toc-ngan-14.jpg" alt="">
        </div>
        <div class="card_tittle">
            <h2>ANH TÚ</h2>
            <span>Front end developer</span>
        </div>
        <div class="card_item">
            <div class="i1">
                <i class="fa-brands fa-facebook"></i>
            </div>
            <div class="i2">
                <i class="fa-brands fa-youtube"></i>
            </div>
            <div class="i3">
                <i class="fa-brands fa-tiktok"></i>
            </div>
            <div class="i4">
                 <i class="fa-brands fa-github"></i>
            </div>
        </div>
        <div class="card_button">
            <button>contact me</button>
        </div>
    </div>
    <!-- card3 -->
    <div class="card">
        <div class="card_img">
            <img src="https://haycafe.vn/wp-content/uploads/2021/12/hinh-anh-gai-xinh-toc-ngan-dep.jpg" alt="">
        </div>
        <div class="card_tittle">
            <h2>ANH TÚ</h2>
            <span>Front end developer</span>
        </div>
        <div class="card_item">
            <div class="i1">
                <i class="fa-brands fa-facebook"></i>
            </div>
            <div class="i2">
                <i class="fa-brands fa-youtube"></i>
            </div>
            <div class="i3">
                <i class="fa-brands fa-tiktok"></i>
            </div>
            <div class="i4">
                 <i class="fa-brands fa-github"></i>
            </div>
        </div>
        <div class="card_button">
            <button>contact me</button>
        </div>
    </div>
</body>
</html>
