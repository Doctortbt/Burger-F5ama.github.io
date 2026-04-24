<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Loading Page</title>

<style>
body {
    margin: 0;
    background: white;
    overflow: hidden;
}

/* شريط التحميل الأحمر فوق */
#bar {
    position: fixed;
    top: 0;
    left: 0;
    height: 5px;
    width: 0%;
    background: red;
    animation: load 3s forwards;
}

/* حركة الشريط */
@keyframes load {
    0% {width: 0%;}
    100% {width: 100%;}
}

/* الصورة في النص */
#logo {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%) scale(0.5);
    width: 150px;
    animation: zoom 3s forwards;
}

/* تكبير الصورة */
@keyframes zoom {
    0% {transform: translate(-50%, -50%) scale(0.5);}
    100% {transform: translate(-50%, -50%) scale(1.2);}
}
</style>
</head>

<body>

<div id="bar"></div>

<img id="logo" src="https://cdn.discordapp.com/attachments/1490843957339361314/1497324717906854031/jojojo.png?ex=69ed1bcf&is=69ebca4f&hm=382709da5b9303826efae91c598ecc3cb2ee326025d9332521d05a2d5a34005d&">

<script>
setTimeout(function(){
    // بعد 3 ثواني ينقلك للصفحة التانية
    window.location.href = "home.html";
}, 3000);
</script>

</body>
</html>
