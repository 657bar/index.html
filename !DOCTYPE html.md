<!DOCTYPE html>  
<html>  
<head>  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<title>Game</title>  
</head>  
  
<body style="text-align:center; font-family:Arial; padding-top:50px">  
  
<h2>🎰 Слот игра</h2>  
  
<h1 id="slot">❓ ❓ ❓</h1>  
  
<button onclick="spin()">Крутить</button>  
  
<script>  
function spin(){  
    let s = ["🍎","⭐","7️⃣","💎","🎲"];  
    document.getElementById("slot").innerText =  
        s[Math.floor(Math.random()*s.length)] + " " +  
        s[Math.floor(Math.random()*s.length)] + " " +  
        s[Math.floor(Math.random()*s.length)];  
}  
</script>  
  
</body>  
</html>  
