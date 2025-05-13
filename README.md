# website-afdal.vgv

[Uploading index.html…]()<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css"
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
    <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
    <title></title>
</head>
<body>
    <div class="container animate__animated animate__zoomIn">
        <!--profil picture -->
        <div class="profile">
            <img src="Mad One Piece GIF by Toei Animation.gif"alt="error image" class="animate__animated animate__pulse animate__infinite " />
            <p class="animate__animated animate__fadeInDownBig">SELAMAT DATANG DI WEB AFDAL.VGV</p>
        </div>

        <!-- link tree button -->
        <div class="link">
            <a href="https://instagram.com/muh.afdaall" target="_blank" class="animate__animated animate__bounceInLeft"> instagram</a> 
            <a href="https://tiktok.com/afdal.vgv" target="_blank" class="animate__animated animate__bounceInLeft animate__delay-1s"> tik tok</a>
            <a href="https://youtube.com/afdaldn" target="_blank" class="animate__animated animate__bounceInLeft animate__delay-2s"> you tube</a>
            <a href="https://whatsApp.com/089603918522" target="_blank" class="animate__animated animate__bounceInLeft animate__delay-3s"> whatsApp</a>       
            
        </div>

        <!-- footer -->
        <div class="footer animate__animated animate__bounceInUp animate__delay-4s">
            <i>AFDAL.VGV❤️ </i>
        </div>
    </div>
</body>
</html>
* {
    margin: 0;
    padding: 0;
}

html {
    .bebas-neue-regular {
  font-family: "Bebas Neue", sans-serif;
  font-weight: 400;
  font-style: normal;
}

}

.container {
    max-width: 500px;
    margin: 0 auto;
    background: red;
    height: 100vh;
    background-image: url("roronoa-zoro-using-santoryu-desktop-wallpaper.jpg");
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
}

.profile {
   display: flex;
   flex-direction: column;
   align-items: center;
   justify-content: center;
   padding: 20px;
}

.profile>img {
width: 150px;
height: 150px;
border: 3px solid #222;
border-radius: 100%;
}

.profile > p {
    font-size: 1.8em;
    font-weight: 900;
    letter-spacing: 2px;
    color: white;
    text-transform: capitalize;
    text-align: center;
}

.link {
    display: flex;
    justify-content: center;
    flex-direction: column;
    padding: 20px;
}

.link > a {
    text-decoration: none;
    color: #222;
    font-size: 24px;
    text-align: center;
    border: 3px solid;
    border-radius: 7px;
    background-color: white;
    margin: 5px 10px;
    padding: 10px;
    text-transform: uppercase;
    font-weight: 500;
}

.link > a:hover {
    background-color: black;
}

.footer {
    text-align: center;
}

.footer > i {
    color: wheat;
    font-size: 20px;
}
