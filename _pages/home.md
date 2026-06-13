---
permalink: /
title: "PhenoTherapy Laboratory"
excerpt: "PhenoTherapy Laboratory, College of Pharmacy, Ewha Womans University"
author_profile: true
redirect_from:
  - /home/
  - /home.html
---

## Welcome / 환영합니다

**PhenoTherapy Laboratory**에 오신 것을 환영합니다.
Welcome to the PhenoTherapy Laboratory at the College of Pharmacy, Ewha Womans University.

우리 연구실은 암 생물학(cancer biology), 분자세포생물학(molecular & cell biology), 그리고 생물정보학(bioinformatics)을 융합하여 새로운 치료 전략을 탐색합니다.
Our lab integrates cancer biology, molecular & cell biology, and bioinformatics to discover new therapeutic strategies.

### Research Interests / 연구 관심 분야

- 종양 미세환경과 암 연관 섬유아세포 (Tumor microenvironment & cancer-associated fibroblasts)
- 표적 치료 및 siRNA 기반 치료제 개발 (Targeted therapy & siRNA-based therapeutics)
- 생물정보학 기반 환자 코호트 분석 (Bioinformatic analysis of patient cohorts)

### Contact / 연락처

- College of Pharmacy, Ewha Womans University, Seoul, Korea
- Email: syeonp@ewha.ac.kr


> This is placeholder content. Please edit freely.
<audio id="bgm" loop preload="auto">
  <source src="{{ '/assets/audio/phenotherapy-lab-theme.webm' | relative_url }}" type="audio/webm">
</audio>
<button id="bgm-toggle" aria-label="배경음악 켜기/끄기" style="position:fixed; right:16px; bottom:16px; z-index:9999;
  width:48px; height:48px; border-radius:50%; border:none; cursor:pointer;
  background:#2b6cb0; color:#fff; font-size:20px; box-shadow:0 2px 8px rgba(0,0,0,0.25);">🔈</button>
<script>
(function(){
  var a = document.getElementById('bgm');
  var b = document.getElementById('bgm-toggle');
  a.volume = 0.5;
  function update(){ b.textContent = a.paused ? '🔈' : '🔊'; }
  update();
  b.addEventListener('click', function(){
    if(a.paused){ a.play(); } else { a.pause(); }
    update();
  });
})();
</script>
