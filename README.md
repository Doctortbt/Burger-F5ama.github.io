<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Loading</title>

<style>
body {
    margin:0;
    background:white;
    overflow:hidden;
}

#bar {
    position:fixed;
    top:0;
    left:0;
    height:5px;
    width:0%;
    background:red;
    animation:load 3s forwards;
}

@keyframes load {
    from {width:0%;}
    to {width:100%;}
}

#logo {
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%) scale(0.5);
    width:160px;
    animation:zoom 3s forwards;
}

@keyframes zoom {
    from {transform:translate(-50%,-50%) scale(0.5);}
    to {transform:translate(-50%,-50%) scale(1.2);}
}
</style>
</head>

<body>

<div id="bar"></div>

<img id="logo" src="https://cdn.discordapp.com/attachments/1490843957339361314/1497324717906854031/jojojo.png">

<script>
setTimeout(function(){
    // أهم سطر 👇 يفتح نفس الموقع بدون 404
    window.location.href = "./";
}, 3000);
</script>

</body>
</html>
