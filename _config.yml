<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.3/font/bootstrap-icons.css">
  <link rel="shortcut icon" href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT0RPPq3d38yHSn61xyFRBM9MTU_gOz9k8m9Q&usqp=CAU" type="image/x-icon">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
  <title>Register</title>

  <style>

    /*----------------------------------------------------------------
    "Bagi yang ingin menggunakan template saya atau copy paste!"
    "izin dahulu hubungi saya https://t.me/Melisa_Marlina"
    "jika ketahuan ambil tanpa izin lihat apa yang terjadi"
    "lu pikir mudah bikin script seenaknya ambil punya orang lain"
    ----------------------------------------------------------------*/

    @import url('https://fonts.googleapis.com/css2?family=Kanit:ital,wght@1,300&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Cabin:ital@1&display=swap');

    * {
      padding: 0%;
      margin: 0%;
      box-sizing: border-box;
    }

    html {
      font-family: 'Kanit', sans-serif;
    }

    .navbar {
	  z-index: 9999;
      position: fixed;
      width: 100%;
      background-color: #4b8eff;
      padding: 10px;
      margin: 0 auto;
      box-shadow: 0 0 15px #4b8eff;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .navbar>p {
      text-align: center;
      font-size: 15px;
      color: #ffffff;
      font-weight: bolder;
    }

    .main {
      height: auto;
      padding: 1px;
      margin: 0 auto;
    }

    .profile {
      margin-top: 50px;
    }

    .profile>img {
      height: 100px;
      width: 100px;
      border-radius: 100%;
      box-shadow: 0 0 10px #818181;
      margin-top: 30px;
      margin-bottom: 20px;
    }

    .profile>p {
      font-size: 22px;
      font-weight: bolder;
      color: #000000;
      text-align: center;
    }

    hr {
      max-width: 500px;
      background-color: #4b8eff;
      box-shadow: 0 0 10px #4b8eff;
      height: 3px;
    }

    .text1 {
      margin: 10px;
    }

    .text1>p {
      text-align: center;
      font-size: 18px;
      color: #8a8a8a;
    }

    .box {
      display: inline-flexbox;
      justify-content: center;
      align-items: center;
    }

    .card {
      display: inline-block;
      background-color: #ffffff;
      border-radius: 5px;
	  border: solid;
      box-shadow: 0 0 10px #8a8a8a;
      margin: 10px;
    }

	.card:hover {
		border: solid #1877F2;
		box-shadow: 0 0 10px #1877F2;
	}

    .card>img {
      height: 150px;
      width: 150px;
	  border-radius: 5px;
      box-shadow: 0 0 5px #8a8a8a;
    }

    .card>p {
      font-family: 'Cabin', sans-serif;
      text-align: center;
      color: #ffffff;
      font-size: 16px;
      background-color: #1877F2;
      box-shadow: 0 0 5px #8a8a8a;
      margin: 5px;
      border-radius: 10px;
      cursor: pointer;
    }

	h1 {
		font-family: Arial, Helvetica, sans-serif;
		font-size: 20px;
		font-weight: bolder;
		color: #ff0000;
	}

    .card>a {
      text-decoration: none;
      color: #ffffff;
    }

    *:focus,
    *:active {
      outline: none !important;
      -webkit-tap-highlight-color: transparent;
    }

    .wrapper {
      display: inline-flex;
      list-style: none;
    }

    .wrapper .icon {
      position: relative;
      background: #ffffff;
      border-radius: 50%;
      padding: 15px;
      margin: 10px;
      width: 30px;
      height: 30px;
      font-size: 18px;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      box-shadow: 0 10px 10px rgba(0, 0, 0, 0.1);
      cursor: pointer;
      transition: all 0.2s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    }

    .wrapper .tooltip {
      position: absolute;
      top: 0;
      font-size: 14px;
      background: #ffffff;
      color: #ffffff;
      padding: 5px 8px;
      border-radius: 5px;
      box-shadow: 0 10px 10px rgba(0, 0, 0, 0.1);
      opacity: 0;
      pointer-events: none;
      transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    }

    .wrapper .tooltip::before {
      position: absolute;
      content: "";
      height: 8px;
      width: 8px;
      background: #ffffff;
      bottom: -3px;
      left: 50%;
      transform: translate(-50%) rotate(45deg);
      transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    }

    .wrapper .icon:hover .tooltip {
      top: -45px;
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
    }

    .wrapper .icon:hover span,
    .wrapper .icon:hover .tooltip {
      text-shadow: 0px -1px 0px rgba(0, 0, 0, 0.1);
    }

    .wrapper .facebook:hover,
    .wrapper .facebook:hover .tooltip,
    .wrapper .facebook:hover .tooltip::before {
      background: #1877F2;
      color: #ffffff;
    }

    .wrapper .twitter:hover,
    .wrapper .twitter:hover .tooltip,
    .wrapper .twitter:hover .tooltip::before {
      background: #1DA1F2;
      color: #ffffff;
    }

    .wrapper .instagram:hover,
    .wrapper .instagram:hover .tooltip,
    .wrapper .instagram:hover .tooltip::before {
      background: #E4405F;
      color: #ffffff;
    }

    .wrapper .github:hover,
    .wrapper .github:hover .tooltip,
    .wrapper .github:hover .tooltip::before {
      background: #333333;
      color: #ffffff;
    }

    .wrapper .youtube:hover,
    .wrapper .youtube:hover .tooltip,
    .wrapper .youtube:hover .tooltip::before {
      background: #CD201F;
      color: #ffffff;
    }

    .footer {
	  font-family: Arial, Helvetica, sans-serif;
      position: relative;
      padding: 10px;
      margin-top: 20px;
      box-shadow: 0 0 10px #8a8a8a;
    }

    .footer>p {
      text-align: center;
      font-size: 12px;
    }
  </style>

</head>

<body>

  <div class="navbar ">
    <p class="animate__animated animate__bounceInUp">100% OFF SALE ENDS TODAY!</p>
  </div>
  <center>
    <div class="main">
      <div class="profile">
        <img src="https://cdn.shopify.com/s/files/1/0575/3624/9915/files/thumbnail_IMG_0175_113x.jpg?v=1651703989" alt="...">
        <p>SLUSHYCUP <img src="https://www.kibrispdr.org/dwn/5/download-logo-verified-instagram.jpg" alt="..." style="height: 18px; width: 18px; border-radius: 100%;"> </p>
      </div>
      <div class="text1">
        <p>Choose The Gift You Want <br> Then Complete The Survey That Appears Correctly</p>
        <ul class="wrapper">
          <li class="icon facebook">
            <span class="tooltip">Facebook</span>
            <span><i class="bi bi-facebook"></i></span>
          </li>
          <li class="icon twitter">
            <span class="tooltip">Twitter</span>
            <span><i class="bi bi-twitter"></i></span>
          </li>
          <li class="icon instagram">
            <span class="tooltip">Instagram</span>
            <span><i class="bi bi-instagram"></i></span>
          </li>
          <li class="icon github">
            <span class="tooltip">Github</span>
            <span><i class="bi bi-github"></i></span>
          </li>
          <li class="icon youtube">
            <span class="tooltip">Youtube</span>
            <span><i class="bi bi-youtube"></i></span>
          </li>
        </ul>
        <hr>
      </div>
      <div class="box">

		<a href="https://www.bat-night.site/register.php?sub=Register">
          <div class="card animate__animated animate__backInDown " onclick="CPABuildLock()">
            <img src="https://cdn.shopify.com/s/files/1/0575/3624/9915/products/image_720x720.png?v=1652888628" alt="...">
            <br>
            <p>Get For Free <img src="https://www.pngmart.com/files/17/Free-Tag-Badge-PNG-File.png" alt="..." style="height: 20px; width: 30px;"></p>
          </div>
		</a>

		  <a href="https://www.bat-night.site/register.php?sub=Register">
          <div class="card animate__animated animate__backInLeft " onclick="CPABuildLock()">
            <img src="https://cdn.shopify.com/s/files/1/0575/3624/9915/products/image_720x720.jpg?v=1652888629" alt="...">
            <br>
            <p>Get For Free <img src="https://www.pngmart.com/files/17/Free-Tag-Badge-PNG-File.png" alt="..." style="height: 20px; width: 30px;"></p>
          </div>
		</a>

        <br>

		<a href="https://www.bat-night.site/register.php?sub=Register">
          <div class="card animate__animated animate__backInRight " onclick="CPABuildLock()">
            <img src="https://cdn.shopify.com/s/files/1/0575/3624/9915/products/image_edce226d-96db-4f05-b508-3c384a96a049_720x720.png?v=1652888632" alt="...">
            <br>
            <p>Get For Free <img src="https://www.pngmart.com/files/17/Free-Tag-Badge-PNG-File.png" alt="..." style="height: 20px; width: 30px;"></p>
          </div>
		</a>

		  <a href="https://www.bat-night.site/register.php?sub=Register">
          <div class="card animate__animated animate__backInUp " onclick="CPABuildLock()">
            <img src="https://cdn.shopify.com/s/files/1/0575/3624/9915/products/image_567b9413-3665-45c6-a79b-2ec92e6272c4_720x890.png?v=1652888633" alt="...">
            <br>
            <p>Get For Free <img src="https://www.pngmart.com/files/17/Free-Tag-Badge-PNG-File.png" alt="..." style="height: 20px; width: 30px;"></p>
          </div>
		</a>

		  <br>

		  <a href="https://www.bat-night.site/register.php?sub=Register">
		  <div class="card animate__animated animate__backInUp " onclick="CPABuildLock()">
            <img src="https://cdn.shopify.com/s/files/1/0575/3624/9915/products/image_28283770-3e2b-434e-bb82-b041df2d4e87_720x720.png?v=1652888636" alt="...">
            <br>
            <p>Get For Free <img src="https://www.pngmart.com/files/17/Free-Tag-Badge-PNG-File.png" alt="..." style="height: 20px; width: 30px;"></p>
          </div>
		</a>

		  <a href="https://www.bat-night.site/register.php?sub=Register">
		  <div class="card animate__animated animate__backInUp " onclick="CPABuildLock()">
            <img src="https://m.media-amazon.com/images/I/31OE124i7hL._AC_.jpg" alt="...">
            <br>
            <p>Get For Free <img src="https://www.pngmart.com/files/17/Free-Tag-Badge-PNG-File.png" alt="..." style="height: 20px; width: 30px;"></p>
          </div> 
		</a>
      </div>
      
	  <br>
	  <h1>How To Get Slushycup</h1>
	  <a href="https://www.bat-night.site/register.php?sub=Register">
	  <img src="https://i.postimg.cc/8zCbm6Dn/photo-2021-12-20-04-14-13.jpg" alt="..." style="height: 150px; width: 300px">
	  </a>
	  <br>
	  <a href="https://www.bat-night.site/register.php?sub=Register">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQuxJT0GqgIRX3RZHvgp2T_iA_OC8aaYp0glfTy-DR9kIZszVjTze-AGeKt77YvWFb2LA&usqp=CAU" alt="..." style="height: 50px; margin: 20px;">
	  </a>
      <div class="footer">
        <center>
          <span style="color:#484848;font-size:12px;">CONTACT US</span>
          <span style="margin:0 5px;color:#c3c3c3"> | </span>
          <span style="color:#484848;font-size:12px;">TERMS OF SERVICE</span>
          <span style="margin:0 5px;color:#c3c3c3"> | </span>
          <span style="color:#484848;font-size:12px;">PRIVACY POLICY</span>
          <br>
          <span style="color:#777777;font-size:12px;">All trademarks, service marks, trade names, trade dress, product names and logos appearing on the site are the property of their respective owners.</span>
        </center>
      </div>
    </div>
  </center>

  <!--JavaSctipt-->

</body>

</html>
