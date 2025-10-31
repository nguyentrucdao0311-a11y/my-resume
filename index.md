<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>履歷 - 113011139</title>
  <style>
    :root {
      --main-color: #0b63ce;
      --light-bg: #f5f8ff;
      --text-color: #333;
      --card-bg: #fff;
    }
    body {
      font-family: "Microsoft JhengHei", Arial, sans-serif;
      background: linear-gradient(180deg, #f0f4ff, #e8f0ff);
      margin: 0;
      padding: 0;
      color: var(--text-color);
    }
    .container {
      max-width: 900px;
      margin: 40px auto;
      background: var(--card-bg);
      border-radius: 16px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.1);
      overflow: hidden;
    }
    header {
      display: flex;
      align-items: center;
      gap: 20px;
      padding: 24px;
      background: var(--light-bg);
      border-bottom: 3px solid #dbe6ff;
    }
    .photo {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      overflow: hidden;
      border: 3px solid #c9dcff;
      flex-shrink: 0;
    }
    .photo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
    .info h1 {
      margin: 0;
      color: var(--main-color);
    }
    .info p {
      margin: 4px 0;
    }
    .chips {
      margin-top: 10px;
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
    }
    .chip {
      background-color: #e9f1ff;
      color: var(--main-color);
      padding: 6px 10px;
      border-radius: 8px;
      font-size: 13px;
    }
    main {
      display: grid;
      grid-template-columns: 1fr 280px;
      gap: 20px;
      padding: 24px;
    }
    section h2 {
      color: var(--main-color);
      font-size: 16px;
      margin-top: 0;
      border-bottom: 2px solid #dbe6ff;
      padding-bottom: 4px;
    }
    section p, li {
      line-height: 1.6;
    }
    section ul {
      margin-top: 0;
      padding-left: 20px;
    }
    aside h2 {
      color: var(--main-color);
      font-size: 16px;
      margin-top: 0;
      border-bottom: 2px solid #dbe6ff;
      padding-bottom: 4px;
    }
    .skill {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin: 6px 0;
    }
    .bar {
      flex: 1;
      height: 8px;
      background: #e3ebff;
      border-radius: 6px;
      margin-left: 8px;
      overflow: hidden;
    }
    .bar i {
      display: block;
      height: 100%;
      background: linear-gradient(90deg, #0b63ce, #5a9cff);
    }
    footer {
      background: var(--light-bg);
      text-align: center;
      padding: 16px;
      font-size: 13px;
      color: #666;
      border-top: 1px solid #e1e8ff;
    }
    button {
      background: var(--main-color);
      color: #fff;
      border: none;
      border-radius: 8px;
      padding: 8px 14px;
      cursor: pointer;
      margin-right: 10px;
    }
    button:hover {
      background: #084c9d;
    }
    .btn-outline {
      background: transparent;
      border: 1px solid var(--main-color);
      color: var(--main-color);
    }
    .actions {
      margin-top: 10px;
    }
    @media(max-width: 800px) {
      main {
        grid-template-columns: 1fr;
      }
      header {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="photo">
        <!-- Ảnh bạn đã tải lên -->
        <img src="avatar.PNG" alt="學生照片">
      </div>
      <div class="info">
        <h1>凌氏玉映（範例姓名）</h1>
        <p>學生 / 健康管理系</p>
        <div class="chips">
          <div class="chip">學號: 113011139</div>
          <div class="chip">Email: example@email.com</div>
          <div class="chip">電話: 09xx-xxx-xxx</div>
        </div>
        <div class="actions">
          <button id="copyId">複製學號</button>
          <button id="download" class="btn-outline">下載履歷</button>
        </div>
      </div>
    </header>

    <main>
      <section>
        <h2>個人簡介</h2>
        <p>我是一位健康管理系的學生，熱衷於公共衛生與健康促進領域。希望能運用專業知識改善社區健康、提升生活品質，並持續學習醫療管理與健康政策相關技能。</p>

        <h2>學歷</h2>
        <ul>
          <li>亞洲大學 健康管理系（2023－至今）</li>
        </ul>

        <h2>實習與經驗</h2>
        <ul>
          <li>醫院行政實習助理 — 協助資料整理與健康宣導。</li>
          <li>社區健康促進活動志工 — 協助問卷調查與現場支援。</li>
        </ul>

        <h2>專案經驗</h2>
        <ul>
          <li>健康促進研究計畫 — 針對社區居民健康行為進行分析與建議。</li>
        </ul>
      </section>

      <aside>
        <h2>技能</h2>
        <div class="skill"><span>Microsoft Office</span><div class="bar"><i style="width:85%"></i></div></div>
        <div class="skill"><span>Excel資料分析</span><div class="bar"><i style="width:75%"></i></div></div>
        <div class="skill"><span>簡報與溝通能力</span><div class="bar"><i style="width:80%"></i></div></div>

        <h2>語言能力</h2>
        <ul>
          <li>中文（母語）</li>
          <li>英文（中級）</li>
        </ul>

        <h2>興趣</h2>
        <ul>
          <li>健康教育與宣導</li>
          <li>志工與社區服務</li>
          <li>運動與瑜伽</li>
        </ul>
      </aside>
    </main>

    <footer>
      © 2025 凌氏玉映．學號 113011139．此履歷由 ChatGPT 生成範例
    </footer>
  </div>

  <script>
    // 複製學號
    document.getElementById('copyId').addEventListener('click', () => {
      const id = '113011139';
      navigator.clipboard.writeText(id)
        .then(() => alert('學號已複製：' + id))
        .catch(() => alert('複製失敗，請手動複製'));
    });

    // 下載履歷
    document.getElementById('download').addEventListener('click', () => {
      const html = '<!doctype html>\\n' + document.documentElement.outerHTML;
      const blob = new Blob([html], {type: 'text/html'});
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = 'resume_113011139.html';
      a.click();
      URL.revokeObjectURL(url);
    });
  </script>
</body>
</html>
