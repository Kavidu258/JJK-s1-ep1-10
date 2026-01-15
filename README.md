<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Watch Anime</title>
  <style>
    body{
      background:#000;
      color:#fff;
      text-align:center;
      font-family:Arial;
      margin-top:100px;
    }
    input,button{
      padding:10px;
      font-size:16px;
      margin-top:10px;
    }
  </style>
</head>
<body>

<h2>🔒 Enter password to watch Jujutsu Kaisen S1 E1</h2>

<input type="password" id="pass" placeholder="Enter password"><br>
<button onclick="check()">GO</button>

<p id="msg" style="color:red;"></p>

<script>
function check(){
  if(document.getElementById("pass").value==="25"){
    window.location.href="PASTE_GOOGLE_DRIVE_LINK_HERE";
  }else{
    document.getElementById("msg").innerText="❌ Wrong password";
  }
}
</script>

</body>
</html>
