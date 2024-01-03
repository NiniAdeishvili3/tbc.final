<!DOCTYPE html>
<html>
<head>
    <title>გაიცანი თეატრი</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F2F2F2;
        }
    
        header {
            background-color: rgb(69, 5, 5);
            color: white;
            padding: 10px;
            text-align: center;
        }
    
        nav ul {
            background-color: rgb(69, 5, 5);
            list-style-type: none;
            padding: 0;
            margin: 0;
            overflow: hidden;
        }
    
        nav ul li {
            float: left;
        }
    
        nav ul li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
    
        nav ul li a:hover {
            background-color: #111;
        }
    
        main {
            padding: 20px;
            background-color: white;
            margin: 15px;
        }
    
        footer {
            background-color: #1e0202;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
    
</head>
<body>
    
    
    
    <header>
        <h1>ვაქციოთ ქართული თეატრი ყოველდღიურობად</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="https://www.tbceducation.ge/"><img src="logo.png"></a></li>
            <li><a href="main.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="news.html">News</a></li>
            <li><a href="Contactus.html">Contact</a></li>
        </ul>
    </nav>
    
    <main>
        
    <div class="image-container">
        <img src="1background" alt="ჩვენი ვებსაიტის დახმარებით, შეისწავლე ქართული თეატრის ისტორია დეტალურად,
         გადახედე შეფასებებს თანამედროვე სპექტაკლებდე, გაუზიარე ახლად მიღებული ცოდნა მეგობრებს
          და, რაც მთავარია, აქციე ქართული თეატრი ყოველდღიურობად!">
        <div class="centered-text">გაიგე მეტი ხელოვნების ამ დარგის შესახებ</div>
      </div>
      <style>
      
      .image-container {
        position: relative;
        width: 100%;
      }
      
      .image-container img {
        width: 100%;
        height: auto;
      }
      
      .centered-text {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        color: white;
        font-size: 24px; 
      }
</style>
<br>
<div class="image-container2">
    <img src="2.jpg" alt="შეისწავლე ქართული თეატრის ისტორია დეტალურად">
    <img src="3.jpg" alt="გადახედე შეფასებებს თანამედროვე თეატრთან დაკავშირებით">
    <img src="4.jpg" alt="გაუზიარე მეგობრებს ახლად მიღებული ცოდნა">
  </div>
<style>
  
  .image-container2 {
    display: flex;
    justify-content: space-between;
  }
  
  .image-container2 img {
    width: calc(33.33% - 10px); 
    margin: 5px; 
  }
  </style>
    </main>
    
    <footer>
        <p>Copyright &copy; 2023</p>
    </footer>
</body>

</html>
