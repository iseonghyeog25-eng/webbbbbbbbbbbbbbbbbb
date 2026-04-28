<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover" />
  <title>연패따 - 연예인 패션 따라잡기</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Apple SD Gothic Neo', 'Noto Sans KR', -apple-system, BlinkMacSystemFont, sans-serif;
      background: #e9eaed;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      min-height: 100vh;
      color: #1d1d1f;
    }
    .app {
      width: 100%;
      max-width: 480px;
      background: #ffffff;
      box-shadow: 0 0 20px rgba(0,0,0,0.05);
      min-height: 100vh;
      position: relative;
      display: flex;
      flex-direction: column;
    }
    .mobile-header {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(255,255,255,0.92);
      backdrop-filter: blur(15px);
      -webkit-backdrop-filter: blur(15px);
      padding: 12px 16px 0;
      border-bottom: 1px solid #f0f0f0;
    }
    .topbar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 12px;
    }
    .icon-btn {
      background: none;
      border: none;
      font-size: 22px;
      cursor: pointer;
      color: #1d1d1f;
      width: 36px;
      height: 36px;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: 0.2s;
    }
    .icon-btn:active {
      opacity: 0.5;
      transform: scale(0.95);
    }
    .logo {
      font-size: 22px;
      font-weight: 800;
      letter-spacing: -1px;
      background: linear-gradient(135deg, #ff3b5c, #ff6b7f);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      text-transform: uppercase;
    }
    .search-box {
      margin-bottom: 12px;
    }
    .search-box input {
      width: 100%;
      padding: 10px 16px;
      background: #f5f5f7;
      border: none;
      border-radius: 25px;
      font-size: 15px;
      outline: none;
      color: #1d1d1f;
      transition: 0.2s;
    }
    .search-box input:focus {
      background: #e8e8ed;
    }
    .search-box input::placeholder {
      color: #8e8e93;
    }
    .category-scroll {
      display: flex;
      gap: 8px;
      overflow-x: auto;
      padding-bottom: 12px;
      white-space: nowrap;
      scrollbar-width: none;
    }
    .category-scroll::-webkit-scrollbar {
      display: none;
    }
    .category-chip {
      flex-shrink: 0;
      padding: 7px 16px;
      border-radius: 20px;
      border: 1px solid #e5e5ea;
      background: #fff;
      font-size: 14px;
      font-weight: 500;
      cursor: pointer;
      transition: 0.2s;
      color: #3a3a3c;
    }
    .category-chip.active {
      background: #1d1d1f;
      color: #fff;
      border-color: #1d1d1f;
      font-weight: 600;
    }
    .content {
      flex: 1;
      padding: 16px;
      padding-bottom: 90px;
      display: flex;
      flex-direction: column;
      gap: 24px;
    }
    .tab-section {
      display: none;
      flex-direction: column;
      gap: 24px;
    }
    .tab-section.active {
      display: flex;
    }
    .hero-banner {
      position: relative;
      border-radius: 16px;
      overflow: hidden;
      height: 220px;
      background: linear-gradient(135deg, #2c2c2e, #48484a);
      display: flex;
      align-items: flex-end;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    }
    .hero-banner::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: url('https://via.placeholder.com/400x220/1d1d1f/FFFFFF?text=Celebrity+Style') center/cover no-repeat;
      opacity: 0.55;
    }
    .hero-text {
      position: relative;
      z-index: 2;
      padding: 20px;
      color: #fff;
    }
    .hero-badge {
      background: #ff3b5c;
      padding: 4px 12px;
      border-radius: 20px;
      font-size: 12px;
      font-weight: 700;
      margin-bottom: 8px;
      display: inline-block;
    }
    .hero-text h2 {
      font-size: 22px;
      font-weight: 800;
      line-height: 1.3;
      text-shadow: 0 2px 4px rgba(0,0,0,0.3);
    }
    .hero-text p {
      font-size: 14px;
      opacity: 0.9;
      margin-top: 4px;
    }
    .section-head {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: -8px;
    }
    .section-head h3 {
      font-size: 18px;
      font-weight: 800;
    }
    .style-feed {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    .style-card {
      background: #fff;
      border-radius: 16px;
      overflow: hidden;
      box-shadow: 0 2px 12px rgba(0,0,0,0.04);
      border: 1px solid #f0f0f0;
      transition: 0.2s;
    }
    .style-card:active {
      transform: scale(0.99);
    }
    .thumb-wrap {
      position: relative;
      overflow: hidden;
      aspect-ratio: 4 / 5;
      background: #f2f2f2;
    }
    .thumb-wrap img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }
    .tag-overlay {
      position: absolute;
      bottom: 12px;
      left: 12px;
      right: 12px;
      display: flex;
      gap: 8px;
      flex-wrap: wrap;
      pointer-events: none;
    }
    .tag-chip {
      background: rgba(0,0,0,0.65);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      color: #fff;
      border: none;
      padding: 8px 14px;
      border-radius: 20px;
      font-size: 13px;
      font-weight: 600;
      cursor: pointer;
      pointer-events: auto;
      transition: 0.2s;
      display: flex;
      align-items: center;
      gap: 4px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      text-decoration: none;
    }
    .tag-chip::before {
      content: '📍';
      font-size: 12px;
    }
    .tag-chip:active {
      background: rgba(0,0,0,0.85);
      transform: scale(0.95);
    }
    .card-detail {
      padding: 16px;
    }
    .card-detail h4 {
      font-size: 16px;
      font-weight: 700;
      margin-bottom: 4px;
      display: flex;
      align-items: center;
      gap: 6px;
    }
    .verified-badge {
      background: #007aff;
      color: #fff;
      font-size: 10px;
      padding: 2px 6px;
      border-radius: 10px;
      font-weight: 500;
    }
    .stats {
      display: flex;
      align-items: center;
      gap: 14px;
      font-size: 13px;
      color: #8e8e93;
      font-weight: 500;
      margin-top: 8px;
      flex-wrap: wrap;
    }
    .stats span {
      display: flex;
      align-items: center;
      gap: 4px;
      cursor: pointer;
    }
    .like-btn {
      color: #8e8e93;
      transition: 0.2s;
      user-select: none;
    }
    .like-btn.liked {
      color: #ff3b5c;
    }
    .bottom-nav {
      position: fixed;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 100%;
      max-width: 480px;
      background: rgba(255,255,255,0.94);
      backdrop-filter: blur(20px);
      -webkit-backdrop-filter: blur(20px);
      border-top: 1px solid #e5e5ea;
      display: flex;
      justify-content: space-around;
      padding: 8px 12px 18px;
      z-index: 100;
      box-shadow: 0 -4px 15px rgba(0,0,0,0.02);
    }
    .nav-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      background: none;
      border: none;
      color: #8e8e93;
      font-size: 21px;
      cursor: pointer;
      transition: 0.2s;
      gap: 2px;
    }
    .nav-item small {
      font-size: 10px;
      font-weight: 500;
    }
    .nav-item.active {
      color: #ff3b5c;
      font-weight: 700;
    }
    .explore-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
    }
    .explore-card {
      background: #f8f8f8;
      border-radius: 16px;
      text-align: center;
      padding: 12px 8px;
      cursor: pointer;
      transition: 0.2s;
    }
    .explore-card:active {
      background: #e5e5ea;
    }
    .explore-card img {
      width: 72px;
      height: 72px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 8px;
      background: #ddd;
    }
    .contact-box {
      background: #f8f8f8;
      border-radius: 20px;
      padding: 24px;
      display: flex;
      flex-direction: column;
      gap: 18px;
    }
    .contact-item {
      display: flex;
      align-items: center;
      gap: 14px;
      font-size: 16px;
      padding: 12px;
      background: #fff;
      border-radius: 14px;
      text-decoration: none;
      color: #1d1d1f;
      font-weight: 500;
    }
    .contact-item span {
      font-size: 24px;
    }
    .empty-message {
      text-align: center;
      color: #8e8e93;
      padding: 40px 0;
    }
  </style>
</head>
<body>
  <div class="app">
    <header class="mobile-header">
      <div class="topbar">
        <button class="icon-btn" aria-label="메뉴">☰</button>
        <h1 class="logo">연패따</h1>
        <div class="top-actions">
          <button class="icon-btn" aria-label="알림">🔔</button>
          <button class="icon-btn" aria-label="메시지">💬</button>
        </div>
      </div>
      <div class="search-box">
        <input type="text" id="searchInput" placeholder="연예인, 스타일, 아이템 검색" />
      </div>
      <div class="category-scroll" id="categoryScroll">
        <button class="category-chip active" data-category="전체">전체</button>
        <button class="category-chip" data-category="데일리룩">데일리룩</button>
        <button class="category-chip" data-category="공항패션">공항패션</button>
        <button class="category-chip" data-category="무대의상">무대의상</button>
        <button class="category-chip" data-category="시상식">시상식</button>
      </div>
    </header>

    <main class="content">
      <div class="tab-section active" id="feedTab">
        <section class="hero-banner">
          <div class="hero-text">
            <span class="hero-badge">🔥 실시간 인기</span>
            <h2>연예인 착장 그대로<br>연패따 하세요</h2>
            <p>아이템 정보부터 구매 링크까지 한 번에</p>
          </div>
        </section>
        <div class="section-head">
          <h3>📸 스타일 피드</h3>
        </div>
        <section class="style-feed" id="styleFeed"></section>
      </div>

      <div class="tab-section" id="exploreTab">
        <div class="section-head">
          <h3>🌟 연예인 탐색</h3>
        </div>
        <div class="search-box" style="margin-top:-8px;">
          <input type="text" id="exploreSearch" placeholder="연예인 이름 검색" />
        </div>
        <div class="explore-grid" id="exploreGrid"></div>
      </div>

      <div class="tab-section" id="contactTab">
        <div class="section-head">
          <h3>📬 문의 / 연결</h3>
        </div>
        <div class="contact-box">
          <a href="https://open.kakao.com/o/example" target="_blank" class="contact-item">
            <span>💬</span> 카카오톡 오픈채팅
          </a>
          <a href="mailto:yeonpatta@style.com" class="contact-item">
            <span>✉️</span> yeonpatta@style.com
          </a>
          <a href="https://instagram.com/yeonpatta_official" target="_blank" class="contact-item">
            <span>📸</span> @yeonpatta_official
          </a>
          <p style="color:#8e8e93; font-size:13px; text-align:center; margin-top:4px;">원하는 연예인 요청도 환영해요!</p>
        </div>
      </div>

      <div class="tab-section" id="wishlistTab">
        <div class="section-head">
          <h3>❤️ 내가 찜한 스타일</h3>
        </div>
        <div id="wishlistContainer" class="style-feed"></div>
      </div>

      <div class="tab-section" id="myTab">
        <div class="section-head">
          <h3>👤 마이 페이지</h3>
        </div>
        <div style="background:#f8f8f8; border-radius:20px; padding:24px; text-align:center;">
          <img src="https://via.placeholder.com/80/ff3b5c/FFFFFF?text=MY" style="border-radius:50%; margin-bottom:12px;" alt="profile" />
          <p style="font-weight:700; font-size:18px;">스타일러</p>
          <p style="color:#8e8e93; font-size:14px;">연패따와 함께 스타일 완성</p>
        </div>
      </div>
    </main>

    <nav class="bottom-nav">
      <button class="nav-item active" data-tab="feedTab"><span>⌂</span><small>피드</small></button>
      <button class="nav-item" data-tab="exploreTab"><span>🔍</span><small>탐색</small></button>
      <button class="nav-item" data-tab="contactTab"><span>💬</span><small>문의</small></button>
      <button class="nav-item" data-tab="wishlistTab"><span>♡</span><small>찜 목록</small></button>
      <button class="nav-item" data-tab="myTab"><span>◡̈</span><small>MY</small></button>
    </nav>
  </div>

  <script>
    (function() {
      // --- 데이터 (수정 완료된 배열) ---
      const styleData = [
        {
          id: 1,
          celebrity: '이나경',
          category: '데일리룩',
          title: '느좋녀 이나경의 데일리룩은?',
          image: 'https://postfiles.pstatic.net/.../IMG_4754.JPG?type=w773',
          items: [
            { name: '상의 정보', link: 'https://m.musinsa.com/.../beloved-ribbon-blouse' },
            { name: '바지 정보', link: 'https://m.musinsa.com/.../cat-washing-denim-pants' }
          ],
          likes: 120,
          comments: 15,
          saves: 340,
          liked: false
        },
        {
          id: 2,
          celebrity: '키키 이솔',
          category: '데일리룩',
          title: '콘서트 비하인드 레트로 무드 티셔츠',
          image: 'https://postfiles.pstatic.net/.../HGl2EFfbAAAOybU.jpg?type=w773',
          items: [
            { name: '상의 정보', link: 'https://m.musinsa.com/.../cross-patch-lace-sleeve' }
          ],
          likes: 85,
          comments: 8,
          saves: 210,
          liked: false
        }
      ];

      const celebrities = ['이나경', '키키 이솔'];

      // --- 상태 ---
      let currentTab = 'feedTab';
      let activeCategory = '전체';
      const wishlist = [];

      const feedContainer = document.getElementById('styleFeed');
      const wishlistContainer = document.getElementById('wishlistContainer');
      const exploreGrid = document.getElementById('exploreGrid');
      const categoryChips = document.querySelectorAll('.category-chip');
      const navItems = document.querySelectorAll('.nav-item');
      const tabSections = document.querySelectorAll('.tab-section');
      const searchInput = document.getElementById('searchInput');
      const exploreSearch = document.getElementById('exploreSearch');

      // 아이템 태그 클릭 시 링크 이동
      function handleTagClick(itemName, link) {
        alert(`"${itemName}" 링크로 이동합니다.\n(실제 서비스에서는 ${link || '상세 페이지'} 연결)`);
        // 실제 연결 시 window.location.href = link; 사용
      }

      function renderFeed(filterCategory = '전체', searchTerm = '') {
        let filtered = styleData.filter(item => {
          const matchCat = filterCategory === '전체' || item.category === filterCategory;
          const searchLower = searchTerm.toLowerCase();
          const matchSearch = !searchTerm || 
            item.celebrity.toLowerCase().includes(searchLower) ||
            item.title.toLowerCase().includes(searchLower) ||
            item.items.some(i => i.name.toLowerCase().includes(searchLower));
          return matchCat && matchSearch;
        });

        if (filtered.length === 0) {
          feedContainer.innerHTML = '<p class="empty-message">해당 스타일이 없어요 🔍</p>';
          return;
        }

        feedContainer.innerHTML = filtered.map(item => {
          const isLiked = wishlist.includes(item.id);
          return `
            <article class="style-card" data-id="${item.id}">
              <div class="thumb-wrap">
                <img src="${item.image}" alt="${item.celebrity}" loading="lazy" />
                <div class="tag-overlay">
                  ${item.items.map(it => 
                    `<button class="tag-chip" onclick="window.handleTagClick('${it.name}', '${it.link}')">${it.name}</button>`
                  ).join('')}
                </div>
              </div>
              <div class="card-detail">
                <h4>${item.celebrity} <span class="verified-badge">공식</span></h4>
                <p>${item.title} · 총 ${item.items.length}개 아이템</p>
                <div class="stats">
                  <span class="like-btn ${isLiked ? 'liked' : ''}" data-id="${item.id}">
                    ${isLiked ? '❤️' : '🤍'} ${item.likes + (isLiked ? 1 : 0)}
                  </span>
                  <span>💬 ${item.comments}</span>
                  <span>🔖 ${item.saves}</span>
                </div>
              </div>
            </article>
          `;
        }).join('');

        document.querySelectorAll('.like-btn').forEach(btn => {
          btn.addEventListener('click', function(e) {
            e.stopPropagation();
            const id = parseInt(this.dataset.id);
            toggleWishlist(id);
            renderFeed(activeCategory, searchInput.value);
            renderWishlist();
          });
        });
      }

      function renderWishlist() {
        if (wishlist.length === 0) {
          wishlistContainer.innerHTML = '<p class="empty-message">찜한 스타일이 없습니다 💔</p>';
          return;
        }
        const wishedItems = styleData.filter(item => wishlist.includes(item.id));
        wishlistContainer.innerHTML = wishedItems.map(item => `
          <article class="style-card">
            <div class="thumb-wrap">
              <img src="${item.image}" alt="${item.celebrity}" loading="lazy" />
            </div>
            <div class="card-detail">
              <h4>${item.celebrity}</h4>
              <p>${item.title}</p>
              <button class="tag-chip" data-id="${item.id}" style="margin-top:8px; background:#ff3b5c; color:white;">찜 해제</button>
            </div>
          </article>
        `).join('');

        document.querySelectorAll('#wishlistContainer .tag-chip').forEach(btn => {
          btn.addEventListener('click', function() {
            const id = parseInt(this.dataset.id);
            toggleWishlist(id);
            renderFeed(activeCategory, searchInput.value);
            renderWishlist();
          });
        });
      }

      function renderExplore(filterTerm = '') {
        const filtered = celebrities.filter(c => c.toLowerCase().includes(filterTerm.toLowerCase()));
        exploreGrid.innerHTML = filtered.map(c => `
          <div class="explore-card">
            <img src="https://via.placeholder.com/72/cccccc/333?text=${c.charAt(0)}" alt="${c}" />
            <div style="font-weight:600; font-size:14px;">${c}</div>
          </div>
        `).join('');
      }

      function toggleWishlist(id) {
        const index = wishlist.indexOf(id);
        if (index > -1) {
          wishlist.splice(index, 1);
        } else {
          wishlist.push(id);
        }
      }

      function switchTab(tabId) {
        currentTab = tabId;
        tabSections.forEach(s => s.classList.remove('active'));
        document.getElementById(tabId).classList.add('active');
        navItems.forEach(n => n.classList.remove('active'));
        document.querySelector(`.nav-item[data-tab="${tabId}"]`).classList.add('active');

        if (tabId === 'wishlistTab') renderWishlist();
        if (tabId === 'exploreTab') renderExplore(exploreSearch.value);
      }

      window.handleTagClick = handleTagClick;

      navItems.forEach(btn => {
        btn.addEventListener('click', () => switchTab(btn.dataset.tab));
      });

      categoryChips.forEach(chip => {
        chip.addEventListener('click', function() {
          categoryChips.forEach(c => c.classList.remove('active'));
          this.classList.add('active');
          activeCategory = this.dataset.category;
          if (currentTab === 'feedTab') renderFeed(activeCategory, searchInput.value);
        });
      });

      searchInput.addEventListener('input', function(e) {
        if (currentTab === 'feedTab') renderFeed(activeCategory, e.target.value);
      });

      exploreSearch.addEventListener('input', function(e) {
        renderExplore(e.target.value);
      });

      // 초기 렌더
      renderFeed();
      renderExplore();
      renderWishlist();
    })();
  </script>
</body>
</html>
