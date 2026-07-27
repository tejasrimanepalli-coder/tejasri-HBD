# tejasri-HBD
HBD teju
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0>

<title>Happy Birthday Teju 🎂</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    overflow:hidden;
    font-family:Arial,sans-serif;

    background:linear-gradient(-45deg,#ff4da6,#ffcc00,#66ccff,#8a2be2);
    background-size:400% 400%;
    animation:bgMove 10s ease infinite;
}

@keyframes bgMove{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

.container{
    text-align:center;
    z-index:2;
}

.cake{
    font-size:90px;
    animation:bounce 1s infinite alternate;
}

@keyframes bounce{
    from{transform:translateY(0);}
    to{transform:translateY(-20px);}
}

h1{
    font-size:70px;
    color:white;
    text-shadow:
    0 0 10px white,
    0 0 20px #ff00ff,
    0 0 40px #ff00ff;
    animation:zoom 2s infinite alternate;
}

@keyframes zoom{
    from{transform:scale(1);}
    to{transform:scale(1.15);}
}

p{
    font-size:30px;
    margin-top:20px;
    color:white;
    font-weight:bold;
    text-shadow:2px 2px 8px black;
}

/* Balloons */
.balloon{
    position:absolute;
    bottom:-120px;
    font-size:60px;
    animation:fly 10s linear infinite;
}

@keyframes fly{
    0%{transform:translateY(0);}
    100%{transform:translateY(-130vh);}
}

/* Hearts */
.heart{
    position:absolute;
    top:-50px;
    font-size:35px;
    animation:fall 8s linear infinite;
}

@keyframes fall{
    0%{transform:translateY(-10vh);}
    100%{transform:translateY(120vh);}
}
</style>
</head>

<body>

<div class="container">

<div class="cake">🎂</div>

<h1>
HAPPY BIRTHDAY<br>
TEJU ❤️
</h1>

<p>
🎉 Happy Birthday Teju! 🎉
<br><br>
✨ May all your dreams come true ✨
<br><br>
😊 Keep smiling forever 😊
<br><br>
😊Your smile is always beautiful😊
</p>

</div>

<!-- Balloons -->
<div class="balloon" style="left:5%;animation-delay:0s;">🎈</div>
<div class="balloon" style="left:18%;animation-delay:2s;">🎈</div>
<div class="balloon" style="left:32%;animation-delay:1s;">🎈</div>
<div class="balloon" style="left:48%;animation-delay:3s;">🎈</div>
<div class="balloon" style="left:62%;animation-delay:4s;">🎈</div>
<div class="balloon" style="left:78%;animation-delay:1s;">🎈</div>
<div class="balloon" style="left:92%;animation-delay:2s;">🎈</div>

<!-- Hearts -->
<div class="heart" style="left:10%;animation-delay:0s;">❤️</div>
<div class="heart" style="left:30%;animation-delay:2s;">💖</div>
<div class="heart" style="left:50%;animation-delay:1s;">💕</div>
<div class="heart" style="left:70%;animation-delay:3s;">💝</div>
<div class="heart" style="left:90%;animation-delay:2s;">❤️</div>

<script>
setTimeout(function(){
    alert("🎉 Happy Birthday Teju! 🎂\n\nMay all your dreams come true ❤️\nKeep smiling forever 😊");
},500);
</script>

</body>
</html>
