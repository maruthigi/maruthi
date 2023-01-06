# maruthi
visit my website:https://maruthigi.github.io/maruthi/
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <label>master</label>
   <input type="text" id="user" style="width: 200px;margin: 10px; " placeholder="enter number one"/><br>
   <label>student</label>
   <input type="text" id="user1" style="width: 200px;margin: 10px;" placeholder="enter number two"/><br>
    <input type="button" value="+" onclick="my()" style="width: 50px; background-color: rgb(26, 21, 21); color: white; font-size: larger;"/>
    <input type="button" value="-" onclick="my1()" style="width: 50px; background-color: rgb(28, 22, 22); color: white; font-size: larger;"/>
    <input type="button" value="*" onclick="my2()" style="width: 50px; background-color: rgb(24, 20, 20); color: white; font-size: larger; "/>
    <input type="button" value="/" onclick="my3()" style="width: 50px; background-color: rgb(44, 34, 34); color: white; font-size: larger;"/>
    <input type="button" value="clear" onclick="my4()" style="width: 50px; background-color: rgb(44, 34, 34); color: white; font-size: larger;"/>
    <p id="answer">

    </p>
    <script>

     var c=document.getElementById("answer")
function my(){
    var a=+(document.getElementById("user").value)
     var b=+(document.getElementById("user1").value)
     var k=a+b
     c.innerHTML=`${k}`

}
function my1(){
    var a=+(document.getElementById("user").value)
     var b=+(document.getElementById("user1").value)
     var k=a-b
     c.innerHTML=`${k}`


}
function my2(){
    var a=document.getElementById("user").value
     var b=document.getElementById("user1").value
     var k=a*b
     c.innerHTML=`${k}`

}
function my3(){
    var a=document.getElementById("user").value
     var b=document.getElementById("user1").value
     var k= Math.floor(a/b)
     c.innerHTML=`${k}`

}
function my4(){
    var a=document.getElementById("user").value=""
     var b=document.getElementById("user1").value=""

     c.innerHTML=""

}

    </script>
</body>
</html>
