<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>화이트데이 이벤트</title>

<style>
* { box-sizing: border-box; }
html { -webkit-text-size-adjust: 100%; }
button { -webkit-appearance: none; appearance: none; font: inherit; }

body{
  margin:0;
  min-height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  padding:24px;
  overflow:hidden;

  background-image:
    linear-gradient(rgba(0,0,0,0.35), rgba(0,0,0,0.35)),
    url("01.jpg");
  background-size:cover;
  background-position:center;
  background-repeat:no-repeat;
  transition: background-image .5s ease;

  font-family: system-ui, -apple-system, "Apple SD Gothic Neo", "Noto Sans KR", sans-serif;
}

.card{
  width:100%;
  max-width:420px;
  background:rgba(255,255,255,.95);
  border-radius:20px;
  padding:32px;
  text-align:center;
  box-shadow:0 15px 40px rgba(0,0,0,.25);
  position:relative;
  z-index:10; /* ✅ 클릭 안 막히게 */
}

h1{
  font-size:20px;
  line-height:1.6;
  margin:0 0 24px;
}

.btn-container{
  position:relative;
  width:280px;
  height:56px;
  margin:0 auto;
  touch-action: manipulation; /* ✅ 모바일 탭 반응 개선 */
}

.btn{
  position:absolute;
  top:0;
  width:120px;
  height:48px;
  border:none;
  border-radius:30px;
  font-size:16px;
  cursor:pointer;
  user-select:none;
  z-index:20;            /* ✅ 클릭 안 막히게 */
  pointer-events:auto;   /* ✅ 클릭 안 막히게 */
  transition: transform .15s ease;
}

.btn:active{ transform:scale(.98); }

.yes{ left:0; background:#ff4d6d; color:#fff; }
.no { left:160px; background:#d6d6d6; color:#111; }

.result{
  margin-top:18px;
  font-size:20px;
  font-weight:700;
  color:#ff4d6d;
  display:none;
}

.heart{
  position:fixed;
  pointer-events:none;
  animation: float 2.8s linear forwards;
  z-index:5;
}

@keyframes float{
  0%{ transform:translateY(0); opacity:1; }
  100%{ transform:translateY(-300px); opacity:0; }
}
</style>
</head>

<body>
  <div class="card">
    <h1>
      발렌타인데이에는 못만났지만<br>
      화이트데이에 같이 데이트 할래?
    </h1>

    <div class="btn-container" id="btnArea">
      <button class="btn yes" id="yesBtn" type="button">Yes</button>
      <button class="btn no" id="noBtn" type="button">No</button>
    </div>

    <div class="result" id="result">❤️ 우리 화이트데이 데이트 확정 ❤️</div>
  </div>

<script>
(function () {
  const yesBtn = document.getElementById("yesBtn") || document.querySelector(".yes");
  const noBtn  = document.getElementById("noBtn")  || document.querySelector(".no");
  const btnArea = document.getElementById("btnArea") || document.querySelector(".btn-container");
  const result = document.getElementById("result");

  if (!yesBtn || !noBtn || !btnArea) {
    // 요소가 없으면(복붙 실수) 그냥 종료
    return;
  }

  yesBtn.addEventListener("click", () => {
    document.body.style.backgroundImage =
      'linear-gradient(rgba(0,0,0,0.35), rgba(0,0,0,0.35)), url("02.jpg")';
    if (result) result.style.display = "block";
    createHearts();
  });

  function createHearts(){
    for(let i=0;i<20;i++){
      const h=document.createElement("div");
      h.className="heart";
      h.textContent="❤️";
      h.style.left = (Math.random()*window.innerWidth) + "px";
      h.style.top  = window.innerHeight + "px";
      document.body.appendChild(h);
      setTimeout(()=>h.remove(), 2800);
    }
  }

  function moveNo(){
    const w = noBtn.offsetWidth || 120;
    const h = noBtn.offsetHeight || 48;
    const maxX = btnArea.clientWidth - w;
    const maxY = btnArea.clientHeight - h;

    const x = Math.max(0, Math.random()*maxX);
    const y = Math.max(0, Math.random()*maxY);

    noBtn.style.left = x + "px";
    noBtn.style.top  = y + "px";
  }

  // PC: 올리면 도망
  noBtn.addEventListener("mouseenter", moveNo);

  // 모바일: 누르려는 순간 도망
  noBtn.addEventListener("touchstart", (e) => {
    e.preventDefault();
    moveNo();
  }, { passive:false });

  // 클릭도 방지
  noBtn.addEventListener("click", (e) => {
    e.preventDefault();
    moveNo();
  });

})();
</script>
</body>
</html>
