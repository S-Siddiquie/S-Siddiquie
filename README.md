- 👋 Hi, I’m @S-Siddiquie
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="weather.css">
    <title>Weather Update</title>
</head>
<body>
    <div class="container">
        <h2>10-cast forecast</h2>
        <div class="div-box">
            <p>Friday 11Oct</p>
            <div class="sun"></div>
            <p>39<sup>o</sup>/29<sup>o</sup></p>
        </div>
        <div class="div-box">
            <p>Saturday12Oct</p>
            <div class="sun"></div>
            <p>38<sup>o</sup>/29<sup>o</sup></p>
        </div>
        <div class="div-box">
            <p>Sunday 13Oct</p>
            <div class="dark"></div>
            <p>37<sup>o</sup>/27<sup>o</sup></p>
        </div>
        <div class="div-box">
            <p>Monday 14Oct</p>
            <div class="dark"></div>
            <p>36<sup>o</sup>/27<sup>o</sup></p>
        </div>
        <div class="div-box">
            <p>Tuesday 15Oct</p>
            <div class="sun"></div>
            <p>37<sup>o</sup>/27<sup>o</sup></p>
        </div>
        <div class="div-box">
            <p>wednesday 16Oct</p>
            <div class="dark"></div>
            <p>37<sup>o</sup>/27<sup>o</sup></p>
        </div>
        <div class="div-box">
            <p>Thursday 17Oct</p>
            <div class="sun"></div>
            <p>38<sup>o</sup>/27<sup>o</sup></p>
        </div>
        <div class="div-box">
            <p>Friday 18Oct</p>
            <div class="dark"></div>
            <p>38<sup>o</sup>/27<sup>o</sup></p>
        </div>
        <div class="div-box">
            <p>Saturday 19Oct</p>
            <div class="dark"></div>
            <p>37<sup>o</sup>/27<sup>o</sup></p>
        </div>
    </div>
</body>
</html>

*{
   margin:0;
}
body{
    background-color: #001f3f;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    color: white;
}
.container{
    /* background-color: #fff; */
    padding: 40px;
    border-radius: 16px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    width: 350px;
  }
h2{
   padding-bottom: 8px;
   font-weight: lighter;
}
.div-box{
    /* display: flex;
    background-color: blue; */
    padding: 15px;
    border-radius: 10px;
    background-color: #304466;
    display: flex;
    justify-content: space-between;
    align-items: center; 
    margin-bottom: 15px;   
}
.sun{
    width: 30px;
    height: 30px;
    background-color: #f9c600;
    border-radius: 50px;
    text-align: left;
}
.dark{
    width: 30px;
    height: 30px;
    background-color: #bdbdbd;
    border-radius: 50px;
    text-align: left;
}

