<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH TƯ VẤN XÂY DỰNG TM-DV ĐỈNH THIÊN | xaydungdinhthien.com</title>
    <meta name="description" content="CÔNG TY TNHH TƯ VẤN XÂY DỰNG TM-DV ĐỈNH THIÊN - Chuyên Tư vấn, Thiết kế Kiến trúc, Thi công xây dựng trọn gói Nhà phố, Biệt thự, Khách sạn, Căn hộ, Nhà xưởng tại Đà Nẵng. Hotline: 0906.500.808.">
    <meta name="keywords" content="xây dựng đỉnh thiên, xaydungdinhthien.com, xây dựng đà nẵng, thi công trọn gói đà nẵng, thiết kế nhà phố đà nẵng, hòa khánh đà nẵng">

    <!-- Open Graph / Thumbnail Logo khi chia sẻ link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Xây Dựng Đỉnh Thiên - xaydungdinhthien.com">
    <meta property="og:title" content="CÔNG TY TNHH TƯ VẤN XÂY DỰNG TM-DV ĐỈNH THIÊN">
    <meta property="og:description" content="Tư vấn thiết kế kiến trúc & Thi công xây dựng trọn gói uy tín tại TP Đà Nẵng. Hotline: 0906.500.808.">
    <meta property="og:url" content="https://xaydungdinhthien.com">
    <meta property="og:image" content="https://placehold.co/1200x630/0F2B46/D49A2A?text=DINH+THIEN+CONSTRUCTION+-+0906.500.808">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH TƯ VẤN XÂY DỰNG TM-DV ĐỈNH THIÊN">
    <meta name="twitter:description" content="Thiết kế & Thi công xây dựng uy tín tại Đà Nẵng - xaydungdinhthien.com">
    <meta name="twitter:image" content="https://placehold.co/1200x630/0F2B46/D49A2A?text=DINH+THIEN+CONSTRUCTION">

    <!-- Favicon sử dụng biểu tượng Logo Đỉnh Thiên -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='10' fill='%230F2B46'/%3E%3Cpath d='M32 10L10 34h8v18h28V34h8L32 10z' fill='none' stroke='%23D49A2A' stroke-width='4' stroke-linejoin='round'/%3E%3Cpath d='M24 52V32l8-9 8 9v20' fill='none' stroke='%23FFFFFF' stroke-width='3.5' stroke-linejoin='round'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

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
                        /* Bảng màu đồng bộ theo Logo Đỉnh Thiên: Xanh Navy Kiến Trúc & Vàng Đồng */
                        brand: {
                            navy: '#0F2B46',
                            navyDark: '#091D31',
                            navyLight: '#1A3E63',
                            gold: '#D49A2A',
                            goldHover: '#B9821B',
                            goldLight: '#FBF5E8',
                            slateBg: '#F4F6F9',
                            border: '#E2E8F0',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Thiết lập chuẩn chống tràn viền, chống lệch phải tuyệt đối */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', system-ui, sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome: 95% chiều ngang màn hình trên máy tính, 100% gọn gàng trên điện thoại */
        .fl-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .fl-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Dropdown menu kiểu Flatsome mượt mà */
        .fl-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }
        .fl-nav-item:hover .fl-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Banner tự trượt: Dùng CSS Grid chồng lớp giúp 2 banner có kích thước bằng nhau 100% trên mọi thiết bị */
        .hero-slider-grid {
            display: grid;
            grid-template-columns: 1fr;
            position: relative;
            width: 100%;
            overflow: hidden;
        }
        .hero-slide {
            grid-area: 1 / 1;
            opacity: 0;
            visibility: hidden;
            pointer-events: none;
            transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
            position: relative;
            width: 100%;
            display: flex;
            align-items: center;
        }
        .hero-slide.is-active {
            opacity: 1;
            visibility: visible;
            pointer-events: auto;
            z-index: 2;
        }

        /* Tiêu đề section kiểu Flatsome UX Builder đơn giản, dễ dựng lại */
        .fl-section-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .fl-section-heading::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 56px;
            height: 3px;
            background-color: #D49A2A;
            border-radius: 2px;
        }
        .fl-section-heading-left {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .fl-section-heading-left::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 56px;
            height: 3px;
            background-color: #D49A2A;
            border-radius: 2px;
        }

        /* Hiệu ứng ảnh phóng nhẹ kiểu Flatsome Box */
        .fl-img-zoom img {
            transition: transform 0.45s ease;
        }
        .fl-img-zoom:hover img {
            transform: scale(1.05);
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes pulseRing {
            0% { box-shadow: 0 0 0 0 rgba(212, 154, 42, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(212, 154, 42, 0); }
            100% { box-shadow: 0 0 0 0 rgba(212, 154, 42, 0); }
        }
        .hotline-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- ========================================================= -->
    <!-- TOP BAR: THÔNG TIN NHANH KIỂU FLATSOME                    -->
    <!-- ========================================================= -->
    <div class="bg-brand-navyDark text-slate-200 text-[11px] sm:text-xs py-1.5 border-b border-white/10">
        <div class="fl-container flex flex-wrap items-center justify-between gap-x-4 gap-y-1">
            <div class="flex items-center gap-3 flex-wrap">
                <span class="inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                    <a href="tel:0906500808" class="hover:text-brand-gold font-medium transition">0906.500.808</a>
                </span>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9"/></svg>
                    <span>xaydungdinhthien.com</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-1.5 text-slate-300">
                <svg class="w-3.5 h-3.5 text-brand-gold shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                <span>Thửa đất số 225, TBĐ 213, Tổ 66, P. Hòa Khánh, TP Đà Nẵng</span>
            </div>
        </div>
    </div>

    <!-- ========================================================= -->
    <!-- HEADER CHÍNH: LOGO GỌN NHỎ + MENU 1 HÀNG KHÔNG NÚT GỌI    -->
    <!-- ========================================================= -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="fl-container flex items-center justify-between h-16 lg:h-[70px] gap-3">

            <!-- Logo Công Ty Chuyên Nghiệp & Gọn Nhỏ -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="Xây Dựng Đỉnh Thiên">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <!-- Nền khối kiến trúc Xanh Navy -->
                    <rect width="64" height="64" rx="10" fill="#0F2B46"/>
                    <!-- Đỉnh mái chữ A & khối cao ốc cách điệu Vàng Đồng -->
                    <path d="M32 9L11 32H18.5V52H45.5V32H53L32 9Z" stroke="#D49A2A" stroke-width="3.2" stroke-linejoin="round"/>
                    <!-- Trụ kiến trúc vững chãi bên trong -->
                    <path d="M25 52V33L32 25.5L39 33V52" stroke="#FFFFFF" stroke-width="3" stroke-linejoin="round"/>
                    <line x1="32" y1="25.5" x2="32" y2="52" stroke="#D49A2A" stroke-width="2.2"/>
                    <line x1="18.5" y1="52" x2="45.5" y2="52" stroke="#D49A2A" stroke-width="3" stroke-linecap="round"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-[15px] sm:text-[17px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition">
                        ĐỈNH THIÊN
                    </div>
                    <div class="text-[8.5px] sm:text-[9.5px] font-bold tracking-[0.14em] text-brand-gold uppercase">
                        XÂY DỰNG &bull; TM-DV
                    </div>
                </div>
            </a>

            <!-- Menu Desktop: Chữ gọn nhỏ, viết liền 1 hàng, không tràn viền, không xuống dòng tên danh mục -->
            <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-x-3 xl:gap-x-5" aria-label="Menu chính">
                <a href="#trang-chu" class="whitespace-nowrap text-[12px] xl:text-[13px] font-bold uppercase text-brand-navy hover:text-brand-gold transition py-2">Trang chủ</a>
                <a href="#gioi-thieu" class="whitespace-nowrap text-[12px] xl:text-[13px] font-bold uppercase text-slate-700 hover:text-brand-gold transition py-2">Giới thiệu</a>

                <!-- Dropdown: Công trình thực tế (theo web mẫu) -->
                <div class="relative fl-nav-item">
                    <a href="#cong-trinh-thuc-te" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-bold uppercase text-slate-700 hover:text-brand-gold transition py-2">
                        <span>Công trình thực tế</span>
                        <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="fl-dropdown-menu absolute left-0 top-full w-60 bg-white border border-slate-200 rounded-lg shadow-lg py-2 z-50">
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san')" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Khách sạn – Căn hộ – Phòng trọ</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Biệt thự</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Nhà phố</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong')" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Văn phòng – Nhà xưởng</a>
                    </div>
                </div>

                <!-- Dropdown: Lĩnh vực hoạt động (theo web mẫu) -->
                <div class="relative fl-nav-item">
                    <a href="#linh-vuc-hoat-dong" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-bold uppercase text-slate-700 hover:text-brand-gold transition py-2">
                        <span>Lĩnh vực hoạt động</span>
                        <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="fl-dropdown-menu absolute left-0 top-full w-56 bg-white border border-slate-200 rounded-lg shadow-lg py-2 z-50">
                        <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Thiết kế Kiến trúc – Nội thất</a>
                        <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Thi công phần thô</a>
                        <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Thi công hoàn thiện</a>
                        <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Thi công nội thất</a>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="whitespace-nowrap text-[12px] xl:text-[13px] font-bold uppercase text-slate-700 hover:text-brand-gold transition py-2">Dự án Đà Nẵng</a>

                <!-- Dropdown: Báo giá (theo web mẫu) -->
                <div class="relative fl-nav-item">
                    <a href="#bao-gia" class="whitespace-nowrap inline-flex items-center gap-1 text-[12px] xl:text-[13px] font-bold uppercase text-slate-700 hover:text-brand-gold transition py-2">
                        <span>Báo giá</span>
                        <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="fl-dropdown-menu absolute right-0 top-full w-56 bg-white border border-slate-200 rounded-lg shadow-lg py-2 z-50">
                        <a href="#bao-gia" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Báo giá thiết kế kiến trúc</a>
                        <a href="#bao-gia" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Báo giá thi công phần thô</a>
                        <a href="#bao-gia" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Báo giá thi công hoàn thiện</a>
                        <a href="#bao-gia" class="block px-4 py-2 text-xs font-semibold text-slate-700 hover:bg-brand-goldLight hover:text-brand-navy transition">Báo giá thi công trọn gói</a>
                    </div>
                </div>

                <a href="#tin-tuc" class="whitespace-nowrap text-[12px] xl:text-[13px] font-bold uppercase text-slate-700 hover:text-brand-gold transition py-2">Tin tức</a>
                <a href="#lien-he" class="whitespace-nowrap text-[12px] xl:text-[13px] font-bold uppercase text-slate-700 hover:text-brand-gold transition py-2">Liên hệ</a>
            </nav>

            <!-- Nút Mở Menu Mobile (không để nút Gọi ngay trên Header tránh tràn viền) -->
            <button id="mobileMenuBtn" type="button" class="lg:hidden p-2 rounded-lg text-brand-navy hover:bg-slate-100 focus:outline-none" aria-label="Mở danh mục">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M4 6h16M4 12h16M4 18h16"/>
                </svg>
            </button>
        </div>

        <!-- Menu Mobile Dạng Xổ Xuống Gọn Đẹp -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="fl-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-brand-navy">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Giới thiệu</a>
                <div class="py-2.5">
                    <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="block hover:text-brand-gold">Công trình thực tế</a>
                    <div class="pl-4 mt-1.5 flex flex-col gap-1.5 text-xs font-medium text-slate-600">
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('khach-san'); closeMobileMenu();" class="py-1 hover:text-brand-gold">• Khách sạn – Căn hộ – Phòng trọ</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu'); closeMobileMenu();" class="py-1 hover:text-brand-gold">• Biệt thự</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho'); closeMobileMenu();" class="py-1 hover:text-brand-gold">• Nhà phố</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong'); closeMobileMenu();" class="py-1 hover:text-brand-gold">• Văn phòng – Nhà xưởng</a>
                    </div>
                </div>
                <a href="#linh-vuc-hoat-dong" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Lĩnh vực hoạt động</a>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Dự án Đà Nẵng</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Báo giá xây dựng</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Tin tức</a>
                <a href="#doi-tac" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Đối tác</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="py-2.5 hover:text-brand-gold">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <!-- ========================================================= -->
    <!-- HERO SECTION: 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU  -->
    <!-- CHỮ NẰM TRONG HẾT BANNER, CÁCH XA VIỀN, KHÔNG THIẾU CHỮ   -->
    <!-- ========================================================= -->
    <section id="trang-chu" class="bg-brand-slateBg py-3 sm:py-4 lg:py-5">
        <div class="fl-container">
            <div id="heroSlider" class="relative rounded-xl overflow-hidden shadow-md bg-brand-navy">
                <div class="hero-slider-grid">

                    <!-- BANNER 1 -->
                    <div class="hero-slide is-active min-h-[290px] sm:min-h-[370px] md:min-h-[430px] lg:min-h-[490px]">
                        <img
                            src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                            onerror="handleDriveImgError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz')"
                            alt="Thi công xây dựng trọn gói Đỉnh Thiên Đà Nẵng"
                            class="absolute inset-0 w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/50"></div>
                        <!-- Vùng an toàn cách xa viền banner trên cả điện thoại và máy tính -->
                        <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-14 md:px-20 md:py-16 lg:px-24 lg:py-20">
                            <div class="max-w-2xl">
                                <p class="text-brand-gold font-bold uppercase tracking-wider text-[11px] sm:text-xs md:text-sm mb-2">
                                    CÔNG TY TNHH TƯ VẤN XÂY DỰNG TM-DV ĐỈNH THIÊN
                                </p>
                                <h1 class="text-white font-extrabold text-lg sm:text-2xl md:text-3xl lg:text-4xl leading-snug mb-3">
                                    TƯ VẤN THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI CHUYÊN NGHIỆP
                                </h1>
                                <p class="text-slate-200 text-xs sm:text-sm md:text-base leading-relaxed mb-5 max-w-xl">
                                    Cam kết chuẩn kỹ thuật, vật tư chính hãng, thi công đúng tiến độ cho mọi công trình Nhà phố, Biệt thự, Khách sạn và Căn hộ tại TP Đà Nẵng.
                                </p>
                                <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                    <a href="#form-bao-gia" class="inline-block bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-xs sm:text-sm px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg transition shadow">
                                        Nhận Báo Giá Miễn Phí
                                    </a>
                                    <a href="#cong-trinh-thuc-te" class="inline-block bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg transition">
                                        Xem Công Trình Thực Tế
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 -->
                    <div class="hero-slide min-h-[290px] sm:min-h-[370px] md:min-h-[430px] lg:min-h-[490px]">
                        <img
                            src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                            onerror="handleDriveImgError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT')"
                            alt="Dự án tiêu biểu tại Đà Nẵng - Xây Dựng Đỉnh Thiên"
                            class="absolute inset-0 w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/50"></div>
                        <!-- Vùng an toàn cách xa viền banner đồng nhất kích thước với Banner 1 -->
                        <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-14 md:px-20 md:py-16 lg:px-24 lg:py-20">
                            <div class="max-w-2xl">
                                <p class="text-brand-gold font-bold uppercase tracking-wider text-[11px] sm:text-xs md:text-sm mb-2">
                                    XAYDUNGDINHTHIEN.COM &bull; HOTLINE 0906.500.808
                                </p>
                                <h2 class="text-white font-extrabold text-lg sm:text-2xl md:text-3xl lg:text-4xl leading-snug mb-3">
                                    KIẾN TẠO KHÔNG GIAN SỐNG BỀN VỮNG &amp; ĐẲNG CẤP TẠI ĐÀ NẴNG
                                </h2>
                                <p class="text-slate-200 text-xs sm:text-sm md:text-base leading-relaxed mb-5 max-w-xl">
                                    Đội ngũ kiến trúc sư và kỹ sư dày dạn kinh nghiệm đồng hành từ khâu thiết kế bản vẽ đến hoàn thiện bàn giao chìa khóa trao tay.
                                </p>
                                <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                    <a href="#du-an-da-nang" class="inline-block bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-xs sm:text-sm px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg transition shadow">
                                        Khám Phá Dự Án Đà Nẵng
                                    </a>
                                    <a href="tel:0906500808" class="inline-block bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg transition">
                                        Tư Vấn: 0906.500.808
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng trái / phải nhỏ gọn sát mép không đè chữ -->
                <button type="button" onclick="prevSlide()" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M15 19l-7-7 7-7"/></svg>
                </button>
                <button type="button" onclick="nextSlide()" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M9 5l7 7-7 7"/></svg>
                </button>

                <!-- Chấm tròn chỉ báo 2 slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToSlide(0)" class="hero-dot w-6 h-2 rounded-full bg-brand-gold transition-all" aria-label="Xem banner 1"></button>
                    <button type="button" onclick="goToSlide(1)" class="hero-dot w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all" aria-label="Xem banner 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- DỊCH VỤ TIÊU BIỂU / LĨNH VỰC HOẠT ĐỘNG (THEO WEB MẪU)     -->
    <!-- ========================================================= -->
    <section id="linh-vuc-hoat-dong" class="py-10 lg:py-14 bg-white">
        <div class="fl-container">
            <div class="text-center mb-8">
                <h2 class="fl-section-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-navy">
                    Dịch Vụ Tiêu Biểu
                </h2>
                <p class="text-slate-600 text-xs sm:text-sm mt-3 max-w-2xl mx-auto">
                    Giải pháp tư vấn, thiết kế và thi công toàn diện theo quy trình chuẩn kỹ thuật của Xây Dựng Đỉnh Thiên.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <div class="bg-brand-slateBg border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:border-brand-gold hover:shadow-md transition">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center">
                        <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"/></svg>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-brand-navy uppercase mb-1.5 leading-snug">Thiết Kế Kiến Trúc – Nội Thất</h3>
                    <p class="text-slate-600 text-[11.5px] sm:text-xs leading-relaxed">Lập hồ sơ thiết kế kiến trúc 3D, kết cấu, điện nước và phối cảnh nội thất tối ưu công năng.</p>
                </div>

                <div class="bg-brand-slateBg border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:border-brand-gold hover:shadow-md transition">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center">
                        <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/></svg>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-brand-navy uppercase mb-1.5 leading-snug">Thi Công Phần Thô</h3>
                    <p class="text-slate-600 text-[11.5px] sm:text-xs leading-relaxed">Thi công móng, kết cấu bê tông cốt thép, xây tô tường đúng tiêu chuẩn bền vững lâu dài.</p>
                </div>

                <div class="bg-brand-slateBg border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:border-brand-gold hover:shadow-md transition">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center">
                        <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/></svg>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-brand-navy uppercase mb-1.5 leading-snug">Thi Công Hoàn Thiện</h3>
                    <p class="text-slate-600 text-[11.5px] sm:text-xs leading-relaxed">Ốp lát, sơn bả, trần thạch cao, cửa nhôm kính, thiết bị vệ sinh và hệ thống điện nước đồng bộ.</p>
                </div>

                <div class="bg-brand-slateBg border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:border-brand-gold hover:shadow-md transition">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 mx-auto mb-3 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center">
                        <svg class="w-6 h-6 sm:w-7 sm:h-7" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M4 5a1 1 0 011-1h14a1 1 0 011 1v2a1 1 0 01-1 1H5a1 1 0 01-1-1V5zM4 13a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H5a1 1 0 01-1-1v-6zM16 13a1 1 0 011-1h2a1 1 0 011 1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-6z"/></svg>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-brand-navy uppercase mb-1.5 leading-snug">Thi Công Nội Thất Trọn Gói</h3>
                    <p class="text-slate-600 text-[11.5px] sm:text-xs leading-relaxed">Sản xuất và lắp đặt nội thất gỗ công nghiệp, gỗ tự nhiên tinh tế, đúng bản vẽ 3D bàn giao.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- GIỚI THIỆU CÔNG TY & THẾ MẠNH (BỐ CỤC CHUẨN FLATSOME)     -->
    <!-- ========================================================= -->
    <section id="gioi-thieu" class="py-10 lg:py-14 bg-brand-slateBg border-y border-slate-200">
        <div class="fl-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10">
                <div class="lg:col-span-6">
                    <h2 class="fl-section-heading-left text-lg sm:text-2xl font-extrabold uppercase text-brand-navy leading-snug">
                        CÔNG TY TNHH TƯ VẤN XÂY DỰNG TM-DV ĐỈNH THIÊN
                    </h2>
                    <p class="text-slate-700 text-xs sm:text-sm leading-relaxed mt-4">
                        <strong>CÔNG TY TNHH TƯ VẤN XÂY DỰNG TM-DV ĐỈNH THIÊN</strong> chuyên Tư vấn – Thiết kế – Thi công Xây dựng các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê, Văn phòng và Nhà xưởng tại khu vực TP Đà Nẵng và miền Trung.
                    </p>
                    <p class="text-slate-700 text-xs sm:text-sm leading-relaxed mt-3">
                        Đặt chữ <strong>“TÂM – TÍN – CHẤT LƯỢNG”</strong> làm kim chỉ nam trong mọi hoạt động, Đỉnh Thiên cam kết đem đến những công trình đạt chuẩn <strong>An toàn – Thẩm mỹ – Đúng tiến độ – Chi phí minh bạch</strong>, giúp khách hàng hoàn toàn an tâm khi trao gửi niềm tin xây dựng tổ ấm và dự án kinh doanh.
                    </p>
                    <div class="grid grid-cols-3 gap-3 mt-5 pt-5 border-t border-slate-300/70">
                        <div class="bg-white rounded-lg p-3 text-center border border-slate-200">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-gold">10+</div>
                            <div class="text-[11px] sm:text-xs font-semibold text-brand-navy mt-0.5">Năm kinh nghiệm</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 text-center border border-slate-200">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-gold">150+</div>
                            <div class="text-[11px] sm:text-xs font-semibold text-brand-navy mt-0.5">Công trình bàn giao</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 text-center border border-slate-200">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-gold">100%</div>
                            <div class="text-[11px] sm:text-xs font-semibold text-brand-navy mt-0.5">Hài lòng chất lượng</div>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-6">
                    <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
                        <img
                            src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1200"
                            onerror="handleDriveImgError(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR')"
                            alt="Đội ngũ thi công Xây Dựng Đỉnh Thiên tại công trường"
                            class="w-full h-60 sm:h-72 lg:h-80 object-cover"
                        >
                    </div>
                </div>
            </div>

            <!-- Thế mạnh của chúng tôi (theo web mẫu tintruongthinh.com) -->
            <div class="text-center mb-6">
                <h3 class="fl-section-heading text-lg sm:text-xl font-extrabold uppercase text-brand-navy">
                    Thế Mạnh Của Đỉnh Thiên
                </h3>
            </div>
            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm">
                    <h4 class="font-bold text-brand-navy text-[13px] sm:text-sm mb-1.5">1. Đội ngũ KTS, kỹ sư giàu kinh nghiệm</h4>
                    <p class="text-slate-600 text-[11.5px] sm:text-xs leading-relaxed">Tập hợp kiến trúc sư sáng tạo, kỹ sư hiện trường chuẩn mực và đội thợ thi công tay nghề cao.</p>
                </div>
                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm">
                    <h4 class="font-bold text-brand-navy text-[13px] sm:text-sm mb-1.5">2. Giải pháp thiết kế hiện đại</h4>
                    <p class="text-slate-600 text-[11.5px] sm:text-xs leading-relaxed">Luôn cập nhật xu hướng kiến trúc mới, vật liệu bền đẹp và tối ưu công năng sử dụng thực tế.</p>
                </div>
                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm">
                    <h4 class="font-bold text-brand-navy text-[13px] sm:text-sm mb-1.5">3. Giám sát tiến độ chặt chẽ</h4>
                    <p class="text-slate-600 text-[11.5px] sm:text-xs leading-relaxed">Báo cáo tiến độ từng giai đoạn rõ ràng, nghiệm thu kỹ thuật minh bạch trước khi chuyển bước.</p>
                </div>
                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm">
                    <h4 class="font-bold text-brand-navy text-[13px] sm:text-sm mb-1.5">4. Bảo hành công trình dài hạn</h4>
                    <p class="text-slate-600 text-[11.5px] sm:text-xs leading-relaxed">Chính sách bảo hành kết cấu và hoàn thiện rõ ràng, hỗ trợ nhanh chóng sau khi bàn giao.</p>
                </div>
                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm">
                    <h4 class="font-bold text-brand-navy text-[13px] sm:text-sm mb-1.5">5. Dự toán minh bạch, không phát sinh</h4>
                    <p class="text-slate-600 text-[11.5px] sm:text-xs leading-relaxed">Bóc tách khối lượng chi tiết, cam kết đúng chủng loại vật tư và mức đầu tư tối ưu nhất.</p>
                </div>
                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm">
                    <h4 class="font-bold text-brand-navy text-[13px] sm:text-sm mb-1.5">6. Hỗ trợ tư vấn miễn phí 24/7</h4>
                    <p class="text-slate-600 text-[11.5px] sm:text-xs leading-relaxed">Khảo sát mặt bằng tận nơi tại Đà Nẵng, tư vấn phương án sơ bộ và pháp lý xây dựng miễn phí.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- CÔNG TRÌNH THỰC TẾ (9 ẢNH THI CÔNG THỰC TẾ TỪ DRIVE)      -->
    <!-- DANH MỤC 1 HÀNG CHỮ GỌN, 2 CỘT TRÊN MOBILE, KHÔNG NHÃN DÁN-->
    <!-- ========================================================= -->
    <section id="cong-trinh-thuc-te" class="py-10 lg:py-14 bg-white">
        <div class="fl-container">
            <div class="text-center mb-6">
                <h2 class="fl-section-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-navy">
                    Công Trình Thực Tế Thi Công
                </h2>
                <p class="text-slate-600 text-xs sm:text-sm mt-3">
                    Hình ảnh thực tế các hạng mục thi công xây dựng do Đỉnh Thiên trực tiếp triển khai.
                </p>
            </div>

            <!-- Thanh lọc danh mục trang chủ: Chữ nhỏ gọn, không xuống dòng từng tên danh mục -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-7" role="tablist" aria-label="Danh mục công trình thực tế">
                <button type="button" data-filter="all" onclick="filterProjects('all')" class="project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-bold uppercase border border-brand-navy bg-brand-navy text-white transition">
                    Tất cả
                </button>
                <button type="button" data-filter="khach-san" onclick="filterProjects('khach-san')" class="project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-bold uppercase border border-slate-200 bg-brand-slateBg text-brand-navy hover:border-brand-gold transition">
                    Khách sạn - Căn hộ - Phòng trọ
                </button>
                <button type="button" data-filter="biet-thu" onclick="filterProjects('biet-thu')" class="project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-bold uppercase border border-slate-200 bg-brand-slateBg text-brand-navy hover:border-brand-gold transition">
                    Biệt thự
                </button>
                <button type="button" data-filter="nha-pho" onclick="filterProjects('nha-pho')" class="project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-bold uppercase border border-slate-200 bg-brand-slateBg text-brand-navy hover:border-brand-gold transition">
                    Nhà phố
                </button>
                <button type="button" data-filter="van-phong" onclick="filterProjects('van-phong')" class="project-tab whitespace-nowrap px-3.5 py-2 rounded-lg text-[11.5px] sm:text-[12.5px] font-bold uppercase border border-slate-200 bg-brand-slateBg text-brand-navy hover:border-brand-gold transition">
                    Văn phòng - Nhà xưởng
                </button>
            </div>

            <!-- Lưới sản phẩm/công trình: 2 cột trên điện thoại, 3 cột trên máy tính, KHÔNG nhãn dán, tên đầy đủ không thiếu chữ -->
            <div id="constructionGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                <!-- Nội dung được render từ dữ liệu 9 ảnh Google Drive thực tế -->
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH DỰ ÁN TỪ DRIVE)       -->
    <!-- 2 CỘT TRÊN MOBILE, 5 CỘT CÂN ĐỐI TRÊN DESKTOP             -->
    <!-- ========================================================= -->
    <section id="du-an-da-nang" class="py-10 lg:py-14 bg-brand-slateBg border-y border-slate-200">
        <div class="fl-container">
            <div class="text-center mb-8">
                <h2 class="fl-section-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-navy">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <p class="text-slate-600 text-xs sm:text-sm mt-3 max-w-2xl mx-auto">
                    Tuyển chọn 10 dự án nhà phố, biệt thự, căn hộ, khách sạn và nhà xưởng thực tế tại các quận huyện TP Đà Nẵng.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 5 cột (2 hàng x 5) cực gọn đẹp trên máy tính, không nhãn dán -->
            <div id="danangProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <!-- Nội dung được render từ 10 ảnh dự án Google Drive tại Đà Nẵng -->
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- BẢNG BÁO GIÁ THAM KHẢO (THEO DANH MỤC WEB MẪU)            -->
    <!-- ========================================================= -->
    <section id="bao-gia" class="py-10 lg:py-14 bg-white">
        <div class="fl-container">
            <div class="text-center mb-8">
                <h2 class="fl-section-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-navy">
                    Báo Giá Thiết Kế &amp; Thi Công
                </h2>
                <p class="text-slate-600 text-xs sm:text-sm mt-3">
                    Đơn giá minh bạch theo từng hạng mục, hỗ trợ khảo sát và lập dự toán chi tiết hoàn toàn miễn phí.
                </p>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <div class="bg-brand-slateBg border border-slate-200 rounded-xl p-4 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-[13px] sm:text-sm font-extrabold uppercase text-brand-navy leading-snug mb-2">Báo Giá Thiết Kế Kiến Trúc</h3>
                        <div class="text-base sm:text-xl font-extrabold text-brand-gold mb-3">Từ 150.000đ / m²</div>
                        <ul class="text-[11.5px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                            <li>• Bản vẽ kiến trúc 2D &amp; 3D mặt tiền</li>
                            <li>• Hồ sơ kết cấu &amp; điện nước M&amp;E</li>
                            <li>• Hỗ trợ hồ sơ xin phép xây dựng</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="block w-full text-center bg-brand-navy hover:bg-brand-gold text-white font-bold text-xs py-2.5 rounded-lg transition">Nhận Báo Giá</a>
                </div>

                <div class="bg-brand-slateBg border border-slate-200 rounded-xl p-4 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-[13px] sm:text-sm font-extrabold uppercase text-brand-navy leading-snug mb-2">Báo Giá Thi Công Phần Thô</h3>
                        <div class="text-base sm:text-xl font-extrabold text-brand-gold mb-3">Từ 3.600.000đ / m²</div>
                        <ul class="text-[11.5px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                            <li>• Vật tư thô chính hãng (Hòa Phát, Sông Gianh)</li>
                            <li>• Nhân công hoàn thiện tiêu chuẩn</li>
                            <li>• Bảo hành kết cấu dài hạn</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="block w-full text-center bg-brand-navy hover:bg-brand-gold text-white font-bold text-xs py-2.5 rounded-lg transition">Nhận Báo Giá</a>
                </div>

                <div class="bg-brand-slateBg border border-slate-200 rounded-xl p-4 sm:p-5 flex flex-col justify-between">
                    <div>
                        <h3 class="text-[13px] sm:text-sm font-extrabold uppercase text-brand-navy leading-snug mb-2">Báo Giá Thi Công Hoàn Thiện</h3>
                        <div class="text-base sm:text-xl font-extrabold text-brand-gold mb-3">Từ 2.400.000đ / m²</div>
                        <ul class="text-[11.5px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                            <li>• Gạch ốp lát, sơn nước cao cấp</li>
                            <li>• Cửa nhôm kính, trần thạch cao</li>
                            <li>• Thiết bị điện, thiết bị vệ sinh</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="block w-full text-center bg-brand-navy hover:bg-brand-gold text-white font-bold text-xs py-2.5 rounded-lg transition">Nhận Báo Giá</a>
                </div>

                <div class="bg-brand-navy text-white border border-brand-navy rounded-xl p-4 sm:p-5 flex flex-col justify-between shadow-md">
                    <div>
                        <h3 class="text-[13px] sm:text-sm font-extrabold uppercase text-brand-gold leading-snug mb-2">Báo Giá Thi Công Trọn Gói</h3>
                        <div class="text-base sm:text-xl font-extrabold text-white mb-3">Từ 5.900.000đ / m²</div>
                        <ul class="text-[11.5px] sm:text-xs text-slate-200 space-y-1.5 mb-4">
                            <li>• Chìa khóa trao tay từ A đến Z</li>
                            <li>• Miễn phí hồ sơ thiết kế kiến trúc</li>
                            <li>• Cam kết không phát sinh chi phí</li>
                        </ul>
                    </div>
                    <a href="#form-bao-gia" class="block w-full text-center bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-xs py-2.5 rounded-lg transition">Đăng Ký Tư Vấn</a>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ                   -->
    <!-- ========================================================= -->
    <section id="form-bao-gia" class="py-10 lg:py-14 bg-brand-navy text-white">
        <div class="fl-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-5">
                    <h2 class="fl-section-heading-left text-xl sm:text-2xl font-extrabold uppercase text-white">
                        Đăng Ký Tư Vấn &amp; Báo Giá Miễn Phí
                    </h2>
                    <p class="text-slate-300 text-xs sm:text-sm leading-relaxed mt-4">
                        Quý khách vui lòng để lại thông tin nhu cầu xây dựng, sửa chữa hoặc thiết kế. Kỹ sư của <strong>Xây Dựng Đỉnh Thiên</strong> sẽ liên hệ khảo sát và gửi bảng dự toán chi tiết nhanh nhất.
                    </p>
                    <div class="mt-5 space-y-3 text-xs sm:text-sm text-slate-200">
                        <div class="flex items-start gap-2.5">
                            <svg class="w-5 h-5 text-brand-gold shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                            <div>
                                <div class="text-slate-400 text-[11px]">Hotline / Zalo tư vấn trực tiếp:</div>
                                <a href="tel:0906500808" class="font-bold text-base text-brand-gold hover:underline">0906.500.808</a>
                            </div>
                        </div>
                        <div class="flex items-start gap-2.5">
                            <svg class="w-5 h-5 text-brand-gold shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                            <div>
                                <div class="text-slate-400 text-[11px]">Văn phòng công ty:</div>
                                <span>Thửa đất số 225, TBĐ 213, Tổ 66, Phường Hòa Khánh, TP Đà Nẵng</span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7">
                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-lg">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qName" class="block text-xs font-bold text-brand-navy mb-1">Họ và tên *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-gold">
                            </div>
                            <div>
                                <label for="qPhone" class="block text-xs font-bold text-brand-navy mb-1">Số điện thoại / Zalo *</label>
                                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0906.500.808" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-gold">
                            </div>
                            <div>
                                <label for="qType" class="block text-xs font-bold text-brand-navy mb-1">Loại công trình</label>
                                <select id="qType" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg bg-white focus:outline-none focus:border-brand-gold">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                                    <option value="Văn phòng - Nhà xưởng">Văn phòng – Nhà xưởng</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo – Sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label for="qBudget" class="block text-xs font-bold text-brand-navy mb-1">Mức đầu tư dự kiến</label>
                                <select id="qBudget" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg bg-white focus:outline-none focus:border-brand-gold">
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                    <option value="1 tỷ - 2 tỷ" selected>1 tỷ – 2 tỷ</option>
                                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                            <div class="sm:col-span-2">
                                <label for="qNote" class="block text-xs font-bold text-brand-navy mb-1">Yêu cầu cụ thể (diện tích, số tầng, địa điểm...)</label>
                                <textarea id="qNote" rows="3" placeholder="Ví dụ: Xây nhà phố 3 tầng diện tích 5x20m tại Hòa Khánh, Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand-gold"></textarea>
                            </div>
                        </div>

                        <div class="mt-4 flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                            <p class="text-[11px] text-slate-500">Thông tin của quý khách được bảo mật tuyệt đối.</p>
                            <button type="submit" class="w-full sm:w-auto bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-sm px-7 py-3 rounded-lg transition shadow">
                                Gửi Yêu Cầu Báo Giá
                            </button>
                        </div>

                        <!-- Hộp thông báo sau khi gửi form (không dùng alert) -->
                        <div id="quoteSuccessBox" class="hidden mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs sm:text-sm font-medium">
                            Cảm ơn quý khách đã gửi yêu cầu báo giá! Đội ngũ kỹ sư Xây Dựng Đỉnh Thiên sẽ liên hệ lại qua số điện thoại bạn cung cấp trong thời gian sớm nhất.
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ                 -->
    <!-- ========================================================= -->
    <section id="tin-tuc" class="py-10 lg:py-14 bg-white">
        <div class="fl-container">
            <div class="text-center mb-8">
                <h2 class="fl-section-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-navy">
                    Tin Tức &amp; Cẩm Nang Xây Dựng
                </h2>
                <p class="text-slate-600 text-xs sm:text-sm mt-3">
                    Chia sẻ kinh nghiệm thiết kế, quy trình kỹ thuật thi công và xu hướng kiến trúc mới nhất.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính, tên bài viết hiển thị đầy đủ -->
            <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Render tự động danh sách bài viết -->
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- DANH MỤC CÁC ĐỐI TÁC                                      -->
    <!-- ========================================================= -->
    <section id="doi-tac" class="py-10 lg:py-12 bg-brand-slateBg border-y border-slate-200">
        <div class="fl-container">
            <div class="text-center mb-7">
                <h2 class="fl-section-heading text-xl sm:text-2xl font-extrabold uppercase text-brand-navy">
                    Đối Tác Cung Ứng Vật Tư
                </h2>
                <p class="text-slate-600 text-xs sm:text-sm mt-3">
                    Hợp tác chiến lược cùng các thương hiệu vật liệu xây dựng hàng đầu, đảm bảo chất lượng cho mọi công trình.
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-6 gap-3 sm:gap-4">
                <div class="bg-white border border-slate-200 rounded-xl h-20 flex flex-col items-center justify-center px-3 hover:border-brand-gold transition">
                    <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">HÒA PHÁT</span>
                    <span class="text-[10px] text-slate-500 uppercase">Thép xây dựng</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl h-20 flex flex-col items-center justify-center px-3 hover:border-brand-gold transition">
                    <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">SÔNG GIANH</span>
                    <span class="text-[10px] text-slate-500 uppercase">Xi măng cao cấp</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl h-20 flex flex-col items-center justify-center px-3 hover:border-brand-gold transition">
                    <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">DULUX</span>
                    <span class="text-[10px] text-slate-500 uppercase">Sơn nội ngoại thất</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl h-20 flex flex-col items-center justify-center px-3 hover:border-brand-gold transition">
                    <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">JOTUN</span>
                    <span class="text-[10px] text-slate-500 uppercase">Sơn &amp; Chống thấm</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl h-20 flex flex-col items-center justify-center px-3 hover:border-brand-gold transition">
                    <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">BÌNH MINH</span>
                    <span class="text-[10px] text-slate-500 uppercase">Hệ thống ống nước</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl h-20 flex flex-col items-center justify-center px-3 hover:border-brand-gold transition">
                    <span class="font-extrabold text-brand-navy text-sm sm:text-base tracking-wide">CADIVI</span>
                    <span class="text-[10px] text-slate-500 uppercase">Dây cáp điện</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- BẢN ĐỒ GOOGLE MAP & FANPAGE NGOÀI TRANG CHỦ               -->
    <!-- ========================================================= -->
    <section id="lien-he" class="py-10 lg:py-14 bg-white">
        <div class="fl-container">
            <div class="text-center mb-8">
                <h2 class="fl-section-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-navy">
                    Bản Đồ Chỉ Đường &amp; Kết Nối Fanpage
                </h2>
                <p class="text-slate-600 text-xs sm:text-sm mt-3">
                    Thửa đất số 225, TBĐ 213, Tổ 66, Phường Hòa Khánh, TP Đà Nẵng &bull; Hotline: 0906.500.808
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 items-stretch">
                <!-- Cột Trái: Google Map trực quan ngoài trang chủ -->
                <div class="bg-brand-slateBg border border-slate-200 rounded-xl overflow-hidden flex flex-col">
                    <div class="px-4 py-3 bg-brand-navy text-white flex items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                            <svg class="w-4 h-4 text-brand-gold shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                            <span>Vị Trí Văn Phòng Xây Dựng Đỉnh Thiên</span>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=Ph%C6%B0%E1%BB%9Dng+H%C3%B2a+Kh%C3%A1nh,+Li%C3%AAn+Chi%E1%BB%83u,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] font-semibold text-brand-gold hover:underline shrink-0">
                            Mở Google Maps &rarr;
                        </a>
                    </div>
                    <div class="w-full flex-1 min-h-[280px] sm:min-h-[320px] bg-slate-200">
                        <iframe
                            title="Bản đồ CÔNG TY TNHH TƯ VẤN XÂY DỰNG TM-DV ĐỈNH THIÊN - Hòa Khánh, TP Đà Nẵng"
                            src="https://maps.google.com/maps?q=Ph%C6%B0%E1%BB%9Dng%20H%C3%B2a%20Kh%C3%A1nh%2C%20Li%C3%AAn%20Chi%E1%BB%83u%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full min-h-[280px] sm:min-h-[320px] border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                        ></iframe>
                    </div>
                    <div class="px-4 py-3 text-xs text-slate-700 bg-white border-t border-slate-200">
                        <strong>Địa chỉ:</strong> Thửa đất số 225, TBĐ 213, Tổ 66, Phường Hòa Khánh, TP Đà Nẵng.
                    </div>
                </div>

                <!-- Cột Phải: Fanpage Facebook trực quan ngoài trang chủ -->
                <div class="bg-brand-slateBg border border-slate-200 rounded-xl overflow-hidden flex flex-col">
                    <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                            <svg class="w-4 h-4 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22.675 0H1.325C.593 0 0 .593 0 1.325v21.351C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.593 1.323-1.325V1.325C24 .593 23.407 0 22.675 0z"/></svg>
                            <span>Fanpage Chính Thức Xây Dựng Đỉnh Thiên</span>
                        </div>
                        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" class="text-[11px] font-semibold bg-white/20 hover:bg-white/30 px-2.5 py-1 rounded transition shrink-0">
                            Xem Fanpage
                        </a>
                    </div>

                    <!-- Khối hiển thị Fanpage chuẩn giao diện Facebook Page Plugin -->
                    <div class="p-4 flex-1 flex flex-col justify-between bg-white">
                        <div>
                            <!-- Ảnh bìa Fanpage -->
                            <div class="relative rounded-lg overflow-hidden h-36 sm:h-40 bg-brand-navy">
                                <img
                                    src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1000"
                                    onerror="handleDriveImgError(this, '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff')"
                                    alt="Ảnh bìa Fanpage Xây Dựng Đỉnh Thiên"
                                    class="w-full h-full object-cover opacity-80"
                                >
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-end gap-3">
                                    <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white flex items-center justify-center shrink-0 shadow">
                                        <svg class="w-8 h-8" viewBox="0 0 64 64" fill="none">
                                            <path d="M32 9L11 32H18.5V52H45.5V32H53L32 9Z" stroke="#D49A2A" stroke-width="3.5" stroke-linejoin="round"/>
                                            <path d="M25 52V33L32 25.5L39 33V52" stroke="#FFFFFF" stroke-width="3" stroke-linejoin="round"/>
                                        </svg>
                                    </div>
                                    <div class="text-white min-w-0">
                                        <div class="font-bold text-sm leading-tight">Xây Dựng Đỉnh Thiên - Đà Nẵng</div>
                                        <div class="text-[11px] text-slate-200 mt-0.5">Công ty Tư vấn &amp; Thi công Xây dựng &bull; 0906.500.808</div>
                                    </div>
                                </div>
                            </div>

                            <!-- Bài đăng cập nhật trên Fanpage -->
                            <div class="mt-4 space-y-2.5 text-xs text-slate-700">
                                <div class="p-3 rounded-lg bg-brand-slateBg border border-slate-200">
                                    <div class="font-bold text-brand-navy mb-1">Cập nhật tiến độ thi công thực tế tại Hòa Khánh, Đà Nẵng</div>
                                    <p class="text-slate-600 leading-relaxed">
                                        Đỉnh Thiên bàn giao giai đoạn kết cấu và chuyển sang hoàn thiện nội ngoại thất cho khách hàng đúng cam kết tiến độ. Liên hệ ngay 0906.500.808 để được tư vấn miễn phí!
                                    </p>
                                </div>
                            </div>
                        </div>

                        <div class="mt-4 pt-3 border-t border-slate-200 flex flex-wrap items-center gap-2.5">
                            <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-[#1877F2] hover:bg-[#1465CC] text-white font-bold text-xs py-2.5 px-4 rounded-lg transition">
                                Thích &amp; Theo Dõi Fanpage
                            </a>
                            <a href="https://zalo.me/0906500808" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-brand-navy hover:bg-brand-gold text-white font-bold text-xs py-2.5 px-4 rounded-lg transition">
                                Nhắn Tin Zalo Tư Vấn
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- FOOTER CHUẨN FLATSOME                                     -->
    <!-- ========================================================= -->
    <footer class="bg-brand-navyDark text-slate-300 pt-10 pb-6 border-t-4 border-brand-gold">
        <div class="fl-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                <!-- Thông tin doanh nghiệp -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-2.5 mb-3">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none">
                            <rect width="64" height="64" rx="10" fill="#1A3E63"/>
                            <path d="M32 9L11 32H18.5V52H45.5V32H53L32 9Z" stroke="#D49A2A" stroke-width="3.2" stroke-linejoin="round"/>
                            <path d="M25 52V33L32 25.5L39 33V52" stroke="#FFFFFF" stroke-width="3" stroke-linejoin="round"/>
                        </svg>
                        <div class="leading-tight">
                            <div class="text-white font-extrabold text-base">ĐỈNH THIÊN</div>
                            <div class="text-brand-gold text-[10px] font-bold tracking-widest uppercase">XÂY DỰNG &bull; TM-DV</div>
                        </div>
                    </div>
                    <h3 class="text-white font-bold text-sm uppercase mb-2">
                        CÔNG TY TNHH TƯ VẤN XÂY DỰNG TM-DV ĐỈNH THIÊN
                    </h3>
                    <ul class="space-y-1.5 text-xs leading-relaxed">
                        <li><strong class="text-white">Mã số thuế:</strong> 0402186266</li>
                        <li><strong class="text-white">Địa chỉ:</strong> Thửa đất số 225, TBĐ 213, Tổ 66, Phường Hòa Khánh, TP Đà Nẵng</li>
                        <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0906500808" class="text-brand-gold font-bold hover:underline">0906.500.808</a></li>
                        <li><strong class="text-white">Website:</strong> xaydungdinhthien.com</li>
                    </ul>
                </div>

                <!-- Lĩnh vực hoạt động -->
                <div class="lg:col-span-4">
                    <h4 class="text-white font-bold text-sm uppercase mb-3 pb-2 border-b border-white/10">Lĩnh Vực Hoạt Động</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">• Thi công phần thô nhà phố, biệt thự</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">• Thi công hoàn thiện &amp; xây nhà trọn gói</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">• Thi công nội thất, khách sạn, căn hộ, nhà xưởng</a></li>
                    </ul>
                </div>

                <!-- Danh mục nhanh -->
                <div class="lg:col-span-3">
                    <h4 class="text-white font-bold text-sm uppercase mb-3 pb-2 border-b border-white/10">Liên Kết Nhanh</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-gold transition">• Công trình thực tế</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-gold transition">• Các dự án tại Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-gold transition">• Bảng báo giá xây dựng</a></li>
                        <li><a href="#tin-tuc" class="hover:text-brand-gold transition">• Tin tức &amp; Cẩm nang</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 text-center text-[11px] sm:text-xs text-slate-400">
                Copyright &copy; 2026 <span class="text-white font-semibold">CÔNG TY TNHH TƯ VẤN XÂY DỰNG TM-DV ĐỈNH THIÊN</span> &bull; xaydungdinhthien.com
            </div>
        </div>
    </footer>

    <!-- ========================================================= -->
    <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE          -->
    <!-- TƯƠNG THÍCH TỐT TRÊN CẢ MÁY TÍNH VÀ ĐIỆN THOẠI            -->
    <!-- ========================================================= -->
    <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0906500808" target="_blank" rel="noopener noreferrer" aria-label="Liên hệ Zalo 0906.500.808" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
            <span class="hidden md:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
            <span class="w-7 h-7 sm:w-7 sm:h-7 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" aria-label="Fanpage Facebook Xây Dựng Đỉnh Thiên" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1360C9] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
            <span class="hidden md:inline text-xs font-bold whitespace-nowrap">Facebook</span>
            <span class="w-7 h-7 sm:w-7 sm:h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M22.675 0H1.325C.593 0 0 .593 0 1.325v21.351C0 23.407.593 24 1.325 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116c.73 0 1.323-.593 1.323-1.325V1.325C24 .593 23.407 0 22.675 0z"/></svg>
            </span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0906500808" aria-label="Gọi Hotline 0906.500.808" class="hotline-pulse flex items-center gap-2 bg-brand-gold hover:bg-brand-goldHover text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition">
            <span class="hidden md:inline text-xs font-extrabold whitespace-nowrap">0906.500.808</span>
            <span class="w-7 h-7 sm:w-7 sm:h-7 rounded-full bg-white text-brand-navy flex items-center justify-center shrink-0">
                <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.4" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            </span>
        </a>
    </div>

    <!-- ========================================================= -->
    <!-- MODAL XEM CHI TIẾT CÔNG TRÌNH / DỰ ÁN / BÀI VIẾT          -->
    <!-- ========================================================= -->
    <div id="detailModal" class="hidden fixed inset-0 z-50 bg-black/70 backdrop-blur-sm flex items-center justify-center p-3 sm:p-5" onclick="closeModalOnBackdrop(event)">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="flex items-center justify-between px-4 sm:px-6 py-3.5 border-b border-slate-200 sticky top-0 bg-white z-10">
                <h3 id="modalTitle" class="font-extrabold text-brand-navy text-sm sm:text-base pr-4"></h3>
                <button type="button" onclick="closeDetailModal()" aria-label="Đóng" class="w-8 h-8 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center shrink-0">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M6 18L18 6M6 6l12 12"/></svg>
                </button>
            </div>
            <div class="p-4 sm:p-6">
                <div class="rounded-lg overflow-hidden bg-slate-100 mb-4">
                    <img id="modalImage" src="" alt="" class="w-full max-h-[380px] object-cover">
                </div>
                <div id="modalMeta" class="text-xs font-semibold text-brand-gold mb-2"></div>
                <p id="modalDesc" class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-5"></p>
                <div class="flex flex-wrap gap-2.5 pt-3 border-t border-slate-200">
                    <a href="tel:0906500808" class="flex-1 text-center bg-brand-navy hover:bg-brand-navyLight text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg transition">
                        Gọi Tư Vấn: 0906.500.808
                    </a>
                    <a href="#form-bao-gia" onclick="closeDetailModal()" class="flex-1 text-center bg-brand-gold hover:bg-brand-goldHover text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg transition">
                        Nhận Báo Giá Công Trình Này
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ========================================================= -->
    <!-- JAVASCRIPT: DỮ LIỆU 19 ẢNH DRIVE, SLIDER, LỌC DANH MỤC    -->
    <!-- ========================================================= -->
    <script>
        /**
         * Xử lý fallback tự động cho ảnh Google Drive
         * Ưu tiên: drive.google.com/thumbnail -> lh3.googleusercontent.com -> ảnh dự phòng có màu nhận diện
         */
        function handleDriveImgError(imgEl, fileId) {
            try {
                var step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
                if (step === 0) {
                    imgEl.setAttribute('data-fallback-step', '1');
                    imgEl.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
                } else {
                    imgEl.onerror = null;
                    imgEl.src = 'https://placehold.co/800x600/0F2B46/D49A2A?text=Xay+Dung+Dinh+Thien';
                }
            } catch (err) {
                imgEl.onerror = null;
            }
        }

        function getDriveThumb(fileId) {
            return 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
        }

        /**
         * 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG TỪ GOOGLE DRIVE
         * Phân loại đúng theo danh mục web mẫu tintruongthinh.com
         */
        var constructionProjects = [
            {
                id: 'tc-1',
                fileId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                title: 'Thi Công Phần Thô & Kết Cấu Nhà Phố Hiện Đại',
                location: 'Quận Liên Chiểu, TP Đà Nẵng',
                desc: 'Hạng mục thi công móng băng, lắp dựng cốp pha, cốt thép sàn dầm và đổ bê tông thương phẩm đúng quy trình kỹ thuật, đảm bảo độ bền vững tối đa cho công trình.'
            },
            {
                id: 'tc-2',
                fileId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                title: 'Thi Công Khung Cột Bê Tông Cốt Thép Nhà Phố 3 Tầng',
                location: 'Phường Hòa Khánh, TP Đà Nẵng',
                desc: 'Giám sát trực tiếp đội ngũ kỹ sư Đỉnh Thiên trong công tác gia công cốt thép, nghiệm thu độ sụt bê tông và bảo dưỡng kết cấu đạt chuẩn.'
            },
            {
                id: 'tc-3',
                fileId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                category: 'khach-san',
                categoryName: 'Khách sạn - Căn hộ - Phòng trọ',
                title: 'Thi Công Trọn Gói Căn Hộ Cho Thuê Cao Cấp',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Thi công trọn gói từ phần thô đến hoàn thiện nội thất căn hộ cho thuê, tối ưu công năng khai thác và hệ thống điện nước PCCC đồng bộ.'
            },
            {
                id: 'tc-4',
                fileId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                category: 'biet-thu',
                categoryName: 'Biệt thự',
                title: 'Thi Công Hoàn Thiện Biệt Thự 2 Mặt Tiền',
                location: 'Khu Đô Thị Hòa Xuân, TP Đà Nẵng',
                desc: 'Hoàn thiện mặt tiền kiến trúc sang trọng, ốp đá tự nhiên, hệ cửa nhôm kính cao cấp và chống thấm toàn diện cho công trình biệt thự.'
            },
            {
                id: 'tc-5',
                fileId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                category: 'nha-pho',
                categoryName: 'Nhà phố',
                title: 'Xây Dựng Trọn Gói Nhà Phố Liền Kề',
                location: 'Quận Cẩm Lệ, TP Đà Nẵng',
                desc: 'Bàn giao chìa khóa trao tay công trình nhà phố hiện đại, bố trí giếng trời thông thoáng, tận dụng tối đa ánh sáng và gió tự nhiên.'
            },
            {
                id: 'tc-6',
                fileId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                category: 'khach-san',
                categoryName: 'Khách sạn - Căn hộ - Phòng trọ',
                title: 'Thi Công Kết Cấu & Hoàn Thiện Khách Sạn Mini',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Công trình khách sạn quy mô 5 tầng được Đỉnh Thiên thi công đảm bảo tiến độ gấp rút, thẩm mỹ cao và tối ưu chi phí cho chủ đầu tư.'
            },
            {
                id: 'tc-7',
                fileId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                category: 'van-phong',
                categoryName: 'Văn phòng - Nhà xưởng',
                title: 'Thi Công Nhà Xưởng & Văn Phòng Điều Hành',
                location: 'KCN Hòa Khánh, TP Đà Nẵng',
                desc: 'Thi công nền bê tông chịu tải, kết cấu khung thép tiền chế kết hợp khối văn phòng làm việc hiện đại và chuẩn an toàn lao động.'
            },
            {
                id: 'tc-8',
                fileId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                category: 'biet-thu',
                categoryName: 'Biệt thự',
                title: 'Thi Công Biệt Thự Hiện Đại Kết Hợp Sân Vườn',
                location: 'Khu Nam Việt Á, TP Đà Nẵng',
                desc: 'Thiết kế và thi công đồng bộ kiến trúc ngoại thất, cảnh quan sân vườn và hồ cá tạo nên không gian nghỉ dưỡng đẳng cấp.'
            },
            {
                id: 'tc-9',
                fileId: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                category: 'van-phong',
                categoryName: 'Văn phòng - Nhà xưởng',
                title: 'Cải Tạo & Thi Công Trọn Gói Văn Phòng Công Ty',
                location: 'Quận Hải Châu, TP Đà Nẵng',
                desc: 'Nâng cấp kết cấu, thi công trần thạch cao, vách kính cường lực, hệ thống chiếu sáng và nội thất văn phòng chuyên nghiệp.'
            }
        ];

        /**
         * 10 ẢNH DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG TỪ GOOGLE DRIVE
         */
        var danangProjects = [
            {
                id: 'dn-1',
                fileId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Dự Án Nhà Phố Hiện Đại – Hòa Khánh, Liên Chiểu',
                location: 'Phường Hòa Khánh, TP Đà Nẵng',
                desc: 'Công trình nhà phố thiết kế mặt tiền tinh tế, công năng 3 tầng đầy đủ tiện nghi do Xây Dựng Đỉnh Thiên thi công trọn gói.'
            },
            {
                id: 'dn-2',
                fileId: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Dự Án Biệt Thự Phố – Khu Đô Thị Hòa Xuân',
                location: 'Quận Cẩm Lệ, TP Đà Nẵng',
                desc: 'Biệt thự phố phong cách hiện đại tại Hòa Xuân, hoàn thiện vật liệu cao cấp, bàn giao đúng tiến độ cam kết.'
            },
            {
                id: 'dn-3',
                fileId: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Dự Án Căn Hộ Dịch Vụ – Quận Sơn Trà',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Tòa nhà căn hộ dịch vụ cao cấp gần biển Mỹ Khê, tối ưu diện tích phòng và hiệu quả kinh doanh lâu dài.'
            },
            {
                id: 'dn-4',
                fileId: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Dự Án Khách Sạn Biển – Mỹ An, Ngũ Hành Sơn',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Công trình khách sạn kiến trúc sang trọng, chú trọng cách âm, chống thấm và hệ thống kỹ thuật tiêu chuẩn.'
            },
            {
                id: 'dn-5',
                fileId: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Dự Án Nhà Phố 3 Tầng – Khu Phước Lý',
                location: 'Khu đô thị Phước Lý, TP Đà Nẵng',
                desc: 'Nhà ở gia đình 3 tầng thoáng sáng, kết cấu kiên cố, tối ưu chi phí vật tư hoàn thiện.'
            },
            {
                id: 'dn-6',
                fileId: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Dự Án Nhà Xưởng & Kho Vận – KCN Hòa Khánh',
                location: 'KCN Hòa Khánh, TP Đà Nẵng',
                desc: 'Thi công hạng mục nhà xưởng công nghiệp kết hợp văn phòng điều hành đạt tiêu chuẩn kỹ thuật nghiêm ngặt.'
            },
            {
                id: 'dn-7',
                fileId: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Dự Án Biệt Thự Ven Sông – Khu Nam Việt Á',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Không gian biệt thự đẳng cấp hòa hợp thiên nhiên, hoàn thiện sắc nét từng chi tiết kiến trúc.'
            },
            {
                id: 'dn-8',
                fileId: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Dự Án Nhà Ở Kết Hợp Kinh Doanh – Hải Châu',
                location: 'Quận Hải Châu, TP Đà Nẵng',
                desc: 'Mô hình shophouse 4 tầng trung tâm thành phố, đáp ứng đồng thời nhu cầu mở showroom và sinh hoạt gia đình.'
            },
            {
                id: 'dn-9',
                fileId: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Dự Án Căn Hộ Cho Thuê – Quận Thanh Khê',
                location: 'Quận Thanh Khê, TP Đà Nẵng',
                desc: 'Tòa căn hộ tiện nghi với thiết kế hiện đại, thông gió tự nhiên tốt và chi phí bảo trì thấp.'
            },
            {
                id: 'dn-10',
                fileId: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Dự Án Văn Phòng Công Ty – Trung Tâm Đà Nẵng',
                location: 'TP Đà Nẵng',
                desc: 'Thiết kế và thi công hoàn thiện trụ sở văn phòng chuyên nghiệp, tối ưu ánh sáng và diện tích làm việc.'
            }
        ];

        /**
         * DANH SÁCH BÀI VIẾT TRANG CHỦ (PHONG CÁCH TIN TỨC XÂY DỰNG)
         */
        var newsArticles = [
            {
                id: 'bv-1',
                fileId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                date: '18/11/2026',
                title: 'Kinh Nghiệm Xây Nhà Trọn Gói Tại Đà Nẵng Không Phát Sinh Chi Phí',
                excerpt: 'Tổng hợp các bước chuẩn bị hồ sơ thiết kế, lựa chọn vật tư và ký kết hợp đồng xây dựng minh bạch giúp gia chủ tiết kiệm ngân sách.',
                content: 'Để xây nhà trọn gói tại Đà Nẵng đạt chất lượng cao và không phát sinh chi phí, chủ đầu tư cần xác định rõ công năng sử dụng trước khi thiết kế, yêu cầu nhà thầu bóc tách bảng dự toán chủng loại vật tư rõ ràng và nghiệm thu chặt chẽ từng giai đoạn từ móng, thân đến hoàn thiện. Xây Dựng Đỉnh Thiên luôn đồng hành tư vấn miễn phí giúp khách hàng an tâm từ bước đầu tiên.'
            },
            {
                id: 'bv-2',
                fileId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                date: '12/11/2026',
                title: 'Hướng Dẫn Bảo Dưỡng Bê Tông Móng Và Sàn Đúng Tiêu Chuẩn Kỹ Thuật',
                excerpt: 'Quy trình giữ ẩm, che chắn và kiểm tra cường độ bê tông sau khi đổ giúp kết cấu công trình đạt độ bền tối đa theo thời gian.',
                content: 'Bảo dưỡng bê tông trong 7 ngày đầu sau khi đổ là yếu tố then chốt tránh hiện tượng rạn nứt bề mặt do mất nước đột ngột dưới nắng gió miền Trung. Kỹ sư Đỉnh Thiên luôn áp dụng quy trình tưới nước giữ ẩm đều đặn, che phủ bao bố và chỉ tháo cốp pha khi bê tông đạt đủ cường độ theo tiêu chuẩn TCVN.'
            },
            {
                id: 'bv-3',
                fileId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                date: '05/11/2026',
                title: '03 Lưu Ý Quan Trọng Khi Chống Thấm Nhà Phố Mùa Mưa Bão Miền Trung',
                excerpt: 'Giải pháp chống thấm sàn mái, tường ngoài và khu vực nhà vệ sinh triệt để ngay từ giai đoạn thi công phần thô.',
                content: 'Khí hậu Đà Nẵng có mùa mưa bão kéo dài đòi hỏi công tác chống thấm phải được xử lý kỹ ngay từ khâu xây tô. Cần sử dụng vữa trộn phụ gia chống thấm, bo góc chân tường, quét 2-3 lớp màng chống thấm đàn hồi và thử nước nghiệm thu tối thiểu 48 giờ trước khi lát gạch hoàn thiện.'
            },
            {
                id: 'bv-4',
                fileId: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                date: '29/10/2026',
                title: 'Xu Hướng Thiết Kế Kiến Trúc & Nội Thất Nhà Phố Hiện Đại 2026',
                excerpt: 'Phong cách tối giản, không gian mở kết hợp mảng xanh giếng trời đang trở thành lựa chọn hàng đầu của các gia đình trẻ.',
                content: 'Thiết kế nhà phố năm 2026 chú trọng sự thông thoáng tự nhiên, hạn chế vách ngăn kín và ưu tiên vật liệu bền vững như đá tự nhiên, gỗ công nghiệp chống ẩm và hệ cửa kính lớn. Điều này vừa nâng cao thẩm mỹ sang trọng vừa giúp tiết kiệm điện năng chiếu sáng và điều hòa hàng tháng.'
            }
        ];

        /**
         * Render 9 Công Trình Thực Tế (2 cột mobile, 3 cột desktop, KHÔNG nhãn dán, tên hiển thị đủ chữ)
         */
        function renderConstructionProjects(filterKey) {
            var grid = document.getElementById('constructionGrid');
            if (!grid) return;

            var filtered = filterKey === 'all'
                ? constructionProjects
                : constructionProjects.filter(function(item) { return item.category === filterKey; });

            var html = filtered.map(function(item) {
                return '' +
                    '<article onclick="openItemModal(\'construction\', \'' + item.id + '\')" class="fl-img-zoom cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md hover:border-brand-gold transition flex flex-col">' +
                        '<div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
                            '<img src="' + getDriveThumb(item.fileId) + '" onerror="handleDriveImgError(this, \'' + item.fileId + '\')" alt="' + item.title + '" loading="lazy" class="w-full h-full object-cover">' +
                        '</div>' +
                        '<div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">' +
                            '<h3 class="text-[12.5px] sm:text-[14.5px] font-bold text-brand-navy leading-snug break-words hover:text-brand-gold transition">' +
                                item.title +
                            '</h3>' +
                            '<p class="text-[11px] sm:text-xs text-slate-500 mt-1.5">' + item.location + '</p>' +
                        '</div>' +
                    '</article>';
            }).join('');

            grid.innerHTML = html;
        }

        /**
         * Lọc danh mục Công trình thực tế
         */
        function filterProjects(categoryKey) {
            renderConstructionProjects(categoryKey);
            var tabs = document.querySelectorAll('.project-tab');
            tabs.forEach(function(btn) {
                var isActive = btn.getAttribute('data-filter') === categoryKey;
                if (isActive) {
                    btn.classList.remove('bg-brand-slateBg', 'text-brand-navy', 'border-slate-200');
                    btn.classList.add('bg-brand-navy', 'text-white', 'border-brand-navy');
                } else {
                    btn.classList.remove('bg-brand-navy', 'text-white', 'border-brand-navy');
                    btn.classList.add('bg-brand-slateBg', 'text-brand-navy', 'border-slate-200');
                }
            });
        }

        /**
         * Render 10 Dự Án Tại Đà Nẵng (2 cột mobile, 5 cột desktop, KHÔNG nhãn dán, tên không thiếu chữ)
         */
        function renderDanangProjects() {
            var grid = document.getElementById('danangProjectsGrid');
            if (!grid) return;

            grid.innerHTML = danangProjects.map(function(item) {
                return '' +
                    '<article onclick="openItemModal(\'danang\', \'' + item.id + '\')" class="fl-img-zoom cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md hover:border-brand-gold transition flex flex-col">' +
                        '<div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">' +
                            '<img src="' + getDriveThumb(item.fileId) + '" onerror="handleDriveImgError(this, \'' + item.fileId + '\')" alt="' + item.title + '" loading="lazy" class="w-full h-full object-cover">' +
                        '</div>' +
                        '<div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">' +
                            '<h3 class="text-[12px] sm:text-[13px] font-bold text-brand-navy leading-snug break-words hover:text-brand-gold transition">' +
                                item.title +
                            '</h3>' +
                            '<p class="text-[10.5px] sm:text-[11px] text-slate-500 mt-1.5">' + item.location + '</p>' +
                        '</div>' +
                    '</article>';
            }).join('');
        }

        /**
         * Render Danh Mục Bài Viết Trang Chủ
         */
        function renderArticles() {
            var grid = document.getElementById('articlesGrid');
            if (!grid) return;

            grid.innerHTML = newsArticles.map(function(art) {
                return '' +
                    '<article onclick="openItemModal(\'article\', \'' + art.id + '\')" class="fl-img-zoom cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md hover:border-brand-gold transition flex flex-col">' +
                        '<div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">' +
                            '<img src="' + getDriveThumb(art.fileId) + '" onerror="handleDriveImgError(this, \'' + art.fileId + '\')" alt="' + art.title + '" loading="lazy" class="w-full h-full object-cover">' +
                        '</div>' +
                        '<div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">' +
                            '<div>' +
                                '<div class="text-[10.5px] text-brand-gold font-semibold mb-1">' + art.date + '</div>' +
                                '<h3 class="text-[12.5px] sm:text-[14px] font-bold text-brand-navy leading-snug break-words hover:text-brand-gold transition">' +
                                    art.title +
                                '</h3>' +
                                '<p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed mt-1.5 hidden sm:block">' +
                                    art.excerpt +
                                '</p>' +
                            '</div>' +
                            '<div class="text-[11px] font-bold text-brand-navy mt-2.5">Xem chi tiết &rarr;</div>' +
                        '</div>' +
                    '</article>';
            }).join('');
        }

        /**
         * Mở Modal xem chi tiết công trình / dự án / bài viết
         */
        function openItemModal(type, id) {
            var item = null;
            var metaText = '';
            var descText = '';

            if (type === 'construction') {
                item = constructionProjects.find(function(x) { return x.id === id; });
                if (item) {
                    metaText = item.categoryName + ' • ' + item.location;
                    descText = item.desc;
                }
            } else if (type === 'danang') {
                item = danangProjects.find(function(x) { return x.id === id; });
                if (item) {
                    metaText = 'Dự án tại Đà Nẵng • ' + item.location;
                    descText = item.desc;
                }
            } else if (type === 'article') {
                item = newsArticles.find(function(x) { return x.id === id; });
                if (item) {
                    metaText = 'Tin tức xây dựng • Ngày đăng: ' + item.date;
                    descText = item.content;
                }
            }

            if (!item) return;

            var modal = document.getElementById('detailModal');
            var modalImg = document.getElementById('modalImage');
            document.getElementById('modalTitle').textContent = item.title;
            document.getElementById('modalMeta').textContent = metaText;
            document.getElementById('modalDesc').textContent = descText;

            modalImg.removeAttribute('data-fallback-step');
            modalImg.onerror = function() { handleDriveImgError(modalImg, item.fileId); };
            modalImg.src = getDriveThumb(item.fileId);
            modalImg.alt = item.title;

            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeDetailModal() {
            document.getElementById('detailModal').classList.add('hidden');
            document.body.style.overflow = '';
        }

        function closeModalOnBackdrop(event) {
            if (event.target.id === 'detailModal') {
                closeDetailModal();
            }
        }

        /**
         * Quản lý 2 Banner Tự Trượt Chuyên Nghiệp + Hỗ Trợ Vuốt Trên Điện Thoại
         */
        var currentSlide = 0;
        var slideInterval = null;

        function showSlide(index) {
            var slides = document.querySelectorAll('.hero-slide');
            var dots = document.querySelectorAll('.hero-dot');
            if (!slides.length) return;

            currentSlide = (index + slides.length) % slides.length;

            slides.forEach(function(slide, i) {
                if (i === currentSlide) {
                    slide.classList.add('is-active');
                } else {
                    slide.classList.remove('is-active');
                }
            });

            dots.forEach(function(dot, i) {
                if (i === currentSlide) {
                    dot.classList.remove('w-2.5', 'bg-white/60');
                    dot.classList.add('w-6', 'bg-brand-gold');
                } else {
                    dot.classList.remove('w-6', 'bg-brand-gold');
                    dot.classList.add('w-2.5', 'bg-white/60');
                }
            });
        }

        function nextSlide() {
            showSlide(currentSlide + 1);
            resetAutoSlide();
        }

        function prevSlide() {
            showSlide(currentSlide - 1);
            resetAutoSlide();
        }

        function goToSlide(index) {
            showSlide(index);
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(function() {
                showSlide(currentSlide + 1);
            }, 5500);
        }

        /* Hỗ trợ vuốt cảm ứng trái/phải cho banner trên điện thoại */
        (function initTouchSwipe() {
            var slider = document.getElementById('heroSlider');
            if (!slider) return;
            var startX = 0;
            slider.addEventListener('touchstart', function(e) {
                startX = e.changedTouches[0].screenX;
            }, { passive: true });
            slider.addEventListener('touchend', function(e) {
                var diff = e.changedTouches[0].screenX - startX;
                if (Math.abs(diff) > 45) {
                    if (diff < 0) nextSlide();
                    else prevSlide();
                }
            }, { passive: true });
        })();

        /**
         * Điều khiển Menu Mobile
         */
        var mobileMenuBtn = document.getElementById('mobileMenuBtn');
        var mobileMenu = document.getElementById('mobileMenu');
        if (mobileMenuBtn && mobileMenu) {
            mobileMenuBtn.addEventListener('click', function() {
                mobileMenu.classList.toggle('hidden');
            });
        }
        function closeMobileMenu() {
            if (mobileMenu) mobileMenu.classList.add('hidden');
        }

        /**
         * Xử lý gửi Form Yêu Cầu Báo Giá (không dùng alert)
         */
        function submitQuoteForm(event) {
            event.preventDefault();
            var successBox = document.getElementById('quoteSuccessBox');
            var form = document.getElementById('quoteForm');
            if (successBox) {
                successBox.classList.remove('hidden');
            }
            if (form) {
                form.reset();
            }
        }

        /* Khởi tạo toàn bộ nội dung khi tải trang */
        window.addEventListener('DOMContentLoaded', function() {
            renderConstructionProjects('all');
            renderDanangProjects();
            renderArticles();
            showSlide(0);
            resetAutoSlide();
        });
    </script>
</body>
</html>
