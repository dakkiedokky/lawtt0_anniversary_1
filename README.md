# lawtt0_anniversary_1
<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>100일 기념</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <main class="app" id="app" aria-live="polite">
    <!-- Progress -->
    <header class="top">
      <div class="brand">100일 기록물</div>
      <div class="progress" aria-label="진행 단계">
        <span class="dot is-on" id="dot-1"></span>
        <span class="dot" id="dot-2"></span>
        <span class="dot" id="dot-3"></span>
        <span class="dot" id="dot-4"></span>
      </div>
    </header>

    <!-- Card -->
    <section class="card" id="card">
      <div class="meta" id="meta">
        <span class="pill" id="stagePill">기록 1</span>
        <span class="date" id="stageDate">ver. 2026-03-04</span>
      </div>

      <h1 class="title" id="title">첫 인상에 관한 의견서</h1>
      <p class="subtitle" id="subtitle">
        아래 내용은 당사자(작성자)의 주관적 관찰을 근거로 작성된 비공식 문서이며, 귀하의 동의 여부와 무관하게 감정이 실린다는 치명적 결함을 내포합니다.
      </p>

      <div class="paper" id="paper">
        <p class="paper-line">
          1. 사실관계(요지): (여기에 첫 인상 내용을 3줄 이상으로 작성)
        </p>
        <p class="paper-line">
          2. 판단(가설): (여기에 “왜 그렇게 느꼈는지”를 논문처럼 한 번 더)
        </p>
        <p class="paper-line">
          3. 결론(잠정): (여기에 첫 인상 결론을 정리)
        </p>
      </div>

      <div class="actions" id="actions">
        <button class="btn primary" id="nextBtn" type="button">다음</button>
      </div>

      <div class="fineprint" id="fineprint">
        본 문서는 법적 효력이 없고, 다만 마음에는 효력이 있을 수 있습니다.
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <span id="hint">PC에서 최적 동작</span>
    </footer>
  </main>

  <script src="script.js"></script>
</body>
</html>
