<!DOCTYPE
<html>
<head>
<title>AwareLink</title>
<meta name="viewport" content="width=device-width,initial-scale=1">
<style>
body{background:#111;color:#fff;font-family:Arial;text-align:center;padding:40px}
button{padding:12px 20px;border:0;border-radius:10px;background:#22c55e;color:#fff}
</style>
</head>
<body>
<h1>🔒 AwareLink</h1>
<p>Safe educational demo</p>
<button onclick="info()">Start</button>
<p id="x"></p>

<script>
function info(){
document.getElementById("x").innerHTML=
"Browser: "+navigator.userAgent+"<br><br>No data is sent.";
}
</script>
</body>
</html> 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>AwareLink</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
  font-family:Arial,sans-serif;
  background:linear-gradient(135deg,#0f172a,#1e3a8a);
  color:white;
  display:flex;
  justify-content:center;
  align-items:center;
  min-height:100vh;
  padding:20px;
}
.card{
  width:100%;
  max-width:420px;
  background:rgba(255,255,255,.08);
  backdrop-filter:blur(14px);
  border-radius:22px;
  padding:28px;
  text-align:center;
  border:1px solid rgba(255,255,255,.15);
}
.logo{font-size:55px}
h1{margin:12px 0}
p{color:#d1d5db;line-height:1.6}
button{
  margin-top:22px;
  width:100%;
  padding:14px;
  border:none;
  border-radius:12px;
  background:#22c55e;
  color:white;
  font-size:17px;
  cursor:pointer;
}
#info{
  margin-top:18px;
  text-align:left;
  background:#111827;
  padding:14px;
  border-radius:12px;
  display:none;
  font-size:14px;
}
.footer{
  margin-top:18px;
  font-size:12px;
  color:#9ca3af;
}
</style>
</head>
<body>
<div class="card">
  <div class="logo">🔒</div>
  <h1>AwareLink</h1>
  <p>Cybersecurity educational demo.<br>
  Learn what information websites can normally detect.</p>

  <button onclick="demo()">Start Demo</button>

  <div id="info"></div>

  <div class="footer">
    Educational only • No data is sent to any server
  </div>
</div>

<script>
function demo(){
  const box=document.getElementById("info");
  box.style.display="block";
  box.innerHTML=
  "<b>Browser</b><br>"+navigator.userAgent+
  "<hr><b>Language</b><br>"+navigator.language+
  "<hr><b>Platform</b><br>"+navigator.platform+
  "<hr><b>Cookies Enabled</b><br>"+navigator.cookieEnabled+
  "<hr><b>Important:</b><br>This demo does not collect or send your IP address.";
}
</script>
</body>
</html>
