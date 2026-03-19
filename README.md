# ukeducation.github.io
<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>英語教育中心 | 專業英語課程 | 閱讀・寫作・劍橋英檢・TED演講</title>
  <meta name="description" content="專業英語教育中心，提供【英語閱讀聊天班】、【英語寫作特訓班】、劍橋YLE、進階閱讀寫作、TED英語演講班、劍橋聆聽會話進階班等多樣化課程，幫助學員全面提升英語能力。"/>
  
  <style>
    :root {
      --primary: #2b6cb0;       /* 專業藍 */
      --primary-dark: #2c5282;
      --accent: #ecc94b;         /* 活潑黃 */
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
      padding: 6rem 0 5rem;
    }
    header h1 { font-size: 3rem; margin-bottom: 1rem; }
    header p  { font-size: 1.4rem; max-width: 800px; margin: 0 auto 2rem; opacity: 0.95; }

    .btn {
      display: inline-block;
      background: white;
      color: var(--primary);
      font-weight: 700;
      padding: 1rem 2.5rem;
      border-radius: 50px;
      text-decoration: none;
      font-size: 1.15rem;
      transition: all 0.3s;
      box-shadow: 0 6px 12px rgba(0,0,0,0.15);
    }
    .btn:hover { transform: translateY(-4px); box-shadow: 0 12px 20px rgba(0,0,0,0.2); }

    section { padding: 5rem 0; }
    h2 { text-align: center; font-size: 2.5rem; margin-bottom: 3rem; color: var(--primary-dark); }

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
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .course-card:hover { transform: translateY(-12px); box-shadow: 0 15px 30px rgba(0,0,0,0.12); }

    .course-img {
      width: 100%;
      height: 220px;
      object-fit: cover;
    }

    .course-content {
      padding: 1.8rem 1.5rem;
      text-align: center;
    }
    .course-content h3 {
      font-size: 1.5rem;
      margin-bottom: 1rem;
      color: var(--primary);
    }
    .course-content p { color: var(--gray); font-size: 1.05rem; }

    .advantages {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      text-align: center;
    }
    .adv-item h3 { color: var(--primary); margin: 1rem 0 0.8rem; }

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
      padding: 3rem 0;
      font-size: 0.95rem;
    }

    @media (max-width: 768px) {
      header h1 { font-size: 2.4rem; }
      header p  { font-size: 1.2rem; }
      h2 { font-size: 2rem; }
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <h1>專業英語教育中心</h1>
      <p>專注兒童與青少年英語能力全面培養<br>從閱讀理解、寫作邏輯到國際英檢與公開演說，幫助每位學員自信使用英語</p>
      <a href="#courses" class="btn">探索適合您的課程 →</a>
    </div>
  </header>

  <section id="courses">
    <div class="container">
      <h2>熱門課程介紹</h2>
      <div class="courses-grid">

        <div class="course-card">
          <img src="https://wpcdn.us-east-1.vip.tn-cloud.net/www.tulsakids.com/content/uploads/2021/11/r/z/gettyimages-486325400-1024x683.jpg" alt="英語閱讀聊天班" class="course-img">
          <div class="course-content">
            <h3>英語閱讀聊天班</h3>
            <p>透過精選優質英文繪本與章節書，培養閱讀興趣與理解力；小組討論分享觀點，提升口語表達與批判思考能力。適合喜愛故事與互動的學員。</p>
          </div>
        </div>

        <div class="course-card">
          <img src="https://instructionalempowerment.com/wp-content/uploads/2024/12/2-girls-partner-work-bow_800.jpg" alt="英語寫作特訓班" class="course-img">
          <div class="course-content">
            <h3>英語寫作特訓班</h3>
            <p>從句子結構到段落組織，再到議論文、故事創作，系統訓練寫作技巧；提供詳細批改與一對一指導，幫助學員寫出邏輯清晰、內容豐富的英文作文。</p>
          </div>
        </div>

        <div class="course-card">
          <img src="https://i.ytimg.com/vi/2D1zBs0ghy4/maxresdefault.jpg" alt="劍橋英檢YLE" class="course-img">
          <div class="course-content">
            <h3>劍橋英檢 YLE</h3>
            <p>針對劍橋兒童英語測驗（Starters / Movers / Flyers）量身設計課程，涵蓋聽說讀寫全方面模擬練習與應試技巧，幫助孩子自信取得國際認證。</p>
          </div>
        </div>

        <div class="course-card">
          <img src="https://www.colorincolorado.org/sites/default/files/styles/share_image/public/main/Teaching-ELLs-sm.jpg?itok=-QkOD8eO" alt="劍橋閱讀與寫作-進階班" class="course-img">
          <div class="course-content">
            <h3>劍橋閱讀與寫作 - 進階班</h3>
            <p>針對 KET / PET 等劍橋主級考試閱讀與寫作部分深度訓練，提升長篇理解、資訊轉換與正式寫作能力，適合準備進階英檢的學員。</p>
          </div>
        </div>

        <div class="course-card">
          <img src="https://pi.tedcdn.com/r/pe.tedcdn.com/images/ted/3afd7962e92217458ad4e0ec5e0e03f32e9d02ca_1600x1200.jpg?u%5Br%5D=2&u%5Bs%5D=0.5&u%5Ba%5D=0.8&u%5Bt%5D=0.03&quality=80&w=3840" alt="TED英語演講班" class="course-img">
          <div class="course-content">
            <h3>TED英語演講班</h3>
            <p>學習TED講者技巧：故事結構、肢體語言、語調控制與簡報設計；每位學員親自準備並上台演講，培養公開表達自信與影響力。</p>
          </div>
        </div>

        <div class="course-card">
          <img src="https://textinspector.com/wp-content/uploads/2023/09/inclusive-practices-in-english-language-teaching.jpg" alt="劍橋聆聽會話-進階班" class="course-img">
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
          <h3>專業師資團隊</h3>
          <p>具劍橋認證與多年教學經驗的外師與中師搭配</p>
        </div>
        <div class="adv-item">
          <h3>小班制教學</h3>
          <p>每班最多8-10人，確保個別關注與充分互動</p>
        </div>
        <div class="adv-item">
          <h3>客製化學習路徑</h3>
          <p>入學評估後提供個人化進度建議與追蹤</p>
        </div>
        <div class="adv-item">
          <h3>成果可見</h3>
          <p>定期報告、模擬考與作品集，清楚展現進步</p>
        </div>
      </div>
    </div>
  </section>

  <section class="cta-section">
    <div class="container">
      <h2>立即為孩子預約免費程度評估</h2>
      <p style="font-size:1.3rem; max-width:800px; margin:1.5rem auto 2.5rem;">
        了解適合課程、師資陣容與最新班級時間表
      </p>
      <a href="https://您的LineID或報名連結" class="btn" style="background:white; color:var(--primary);">免費諮詢 & 報名 →</a>
      <p style="margin-top:1.8rem; font-size:1.1rem;">名額有限，建議盡早預約</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>© 2026 英語教育中心 | 澳門 | 專業英語培訓機構 | 詳情請聯繫我們</p>
    </div>
  </footer>

</body>
</html>
