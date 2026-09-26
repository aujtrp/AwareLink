<!DOCTYPE html>
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
