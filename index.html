<!DOCTYPE html>
<html>
<head>
<title>Spring Mass System</title>
<style>
body { background:#0f172a; color:white; font-family:sans-serif; text-align:center; }
canvas { background:#1e293b; border-radius:20px; margin-top:20px; }
input { margin:10px; }
.box { background:#1e293b; padding:15px; border-radius:15px; display:inline-block; margin-top:15px; }
</style>
</head>
<body>
<h2>🌱 Spring Mass System</h2>
<div class="box">
Mass: <input type="range" id="mass" min="1" max="10" value="3"> <span id="massVal">3 kg</span><br>
Stiffness (k): <input type="range" id="k" min="10" max="100" value="40"> <span id="kVal">40 N/m</span>
</div>
<br>
<canvas id="c" width="400" height="400"></canvas>
<script>
let canvas=document.getElementById('c'), ctx=canvas.getContext('2d');
let mass=3, k=40, y=150, vy=0;
document.getElementById('mass').oninput=e=>{mass=e.target.value; document.getElementById('massVal').innerText=mass+' kg'}
document.getElementById('k').oninput=e=>{k=e.target.value; document.getElementById('kVal').innerText=k+' N/m'}
function animate(){
  let F = -k * (y-150) - 0.5*vy; // spring + damping
  let a = F / mass;
  vy += a * 0.02;
  y += vy;
  ctx.clearRect(0,0,400,400);
  // ceiling
  ctx.fillRect(150,20,100,10);
  // spring
  ctx.beginPath(); ctx.moveTo(200,30);
  let segments=20;
  for(let i=0;i<segments;i++){
    let sy = 30 + (y-30)*(i/segments);
    let sx = 200 + (i%2==0? -20:20);
    ctx.lineTo(sx,sy);
  }
  ctx.strokeStyle='#38bdf8'; ctx.lineWidth=3; ctx.stroke();
  // mass box
  ctx.fillStyle='#f472b6'; ctx.fillRect(170,y,60,60);
  ctx.fillStyle='white'; ctx.fillText(mass+'kg',185,y+35);
  requestAnimationFrame(animate);
}
animate();
</script>
</body>
</html>
