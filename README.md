<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>JOSHI YADAV // UNIQ</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;800&display=swap');
*{margin:0;padding:0;box-sizing:border-box;font-family:'JetBrains Mono',monospace}
body{background:#050507;color:#fff;min-height:100vh}
.top{height:4px;background:linear-gradient(90deg,#ff006a,#00f5ff,#ffe600);animation:move 3s linear infinite}
@keyframes move{0%{filter:hue-rotate(0)}100%{filter:hue-rotate(360deg)}}
.wrap{max-width:400px;margin:auto;padding:20px}
.head{display:flex;justify-content:space-between;padding:15px 0;border-bottom:1px dashed #222}
.logo{font-weight:800;cursor:pointer}
.hero{margin:50px 0}
.hero h1{font-size:48px;font-weight:800;line-height:0.9;letter-spacing:-2px}
#type{color:#00f5ff;min-height:60px}
.tag{color:#666;font-size:12px;margin:10px 0}
.box{border:1px solid #1a1a1a;background:#0e0e10;border-radius:18px;padding:20px;margin:18px 0;position:relative;overflow:hidden}
.box::before{content:'';position:absolute;top:-1px;left:-1px;right:-1px;height:1px;background:linear-gradient(90deg,transparent,#00f5ff,transparent)}
.num{font-size:50px;font-weight:800;color:#111;-webkit-text-stroke:1px #222;position:absolute;right:10px;top:5px}
.btn{display:block;background:#fff;color:#000;text-align:center;padding:16px;border-radius:100px;text-decoration:none;font-weight:800;margin-top:15px;letter-spacing:1px}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.small{font-size:11px;color:#555;margin-top:40px;text-align:center}
</style>
</head>
<body>
<div class="top"></div>
<div class="wrap">
<div class="head"><div class="logo" id="logo">JY_</div><div style="color:#00f5ff;font-size:11px">● SYSTEM ONLINE</div></div>

<div class="hero">
<div class="tag">[ BCA 1ST YEAR / O-LEVEL CERTIFIED ]</div>
<h1 id="type"></h1>
<p style="color:#666;margin-top:15px;font-size:13px">77.8% in 12th Maths. Building web on phone. No laptop, no excuses.</p>
</div>

<div class="box">
<div class="num">01</div>
<b>JOSHI YADAV</b><br><br>
<span style="color:#888;font-size:13px">Stack: HTML / CSS / JS / Python<br>Mission: Make phone coding cool</span>
<a class="btn" href="https://github.com/Joshii-codes">EXPLORE GITHUB →</a>
</div>

<div class="grid">
<div class="box" style="text-align:center"><b style="font-size:28px">07+</b><br><span style="color:#666;font-size:11px">PROJECTS</span></div>
<div class="box" style="text-align:center"><b style="font-size:28px">100%</b><br><span style="color:#666;font-size:11px">PHONE MADE</span></div>
</div>

<div class="box" style="background:#00f5ff;color:#000;border:none">
<b>MY FLEX 💎</b><br><span style="font-size:13px">BCA me sab laptop maang rahe hain, main phone se portfolio live kar chuki hu.</span>
</div>

<div class="small">shake your phone = magic // click logo 5x = secret<br>© JOSHI YADAV 2026</div>
</div>

<script>
let texts=["JOSHI","YADAV","UNIQUE","BUILDER"],i=0,j=0,del=false;
function type(){let cur=texts[i];document.getElementById('type').innerHTML=cur.substring(0,j)+(j%2?'_':' ');if(!del){j++;if(j>cur.length+8){del=true}}else{j--;if(j==0){del=false;i=(i+1)%texts.length}}setTimeout(type,120)}
type();
let c=0;document.getElementById('logo').onclick=()=>{c++;if(c==5){document.body.style.background='#ff006a';alert('BOOM! You found secret mode! 🔥');c=0}};
window.addEventListener('deviceorientation',e=>{document.body.style.filter=`hue-rotate(${e.gamma*2}deg)`});
</script>
</body>
</html>
