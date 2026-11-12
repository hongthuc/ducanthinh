<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Đức An Thịnh Decor - Thiết Kế & Thi Công Nội Thất, Quảng Cáo, Xây Dựng Trọn Gói Đà Nẵng | ducanthinh.com</title>
    <meta name="description" content="Đức An Thịnh Decor (ducanthinh.com) - Chuyên Thiết Kế & Thi Công Xây Dựng, Quảng Cáo, Nội Thất Trọn Gói Shop, Showroom, Spa, Tiệm Nail, Hair Salon, Coffee, Photobooth, Music Box, Văn Phòng, Nhà Hàng tại Đà Nẵng. Hotline: 0981.708.494">
    
    <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://ducanthinh.com/">
    <meta property="og:title" content="Đức An Thịnh Decor - Thiết Kế & Thi Công Nội Thất, Quảng Cáo Trọn Gói">
    <meta property="og:description" content="Thiết Kế & Thi Công Xây Dựng - Quảng Cáo - Nội Thất Trọn Gói Shop, Spa, Tiệm Nail, Hair Salon, Coffee, Văn Phòng, Nhà Hàng tại Đà Nẵng. Hotline: 0981.708.494">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1MhjyXTntX8l9fCvcrilImo1RjWkZ3pIk=w1200">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1MhjyXTntX8l9fCvcrilImo1RjWkZ3pIk=w1200">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1MhjyXTntX8l9fCvcrilImo1RjWkZ3pIk=w300">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            dark: '#16202E',      /* Xanh đen than chì sang trọng theo tông logo & PenConcept */
                            navy: '#1E293B',      /* Xanh đậm kiến trúc */
                            gold: '#C59B27',      /* Vàng đồng kim loại chủ đạo từ logo */
                            goldLight: '#E5C158', /* Vàng sáng điểm nhấn */
                            goldDark: '#9E7816',  /* Vàng đậm hover */
                            bgLight: '#F8FAFC',   /* Nền xám trắng tinh tế chuẩn Flatsome */
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Khóa tràn viền tuyệt đối và chống lệch phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
            background-color: #F8FAFC;
            color: #1E293B;
        }

        /* Khung chuẩn Flatsome: 95% chiều ngang màn hình trên máy tính, 100% có padding gọn trên điện thoại */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tiêu đề Section chuẩn UX Builder Flatsome (Line + Text Center) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            margin-bottom: 1.5rem;
            text-align: center;
        }
        .flatsome-section-title b {
            display: block;
            flex: 1;
            height: 2px;
            background-color: #E2E8F0;
        }
        .flatsome-section-title span {
            padding: 0 16px;
            font-family: 'Montserrat', sans-serif;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 0.03em;
            color: #16202E;
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, tuyệt đối không xuống dòng từng chữ trong tên danh mục */
        .nav-cat-item {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            line-height: 1.2;
            transition: all 0.2s ease;
        }

        /* Nút danh mục ở trang chủ nhỏ gọn, viết liền không gãy dòng tên danh mục */
        .home-cat-pill {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s ease;
        }

        /* Đảm bảo tên sản phẩm hiển thị đầy đủ, không bị cắt chữ (...) và không tràn khung */
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
        }

        /* Hiệu ứng nút nổi Zalo, Facebook, Hotline */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(197, 155, 39, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(197, 155, 39, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(197, 155, 39, 0); }
        }
        .pulse-btn {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="font-sans antialiased selection:bg-brand-gold selection:text-white">

    <!-- ==========================================
         TOP BAR (Chuẩn Flatsome Top Bar đơn giản)
         ========================================== -->
    <div class="bg-brand-dark text-slate-200 text-[11px] sm:text-xs py-2 border-b border-slate-800">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 sm:gap-4 truncate max-w-full">
                <span class="inline-flex items-center gap-1.5 text-brand-goldLight font-medium truncate">
                    <i class="fa-solid fa-building-shield"></i>
                    <span>ĐỨC AN THỊNH DECOR - THIẾT KẾ & THI CÔNG TRỌN GÓI UY TÍN TẠI ĐÀ NẴNG</span>
                </span>
                <span class="hidden xl:inline-flex items-center gap-1.5 text-slate-300">
                    <i class="fa-solid fa-location-dot text-brand-gold"></i>
                    <span>VP + XSX 1: 19 Ngô Chân Lưu, P. Hoà Khánh | XSX 2: 121 Nguyễn Bảo, Hoà Châu</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-slate-300 shrink-0">
                <a href="https://ducanthinh.com" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-globe mr-1 text-brand-gold"></i>ducanthinh.com</a>
                <span>|</span>
                <a href="https://www.facebook.com/profile.php?id=61585341208717" target="_blank" rel="noopener noreferrer" class="hover:text-brand-goldLight transition">
                    <i class="fa-brands fa-facebook mr-1 text-blue-400"></i>Fanpage Đức An Thịnh Decor
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER & NAVIGATION (Logo nhỏ gọn, KHÔNG để nút gọi ngay để tránh tràn viền, Danh mục viết liền trên 1 hàng chữ nhỏ gọn)
         ========================================== -->
    <header class="sticky top-0 z-40 bg-white shadow-sm border-b border-slate-200">
        <div class="flatsome-container">
            <div class="flex items-center justify-between py-2 lg:py-2.5 gap-3">
                
                <!-- Logo chỉnh gọn nhỏ lại + Tên thương hiệu -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg overflow-hidden border border-brand-gold/40 bg-brand-dark flex items-center justify-center shrink-0 p-0.5 shadow-sm">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1MhjyXTntX8l9fCvcrilImo1RjWkZ3pIk=w300" 
                            data-drive-id="1MhjyXTntX8l9fCvcrilImo1RjWkZ3pIk"
                            alt="Logo Đức An Thịnh Decor" 
                            class="w-full h-full object-contain rounded"
                            onerror="handleDriveImgError(this, 'https://placehold.co/120x120/16202E/C59B27?text=DAT')"
                        >
                    </div>
                    <div class="leading-tight">
                        <span class="block font-heading font-extrabold text-brand-dark text-sm sm:text-base tracking-tight group-hover:text-brand-gold transition">
                            ĐỨC AN THỊNH <span class="text-brand-gold">DECOR</span>
                        </span>
                        <span class="block text-[10px] sm:text-[11px] text-slate-500 font-medium">
                            ducanthinh.com • Nội Thất & Quảng Cáo
                        </span>
                    </div>
                </a>

                <!-- Menu Danh Mục Máy Tính: chữ nhỏ gọn, viết liền không gãy dòng tên danh mục, tự cân đối trên 1 hàng (hoặc xuống hàng 2 nguyên cụm) -->
                <nav class="hidden lg:flex flex-wrap items-center justify-end gap-x-1 xl:gap-x-1.5 gap-y-1 flex-1">
                    <a href="#trang-chu" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-bold text-brand-gold bg-amber-50/80 rounded">Trang Chủ</a>
                    <a href="#danh-muc-san-pham" onclick="filterCategory('shop')" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-semibold text-slate-700 hover:text-brand-gold rounded">Shop - Showroom</a>
                    <a href="#danh-muc-san-pham" onclick="filterCategory('spa')" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-semibold text-slate-700 hover:text-brand-gold rounded">Thẩm Mỹ Viện - Spa</a>
                    <a href="#danh-muc-san-pham" onclick="filterCategory('nail')" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-semibold text-slate-700 hover:text-brand-gold rounded">Tiệm Nail - Hair Salon</a>
                    <a href="#danh-muc-san-pham" onclick="filterCategory('cafe')" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-semibold text-slate-700 hover:text-brand-gold rounded">Nhà Hàng - Coffee</a>
                    <a href="#danh-muc-san-pham" onclick="filterCategory('photobooth')" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-semibold text-slate-700 hover:text-brand-gold rounded">Photobooth - Music Box - Pilates</a>
                    <a href="#danh-muc-san-pham" onclick="filterCategory('quangcao')" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-semibold text-slate-700 hover:text-brand-gold rounded">Văn Phòng - Quảng Cáo</a>
                    <a href="#du-an-da-nang" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-semibold text-slate-700 hover:text-brand-gold rounded">Dự Án Đà Nẵng</a>
                    <a href="#doi-tac" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-semibold text-slate-700 hover:text-brand-gold rounded">Đối Tác</a>
                    <a href="#tin-tuc" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-semibold text-slate-700 hover:text-brand-gold rounded">Bài Viết</a>
                    <a href="#form-bao-gia" class="nav-cat-item px-2 py-1 text-[11px] xl:text-[12px] font-semibold text-slate-700 hover:text-brand-gold rounded">Báo Giá</a>
                </nav>

                <!-- Nút mở Menu trên Điện Thoại (Không để nút gọi ngay trên header để tránh tràn viền) -->
                <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Menu danh mục" class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-slate-100 text-brand-dark hover:bg-brand-gold hover:text-white transition text-xs font-bold shrink-0">
                    <i class="fa-solid fa-bars text-sm"></i>
                    <span>DANH MỤC</span>
                </button>
            </div>
        </div>

        <!-- Thanh trượt nhanh danh mục trên Điện Thoại (Giúp khách xem trên điện thoại chọn nhanh và đẹp mắt) -->
        <div class="lg:hidden bg-slate-50 border-t border-slate-200/80 py-1.5">
            <div class="flatsome-container flex items-center gap-1.5 overflow-x-auto no-scrollbar">
                <a href="#danh-muc-san-pham" onclick="filterCategory('all')" class="nav-cat-item px-2.5 py-1 rounded bg-brand-dark text-brand-goldLight text-[11px] font-semibold shrink-0">Tất Cả</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('shop')" class="nav-cat-item px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 text-[11px] font-medium shrink-0">Shop & Showroom</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('spa')" class="nav-cat-item px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 text-[11px] font-medium shrink-0">Spa - Nail - Salon</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('cafe')" class="nav-cat-item px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 text-[11px] font-medium shrink-0">Coffee - Nhà Hàng</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('photobooth')" class="nav-cat-item px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 text-[11px] font-medium shrink-0">Photobooth - Music Box</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('quangcao')" class="nav-cat-item px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 text-[11px] font-medium shrink-0">Quảng Cáo - Văn Phòng</a>
                <a href="#du-an-da-nang" class="nav-cat-item px-2.5 py-1 rounded bg-white border border-slate-200 text-slate-700 text-[11px] font-medium shrink-0">Dự Án Đà Nẵng</a>
                <a href="#form-bao-gia" class="nav-cat-item px-2.5 py-1 rounded bg-brand-gold text-white text-[11px] font-semibold shrink-0">Nhận Báo Giá</a>
            </div>
        </div>

        <!-- Drawer Menu Điện Thoại -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-xl">
            <div class="flatsome-container py-3 grid grid-cols-2 gap-2 text-xs font-semibold">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-house text-brand-gold"></i>Trang Chủ</a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-award text-brand-gold"></i>Giới Thiệu</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('shop'); toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-store text-brand-gold"></i>Nội Thất Shop</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('spa'); toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-spa text-brand-gold"></i>Spa - Nail - Salon</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('cafe'); toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-mug-hot text-brand-gold"></i>Coffee - Nhà Hàng</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('photobooth'); toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-camera-retro text-brand-gold"></i>Photobooth & Box</a>
                <a href="#danh-muc-san-pham" onclick="filterCategory('quangcao'); toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-bullhorn text-brand-gold"></i>Bảng Hiệu & VP</a>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-city text-brand-gold"></i>Dự Án Đà Nẵng</a>
                <a href="#doi-tac" onclick="toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-handshake text-brand-gold"></i>Đối Tác</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-newspaper text-brand-gold"></i>Tin Tức</a>
                <a href="#bando-fanpage" onclick="toggleMobileMenu()" class="p-2.5 rounded bg-slate-50 text-brand-dark flex items-center gap-2"><i class="fa-solid fa-map-location-dot text-brand-gold"></i>Bản Đồ & Fanpage</a>
                <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="p-2.5 rounded bg-brand-gold text-white flex items-center gap-2"><i class="fa-solid fa-file-signature"></i>Yêu Cầu Báo Giá</a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         HERO BANNER SLIDER TỰ TRƯỢT (2 Banner kích thước bằng nhau)
         - Thiết kế riêng ảnh banner trên Máy Tính và ảnh banner trên Điện Thoại
         - Chữ nhỏ gọn nằm trọn bên trong ảnh banner, tuyệt đối không tràn viền
         ========================================== -->
    <section id="trang-chu" class="py-3 sm:py-4">
        <div class="flatsome-container">
            <div class="relative rounded-xl overflow-hidden shadow-md bg-brand-dark">

                <!-- ================= SLIDE 1 ================= -->
                <div class="hero-slide transition-opacity duration-700 ease-in-out" data-slide="0">
                    
                    <!-- BANNER MÁY TÍNH SLIDE 1 (Cố định chiều cao 420px bằng nhau) -->
                    <div class="hidden md:flex relative w-full h-[420px] items-center overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl=w1600" 
                            data-drive-id="1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl"
                            alt="Banner Máy Tính 1 - Đức An Thịnh Decor" 
                            class="absolute inset-0 w-full h-full object-cover object-center scale-105"
                            onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=1600&q=80')"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/95 via-brand-dark/80 to-brand-dark/30"></div>
                        
                        <!-- Nội dung chữ thu gọn nằm trọn trong khung an toàn máy tính -->
                        <div class="relative z-10 w-full px-12 lg:px-16 py-8 flex items-center justify-between gap-8">
                            <div class="max-w-2xl text-white">
                                <p class="inline-block px-3 py-1 rounded bg-brand-gold/20 border border-brand-gold text-brand-goldLight text-xs font-bold uppercase tracking-wider mb-2.5">
                                    ĐỨC AN THỊNH DECOR • DUCANTHINH.COM
                                </p>
                                <h1 class="font-heading text-2xl lg:text-3xl font-extrabold leading-snug text-white mb-2.5">
                                    THIẾT KẾ & THI CÔNG XÂY DỰNG - QUẢNG CÁO - NỘI THẤT TRỌN GÓI
                                </h1>
                                <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-4">
                                    Chuyên kiến tạo không gian <strong class="text-brand-goldLight">Shop, Showroom, Spa, Tiệm Nail, Hair Salon, Coffee, Photobooth, Music Box, Văn Phòng, Nhà Hàng</strong> chuyên nghiệp tại Đà Nẵng & Miền Trung. Trực tiếp sản xuất tại 2 xưởng, tối ưu 30% chi phí.
                                </p>
                                <div class="grid grid-cols-2 gap-2.5 text-xs text-slate-200 mb-5 bg-white/5 p-3 rounded-lg border border-white/10">
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-location-dot text-brand-gold"></i>
                                        <span>VP + XSX 1: 19 Ngô Chân Lưu, P. Hoà Khánh, Đà Nẵng</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <i class="fa-solid fa-industry text-brand-gold"></i>
                                        <span>Xưởng XSX 2: 121 Nguyễn Bảo, Hoà Châu, Đà Nẵng</span>
                                    </div>
                                </div>
                                <div class="flex items-center gap-3">
                                    <a href="#form-bao-gia" class="px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs uppercase tracking-wide transition shadow">
                                        Nhận Báo Giá Trọn Gói
                                    </a>
                                    <a href="#danh-muc-san-pham" class="px-5 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 text-white border border-white/25 font-semibold text-xs uppercase tracking-wide transition">
                                        Xem Dự Án Thực Tế
                                    </a>
                                </div>
                            </div>

                            <!-- Khung ảnh thực tế phụ bên phải banner máy tính -->
                            <div class="hidden xl:block w-72 h-72 rounded-xl overflow-hidden border-2 border-brand-gold/60 shadow-2xl shrink-0 relative">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/13jgchAVsd5mT8za7XSB8rsvskLKlbKyS=w800" 
                                    data-drive-id="13jgchAVsd5mT8za7XSB8rsvskLKlbKyS"
                                    alt="Công trình thực tế Đức An Thịnh" 
                                    class="w-full h-full object-cover"
                                    onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80')"
                                >
                                <div class="absolute bottom-0 inset-x-0 bg-brand-dark/90 backdrop-blur-sm px-3 py-2 text-center">
                                    <span class="text-[11px] font-bold text-brand-goldLight">Hotline/Zalo: 0981.708.494</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER ĐIỆN THOẠI SLIDE 1 (Thiết kế riêng cho Mobile, cố định chiều cao 290px, chữ nhỏ gọn nằm trọn bên trong) -->
                    <div class="flex md:hidden relative w-full h-[290px] items-center justify-center overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1rAw6vKjVMRcNJS2BxpVDMMDfqoSe8Enl=w900" 
                            data-drive-id="1rAw6vKjVMRcNJS2BxpVDMMDfqoSe8Enl"
                            alt="Banner Điện Thoại 1 - Đức An Thịnh Decor" 
                            class="absolute inset-0 w-full h-full object-cover object-center"
                            onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1586023492125-27b2c045efd7?auto=format&fit=crop&w=900&q=80')"
                        >
                        <div class="absolute inset-0 bg-gradient-to-b from-brand-dark/90 via-brand-dark/85 to-brand-dark/95"></div>
                        <div class="relative z-10 w-full px-5 py-4 text-center text-white">
                            <span class="inline-block px-2.5 py-0.5 rounded bg-brand-gold/25 border border-brand-gold text-brand-goldLight text-[10px] font-bold uppercase mb-1.5">
                                ĐỨC AN THỊNH DECOR • ĐÀ NẴNG
                            </span>
                            <h2 class="font-heading text-sm sm:text-base font-extrabold leading-snug text-white mb-1.5">
                                THIẾT KẾ & THI CÔNG NỘI THẤT - QUẢNG CÁO - XÂY DỰNG TRỌN GÓI
                            </h2>
                            <p class="text-[11px] text-slate-200 leading-relaxed mb-2.5 px-1">
                                Chuyên Shop, Spa, Tiệm Nail, Hair Salon, Coffee, Photobooth, Văn Phòng, Nhà Hàng.
                            </p>
                            <div class="text-[10px] text-amber-200 bg-white/10 rounded px-2.5 py-1.5 mb-2.5 leading-normal">
                                <div>VP + XSX1: 19 Ngô Chân Lưu, P. Hoà Khánh, Đà Nẵng</div>
                                <div>XSX2: 121 Nguyễn Bảo, Hoà Châu • ĐT: 0981.708.494</div>
                            </div>
                            <div class="flex items-center justify-center gap-2">
                                <a href="#form-bao-gia" class="px-3.5 py-1.5 rounded bg-brand-gold text-white font-bold text-[11px]">
                                    Nhận Báo Giá
                                </a>
                                <a href="tel:0981708494" class="px-3.5 py-1.5 rounded bg-white/15 border border-white/30 text-white font-semibold text-[11px]">
                                    0981.708.494
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ================= SLIDE 2 ================= -->
                <div class="hero-slide hidden transition-opacity duration-700 ease-in-out" data-slide="1">
                    
                    <!-- BANNER MÁY TÍNH SLIDE 2 (Cố định chiều cao 420px bằng Slide 1) -->
                    <div class="hidden md:flex relative w-full h-[420px] items-center overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1c954dUrUQmmKWRCTfqlZnANCflrRXZAX=w1600" 
                            data-drive-id="1c954dUrUQmmKWRCTfqlZnANCflrRXZAX"
                            alt="Banner Máy Tính 2 - Xưởng Sản Xuất Nội Thất Quảng Cáo Đà Nẵng" 
                            class="absolute inset-0 w-full h-full object-cover object-center scale-105"
                            onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&w=1600&q=80')"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-slate-950/95 via-slate-900/80 to-slate-900/30"></div>
                        
                        <div class="relative z-10 w-full px-12 lg:px-16 py-8 flex items-center justify-between gap-8">
                            <div class="max-w-2xl text-white">
                                <p class="inline-block px-3 py-1 rounded bg-brand-gold/20 border border-brand-gold text-brand-goldLight text-xs font-bold uppercase tracking-wider mb-2.5">
                                    GIẢI PHÁP KHÔNG GIAN KINH DOANH ĐẲNG CẤP
                                </p>
                                <h2 class="font-heading text-2xl lg:text-3xl font-extrabold leading-snug text-white mb-2.5">
                                    XƯỞNG SẢN XUẤT TRỰC TIẾP - MIỄN PHÍ TƯ VẤN & KHẢO SÁT TẬN NƠI
                                </h2>
                                <p class="text-xs lg:text-sm text-slate-200 leading-relaxed mb-4">
                                    Tư vấn 1:1 cùng Kiến Trúc Sư, lên bản vẽ phối cảnh 3D sát thực tế 99%, thi công chuẩn tiến độ từ phần thô xây dựng, bảng hiệu Alu - chữ nổi LED đến hoàn thiện nội thất MDF chống ẩm cao cấp.
                                </p>
                                <div class="grid grid-cols-3 gap-2.5 text-xs text-slate-200 mb-5 bg-white/5 p-3 rounded-lg border border-white/10">
                                    <div class="flex items-center gap-1.5">
                                        <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                        <span>Bản vẽ 3D Tối Ưu Công Năng</span>
                                    </div>
                                    <div class="flex items-center gap-1.5">
                                        <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                        <span>Giá Gốc Tại 2 Xưởng Đà Nẵng</span>
                                    </div>
                                    <div class="flex items-center gap-1.5">
                                        <i class="fa-solid fa-circle-check text-brand-gold"></i>
                                        <span>Bảo Hành Dài Hạn Tận Tâm</span>
                                    </div>
                                </div>
                                <div class="flex items-center gap-3">
                                    <a href="#du-an-da-nang" class="px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs uppercase tracking-wide transition shadow">
                                        Khám Phá Dự Án Đà Nẵng
                                    </a>
                                    <a href="#bando-fanpage" class="px-5 py-2.5 rounded-lg bg-white/10 hover:bg-white/20 text-white border border-white/25 font-semibold text-xs uppercase tracking-wide transition">
                                        Xem Địa Chỉ Xưởng & Map
                                    </a>
                                </div>
                            </div>

                            <div class="hidden xl:block w-72 h-72 rounded-xl overflow-hidden border-2 border-brand-gold/60 shadow-2xl shrink-0 relative">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86=w800" 
                                    data-drive-id="1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86"
                                    alt="Thi công thực tế Đức An Thịnh" 
                                    class="w-full h-full object-cover"
                                    onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1555396273-367ea4eb4db5?auto=format&fit=crop&w=800&q=80')"
                                >
                                <div class="absolute bottom-0 inset-x-0 bg-brand-dark/90 backdrop-blur-sm px-3 py-2 text-center">
                                    <span class="text-[11px] font-bold text-brand-goldLight">Cam Kết Tiến Độ & Chất Lượng</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER ĐIỆN THOẠI SLIDE 2 (Thiết kế riêng cho Mobile, cố định chiều cao 290px bằng Slide 1) -->
                    <div class="flex md:hidden relative w-full h-[290px] items-center justify-center overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1SLFGLkI0UifBXEtTqOkfmBxf1SK-Kkjo=w900" 
                            data-drive-id="1SLFGLkI0UifBXEtTqOkfmBxf1SK-Kkjo"
                            alt="Banner Điện Thoại 2 - Đức An Thịnh Decor" 
                            class="absolute inset-0 w-full h-full object-cover object-center"
                            onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?auto=format&fit=crop&w=900&q=80')"
                        >
                        <div class="absolute inset-0 bg-gradient-to-b from-slate-950/90 via-slate-900/85 to-slate-950/95"></div>
                        <div class="relative z-10 w-full px-5 py-4 text-center text-white">
                            <span class="inline-block px-2.5 py-0.5 rounded bg-brand-gold/25 border border-brand-gold text-brand-goldLight text-[10px] font-bold uppercase mb-1.5">
                                XƯỞNG SẢN XUẤT TRỰC TIẾP ĐÀ NẴNG
                            </span>
                            <h2 class="font-heading text-sm sm:text-base font-extrabold leading-snug text-white mb-1.5">
                                TƯ VẤN 1:1 VỚI KIẾN TRÚC SƯ - TỐI ƯU 30% CHI PHÍ ĐẦU TƯ
                            </h2>
                            <p class="text-[11px] text-slate-200 leading-relaxed mb-2.5 px-1">
                                Thi công trọn gói từ Xây Dựng, Bảng Hiệu Quảng Cáo đến Nội Thất Shop, Spa, Salon, Cafe.
                            </p>
                            <div class="text-[10px] text-amber-200 bg-white/10 rounded px-2.5 py-1.5 mb-2.5 leading-normal">
                                <div>Khảo sát tận nơi • Phác thảo 3D nhanh chóng</div>
                                <div>Bảo hành uy tín • Website: ducanthinh.com</div>
                            </div>
                            <div class="flex items-center justify-center gap-2">
                                <a href="#du-an-da-nang" class="px-3.5 py-1.5 rounded bg-brand-gold text-white font-bold text-[11px]">
                                    Dự Án Đà Nẵng
                                </a>
                                <a href="#bando-fanpage" class="px-3.5 py-1.5 rounded bg-white/15 border border-white/30 text-white font-semibold text-[11px]">
                                    Xem Bản Đồ
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slider -->
                <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand-gold text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand-gold text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm tròn chỉ báo Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToSlide(0)" class="slide-dot w-6 h-1.5 rounded-full bg-brand-gold transition-all" aria-label="Banner 1"></button>
                    <button onclick="goToSlide(1)" class="slide-dot w-2 h-1.5 rounded-full bg-white/50 transition-all" aria-label="Banner 2"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         4 GIÁ TRỊ CỐT LÕI (Bố cục giống web mẫu PenConcept)
         ========================================== -->
    <section id="gioi-thieu" class="py-5">
        <div class="flatsome-container">
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200/80 shadow-sm flex flex-col sm:flex-row items-start sm:items-center gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-user-tie"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark">Tư Vấn 1:1 Kiến Trúc Sư</h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-0.5 leading-snug">Làm việc trực tiếp chuyên gia, khảo sát thực tế tận nơi tại Đà Nẵng.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200/80 shadow-sm flex flex-col sm:flex-row items-start sm:items-center gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark">Hỗ Trợ Bản Vẽ Sơ Bộ</h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-0.5 leading-snug">Phác thảo ý tưởng mặt bằng 2D & phối cảnh 3D tối ưu công năng.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200/80 shadow-sm flex flex-col sm:flex-row items-start sm:items-center gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-yin-yang"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark">Phân Tích Phong Thủy</h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-0.5 leading-snug">Bố trí quầy thu ngân, hướng cửa, màu sắc hợp mệnh thu hút tài lộc.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200/80 shadow-sm flex flex-col sm:flex-row items-start sm:items-center gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-dark text-brand-goldLight flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark">2 Xưởng SX & Bảo Hành</h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-0.5 leading-snug">Chủ động tiến độ tại Hòa Khánh & Hòa Châu, cam kết bảo hành rõ ràng.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC DỊCH VỤ & SẢN PHẨM (Lấy danh mục từ PenConcept kết hợp Đức An Thịnh)
         - Tối ưu hiển thị đẹp trên cả Máy Tính và Điện Thoại
         - Chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng không gãy chữ
         ========================================== -->
    <section class="py-5 bg-white border-y border-slate-200/70">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">DANH MỤC THIẾT KẾ & THI CÔNG TRỌN GÓI</span>
                <b></b>
            </div>
            <p class="text-center text-xs sm:text-sm text-slate-600 max-w-3xl mx-auto -mt-3 mb-5">
                Đức An Thịnh Decor cung cấp giải pháp toàn diện từ Thiết Kế 3D, Xây Dựng Cải Tạo, Bảng Hiệu Quảng Cáo đến Sản Xuất & Lắp Đặt Nội Thất Trọn Gói.
            </p>

            <!-- Lưới Danh Mục: 2 cột trên Điện Thoại, 4 cột trên Máy Tính, không dán nhãn đè lên ảnh -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-4">
                <a href="#danh-muc-san-pham" onclick="filterCategory('shop')" class="group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold transition shadow-sm">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl=w700" data-drive-id="1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl" alt="Thiết kế nội thất Shop, Showroom" class="w-full h-full object-cover group-hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1441986300917-64674bd600d8?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-2.5 sm:p-3 text-center">
                        <h3 class="font-heading font-bold text-xs sm:text-[13px] text-brand-dark group-hover:text-brand-gold transition product-title-full">Thiết Kế Nội Thất Shop, Showroom</h3>
                    </div>
                </a>

                <a href="#danh-muc-san-pham" onclick="filterCategory('spa')" class="group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold transition shadow-sm">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/13jgchAVsd5mT8za7XSB8rsvskLKlbKyS=w700" data-drive-id="13jgchAVsd5mT8za7XSB8rsvskLKlbKyS" alt="Thiết kế nội thất Thẩm mỹ viện, Spa" class="w-full h-full object-cover group-hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-2.5 sm:p-3 text-center">
                        <h3 class="font-heading font-bold text-xs sm:text-[13px] text-brand-dark group-hover:text-brand-gold transition product-title-full">Thiết Kế Thẩm Mỹ Viện, Spa</h3>
                    </div>
                </a>

                <a href="#danh-muc-san-pham" onclick="filterCategory('nail')" class="group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold transition shadow-sm">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/16jmRHwZqTYGHlB9U-lxin2VZTwobwEUW=w700" data-drive-id="16jmRHwZqTYGHlB9U-lxin2VZTwobwEUW" alt="Thiết kế Tiệm Nail - Hair Salon" class="w-full h-full object-cover group-hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1560066984-138dadb4c035?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-2.5 sm:p-3 text-center">
                        <h3 class="font-heading font-bold text-xs sm:text-[13px] text-brand-dark group-hover:text-brand-gold transition product-title-full">Thiết Kế Tiệm Nail, Hair Salon</h3>
                    </div>
                </a>

                <a href="#danh-muc-san-pham" onclick="filterCategory('cafe')" class="group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold transition shadow-sm">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/14J36h1Gn6nJEHu4_yQj4P11p9enPr5pP=w700" data-drive-id="14J36h1Gn6nJEHu4_yQj4P11p9enPr5pP" alt="Thiết kế nội thất Cà phê, Nhà hàng, Bar" class="w-full h-full object-cover group-hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1554118811-1e0d58224f24?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-2.5 sm:p-3 text-center">
                        <h3 class="font-heading font-bold text-xs sm:text-[13px] text-brand-dark group-hover:text-brand-gold transition product-title-full">Thiết Kế Nhà Hàng, Cà Phê, Bar</h3>
                    </div>
                </a>

                <a href="#danh-muc-san-pham" onclick="filterCategory('photobooth')" class="group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold transition shadow-sm">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1mj2bb_Q5lhK7yJfDmDWihaLfG6f4UR6q=w700" data-drive-id="1mj2bb_Q5lhK7yJfDmDWihaLfG6f4UR6q" alt="Thiết kế nội thất Photobooth" class="w-full h-full object-cover group-hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-2.5 sm:p-3 text-center">
                        <h3 class="font-heading font-bold text-xs sm:text-[13px] text-brand-dark group-hover:text-brand-gold transition product-title-full">Thiết Kế Nội Thất Photobooth</h3>
                    </div>
                </a>

                <a href="#danh-muc-san-pham" onclick="filterCategory('photobooth')" class="group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold transition shadow-sm">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1R6wUU4Ty3YNgLT2JDSuGAsohxJRCAs3c=w700" data-drive-id="1R6wUU4Ty3YNgLT2JDSuGAsohxJRCAs3c" alt="Thiết kế nội thất Music Box & Pilates" class="w-full h-full object-cover group-hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1598488035139-bdbb2231ce04?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-2.5 sm:p-3 text-center">
                        <h3 class="font-heading font-bold text-xs sm:text-[13px] text-brand-dark group-hover:text-brand-gold transition product-title-full">Thiết Kế Music Box & Phòng Pilates</h3>
                    </div>
                </a>

                <a href="#danh-muc-san-pham" onclick="filterCategory('quangcao')" class="group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold transition shadow-sm">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1iDGy3qGrl7B825739Dso1dXUl5N5pjZp=w700" data-drive-id="1iDGy3qGrl7B825739Dso1dXUl5N5pjZp" alt="Thiết kế nội thất Văn phòng" class="w-full h-full object-cover group-hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1497366811353-6870744d04b2?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-2.5 sm:p-3 text-center">
                        <h3 class="font-heading font-bold text-xs sm:text-[13px] text-brand-dark group-hover:text-brand-gold transition product-title-full">Thiết Kế & Thi Công Văn Phòng</h3>
                    </div>
                </a>

                <a href="#danh-muc-san-pham" onclick="filterCategory('quangcao')" class="group bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold transition shadow-sm">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1kfeqpT5OPp4qxeF2mSi38icE7jb1hF5I=w700" data-drive-id="1kfeqpT5OPp4qxeF2mSi38icE7jb1hF5I" alt="Thi công Xây dựng & Bảng hiệu Quảng cáo" class="w-full h-full object-cover group-hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1542744173-8e7e53415bb0?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-2.5 sm:p-3 text-center">
                        <h3 class="font-heading font-bold text-xs sm:text-[13px] text-brand-dark group-hover:text-brand-gold transition product-title-full">Xây Dựng & Bảng Hiệu Quảng Cáo</h3>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SẢN PHẨM & HẠNG MỤC THI CÔNG THỰC TẾ (15 Ảnh Google Drive)
         - Điện thoại chia 2 cột, Máy tính chia 4 cột
         - KHÔNG để nhãn dán đè trên ảnh ở trang chủ
         - Tên sản phẩm hiển thị trọn vẹn, không tràn viền, không mất chữ
         ========================================== -->
    <section id="danh-muc-san-pham" class="py-7">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">SẢN PHẨM & CÔNG TRÌNH THỰC TẾ NỔI BẬT</span>
                <b></b>
            </div>

            <!-- Thanh lọc danh mục trang chủ: Chữ nhỏ gọn, tên danh mục viết liền trên 1 hàng không gãy dòng -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                <button onclick="filterCategory('all')" data-cat-btn="all" class="home-cat-pill px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-bold bg-brand-dark text-brand-goldLight border border-brand-dark">
                    Tất Cả Hạng Mục (15)
                </button>
                <button onclick="filterCategory('shop')" data-cat-btn="shop" class="home-cat-pill px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-gold">
                    Nội Thất Shop - Showroom
                </button>
                <button onclick="filterCategory('spa')" data-cat-btn="spa" class="home-cat-pill px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-gold">
                    Thẩm Mỹ Viện - Spa
                </button>
                <button onclick="filterCategory('nail')" data-cat-btn="nail" class="home-cat-pill px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-gold">
                    Tiệm Nail - Hair Salon
                </button>
                <button onclick="filterCategory('cafe')" data-cat-btn="cafe" class="home-cat-pill px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-gold">
                    Nhà Hàng - Cà Phê - Bar
                </button>
                <button onclick="filterCategory('photobooth')" data-cat-btn="photobooth" class="home-cat-pill px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-gold">
                    Photobooth - Music Box - Pilates
                </button>
                <button onclick="filterCategory('quangcao')" data-cat-btn="quangcao" class="home-cat-pill px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-gold">
                    Văn Phòng - Bảng Hiệu Quảng Cáo
                </button>
            </div>

            <!-- Lưới Sản Phẩm: 2 Cột trên Điện Thoại (grid-cols-2), 4 Cột trên Máy Tính (lg:grid-cols-4) -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Đổ dữ liệu 15 ảnh thực tế Google Drive qua JS để đảm bảo sạch gọn & dễ quản lý -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (Section chuyên biệt trên Trang Chủ)
         - Chia 2 cột trên Điện Thoại, 4 cột trên Máy Tính
         - Không gắn nhãn dán
         ========================================== -->
    <section id="du-an-da-nang" class="py-7 bg-white border-y border-slate-200">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">DỰ ÁN THIẾT KẾ & THI CÔNG TẠI ĐÀ NẴNG</span>
                <b></b>
            </div>
            <p class="text-center text-xs sm:text-sm text-slate-600 max-w-3xl mx-auto -mt-3 mb-6">
                Các công trình thực tế do đội ngũ Kiến Trúc Sư và Xưởng Sản Xuất Đức An Thịnh Decor trực tiếp thiết kế, thi công tại các quận Hải Châu, Thanh Khê, Sơn Trà, Ngũ Hành Sơn, Liên Chiểu, Cẩm Lệ và Hòa Vang – TP. Đà Nẵng.
            </p>

            <!-- Lưới Dự Án Đà Nẵng: 2 cột trên Điện Thoại, 4 cột trên Máy Tính -->
            <div id="danangProjectGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Được render tự động từ dữ liệu dự án thực tế Đà Nẵng -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         QUY TRÌNH THIẾT KẾ & THI CÔNG TRỌN GÓI (Chuẩn PenConcept & UX Builder)
         ========================================== -->
    <section class="py-7">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">QUY TRÌNH LÀM VIỆC CHUYÊN NGHIỆP</span>
                <b></b>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center">
                    <div class="w-8 h-8 rounded-full bg-brand-dark text-brand-goldLight font-heading font-bold text-xs flex items-center justify-center mx-auto mb-2">01</div>
                    <h4 class="font-heading font-bold text-xs text-brand-dark mb-1">Tiếp Nhận & Tư Vấn</h4>
                    <p class="text-[11px] text-slate-500 leading-snug">Lắng nghe nhu cầu, định hướng phong cách & ngân sách đầu tư.</p>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center">
                    <div class="w-8 h-8 rounded-full bg-brand-dark text-brand-goldLight font-heading font-bold text-xs flex items-center justify-center mx-auto mb-2">02</div>
                    <h4 class="font-heading font-bold text-xs text-brand-dark mb-1">Khảo Sát Thực Tế</h4>
                    <p class="text-[11px] text-slate-500 leading-snug">Đo đạc mặt bằng tận nơi miễn phí tại Đà Nẵng & khu vực lân cận.</p>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center">
                    <div class="w-8 h-8 rounded-full bg-brand-dark text-brand-goldLight font-heading font-bold text-xs flex items-center justify-center mx-auto mb-2">03</div>
                    <h4 class="font-heading font-bold text-xs text-brand-dark mb-1">Thiết Kế 2D & 3D</h4>
                    <p class="text-[11px] text-slate-500 leading-snug">Bố trí công năng khoa học, dựng phối cảnh 3D trực quan sắc nét.</p>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center">
                    <div class="w-8 h-8 rounded-full bg-brand-dark text-brand-goldLight font-heading font-bold text-xs flex items-center justify-center mx-auto mb-2">04</div>
                    <h4 class="font-heading font-bold text-xs text-brand-dark mb-1">Báo Giá Chi Tiết</h4>
                    <p class="text-[11px] text-slate-500 leading-snug">Bóc tách khối lượng minh bạch, báo giá gốc tại xưởng không phát sinh.</p>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center">
                    <div class="w-8 h-8 rounded-full bg-brand-dark text-brand-goldLight font-heading font-bold text-xs flex items-center justify-center mx-auto mb-2">05</div>
                    <h4 class="font-heading font-bold text-xs text-brand-dark mb-1">Sản Xuất & Thi Công</h4>
                    <p class="text-[11px] text-slate-500 leading-snug">Gia công tại 2 xưởng Hòa Khánh & Hòa Châu, lắp đặt hoàn thiện.</p>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center">
                    <div class="w-8 h-8 rounded-full bg-brand-dark text-brand-goldLight font-heading font-bold text-xs flex items-center justify-center mx-auto mb-2">06</div>
                    <h4 class="font-heading font-bold text-xs text-brand-dark mb-1">Nghiệm Thu & Bảo Hành</h4>
                    <p class="text-[11px] text-slate-500 leading-snug">Bàn giao đúng tiến độ khai trương, bảo hành & bảo trì tận tâm.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
         ========================================== -->
    <section id="form-bao-gia" class="py-7 bg-brand-dark text-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                
                <!-- Thông tin cam kết báo giá -->
                <div class="lg:col-span-5 space-y-3">
                    <span class="inline-block px-3 py-1 rounded bg-brand-gold/20 border border-brand-gold text-brand-goldLight text-xs font-bold uppercase">
                        NHẬN BÁO GIÁ GỐC TẠI XƯỞNG
                    </span>
                    <h2 class="font-heading text-xl sm:text-2xl font-extrabold text-white leading-snug">
                        ĐĂNG KÝ TƯ VẤN & BÁO GIÁ THIẾT KẾ THI CÔNG TRỌN GÓI
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                        Quý khách để lại thông tin công trình, Kiến Trúc Sư trưởng của <strong class="text-brand-goldLight">Đức An Thịnh Decor</strong> sẽ liên hệ tư vấn phương án mặt bằng, vật liệu và gửi bảng dự toán chi tiết trong vòng 15 phút.
                    </p>
                    <div class="space-y-2 pt-2 text-xs sm:text-sm text-slate-200">
                        <div class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-brand-gold mt-1"></i>
                            <span><strong>Văn Phòng + XSX 1:</strong> 19 Ngô Chân Lưu - P. Hoà Khánh - TP. Đà Nẵng</span>
                        </div>
                        <div class="flex items-start gap-2.5">
                            <i class="fa-solid fa-warehouse text-brand-gold mt-1"></i>
                            <span><strong>Xưởng XSX 2:</strong> 121 Nguyễn Bảo - Hoà Châu - Đà Nẵng</span>
                        </div>
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone-volume text-brand-gold"></i>
                            <span><strong>Hotline / Zalo 24/7:</strong> <a href="tel:0981708494" class="text-brand-goldLight font-bold hover:underline">0981.708.494</a></span>
                        </div>
                    </div>
                </div>

                <!-- Form nhập thông tin yêu cầu & báo giá -->
                <div class="lg:col-span-7 bg-white text-slate-800 rounded-xl p-4 sm:p-6 shadow-xl border border-brand-gold/40">
                    <h3 class="font-heading font-bold text-sm sm:text-base text-brand-dark mb-3 pb-2 border-b border-slate-200">
                        FORM YÊU CẦU TƯ VẤN & BÁO GIÁ NHANH
                    </h3>
                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên Quý khách *</label>
                                <input type="text" id="qName" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-gold">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="qPhone" required placeholder="Nhập SĐT (VD: 0981...)" class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-gold">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục cần tư vấn *</label>
                                <select id="qService" class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm bg-white focus:outline-none focus:border-brand-gold">
                                    <option value="Thiết kế & Thi công Shop / Showroom">Nội thất Shop / Showroom</option>
                                    <option value="Thiết kế & Thi công Spa / Nail / Hair Salon">Spa / Tiệm Nail / Hair Salon</option>
                                    <option value="Thiết kế & Thi công Quán Coffee / Nhà hàng">Quán Coffee / Trà sữa / Nhà hàng</option>
                                    <option value="Thiết kế & Thi công Photobooth / Music Box">Photobooth / Music Box / Pilates</option>
                                    <option value="Thiết kế & Thi công Văn phòng">Thiết kế & Thi công Văn phòng</option>
                                    <option value="Bảng hiệu Quảng cáo & Xây dựng trọn gói">Bảng hiệu Quảng cáo & Xây dựng</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Diện tích dự kiến (m²)</label>
                                <input type="text" id="qArea" placeholder="VD: 50m2, 120m2..." class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-gold">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Khu vực công trình</label>
                                <input type="text" id="qAddress" placeholder="VD: Hải Châu, Đà Nẵng..." class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-gold">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Yêu cầu chi tiết (Phong cách mong muốn, ngân sách dự kiến...)</label>
                            <textarea id="qNote" rows="2" placeholder="Nhập yêu cầu cụ thể của Quý khách..." class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-brand-gold"></textarea>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                            <span class="text-[11px] text-slate-500">
                                <i class="fa-solid fa-lock text-brand-gold mr-1"></i>Bảo mật thông tin khách hàng 100%
                            </span>
                            <button type="submit" class="w-full sm:w-auto px-6 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-heading font-bold text-xs uppercase tracking-wider transition shadow">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i>Gửi Yêu Cầu Báo Giá Ngay
                            </button>
                        </div>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức & Kinh nghiệm thiết kế giống PenConcept)
         - Điện thoại 2 cột, Máy tính 3 cột
         ========================================== -->
    <section id="tin-tuc" class="py-7">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">TIN TỨC & KINH NGHIỆM THIẾT KẾ NỘI THẤT</span>
                <b></b>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1L-50zH_kYfXmupV2kAK43Ky0Ad6zgRvk=w700" data-drive-id="1L-50zH_kYfXmupV2kAK43Ky0Ad6zgRvk" alt="Kinh nghiệm thiết kế Shop thời trang, mỹ phẩm tại Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1441986300917-64674bd600d8?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5 product-title-full">
                                Báo Giá Thiết Kế & Thi Công Shop Thời Trang, Mỹ Phẩm Trọn Gói Đà Nẵng 2026
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 line-clamp-2">
                                Bí quyết bố trí quầy thu ngân, hệ tủ kệ trưng bày MDF chống ẩm kết hợp đèn LED thanh ray tôn vinh sản phẩm và tối ưu chi phí mở shop.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11px] font-bold text-brand-gold mt-2.5 hover:underline">
                            <span>Xem chi tiết & nhận báo giá</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1D4UTUkj_2FmCcC9oJMCCwr4mM8YK2j5q=w700" data-drive-id="1D4UTUkj_2FmCcC9oJMCCwr4mM8YK2j5q" alt="Xu hướng thiết kế Spa, Tiệm Nail, Hair Salon" class="w-full h-full object-cover hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5 product-title-full">
                                Xu Hướng Thiết Kế Spa Dưỡng Sinh, Tiệm Nail & Hair Salon Sang Trọng Hút Khách
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 line-clamp-2">
                                Tổng hợp các mẫu thiết kế Spa, Nail, Salon phong cách Hàn Quốc, Indochine và Wabi Sabi nhẹ nhàng, tối ưu trải nghiệm thư giãn cho khách hàng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11px] font-bold text-brand-gold mt-2.5 hover:underline">
                            <span>Xem chi tiết & nhận báo giá</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/17bzkccO8qBV0nlhzwO1rGdvVLB5Nrx6C=w700" data-drive-id="17bzkccO8qBV0nlhzwO1rGdvVLB5Nrx6C" alt="Thiết kế Photobooth & Music Box Hàn Quốc" class="w-full h-full object-cover hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5 product-title-full">
                                Thiết Kế Thi Công Photobooth & Music Box Độc Đáo – Mô Hình Giải Trí Hút Giới Trẻ
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 line-clamp-2">
                                Giải pháp cách âm tiêu âm phòng Music Box và thiết kế góc check-in ánh sáng studio chuẩn Hàn Quốc cho chuỗi cửa hàng Photobooth tại Đà Nẵng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11px] font-bold text-brand-gold mt-2.5 hover:underline">
                            <span>Xem chi tiết & nhận báo giá</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1kfeqpT5OPp4qxeF2mSi38icE7jb1hF5I=w700" data-drive-id="1kfeqpT5OPp4qxeF2mSi38icE7jb1hF5I" alt="Thi công bảng hiệu quảng cáo Alu chữ nổi LED Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-500" onerror="handleDriveImgError(this, 'https://images.unsplash.com/photo-1542744173-8e7e53415bb0?auto=format&fit=crop&w=700&q=80')">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark mb-1.5 product-title-full">
                                Kinh Nghiệm Làm Bảng Hiệu Quảng Cáo Mặt Tiền Shop, Quán Cafe, Spa Bền Đẹp
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 line-clamp-2">
                                Lựa chọn vật liệu Alu, chữ nổi Mica, Inox sáng chân LED chống chịu thời tiết biển miền Trung, giúp mặt tiền cửa hàng nổi bật cả ngày lẫn đêm.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11px] font-bold text-brand-gold mt-2.5 hover:underline">
                            <span>Xem chi tiết & nhận báo giá</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC ĐỐI TÁC & VẬT LIỆU CHÍNH HÃNG (Section Đối Tác trên Trang Chủ)
         ========================================== -->
    <section id="doi-tac" class="py-7 bg-white border-y border-slate-200">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">ĐỐI TÁC VẬT LIỆU & KHÁCH HÀNG ĐỒNG HÀNH</span>
                <b></b>
            </div>
            <p class="text-center text-xs sm:text-sm text-slate-600 max-w-3xl mx-auto -mt-3 mb-5">
                Đức An Thịnh Decor cam kết sử dụng vật tư nội thất, phụ kiện, sơn và hệ thống chiếu sáng chính hãng từ các thương hiệu hàng đầu Việt Nam & Quốc Tế.
            </p>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="font-heading font-extrabold text-xs sm:text-sm text-brand-dark">AN CƯỜNG WOOD</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Gỗ Công Nghiệp MDF/HDF</span>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="font-heading font-extrabold text-xs sm:text-sm text-brand-dark">HÄFELE & BLUM</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Phụ Kiện Nội Thất Cao Cấp</span>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="font-heading font-extrabold text-xs sm:text-sm text-brand-dark">DULUX & JOTUN</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Sơn Nước & Sơn Hiệu Ứng</span>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="font-heading font-extrabold text-xs sm:text-sm text-brand-dark">RẠNG ĐÔNG & KINGLED</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Hệ Thống Đèn LED Showroom</span>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="font-heading font-extrabold text-xs sm:text-sm text-brand-dark">ALCOREST & MICA FS</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Vật Tư Bảng Hiệu Quảng Cáo</span>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center hover:border-brand-gold transition">
                    <span class="font-heading font-extrabold text-xs sm:text-sm text-brand-dark">VĨNH TƯỜNG GYPROC</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Hệ Trần & Vách Thạch Cao</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FANPAGE FACEBOOK & BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ
         - Đưa Fanpage Đức An Thịnh Decor ra ngoài trang chủ
         - Đưa Bản Đồ Google Maps 2 cơ sở Đà Nẵng ra ngoài trang chủ
         ========================================== -->
    <section id="bando-fanpage" class="py-7">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-lg">FANPAGE CHÍNH THỨC & BẢN ĐỒ XƯỞNG ĐỨC AN THỊNH DECOR</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                
                <!-- Cột Fanpage chính thức ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-4 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 pb-3 mb-3 border-b border-slate-100">
                            <div class="flex items-center gap-2.5">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1MhjyXTntX8l9fCvcrilImo1RjWkZ3pIk=w200" 
                                    data-drive-id="1MhjyXTntX8l9fCvcrilImo1RjWkZ3pIk"
                                    alt="Logo Fanpage Đức An Thịnh Decor" 
                                    class="w-11 h-11 rounded-lg object-contain bg-brand-dark p-1 border border-brand-gold"
                                    onerror="handleDriveImgError(this, 'https://placehold.co/100x100/16202E/C59B27?text=DAT')"
                                >
                                <div>
                                    <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                        Đức An Thịnh Decor - Nội Thất & Quảng Cáo
                                    </h3>
                                    <p class="text-[11px] text-slate-500">Fanpage cập nhật công trình thực tế mỗi ngày</p>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/profile.php?id=61585341208717" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-[11px] font-bold shrink-0">
                                <i class="fa-brands fa-facebook-f mr-1"></i>Theo Dõi
                            </a>
                        </div>

                        <!-- Khung nhúng Facebook Page Plugin kết hợp Thẻ Trực Quan Fanpage -->
                        <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-50 mb-3">
                            <iframe 
                                title="Fanpage Đức An Thịnh Decor"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61585341208717&tabs=timeline&width=500&height=260&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                width="100%" 
                                height="250" 
                                style="border:none;overflow:hidden" 
                                scrolling="no" 
                                frameborder="0" 
                                allowfullscreen="true" 
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                            </iframe>
                        </div>
                    </div>

                    <div class="bg-slate-50 p-3 rounded-lg border border-slate-200/80 text-xs space-y-1.5">
                        <div class="font-bold text-brand-dark">Kết nối trực tiếp qua Fanpage & Zalo:</div>
                        <p class="text-slate-600 text-[11px]">
                            Xem album hình ảnh tiến độ thi công thực tế tại xưởng Hòa Khánh & Hòa Châu trên trang Facebook chính thức của chúng tôi.
                        </p>
                        <div class="flex flex-wrap gap-2 pt-1">
                            <a href="https://www.facebook.com/profile.php?id=61585341208717" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded bg-blue-600 text-white font-semibold text-[11px]">
                                <i class="fa-brands fa-facebook"></i>Mở Fanpage Facebook
                            </a>
                            <a href="https://zalo.me/0981708494" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded bg-sky-600 text-white font-semibold text-[11px]">
                                <i class="fa-solid fa-comment-dots"></i>Chat Zalo: 0981.708.494
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Cột Bản đồ Google Maps 2 cơ sở ngoài trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-4 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-3 border-b border-slate-100">
                            <div>
                                <h3 class="font-heading font-bold text-xs sm:text-sm text-brand-dark">
                                    HỆ THỐNG VĂN PHÒNG & 2 XƯỞNG SẢN XUẤT TẠI ĐÀ NẴNG
                                </h3>
                                <p class="text-[11px] text-slate-500">Bấm chọn địa chỉ bên dưới để xem vị trí trên bản đồ Google Maps</p>
                            </div>
                            <div class="flex items-center gap-1.5">
                                <button onclick="switchMapLocation(1)" id="mapBtn1" class="px-2.5 py-1.5 rounded-lg bg-brand-dark text-brand-goldLight text-[11px] font-bold">
                                    VP & XSX 1: 19 Ngô Chân Lưu
                                </button>
                                <button onclick="switchMapLocation(2)" id="mapBtn2" class="px-2.5 py-1.5 rounded-lg bg-slate-100 text-slate-700 hover:bg-slate-200 text-[11px] font-semibold">
                                    XSX 2: 121 Nguyễn Bảo
                                </button>
                            </div>
                        </div>

                        <!-- Khung Google Maps trực tiếp ngoài trang chủ -->
                        <div class="rounded-lg overflow-hidden border border-slate-200 h-[250px] sm:h-[275px] bg-slate-100 relative">
                            <iframe 
                                id="googleMapIframe"
                                title="Bản đồ Đức An Thịnh Decor Đà Nẵng"
                                src="https://maps.google.com/maps?q=19%20Ng%C3%B4%20Ch%C3%A2n%20L%C6%B0u%2C%20Ho%C3%A0%20Kh%C3%A1nh%2C%20Li%C3%AAn%20Chi%E1%BB%83u%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                                width="100%" 
                                height="100%" 
                                style="border:0;" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 mt-3 text-xs">
                        <div class="p-2.5 rounded-lg bg-slate-50 border border-slate-200">
                            <div class="font-bold text-brand-dark flex items-center gap-1.5">
                                <i class="fa-solid fa-location-dot text-brand-gold"></i>
                                <span>Văn Phòng + XSX 1:</span>
                            </div>
                            <p class="text-[11px] text-slate-600 mt-0.5">19 Ngô Chân Lưu - P. Hoà Khánh - TP. Đà Nẵng</p>
                        </div>
                        <div class="p-2.5 rounded-lg bg-slate-50 border border-slate-200">
                            <div class="font-bold text-brand-dark flex items-center gap-1.5">
                                <i class="fa-solid fa-industry text-brand-gold"></i>
                                <span>Xưởng Sản Xuất 2:</span>
                            </div>
                            <p class="text-[11px] text-slate-600 mt-0.5">121 Nguyễn Bảo - Hoà Châu - TP. Đà Nẵng</p>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME
         ========================================== -->
    <footer class="bg-brand-dark text-slate-300 pt-10 pb-20 lg:pb-8 border-t-4 border-brand-gold">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-slate-800">
                
                <!-- Cột 1: Thông tin công ty & Logo -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-3">
                        <div class="w-11 h-11 rounded-lg overflow-hidden border border-brand-gold bg-white/5 p-0.5 shrink-0">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1MhjyXTntX8l9fCvcrilImo1RjWkZ3pIk=w300" 
                                data-drive-id="1MhjyXTntX8l9fCvcrilImo1RjWkZ3pIk"
                                alt="Logo Đức An Thịnh Decor" 
                                class="w-full h-full object-contain rounded"
                                onerror="handleDriveImgError(this, 'https://placehold.co/120x120/16202E/C59B27?text=DAT')"
                            >
                        </div>
                        <div>
                            <h3 class="font-heading font-extrabold text-white text-base tracking-wide">
                                ĐỨC AN THỊNH <span class="text-brand-goldLight">DECOR</span>
                            </h3>
                            <p class="text-xs text-brand-goldLight font-medium">Website: ducanthinh.com</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        Đơn vị uy tín hàng đầu tại Đà Nẵng chuyên Thiết Kế & Thi Công Xây Dựng - Quảng Cáo - Nội Thất Trọn Gói: Shop, Showroom, Thẩm Mỹ Viện, Spa, Tiệm Nail, Hair Salon, Coffee, Nhà Hàng, Photobooth, Music Box, Phòng Tập Pilates, Văn Phòng.
                    </p>
                    <div class="space-y-1.5 text-xs text-slate-200 pt-1">
                        <div><i class="fa-solid fa-location-dot text-brand-gold w-5"></i><strong>VP + XSX 1:</strong> 19 Ngô Chân Lưu - P. Hoà Khánh - TP. Đà Nẵng</div>
                        <div><i class="fa-solid fa-warehouse text-brand-gold w-5"></i><strong>Xưởng XSX 2:</strong> 121 Nguyễn Bảo - Hoà Châu - Đà Nẵng</div>
                        <div><i class="fa-solid fa-phone text-brand-gold w-5"></i><strong>Hotline / Zalo:</strong> <a href="tel:0981708494" class="text-brand-goldLight font-bold">0981.708.494</a></div>
                        <div><i class="fa-solid fa-globe text-brand-gold w-5"></i><strong>Website:</strong> <a href="https://ducanthinh.com" class="hover:text-brand-goldLight">https://ducanthinh.com</a></div>
                    </div>
                </div>

                <!-- Cột 2: Danh mục dịch vụ chuẩn PenConcept -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="font-heading font-bold text-xs sm:text-sm text-white uppercase tracking-wider border-l-4 border-brand-gold pl-2.5">
                        DANH MỤC THIẾT KẾ & THI CÔNG
                    </h4>
                    <ul class="grid grid-cols-1 sm:grid-cols-2 gap-2 text-xs text-slate-300 pt-1">
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('shop')" class="hover:text-brand-goldLight"><i class="fa-solid fa-angle-right text-brand-gold mr-1.5"></i>Nội Thất Shop - Showroom</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('spa')" class="hover:text-brand-goldLight"><i class="fa-solid fa-angle-right text-brand-gold mr-1.5"></i>Thẩm Mỹ Viện - Spa</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('nail')" class="hover:text-brand-goldLight"><i class="fa-solid fa-angle-right text-brand-gold mr-1.5"></i>Tiệm Nail - Hair Salon</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('cafe')" class="hover:text-brand-goldLight"><i class="fa-solid fa-angle-right text-brand-gold mr-1.5"></i>Nhà Hàng - Coffee - Bar</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('photobooth')" class="hover:text-brand-goldLight"><i class="fa-solid fa-angle-right text-brand-gold mr-1.5"></i>Nội Thất Photobooth</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('photobooth')" class="hover:text-brand-goldLight"><i class="fa-solid fa-angle-right text-brand-gold mr-1.5"></i>Music Box & Phòng Pilates</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('quangcao')" class="hover:text-brand-goldLight"><i class="fa-solid fa-angle-right text-brand-gold mr-1.5"></i>Nội Thất Văn Phòng</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterCategory('quangcao')" class="hover:text-brand-goldLight"><i class="fa-solid fa-angle-right text-brand-gold mr-1.5"></i>Xây Dựng & Quảng Cáo</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hỗ trợ khách hàng -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="font-heading font-bold text-xs sm:text-sm text-white uppercase tracking-wider border-l-4 border-brand-gold pl-2.5">
                        KẾT NỐI VỚI CHÚNG TÔI
                    </h4>
                    <p class="text-xs text-slate-300 leading-relaxed pt-1">
                        Khảo sát tận nơi miễn phí tại Đà Nẵng & Miền Trung. Cam kết đúng tiến độ khai trương và chất lượng vật tư theo hợp đồng.
                    </p>
                    <div class="flex items-center gap-2.5 pt-2">
                        <a href="https://www.facebook.com/profile.php?id=61585341208717" target="_blank" rel="noopener noreferrer" class="w-9 h-9 rounded-lg bg-blue-600 hover:bg-blue-500 text-white flex items-center justify-center transition" aria-label="Facebook">
                            <i class="fa-brands fa-facebook-f"></i>
                        </a>
                        <a href="https://zalo.me/0981708494" target="_blank" rel="noopener noreferrer" class="w-9 h-9 rounded-lg bg-sky-500 hover:bg-sky-400 text-white flex items-center justify-center transition font-bold text-xs" aria-label="Zalo">
                            Zalo
                        </a>
                        <a href="tel:0981708494" class="w-9 h-9 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white flex items-center justify-center transition" aria-label="Gọi điện">
                            <i class="fa-solid fa-phone"></i>
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <div>© 2026 Bản quyền thuộc về <strong class="text-white">Đức An Thịnh Decor (ducanthinh.com)</strong>.</div>
                <div>Hotline/Zalo: <strong class="text-brand-goldLight">0981.708.494</strong> • Đà Nẵng, Việt Nam</div>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         - Tương thích hiển thị đẹp trên cả Máy Tính và Điện Thoại
         ========================================== -->
    <!-- Cụm nút nổi bên phải màn hình -->
    <div class="fixed right-3 bottom-16 lg:bottom-6 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=61585341208717" target="_blank" rel="noopener noreferrer" class="group flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white p-2.5 sm:px-3.5 sm:py-2.5 rounded-full shadow-lg transition" title="Chat Facebook Fanpage">
            <i class="fa-brands fa-facebook-messenger text-base sm:text-lg"></i>
            <span class="hidden sm:inline text-xs font-bold">Fanpage</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0981708494" target="_blank" rel="noopener noreferrer" class="group flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white p-2.5 sm:px-3.5 sm:py-2.5 rounded-full shadow-lg transition" title="Nhắn tin Zalo 0981.708.494">
            <span class="font-extrabold text-xs sm:text-sm leading-none px-0.5">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold">0981.708.494</span>
        </a>

        <!-- Nút Gọi Hotline -->
        <a href="tel:0981708494" class="pulse-btn flex items-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white p-3 sm:px-4 sm:py-2.5 rounded-full shadow-xl transition" title="Gọi ngay 0981.708.494">
            <i class="fa-solid fa-phone-volume text-base sm:text-lg"></i>
            <span class="hidden sm:inline text-xs font-extrabold tracking-wide">0981.708.494</span>
        </a>
    </div>

    <!-- Thanh liên hệ nhanh cố định dưới đáy màn hình Điện Thoại -->
    <div class="lg:hidden fixed bottom-0 inset-x-0 z-50 bg-white border-t border-slate-200 shadow-2xl grid grid-cols-3 text-center">
        <a href="tel:0981708494" class="py-2.5 flex items-center justify-center gap-1.5 bg-brand-gold text-white font-bold text-xs">
            <i class="fa-solid fa-phone-volume"></i>
            <span>0981.708.494</span>
        </a>
        <a href="https://zalo.me/0981708494" target="_blank" rel="noopener noreferrer" class="py-2.5 flex items-center justify-center gap-1.5 bg-sky-600 text-white font-bold text-xs">
            <i class="fa-solid fa-comment-dots"></i>
            <span>Chat Zalo</span>
        </a>
        <a href="https://www.facebook.com/profile.php?id=61585341208717" target="_blank" rel="noopener noreferrer" class="py-2.5 flex items-center justify-center gap-1.5 bg-blue-600 text-white font-bold text-xs">
            <i class="fa-brands fa-facebook"></i>
            <span>Fanpage</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM CHI TIẾT SẢN PHẨM & NHẬN BÁO GIÁ (Không dùng alert)
         ========================================== -->
    <div id="productModal" class="fixed inset-0 z-50 hidden bg-black/75 backdrop-blur-sm flex items-center justify-center p-3">
        <div class="bg-white rounded-xl max-w-2xl w-full overflow-hidden shadow-2xl border border-slate-200 relative animate-fadeIn">
            <button onclick="closeProductModal()" aria-label="Đóng" class="absolute top-3 right-3 z-10 w-8 h-8 rounded-full bg-black/60 hover:bg-brand-gold text-white flex items-center justify-center transition">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="grid grid-cols-1 md:grid-cols-2">
                <div class="aspect-[4/3] md:aspect-auto bg-slate-100">
                    <img id="modalImg" src="" alt="" class="w-full h-full object-cover">
                </div>
                <div class="p-4 sm:p-5 flex flex-col justify-between">
                    <div>
                        <span id="modalCat" class="inline-block text-[11px] font-bold text-brand-gold uppercase mb-1">Đức An Thịnh Decor</span>
                        <h3 id="modalTitle" class="font-heading font-bold text-sm sm:text-base text-brand-dark mb-2"></h3>
                        <p id="modalDesc" class="text-xs text-slate-600 leading-relaxed mb-3"></p>
                        <div class="bg-slate-50 p-2.5 rounded-lg border border-slate-200 text-[11px] text-slate-700 space-y-1 mb-4">
                            <div><i class="fa-solid fa-check text-brand-gold mr-1.5"></i>Khảo sát & tư vấn thiết kế 3D tận nơi</div>
                            <div><i class="fa-solid fa-check text-brand-gold mr-1.5"></i>Sản xuất trực tiếp tại 2 xưởng Đà Nẵng</div>
                            <div><i class="fa-solid fa-check text-brand-gold mr-1.5"></i>Hotline/Zalo báo giá: <strong>0981.708.494</strong></div>
                        </div>
                    </div>
                    <div class="flex items-center gap-2">
                        <a href="#form-bao-gia" onclick="closeProductModal()" class="flex-1 text-center py-2.5 px-3 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-xs">
                            Nhận Báo Giá Mẫu Này
                        </a>
                        <a href="https://zalo.me/0981708494" target="_blank" rel="noopener noreferrer" class="py-2.5 px-3 rounded-lg bg-sky-600 hover:bg-sky-700 text-white font-bold text-xs">
                            Chat Zalo
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Hộp thông báo gửi form thành công (Thay thế hoàn toàn alert) -->
    <div id="toastMessage" class="fixed top-5 right-5 z-50 hidden max-w-sm bg-brand-dark text-white px-4 py-3 rounded-xl shadow-2xl border-l-4 border-brand-gold text-xs">
        <div class="font-bold text-brand-goldLight mb-0.5"><i class="fa-solid fa-circle-check mr-1.5"></i>Đã ghi nhận yêu cầu báo giá!</div>
        <div id="toastBody" class="text-slate-200 leading-snug"></div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU 15 ẢNH GOOGLE DRIVE, DỰ ÁN ĐÀ NẴNG & SLIDER
         ========================================== -->
    <script>
        // Hàm dự phòng đa tầng cho ảnh Google Drive giúp luôn hiển thị tốt
        function handleDriveImgError(imgEl, fallbackUrl) {
            const driveId = imgEl.getAttribute('data-drive-id');
            const step = parseInt(imgEl.getAttribute('data-retry-step') || '0', 10);
            if (driveId && step === 0) {
                imgEl.setAttribute('data-retry-step', '1');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1200';
            } else if (driveId && step === 1) {
                imgEl.setAttribute('data-retry-step', '2');
                imgEl.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
            } else {
                imgEl.onerror = null;
                imgEl.src = fallbackUrl;
            }
        }

        // Danh sách đầy đủ 15 ảnh thực tế từ Google Drive phân loại chuẩn theo danh mục PenConcept & Đức An Thịnh Decor
        const realProducts = [
            {
                id: 1,
                driveId: '1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl',
                category: 'shop',
                categoryName: 'Thiết Kế Nội Thất Shop - Showroom',
                title: 'Thiết Kế & Thi Công Nội Thất Showroom Trưng Bày Hiện Đại Sang Trọng',
                desc: 'Thi công trọn gói hệ tủ kệ trưng bày MDF chống ẩm phủ Melamine kết hợp đèn LED thanh ray tôn vinh sản phẩm tại Đà Nẵng.',
                fallback: 'https://images.unsplash.com/photo-1441986300917-64674bd600d8?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 2,
                driveId: '13jgchAVsd5mT8za7XSB8rsvskLKlbKyS',
                category: 'spa',
                categoryName: 'Thiết Kế Thẩm Mỹ Viện - Spa',
                title: 'Thiết Kế & Thi Công Không Gian Thẩm Mỹ Viện & Spa Chăm Sóc Sắc Đẹp',
                desc: 'Không gian sảnh đón tiếp và phòng liệu trình Spa thiết kế tinh tế, ánh sáng ấm áp, tối ưu công năng vận hành.',
                fallback: 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 3,
                driveId: '1rAw6vKjVMRcNJS2BxpVDMMDfqoSe8Enl',
                category: 'shop',
                categoryName: 'Thiết Kế Nội Thất Shop - Showroom',
                title: 'Thiết Kế & Thi Công Trọn Gói Shop Thời Trang & Phụ Kiện Cao Cấp',
                desc: 'Bố trí quầy thu ngân phong thủy, giá treo inox mạ vàng PVD và hệ thống gương soi nịnh dáng cho cửa hàng thời trang.',
                fallback: 'https://images.unsplash.com/photo-1567401893414-76b7b1e5a7a5?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 4,
                driveId: '1c954dUrUQmmKWRCTfqlZnANCflrRXZAX',
                category: 'quangcao',
                categoryName: 'Văn Phòng - Bảng Hiệu Quảng Cáo',
                title: 'Thiết Kế & Thi Công Nội Thất Văn Phòng Công Ty Chuyên Nghiệp',
                desc: 'Thi công vách logo nhận diện thương hiệu, bàn họp, cụm bàn làm việc nhân viên hiện đại tối ưu diện tích.',
                fallback: 'https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 5,
                driveId: '1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86',
                category: 'cafe',
                categoryName: 'Nhà Hàng - Cà Phê - Bar',
                title: 'Thiết Kế & Thi Công Trọn Gói Quán Coffee & Không Gian F&B Ấn Tượng',
                desc: 'Thi công quầy pha chế Barista, bàn ghế gỗ tự nhiên kết hợp sắt sơn tĩnh điện và trang trí ánh sáng thu hút khách hàng.',
                fallback: 'https://images.unsplash.com/photo-1554118811-1e0d58224f24?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 6,
                driveId: '1SLFGLkI0UifBXEtTqOkfmBxf1SK-Kkjo',
                category: 'nail',
                categoryName: 'Tiệm Nail - Hair Salon',
                title: 'Thiết Kế & Thi Công Nội Thất Tiệm Nail - Mi Phong Cách Hàn Quốc',
                desc: 'Hệ ghế sofa làm Nail êm ái, bồn ngâm chân, kệ trưng bày sơn gel âm tường sang trọng thu hút phái đẹp.',
                fallback: 'https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 7,
                driveId: '16jmRHwZqTYGHlB9U-lxin2VZTwobwEUW',
                category: 'nail',
                categoryName: 'Tiệm Nail - Hair Salon',
                title: 'Thiết Kế & Thi Công Trọn Gói Hair Salon & Tạo Mẫu Tóc Chuyên Nghiệp',
                desc: 'Trang bị hệ gương cắt tóc đèn LED cảm ứng, giường gội đầu dưỡng sinh và tủ trưng bày mỹ phẩm tóc cao cấp.',
                fallback: 'https://images.unsplash.com/photo-1560066984-138dadb4c035?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 8,
                driveId: '14J36h1Gn6nJEHu4_yQj4P11p9enPr5pP',
                category: 'cafe',
                categoryName: 'Nhà Hàng - Cà Phê - Bar',
                title: 'Thiết Kế & Thi Công Nội Thất Nhà Hàng Ẩm Thực & Phòng VIP',
                desc: 'Không gian ẩm thực ấm cúng, phân luồng di chuyển khoa học, kết hợp hệ thống hút mùi và chiếu sáng chuẩn nhà hàng.',
                fallback: 'https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 9,
                driveId: '1mj2bb_Q5lhK7yJfDmDWihaLfG6f4UR6q',
                category: 'photobooth',
                categoryName: 'Photobooth - Music Box - Pilates',
                title: 'Thiết Kế & Thi Công Cửa Hàng Photobooth Chụp Ảnh Lấy Liền',
                desc: 'Thiết kế các buồng chụp ảnh theo concept trẻ trung, khu vực makeup & trưng bày phụ kiện bắt mắt giới trẻ.',
                fallback: 'https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 10,
                driveId: '1R6wUU4Ty3YNgLT2JDSuGAsohxJRCAs3c',
                category: 'photobooth',
                categoryName: 'Photobooth - Music Box - Pilates',
                title: 'Thiết Kế & Thi Công Phòng Giải Trí Music Box & Studio Cách Âm',
                desc: 'Thi công vách cách âm - tiêu âm chuyên dụng, hiệu ứng đèn LED RGB hiện đại cho mô hình phòng hát Music Box.',
                fallback: 'https://images.unsplash.com/photo-1598488035139-bdbb2231ce04?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 11,
                driveId: '1iDGy3qGrl7B825739Dso1dXUl5N5pjZp',
                category: 'quangcao',
                categoryName: 'Văn Phòng - Bảng Hiệu Quảng Cáo',
                title: 'Thiết Kế & Thi Công Quầy Lễ Tân & Không Gian Văn Phòng Giao Dịch',
                desc: 'Gia công quầy lễ tân bo cong hiện đại kết hợp vách nan gỗ và chữ nổi thương hiệu sang trọng.',
                fallback: 'https://images.unsplash.com/photo-1497366811353-6870744d04b2?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 12,
                driveId: '1kfeqpT5OPp4qxeF2mSi38icE7jb1hF5I',
                category: 'quangcao',
                categoryName: 'Văn Phòng - Bảng Hiệu Quảng Cáo',
                title: 'Thi Công Mặt Tiền Bảng Hiệu Quảng Cáo Alu Chữ Nổi Đèn LED Trọn Gói',
                desc: 'Thiết kế và thi công mặt dựng Alu, khung sắt mạ kẽm, chữ nổi Mica/Inox gắn LED siêu sáng bền bỉ tại Đà Nẵng.',
                fallback: 'https://images.unsplash.com/photo-1542744173-8e7e53415bb0?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 13,
                driveId: '1L-50zH_kYfXmupV2kAK43Ky0Ad6zgRvk',
                category: 'shop',
                categoryName: 'Thiết Kế Nội Thất Shop - Showroom',
                title: 'Thiết Kế & Thi Công Showroom Mỹ Phẩm, Nước Hoa & Quà Tặng',
                desc: 'Hệ tủ trưng bày kính cường lực tích hợp LED hắt sáng từng tầng kệ giúp sản phẩm lung linh và nâng tầm thương hiệu.',
                fallback: 'https://images.unsplash.com/photo-1522337360788-8b13dee7a37e?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 14,
                driveId: '1D4UTUkj_2FmCcC9oJMCCwr4mM8YK2j5q',
                category: 'spa',
                categoryName: 'Thiết Kế Thẩm Mỹ Viện - Spa',
                title: 'Thiết Kế & Thi Công Spa Dưỡng Sinh & Phòng Tập Pilates Hiện Đại',
                desc: 'Tối ưu không gian thư giãn yên tĩnh, sàn gỗ ấm áp, hệ vòm cong mềm mại chuẩn phong cách Hàn Quốc & Wabi Sabi.',
                fallback: 'https://images.unsplash.com/photo-1519823551278-64ac92734fb1?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 15,
                driveId: '17bzkccO8qBV0nlhzwO1rGdvVLB5Nrx6C',
                category: 'cafe',
                categoryName: 'Nhà Hàng - Cà Phê - Bar',
                title: 'Thiết Kế & Thi Công Trọn Gói Quán Trà Sữa, Bakery & Cafe Check-in',
                desc: 'Không gian trẻ trung với nhiều góc chụp hình ấn tượng, thi công nhanh gọn từ phần thô xây dựng đến nội thất hoàn thiện.',
                fallback: 'https://images.unsplash.com/photo-1501339847302-ac426a4a7cbb?auto=format&fit=crop&w=800&q=80'
            }
        ];

        // Danh sách 8 Dự Án Tiêu Biểu tại Đà Nẵng (Section Dự Án Đà Nẵng ngoài Trang Chủ)
        const danangProjects = [
            {
                driveId: '1wv3EVzvsQc5bE_5SE_nSeU9949rs5Ttl',
                title: 'Dự Án Thiết Kế & Thi Công Showroom Thời Trang – Quận Hải Châu, Đà Nẵng',
                area: 'Hoàn thiện trọn gói bảng hiệu & nội thất MDF chống ẩm An Cường',
                fallback: 'https://images.unsplash.com/photo-1441986300917-64674bd600d8?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '13jgchAVsd5mT8za7XSB8rsvskLKlbKyS',
                title: 'Dự Án Thẩm Mỹ Viện & Spa Chăm Sóc Da – Quận Thanh Khê, Đà Nẵng',
                area: 'Thi công cải tạo phần thô, vách thạch cao & nội thất phòng VIP',
                fallback: 'https://images.unsplash.com/photo-1540555700478-4be289fbecef?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '16jmRHwZqTYGHlB9U-lxin2VZTwobwEUW',
                title: 'Dự Án Tổ Hợp Tiệm Nail & Hair Salon – Quận Sơn Trà, Đà Nẵng',
                area: 'Thiết kế 3D & sản xuất lắp đặt trọn gói tại xưởng Đức An Thịnh',
                fallback: 'https://images.unsplash.com/photo-1560066984-138dadb4c035?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1GDsxm71PFzCSGQR4X-e4oQxCIbgAnK86',
                title: 'Dự Án Không Gian Quán Coffee & Trà Sữa – Quận Liên Chiểu, Đà Nẵng',
                area: 'Thi công quầy Bar, hệ thống điện ánh sáng & nội thất bàn ghế',
                fallback: 'https://images.unsplash.com/photo-1554118811-1e0d58224f24?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1mj2bb_Q5lhK7yJfDmDWihaLfG6f4UR6q',
                title: 'Dự Án Chuỗi Cửa Hàng Photobooth Hàn Quốc – Trung Tâm TP. Đà Nẵng',
                area: 'Thiết kế & thi công trọn gói buồng chụp, khu vực gương trang điểm',
                fallback: 'https://images.unsplash.com/photo-1513694203232-719a280e022f?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1R6wUU4Ty3YNgLT2JDSuGAsohxJRCAs3c',
                title: 'Dự Án Phòng Giải Trí Music Box & Studio – Quận Cẩm Lệ, Đà Nẵng',
                area: 'Thi công cách âm tiêu âm, trang trí nội thất & ánh sáng LED',
                fallback: 'https://images.unsplash.com/photo-1598488035139-bdbb2231ce04?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1c954dUrUQmmKWRCTfqlZnANCflrRXZAX',
                title: 'Dự Án Văn Phòng Đại Diện & Showroom – Quận Ngũ Hành Sơn, Đà Nẵng',
                area: 'Thiết kế thi công sảnh lễ tân, phòng họp & khu làm việc',
                fallback: 'https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1kfeqpT5OPp4qxeF2mSi38icE7jb1hF5I',
                title: 'Dự Án Bảng Hiệu Quảng Cáo & Mặt Tiền Cửa Hàng – Hòa Khánh, Đà Nẵng',
                area: 'Gia công lắp đặt mặt dựng Alu, chữ nổi Mica LED sáng chân',
                fallback: 'https://images.unsplash.com/photo-1542744173-8e7e53415bb0?auto=format&fit=crop&w=800&q=80'
            }
        ];

        // Render Sản Phẩm (Không để nhãn dán đè lên ảnh, Điện thoại 2 cột, Tên sản phẩm hiển thị đầy đủ)
        function renderProducts(filterCat = 'all') {
            const grid = document.getElementById('productGrid');
            if (!grid) return;

            const filtered = filterCat === 'all'
                ? realProducts
                : realProducts.filter(item => item.category === filterCat);

            grid.innerHTML = filtered.map(item => `
                <div class="bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold transition shadow-sm flex flex-col justify-between group">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openProductModal(${item.id})">
                            <img 
                                src="https://lh3.googleusercontent.com/d/${item.driveId}=w700" 
                                data-drive-id="${item.driveId}"
                                alt="${item.title}" 
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                onerror="handleDriveImgError(this, '${item.fallback}')"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[10.5px] sm:text-[11px] font-semibold text-brand-gold mb-1 product-title-full">${item.categoryName}</div>
                            <h3 onclick="openProductModal(${item.id})" class="font-heading font-bold text-xs sm:text-[13.5px] text-brand-dark group-hover:text-brand-gold transition cursor-pointer product-title-full">
                                ${item.title}
                            </h3>
                            <p class="hidden sm:block text-xs text-slate-500 mt-1.5 line-clamp-2">${item.desc}</p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 flex items-center justify-between gap-2 border-t border-slate-100 mt-1">
                        <button onclick="openProductModal(${item.id})" class="text-[11px] font-bold text-brand-dark hover:text-brand-gold transition">
                            Xem Chi Tiết
                        </button>
                        <a href="#form-bao-gia" class="px-2.5 py-1 rounded bg-brand-dark hover:bg-brand-gold text-brand-goldLight hover:text-white text-[10.5px] sm:text-[11px] font-bold transition">
                            Báo Giá
                        </a>
                    </div>
                </div>
            `).join('');
        }

        // Lọc danh mục sản phẩm
        function filterCategory(cat) {
            renderProducts(cat);
            const buttons = document.querySelectorAll('[data-cat-btn]');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === cat) {
                    btn.className = 'home-cat-pill px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-bold bg-brand-dark text-brand-goldLight border border-brand-dark';
                } else {
                    btn.className = 'home-cat-pill px-2.5 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-gold';
                }
            });
        }

        // Render Dự Án Đà Nẵng (Điện thoại 2 cột, Máy tính 4 cột, không nhãn dán)
        function renderDanangProjects() {
            const container = document.getElementById('danangProjectGrid');
            if (!container) return;

            container.innerHTML = danangProjects.map(proj => `
                <div class="bg-slate-50 rounded-xl overflow-hidden border border-slate-200 hover:border-brand-gold transition shadow-sm flex flex-col justify-between group">
                    <div>
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                            <img 
                                src="https://lh3.googleusercontent.com/d/${proj.driveId}=w700" 
                                data-drive-id="${proj.driveId}"
                                alt="${proj.title}" 
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                onerror="handleDriveImgError(this, '${proj.fallback}')"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="font-heading font-bold text-xs sm:text-[13.5px] text-brand-dark group-hover:text-brand-gold transition product-title-full">
                                ${proj.title}
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 mt-1 product-title-full">${proj.area}</p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5">
                        <a href="#form-bao-gia" class="inline-flex items-center gap-1 text-[11px] font-bold text-brand-gold hover:underline">
                            <span>Nhận tư vấn tương tự</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </div>
            `).join('');
        }

        // Mở Modal chi tiết sản phẩm
        function openProductModal(id) {
            const item = realProducts.find(p => p.id === id);
            if (!item) return;
            const modal = document.getElementById('productModal');
            const img = document.getElementById('modalImg');
            img.setAttribute('data-drive-id', item.driveId);
            img.setAttribute('data-retry-step', '0');
            img.onerror = function() { handleDriveImgError(this, item.fallback); };
            img.src = `https://lh3.googleusercontent.com/d/${item.driveId}=w900`;
            img.alt = item.title;

            document.getElementById('modalCat').textContent = item.categoryName;
            document.getElementById('modalTitle').textContent = item.title;
            document.getElementById('modalDesc').textContent = item.desc;
            modal.classList.remove('hidden');
        }

        function closeProductModal() {
            document.getElementById('productModal').classList.add('hidden');
        }

        // Điều khiển Slider 2 Banner Tự Trượt Kích Thước Bằng Nhau
        let currentSlideIndex = 0;
        const totalSlides = 2;
        let slideInterval;

        function showSlide(index) {
            const slides = document.querySelectorAll('.hero-slide');
            const dots = document.querySelectorAll('.slide-dot');
            currentSlideIndex = (index + totalSlides) % totalSlides;

            slides.forEach((slide, idx) => {
                if (idx === currentSlideIndex) {
                    slide.classList.remove('hidden');
                } else {
                    slide.classList.add('hidden');
                }
            });

            dots.forEach((dot, idx) => {
                if (idx === currentSlideIndex) {
                    dot.className = 'slide-dot w-6 h-1.5 rounded-full bg-brand-gold transition-all';
                } else {
                    dot.className = 'slide-dot w-2 h-1.5 rounded-full bg-white/50 transition-all';
                }
            });
        }

        function changeSlide(step) {
            showSlide(currentSlideIndex + step);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlideIndex + 1);
            }, 5500);
        }

        // Chuyển đổi địa chỉ Google Maps giữa Xưởng 1 và Xưởng 2
        function switchMapLocation(loc) {
            const iframe = document.getElementById('googleMapIframe');
            const btn1 = document.getElementById('mapBtn1');
            const btn2 = document.getElementById('mapBtn2');
            if (loc === 1) {
                iframe.src = 'https://maps.google.com/maps?q=19%20Ng%C3%B4%20Ch%C3%A2n%20L%C6%B0u%2C%20Ho%C3%A0%20Kh%C3%A1nh%2C%20Li%C3%AAn%20Chi%E1%BB%83u%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed';
                btn1.className = 'px-2.5 py-1.5 rounded-lg bg-brand-dark text-brand-goldLight text-[11px] font-bold';
                btn2.className = 'px-2.5 py-1.5 rounded-lg bg-slate-100 text-slate-700 hover:bg-slate-200 text-[11px] font-semibold';
            } else {
                iframe.src = 'https://maps.google.com/maps?q=121%20Nguy%E1%BB%85n%20B%E1%BA%A3o%2C%20Ho%C3%A0%20Ch%C3%A2u%2C%20H%C3%B2a%20Vang%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed';
                btn2.className = 'px-2.5 py-1.5 rounded-lg bg-brand-dark text-brand-goldLight text-[11px] font-bold';
                btn1.className = 'px-2.5 py-1.5 rounded-lg bg-slate-100 text-slate-700 hover:bg-slate-200 text-[11px] font-semibold';
            }
        }

        // Bật/tắt Menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        // Xử lý gửi Form Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const service = document.getElementById('qService').value;

            const toast = document.getElementById('toastMessage');
            const toastBody = document.getElementById('toastBody');
            toastBody.textContent = `Cảm ơn ${name} (${phone}). Bộ phận Kiến Trúc Sư Đức An Thịnh Decor sẽ liên hệ tư vấn hạng mục "${service}" ngay!`;
            toast.classList.remove('hidden');

            document.getElementById('quoteForm').reset();
            setTimeout(() => {
                toast.classList.add('hidden');
            }, 6000);
        }

        // Khởi tạo khi tải trang
        window.addEventListener('DOMContentLoaded', () => {
            renderProducts('all');
            renderDanangProjects();
            resetSlideTimer();
        });
    </script>
</body>
</html>
