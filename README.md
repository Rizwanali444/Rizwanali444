
Coded  by Rizwan Ali digital clock⏰ 🙂🙂 in simple html  and  css

<html>

<head>

<title>

Digital Clock

</title>

<style>

body {

background:black;

}

div {

width:40%;

text-align:center;

font-size:500%;

padding:50px;

border-radius:20px;

background:black;

color:lime;

margin-top:20%;

box-shadow:10px 10px 15px lime, -10px -10px 15px lime, -10px 10px 15px lime, 10px -10px 15px lime;

}

</style>

</head>

<body>

<center>

<div id="clock">00 : 00 : 00</div>

</center>

<script>

setInterval(function() {

var time = new Date();

var clock = document.getElementById("clock");

clock.innerHTML = time.getHours() + " : " + time.getMinutes() + " : " + time.getSeconds();

}, 100)

</script>

</body>

</html>
- 👋 Hi, I’m @Rizwanali444
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Rizwanali444/Rizwanali444 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
