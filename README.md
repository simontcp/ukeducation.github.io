<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>英語教育中心 | 專業英語課程 | 閱讀・寫作・劍橋英檢・TED演講</title>
  <meta name="description" content="專業英語教育中心，提供英語閱讀聊天班、英語寫作特訓班、劍橋YLE、進階閱讀寫作、TED英語演講班、劍橋聆聽會話進階班等多樣化課程，幫助學員全面提升英語能力。"/>
  
  <style>
    :root {
      --primary: #2b6cb0;       /* 專業藍 */
      --primary-dark: #2c5282;
      --accent: #ecc94b;         /* 活潑黃，可選用作重點色 */
      --text: #2d3748;
      --light: #f7fafc;
      --gray: #718096;
    }

    * { margin:0; padding:0; box-sizing:border-box; }
    body {
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
      line-height: 1.6;
      color: var(--text);
      background: var(--light);
    }
    .container { max-width: 1200px; margin: 0 auto; padding: 0 1.5rem; }

    header {
      background: linear-gradient(to bottom right, var(--primary), var(--primary-dark));
      color: white;
      text-align: center;
      padding: 7rem 0 5rem;
    }
    header h1 { font-size: 3.2rem; margin-bottom: 1.2rem; }
    header p  { font-size: 1.4rem; max-width: 800px; margin: 0 auto 2.5rem; opacity: 0.95; }

    .btn {
      display: inline-block;
      background: white;
      color: var(--primary);
      font-weight: 700;
      padding: 1.1rem 2.8rem;
      border-radius: 50px;
      text-decoration: none;
      font-size: 1.2rem;
      transition: all 0.3s ease;
      box-shadow: 0 6px 12px rgba(0,0,0,0.15);
    }
    .btn:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 20px rgba(0,0,0,0.2);
    }

    section { padding: 6rem 0; }
    h2 { text-align: center; font-size: 2.6rem; margin-bottom: 3.5rem; color: var(--primary-dark); }

    .courses-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
      gap: 2.5rem;
    }

    .course-card {
      background: white;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 6px 20px rgba(0,0,0,0.08);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .course-card:hover {
      transform: translateY(-12px);
      box-shadow: 0 15px 30px rgba(0,0,0,0.12);
    }

    .course-img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }

    .course-content {
      padding: 2rem 1.8rem;
      text-align: center;
    }
    .course-content h3 {
      font-size: 1.6rem;
      margin-bottom: 1rem;
      color: var(--primary);
    }
    .course-content p {
      color: var(--gray);
      font-size: 1.08rem;
    }

    .advantages {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2.5rem;
      text-align: center;
    }
    .adv-item h3 {
      color: var(--primary);
      margin: 1.2rem 0 0.8rem;
      font-size: 1.4rem;
    }

    .cta-section {
      background: var(--primary);
      color: white;
      text-align: center;
    }
    .cta-section h2 { color: white; }

    footer {
      background: #1a202c;
      color: #a0aec0;
      text-align: center;
      padding: 3.5rem 0;
      font-size: 0.98rem;
    }

    @media (max-width: 768px) {
      header h1 { font-size: 2.5rem; }
      header p  { font-size: 1.25rem; }
      h2 { font-size: 2.2rem; }
      section { padding: 4rem 0; }
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <h1>專業英語教育中心</h1>
      <p>專注兒童、青少年與成人英語能力全面培養<br>從閱讀興趣、寫作邏輯到國際英檢與公開演說，幫助每位學員自信運用英語</p>
      <a href="#courses" class="btn">探索課程 →</a>
    </div>
  </header>

  <section id="courses">
    <div class="container">
      <h2>核心課程介紹</h2>
      <div class="courses-grid">

        <div class="course-card">
          <img src="https://images.unsplash.com/photo-1456513080510-7bf3a84b82f8?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" alt="英語閱讀聊天班" class="course-img">
          <div class="course-content">
            <h3>英語閱讀聊天班</h3>
            <p>精選優質英文繪本與章節書，培養深度閱讀興趣與理解力；小組討論分享觀點，提升口語表達與批判思考能力。適合喜愛故事與互動的學員。</p>
          </div>
        </div>

        <div class="course-card">
          <img src="https://images.unsplash.com/photo-1455390582262-044cdead277a?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" alt="英語寫作特訓班" class="course-img">
          <div class="course-content">
            <h3>英語寫作特訓班</h3>
            <p>從基礎句子到進階議論文、創意故事，系統訓練寫作結構與邏輯；提供詳細批改與個別指導，幫助學員寫出清晰、有說服力的英文作文。</p>
          </div>
        </div>

        <div class="course-card">
          <img src="https://images.unsplash.com/photo-1581287053822-fd7bf4f2c67e?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" alt="劍橋英檢YLE" class="course-img">
          <div class="course-content">
            <h3>劍橋英檢 YLE</h3>
            <p>針對 Starters / Movers / Flyers 量身設計，涵蓋聽說讀寫全方面模擬練習與應試技巧，幫助孩子自信取得劍橋兒童英語國際認證。</p>
          </div>
        </div>

        <div class="course-card">
          <img src="https://images.unsplash.com/photo-1503676260728-1c00da094a0b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" alt="劍橋閱讀與寫作-進階班" class="course-img">
          <div class="course-content">
            <h3>劍橋閱讀與寫作 - 進階班</h3>
            <p>針對 KET / PET 等進階劍橋考試閱讀與寫作部分深度訓練，提升長篇理解、資訊提取與正式寫作能力，適合準備更高級英檢的學員。</p>
          </div>
        </div>

        <div class="course-card">
          <img src="https://images.unsplash.com/photo-1557804506-669a67965ba0?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" alt="TED英語演講班" class="course-img">
          <div class="course-content">
            <h3>TED英語演講班</h3>
            <p>學習世界級 TED 講者技巧：故事架構、肢體語言、語調控制與簡報設計；每位學員親自準備並上台演講，培養公開表達自信與影響力。</p>
          </div>
        </div>

        <div class="course-card">
          <img src="https://images.unsplash.com/photo-1524178232363-1fb2b075b655?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" alt="劍橋聆聽會話-進階班" class="course-img">
          <div class="course-content">
            <h3>劍橋聆聽會話 - 進階班</h3>
            <p>強化真實情境聽力理解與流利對話能力，針對劍橋聽說考試題型密集練習；小班互動教學，確保每位學員獲得充分口語實戰機會。</p>
          </div>
        </div>

      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <h2>我們的教學優勢</h2>
      <div class="advantages">
        <div class="adv-item">
          <h3>專業雙語師資</h3>
          <p>具劍橋認證與豐富教學經驗的外籍與本地教師搭配授課</p>
        </div>
        <div class="adv-item">
          <h3>小班精緻教學</h3>
          <p>每班限 6–10 人，確保個別關注與充分互動練習</p>
        </div>
        <div class="adv-item">
          <h3>客製化學習計畫</h3>
          <p>入學程度評估後，提供個人化進度建議與持續追蹤</p>
        </div>
        <div class="adv-item">
          <h3>成果透明可見</h3>
          <p>定期能力報告、模擬考試與作品集，清楚展現學習進步</p>
        </div>
      </div>
    </div>
  </section>

  <section class="cta-section">
    <div class="container">
      <h2>立即為孩子/自己預約免費程度評估</h2>
      <p style="font-size:1.35rem; max-width:800px; margin:2rem auto 3rem;">
        了解最適合的課程、師資陣容與最新開班時間表
      </p>
      <a href="https://您的Line官方帳號或報名連結" class="btn" style="background:white; color:var(--primary);">免費諮詢 & 報名 →</a>
      <p style="margin-top:2rem; font-size:1.15rem;">名額有限，建議盡早預約</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>© 2026 英語教育中心 | 澳門 | 專業英語培訓機構<br>聯絡我們 | 隱私政策 | 詳情請透過 Line 或電話查詢</p>
    </div>
  </footer>

</body>
</html>
