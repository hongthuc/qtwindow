<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>QTWINDOW.COM | Công Ty TNHH Thương Mại Và Xây Dựng Quang Tấn - Cửa Nhôm Xingfa Đà Nẵng</title>
  <meta name="description" content="Công Ty TNHH Thương Mại Và Xây Dựng Quang Tấn (qtwindow.com) - Chuyên sản xuất, thi công cửa nhôm Xingfa, cửa kính cường lực, cầu thang kính, phòng tắm kính, kính ốp bếp uy tín tại 82 Đặng Phúc Thông, An Khê, Đà Nẵng. Hotline: 0905.481.481." />

  <!-- Open Graph & Thumbnail chia sẻ link trang web bằng Logo công ty -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="QTWINDOW.COM - Quang Tấn Đà Nẵng" />
  <meta property="og:url" content="https://qtwindow.com" />
  <meta property="og:title" content="CÔNG TY TNHH TM & XD QUANG TẤN - Cửa Nhôm Xingfa Đà Nẵng | qtwindow.com" />
  <meta property="og:description" content="Chuyên sản xuất & lắp đặt Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cầu thang kính, Phòng tắm kính, Kính ốp bếp tại Đà Nẵng. Địa chỉ: 82 Đặng Phúc Thông, P. An Khê, TP Đà Nẵng. SĐT: 0905.481.481." />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk" />
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk" />
  <meta property="og:image:alt" content="Logo Công Ty TNHH Thương Mại Và Xây Dựng Quang Tấn - qtwindow.com" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="QTWINDOW.COM - Cửa Nhôm Xingfa Cao Cấp Quang Tấn Đà Nẵng" />
  <meta name="twitter:description" content="Sản xuất & lắp đặt trực tiếp tại xưởng 82 Đặng Phúc Thông, An Khê, Đà Nẵng. Hotline: 0905.481.481." />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk" />
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk" />

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              50: '#eff6ff',
              100: '#dbeafe',
              200: '#bfdbfe',
              500: '#1d5fa7',
              600: '#0f4c8a',
              700: '#0b3c6f',
              800: '#082d54',
              900: '#051e3a',
            },
            accent: {
              500: '#e02424',
              600: '#c81e1e',
              700: '#9b1c1c',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* ==========================================================================
       CẤU HÌNH CHUNG CHỐNG TRÀN VIỀN & CHUẨN BỐ CỤC FLATSOME UX BUILDER
       ========================================================================== */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
    }

    body {
      font-family: 'Inter', sans-serif;
      color: #1e293b;
      background-color: #f8fafc;
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
    }

    /* Chiều ngang giao diện trên máy tính bằng đúng 95% kích thước màn hình */
    .qt-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 1024px) {
      .qt-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tiêu đề Section chuẩn Flatsome UX Builder ([title style="center"]) */
    .ux-section-title {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 14px;
      margin-bottom: 1.5rem;
      text-align: center;
    }

    .ux-section-title::before,
    .ux-section-title::after {
      content: "";
      flex: 1;
      height: 2px;
      background: linear-gradient(90deg, rgba(15, 76, 138, 0.12), rgba(15, 76, 138, 0.35));
      max-width: 140px;
    }

    .ux-section-title::after {
      background: linear-gradient(90deg, rgba(15, 76, 138, 0.35), rgba(15, 76, 138, 0.12));
    }

    /* Menu Desktop 1 hàng gọn đẹp, tuyệt đối không gãy chữ tên danh mục */
    .desktop-nav-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: flex-end;
      gap: 2px 4px;
      list-style: none;
      margin: 0;
      padding: 0;
    }

    .desktop-nav-item {
      position: relative;
      flex-shrink: 0;
    }

    .desktop-nav-link {
      display: inline-flex;
      align-items: center;
      gap: 3px;
      white-space: nowrap;
      font-size: 12px;
      font-weight: 600;
      color: #0f3c6e;
      padding: 8px 7px;
      border-radius: 6px;
      transition: all 0.2s ease;
      text-transform: uppercase;
      letter-spacing: -0.01em;
    }

    @media (min-width: 1280px) {
      .desktop-nav-link {
        font-size: 12.5px;
        padding: 8px 10px;
      }
    }

    @media (min-width: 1440px) {
      .desktop-nav-link {
        font-size: 13px;
        padding: 9px 12px;
      }
    }

    .desktop-nav-link:hover,
    .desktop-nav-item:hover > .desktop-nav-link {
      color: #c81e1e;
      background-color: #eff6ff;
    }

    /* Dropdown Flatsome sạch sẽ */
    .desktop-dropdown {
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 225px;
      background: #ffffff;
      border: 1px solid #e2e8f0;
      border-top: 3px solid #0f4c8a;
      border-radius: 0 0 8px 8px;
      box-shadow: 0 12px 28px rgba(15, 23, 42, 0.12);
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      z-index: 60;
      padding: 6px 0;
    }

    .desktop-nav-item:hover > .desktop-dropdown,
    .desktop-nav-item:focus-within > .desktop-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    .desktop-dropdown a {
      display: block;
      padding: 8px 14px;
      font-size: 13px;
      font-weight: 500;
      color: #334155;
      white-space: nowrap;
      transition: background 0.15s ease, color 0.15s ease;
    }

    .desktop-dropdown a:hover {
      background-color: #eff6ff;
      color: #0f4c8a;
      padding-left: 18px;
    }

    /* Banner tự trượt chuyên nghiệp: 2 slide kích thước bằng nhau tuyệt đối */
    .banner-viewport {
      position: relative;
      width: 100%;
      overflow: hidden;
      border-radius: 12px;
      background-color: #082d54;
    }

    .banner-track {
      display: grid;
      grid-template-columns: repeat(2, 100%);
      transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
      align-items: stretch;
    }

    .banner-slide {
      width: 100%;
      display: flex;
      align-items: center;
      position: relative;
      overflow: hidden;
    }

    /* Hiệu ứng ảnh zoom nhẹ kiểu Flatsome */
    .ux-img-zoom {
      transition: transform 0.45s ease;
    }

    .group:hover .ux-img-zoom {
      transform: scale(1.05);
    }

    /* Nút liên hệ nổi bật (Hotline, Zalo, Facebook) */
    @keyframes qtPulseRing {
      0% {
        transform: scale(0.95);
        box-shadow: 0 0 0 0 rgba(224, 36, 36, 0.55);
      }
      70% {
        transform: scale(1);
        box-shadow: 0 0 0 11px rgba(224, 36, 36, 0);
      }
      100% {
        transform: scale(0.95);
        box-shadow: 0 0 0 0 rgba(224, 36, 36, 0);
      }
    }

    .hotline-pulse {
      animation: qtPulseRing 2s infinite;
    }
  </style>
</head>
<body class="antialiased">

  <!-- ========================================================================
       HEADER FLATSOME: TOP BAR + LOGO GỌN NHỎ + DANH MỤC 1 HÀNG (KHÔNG NÚT GỌI NGAY)
       ======================================================================== -->
  <header class="sticky top-0 z-50 bg-white border-b border-slate-200 shadow-sm w-full">
    <!-- Top Bar thông tin gọn nhẹ -->
    <div class="bg-brand-800 text-slate-100 text-[11px] sm:text-xs py-1.5">
      <div class="qt-container flex flex-wrap items-center justify-between gap-2">
        <div class="flex items-center gap-3 min-w-0">
          <span class="truncate">📍 82 Đặng Phúc Thông, Phường An Khê, TP Đà Nẵng</span>
          <span class="hidden md:inline text-slate-300">|</span>
          <span class="hidden md:inline whitespace-nowrap">🕒 Làm việc: 07:30 - 18:00 (Thứ 2 - CN)</span>
        </div>
        <div class="hidden sm:flex items-center gap-3 whitespace-nowrap">
          <span>✉️ qtwindows.danang@gmail.com</span>
          <span class="text-slate-400">|</span>
          <span class="font-semibold text-white">qtwindow.com</span>
        </div>
      </div>
    </div>

    <!-- Thanh điều hướng chính (Không để nút gọi ngay tránh tràn viền) -->
    <div class="qt-container">
      <div class="flex items-center justify-between gap-3 py-2 lg:py-2.5">
        <!-- Logo Quang Tấn chỉnh gọn nhỏ lại -->
        <a href="#trang-chu" class="flex items-center gap-2 shrink-0 focus:outline-none" aria-label="QT Window - Công ty TNHH TM & XD Quang Tấn">
          <img
            src="https://lh3.googleusercontent.com/d/1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk"
            alt="Logo Quang Tấn Window - qtwindow.com"
            class="h-9 sm:h-10 lg:h-11 w-auto max-w-[140px] sm:max-w-[165px] object-contain rounded"
            onerror="handleDriveImgError(this, '1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk', 'QTWINDOW')"
          />
          <div class="hidden sm:flex flex-col leading-tight">
            <span class="text-brand-700 font-extrabold text-sm tracking-tight whitespace-nowrap">QTWINDOW</span>
            <span class="text-[10px] text-slate-500 font-medium whitespace-nowrap">Quang Tấn Đà Nẵng</span>
          </div>
        </a>

        <!-- Menu Desktop: Tất cả danh mục nằm gọn trên 1 hàng, không xuống dòng tên danh mục -->
        <nav class="hidden lg:block flex-1 min-w-0" aria-label="Danh mục chính">
          <ul class="desktop-nav-list">
            <li class="desktop-nav-item">
              <a href="#trang-chu" class="desktop-nav-link">Trang chủ</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#san-pham-noi-bat" class="desktop-nav-link">
                <span>Cửa nhôm xingfa</span>
                <svg class="w-3 h-3 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
              </a>
              <div class="desktop-dropdown">
                <a href="#san-pham-noi-bat" onclick="filterProducts('1-canh')">+ Cửa nhôm xingfa 1 cánh</a>
                <a href="#san-pham-noi-bat" onclick="filterProducts('2-canh')">+ Cửa nhôm xingfa 2 cánh</a>
                <a href="#san-pham-noi-bat" onclick="filterProducts('3-canh')">+ Cửa nhôm xingfa 3 cánh</a>
                <a href="#san-pham-noi-bat" onclick="filterProducts('4-canh')">+ Cửa nhôm xingfa 4 cánh</a>
                <a href="#san-pham-noi-bat" onclick="filterProducts('xep-truot')">+ Cửa nhôm xingfa 5 cánh</a>
              </div>
            </li>
            <li class="desktop-nav-item">
              <a href="#danh-muc-san-pham" onclick="openCategoryModal('cuakinh')" class="desktop-nav-link">Cửa kính cường lực</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#danh-muc-san-pham" class="desktop-nav-link">
                <span>Sản phẩm</span>
                <svg class="w-3 h-3 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
              </a>
              <div class="desktop-dropdown">
                <a href="#danh-muc-san-pham" onclick="openCategoryModal('xingfa')">+ Cửa nhôm xingfa</a>
                <a href="#danh-muc-san-pham" onclick="openCategoryModal('cuanhua')">+ Cửa nhựa lõi thép</a>
                <a href="#danh-muc-san-pham" onclick="openCategoryModal('cuatudong')">+ Cửa kính tự động</a>
                <a href="#danh-muc-san-pham" onclick="openCategoryModal('cauthang')">+ Cầu thang kính</a>
                <a href="#danh-muc-san-pham" onclick="openCategoryModal('kinhbep')">+ Kính ốp bếp</a>
                <a href="#danh-muc-san-pham" onclick="openCategoryModal('phongtam')">+ Phòng tắm kính</a>
              </div>
            </li>
            <li class="desktop-nav-item">
              <a href="#cong-trinh" class="desktop-nav-link">Công trình</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#bao-gia" class="desktop-nav-link">Báo giá</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
            </li>
            <li class="desktop-nav-item">
              <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
            </li>
          </ul>
        </nav>

        <!-- Nút mở menu trên điện thoại & máy tính bảng -->
        <button
          id="mobileMenuBtn"
          type="button"
          class="lg:hidden inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg border border-slate-200 bg-slate-50 text-brand-700 font-semibold text-xs hover:bg-brand-50 transition"
          aria-label="Mở danh mục trang web"
          aria-expanded="false"
        >
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
          <span>Danh mục</span>
        </button>
      </div>
    </div>
  </header>

  <!-- Mobile Navigation Drawer (Chuẩn Flatsome Off-Canvas Sidebar) -->
  <div id="mobileDrawerBackdrop" class="fixed inset-0 bg-slate-900/50 z-[70] hidden transition-opacity" onclick="closeMobileMenu()"></div>
  <aside id="mobileDrawer" class="fixed top-0 left-0 h-full w-[82%] max-w-[320px] bg-white z-[80] shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
    <div class="flex items-center justify-between px-4 py-3 border-b border-slate-200 bg-brand-700 text-white">
      <div class="flex items-center gap-2">
        <img
          src="https://lh3.googleusercontent.com/d/1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk"
          alt="Logo QT Window"
          class="h-8 w-auto bg-white rounded px-1 py-0.5 object-contain"
          onerror="handleDriveImgError(this, '1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk', 'QT')"
        />
        <span class="font-bold text-sm tracking-wide">QTWINDOW.COM</span>
      </div>
      <button type="button" onclick="closeMobileMenu()" class="p-1.5 rounded-lg hover:bg-white/15" aria-label="Đóng menu">
        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
    </div>

    <div class="overflow-y-auto flex-1 py-2">
      <ul class="divide-y divide-slate-100 text-sm font-semibold text-slate-800">
        <li><a href="#trang-chu" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-50 hover:text-brand-700">Trang chủ</a></li>
        <li><a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-50 hover:text-brand-700">Giới thiệu</a></li>

        <!-- Accordion: Cửa nhôm xingfa -->
        <li>
          <div class="flex items-center justify-between px-4 py-3">
            <a href="#san-pham-noi-bat" onclick="closeMobileMenu()" class="flex-1 hover:text-brand-700">Cửa nhôm xingfa</a>
            <button type="button" onclick="toggleSubmenu('mob-sub-xingfa', this)" class="p-1.5 rounded bg-slate-100 text-slate-600" aria-label="Mở rộng Cửa nhôm xingfa">
              <svg class="w-4 h-4 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M19 9l-7 7-7-7"/></svg>
            </button>
          </div>
          <ul id="mob-sub-xingfa" class="hidden bg-slate-50 border-t border-slate-100 text-xs font-medium text-slate-700">
            <li><a href="#san-pham-noi-bat" onclick="filterProducts('1-canh'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProducts('2-canh'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProducts('3-canh'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProducts('4-canh'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProducts('xep-truot'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </li>

        <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cuakinh'); closeMobileMenu();" class="block px-4 py-3 hover:bg-brand-50 hover:text-brand-700">Cửa kính cường lực</a></li>

        <!-- Accordion: Sản phẩm -->
        <li>
          <div class="flex items-center justify-between px-4 py-3">
            <a href="#danh-muc-san-pham" onclick="closeMobileMenu()" class="flex-1 hover:text-brand-700">Sản phẩm</a>
            <button type="button" onclick="toggleSubmenu('mob-sub-sp', this)" class="p-1.5 rounded bg-slate-100 text-slate-600" aria-label="Mở rộng Sản phẩm">
              <svg class="w-4 h-4 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M19 9l-7 7-7-7"/></svg>
            </button>
          </div>
          <ul id="mob-sub-sp" class="hidden bg-slate-50 border-t border-slate-100 text-xs font-medium text-slate-700">
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('xingfa'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Cửa nhôm xingfa</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cuanhua'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cuatudong'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cauthang'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Cầu thang kính</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('kinhbep'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Kính ốp bếp</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('phongtam'); closeMobileMenu();" class="block pl-8 pr-4 py-2.5 hover:text-brand-700">+ Phòng tắm kính</a></li>
          </ul>
        </li>

        <li><a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-50 hover:text-brand-700">Công trình</a></li>
        <li><a href="#bao-gia" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-50 hover:text-brand-700">Báo giá</a></li>
        <li><a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-50 hover:text-brand-700">Tin tức</a></li>
        <li><a href="#lien-he" onclick="closeMobileMenu()" class="block px-4 py-3 hover:bg-brand-50 hover:text-brand-700">Liên hệ</a></li>
      </ul>
    </div>

    <div class="p-4 border-t border-slate-200 bg-slate-50 text-xs text-slate-600 space-y-1">
      <p class="font-bold text-brand-700">CÔNG TY TNHH TM & XD QUANG TẤN</p>
      <p>📍 82 Đặng Phúc Thông, P. An Khê, TP Đà Nẵng</p>
      <p>📞 Hotline: <a href="tel:0905481481" class="font-bold text-accent-600">0905.481.481</a></p>
    </div>
  </aside>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- ======================================================================
         UX BUILDER SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP BẰNG NHAU
         - Hình ảnh và chữ nằm hoàn toàn trong banner
         - Chữ cách xa viền banner, không thiếu chữ trên cả điện thoại & máy tính
         ====================================================================== -->
    <section class="pt-3 sm:pt-4 pb-6 bg-white">
      <div class="qt-container">
        <div id="heroSlider" class="banner-viewport shadow-md">
          <div id="bannerTrack" class="banner-track">

            <!-- SLIDE 1 -->
            <div class="banner-slide bg-gradient-to-br from-brand-900 via-brand-700 to-brand-600 text-white">
              <div class="w-full px-6 py-8 sm:px-12 sm:py-11 lg:px-16 lg:py-14">
                <div class="grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                  <!-- Nội dung chữ cách xa viền ảnh banner -->
                  <div class="md:col-span-7 space-y-3 sm:space-y-4">
                    <p class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-blue-200">
                      CÔNG TY TNHH THƯƠNG MẠI VÀ XÂY DỰNG QUANG TẤN
                    </p>
                    <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight text-white">
                      CỬA NHÔM XINGFA CAO CẤP &amp; NHÔM KÍNH ĐÀ NẴNG
                    </h1>
                    <p class="text-xs sm:text-sm lg:text-base text-blue-100 leading-relaxed max-w-2xl">
                      Sản xuất và lắp đặt trực tiếp tại xưởng 82 Đặng Phúc Thông, An Khê, Đà Nẵng. Nhôm Xingfa nhập khẩu tem đỏ chính hãng, phụ kiện đồng bộ, thi công nhanh chuẩn xác và giá cạnh tranh nhất Miền Trung.
                    </p>
                    <div class="flex flex-wrap items-center gap-3 pt-1">
                      <a href="#yeu-cau-bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-accent-500 hover:bg-accent-600 text-white font-bold text-xs sm:text-sm shadow transition">
                        Nhận báo giá miễn phí
                      </a>
                      <a href="#san-pham-noi-bat" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white font-semibold text-xs sm:text-sm transition">
                        Xem mẫu cửa đẹp
                      </a>
                    </div>
                  </div>
                  <!-- Ảnh sản phẩm nằm hoàn toàn trong khung banner -->
                  <div class="md:col-span-5">
                    <div class="rounded-xl overflow-hidden border-2 border-white/25 bg-white/10 shadow-lg aspect-[16/10] w-full">
                      <img
                        src="https://lh3.googleusercontent.com/d/1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                        alt="Cửa đi quay mở 4 cánh nhôm Xingfa Quang Tấn Đà Nẵng"
                        class="w-full h-full object-cover"
                        onerror="handleDriveImgError(this, '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-', 'Cua Nhom Xingfa Quang Tan')"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- SLIDE 2 (Cùng kích thước và cấu trúc cân đối với Slide 1) -->
            <div class="banner-slide bg-gradient-to-br from-slate-900 via-brand-800 to-brand-600 text-white">
              <div class="w-full px-6 py-8 sm:px-12 sm:py-11 lg:px-16 lg:py-14">
                <div class="grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                  <div class="md:col-span-7 space-y-3 sm:space-y-4">
                    <p class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-blue-200">
                      QTWINDOW.COM — NÂNG TẦM KHÔNG GIAN SỐNG HIỆN ĐẠI
                    </p>
                    <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-tight text-white">
                      THI CÔNG TRỌN GÓI KÍNH CƯỜNG LỰC &amp; NỘI THẤT KÍNH
                    </h2>
                    <p class="text-xs sm:text-sm lg:text-base text-blue-100 leading-relaxed max-w-2xl">
                      Chuyên Cửa kính cường lực, Cầu thang kính, Phòng tắm kính, Kính ốp bếp, Cửa nhựa lõi thép &amp; Cửa kính tự động. Miễn phí khảo sát đo đạc tận công trình, bảo hành dài hạn uy tín.
                    </p>
                    <div class="flex flex-wrap items-center gap-3 pt-1">
                      <a href="#cong-trinh" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-accent-500 hover:bg-accent-600 text-white font-bold text-xs sm:text-sm shadow transition">
                        Xem công trình thực tế
                      </a>
                      <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white font-semibold text-xs sm:text-sm transition">
                        Bảng giá mới nhất
                      </a>
                    </div>
                  </div>
                  <div class="md:col-span-5">
                    <div class="rounded-xl overflow-hidden border-2 border-white/25 bg-white/10 shadow-lg aspect-[16/10] w-full">
                      <img
                        src="https://lh3.googleusercontent.com/d/1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ"
                        alt="Cửa nhôm Xingfa xếp trượt cao cấp Quang Tấn Đà Nẵng"
                        class="w-full h-full object-cover"
                        onerror="handleDriveImgError(this, '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ', 'Thi Cong Nhom Kinh Da Nang')"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>

          <!-- Điều hướng Slide đặt gọn ở cạnh dưới tránh đè lên chữ banner -->
          <div class="absolute bottom-2.5 left-0 right-0 flex items-center justify-center gap-3 z-20">
            <button type="button" onclick="prevBanner()" class="w-7 h-7 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition" aria-label="Banner trước">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M15 19l-7-7 7-7"/></svg>
            </button>
            <div class="flex items-center gap-2">
              <button type="button" id="dot-0" onclick="goToBanner(0)" class="w-6 h-2 rounded-full bg-white transition-all" aria-label="Slide 1"></button>
              <button type="button" id="dot-1" onclick="goToBanner(1)" class="w-2.5 h-2 rounded-full bg-white/45 hover:bg-white/80 transition-all" aria-label="Slide 2"></button>
            </div>
            <button type="button" onclick="nextBanner()" class="w-7 h-7 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition" aria-label="Banner tiếp theo">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M9 5l7 7-7 7"/></svg>
            </button>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================
         UX BUILDER SECTION 2: GIỚI THIỆU CÔNG TY QUANG TẤN (THEO MẪU NGỌC HÂN)
         ====================================================================== -->
    <section id="gioi-thieu" class="py-8 sm:py-10 bg-slate-50 border-t border-slate-200/70">
      <div class="qt-container">
        <div class="bg-white rounded-xl border border-slate-200 p-5 sm:p-8 shadow-sm">
          <div class="ux-section-title">
            <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-700 uppercase tracking-tight">
              CÔNG TY CỬA NHÔM XINGFA ĐÀ NẴNG – QUANG TẤN (QTWINDOW)
            </h2>
          </div>

          <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
            <div class="lg:col-span-7 space-y-3 text-sm sm:text-[15px] text-slate-600 leading-relaxed text-justify">
              <p>
                <strong class="text-brand-700">CÔNG TY TNHH THƯƠNG MẠI VÀ XÂY DỰNG QUANG TẤN (qtwindow.com)</strong> là đơn vị chuyên sản xuất, thiết kế và thi công lắp đặt các hạng mục nhôm kính cao cấp uy tín hàng đầu tại Đà Nẵng và khu vực Miền Trung.
              </p>
              <p>
                Sở hữu hệ thống kho xưởng khang trang rộng rãi ngay tại <strong>82 Đặng Phúc Thông, Phường An Khê, TP Đà Nẵng</strong> cùng dây chuyền máy móc hiện đại và đội ngũ kỹ thuật viên tay nghề cao, Quang Tấn cung cấp trọn gói: <strong>Cửa nhôm Xingfa nhập khẩu tem đỏ, Cửa nhựa lõi thép, Cửa kính cường lực, Cửa kính tự động, Cầu thang kính, Phòng tắm kính, Kính ốp bếp và Cánh kính nội thất</strong>.
              </p>
              <p>
                Quý khách có thể trực tiếp tham quan xưởng sản xuất để kiểm soát chất lượng thanh nhôm, kính và phụ kiện. QTwindows cam kết <strong>thi công nhanh chóng – chuẩn xác – giá xuất xưởng cạnh tranh – bảo hành dài hạn</strong>, góp phần nâng tầm không gian sống hiện đại, bền đẹp và an toàn cho mọi công trình.
              </p>
            </div>

            <!-- 4 Chỉ số năng lực kiểu Flatsome Counter -->
            <div class="lg:col-span-5 grid grid-cols-2 gap-3 sm:gap-4">
              <div class="rounded-xl bg-brand-50 border border-brand-100 p-4 text-center">
                <div class="text-2xl sm:text-3xl font-extrabold text-brand-700">150+</div>
                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Dự án đã hoàn thành</div>
              </div>
              <div class="rounded-xl bg-brand-50 border border-brand-100 p-4 text-center">
                <div class="text-2xl sm:text-3xl font-extrabold text-brand-700">50+</div>
                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Nhân viên kinh nghiệm</div>
              </div>
              <div class="rounded-xl bg-brand-50 border border-brand-100 p-4 text-center">
                <div class="text-2xl sm:text-3xl font-extrabold text-brand-700">100+</div>
                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Mẫu sản phẩm chất lượng</div>
              </div>
              <div class="rounded-xl bg-brand-50 border border-brand-100 p-4 text-center">
                <div class="text-2xl sm:text-3xl font-extrabold text-accent-600">100%</div>
                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Khách hàng hài lòng</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================
         UX BUILDER SECTION 3: DANH MỤC SẢN PHẨM (6 DANH MỤC TỪ WEB MẪU)
         - Chữ danh mục nhỏ gọn, tối ưu trên máy tính (1 hàng 6 cột) và điện thoại
         ====================================================================== -->
    <section id="danh-muc-san-pham" class="py-8 sm:py-10 bg-white border-t border-slate-200/70">
      <div class="qt-container">
        <div class="ux-section-title">
          <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-700 uppercase">
            DANH MỤC SẢN PHẨM
          </h2>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
          <!-- Danh mục 1: Cửa nhôm xingfa -->
          <button type="button" onclick="openCategoryModal('xingfa')" class="group text-left bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
              <img
                src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                alt="Cửa nhôm xingfa"
                class="w-full h-full object-cover ux-img-zoom"
                onerror="handleDriveImgError(this, '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX', 'Cua Nhom Xingfa')"
              />
            </div>
            <div class="p-2.5 text-center bg-brand-700 group-hover:bg-brand-600 transition flex-1 flex items-center justify-center">
              <h3 class="text-[11px] sm:text-xs font-bold text-white uppercase leading-tight">Cửa nhôm xingfa</h3>
            </div>
          </button>

          <!-- Danh mục 2: Cửa nhựa lõi thép -->
          <button type="button" onclick="openCategoryModal('cuanhua')" class="group text-left bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
              <img
                src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
                alt="Cửa nhựa lõi thép"
                class="w-full h-full object-cover ux-img-zoom"
                onerror="handleDriveImgError(this, '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA', 'Cua Nhua Loi Thep')"
              />
            </div>
            <div class="p-2.5 text-center bg-brand-700 group-hover:bg-brand-600 transition flex-1 flex items-center justify-center">
              <h3 class="text-[11px] sm:text-xs font-bold text-white uppercase leading-tight">Cửa nhựa lõi thép</h3>
            </div>
          </button>

          <!-- Danh mục 3: Cửa tự động -->
          <button type="button" onclick="openCategoryModal('cuatudong')" class="group text-left bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
              <img
                src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
                alt="Cửa kính tự động"
                class="w-full h-full object-cover ux-img-zoom"
                onerror="handleDriveImgError(this, '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ', 'Cua Tu Dong')"
              />
            </div>
            <div class="p-2.5 text-center bg-brand-700 group-hover:bg-brand-600 transition flex-1 flex items-center justify-center">
              <h3 class="text-[11px] sm:text-xs font-bold text-white uppercase leading-tight">Cửa kính tự động</h3>
            </div>
          </button>

          <!-- Danh mục 4: Cầu thang kính -->
          <button type="button" onclick="openCategoryModal('cauthang')" class="group text-left bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
              <img
                src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
                alt="Cầu thang kính"
                class="w-full h-full object-cover ux-img-zoom"
                onerror="handleDriveImgError(this, '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul', 'Cau Thang Kinh')"
              />
            </div>
            <div class="p-2.5 text-center bg-brand-700 group-hover:bg-brand-600 transition flex-1 flex items-center justify-center">
              <h3 class="text-[11px] sm:text-xs font-bold text-white uppercase leading-tight">Cầu thang kính</h3>
            </div>
          </button>

          <!-- Danh mục 5: Kính ốp bếp -->
          <button type="button" onclick="openCategoryModal('kinhbep')" class="group text-left bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
              <img
                src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
                alt="Kính ốp bếp"
                class="w-full h-full object-cover ux-img-zoom"
                onerror="handleDriveImgError(this, '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb', 'Kinh Op Bep')"
              />
            </div>
            <div class="p-2.5 text-center bg-brand-700 group-hover:bg-brand-600 transition flex-1 flex items-center justify-center">
              <h3 class="text-[11px] sm:text-xs font-bold text-white uppercase leading-tight">Kính ốp bếp</h3>
            </div>
          </button>

          <!-- Danh mục 6: Phòng tắm kính -->
          <button type="button" onclick="openCategoryModal('phongtam')" class="group text-left bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-500 transition flex flex-col">
            <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
              <img
                src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                alt="Phòng tắm kính"
                class="w-full h-full object-cover ux-img-zoom"
                onerror="handleDriveImgError(this, '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH', 'Phong Tam Kinh')"
              />
            </div>
            <div class="p-2.5 text-center bg-brand-700 group-hover:bg-brand-600 transition flex-1 flex items-center justify-center">
              <h3 class="text-[11px] sm:text-xs font-bold text-white uppercase leading-tight">Phòng tắm kính</h3>
            </div>
          </button>
        </div>
      </div>
    </section>

    <!-- ======================================================================
         UX BUILDER SECTION 4: SẢN PHẨM CỬA NHÔM XINGFA NỔI BẬT
         - 2 cột trên điện thoại, 3 cột trên máy tính
         - Tên sản phẩm hiển thị đầy đủ, không tràn ra ngoài hay thiếu chữ
         - Có giá bán, giá gốc và giảm giá % góc trên bên trái
         ====================================================================== -->
    <section id="san-pham-noi-bat" class="py-8 sm:py-10 bg-slate-50 border-t border-slate-200/70">
      <div class="qt-container">
        <div class="ux-section-title">
          <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-700 uppercase">
            SẢN PHẨM CỬA NHÔM XINGFA NỔI BẬT
          </h2>
        </div>

        <!-- Bộ lọc nhanh sản phẩm -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-6" id="productFilterBar">
          <button type="button" data-filter="all" onclick="filterProducts('all')" class="filter-btn active px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-700 text-white transition">Tất cả</button>
          <button type="button" data-filter="1-canh" onclick="filterProducts('1-canh')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-500 transition">Cửa 1 cánh</button>
          <button type="button" data-filter="2-canh" onclick="filterProducts('2-canh')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-500 transition">Cửa 2 cánh</button>
          <button type="button" data-filter="3-canh" onclick="filterProducts('3-canh')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-500 transition">Cửa 3 cánh</button>
          <button type="button" data-filter="4-canh" onclick="filterProducts('4-canh')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-500 transition">Cửa 4 cánh</button>
          <button type="button" data-filter="xep-truot" onclick="filterProducts('xep-truot')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-500 transition">Xếp trượt &amp; Cửa sổ</button>
        </div>

        <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột trên máy tính -->
        <div id="productGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-2.5 sm:gap-5">
          <!-- Sản phẩm được render tự động từ dữ liệu chính xác -->
        </div>
      </div>
    </section>

    <!-- ======================================================================
         UX BUILDER SECTION 5: BẢNG BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
         ====================================================================== -->
    <section id="bao-gia" class="py-8 sm:py-10 bg-white border-t border-slate-200/70">
      <div class="qt-container">
        <div class="ux-section-title">
          <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-700 uppercase">
            BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG MỚI NHẤT
          </h2>
        </div>

        <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="overflow-x-auto w-full">
            <table class="w-full text-left border-collapse text-xs sm:text-sm">
              <thead>
                <tr class="bg-brand-700 text-white">
                  <th class="py-3 px-3 sm:px-4 font-bold w-12 text-center">STT</th>
                  <th class="py-3 px-3 sm:px-4 font-bold">Hạng mục cửa nhôm Xingfa nhập khẩu tem đỏ</th>
                  <th class="py-3 px-3 sm:px-4 font-bold">Hệ nhôm &amp; Độ dày</th>
                  <th class="py-3 px-3 sm:px-4 font-bold text-right whitespace-nowrap">Đơn giá (VNĐ/m²)</th>
                </tr>
              </thead>
              <tbody class="divide-y divide-slate-200 text-slate-700">
                <tr class="hover:bg-brand-50/50">
                  <td class="py-3 px-3 sm:px-4 text-center font-semibold">1</td>
                  <td class="py-3 px-3 sm:px-4 font-semibold text-slate-900">Cửa sổ mở hất 2 cánh nhôm Xingfa</td>
                  <td class="py-3 px-3 sm:px-4">Xingfa Hệ 55 – Dày 1.4mm</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent-600 whitespace-nowrap">1.750.000 ₫</td>
                </tr>
                <tr class="hover:bg-brand-50/50 bg-slate-50/60">
                  <td class="py-3 px-3 sm:px-4 text-center font-semibold">2</td>
                  <td class="py-3 px-3 sm:px-4 font-semibold text-slate-900">Cửa đi quay mở 1 cánh nhôm Xingfa</td>
                  <td class="py-3 px-3 sm:px-4">Xingfa Hệ 55 – Dày 2.0mm</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent-600 whitespace-nowrap">1.850.000 ₫</td>
                </tr>
                <tr class="hover:bg-brand-50/50">
                  <td class="py-3 px-3 sm:px-4 text-center font-semibold">3</td>
                  <td class="py-3 px-3 sm:px-4 font-semibold text-slate-900">Cửa đi quay mở 2 cánh nhôm Xingfa</td>
                  <td class="py-3 px-3 sm:px-4">Xingfa Hệ 55 – Dày 2.0mm</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent-600 whitespace-nowrap">1.920.000 ₫</td>
                </tr>
                <tr class="hover:bg-brand-50/50 bg-slate-50/60">
                  <td class="py-3 px-3 sm:px-4 text-center font-semibold">4</td>
                  <td class="py-3 px-3 sm:px-4 font-semibold text-slate-900">Cửa đi quay mở 3 cánh nhôm Xingfa</td>
                  <td class="py-3 px-3 sm:px-4">Xingfa Hệ 55 – Dày 2.0mm</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent-600 whitespace-nowrap">1.980.000 ₫</td>
                </tr>
                <tr class="hover:bg-brand-50/50">
                  <td class="py-3 px-3 sm:px-4 text-center font-semibold">5</td>
                  <td class="py-3 px-3 sm:px-4 font-semibold text-slate-900">Cửa đi quay mở 4 cánh nhôm Xingfa</td>
                  <td class="py-3 px-3 sm:px-4">Xingfa Hệ 55 – Dày 2.0mm</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent-600 whitespace-nowrap">2.050.000 ₫</td>
                </tr>
                <tr class="hover:bg-brand-50/50 bg-slate-50/60">
                  <td class="py-3 px-3 sm:px-4 text-center font-semibold">6</td>
                  <td class="py-3 px-3 sm:px-4 font-semibold text-slate-900">Cửa Nhôm Xingfa Cửa Đi Xếp Trượt (4 - 6 cánh)</td>
                  <td class="py-3 px-3 sm:px-4">Xingfa Hệ 63 – Dày 2.0mm</td>
                  <td class="py-3 px-3 sm:px-4 text-right font-bold text-accent-600 whitespace-nowrap">2.100.000 ₫</td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="bg-brand-50 px-4 py-3 text-xs sm:text-sm text-slate-700 flex flex-wrap items-center justify-between gap-2">
            <span>* Đơn giá tham khảo đã bao gồm kính cường lực 8mm Chu Lai, miễn phí vận chuyển &amp; lắp đặt nội thành Đà Nẵng.</span>
            <a href="#yeu-cau-bao-gia" class="font-bold text-brand-700 hover:text-accent-600 underline whitespace-nowrap">Đăng ký nhận báo giá chi tiết →</a>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================
         UX BUILDER SECTION 6: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (6 DỰ ÁN THỰC TẾ)
         ====================================================================== -->
    <section id="cong-trinh" class="py-8 sm:py-10 bg-slate-50 border-t border-slate-200/70">
      <div class="qt-container">
        <div class="ux-section-title">
          <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-700 uppercase">
            CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
          </h2>
        </div>

        <div id="projectGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
          <!-- Dự án được render từ dữ liệu chính xác -->
        </div>
      </div>
    </section>

    <!-- ======================================================================
         UX BUILDER SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
         ====================================================================== -->
    <section id="yeu-cau-bao-gia" class="py-8 sm:py-12 bg-brand-800 text-white">
      <div class="qt-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-center">
          <!-- Cam kết dịch vụ Quang Tấn -->
          <div class="lg:col-span-6 space-y-4">
            <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-tight">
              ĐĂNG KÝ YÊU CẦU TƯ VẤN &amp; BÁO GIÁ MIỄN PHÍ
            </h2>
            <p class="text-sm sm:text-base text-blue-100 leading-relaxed">
              Quý khách chỉ cần để lại thông tin hoặc số điện thoại, đội ngũ kỹ thuật viên <strong>CÔNG TY TNHH TM &amp; XD QUANG TẤN</strong> sẽ liên hệ tư vấn mẫu cửa phù hợp, khảo sát đo đạc tận nơi và gửi báo giá chi tiết trong vòng 15 phút.
            </p>
            <ul class="space-y-2.5 text-sm text-blue-50">
              <li class="flex items-start gap-2.5">
                <span class="text-green-400 font-bold">✓</span>
                <span>Xưởng sản xuất trực tiếp tại <strong>82 Đặng Phúc Thông, P. An Khê, TP Đà Nẵng</strong> — giá gốc xuất xưởng.</span>
              </li>
              <li class="flex items-start gap-2.5">
                <span class="text-green-400 font-bold">✓</span>
                <span>100% nhôm Xingfa chính hãng, kính cường lực an toàn và phụ kiện đồng bộ cao cấp.</span>
              </li>
              <li class="flex items-start gap-2.5">
                <span class="text-green-400 font-bold">✓</span>
                <span>Miễn phí tư vấn thiết kế, khảo sát công trình và lắp đặt chuẩn kỹ thuật tại Đà Nẵng.</span>
              </li>
              <li class="flex items-start gap-2.5">
                <span class="text-green-400 font-bold">✓</span>
                <span>Hotline hỗ trợ nhanh: <a href="tel:0905481481" class="font-extrabold text-amber-300 underline">0905.481.481</a></span>
              </li>
            </ul>
          </div>

          <!-- Form nhập yêu cầu & báo giá -->
          <div class="lg:col-span-6">
            <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-6 shadow-xl space-y-4" novalidate>
              <h3 class="text-base sm:text-lg font-extrabold text-brand-700 border-b border-slate-200 pb-2.5">
                FORM GỬI YÊU CẦU BÁO GIÁ
              </h3>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                <div>
                  <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                  <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-200 outline-none" />
                </div>
                <div>
                  <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input id="qPhone" type="tel" required placeholder="VD: 0905 481 481" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-200 outline-none" />
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                <div>
                  <label for="qCategory" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                  <select id="qCategory" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-600 focus:ring-2 focus:ring-brand-200 outline-none">
                    <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa (1 - 5 cánh / Xếp trượt)</option>
                    <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                    <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                    <option value="Cửa kính tự động">Cửa kính tự động</option>
                    <option value="Cầu thang kính">Cầu thang kính</option>
                    <option value="Kính ốp bếp">Kính ốp bếp</option>
                    <option value="Phòng tắm kính">Phòng tắm kính</option>
                  </select>
                </div>
                <div>
                  <label for="qArea" class="block text-xs font-semibold text-slate-700 mb-1">Khối lượng / Diện tích dự kiến</label>
                  <input id="qArea" type="text" placeholder="VD: Khoảng 25m² hoặc nhà 3 tầng" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-200 outline-none" />
                </div>
              </div>

              <div>
                <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ công trình &amp; Yêu cầu chi tiết</label>
                <textarea id="qNote" rows="3" placeholder="Nhập địa chỉ công trình tại Đà Nẵng hoặc kích thước cửa cần báo giá..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-600 focus:ring-2 focus:ring-brand-200 outline-none"></textarea>
              </div>

              <button type="submit" class="w-full py-3 rounded-lg bg-accent-500 hover:bg-accent-600 text-white font-bold text-sm uppercase tracking-wide shadow transition">
                Gửi yêu cầu nhận báo giá ngay
              </button>

              <!-- Thông báo kết quả gửi form -->
              <div id="quoteFormMessage" class="hidden rounded-lg p-3 text-xs sm:text-sm font-medium"></div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================
         UX BUILDER SECTION 8: DANH MỤC CÁC BÀI VIẾT & TIN TỨC NỔI BẬT TRANG CHỦ
         ====================================================================== -->
    <section id="tin-tuc" class="py-8 sm:py-10 bg-white border-t border-slate-200/70">
      <div class="qt-container">
        <div class="ux-section-title">
          <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-700 uppercase">
            DANH MỤC BÀI VIẾT &amp; TIN TỨC NỔI BẬT
          </h2>
        </div>

        <!-- Thanh danh mục bài viết -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-6" id="articleCategoryBar">
          <button type="button" data-artcat="all" onclick="filterArticles('all')" class="art-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-700 text-white transition">Tất cả bài viết</button>
          <button type="button" data-artcat="kinh-nghiem" onclick="filterArticles('kinh-nghiem')" class="art-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition">Kinh nghiệm chọn cửa</button>
          <button type="button" data-artcat="bao-gia" onclick="filterArticles('bao-gia')" class="art-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition">Báo giá &amp; Tư vấn</button>
          <button type="button" data-artcat="ky-thuat" onclick="filterArticles('ky-thuat')" class="art-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition">Kỹ thuật thi công</button>
        </div>

        <div id="articleGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
          <!-- Bài viết được render tự động -->
        </div>
      </div>
    </section>

    <!-- ======================================================================
         UX BUILDER SECTION 9: ĐỐI TÁC CỦA CHÚNG TÔI (6 LOGO ĐỐI TÁC GOOGLE DRIVE)
         ====================================================================== -->
    <section class="py-8 sm:py-10 bg-slate-50 border-t border-slate-200/70">
      <div class="qt-container">
        <div class="ux-section-title">
          <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-700 uppercase">
            ĐỐI TÁC CỦA CHÚNG TÔI
          </h2>
        </div>

        <div class="grid grid-cols-3 md:grid-cols-6 gap-3 sm:gap-4">
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:border-brand-400 transition">
            <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" alt="Đối tác Quang Tấn 1" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk', 'Doi Tac 1')" />
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:border-brand-400 transition">
            <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" alt="Đối tác Quang Tấn 2" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq', 'Doi Tac 2')" />
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:border-brand-400 transition">
            <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" alt="Đối tác Quang Tấn 3" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn', 'Doi Tac 3')" />
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:border-brand-400 transition">
            <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" alt="Đối tác Quang Tấn 4" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT', 'Doi Tac 4')" />
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:border-brand-400 transition">
            <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-" alt="Đối tác Quang Tấn 5" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, '1SDcarhnX0yypmqdbawICjYBRtFnKngn-', 'Doi Tac 5')" />
          </div>
          <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:border-brand-400 transition">
            <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" alt="Đối tác Quang Tấn 6" class="max-h-full max-w-full object-contain" onerror="handleDriveImgError(this, '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg', 'Doi Tac 6')" />
          </div>
        </div>
      </div>
    </section>

    <!-- ======================================================================
         UX BUILDER SECTION 10: BẢN ĐỒ GOOGLE MAPS & FANPAGE FACEBOOK TRANG CHỦ
         ====================================================================== -->
    <section id="lien-he" class="py-8 sm:py-10 bg-white border-t border-slate-200/70">
      <div class="qt-container">
        <div class="ux-section-title">
          <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold text-brand-700 uppercase">
            BẢN ĐỒ CHỈ ĐƯỜNG &amp; FANPAGE CHÍNH THỨC
          </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6">
          <!-- Cột trái: Google Map 82 Đặng Phúc Thông, Phường An Khê, TP Đà Nẵng -->
          <div class="lg:col-span-7 bg-slate-50 rounded-xl border border-slate-200 p-4 flex flex-col">
            <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
              <div>
                <h3 class="text-sm sm:text-base font-bold text-brand-700">BẢN ĐỒ XƯỞNG &amp; SHOWROOM QUANG TẤN</h3>
                <p class="text-xs text-slate-600">82 Đặng Phúc Thông, Phường An Khê, TP Đà Nẵng</p>
              </div>
              <a
                href="https://www.google.com/maps/search/?api=1&query=82+Đặng+Phúc+Thông,+Phường+An+Khê,+Đà+Nẵng"
                target="_blank"
                rel="noopener noreferrer"
                class="inline-flex items-center gap-1 px-3 py-1.5 rounded-lg bg-brand-700 hover:bg-brand-600 text-white text-xs font-semibold transition"
              >
                <span>Chỉ đường Google Maps</span>
              </a>
            </div>
            <div class="w-full h-[300px] sm:h-[340px] rounded-lg overflow-hidden border border-slate-200 bg-slate-200">
              <iframe
                title="Bản đồ Công ty TNHH TM & XD Quang Tấn - 82 Đặng Phúc Thông, An Khê, Đà Nẵng"
                src="https://maps.google.com/maps?q=82+%C4%90%E1%BA%B7ng+Ph%C3%BAc+Th%C3%B4ng,+An+Kh%C3%AA,+Thanh+Kh%C3%AA,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                width="100%"
                height="100%"
                style="border:0;"
                allowfullscreen=""
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>

          <!-- Cột phải: Fanpage Facebook ra ngoài trang chủ -->
          <div class="lg:col-span-5 bg-slate-50 rounded-xl border border-slate-200 p-4 flex flex-col">
            <div class="flex items-center justify-between gap-2 mb-3">
              <div>
                <h3 class="text-sm sm:text-base font-bold text-brand-700">FANPAGE FACEBOOK QUANG TẤN</h3>
                <p class="text-xs text-slate-600">facebook.com/qtwindows.danang</p>
              </div>
              <a
                href="https://www.facebook.com/qtwindows.danang"
                target="_blank"
                rel="noopener noreferrer"
                class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-[#1877f2] hover:bg-[#145dbf] text-white text-xs font-semibold transition shrink-0"
              >
                <span>Theo dõi Fanpage</span>
              </a>
            </div>

            <!-- Thẻ giới thiệu Fanpage kết hợp nhúng Facebook Page Plugin -->
            <div class="bg-white rounded-lg border border-slate-200 overflow-hidden flex-1 flex flex-col justify-between">
              <div class="p-3.5 bg-gradient-to-r from-[#1877f2] to-brand-700 text-white flex items-center gap-3">
                <img
                  src="https://lh3.googleusercontent.com/d/1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk"
                  alt="Avatar Fanpage Nhôm Kính Quang Tấn Đà Nẵng"
                  class="w-12 h-12 rounded-lg bg-white p-1 object-contain shrink-0"
                  onerror="handleDriveImgError(this, '1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk', 'QT')"
                />
                <div class="min-w-0">
                  <p class="font-bold text-sm leading-snug">Nhôm Kính Cao Cấp Quang Tấn Đà Nẵng</p>
                  <p class="text-[11px] text-blue-100">LH: 0905 481 481 • 100% khách hàng đề xuất</p>
                </div>
              </div>

              <div class="w-full h-[220px] sm:h-[250px] overflow-hidden bg-white">
                <iframe
                  title="Fanpage Nhôm Kính Cao Cấp Quang Tấn Đà Nẵng"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fqtwindows.danang&tabs=timeline&width=500&height=250&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                  width="100%"
                  height="250"
                  style="border:none;overflow:hidden;width:100%;"
                  scrolling="no"
                  frameborder="0"
                  allowfullscreen="true"
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                ></iframe>
              </div>

              <div class="p-2.5 bg-slate-50 border-t border-slate-200 flex items-center justify-between gap-2 text-xs">
                <span class="text-slate-600">Cập nhật công trình mới mỗi ngày</span>
                <a href="https://www.facebook.com/qtwindows.danang" target="_blank" rel="noopener noreferrer" class="font-bold text-[#1877f2] hover:underline whitespace-nowrap">
                  Nhắn tin Messenger →
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- ========================================================================
       FOOTER FLATSOME 4 CỘT CHUẨN SEO & DỄ DỰNG LẠI TRÊN UX BUILDER
       ======================================================================== -->
  <footer class="bg-brand-900 text-slate-200 pt-10 pb-20 lg:pb-8 border-t-4 border-accent-500">
    <div class="qt-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 lg:gap-8 pb-8 border-b border-white/10 text-sm">
        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <img
              src="https://lh3.googleusercontent.com/d/1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk"
              alt="Logo QT Window"
              class="h-10 w-auto bg-white rounded-md px-1.5 py-1 object-contain"
              onerror="handleDriveImgError(this, '1v7MMVtGvGJw2_KtQeQuw4VHDhMsbxAgk', 'QTWINDOW')"
            />
            <div>
              <div class="font-extrabold text-white text-sm">QTWINDOW.COM</div>
              <div class="text-[11px] text-blue-200">Nhôm Kính Cao Cấp Đà Nẵng</div>
            </div>
          </div>
          <p class="font-bold text-white text-xs sm:text-sm leading-snug">
            CÔNG TY TNHH THƯƠNG MẠI VÀ XÂY DỰNG QUANG TẤN
          </p>
          <ul class="space-y-1.5 text-xs text-slate-300">
            <li>📍 Địa chỉ: 82 Đặng Phúc Thông, Phường An Khê, TP Đà Nẵng</li>
            <li>📞 Hotline: <a href="tel:0905481481" class="text-amber-300 font-bold hover:underline">0905.481.481</a></li>
            <li>✉️ Email: qtwindows.danang@gmail.com</li>
            <li>🌐 Website: qtwindow.com</li>
            <li>🧾 MST: 0401833337</li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục Cửa nhôm Xingfa -->
        <div>
          <h4 class="font-bold text-white uppercase text-xs tracking-wider pb-2 mb-3 border-b border-white/15">
            Cửa nhôm xingfa
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#san-pham-noi-bat" onclick="filterProducts('1-canh')" class="hover:text-white transition">› Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProducts('2-canh')" class="hover:text-white transition">› Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProducts('3-canh')" class="hover:text-white transition">› Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProducts('4-canh')" class="hover:text-white transition">› Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-noi-bat" onclick="filterProducts('xep-truot')" class="hover:text-white transition">› Cửa nhôm xingfa 5 cánh &amp; Xếp trượt</a></li>
            <li><a href="#bao-gia" class="hover:text-white transition">› Báo giá cửa nhôm Xingfa Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục Sản phẩm & Dịch vụ -->
        <div>
          <h4 class="font-bold text-white uppercase text-xs tracking-wider pb-2 mb-3 border-b border-white/15">
            Danh mục sản phẩm
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('xingfa')" class="hover:text-white transition">› Cửa nhôm xingfa Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cuakinh')" class="hover:text-white transition">› Cửa kính cường lực Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cuanhua')" class="hover:text-white transition">› Cửa nhựa lõi thép Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cuatudong')" class="hover:text-white transition">› Cửa kính tự động Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('cauthang')" class="hover:text-white transition">› Cầu thang kính Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('kinhbep')" class="hover:text-white transition">› Kính ốp bếp Đà Nẵng</a></li>
            <li><a href="#danh-muc-san-pham" onclick="openCategoryModal('phongtam')" class="hover:text-white transition">› Phòng tắm kính Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh & Kết nối -->
        <div>
          <h4 class="font-bold text-white uppercase text-xs tracking-wider pb-2 mb-3 border-b border-white/15">
            Hỗ trợ khách hàng
          </h4>
          <ul class="space-y-2 text-xs text-slate-300 mb-4">
            <li><a href="#gioi-thieu" class="hover:text-white transition">› Giới thiệu công ty Quang Tấn</a></li>
            <li><a href="#cong-trinh" class="hover:text-white transition">› Các công trình đã thi công</a></li>
            <li><a href="#tin-tuc" class="hover:text-white transition">› Tin tức &amp; Kinh nghiệm chọn cửa</a></li>
            <li><a href="#yeu-cau-bao-gia" class="hover:text-white transition">› Gửi yêu cầu báo giá trực tuyến</a></li>
          </ul>
          <div class="flex items-center gap-2">
            <a href="https://www.facebook.com/qtwindows.danang" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-[#1877f2] hover:bg-[#145dbf] text-white text-xs font-semibold transition">Facebook</a>
            <a href="https://zalo.me/0905481481" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-[#0068ff] hover:bg-[#0052cc] text-white text-xs font-semibold transition">Zalo</a>
            <a href="tel:0905481481" class="px-3 py-1.5 rounded-lg bg-accent-500 hover:bg-accent-600 text-white text-xs font-semibold transition">Gọi ngay</a>
          </div>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
        <p>Copyright © 2026 <strong class="text-white">qtwindow.com</strong> — CÔNG TY TNHH THƯƠNG MẠI VÀ XÂY DỰNG QUANG TẤN.</p>
        <p>Thiết kế chuẩn bố cục Flatsome UX Builder.</p>
      </div>
    </div>
  </footer>

  <!-- ========================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH MOBILE & PC)
       ======================================================================== -->
  <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-[65] flex flex-col items-end gap-2.5">
    <!-- Nút lên đầu trang -->
    <button
      id="backToTopBtn"
      type="button"
      onclick="window.scrollTo({top: 0, behavior: 'smooth'})"
      class="hidden w-10 h-10 rounded-full bg-slate-800/85 hover:bg-slate-900 text-white shadow-lg flex items-center justify-center transition"
      aria-label="Lên đầu trang"
    >
      <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 15l7-7 7 7"/></svg>
    </button>

    <!-- Nút Facebook -->
    <a
      href="https://www.facebook.com/qtwindows.danang"
      target="_blank"
      rel="noopener noreferrer"
      class="group flex items-center gap-2 rounded-full bg-[#1877f2] hover:bg-[#145dbf] text-white shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
      aria-label="Liên hệ Facebook Quang Tấn"
    >
      <svg class="w-5 h-5 shrink-0 fill-current" viewBox="0 0 24 24">
        <path d="M22.675 0H1.325C.593 0 0 .593 0 1.325v21.351C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.593 1.323-1.325V1.325C24 .593 23.407 0 22.675 0z"/>
      </svg>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0905481481"
      target="_blank"
      rel="noopener noreferrer"
      class="group flex items-center gap-2 rounded-full bg-[#0068ff] hover:bg-[#0052cc] text-white shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
      aria-label="Nhắn tin Zalo 0905.481.481"
    >
      <span class="w-5 h-5 rounded-full bg-white text-[#0068ff] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a
      href="tel:0905481481"
      class="hotline-pulse flex items-center gap-2 rounded-full bg-accent-500 hover:bg-accent-600 text-white shadow-xl p-3 sm:px-4 sm:py-2.5 transition"
      aria-label="Gọi Hotline 0905.481.481"
    >
      <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
      </svg>
      <span class="hidden sm:inline text-xs font-extrabold whitespace-nowrap">0905.481.481</span>
    </a>
  </div>

  <!-- ========================================================================
       MODAL CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT / DANH MỤC (KHÔNG DÙNG ALERT)
       ======================================================================== -->
  <div id="detailModal" class="fixed inset-0 z-[90] hidden items-center justify-center p-3 sm:p-5 bg-slate-900/65 backdrop-blur-xs">
    <div class="bg-white rounded-2xl shadow-2xl w-full max-w-2xl max-h-[90vh] overflow-hidden flex flex-col">
      <div class="flex items-center justify-between px-5 py-3.5 bg-brand-700 text-white">
        <h3 id="modalTitle" class="font-bold text-sm sm:text-base pr-4 leading-snug">Chi tiết thông tin</h3>
        <button type="button" onclick="closeDetailModal()" class="p-1.5 rounded-lg hover:bg-white/20 shrink-0" aria-label="Đóng hộp thoại">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div id="modalBody" class="p-5 overflow-y-auto text-sm text-slate-700 space-y-4">
        <!-- Nội dung modal được đổ động -->
      </div>
      <div class="px-5 py-3.5 border-t border-slate-200 bg-slate-50 flex flex-wrap items-center justify-between gap-2">
        <a href="tel:0905481481" class="inline-flex items-center gap-1.5 px-4 py-2 rounded-lg bg-accent-500 hover:bg-accent-600 text-white font-bold text-xs sm:text-sm transition">
          📞 Gọi tư vấn: 0905.481.481
        </a>
        <a href="#yeu-cau-bao-gia" onclick="closeDetailModal()" class="inline-flex items-center gap-1.5 px-4 py-2 rounded-lg bg-brand-700 hover:bg-brand-600 text-white font-bold text-xs sm:text-sm transition">
          Nhận báo giá mẫu này
        </a>
      </div>
    </div>
  </div>

  <!-- ========================================================================
       JAVASCRIPT: DỮ LIỆU CHÍNH XÁC, SLIDER TỰ TRƯỢT, LỌC SẢN PHẨM, BÀI VIẾT & FORM
       ======================================================================== -->
  <script>
    /**
     * Hàm xử lý fallback khi tải ảnh Google Drive gặp sự cố mạng hoặc giới hạn trình duyệt
     */
    function handleDriveImgError(imgEl, fileId, labelText) {
      try {
        const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
        if (step === 0) {
          imgEl.setAttribute('data-fallback-step', '1');
          imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
        } else if (step === 1) {
          imgEl.setAttribute('data-fallback-step', '2');
          imgEl.src = 'https://placehold.co/640x480/0f4c8a/ffffff?text=' + encodeURIComponent(labelText || 'QT Window');
        }
      } catch (err) {
        console.error('Image fallback error:', err);
      }
    }

    /* ------------------------------------------------------------------------
       DỮ LIỆU 6 SẢN PHẨM CHÍNH XÁC THEO YÊU CẦU + GIÁ & GIẢM GIÁ %
       ------------------------------------------------------------------------ */
    const PRODUCTS = [
      {
        id: 'sp-1',
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        category: '1-canh',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: '2.200.000 ₫',
        salePrice: '1.850.000 ₫',
        discount: '-16%',
        specs: [
          'Thanh profile: Nhôm Xingfa hệ 55 nhập khẩu chính hãng tem đỏ Quảng Đông',
          'Độ dày nhôm: Khuôn bao và cánh cửa dày 2.0mm (+-5%)',
          'Kính: Kính cường lực an toàn 8mm – 10mm (hoặc kính hộp cách âm)',
          'Phụ kiện: Kinlong / Draho / Cmech đồng bộ chính hãng',
          'Bảo hành: 5 năm thanh nhôm, 2 năm phụ kiện, bảo trì định kỳ tại Đà Nẵng'
        ],
        desc: 'Cửa đi mở quay 1 cánh nhôm Xingfa phù hợp cho cửa thông phòng, cửa ban công, cửa phòng ngủ và nhà vệ sinh. Thiết kế kín khít tuyệt đối nhờ hệ gioăng kép EPDM giúp cách âm, chống thấm nước mưa tối đa.'
      },
      {
        id: 'sp-2',
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        category: '2-canh',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: '2.350.000 ₫',
        salePrice: '1.920.000 ₫',
        discount: '-18%',
        specs: [
          'Thanh profile: Nhôm Xingfa hệ 55 nhập khẩu tem đỏ Quảng Đông',
          'Độ dày nhôm: 2.0mm ép góc ke nhảy / ke vĩnh cửu kín khít',
          'Màu sắc: Xám ghi, Đen tuyền, Trắng sứ, Nâu cà phê, Vân gỗ',
          'Phụ kiện: Bản lề 3D chịu lực, khóa đa điểm an toàn chống cạy phá',
          'Ứng dụng: Cửa mặt tiền nhà phố, cửa ban công rộng, cửa văn phòng'
        ],
        desc: 'Mẫu cửa đi mở quay 2 cánh nhôm Xingfa tạo không gian thoáng rộng, lấy sáng tối ưu và mang lại vẻ đẹp sang trọng, bền bỉ vượt trội trước khí hậu nắng gió miền Trung.'
      },
      {
        id: 'sp-3',
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        category: '3-canh',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: '2.400.000 ₫',
        salePrice: '1.980.000 ₫',
        discount: '-17%',
        specs: [
          'Thanh profile: Nhôm Xingfa hệ 55 nhập khẩu Quảng Đông chính hãng',
          'Độ dày: 2.0mm chịu gió bão cấp cao tại khu vực Đà Nẵng',
          'Kính: Kính cường lực 8mm – 10mm phôi Việt Nhật / Chu Lai',
          'Keo: Keo Apollo / Dow Corning đặc chủng chống thấm tuyệt đối',
          'Thi công: Đo đạc, sản xuất trực tiếp tại xưởng Quang Tấn'
        ],
        desc: 'Cửa đi mở quay 3 cánh nhôm Xingfa là giải pháp cân đối hoàn hảo cho những khung cửa có chiều ngang trung bình từ 2.2m đến 3.0m, tối ưu công năng mở rộng linh hoạt.'
      },
      {
        id: 'sp-4',
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        category: '4-canh',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: '2.480.000 ₫',
        salePrice: '2.050.000 ₫',
        discount: '-17%',
        specs: [
          'Thanh profile: Nhôm Xingfa hệ 55 tem đỏ Quảng Đông dày 2.0mm',
          'Cấu trúc: 4 cánh mở quay linh hoạt, đón gió & ánh sáng tối đa',
          'Sơn tĩnh điện: Phủ sơn ngoài trời cao cấp chống oxy hóa muối biển',
          'Phụ kiện: Bản lề 3D, khóa đa điểm, chốt âm đồng bộ chính hãng',
          'Phù hợp: Cửa chính mặt tiền nhà phố, biệt thự, showroom'
        ],
        desc: 'Dòng cửa chính mặt tiền được ưa chuộng nhất tại Đà Nẵng. Kết cấu khoang rỗng gân gia cường siêu cứng vững, thay thế hoàn hảo cho cửa gỗ tự nhiên mà không cong vênh mối mọt.'
      },
      {
        id: 'sp-5',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        category: 'xep-truot',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: '2.550.000 ₫',
        salePrice: '2.100.000 ₫',
        discount: '-18%',
        specs: [
          'Thanh profile: Nhôm Xingfa hệ 63 chuyên dụng xếp trượt (3, 4, 5, 6 cánh)',
          'Độ dày nhôm: 2.0mm – 3.5mm tại các vị trí ray treo chịu tải',
          'Cơ chế mở: Kết hợp trục bản lề và bánh xe trượt êm ái, mở thông thủy tới 95%',
          'Kính: Kính cường lực an toàn hoặc kính hộp cách nhiệt',
          'Phù hợp: Biệt thự sân vườn, khách sạn, resort, quán café mặt tiền rộng'
        ],
        desc: 'Cửa đi xếp trượt nhôm Xingfa hệ 63 cho phép gấp gọn toàn bộ các cánh cửa sang một bên, mở rộng không gian tối đa và tạo điểm nhấn kiến trúc đẳng cấp.'
      },
      {
        id: 'sp-6',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: 'xep-truot',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: '2.050.000 ₫',
        salePrice: '1.750.000 ₫',
        discount: '-15%',
        specs: [
          'Thanh profile: Nhôm Xingfa hệ 55 nhập khẩu tem đỏ dày 1.4mm',
          'Góc mở: Tối đa 45 độ với thanh định vị chống va đập gió giật',
          'Ưu điểm: Mở lấy thoáng ngay cả khi trời mưa mà không lo hắt nước',
          'Kính: Kính cường lực 6mm – 8mm trong suốt hoặc kính mờ',
          'Bảo hành: Chính hãng Quang Tấn Window Đà Nẵng'
        ],
        desc: 'Cửa sổ mở hất 2 cánh nhôm Xingfa là lựa chọn tối ưu cho nhà cao tầng, khách sạn và nhà phố nhờ khả năng thông gió an toàn, chống gió đập và ngăn nước mưa hiệu quả.'
      }
    ];

    /* ------------------------------------------------------------------------
       DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
       ------------------------------------------------------------------------ */
    const PROJECTS = [
      {
        title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
        driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
        location: 'TP. Đà Nẵng',
        scope: 'Thi công toàn bộ hệ thống cửa nhôm Xingfa nhập khẩu tem đỏ, vách kính mặt dựng và phòng tắm kính cường lực cao cấp.'
      },
      {
        title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
        driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
        location: 'Quảng Nam – Đà Nẵng',
        scope: 'Sản xuất và lắp đặt hạng mục cửa đi xếp trượt nhôm Xingfa, cửa sổ cách âm, lan can kính và vách kính khu nghỉ dưỡng tiêu chuẩn 4 sao.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
        driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
        location: 'TP. Đà Nẵng',
        scope: 'Cung cấp & lắp đặt trọn gói cửa nhôm kính cách âm chống gió biển, cửa kính tự động sảnh chính và phòng tắm kính khách sạn.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
        driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
        location: 'TP. Đà Nẵng',
        scope: 'Thi công hoàn thiện hệ cửa đi, cửa sổ nhôm Xingfa hệ 55, vách kính cường lực mặt tiền và cầu thang kính hiện đại.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
        driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
        location: 'TP. Đà Nẵng',
        scope: 'Lắp đặt hệ thống cửa nhôm kính cao cấp chuẩn tiêu chuẩn khách sạn ven biển, kính cường lực an toàn và phụ kiện chống gỉ sét.'
      },
      {
        title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
        driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
        location: 'Ven biển Mỹ Khê, Đà Nẵng',
        scope: 'Thi công cửa nhôm Xingfa chịu gió bão ven biển, hệ vách kính cường lực tầm nhìn panorama và cabin tắm kính toàn dự án.'
      }
    ];

    /* ------------------------------------------------------------------------
       DỮ LIỆU 6 BÀI VIẾT TIN TỨC NỔI BẬT TRANG CHỦ
       ------------------------------------------------------------------------ */
    const ARTICLES = [
      {
        id: 'art-1',
        cat: 'kinh-nghiem',
        catLabel: 'Kinh nghiệm chọn cửa',
        date: '18/11/2026',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu biển Đà Nẵng không?',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        excerpt: 'Đà Nẵng có khí hậu nắng nóng, gió bão và hơi muối biển cao. Tìm hiểu lý do cửa nhôm Xingfa tem đỏ sơn tĩnh điện là lựa chọn hàng đầu...',
        content: 'Với đặc thù khí hậu ven biển Đà Nẵng có độ ẩm cao, hơi muối dễ gây ăn mòn kim loại thông thường và mưa bão mạnh vào cuối năm, cửa nhôm Xingfa nhập khẩu chính hãng là giải pháp vượt trội. Thanh nhôm dày 1.4mm – 2.0mm phủ sơn tĩnh điện ngoài trời cao cấp không bong tróc, không han gỉ, kết hợp gioăng EPDM kín khít giúp ngăn nước mưa hắt và giảm tiếng ồn hiệu quả. Tại Quang Tấn Window (82 Đặng Phúc Thông), chúng tôi luôn tư vấn phụ kiện inox 304 và hệ kính cường lực phù hợp nhất cho từng vị trí công trình.'
      },
      {
        id: 'art-2',
        cat: 'bao-gia',
        catLabel: 'Báo giá & Tư vấn',
        date: '12/11/2026',
        title: 'Cửa nhôm Xingfa bao nhiêu 1m² tại Đà Nẵng? Cách tính giá chuẩn nhất',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        excerpt: 'Hướng dẫn cách tính diện tích cửa nhôm Xingfa, bảng đơn giá xuất xưởng và các yếu tố ảnh hưởng đến chi phí hoàn thiện...',
        content: 'Công thức tính tổng chi phí lắp đặt cửa nhôm Xingfa chuẩn xác nhất là: Giá 1 bộ cửa = (Diện tích cửa m² x Đơn giá thanh nhôm kính) + Đơn giá bộ phụ kiện tương ứng. Tại xưởng Quang Tấn Đà Nẵng, giá cửa nhôm Xingfa nhập khẩu tem đỏ dao động từ 1.750.000đ đến 2.100.000đ/m² tùy hệ cửa sổ hay cửa đi xếp trượt. Quý khách đặt trọn gói công trình nhà phố hoặc khách sạn sẽ nhận mức chiết khấu trực tiếp tại xưởng.'
      },
      {
        id: 'art-3',
        cat: 'kinh-nghiem',
        catLabel: 'Kinh nghiệm chọn cửa',
        date: '05/11/2026',
        title: 'So sánh cửa nhôm Xingfa và cửa gỗ: Nên chọn loại nào cho nhà phố?',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        excerpt: 'Cửa nhôm Xingfa là vật liệu thay thế gỗ bền vững với độ bền hàng chục năm, không cong vênh mối mọt và chi phí hợp lý...',
        content: 'So với cửa gỗ truyền thống dễ bị co ngót, cong vênh dưới nắng gắt hoặc mối mọt khi trời nồm ẩm, cửa nhôm Xingfa mang lại độ bền gần như vĩnh cửu, trọng lượng nhẹ giúp giảm tải kết cấu công trình và đặc biệt giữ không gian luôn sáng thoáng nhờ diện tích kính lớn. Ngoài ra, phiên bản nhôm Xingfa vân gỗ vẫn giữ được nét ấm cúng sang trọng như gỗ thật nhưng chi phí đầu tư tiết kiệm hơn đến 40%.'
      },
      {
        id: 'art-4',
        cat: 'ky-thuat',
        catLabel: 'Kỹ thuật thi công',
        date: '28/10/2026',
        title: 'Quy trình thi công cầu thang kính và phòng tắm kính chuẩn an toàn',
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        excerpt: 'Tiêu chuẩn độ dày kính cường lực 10mm - 12mm, phụ kiện inox 304 và kỹ thuật bắn keo chống thấm cho phòng tắm kính hiện đại...',
        content: 'Để đảm bảo an toàn tuyệt đối và tính thẩm mỹ lâu dài cho cầu thang kính và cabin phòng tắm kính, Quang Tấn áp dụng quy trình 5 bước nghiêm ngặt: khảo sát laser lấy cốt chuẩn, tôi kính cường lực 10mm – 12mm đạt chuẩn TCVN, sử dụng bản lề kẹp inox 304 chống gỉ tuyệt đối, cân chỉnh khe hở đồng đều và bơm keo silicone trung tính chống mốc. Toàn bộ công trình được nghiệm thu kỹ lưỡng trước khi bàn giao.'
      },
      {
        id: 'art-5',
        cat: 'ky-thuat',
        catLabel: 'Kỹ thuật thi công',
        date: '20/10/2026',
        title: 'Cửa nhôm Xingfa có chống trộm và cách âm tốt không?',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        excerpt: 'Phân tích cấu tạo thanh profile đa khoang, khóa đa điểm và kính dán an toàn giúp nâng cao an ninh tuyệt đối cho ngôi nhà...',
        content: 'Cửa nhôm Xingfa chính hãng có khả năng chống trộm rất cao khi kết hợp đồng bộ khóa đa điểm, chốt âm chắc chắn, bản lề 3D chịu lực và kính cường lực hoặc kính dán an toàn 2 lớp. Bên cạnh đó, cấu trúc thanh nhôm khoang rỗng kết hợp hệ gioăng kép giúp giảm tới 70% tiếng ồn xe cộ đô thị và ngăn thất thoát hơi lạnh điều hòa, tiết kiệm điện năng đáng kể.'
      },
      {
        id: 'art-6',
        cat: 'bao-gia',
        catLabel: 'Báo giá & Tư vấn',
        date: '14/10/2026',
        title: 'Xu hướng kính ốp bếp cường lực sơn màu bền đẹp dễ lau chùi 2026',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        excerpt: 'Kính ốp bếp cường lực 8mm liền mạch không mạch vữa giúp căn bếp luôn sạch bóng, chịu nhiệt cao và đa dạng màu phong thủy...',
        content: 'Kính ốp bếp cường lực 8mm sơn màu chịu nhiệt là giải pháp thay thế gạch men ốp bếp truyền thống. Bề mặt kính phẳng bóng, không có đường ron nên dầu mỡ dễ dàng lau sạch chỉ trong vài giây. Quang Tấn cung cấp hơn 30 mã màu thời thượng như xanh ngọc, vàng chanh, trắng sữa, ghi xám, xanh dương... đo cắt CNC chính xác ổ điện ngay tại Đà Nẵng.'
      }
    ];

    /* ------------------------------------------------------------------------
       DỮ LIỆU CHI TIẾT 7 DANH MỤC (KHI NGƯỜI DÙNG BẤM VÀO MENU HOẶC DANH MỤC)
       ------------------------------------------------------------------------ */
    const CATEGORY_INFO = {
      xingfa: {
        title: 'Cửa Nhôm Xingfa Chính Hãng Đà Nẵng',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        desc: 'Chuyên sản xuất & lắp đặt trọn gói cửa nhôm Xingfa nhập khẩu tem đỏ Quảng Đông (hệ 55, hệ 63, hệ 93): cửa đi mở quay 1-2-3-4 cánh, cửa đi xếp trượt 4-5-6 cánh, cửa lùa trượt và cửa sổ mở hất. Bảo hành chính hãng 5 năm.'
      },
      cuakinh: {
        title: 'Cửa Kính Cường Lực Đà Nẵng',
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        desc: 'Cung cấp cửa kính cường lực bản lề sàn 10mm – 12mm, cửa kính lùa treo ray inox, vách kính văn phòng và mặt tiền showroom. Phụ kiện VVP Thái Lan, Hafele, Adler chính hãng bền bỉ.'
      },
      cuanhua: {
        title: 'Cửa Nhựa Lõi Thép uPVC Đà Nẵng',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        desc: 'Cửa nhựa lõi thép gia cường uPVC cách âm, cách nhiệt tối ưu, chống nước tuyệt đối. Phù hợp cho cửa phòng ngủ, cửa nhà vệ sinh, cửa sổ căn hộ và công trình tiết kiệm chi phí.'
      },
      cuatudong: {
        title: 'Cửa Kính Tự Động Đà Nẵng',
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        desc: 'Thi công cửa trượt tự động mắt thần cảm biến cho khách sạn, bệnh viện, siêu thị, showroom và văn phòng hiện đại. Motor nhập khẩu Hàn Quốc, Nhật Bản vận hành êm ái, bền bỉ.'
      },
      cauthang: {
        title: 'Cầu Thang Kính & Lan Can Kính Đà Nẵng',
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        desc: 'Thiết kế & thi công cầu thang kính cường lực 10mm – 12mm kết hợp tay vịn gỗ lim, inox 304 hoặc nhôm định hình. Tạo cảm giác không gian rộng thoáng, sang trọng và an toàn tuyệt đối.'
      },
      kinhbep: {
        title: 'Kính Ốp Bếp Cường Lực Sơn Màu Đà Nẵng',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        desc: 'Kính cường lực 8mm sơn màu chịu nhiệt cao cấp, bảng màu đa dạng chuẩn phong thủy. Đo cắt CNC ổ điện chính xác, lắp đặt nhanh gọn trong ngày, không mối nối, cực kỳ dễ vệ sinh.'
      },
      phongtam: {
        title: 'Phòng Tắm Kính (Cabin Tắm) Đà Nẵng',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        desc: 'Thi công vách tắm kính đứng 90 độ, 135 độ, cửa lùa ray treo tiết kiệm diện tích. Kính cường lực 10mm an toàn cùng bộ phụ kiện inox 304 chống rỉ sét, giữ phòng tắm luôn khô ráo sạch sẽ.'
      }
    };

    /* ------------------------------------------------------------------------
       RENDER SẢN PHẨM (2 CỘT TRÊN MOBILE, ĐẦY ĐỦ TÊN, GIÁ & GIẢM GIÁ % GÓC TRÊN TRÁI)
       ------------------------------------------------------------------------ */
    function renderProducts(filterKey) {
      const grid = document.getElementById('productGrid');
      if (!grid) return;

      const list = filterKey === 'all'
        ? PRODUCTS
        : PRODUCTS.filter(p => p.category === filterKey);

      grid.innerHTML = list.map(p => `
        <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-400 transition flex flex-col">
          <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openProductModal('${p.id}')">
            <!-- Giảm giá % góc trên bên trái sản phẩm -->
            <span class="absolute top-2 left-2 z-10 inline-flex items-center justify-center px-2 py-0.5 rounded-md bg-accent-500 text-white font-extrabold text-[11px] sm:text-xs shadow">
              ${p.discount}
            </span>
            <img
              src="https://lh3.googleusercontent.com/d/${p.driveId}"
              alt="${p.name}"
              class="w-full h-full object-cover ux-img-zoom"
              onerror="handleDriveImgError(this, '${p.driveId}', '${p.name}')"
            />
          </div>

          <div class="p-2.5 sm:p-4 flex flex-col flex-1 justify-between gap-2">
            <!-- Tên sản phẩm đầy đủ, không cắt chữ, không tràn viền -->
            <h3
              onclick="openProductModal('${p.id}')"
              class="cursor-pointer text-[13px] sm:text-[15px] font-bold text-slate-800 group-hover:text-brand-700 leading-snug break-words"
            >
              ${p.name}
            </h3>

            <div class="space-y-2 pt-1 border-t border-slate-100">
              <!-- Giá bán và giá gốc -->
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-sm sm:text-base font-extrabold text-accent-600">${p.salePrice}</span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${p.oldPrice}</span>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-1.5">
                <button
                  type="button"
                  onclick="openProductModal('${p.id}')"
                  class="w-full py-1.5 px-2 rounded-lg bg-brand-700 hover:bg-brand-600 text-white font-semibold text-[11px] sm:text-xs transition text-center"
                >
                  Xem chi tiết
                </button>
                <a
                  href="#yeu-cau-bao-gia"
                  onclick="preselectQuote('${p.name}')"
                  class="w-full py-1.5 px-2 rounded-lg bg-brand-50 hover:bg-brand-100 text-brand-700 border border-brand-200 font-semibold text-[11px] sm:text-xs transition text-center"
                >
                  Báo giá
                </a>
              </div>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterProducts(filterKey) {
      renderProducts(filterKey);
      const buttons = document.querySelectorAll('#productFilterBar .filter-btn');
      buttons.forEach(btn => {
        if (btn.getAttribute('data-filter') === filterKey) {
          btn.className = 'filter-btn active px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-700 text-white transition';
        } else {
          btn.className = 'filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand-500 transition';
        }
      });
    }

    /* ------------------------------------------------------------------------
       RENDER 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
       ------------------------------------------------------------------------ */
    function renderProjects() {
      const grid = document.getElementById('projectGrid');
      if (!grid) return;

      grid.innerHTML = PROJECTS.map((proj, idx) => `
        <article onclick="openProjectModal(${idx})" class="cursor-pointer group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-400 transition flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/${proj.driveId}"
              alt="${proj.title}"
              class="w-full h-full object-cover ux-img-zoom"
              onerror="handleDriveImgError(this, '${proj.driveId}', 'Du An Da Nang')"
            />
          </div>
          <div class="p-3.5 sm:p-4 flex flex-col flex-1 justify-between gap-2">
            <h3 class="text-xs sm:text-sm font-extrabold text-brand-800 group-hover:text-accent-600 leading-snug break-words uppercase">
              ${proj.title}
            </h3>
            <p class="text-xs text-slate-600 leading-relaxed">${proj.scope}</p>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] font-semibold text-slate-500">
              <span>📍 ${proj.location}</span>
              <span class="text-brand-700 group-hover:underline">Xem chi tiết →</span>
            </div>
          </div>
        </article>
      `).join('');
    }

    /* ------------------------------------------------------------------------
       RENDER DANH MỤC BÀI VIẾT TRANG CHỦ
       ------------------------------------------------------------------------ */
    function renderArticles(catKey) {
      const grid = document.getElementById('articleGrid');
      if (!grid) return;

      const list = catKey === 'all'
        ? ARTICLES
        : ARTICLES.filter(a => a.cat === catKey);

      grid.innerHTML = list.map(art => `
        <article onclick="openArticleModal('${art.id}')" class="cursor-pointer group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-400 transition flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/${art.driveId}"
              alt="${art.title}"
              class="w-full h-full object-cover ux-img-zoom"
              onerror="handleDriveImgError(this, '${art.driveId}', 'Tin Tuc QT Window')"
            />
          </div>
          <div class="p-3.5 sm:p-4 flex flex-col flex-1 justify-between gap-2">
            <div class="space-y-1.5">
              <div class="flex items-center justify-between text-[11px] text-slate-500">
                <span class="font-semibold text-brand-700">${art.catLabel}</span>
                <span>${art.date}</span>
              </div>
              <h3 class="text-sm font-bold text-slate-800 group-hover:text-brand-700 leading-snug">
                ${art.title}
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">${art.excerpt}</p>
            </div>
            <div class="pt-2 border-t border-slate-100">
              <span class="text-xs font-bold text-brand-700 group-hover:text-accent-600">Xem thêm →</span>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterArticles(catKey) {
      renderArticles(catKey);
      const buttons = document.querySelectorAll('#articleCategoryBar .art-btn');
      buttons.forEach(btn => {
        if (btn.getAttribute('data-artcat') === catKey) {
          btn.className = 'art-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-brand-700 text-white transition';
        } else {
          btn.className = 'art-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-50 hover:text-brand-700 transition';
        }
      });
    }

    /* ------------------------------------------------------------------------
       BANNER TỰ TRƯỢT 2 SLIDE (AUTO-SLIDE + CHẠM VUỐT MOBILE)
       ------------------------------------------------------------------------ */
    let currentBannerIndex = 0;
    let bannerTimer = null;

    function updateBannerUI() {
      const track = document.getElementById('bannerTrack');
      if (!track) return;
      track.style.transform = `translateX(-${currentBannerIndex * 100}%)`;

      const dot0 = document.getElementById('dot-0');
      const dot1 = document.getElementById('dot-1');
      if (dot0 && dot1) {
        dot0.className = currentBannerIndex === 0
          ? 'w-6 h-2 rounded-full bg-white transition-all'
          : 'w-2.5 h-2 rounded-full bg-white/45 hover:bg-white/80 transition-all';
        dot1.className = currentBannerIndex === 1
          ? 'w-6 h-2 rounded-full bg-white transition-all'
          : 'w-2.5 h-2 rounded-full bg-white/45 hover:bg-white/80 transition-all';
      }
    }

    function goToBanner(idx) {
      currentBannerIndex = idx;
      updateBannerUI();
      resetBannerTimer();
    }

    function nextBanner() {
      currentBannerIndex = (currentBannerIndex + 1) % 2;
      updateBannerUI();
      resetBannerTimer();
    }

    function prevBanner() {
      currentBannerIndex = (currentBannerIndex + 1) % 2;
      updateBannerUI();
      resetBannerTimer();
    }

    function resetBannerTimer() {
      if (bannerTimer) clearInterval(bannerTimer);
      bannerTimer = setInterval(() => {
        currentBannerIndex = (currentBannerIndex + 1) % 2;
        updateBannerUI();
      }, 5500);
    }

    function initBannerSwipe() {
      const slider = document.getElementById('heroSlider');
      if (!slider) return;
      let startX = 0;
      slider.addEventListener('touchstart', (e) => {
        startX = e.changedTouches[0].screenX;
      }, { passive: true });
      slider.addEventListener('touchend', (e) => {
        const diff = e.changedTouches[0].screenX - startX;
        if (Math.abs(diff) > 45) {
          if (diff < 0) nextBanner();
          else prevBanner();
        }
      }, { passive: true });
    }

    /* ------------------------------------------------------------------------
       MODAL CHI TIẾT (SẢN PHẨM, DỰ ÁN, BÀI VIẾT, DANH MỤC)
       ------------------------------------------------------------------------ */
    function openDetailModal(title, htmlContent) {
      const modal = document.getElementById('detailModal');
      document.getElementById('modalTitle').textContent = title;
      document.getElementById('modalBody').innerHTML = htmlContent;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    function openProductModal(id) {
      const p = PRODUCTS.find(item => item.id === id);
      if (!p) return;
      const html = `
        <div class="grid grid-cols-1 sm:grid-cols-12 gap-4 items-start">
          <div class="sm:col-span-5 relative rounded-xl overflow-hidden border border-slate-200">
            <span class="absolute top-2 left-2 px-2.5 py-0.5 rounded-md bg-accent-500 text-white font-bold text-xs">${p.discount}</span>
            <img src="https://lh3.googleusercontent.com/d/${p.driveId}" alt="${p.name}" class="w-full h-auto object-cover" onerror="handleDriveImgError(this, '${p.driveId}', '${p.name}')" />
          </div>
          <div class="sm:col-span-7 space-y-3">
            <div class="flex items-baseline gap-2.5">
              <span class="text-xl font-extrabold text-accent-600">${p.salePrice} / m²</span>
              <span class="text-sm text-slate-400 line-through">${p.oldPrice}</span>
            </div>
            <p class="text-slate-600 leading-relaxed">${p.desc}</p>
            <div class="bg-slate-50 rounded-lg p-3 border border-slate-200">
              <p class="font-bold text-brand-700 text-xs uppercase mb-1.5">Thông số kỹ thuật tiêu chuẩn:</p>
              <ul class="space-y-1 text-xs text-slate-700 list-disc pl-4">
                ${p.specs.map(s => `<li>${s}</li>`).join('')}
              </ul>
            </div>
          </div>
        </div>
      `;
      openDetailModal(p.name, html);
    }

    function openProjectModal(index) {
      const proj = PROJECTS[index];
      if (!proj) return;
      const html = `
        <div class="space-y-4">
          <div class="rounded-xl overflow-hidden border border-slate-200 max-h-[320px]">
            <img src="https://lh3.googleusercontent.com/d/${proj.driveId}" alt="${proj.title}" class="w-full h-full object-cover" onerror="handleDriveImgError(this, '${proj.driveId}', 'Du An Da Nang')" />
          </div>
          <div class="space-y-2">
            <p class="text-xs font-semibold text-brand-700">📍 Khu vực thi công: ${proj.location}</p>
            <p class="text-slate-700 leading-relaxed">${proj.scope}</p>
            <p class="text-xs text-slate-500">Đơn vị thi công: <strong>CÔNG TY TNHH THƯƠNG MẠI VÀ XÂY DỰNG QUANG TẤN (qtwindow.com)</strong> — 82 Đặng Phúc Thông, P. An Khê, TP Đà Nẵng.</p>
          </div>
        </div>
      `;
      openDetailModal(proj.title, html);
    }

    function openArticleModal(id) {
      const art = ARTICLES.find(a => a.id === id);
      if (!art) return;
      const html = `
        <div class="space-y-4">
          <div class="flex items-center gap-3 text-xs text-slate-500">
            <span class="px-2.5 py-1 rounded bg-brand-50 text-brand-700 font-semibold">${art.catLabel}</span>
            <span>Ngày đăng: ${art.date}</span>
          </div>
          <div class="rounded-xl overflow-hidden border border-slate-200 max-h-[280px]">
            <img src="https://lh3.googleusercontent.com/d/${art.driveId}" alt="${art.title}" class="w-full h-full object-cover" onerror="handleDriveImgError(this, '${art.driveId}', 'QT Window')" />
          </div>
          <p class="text-slate-700 leading-relaxed text-sm sm:text-[15px]">${art.content}</p>
          <div class="p-3.5 rounded-lg bg-brand-50 border border-brand-100 text-xs text-slate-700">
            Quý khách cần tư vấn kỹ thuật hoặc nhận báo giá ưu đãi trực tiếp từ xưởng, vui lòng liên hệ Hotline/Zalo: <strong class="text-accent-600">0905.481.481</strong> hoặc ghé trực tiếp <strong>82 Đặng Phúc Thông, An Khê, Đà Nẵng</strong>.
          </div>
        </div>
      `;
      openDetailModal(art.title, html);
    }

    function openCategoryModal(key) {
      const info = CATEGORY_INFO[key];
      if (!info) return;
      const html = `
        <div class="space-y-4">
          <div class="rounded-xl overflow-hidden border border-slate-200 max-h-[280px]">
            <img src="https://lh3.googleusercontent.com/d/${info.driveId}" alt="${info.title}" class="w-full h-full object-cover" onerror="handleDriveImgError(this, '${info.driveId}', '${info.title}')" />
          </div>
          <p class="text-slate-700 leading-relaxed">${info.desc}</p>
          <div class="p-3.5 rounded-lg bg-slate-50 border border-slate-200 text-xs text-slate-600 space-y-1">
            <p><strong>Cam kết Quang Tấn Window:</strong></p>
            <p>✓ Khảo sát đo đạc và lên bản vẽ báo giá miễn phí 100% tại Đà Nẵng.</p>
            <p>✓ Gia công trực tiếp tại xưởng 82 Đặng Phúc Thông, không qua trung gian.</p>
            <p>✓ Bảo hành sản phẩm và phụ kiện dài hạn, hỗ trợ kỹ thuật nhanh chóng.</p>
          </div>
        </div>
      `;
      openDetailModal(info.title, html);
    }

    function preselectQuote(productName) {
      const noteEl = document.getElementById('qNote');
      if (noteEl) {
        noteEl.value = 'Tôi cần tư vấn và nhận báo giá cho mẫu: ' + productName;
      }
    }

    /* ------------------------------------------------------------------------
       ĐIỀU KHIỂN MENU MOBILE
       ------------------------------------------------------------------------ */
    function openMobileMenu() {
      const drawer = document.getElementById('mobileDrawer');
      const backdrop = document.getElementById('mobileDrawerBackdrop');
      drawer.classList.remove('-translate-x-full');
      backdrop.classList.remove('hidden');
      document.getElementById('mobileMenuBtn').setAttribute('aria-expanded', 'true');
      document.body.style.overflow = 'hidden';
    }

    function closeMobileMenu() {
      const drawer = document.getElementById('mobileDrawer');
      const backdrop = document.getElementById('mobileDrawerBackdrop');
      drawer.classList.add('-translate-x-full');
      backdrop.classList.add('hidden');
      document.getElementById('mobileMenuBtn').setAttribute('aria-expanded', 'false');
      document.body.style.overflow = '';
    }

    function toggleSubmenu(id, btn) {
      const sub = document.getElementById(id);
      if (!sub) return;
      sub.classList.toggle('hidden');
      const svg = btn.querySelector('svg');
      if (svg) svg.classList.toggle('rotate-180');
    }

    /* ------------------------------------------------------------------------
       XỬ LÝ FORM YÊU CẦU & BÁO GIÁ (KHÔNG DÙNG ALERT)
       ------------------------------------------------------------------------ */
    function initQuoteForm() {
      const form = document.getElementById('quoteForm');
      const msgBox = document.getElementById('quoteFormMessage');
      if (!form || !msgBox) return;

      form.addEventListener('submit', function (e) {
        e.preventDefault();
        const name = document.getElementById('qName').value.trim();
        const phone = document.getElementById('qPhone').value.trim();
        const category = document.getElementById('qCategory').value;

        if (!name || !phone) {
          msgBox.className = 'rounded-lg p-3 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
          msgBox.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Quang Tấn liên hệ báo giá cho bạn.';
          msgBox.classList.remove('hidden');
          return;
        }

        msgBox.className = 'rounded-lg p-3.5 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
        msgBox.innerHTML = `Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá hạng mục <strong>${category}</strong> của bạn đã được ghi nhận. Kỹ thuật viên <strong>Quang Tấn (0905.481.481)</strong> sẽ liên hệ qua SĐT <strong>${phone}</strong> trong ít phút.`;
        msgBox.classList.remove('hidden');
        form.reset();
      });
    }

    /* ------------------------------------------------------------------------
       KHỞI TẠO TOÀN TRANG KHI TẢI XONG
       ------------------------------------------------------------------------ */
    document.addEventListener('DOMContentLoaded', function () {
      renderProducts('all');
      renderProjects();
      renderArticles('all');
      updateBannerUI();
      resetBannerTimer();
      initBannerSwipe();
      initQuoteForm();

      const mobileBtn = document.getElementById('mobileMenuBtn');
      if (mobileBtn) {
        mobileBtn.addEventListener('click', openMobileMenu);
      }

      // Đóng modal khi click ra ngoài khung trắng
      const modal = document.getElementById('detailModal');
      if (modal) {
        modal.addEventListener('click', function (e) {
          if (e.target === modal) closeDetailModal();
        });
      }

      // Hiện nút lên đầu trang khi cuộn xuống
      const backBtn = document.getElementById('backToTopBtn');
      window.addEventListener('scroll', function () {
        if (!backBtn) return;
        if (window.scrollY > 360) backBtn.classList.remove('hidden');
        else backBtn.classList.add('hidden');
      }, { passive: true });
    });
  </script>
</body>
</html>
