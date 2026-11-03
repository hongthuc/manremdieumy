<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Màn Rèm Diệu My Đà Nẵng - Chuyên Thi Công Màn Rèm, Cửa Lưới, Chăn Ga Gối Nệm</title>
    <meta name="description" content="Màn Rèm Diệu My (manremdieumy.com) - Chuyên tư vấn, thiết kế và thi công lắp đặt màn rèm cửa, cửa lưới chống muỗi, chăn ga gối nệm, giàn phơi thông minh uy tín tại 71 Âu Cơ, Liên Chiểu, Đà Nẵng. Hotline: 0899.922.221 - 0788.694.567.">

    <!-- Open Graph Thumbnail là Logo trang web khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://manremdieumy.com/">
    <meta property="og:title" content="Màn Rèm Diệu My Đà Nẵng | manremdieumy.com">
    <meta property="og:description" content="Chuyên thi công lắp đặt màn rèm cửa, cửa lưới chống muỗi, chăn ga gối đệm, giàn phơi thông minh tại 71 Âu Cơ, Liên Chiểu, Đà Nẵng. ĐT: 0899.922.221 - 0788.694.567">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1S3ovJm0_cQAApYDoNDZU19yCApAsddAE=w1200">
    <meta property="og:image:alt" content="Logo Màn Rèm Diệu My Đà Nẵng">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Màn Rèm Diệu My Đà Nẵng | manremdieumy.com">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1S3ovJm0_cQAApYDoNDZU19yCApAsddAE=w1200">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1S3ovJm0_cQAApYDoNDZU19yCApAsddAE=w200">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter / Roboto chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        primary: '#0f4c81',      /* Xanh đậm nội thất sang trọng */
                        primaryDark: '#09345a',
                        accent: '#d97706',       /* Vàng đồng điểm nhấn */
                        saleRed: '#d0021b',      /* Đỏ giảm giá chuẩn Flatsome */
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome Container 1200px */
        .flatsome-container {
            width: 100%;
            max-width: 1220px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 640px) {
            .flatsome-container {
                padding-left: 16px;
                padding-right: 16px;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder (Section Title Style: Normal/Center) */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-main {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 10px;
            gap: 8px;
            flex-wrap: wrap;
        }
        .section-title-main h2 {
            position: relative;
            font-weight: 800;
            text-transform: uppercase;
            color: #0f4c81;
            margin: 0;
            line-height: 1.3;
        }
        .section-title-main h2::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: -12px;
            width: 100%;
            height: 3px;
            background-color: #d97706;
        }

        /* Badge giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-Badge-sale {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #d0021b;
            color: #ffffff;
            font-weight: 700;
            font-size: 12px;
            line-height: 1;
            padding: 6px 8px;
            border-radius: 9999px;
            box-shadow: 0 2px 6px rgba(208, 2, 27, 0.35);
        }

        /* Dropdown menu trên máy tính */
        .nav-item-has-children:hover .nav-dropdown {
            display: block;
            animation: fadeInDown 0.18s ease-out;
        }
        @keyframes fadeInDown {
            from { opacity: 0; transform: translateY(6px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(208, 2, 27, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(208, 2, 27, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(208, 2, 27, 0); }
        }
        .pulse-btn {
            animation: pulseRing 2s infinite;
        }

        /* Ẩn thanh cuộn phụ nhưng vẫn cho phép cuộn nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- ==========================================
         TOP BAR CHUẨN FLATSOME (KHÔNG HIỂN THỊ TÙY CHỌN UX BUILDER)
    =========================================== -->
    <div class="bg-primaryDark text-white text-xs py-2 border-b border-white/10">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 flex-wrap">
                <span class="inline-flex items-center gap-1.5 font-medium">
                    <i class="fa-solid fa-globe text-amber-400"></i>
                    <span>manremdieumy.com</span>
                </span>
                <span class="hidden md:inline text-white/30">|</span>
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    <span>71 Âu Cơ, Phường Liên Chiểu, Tp.Đà Nẵng</span>
                </span>
            </div>
            <div class="hidden sm:flex items-center gap-4">
                <a href="https://maps.app.goo.gl/cWTEd5tFcBXQV7EBA" target="_blank" rel="noopener" class="hover:text-amber-300 transition inline-flex items-center gap-1">
                    <i class="fa-solid fa-map-location-dot text-amber-400"></i> Chỉ đường Google Maps
                </a>
                <span class="text-white/30">|</span>
                <a href="https://www.facebook.com/manremcuasodanang" target="_blank" rel="noopener" class="hover:text-amber-300 transition inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook text-amber-400"></i> Fanpage Màn Rèm Diệu My
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER MAIN CHUẨN FLATSOME
         (Không để nút Gọi Ngay trên Header để tránh tràn viền)
    =========================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
        <div class="flatsome-container py-2.5 sm:py-3.5">
            <div class="flex items-center justify-between gap-2 sm:gap-4">
                
                <!-- Nút mở Menu trên Điện Thoại -->
                <button type="button" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-primary hover:bg-slate-100 shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo thương hiệu Màn Rèm Diệu My -->
                <a href="#top" class="flex items-center gap-2.5 min-w-0 shrink-0">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1S3ovJm0_cQAApYDoNDZU19yCApAsddAE=w400" 
                        onerror="handleDriveImgError(this, '1S3ovJm0_cQAApYDoNDZU19yCApAsddAE', 'DIỆU MY')"
                        alt="Logo Màn Rèm Diệu My Đà Nẵng" 
                        class="h-11 w-11 sm:h-14 sm:w-14 object-contain rounded-lg border border-slate-100 bg-white p-0.5 shrink-0"
                    >
                    <div class="min-w-0">
                        <span class="block font-extrabold text-primary text-base sm:text-xl tracking-tight leading-tight truncate">
                            MÀN RÈM DIỆU MY
                        </span>
                        <span class="block text-[11px] sm:text-xs text-slate-500 font-medium truncate">
                            Sắc màu cuộc sống • Đà Nẵng
                        </span>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-4">
                    <form onsubmit="handleSearch(event)" class="w-full flex rounded-lg overflow-hidden border-2 border-primary/80 bg-white focus-within:border-amber-600 transition">
                        <select id="searchCategorySelect" class="bg-slate-100 text-slate-700 text-xs font-semibold px-3 border-r border-slate-200 focus:outline-none">
                            <option value="all">Tất cả danh mục</option>
                            <option value="rem-cua">Rèm Cửa</option>
                            <option value="cua-luoi">Cửa Lưới Chống Muỗi</option>
                            <option value="nem">Nệm Cao Cấp</option>
                            <option value="gian-phoi">Giàn Phơi Thông Minh</option>
                            <option value="chan-ga">Chăn Ga Khách Sạn</option>
                            <option value="goi">Gối Cao Cấp</option>
                        </select>
                        <input 
                            type="text" 
                            id="desktopSearchInput"
                            placeholder="Tìm kiếm rèm vải 2 lớp, rèm cầu vồng, cửa lưới, chăn ga..." 
                            class="w-full px-3.5 py-2 text-sm text-slate-800 focus:outline-none"
                        >
                        <button type="submit" class="bg-primary hover:bg-primaryDark text-white px-4 text-sm font-semibold transition shrink-0">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </form>
                </div>

                <!-- Thông tin địa chỉ & Nút mở form báo giá (Không để nút gọi ngay tránh tràn viền) -->
                <div class="flex items-center gap-2 shrink-0">
                    <div class="hidden xl:flex items-center gap-2.5 text-left pr-2">
                        <div class="w-9 h-9 rounded-full bg-amber-50 text-amber-600 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-award"></i>
                        </div>
                        <div class="text-xs leading-tight">
                            <p class="font-bold text-slate-800">Tư Vấn & Đo Đạc Tận Nơi</p>
                            <p class="text-slate-500">Miễn phí 100% tại Đà Nẵng</p>
                        </div>
                    </div>
                    <a href="#bao-gia" class="inline-flex items-center gap-1.5 bg-amber-600 hover:bg-amber-700 text-white text-xs sm:text-sm font-bold px-3 py-2 sm:px-4 sm:py-2.5 rounded-lg shadow-sm transition shrink-0">
                        <i class="fa-solid fa-file-signature"></i>
                        <span>Nhận Báo Giá</span>
                    </a>
                </div>
            </div>

            <!-- Thanh tìm kiếm gọn trên điện thoại -->
            <div class="mt-2.5 md:hidden">
                <form onsubmit="handleMobileSearch(event)" class="flex w-full rounded-lg overflow-hidden border border-slate-300 bg-slate-50">
                    <input 
                        type="text" 
                        id="mobileSearchInput"
                        placeholder="Tìm rèm vải, rèm cầu vồng, cửa lưới, nệm..." 
                        class="w-full px-3 py-2 text-xs text-slate-800 bg-transparent focus:outline-none"
                    >
                    <button type="submit" aria-label="Tìm kiếm" class="bg-primary text-white px-3.5 text-xs font-semibold shrink-0">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </form>
            </div>
        </div>

        <!-- ==========================================
             THANH ĐIỀU HƯỚNG & DANH MỤC TRÊN MÁY TÍNH (CHUẨN FLATSOME)
        =========================================== -->
        <nav class="hidden lg:block bg-primary text-white">
            <div class="flatsome-container flex items-center justify-between">
                
                <!-- Nút Mega Danh Mục Sản Phẩm Bên Trái -->
                <div class="relative nav-item-has-children">
                    <button type="button" class="flex items-center gap-2.5 bg-amber-600 hover:bg-amber-700 text-white font-bold text-xs uppercase tracking-wider px-4 py-3.5 transition">
                        <i class="fa-solid fa-bars-staggered text-sm"></i>
                        <span>DANH MỤC SẢN PHẨM</span>
                        <i class="fa-solid fa-chevron-down text-[10px] ml-1"></i>
                    </button>
                    <!-- Dropdown Danh mục đầy đủ như web mẫu HoangKimHome -->
                    <div class="nav-dropdown hidden absolute left-0 top-full w-64 bg-white text-slate-800 shadow-xl border border-slate-200 rounded-b-lg z-50 py-1">
                        <a href="#sec-rem-cua" class="flex items-center justify-between px-4 py-2.5 text-sm font-semibold hover:bg-amber-50 hover:text-primary border-b border-slate-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-person-booth text-primary w-4"></i> Rèm Cửa Cao Cấp</span>
                            <span class="text-[11px] bg-slate-100 px-1.5 py-0.5 rounded text-slate-600">8 loại</span>
                        </a>
                        <a href="#sec-cua-luoi" class="flex items-center justify-between px-4 py-2.5 text-sm font-semibold hover:bg-amber-50 hover:text-primary border-b border-slate-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-shield-virus text-primary w-4"></i> Cửa Lưới Chống Muỗi</span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400"></i>
                        </a>
                        <a href="#sec-nem" class="flex items-center justify-between px-4 py-2.5 text-sm font-semibold hover:bg-amber-50 hover:text-primary border-b border-slate-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-bed text-primary w-4"></i> Nệm Cao Su / Foam / Gấp 3</span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400"></i>
                        </a>
                        <a href="#sec-gian-phoi" class="flex items-center justify-between px-4 py-2.5 text-sm font-semibold hover:bg-amber-50 hover:text-primary border-b border-slate-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-shirt text-primary w-4"></i> Giàn Phơi Thông Minh</span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400"></i>
                        </a>
                        <a href="#sec-chan-ga" class="flex items-center justify-between px-4 py-2.5 text-sm font-semibold hover:bg-amber-50 hover:text-primary border-b border-slate-100">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-hotel text-primary w-4"></i> Chăn Ga Khách Sạn & Gia Đình</span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400"></i>
                        </a>
                        <a href="#sec-goi" class="flex items-center justify-between px-4 py-2.5 text-sm font-semibold hover:bg-amber-50 hover:text-primary">
                            <span class="flex items-center gap-2.5"><i class="fa-solid fa-cloud text-primary w-4"></i> Gối Cao Su & Gối Lông Vũ</span>
                            <i class="fa-solid fa-angle-right text-xs text-slate-400"></i>
                        </a>
                    </div>
                </div>

                <!-- Menu Ngang Chính -->
                <ul class="flex items-center gap-1 xl:gap-2 text-xs font-bold uppercase tracking-wide">
                    <li>
                        <a href="#top" class="block px-3 py-3.5 hover:bg-white/10 transition text-amber-300">Trang Chủ</a>
                    </li>
                    <!-- Dropdown Rèm Cửa -->
                    <li class="relative nav-item-has-children">
                        <a href="#sec-rem-cua" class="flex items-center gap-1 px-3 py-3.5 hover:bg-white/10 transition">
                            <span>Rèm Cửa</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown hidden absolute left-0 top-full w-56 bg-white text-slate-800 shadow-xl border border-slate-200 rounded-b-lg z-50 py-1 font-medium normal-case">
                            <a href="#sec-rem-cua" onclick="filterRemCategory('all')" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Tất cả Rèm Cửa</a>
                            <a href="#sec-rem-cua" onclick="filterRemCategory('rem-vai')" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Rèm Vải 2 Lớp & Chống Nắng</a>
                            <a href="#sec-rem-cua" onclick="filterRemCategory('rem-cau-vong')" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Rèm Cầu Vồng Hàn Quốc</a>
                            <a href="#sec-rem-cua" onclick="filterRemCategory('rem-cuon')" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Rèm Cuốn Văn Phòng & Trơn</a>
                            <a href="#sec-rem-cua" onclick="filterRemCategory('rem-go')" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Rèm Gỗ Tự Nhiên</a>
                            <a href="#sec-rem-cua" onclick="filterRemCategory('rem-to-ong')" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Rèm Tổ Ong & Vách Ngăn</a>
                            <a href="#sec-rem-cua" onclick="filterRemCategory('rem-la-doc')" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Rèm Lá Dọc & Rèm Nhôm</a>
                            <a href="#sec-rem-cua" onclick="filterRemCategory('thiet-bi')" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Động Cơ Rèm & Phụ Kiện</a>
                        </div>
                    </li>
                    <li>
                        <a href="#sec-cua-luoi" class="block px-3 py-3.5 hover:bg-white/10 transition">Cửa Lưới Chống Muỗi</a>
                    </li>
                    <li class="relative nav-item-has-children">
                        <a href="#sec-nem" class="flex items-center gap-1 px-3 py-3.5 hover:bg-white/10 transition">
                            <span>Nệm</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown hidden absolute left-0 top-full w-52 bg-white text-slate-800 shadow-xl border border-slate-200 rounded-b-lg z-50 py-1 font-medium normal-case">
                            <a href="#sec-nem" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Nệm Gấp Ba</a>
                            <a href="#sec-nem" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Nệm Cao Su Thiên Nhiên</a>
                            <a href="#sec-nem" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Nệm Cao Su / Memory Foam</a>
                            <a href="#sec-nem" class="block px-4 py-2 text-sm hover:bg-amber-50 hover:text-primary">Hỗ Trợ Nệm / Topper</a>
                        </div>
                    </li>
                    <li>
                        <a href="#sec-gian-phoi" class="block px-3 py-3.5 hover:bg-white/10 transition">Giàn Phơi</a>
                    </li>
                    <li>
                        <a href="#sec-chan-ga" class="block px-3 py-3.5 hover:bg-white/10 transition">Chăn Ga Khách Sạn</a>
                    </li>
                    <li>
                        <a href="#sec-goi" class="block px-3 py-3.5 hover:bg-white/10 transition">Gối</a>
                    </li>
                    <li>
                        <a href="#du-an-thi-cong" class="block px-3 py-3.5 hover:bg-white/10 transition">Dự Án Đà Nẵng</a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="block px-3 py-3.5 hover:bg-white/10 transition">Tin Tức</a>
                    </li>
                    <li>
                        <a href="#lien-he-map" class="block px-3 py-3.5 hover:bg-white/10 transition">Liên Hệ</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- ==========================================
         MENU TRƯỢT TRÊN ĐIỆN THOẠI (OFF-CANVAS MOBILE MENU)
    =========================================== -->
    <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-slate-900/60 z-50 hidden backdrop-blur-xs"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-[290px] max-w-[85vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="p-4 bg-primary text-white flex items-center justify-between">
            <div class="flex items-center gap-2">
                <img src="https://lh3.googleusercontent.com/d/1S3ovJm0_cQAApYDoNDZU19yCApAsddAE=w200" onerror="handleDriveImgError(this, '1S3ovJm0_cQAApYDoNDZU19yCApAsddAE', 'DM')" alt="Logo" class="w-9 h-9 rounded bg-white object-contain p-0.5">
                <div>
                    <p class="font-bold text-sm leading-tight">MÀN RÈM DIỆU MY</p>
                    <p class="text-[11px] text-amber-300">manremdieumy.com</p>
                </div>
            </div>
            <button type="button" onclick="toggleMobileMenu()" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center text-white">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>
        <div class="p-3 overflow-y-auto flex-1 divide-y divide-slate-100 text-sm font-semibold text-slate-700">
            <a href="#top" onclick="toggleMobileMenu()" class="flex items-center gap-3 py-2.5 px-2 text-primary">
                <i class="fa-solid fa-house w-5 text-center"></i> Trang Chủ
            </a>
            <div class="py-2">
                <p class="px-2 text-[11px] font-bold uppercase text-slate-400 mb-1">Danh Mục Rèm Cửa</p>
                <a href="#sec-rem-cua" onclick="filterRemCategory('all'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">• Tất Cả Rèm Cửa</a>
                <a href="#sec-rem-cua" onclick="filterRemCategory('rem-vai'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">• Rèm Vải 2 Lớp & Cản Sáng</a>
                <a href="#sec-rem-cua" onclick="filterRemCategory('rem-cau-vong'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">• Rèm Cầu Vồng Hàn Quốc</a>
                <a href="#sec-rem-cua" onclick="filterRemCategory('rem-cuon'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">• Rèm Cuốn Văn Phòng</a>
                <a href="#sec-rem-cua" onclick="filterRemCategory('rem-go'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">• Rèm Sáo Gỗ Tự Nhiên</a>
                <a href="#sec-rem-cua" onclick="filterRemCategory('rem-to-ong'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">• Rèm Tổ Ong & Vách Ngăn</a>
                <a href="#sec-rem-cua" onclick="filterRemCategory('rem-la-doc'); toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">• Rèm Lá Dọc & Rèm Nhôm</a>
            </div>
            <a href="#sec-cua-luoi" onclick="toggleMobileMenu()" class="flex items-center gap-3 py-2.5 px-2 hover:text-primary">
                <i class="fa-solid fa-shield-virus w-5 text-center text-primary"></i> Cửa Lưới Chống Muỗi
            </a>
            <a href="#sec-nem" onclick="toggleMobileMenu()" class="flex items-center gap-3 py-2.5 px-2 hover:text-primary">
                <i class="fa-solid fa-bed w-5 text-center text-primary"></i> Nệm Cao Su / Nệm Gấp 3
            </a>
            <a href="#sec-gian-phoi" onclick="toggleMobileMenu()" class="flex items-center gap-3 py-2.5 px-2 hover:text-primary">
                <i class="fa-solid fa-shirt w-5 text-center text-primary"></i> Giàn Phơi Thông Minh
            </a>
            <a href="#sec-chan-ga" onclick="toggleMobileMenu()" class="flex items-center gap-3 py-2.5 px-2 hover:text-primary">
                <i class="fa-solid fa-hotel w-5 text-center text-primary"></i> Chăn Ga Khách Sạn
            </a>
            <a href="#sec-goi" onclick="toggleMobileMenu()" class="flex items-center gap-3 py-2.5 px-2 hover:text-primary">
                <i class="fa-solid fa-cloud w-5 text-center text-primary"></i> Gối Cao Su & Lông Vũ
            </a>
            <a href="#du-an-thi-cong" onclick="toggleMobileMenu()" class="flex items-center gap-3 py-2.5 px-2 hover:text-primary">
                <i class="fa-solid fa-building-circle-check w-5 text-center text-amber-600"></i> Dự Án Thi Công Đà Nẵng
            </a>
            <a href="#bao-gia" onclick="toggleMobileMenu()" class="flex items-center gap-3 py-2.5 px-2 hover:text-primary">
                <i class="fa-solid fa-calculator w-5 text-center text-amber-600"></i> Yêu Cầu Báo Giá Nhanh
            </a>
            <a href="#tin-tuc" onclick="toggleMobileMenu()" class="flex items-center gap-3 py-2.5 px-2 hover:text-primary">
                <i class="fa-solid fa-newspaper w-5 text-center text-primary"></i> Bài Viết & Kinh Nghiệm
            </a>
            <a href="#lien-he-map" onclick="toggleMobileMenu()" class="flex items-center gap-3 py-2.5 px-2 hover:text-primary">
                <i class="fa-solid fa-map-location-dot w-5 text-center text-primary"></i> Bản Đồ & Fanpage
            </a>
        </div>
        <div class="p-3 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1">
            <p class="font-bold text-slate-800"><i class="fa-solid fa-location-dot text-saleRed mr-1"></i> 71 Âu Cơ, P. Liên Chiểu, Đà Nẵng</p>
            <p class="font-bold text-primary"><i class="fa-solid fa-phone mr-1"></i> 0899.922.221 - 0788.694.567</p>
        </div>
    </aside>

    <!-- ==========================================
         UX SECTION 1: 2 ẢNH BANNER THI CÔNG LẮP ĐẶT MÀN RÈM TỰ TRƯỢT
         (Kích thước chuyên nghiệp, tối ưu điện thoại, chữ không tràn viền)
    =========================================== -->
    <section id="top" class="py-3 sm:py-5 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="relative rounded-xl overflow-hidden shadow-md bg-slate-900">
                
                <!-- Khung chứa 2 Slide tự động trượt -->
                <div id="heroSliderWrapper" class="relative w-full min-h-[250px] sm:min-h-[360px] lg:min-h-[430px]">
                    
                    <!-- SLIDE 1: THI CÔNG LẮP ĐẶT MÀN RÈM ĐÀ NẴNG -->
                    <div class="hero-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10 flex items-center">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1Gg80R0yhC4ncnfdhW-_3RfNGqaE4xYIL=w1600" 
                            onerror="handleDriveImgError(this, '1Gg80R0yhC4ncnfdhW-_3RfNGqaE4xYIL', 'THI CONG MAN REM DIEU MY')"
                            alt="Banner Thi Công Lắp Đặt Màn Rèm Diệu My Đà Nẵng" 
                            class="
                                absolute inset-0 w-full h-full object-cover object-center
                            "
                        >
                        <!-- Lớp phủ giúp chữ sắc nét và không bao giờ tràn viền -->
                        <div class="absolute inset-0 bg-gradient-to-r from-slate-950/90 via-slate-900/75 to-slate-900/35"></div>

                        <div class="relative z-10 w-full px-4 py-6 sm:px-10 md:px-14 lg:px-16 max-w-3xl text-white">
                            <p class="text-amber-400 font-bold text-xs sm:text-sm uppercase tracking-wider mb-1.5 break-words">
                                MÀN RÈM DIỆU MY • MANREMDIEUMY.COM
                            </p>
                            <h1 class="text-lg sm:text-3xl lg:text-4xl font-extrabold leading-snug sm:leading-tight mb-2 sm:mb-3 break-words">
                                THI CÔNG &amp; LẮP ĐẶT MÀN RÈM CỬA UY TÍN TẠI ĐÀ NẴNG
                            </h1>
                            <p class="text-xs sm:text-base text-slate-200 leading-relaxed mb-4 sm:mb-6 max-w-2xl break-words">
                                Chuyên Rèm Vải 2 Lớp, Rèm Cầu Vồng Hàn Quốc, Rèm Cuốn, Rèm Gỗ, Cửa Lưới Chống Muỗi &amp; Chăn Ga Gối Nệm. Mang mẫu tư vấn, đo đạc miễn phí tận nhà!
                            </p>
                            <div class="flex flex-wrap items-center gap-2 sm:gap-3">
                                <a href="#bao-gia" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-extrabold text-xs sm:text-sm px-4 py-2.5 sm:px-6 sm:py-3 rounded-lg shadow transition">
                                    Đăng Ký Tư Vấn Tận Nơi
                                </a>
                                <a href="#sec-rem-cua" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm px-4 py-2.5 sm:px-5 sm:py-3 rounded-lg transition">
                                    Xem Mẫu Thực Tế
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- SLIDE 2: TỔNG KHO MÀN RÈM - CỬA LƯỚI - CHĂN GA GỐI NỆM -->
                    <div class="hero-slide absolute inset-0 transition-opacity duration-700 opacity-0 z-0 flex items-center">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1CcbK-jTlYbUG7SzSJMNae3pyCuBIfEn_=w1600" 
                            onerror="handleDriveImgError(this, '1CcbK-jTlYbUG7SzSJMNae3pyCuBIfEn_', 'CONG TRINH MAN REM DA NANG')"
                            alt="Banner Công Trình Lắp Đặt Màn Rèm Cửa Sổ Đà Nẵng" 
                            class="absolute inset-0 w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-primaryDark/95 via-primaryDark/80 to-slate-900/40"></div>

                        <div class="relative z-10 w-full px-4 py-6 sm:px-10 md:px-14 lg:px-16 max-w-3xl text-white">
                            <p class="text-amber-300 font-bold text-xs sm:text-sm uppercase tracking-wider mb-1.5 break-words">
                                GIẢI PHÁP NỘI THẤT TRỌN GÓI CHO GIA ĐÌNH &amp; KHÁCH SẠN
                            </p>
                            <h2 class="text-lg sm:text-3xl lg:text-4xl font-extrabold leading-snug sm:leading-tight mb-2 sm:mb-3 break-words">
                                ƯU ĐÃI GIẢM ĐẾN 35% KHI LẮP ĐẶT TRỌN GÓI MÀN RÈM
                            </h2>
                            <p class="text-xs sm:text-base text-slate-200 leading-relaxed mb-4 sm:mb-6 max-w-2xl break-words">
                                Địa chỉ: 71 Âu Cơ, Phường Liên Chiểu, Tp.Đà Nẵng. Cam kết vải rèm chính hãng cản nắng 100%, phụ kiện hợp kim siêu bền, bảo hành dài hạn chu đáo.
                            </p>
                            <div class="flex flex-wrap items-center gap-2 sm:gap-3">
                                <a href="#du-an-thi-cong" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-extrabold text-xs sm:text-sm px-4 py-2.5 sm:px-6 sm:py-3 rounded-lg shadow transition">
                                    Xem Dự Án Đã Thi Công
                                </a>
                                <a href="tel:0899922221" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm px-4 py-2.5 sm:px-5 sm:py-3 rounded-lg transition">
                                    Hotline: 0899.922.221
                                </a>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng Trước / Sau trên Banner -->
                <button type="button" onclick="prevBannerSlide()" aria-label="Slide trước" class="hidden sm:flex absolute left-3 top-1/2 -translate-y-1/2 z-20 w-9 h-9 rounded-full bg-black/40 hover:bg-black/70 text-white items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-sm"></i>
                </button>
                <button type="button" onclick="nextBannerSlide()" aria-label="Slide tiếp theo" class="hidden sm:flex absolute right-3 top-1/2 -translate-y-1/2 z-20 w-9 h-9 rounded-full bg-black/40 hover:bg-black/70 text-white items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-sm"></i>
                </button>

                <!-- Chấm tròn chỉ báo Slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToBannerSlide(0)" class="banner-dot w-6 h-2 rounded-full bg-amber-400 transition-all" aria-label="Banner 1"></button>
                    <button type="button" onclick="goToBannerSlide(1)" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ (CHUẨN MẪU HOANGKIMHOME)
         (Tối ưu trên cả máy tính 6 cột và điện thoại 3 cột, không tràn viền)
    =========================================== -->
    <section class="py-5 sm:py-7 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="text-base sm:text-xl">DANH MỤC SẢN PHẨM CHÍNH</h2>
                    <span class="text-xs text-slate-500 font-medium">Chọn nhanh danh mục bạn cần xem</span>
                </div>
            </div>

            <!-- 6 Danh mục lớn lấy từ web mẫu HoangKimHome -->
            <div class="grid grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-4">
                <a href="#sec-rem-cua" class="group bg-slate-50 hover:bg-primary hover:text-white rounded-xl p-3 sm:p-4 text-center border border-slate-200/80 transition shadow-2xs flex flex-col items-center justify-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full bg-primary/10 group-hover:bg-white/20 text-primary group-hover:text-amber-300 flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-person-booth text-xl sm:text-2xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm leading-snug break-words">Rèm Cửa</h3>
                    <p class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5 hidden sm:block">Vải, Cầu vồng, Cuốn, Gỗ</p>
                </a>

                <a href="#sec-cua-luoi" class="group bg-slate-50 hover:bg-primary hover:text-white rounded-xl p-3 sm:p-4 text-center border border-slate-200/80 transition shadow-2xs flex flex-col items-center justify-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full bg-primary/10 group-hover:bg-white/20 text-primary group-hover:text-amber-300 flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-shield-virus text-xl sm:text-2xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm leading-snug break-words">Cửa Chống Muỗi</h3>
                    <p class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5 hidden sm:block">Hệ xếp, Hệ lùa, Tự cuốn</p>
                </a>

                <a href="#sec-nem" class="group bg-slate-50 hover:bg-primary hover:text-white rounded-xl p-3 sm:p-4 text-center border border-slate-200/80 transition shadow-2xs flex flex-col items-center justify-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full bg-primary/10 group-hover:bg-white/20 text-primary group-hover:text-amber-300 flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-bed text-xl sm:text-2xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm leading-snug break-words">Nệm</h3>
                    <p class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5 hidden sm:block">Cao su, Foam, Nệm gấp 3</p>
                </a>

                <a href="#sec-gian-phoi" class="group bg-slate-50 hover:bg-primary hover:text-white rounded-xl p-3 sm:p-4 text-center border border-slate-200/80 transition shadow-2xs flex flex-col items-center justify-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full bg-primary/10 group-hover:bg-white/20 text-primary group-hover:text-amber-300 flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-shirt text-xl sm:text-2xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm leading-snug break-words">Giàn Phơi</h3>
                    <p class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5 hidden sm:block">Gắn trần, Xếp gắn tường</p>
                </a>

                <a href="#sec-chan-ga" class="group bg-slate-50 hover:bg-primary hover:text-white rounded-xl p-3 sm:p-4 text-center border border-slate-200/80 transition shadow-2xs flex flex-col items-center justify-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full bg-primary/10 group-hover:bg-white/20 text-primary group-hover:text-amber-300 flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-hotel text-xl sm:text-2xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm leading-snug break-words">Chăn Ga Khách Sạn</h3>
                    <p class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5 hidden sm:block">Trắng sọc T250, T300, T400</p>
                </a>

                <a href="#sec-goi" class="group bg-slate-50 hover:bg-primary hover:text-white rounded-xl p-3 sm:p-4 text-center border border-slate-200/80 transition shadow-2xs flex flex-col items-center justify-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full bg-primary/10 group-hover:bg-white/20 text-primary group-hover:text-amber-300 flex items-center justify-center mb-2 transition">
                        <i class="fa-solid fa-cloud text-xl sm:text-2xl"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm leading-snug break-words">Gối</h3>
                    <p class="text-[11px] text-slate-500 group-hover:text-slate-200 mt-0.5 hidden sm:block">Cao su thiên nhiên, Lông vũ</p>
                </a>
            </div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 3: DANH MỤC RÈM CỬA & 15 ẢNH SẢN PHẨM THỰC TẾ DIỆU MY
         (2 cột trên điện thoại, 4 cột trên máy tính, % giảm giá góc trên trái)
    =========================================== -->
    <section id="sec-rem-cua" class="py-6 sm:py-9">
        <div class="flatsome-container">
            
            <!-- Header Section Rèm Cửa -->
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="text-base sm:text-xl">RÈM CỬA – MẪU THỰC TẾ TẠI MÀN RÈM DIỆU MY</h2>
                    <a href="#bao-gia" class="text-xs sm:text-sm font-bold text-primary hover:text-amber-600 inline-flex items-center gap-1">
                        <span>Nhận báo giá theo kích thước cửa</span>
                        <i class="fa-solid fa-arrow-right"></i>
                    </a>
                </div>
            </div>

            <!-- 8 Danh mục con của Rèm Cửa giống hệt web mẫu HoangKimHome -->
            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-9 gap-2 mb-5">
                <button type="button" onclick="filterRemCategory('all')" data-cat="all" class="rem-filter-btn bg-primary text-white font-bold text-xs py-2.5 px-2 rounded-lg border border-primary transition text-center">
                    TẤT CẢ (15)
                </button>
                <button type="button" onclick="filterRemCategory('rem-vai')" data-cat="rem-vai" class="rem-filter-btn bg-white hover:bg-slate-100 text-slate-700 font-semibold text-xs py-2.5 px-2 rounded-lg border border-slate-200 transition text-center">
                    RÈM VẢI
                </button>
                <button type="button" onclick="filterRemCategory('rem-cuon')" data-cat="rem-cuon" class="rem-filter-btn bg-white hover:bg-slate-100 text-slate-700 font-semibold text-xs py-2.5 px-2 rounded-lg border border-slate-200 transition text-center">
                    RÈM CUỐN
                </button>
                <button type="button" onclick="filterRemCategory('rem-cau-vong')" data-cat="rem-cau-vong" class="rem-filter-btn bg-white hover:bg-slate-100 text-slate-700 font-semibold text-xs py-2.5 px-2 rounded-lg border border-slate-200 transition text-center">
                    CẦU VỒNG
                </button>
                <button type="button" onclick="filterRemCategory('rem-la-doc')" data-cat="rem-la-doc" class="rem-filter-btn bg-white hover:bg-slate-100 text-slate-700 font-semibold text-xs py-2.5 px-2 rounded-lg border border-slate-200 transition text-center">
                    LÁ DỌC
                </button>
                <button type="button" onclick="filterRemCategory('rem-go')" data-cat="rem-go" class="rem-filter-btn bg-white hover:bg-slate-100 text-slate-700 font-semibold text-xs py-2.5 px-2 rounded-lg border border-slate-200 transition text-center">
                    RÈM GỖ
                </button>
                <button type="button" onclick="filterRemCategory('rem-nhom')" data-cat="rem-nhom" class="rem-filter-btn bg-white hover:bg-slate-100 text-slate-700 font-semibold text-xs py-2.5 px-2 rounded-lg border border-slate-200 transition text-center">
                    RÈM NHÔM
                </button>
                <button type="button" onclick="filterRemCategory('rem-to-ong')" data-cat="rem-to-ong" class="rem-filter-btn bg-white hover:bg-slate-100 text-slate-700 font-semibold text-xs py-2.5 px-2 rounded-lg border border-slate-200 transition text-center">
                    TỔ ONG
                </button>
                <button type="button" onclick="filterRemCategory('thiet-bi')" data-cat="thiet-bi" class="rem-filter-btn bg-white hover:bg-slate-100 text-slate-700 font-semibold text-xs py-2.5 px-2 rounded-lg border border-slate-200 transition text-center col-span-2 sm:col-span-1">
                    THIẾT BỊ
                </button>
            </div>

            <!-- Lưới hiển thị 15 sản phẩm thực tế từ Google Drive (2 cột Mobile, 4 cột Desktop) -->
            <div id="remProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Được render tự động bằng JS từ mảng 15 file ảnh Google Drive thực tế -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 4: CỬA LƯỚI CHỐNG MUỖI (CHUẨN DANH MỤC WEB MẪU)
    =========================================== -->
    <section id="sec-cua-luoi" class="py-6 sm:py-8 bg-white border-t border-b border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="text-base sm:text-xl">CỬA LƯỚI CHỐNG MUỖI ĐÀ NẴNG</h2>
                    <a href="#bao-gia" class="text-xs sm:text-sm font-bold text-primary hover:text-amber-600">Xem tất cả &amp; Báo giá →</a>
                </div>
            </div>
            <div id="cuaLuoiGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5"></div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 5: NỆM (NỆM GẤP BA, HỖ TRỢ NỆM, NỆM CAO SU / FOAM)
    =========================================== -->
    <section id="sec-nem" class="py-6 sm:py-8">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="text-base sm:text-xl">NỆM CAO SU – NỆM FOAM – NỆM GẤP BA</h2>
                    <div class="flex flex-wrap gap-2 text-xs font-semibold text-slate-600">
                        <span class="px-2 py-1 bg-white rounded border border-slate-200">Nệm Gấp Ba</span>
                        <span class="px-2 py-1 bg-white rounded border border-slate-200">Hỗ Trợ Nệm</span>
                        <span class="px-2 py-1 bg-white rounded border border-slate-200">Nệm Cao Su / Foam</span>
                        <span class="px-2 py-1 bg-white rounded border border-slate-200">Cao Su Thiên Nhiên</span>
                    </div>
                </div>
            </div>
            <div id="nemGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5"></div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 6: GIÀN PHƠI THÔNG MINH
    =========================================== -->
    <section id="sec-gian-phoi" class="py-6 sm:py-8 bg-white border-t border-b border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="text-base sm:text-xl">GIÀN PHƠI THÔNG MINH GẮN TRẦN &amp; XẾP TƯỜNG</h2>
                    <a href="#bao-gia" class="text-xs sm:text-sm font-bold text-primary hover:text-amber-600">Tư vấn lắp đặt →</a>
                </div>
            </div>
            <div id="gianPhoiGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5"></div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 7: CHĂN GA KHÁCH SẠN & GIA ĐÌNH
    =========================================== -->
    <section id="sec-chan-ga" class="py-6 sm:py-8">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="text-base sm:text-xl">CHĂN GA KHÁCH SẠN &amp; GIA ĐÌNH</h2>
                    <a href="#bao-gia" class="text-xs sm:text-sm font-bold text-primary hover:text-amber-600">Nhận bảng giá sỉ khách sạn →</a>
                </div>
            </div>
            <div id="chanGaGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5"></div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 8: GỐI CAO SU, GỐI LÔNG VŨ, GỐI CHỨC NĂNG
    =========================================== -->
    <section id="sec-goi" class="py-6 sm:py-8 bg-white border-t border-b border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="text-base sm:text-xl">GỐI CAO SU – GỐI LÔNG VŨ – GỐI CHỨC NĂNG</h2>
                    <div class="flex flex-wrap gap-2 text-xs font-semibold text-slate-600">
                        <span class="px-2 py-1 bg-slate-50 rounded border border-slate-200">Gối Cao Su</span>
                        <span class="px-2 py-1 bg-slate-50 rounded border border-slate-200">Gối Lông Vũ</span>
                        <span class="px-2 py-1 bg-slate-50 rounded border border-slate-200">Gối Chức Năng</span>
                    </div>
                </div>
            </div>
            <div id="goiGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5"></div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 9: 9 DỰ ÁN THI CÔNG LẮP ĐẶT MÀN RÈM THỰC TẾ TẠI ĐÀ NẴNG
         (Lấy từ 9 link Google Drive dự án thực tế khách hàng cung cấp)
    =========================================== -->
    <section id="du-an-thi-cong" class="py-7 sm:py-10 bg-slate-100/80 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="text-base sm:text-xl">DỰ ÁN THI CÔNG LẮP ĐẶT MÀN RÈM TẠI ĐÀ NẴNG</h2>
                    <span class="text-xs sm:text-sm text-slate-600 font-medium">Hình ảnh thực tế 100% do đội ngũ Màn Rèm Diệu My thực hiện</span>
                </div>
            </div>

            <!-- Lưới 9 dự án thi công thực tế (2 cột trên điện thoại, 3 cột trên máy tính) -->
            <div id="projectGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                <!-- Được render bằng JS từ 9 file ảnh dự án thực tế -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 10: FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ
    =========================================== -->
    <section id="bao-gia" class="py-8 sm:py-11 bg-primary text-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-center">
                
                <!-- Cột thông tin cam kết bên trái -->
                <div class="lg:col-span-5 space-y-4">
                    <span class="inline-block bg-amber-500 text-slate-950 font-extrabold text-xs uppercase px-3 py-1 rounded">
                        BÁO GIÁ NHANH TRONG 5 PHÚT
                    </span>
                    <h2 class="text-xl sm:text-3xl font-extrabold leading-tight">
                        ĐĂNG KÝ NHẬN BÁO GIÁ &amp; MANG MẪU TƯ VẤN TẬN NHÀ MIỄN PHÍ
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                        Quý khách tại Đà Nẵng và khu vực lân cận chỉ cần để lại thông tin hoặc kích thước sơ bộ, kỹ thuật viên <strong>Màn Rèm Diệu My</strong> sẽ mang quyển mẫu vải rèm, mẫu cửa lưới đến tận công trình đo đạc và báo giá chi tiết hoàn toàn miễn phí.
                    </p>
                    <div class="space-y-2.5 pt-2 text-xs sm:text-sm">
                        <div class="flex items-start gap-3">
                            <i class="fa-solid fa-circle-check text-amber-400 mt-1"></i>
                            <span><strong>Địa chỉ xưởng &amp; Showroom:</strong> 71 Âu Cơ, Phường Liên Chiểu, Tp.Đà Nẵng</span>
                        </div>
                        <div class="flex items-start gap-3">
                            <i class="fa-solid fa-circle-check text-amber-400 mt-1"></i>
                            <span><strong>Hotline / Zalo tư vấn 24/7:</strong> 0899.922.221 – 0788.694.567</span>
                        </div>
                        <div class="flex items-start gap-3">
                            <i class="fa-solid fa-circle-check text-amber-400 mt-1"></i>
                            <span><strong>Cam kết:</strong> Giá gốc tại xưởng – Lắp đặt thẩm mỹ, sạch sẽ – Bảo hành uy tín dài hạn.</span>
                        </div>
                    </div>
                </div>

                <!-- Cột Form Yêu Cầu & Báo Giá bên phải -->
                <div class="lg:col-span-7">
                    <div class="bg-white text-slate-800 rounded-xl shadow-xl p-4 sm:p-6 md:p-7">
                        <h3 class="text-base sm:text-lg font-extrabold text-primary uppercase mb-1">
                            FORM YÊU CẦU TƯ VẤN &amp; BÁO GIÁ MÀN RÈM
                        </h3>
                        <p class="text-xs text-slate-500 mb-4">
                            Điền thông tin bên dưới để nhận bảng báo giá ưu đãi mới nhất từ Màn Rèm Diệu My
                        </p>

                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                                    <input type="text" id="quoteName" required placeholder="Ví dụ: Anh Minh / Chị Lan" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-primary focus:outline-none">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="quotePhone" required placeholder="Nhập SĐT để nhận báo giá" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-primary focus:outline-none">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần báo giá *</label>
                                    <select id="quoteService" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-primary focus:outline-none bg-white">
                                        <option value="Rèm Vải 2 Lớp / Rèm Vải Cản Sáng">Rèm Vải 2 Lớp / Rèm Vải Cản Sáng</option>
                                        <option value="Rèm Cầu Vồng Hàn Quốc">Rèm Cầu Vồng Hàn Quốc</option>
                                        <option value="Rèm Cuốn Văn Phòng / Rèm Sáo Gỗ">Rèm Cuốn Văn Phòng / Rèm Sáo Gỗ</option>
                                        <option value="Rèm Tổ Ong / Vách Ngăn Lạnh">Rèm Tổ Ong / Vách Ngăn Lạnh</option>
                                        <option value="Cửa Lưới Chống Muỗi Đà Nẵng">Cửa Lưới Chống Muỗi Đà Nẵng</option>
                                        <option value="Chăn Ga Gối Nệm Gia Đình & Khách Sạn">Chăn Ga Gối Nệm Gia Đình &amp; Khách Sạn</option>
                                        <option value="Giàn Phơi Thông Minh">Giàn Phơi Thông Minh</option>
                                        <option value="Thi Công Trọn Gói Nhà Phố / Căn Hộ">Thi Công Trọn Gói Nhà Phố / Căn Hộ</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ công trình tại Đà Nẵng</label>
                                    <input type="text" id="quoteAddress" placeholder="VD: Liên Chiểu, Hải Châu, Hòa Xuân..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-primary focus:outline-none">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Kích thước dự kiến / Yêu cầu chi tiết</label>
                                <textarea id="quoteNote" rows="3" placeholder="Nhập số lượng cửa, kích thước ước lượng hoặc thời gian muốn kỹ thuật mang mẫu đến tận nơi..." class="w-full px-3.5 py-2 text-sm rounded-lg border border-slate-300 focus:border-primary focus:outline-none"></textarea>
                            </div>

                            <div class="flex flex-col sm:flex-row items-stretch sm:items-center gap-2.5 pt-1">
                                <button type="submit" class="flex-1 bg-saleRed hover:bg-red-700 text-white font-extrabold text-sm py-3 px-5 rounded-lg shadow transition flex items-center justify-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i>
                                    <span>GỬI YÊU CẦU &amp; NHẬN BÁO GIÁ NGAY</span>
                                </button>
                                <a href="https://zalo.me/0899922221" target="_blank" rel="noopener" class="bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs sm:text-sm py-3 px-4 rounded-lg transition text-center flex items-center justify-center gap-1.5">
                                    <i class="fa-solid fa-comment-dots"></i>
                                    <span>Gửi Qua Zalo 0899.922.221</span>
                                </a>
                            </div>
                        </form>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 11: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC - KINH NGHIỆM)
    =========================================== -->
    <section id="tin-tuc" class="py-7 sm:py-10 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="text-base sm:text-xl">TIN TỨC – KINH NGHIỆM – BÁO GIÁ MÀN RÈM</h2>
                    <!-- Các tab danh mục bài viết chuẩn mẫu HoangKimHome -->
                    <div class="flex flex-wrap gap-1.5">
                        <button type="button" onclick="filterBlog('all')" data-blog="all" class="blog-tab-btn bg-primary text-white text-xs font-bold px-3 py-1.5 rounded">Tất Cả</button>
                        <button type="button" onclick="filterBlog('tin-rem')" data-blog="tin-rem" class="blog-tab-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded">Tin Tức Rèm Cửa</button>
                        <button type="button" onclick="filterBlog('tin-cua-luoi')" data-blog="tin-cua-luoi" class="blog-tab-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded">Tin Cửa Lưới Chống Muỗi</button>
                        <button type="button" onclick="filterBlog('tin-chan-ga')" data-blog="tin-chan-ga" class="blog-tab-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded">Tin Chăn Ga Gối Nệm</button>
                    </div>
                </div>
            </div>

            <div id="blogGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                <!-- Được render bằng JS -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 12: ĐƯA GOOGLE MAP VÀ FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
    =========================================== -->
    <section id="lien-he-map" class="py-7 sm:py-10 bg-slate-50 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="text-base sm:text-xl">BẢN ĐỒ ĐƯỜNG ĐI &amp; FANPAGE MÀN RÈM DIỆU MY</h2>
                    <span class="text-xs text-slate-500 font-medium">71 Âu Cơ, Phường Liên Chiểu, Tp.Đà Nẵng</span>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
                
                <!-- Cột Google Maps trực tiếp ngoài trang chủ (7/12 cột) -->
                <div class="lg:col-span-7 bg-white rounded-xl shadow-sm border border-slate-200 overflow-hidden flex flex-col">
                    <div class="p-3.5 sm:p-4 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
                        <div class="min-w-0">
                            <h3 class="font-extrabold text-sm sm:text-base text-primary flex items-center gap-2">
                                <i class="fa-solid fa-location-dot text-saleRed"></i>
                                <span>VỊ TRÍ GOOGLE MAPS: 71 ÂU CƠ, LIÊN CHIỂU, ĐÀ NẴNG</span>
                            </h3>
                            <p class="text-xs text-slate-500 mt-0.5">Màn Rèm Diệu My – Mở cửa: 07:30 - 21:00 tất cả các ngày trong tuần</p>
                        </div>
                        <a 
                            href="https://maps.app.goo.gl/cWTEd5tFcBXQV7EBA" 
                            target="_blank" 
                            rel="noopener" 
                            class="bg-primary hover:bg-primaryDark text-white text-xs font-bold px-3.5 py-2 rounded-lg transition inline-flex items-center gap-1.5 shrink-0"
                        >
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span>Mở Bản Đồ Lớn</span>
                        </a>
                    </div>

                    <!-- Bản đồ Google Map nhúng trực tiếp ngoài trang chủ -->
                    <div class="relative w-full h-[290px] sm:h-[340px] bg-slate-100 flex-1">
                        <iframe 
                            title="Bản đồ Màn Rèm Diệu My 71 Âu Cơ Liên Chiểu Đà Nẵng"
                            src="https://maps.google.com/maps?q=71%20%C3%82u%20C%C6%A1,%20Li%C3%AAn%20Chi%E1%BB%83u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-full border-0" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>

                    <div class="p-3 bg-slate-50 border-t border-slate-200 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600">
                        <span><i class="fa-solid fa-map-pin text-saleRed mr-1"></i> <strong>Địa chỉ:</strong> 71 Âu Cơ, Phường Liên Chiểu, Tp.Đà Nẵng</span>
                        <a href="https://maps.app.goo.gl/cWTEd5tFcBXQV7EBA" target="_blank" rel="noopener" class="text-primary font-bold hover:underline">
                            Link Google Map: maps.app.goo.gl/cWTEd5tFcBXQV7EBA
                        </a>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook trực tiếp ngoài trang chủ (5/12 cột) -->
                <div class="lg:col-span-5 bg-white rounded-xl shadow-sm border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="p-3.5 sm:p-4 border-b border-slate-100 flex items-center justify-between gap-2">
                            <h3 class="font-extrabold text-sm sm:text-base text-primary flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                                <span>FANPAGE FACEBOOK CHÍNH THỨC</span>
                            </h3>
                            <a href="https://www.facebook.com/manremcuasodanang" target="_blank" rel="noopener" class="text-xs font-bold text-blue-600 hover:underline">
                                Theo dõi trang →
                            </a>
                        </div>

                        <!-- Thẻ giao diện Fanpage trực quan + Plugin Facebook -->
                        <div class="p-4">
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50">
                                <!-- Ảnh bìa Fanpage -->
                                <div class="relative h-28 sm:h-32 bg-primaryDark overflow-hidden">
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1E6uN6ClhHistK_QMzGkmfcKWc_j0NhN-=w800" 
                                        onerror="handleDriveImgError(this, '1E6uN6ClhHistK_QMzGkmfcKWc_j0NhN-', 'FANPAGE MAN REM DIEU MY')"
                                        alt="Ảnh bìa Fanpage Màn Rèm Diệu My" 
                                        class="w-full h-full object-cover opacity-75"
                                    >
                                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                    <div class="absolute bottom-3 left-3 right-3 flex items-end gap-3">
                                        <img 
                                            src="https://lh3.googleusercontent.com/d/1S3ovJm0_cQAApYDoNDZU19yCApAsddAE=w200" 
                                            onerror="handleDriveImgError(this, '1S3ovJm0_cQAApYDoNDZU19yCApAsddAE', 'DM')"
                                            alt="Logo Fanpage Màn Rèm Diệu My" 
                                            class="w-14 h-14 rounded-lg border-2 border-white bg-white object-contain p-0.5 shadow-md shrink-0"
                                        >
                                        <div class="text-white min-w-0">
                                            <a href="https://www.facebook.com/manremcuasodanang" target="_blank" rel="noopener" class="font-extrabold text-sm sm:text-base hover:underline block truncate">
                                                Màn Rèm Diệu My - Đà Nẵng
                                            </a>
                                            <p class="text-[11px] text-slate-200 truncate">@manremcuasodanang • Sản phẩm/Dịch vụ</p>
                                        </div>
                                    </div>
                                </div>

                                <!-- Thông tin Fanpage -->
                                <div class="p-3.5 space-y-2.5 text-xs text-slate-700">
                                    <p class="leading-relaxed">
                                        <strong>Màn Rèm Diệu My - Sắc màu cuộc sống:</strong> Chuyên may đo, thi công lắp đặt Màn Rèm Cửa Sổ, Cửa Lưới Chống Muỗi, Chăn Ga Gối Đệm uy tín giá xưởng tại Đà Nẵng.
                                    </p>
                                    <div class="grid grid-cols-3 gap-1.5 pt-1">
                                        <img src="https://lh3.googleusercontent.com/d/1T1eyMIlEwWrmX0e21ES69bRT9pzy4yxD=w300" onerror="handleDriveImgError(this, '1T1eyMIlEwWrmX0e21ES69bRT9pzy4yxD', 'REM 1')" alt="Ảnh fanpage 1" class="h-16 w-full object-cover rounded">
                                        <img src="https://lh3.googleusercontent.com/d/103_ukTv2lylbLYosshiQhajIRyEFlitN=w300" onerror="handleDriveImgError(this, '103_ukTv2lylbLYosshiQhajIRyEFlitN', 'REM 2')" alt="Ảnh fanpage 2" class="h-16 w-full object-cover rounded">
                                        <img src="https://lh3.googleusercontent.com/d/1XquGWERg7ssFKlO7TvG9GjOgImGlH-Xv=w300" onerror="handleDriveImgError(this, '1XquGWERg7ssFKlO7TvG9GjOgImGlH-Xv', 'REM 3')" alt="Ảnh fanpage 3" class="h-16 w-full object-cover rounded">
                                    </div>
                                    <div class="flex flex-wrap gap-2 pt-2">
                                        <a href="https://www.facebook.com/manremcuasodanang" target="_blank" rel="noopener" class="flex-1 bg-blue-600 hover:bg-blue-700 text-white font-bold py-2.5 px-3 rounded-lg text-center inline-flex items-center justify-center gap-1.5 transition">
                                            <i class="fa-brands fa-facebook"></i>
                                            <span>Truy Cập Fanpage</span>
                                        </a>
                                        <a href="https://www.facebook.com/manremcuasodanang" target="_blank" rel="noopener" class="flex-1 bg-slate-200 hover:bg-slate-300 text-slate-800 font-bold py-2.5 px-3 rounded-lg text-center inline-flex items-center justify-center gap-1.5 transition">
                                            <i class="fa-brands fa-facebook-messenger text-blue-600"></i>
                                            <span>Nhắn Tin Tư Vấn</span>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="p-3 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 flex items-center justify-between">
                        <span><i class="fa-brands fa-facebook text-blue-600 mr-1"></i> facebook.com/manremcuasodanang</span>
                        <span class="font-bold text-primary">0899.922.221</span>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         UX SECTION 13: PHƯƠNG CHÂM HOẠT ĐỘNG (GIỐNG WEB MẪU HOANGKIMHOME)
    =========================================== -->
    <section class="py-6 sm:py-8 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200/80 text-center">
                    <i class="fa-solid fa-tags text-2xl text-amber-600 mb-2"></i>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800">Giá Tốt Nhất Thị Trường</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">May đo trực tiếp tại xưởng</p>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200/80 text-center">
                    <i class="fa-solid fa-certificate text-2xl text-amber-600 mb-2"></i>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800">Sản Phẩm Chính Hãng</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">Chất liệu cao cấp, bền đẹp</p>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200/80 text-center">
                    <i class="fa-solid fa-headset text-2xl text-amber-600 mb-2"></i>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800">Tư Vấn Tận Nơi</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">Mang mẫu miễn phí tại Đà Nẵng</p>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200/80 text-center">
                    <i class="fa-solid fa-screwdriver-wrench text-2xl text-amber-600 mb-2"></i>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800">Thi Công Nhanh Chuẩn</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">Lắp đặt gọn gàng, sạch sẽ</p>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200/80 text-center col-span-2 sm:col-span-1">
                    <i class="fa-solid fa-shield-halved text-2xl text-amber-600 mb-2"></i>
                    <h3 class="font-bold text-xs sm:text-sm text-slate-800">Bảo Hành Đúng Quy Định</h3>
                    <p class="text-[11px] text-slate-500 mt-0.5">Hỗ trợ bảo trì trọn đời</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME
    =========================================== -->
    <footer class="bg-slate-900 text-slate-300 pt-10 pb-24 sm:pb-10 text-xs sm:text-sm">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-slate-800">
                
                <!-- Thông tin Màn Rèm Diệu My -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-3">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1S3ovJm0_cQAApYDoNDZU19yCApAsddAE=w200" 
                            onerror="handleDriveImgError(this, '1S3ovJm0_cQAApYDoNDZU19yCApAsddAE', 'DM')"
                            alt="Logo Màn Rèm Diệu My" 
                            class="w-12 h-12 rounded-lg bg-white object-contain p-0.5"
                        >
                        <div>
                            <h3 class="font-extrabold text-white text-base sm:text-lg">MÀN RÈM DIỆU MY ĐÀ NẴNG</h3>
                            <p class="text-xs text-amber-400">Website: manremdieumy.com</p>
                        </div>
                    </div>
                    <p class="text-slate-400 leading-relaxed text-xs sm:text-sm">
                        Chuyên tư vấn, thiết kế, thi công lắp đặt Màn Rèm Cửa, Cửa Lưới Chống Muỗi, Chăn Ga Gối Nệm, Giàn Phơi Thông Minh cho gia đình, căn hộ, văn phòng, khách sạn và công trình tại Đà Nẵng.
                    </p>
                    <ul class="space-y-1.5 text-xs sm:text-sm">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i> <strong>Địa chỉ:</strong> 71 Âu Cơ, Phường Liên Chiểu, Tp.Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 w-5"></i> <strong>Điện thoại / Zalo:</strong> <a href="tel:0899922221" class="text-white font-bold hover:text-amber-300">0899.922.221</a> – <a href="tel:0788694567" class="text-white font-bold hover:text-amber-300">0788.694.567</a></li>
                        <li><i class="fa-brands fa-facebook text-amber-400 w-5"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/manremcuasodanang" target="_blank" rel="noopener" class="hover:text-amber-300 break-all">facebook.com/manremcuasodanang</a></li>
                        <li><i class="fa-solid fa-map text-amber-400 w-5"></i> <strong>Google Map:</strong> <a href="https://maps.app.goo.gl/cWTEd5tFcBXQV7EBA" target="_blank" rel="noopener" class="hover:text-amber-300">Xem vị trí cửa hàng</a></li>
                    </ul>
                </div>

                <!-- Danh mục sản phẩm -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="font-extrabold text-white uppercase text-sm tracking-wide border-b border-slate-800 pb-2">
                        DANH MỤC SẢN PHẨM
                    </h4>
                    <div class="grid grid-cols-2 gap-2 text-xs text-slate-400">
                        <a href="#sec-rem-cua" class="hover:text-amber-400">▸ Rèm Vải 2 Lớp Đà Nẵng</a>
                        <a href="#sec-rem-cua" class="hover:text-amber-400">▸ Rèm Cầu Vồng Hàn Quốc</a>
                        <a href="#sec-rem-cua" class="hover:text-amber-400">▸ Rèm Cuốn Cản Sáng 100%</a>
                        <a href="#sec-rem-cua" class="hover:text-amber-400">▸ Rèm Sáo Gỗ Tự Nhiên</a>
                        <a href="#sec-rem-cua" class="hover:text-amber-400">▸ Rèm Tổ Ong Vách Ngăn</a>
                        <a href="#sec-rem-cua" class="hover:text-amber-400">▸ Rèm Lá Dọc Văn Phòng</a>
                        <a href="#sec-cua-luoi" class="hover:text-amber-400">▸ Cửa Lưới Chống Muỗi</a>
                        <a href="#sec-nem" class="hover:text-amber-400">▸ Nệm Cao Su &amp; Nệm Gấp 3</a>
                        <a href="#sec-gian-phoi" class="hover:text-amber-400">▸ Giàn Phơi Thông Minh</a>
                        <a href="#sec-chan-ga" class="hover:text-amber-400">▸ Chăn Ga Gối Khách Sạn</a>
                    </div>
                </div>

                <!-- Hỗ trợ khách hàng -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="font-extrabold text-white uppercase text-sm tracking-wide border-b border-slate-800 pb-2">
                        HỖ TRỢ KHÁCH HÀNG
                    </h4>
                    <ul class="space-y-2 text-xs text-slate-400">
                        <li><a href="#bao-gia" class="hover:text-amber-400">▸ Quy trình đo đạc &amp; báo giá tận nhà</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-400">▸ Chính sách lắp đặt &amp; giao hàng</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-400">▸ Chính sách bảo hành sản phẩm</a></li>
                        <li><a href="#du-an-thi-cong" class="hover:text-amber-400">▸ Công trình tiêu biểu tại Đà Nẵng</a></li>
                        <li><a href="#lien-he-map" class="hover:text-amber-400">▸ Chỉ đường đến 71 Âu Cơ, Đà Nẵng</a></li>
                    </ul>
                </div>

            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-500">
                <p>© Bản quyền thuộc về <strong class="text-slate-300">Màn Rèm Diệu My (manremdieumy.com)</strong> – 71 Âu Cơ, Liên Chiểu, Đà Nẵng.</p>
                <p>Thiết kế chuẩn giao diện Flatsome UX Builder</p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
    =========================================== -->
    <div class="fixed left-3 bottom-4 z-40 flex flex-col gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a 
            href="https://zalo.me/0899922221" 
            target="_blank" 
            rel="noopener" 
            aria-label="Chat Zalo 0899.922.221"
            class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs px-3 py-2.5 rounded-full shadow-lg transition"
        >
            <span class="w-7 h-7 rounded-full bg-white text-blue-600 font-black flex items-center justify-center text-[11px] shrink-0">Zalo</span>
            <span class="pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a 
            href="https://www.facebook.com/manremcuasodanang" 
            target="_blank" 
            rel="noopener" 
            aria-label="Fanpage Màn Rèm Diệu My"
            class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white font-bold text-xs px-3 py-2.5 rounded-full shadow-lg transition"
        >
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center text-sm shrink-0">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="pr-1">Fanpage</span>
        </a>

        <!-- Nút Hotline 1 nổi bật -->
        <a 
            href="tel:0899922221" 
            aria-label="Gọi 0899.922.221"
            class="pulse-btn flex items-center gap-2 bg-saleRed hover:bg-red-700 text-white font-extrabold text-xs px-3 py-2.5 rounded-full shadow-lg transition"
        >
            <span class="w-7 h-7 rounded-full bg-white text-saleRed flex items-center justify-center text-xs shrink-0">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <span class="pr-1">0899.922.221</span>
        </a>

        <!-- Nút Hotline 2 nổi bật -->
        <a 
            href="tel:0788694567" 
            aria-label="Gọi 0788.694.567"
            class="flex items-center gap-2 bg-amber-600 hover:bg-amber-700 text-white font-extrabold text-xs px-3 py-2 rounded-full shadow-lg transition"
        >
            <span class="w-6 h-6 rounded-full bg-white text-amber-600 flex items-center justify-center text-xs shrink-0">
                <i class="fa-solid fa-phone"></i>
            </span>
            <span class="pr-1">0788.694.567</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM CHI TIẾT SẢN PHẨM / ẢNH THỰC TẾ / BÀI VIẾT
    =========================================== -->
    <div id="detailModal" class="fixed inset-0 bg-slate-900/75 z-50 hidden items-center justify-center p-3 sm:p-5 backdrop-blur-xs">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="p-4 border-b border-slate-100 flex items-center justify-between sticky top-0 bg-white z-10">
                <h3 id="modalTitle" class="font-extrabold text-primary text-sm sm:text-base pr-4 break-words">Chi tiết sản phẩm</h3>
                <button type="button" onclick="closeDetailModal()" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="modalBody" class="p-4 sm:p-5 space-y-4"></div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU & TƯƠNG TÁC
    =========================================== -->
    <script>
        /* Hàm dự phòng tự động khi load ảnh Google Drive */
        function handleDriveImgError(imgEl, fileId, fallbackLabel) {
            const currentAttempt = parseInt(imgEl.getAttribute('data-attempt') || '0', 10);
            if (currentAttempt === 0) {
                imgEl.setAttribute('data-attempt', '1');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
            } else if (currentAttempt === 1) {
                imgEl.setAttribute('data-attempt', '2');
                imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                imgEl.onerror = null;
                imgEl.src = 'https://placehold.co/600x600/0f4c81/ffffff?text=' + encodeURIComponent(fallbackLabel || 'Man Rem Dieu My');
            }
        }

        /* 15 ẢNH SẢN PHẨM THỰC TẾ TỪ GOOGLE DRIVE ĐƯỢC PHÂN LOẠI VÀO ĐÚNG DANH MỤC RÈM CỬA */
        const remRealProducts = [
            {
                id: 'rem-1',
                driveId: '1T1eyMIlEwWrmX0e21ES69bRT9pzy4yxD',
                name: 'Rèm Vải 2 Lớp Cao Cấp Phòng Khách Đẹp Sang Trọng – Mẫu Thực Tế 01',
                category: 'rem-vai',
                categoryLabel: 'Rèm Vải',
                oldPrice: '980.000 ₫',
                newPrice: '850.000 ₫',
                discount: '-13%',
                unit: 'mét ngang hoàn thiện'
            },
            {
                id: 'rem-2',
                driveId: '103_ukTv2lylbLYosshiQhajIRyEFlitN',
                name: 'Rèm Vải Chống Nắng Cản Sáng 100% Tone Xám Hiện Đại – Mẫu Thực Tế 02',
                category: 'rem-vai',
                categoryLabel: 'Rèm Vải',
                oldPrice: '750.000 ₫',
                newPrice: '620.000 ₫',
                discount: '-17%',
                unit: 'mét ngang hoàn thiện'
            },
            {
                id: 'rem-3',
                driveId: '1XquGWERg7ssFKlO7TvG9GjOgImGlH-Xv',
                name: 'Rèm Vải Voan Thêu Kết Hợp Vải Bố Dày Cao Cấp – Mẫu Thực Tế 03',
                category: 'rem-vai',
                categoryLabel: 'Rèm Vải',
                oldPrice: '1.050.000 ₫',
                newPrice: '890.000 ₫',
                discount: '-15%',
                unit: 'mét ngang hoàn thiện'
            },
            {
                id: 'rem-4',
                driveId: '1NX4G0AXRlon4O8WKZltdXxkgd7jPoR3P',
                name: 'Rèm Cầu Vồng Hàn Quốc Cản Sáng Phòng Ngủ & Phòng Khách – Mẫu 04',
                category: 'rem-cau-vong',
                categoryLabel: 'Rèm Cầu Vồng',
                oldPrice: '550.000 ₫',
                newPrice: '390.000 ₫',
                discount: '-29%',
                unit: 'm² hoàn thiện'
            },
            {
                id: 'rem-5',
                driveId: '1uSeFp62Oyeaf0J6jSdiKYny3eZ8sp6kF',
                name: 'Rèm Cầu Vồng Hãng Star Basic Chống Nắng Cửa Sổ – Mẫu Thực Tế 05',
                category: 'rem-cau-vong',
                categoryLabel: 'Rèm Cầu Vồng',
                oldPrice: '620.000 ₫',
                newPrice: '430.000 ₫',
                discount: '-31%',
                unit: 'm² hoàn thiện'
            },
            {
                id: 'rem-6',
                driveId: '1PAwVocZM-6YqZBU51fdJJ8rGjvuOSWSj',
                name: 'Rèm Cầu Vồng Hàn Quốc Wood Look Sang Trọng – Mẫu Thực Tế 06',
                category: 'rem-cau-vong',
                categoryLabel: 'Rèm Cầu Vồng',
                oldPrice: '680.000 ₫',
                newPrice: '480.000 ₫',
                discount: '-29%',
                unit: 'm² hoàn thiện'
            },
            {
                id: 'rem-7',
                driveId: '1KQ-Y7Xz54YVzkF254tpK2SAmR9ZNhKod',
                name: 'Rèm Cuốn Trơn Cản Sáng 100% Chống Nắng Cách Nhiệt – Mẫu Thực Tế 07',
                category: 'rem-cuon',
                categoryLabel: 'Rèm Cuốn',
                oldPrice: '360.000 ₫',
                newPrice: '295.000 ₫',
                discount: '-18%',
                unit: 'm² hoàn thiện'
            },
            {
                id: 'rem-8',
                driveId: '1eKlktHuNntZ38DM1Dobuf-Fcp0EG2UEy',
                name: 'Rèm Cuốn Lưới Văn Phòng & Quán Cafe Hiện Đại – Mẫu Thực Tế 08',
                category: 'rem-cuon',
                categoryLabel: 'Rèm Cuốn',
                oldPrice: '390.000 ₫',
                newPrice: '330.000 ₫',
                discount: '-15%',
                unit: 'm² hoàn thiện'
            },
            {
                id: 'rem-9',
                driveId: '1ET3T3RJRHK5dTBCOyaTKqUQhNjHKNK54',
                name: 'Rèm Sáo Gỗ Tự Nhiên Bản 5cm Chống Cong Vênh – Mẫu Thực Tế 09',
                category: 'rem-go',
                categoryLabel: 'Rèm Gỗ',
                oldPrice: '1.000.000 ₫',
                newPrice: '810.000 ₫',
                discount: '-19%',
                unit: 'm² hoàn thiện'
            },
            {
                id: 'rem-10',
                driveId: '1HZ3bPRZbIsepfnu8FbdgwR2_G7HJhM0X',
                name: 'Rèm Gỗ Tự Nhiên Cao Cấp Cho Phòng Khách & Phòng Thờ – Mẫu 10',
                category: 'rem-go',
                categoryLabel: 'Rèm Gỗ',
                oldPrice: '1.100.000 ₫',
                newPrice: '860.000 ₫',
                discount: '-22%',
                unit: 'm² hoàn thiện'
            },
            {
                id: 'rem-11',
                driveId: '1fOnUstdZPdij5Shhz15b7B5KJ5LkPPQd',
                name: 'Rèm Lá Dọc Văn Phòng Cản Nắng Xoay Lật 180 Độ – Mẫu Thực Tế 11',
                category: 'rem-la-doc',
                categoryLabel: 'Rèm Lá Dọc',
                oldPrice: '420.000 ₫',
                newPrice: '320.000 ₫',
                discount: '-24%',
                unit: 'm² hoàn thiện'
            },
            {
                id: 'rem-12',
                driveId: '10oK9G4BPGtNnaRKxKovVAnkQ3m66yF_C',
                name: 'Rèm Sáo Nhôm Cửa Sổ Chống Nước Sơn Tĩnh Điện – Mẫu Thực Tế 12',
                category: 'rem-nhom',
                categoryLabel: 'Rèm Nhôm',
                oldPrice: '380.000 ₫',
                newPrice: '310.000 ₫',
                discount: '-18%',
                unit: 'm² hoàn thiện'
            },
            {
                id: 'rem-13',
                driveId: '10xlr4VYLhgRMUE8-LVMGu7MK7yp9Txbu',
                name: 'Rèm Tổ Ong Cách Nhiệt Ngăn Phòng Điều Hòa – Mẫu Thực Tế 13',
                category: 'rem-to-ong',
                categoryLabel: 'Rèm Tổ Ong',
                oldPrice: '980.000 ₫',
                newPrice: '790.000 ₫',
                discount: '-19%',
                unit: 'm² hoàn thiện'
            },
            {
                id: 'rem-14',
                driveId: '17rFvaMwvRtavWVKbSXIij4fuC8DxXO7s',
                name: 'Rèm Vải Âm Trần Thông Tầng Căn Hộ & Biệt Thự Đà Nẵng – Mẫu 14',
                category: 'rem-vai',
                categoryLabel: 'Rèm Vải',
                oldPrice: '1.150.000 ₫',
                newPrice: '920.000 ₫',
                discount: '-20%',
                unit: 'mét ngang hoàn thiện'
            },
            {
                id: 'rem-15',
                driveId: '1VLPNvyupTjdZyNDKGampUpAn46iYEY6p',
                name: 'Động Cơ Rèm Tự Động Thông Minh & Phụ Kiện Thanh Ray Hợp Kim – Mẫu 15',
                category: 'thiet-bi',
                categoryLabel: 'Thiết Bị Đi Kèm',
                oldPrice: '3.000.000 ₫',
                newPrice: '2.450.000 ₫',
                discount: '-18%',
                unit: 'bộ hoàn thiện'
            }
        ];

        /* DỮ LIỆU CÁC DANH MỤC TỪ WEB MẪU HOANGKIMHOME.COM */
        const cuaLuoiProducts = [
            {
                name: 'Cửa Lưới Chống Muỗi Hệ Xếp 2 Cánh Cao Cấp Đà Nẵng',
                driveId: '10xlr4VYLhgRMUE8-LVMGu7MK7yp9Txbu',
                oldPrice: '800.000 ₫',
                newPrice: '550.000 ₫',
                discount: '-31%'
            },
            {
                name: 'Cửa Lưới Chống Muỗi Hệ Xếp 1 Cánh Khung Nhôm Xingfa',
                driveId: '10oK9G4BPGtNnaRKxKovVAnkQ3m66yF_C',
                oldPrice: '750.000 ₫',
                newPrice: '550.000 ₫',
                discount: '-27%'
            },
            {
                name: 'Cửa Lưới Chống Muỗi Kết Hợp Rèm Tổ Ong 2 Trong 1',
                driveId: '17rFvaMwvRtavWVKbSXIij4fuC8DxXO7s',
                oldPrice: '1.050.000 ₫',
                newPrice: '900.000 ₫',
                discount: '-14%'
            },
            {
                name: 'Cửa Lưới Chống Muỗi Hệ Tự Cuốn & Hệ Lùa Inox 304',
                driveId: '1fOnUstdZPdij5Shhz15b7B5KJ5LkPPQd',
                oldPrice: '790.000 ₫',
                newPrice: '690.000 ₫',
                discount: '-13%'
            }
        ];

        const nemProducts = [
            {
                name: 'Nệm Cao Su Thiên Nhiên Latex Đàn Hồi Cao Cấp',
                driveId: '1T1eyMIlEwWrmX0e21ES69bRT9pzy4yxD',
                oldPrice: '6.800.000 ₫',
                newPrice: '4.620.000 ₫',
                discount: '-32%'
            },
            {
                name: 'Nệm Cao Cấp Memory Foam Êm Ái Thoáng Khí',
                driveId: '103_ukTv2lylbLYosshiQhajIRyEFlitN',
                oldPrice: '4.800.000 ₫',
                newPrice: '3.400.000 ₫',
                discount: '-29%'
            },
            {
                name: 'Nệm Bông Ép Gấp 3 Vỏ Gấm Cao Cấp Giá Rẻ Đà Nẵng',
                driveId: '1XquGWERg7ssFKlO7TvG9GjOgImGlH-Xv',
                oldPrice: '2.200.000 ₫',
                newPrice: '1.650.000 ₫',
                discount: '-25%'
            },
            {
                name: 'Topper Hỗ Trợ Nệm Êm Ái Chuẩn Khách Sạn 5 Sao',
                driveId: '1VLPNvyupTjdZyNDKGampUpAn46iYEY6p',
                oldPrice: '1.250.000 ₫',
                newPrice: '890.000 ₫',
                discount: '-29%'
            }
        ];

        const gianPhoiProducts = [
            {
                name: 'Giàn Phơi Thông Minh Gắn Trần Quay Tay Tải Trọng 60Kg',
                driveId: '1PAwVocZM-6YqZBU51fdJJ8rGjvuOSWSj',
                oldPrice: '1.650.000 ₫',
                newPrice: '1.250.000 ₫',
                discount: '-24%'
            },
            {
                name: 'Giàn Phơi Thông Minh GT01 Gắn Tường Xếp Gọn Cho Nhà Phố',
                driveId: '1KQ-Y7Xz54YVzkF254tpK2SAmR9ZNhKod',
                oldPrice: '1.450.000 ₫',
                newPrice: '950.000 ₫',
                discount: '-34%'
            },
            {
                name: 'Giàn Phơi Thông Minh GT03 Xếp Tường Inox/Nhôm Chịu Tải Cao',
                driveId: '1eKlktHuNntZ38DM1Dobuf-Fcp0EG2UEy',
                oldPrice: '1.750.000 ₫',
                newPrice: '1.350.000 ₫',
                discount: '-23%'
            },
            {
                name: 'Giàn Phơi Thông Minh Điện Tử Điều Khiển Từ Xa Cao Cấp',
                driveId: '1ET3T3RJRHK5dTBCOyaTKqUQhNjHKNK54',
                oldPrice: '4.500.000 ₫',
                newPrice: '3.600.000 ₫',
                discount: '-20%'
            }
        ];

        const chanGaProducts = [
            {
                name: 'Bộ Chăn Ga Khách Sạn T300 Trắng Sọc 100% Cotton Cao Cấp',
                driveId: '1HZ3bPRZbIsepfnu8FbdgwR2_G7HJhM0X',
                oldPrice: '1.600.000 ₫',
                newPrice: '1.200.000 ₫',
                discount: '-25%'
            },
            {
                name: 'Bộ Chăn Ga Khách Sạn T300 Trắng Trơn Mềm Mịn Sang Trọng',
                driveId: '1NX4G0AXRlon4O8WKZltdXxkgd7jPoR3P',
                oldPrice: '1.425.000 ₫',
                newPrice: '1.150.000 ₫',
                discount: '-19%'
            },
            {
                name: 'Bộ Chăn Ga Khách Sạn T250 Trắng Sọc Bền Đẹp Dễ Giặt Ủi',
                driveId: '1uSeFp62Oyeaf0J6jSdiKYny3eZ8sp6kF',
                oldPrice: '1.200.000 ₫',
                newPrice: '950.000 ₫',
                discount: '-21%'
            },
            {
                name: 'Ruột Chăn Khách Sạn Chần Bông Microfiber Nguyên Tấm',
                driveId: '1T1eyMIlEwWrmX0e21ES69bRT9pzy4yxD',
                oldPrice: '560.000 ₫',
                newPrice: '390.000 ₫',
                discount: '-30%'
            }
        ];

        const goiProducts = [
            {
                name: 'Gối 100% Cao Su Thiên Nhiên Dáng Lượn Sóng Nâng Đỡ Cổ Vai Gáy',
                driveId: '103_ukTv2lylbLYosshiQhajIRyEFlitN',
                oldPrice: '650.000 ₫',
                newPrice: '520.000 ₫',
                discount: '-20%'
            },
            {
                name: 'Gối 100% Cao Su Thiên Nhiên Dáng Oval Êm Ái Thoáng Khí',
                driveId: '1XquGWERg7ssFKlO7TvG9GjOgImGlH-Xv',
                oldPrice: '650.000 ₫',
                newPrice: '520.000 ₫',
                discount: '-20%'
            },
            {
                name: 'Gối Lông Vũ Nhân Tạo Microfiber Khách Sạn 5 Sao Cao Cấp',
                driveId: '17rFvaMwvRtavWVKbSXIij4fuC8DxXO7s',
                oldPrice: '480.000 ₫',
                newPrice: '290.000 ₫',
                discount: '-40%'
            },
            {
                name: 'Gối Ôm Gòn Cao Cấp & Gối Công Thái Học Chống Đau Mỏi Cổ',
                driveId: '1VLPNvyupTjdZyNDKGampUpAn46iYEY6p',
                oldPrice: '360.000 ₫',
                newPrice: '180.000 ₫',
                discount: '-50%'
            }
        ];

        /* 9 DỰ ÁN THI CÔNG LẮP ĐẶT MÀN RÈM THỰC TẾ TẠI ĐÀ NẴNG TỪ GOOGLE DRIVE */
        const daNangProjects = [
            {
                driveId: '1Gg80R0yhC4ncnfdhW-_3RfNGqaE4xYIL',
                title: 'Thi Công Rèm Vải 2 Lớp Âm Trần Nhà Phố Tại Đường Âu Cơ, Liên Chiểu, Đà Nẵng',
                location: 'Phường Liên Chiểu, Đà Nẵng',
                date: '28 Th10',
                desc: 'Hoàn thiện trọn gói hệ rèm vải 2 lớp cản nắng 100% kết hợp voan trắng sang trọng cho phòng khách và 3 phòng ngủ.'
            },
            {
                driveId: '1CcbK-jTlYbUG7SzSJMNae3pyCuBIfEn_',
                title: 'Lắp Đặt Rèm Vải & Rèm Cầu Vồng Cho Căn Hộ Gia Đình Tại Hải Châu, Đà Nẵng',
                location: 'Quận Hải Châu, Đà Nẵng',
                date: '24 Th10',
                desc: 'Thiết kế may đo chuẩn kích thước cửa sổ lớn, sử dụng thanh ray hợp kim nhôm trượt êm ái và vải chống tia UV.'
            },
            {
                driveId: '1E6uN6ClhHistK_QMzGkmfcKWc_j0NhN-',
                title: 'Hoàn Thiện Màn Rèm Cao Cấp Cho Biệt Thự Khu Đô Thị Hòa Xuân, Cẩm Lệ, Đà Nẵng',
                location: 'Hòa Xuân, Đà Nẵng',
                date: '19 Th10',
                desc: 'Bàn giao công trình rèm vải 2 lớp tone màu trung tính hiện đại, tôn lên vẻ đẹp sang trọng cho không gian nội thất.'
            },
            {
                driveId: '1_rd-dDP9z_pgGmBzACv8-JSxW7MNBK56',
                title: 'Thi Công Rèm Cửa Sổ & Rèm Phòng Ngủ Tại Khu Đô Thị Golden Hills, Liên Chiểu',
                location: 'Liên Chiểu, Đà Nẵng',
                date: '15 Th10',
                desc: 'Lắp đặt nhanh gọn trong ngày, đường may sóng rèm đều đẹp, cản sáng tuyệt đối giúp giấc ngủ ngon hơn.'
            },
            {
                driveId: '1Jet5D77xnZvAVBdn_aSlo4n0DEvpvdse',
                title: 'Lắp Đặt Trọn Gói Màn Rèm Cho Khách Sạn & Căn Hộ Dịch Vụ Ven Biển Sơn Trà, Đà Nẵng',
                location: 'Quận Sơn Trà, Đà Nẵng',
                date: '11 Th10',
                desc: 'Cung cấp rèm vải chống nắng muối biển và bộ chăn ga gối tiêu chuẩn khách sạn độ bền cao.'
            },
            {
                driveId: '1kckdMSuEWJ5kspNvwqpoLqqGVYkIzS4-',
                title: 'Thi Công Rèm Cầu Vồng Hàn Quốc & Rèm Cuốn Tại Văn Phòng Công Ty Thanh Khê, Đà Nẵng',
                location: 'Quận Thanh Khê, Đà Nẵng',
                date: '06 Th10',
                desc: 'Giải pháp rèm văn phòng gọn gàng, điều chỉnh ánh sáng linh hoạt và tiết kiệm điện năng máy lạnh.'
            },
            {
                driveId: '1R3SFasiT69ubRQAyE6Xw3LcWiry0M7Pu',
                title: 'Hoàn Thiện Rèm Vải 2 Lớp Cho Gia Đình Chị Hương Tại Ngũ Hành Sơn, Đà Nẵng',
                location: 'Ngũ Hành Sơn, Đà Nẵng',
                date: '02 Th10',
                desc: 'Tư vấn chọn màu vải hợp phong thủy gia chủ, lắp đặt tỉ mỉ, vệ sinh sạch sẽ sau khi bàn giao.'
            },
            {
                driveId: '1Ohvf84AoIeJ3lr3VLcdSYAWWreTWJ6sB',
                title: 'Lắp Đặt Rèm Cửa Sổ & Cửa Lưới Chống Muỗi Cho Nhà Phố Hòa Minh, Liên Chiểu',
                location: 'Hòa Minh, Liên Chiểu, Đà Nẵng',
                date: '26 Th09',
                desc: 'Kết hợp hoàn hảo giữa rèm cản nắng và cửa lưới chống muỗi giúp ngôi nhà luôn thoáng mát, an toàn.'
            },
            {
                driveId: '1rtuFS_8TGNZiqfm8kczIBQC--0F4Fve4',
                title: 'Thi Công Hệ Rèm Vải Cao Cấp Thông Tầng Tại Khu Biệt Thự Euro Village Đà Nẵng',
                location: 'Tp. Đà Nẵng',
                date: '18 Th09',
                desc: 'Đội ngũ kỹ thuật Màn Rèm Diệu My thi công rèm khổ lớn chuẩn kỹ thuật, sóng rèm suôn mềm đẳng cấp.'
            }
        ];

        /* DỮ LIỆU BÀI VIẾT TRANG CHỦ */
        const blogPosts = [
            {
                cat: 'tin-rem',
                catName: 'Tin Tức Rèm Cửa',
                driveId: '1Gg80R0yhC4ncnfdhW-_3RfNGqaE4xYIL',
                title: 'Báo Giá Thi Công Màn Rèm Cửa Đà Nẵng Mới Nhất – Màn Rèm Diệu My 71 Âu Cơ',
                excerpt: 'Tổng hợp bảng báo giá rèm vải 2 lớp, rèm cầu vồng Hàn Quốc, rèm cuốn văn phòng, rèm sáo gỗ mới nhất tại Đà Nẵng kèm ưu đãi miễn phí lắp đặt.'
            },
            {
                cat: 'tin-rem',
                catName: 'Tin Tức Rèm Cửa',
                driveId: '1CcbK-jTlYbUG7SzSJMNae3pyCuBIfEn_',
                title: 'Kinh Nghiệm Chọn Rèm Vải 2 Lớp Và Rèm Cầu Vồng Cho Nhà Phố, Căn Hộ Đà Nẵng',
                excerpt: 'Hướng dẫn cách phối màu rèm cửa hợp với màu sơn tường và nội thất, giúp không gian phòng khách rộng rãi, sang trọng và chống nóng hiệu quả.'
            },
            {
                cat: 'tin-cua-luoi',
                catName: 'Cửa Lưới Chống Muỗi',
                driveId: '1Ohvf84AoIeJ3lr3VLcdSYAWWreTWJ6sB',
                title: 'Cửa Lưới Chống Muỗi Đà Nẵng – Giải Pháp Ngăn Côn Trùng Giữ Nhà Luôn Thoáng Mát',
                excerpt: 'So sánh các dòng cửa lưới chống muỗi hệ xếp, hệ tự cuốn, hệ lùa và cửa lưới kết hợp rèm tổ ong 2 trong 1 đang được ưa chuộng nhất hiện nay.'
            },
            {
                cat: 'tin-chan-ga',
                catName: 'Chăn Ga Gối Nệm',
                driveId: '1HZ3bPRZbIsepfnu8FbdgwR2_G7HJhM0X',
                title: 'Cách Chọn Chăn Ga Gối Nệm Khách Sạn & Gia Đình Bền Đẹp, Chuẩn Êm Ái',
                excerpt: 'Bí quyết chọn vải T250, T300 trắng sọc cho khách sạn, homestay tại Đà Nẵng và cách bảo quản nệm cao su thiên nhiên luôn bền đẹp như mới.'
            }
        ];

        /* HÀM TẠO CARD SẢN PHẨM CHUẨN FLATSOME:
           - Nhãn giảm giá -XX% góc trên bên trái
           - Chia 2 cột trên điện thoại
           - Tên sản phẩm hiển thị đầy đủ (không cắt chữ, không tràn viền)
        */
        function createFlatsomeProductCard(item) {
            const safeName = item.name.replace(/'/g, "\\'");
            return `
                <div class="bg-white rounded-xl border border-slate-200/90 shadow-2xs hover:shadow-md transition overflow-hidden flex flex-col justify-between group">
                    <div>
                        <div class="relative aspect-square w-full bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal('${safeName}', '${item.driveId}', '${item.oldPrice}', '${item.newPrice}', '${item.discount}')">
                            <!-- Badge % giảm giá chuẩn Flatsome góc trên bên trái -->
                            <span class="flatsome-Badge-sale">${item.discount}</span>
                            <img 
                                src="https://lh3.googleusercontent.com/d/${item.driveId}=w700" 
                                onerror="handleDriveImgError(this, '${item.driveId}', 'MAN REM DIEU MY')"
                                alt="${item.name}" 
                                loading="lazy"
                                class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <!-- Tên sản phẩm đầy đủ, tự xuống dòng, không bị cắt chữ hay tràn ra ngoài -->
                            <h3 onclick="openProductModal('${safeName}', '${item.driveId}', '${item.oldPrice}', '${item.newPrice}', '${item.discount}')" class="text-xs sm:text-[14px] font-semibold text-slate-800 hover:text-primary leading-snug break-words whitespace-normal cursor-pointer">
                                ${item.name}
                            </h3>
                        </div>
                    </div>

                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 mt-1">
                        <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5 mb-2">
                            <del class="text-[11px] sm:text-xs text-slate-400">${item.oldPrice}</del>
                            <span class="text-xs sm:text-sm font-extrabold text-saleRed">${item.newPrice}</span>
                        </div>
                        <div class="grid grid-cols-2 gap-1.5">
                            <button type="button" onclick="prefillQuote('${safeName}')" class="bg-primary hover:bg-primaryDark text-white font-bold text-[11px] sm:text-xs py-2 px-2 rounded-lg transition text-center">
                                Báo Giá
                            </button>
                            <button type="button" onclick="openProductModal('${safeName}', '${item.driveId}', '${item.oldPrice}', '${item.newPrice}', '${item.discount}')" class="bg-slate-100 hover:bg-slate-200 text-slate-700 font-semibold text-[11px] sm:text-xs py-2 px-2 rounded-lg transition text-center">
                                Xem Ảnh
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        /* RENDER DANH MỤC RÈM CỬA (15 ẢNH THỰC TẾ) */
        function renderRemProducts(categoryFilter = 'all', keyword = '') {
            const grid = document.getElementById('remProductGrid');
            const filtered = remRealProducts.filter(item => {
                const matchCat = categoryFilter === 'all' || item.category === categoryFilter;
                const matchKw = !keyword || item.name.toLowerCase().includes(keyword.toLowerCase());
                return matchCat && matchKw;
            });

            if (filtered.length === 0) {
                grid.innerHTML = `
                    <div class="col-span-full bg-white rounded-xl p-6 text-center border border-slate-200">
                        <p class="text-sm text-slate-600 mb-3">Không tìm thấy mẫu phù hợp với từ khóa. Hiển thị lại toàn bộ 15 mẫu thực tế:</p>
                        <button type="button" onclick="filterRemCategory('all')" class="bg-primary text-white text-xs font-bold px-4 py-2 rounded-lg">Xem Tất Cả Mẫu Rèm</button>
                    </div>
                `;
                return;
            }

            grid.innerHTML = filtered.map(item => createFlatsomeProductCard(item)).join('');
        }

        function filterRemCategory(cat) {
            document.querySelectorAll('.rem-filter-btn').forEach(btn => {
                if (btn.getAttribute('data-cat') === cat) {
                    btn.className = 'rem-filter-btn bg-primary text-white font-bold text-xs py-2.5 px-2 rounded-lg border border-primary transition text-center';
                } else {
                    btn.className = 'rem-filter-btn bg-white hover:bg-slate-100 text-slate-700 font-semibold text-xs py-2.5 px-2 rounded-lg border border-slate-200 transition text-center';
                }
            });
            renderRemProducts(cat);
        }

        /* RENDER CÁC DANH MỤC KHÁC TRÊN TRANG CHỦ */
        function renderAllOtherCategories() {
            document.getElementById('cuaLuoiGrid').innerHTML = cuaLuoiProducts.map(createFlatsomeProductCard).join('');
            document.getElementById('nemGrid').innerHTML = nemProducts.map(createFlatsomeProductCard).join('');
            document.getElementById('gianPhoiGrid').innerHTML = gianPhoiProducts.map(createFlatsomeProductCard).join('');
            document.getElementById('chanGaGrid').innerHTML = chanGaProducts.map(createFlatsomeProductCard).join('');
            document.getElementById('goiGrid').innerHTML = goiProducts.map(createFlatsomeProductCard).join('');
        }

        /* RENDER 9 DỰ ÁN THI CÔNG LẮP ĐẶT MÀN RÈM TẠI ĐÀ NẴNG */
        function renderProjects() {
            const grid = document.getElementById('projectGrid');
            grid.innerHTML = daNangProjects.map((proj, idx) => {
                const safeTitle = proj.title.replace(/'/g, "\\'");
                const safeDesc = proj.desc.replace(/'/g, "\\'");
                return `
                    <article class="bg-white rounded-xl border border-slate-200 shadow-2xs hover:shadow-md transition overflow-hidden flex flex-col justify-between group cursor-pointer" onclick="openProjectModal('${safeTitle}', '${proj.driveId}', '${proj.location}', '${safeDesc}')">
                        <div>
                            <div class="relative aspect-[4/3] w-full bg-slate-200 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/${proj.driveId}=w800" 
                                    onerror="handleDriveImgError(this, '${proj.driveId}', 'DU AN DA NANG ${idx + 1}')"
                                    alt="${proj.title}" 
                                    loading="lazy"
                                    class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                >
                                <!-- Hộp ngày tháng chuẩn bài viết công trình Flatsome -->
                                <div class="absolute top-2.5 left-2.5 bg-white/95 text-primary font-extrabold text-[11px] px-2.5 py-1 rounded shadow">
                                    ${proj.date}
                                </div>
                            </div>
                            <div class="p-3 sm:p-4">
                                <p class="text-[11px] font-bold text-amber-600 uppercase mb-1">
                                    <i class="fa-solid fa-location-dot mr-1"></i>${proj.location}
                                </p>
                                <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-primary leading-snug break-words whitespace-normal mb-1.5">
                                    ${proj.title}
                                </h3>
                                <p class="text-xs text-slate-500 leading-relaxed hidden sm:block">
                                    ${proj.desc}
                                </p>
                            </div>
                        </div>
                        <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-1 flex items-center justify-between text-xs font-bold text-primary">
                            <span>Xem ảnh công trình</span>
                            <i class="fa-solid fa-magnifying-glass-plus"></i>
                        </div>
                    </article>
                `;
            }).join('');
        }

        /* RENDER DANH MỤC BÀI VIẾT TRANG CHỦ */
        function renderBlogs(catFilter = 'all') {
            const grid = document.getElementById('blogGrid');
            const list = catFilter === 'all' ? blogPosts : blogPosts.filter(b => b.cat === catFilter);
            grid.innerHTML = list.map(post => {
                const safeTitle = post.title.replace(/'/g, "\\'");
                const safeExcerpt = post.excerpt.replace(/'/g, "\\'");
                return `
                    <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between cursor-pointer" onclick="openBlogModal('${safeTitle}', '${post.driveId}', '${post.catName}', '${safeExcerpt}')">
                        <div>
                            <div class="aspect-[16/10] w-full bg-slate-200 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/${post.driveId}=w700" 
                                    onerror="handleDriveImgError(this, '${post.driveId}', 'TIN TUC MAN REM')"
                                    alt="${post.title}" 
                                    loading="lazy"
                                    class="w-full h-full object-cover hover:scale-105 transition duration-500"
                                >
                            </div>
                            <div class="p-3.5">
                                <span class="inline-block text-[11px] font-bold text-amber-600 uppercase mb-1">${post.catName}</span>
                                <h3 class="font-bold text-sm text-slate-800 hover:text-primary leading-snug break-words mb-2">
                                    ${post.title}
                                </h3>
                                <p class="text-xs text-slate-600 leading-relaxed">
                                    ${post.excerpt}
                                </p>
                            </div>
                        </div>
                        <div class="px-3.5 pb-3.5 pt-1 text-xs font-bold text-primary flex items-center gap-1">
                            <span>Đọc chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </div>
                    </article>
                `;
            }).join('');
        }

        function filterBlog(cat) {
            document.querySelectorAll('.blog-tab-btn').forEach(btn => {
                if (btn.getAttribute('data-blog') === cat) {
                    btn.className = 'blog-tab-btn bg-primary text-white text-xs font-bold px-3 py-1.5 rounded';
                } else {
                    btn.className = 'blog-tab-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold px-3 py-1.5 rounded';
                }
            });
            renderBlogs(cat);
        }

        /* XỬ LÝ BANNER SLIDER TỰ TRƯỢT */
        let currentBannerIndex = 0;
        let bannerInterval = null;

        function showBannerSlide(index) {
            const slides = document.querySelectorAll('.hero-slide');
            const dots = document.querySelectorAll('.banner-dot');
            currentBannerIndex = (index + slides.length) % slides.length;

            slides.forEach((slide, i) => {
                if (i === currentBannerIndex) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            dots.forEach((dot, i) => {
                if (i === currentBannerIndex) {
                    dot.className = 'banner-dot w-6 h-2 rounded-full bg-amber-400 transition-all';
                } else {
                    dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            });
        }

        function nextBannerSlide() {
            showBannerSlide(currentBannerIndex + 1);
            resetBannerTimer();
        }

        function prevBannerSlide() {
            showBannerSlide(currentBannerIndex - 1);
            resetBannerTimer();
        }

        function goToBannerSlide(index) {
            showBannerSlide(index);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                showBannerSlide(currentBannerIndex + 1);
            }, 5000);
        }

        /* MENU ĐIỆN THOẠI */
        function toggleMobileMenu() {
            const overlay = document.getElementById('mobileMenuOverlay');
            const drawer = document.getElementById('mobileMenuDrawer');
            const isOpen = !overlay.classList.contains('hidden');
            if (isOpen) {
                overlay.classList.add('hidden');
                drawer.classList.add('-translate-x-full');
            } else {
                overlay.classList.remove('hidden');
                drawer.classList.remove('-translate-x-full');
            }
        }

        /* TÌM KIẾM SẢN PHẨM */
        function handleSearch(e) {
            e.preventDefault();
            const kw = document.getElementById('desktopSearchInput').value.trim();
            const cat = document.getElementById('searchCategorySelect').value;
            if (cat !== 'all' && cat !== 'rem-cua') {
                const targetEl = document.getElementById('sec-' + cat);
                if (targetEl) targetEl.scrollIntoView({ behavior: 'smooth' });
                return;
            }
            renderRemProducts('all', kw);
            document.getElementById('sec-rem-cua').scrollIntoView({ behavior: 'smooth' });
        }

        function handleMobileSearch(e) {
            e.preventDefault();
            const kw = document.getElementById('mobileSearchInput').value.trim();
            renderRemProducts('all', kw);
            document.getElementById('sec-rem-cua').scrollIntoView({ behavior: 'smooth' });
        }

        /* ĐIỀN NHANH FORM BÁO GIÁ KHI BẤM NÚT TRÊN SẢN PHẨM */
        function prefillQuote(productName) {
            const noteInput = document.getElementById('quoteNote');
            noteInput.value = 'Tôi cần tư vấn & báo giá mẫu: ' + productName;
            document.getElementById('bao-gia').scrollIntoView({ behavior: 'smooth' });
            document.getElementById('quoteName').focus();
        }

        /* MODAL XEM ẢNH SẢN PHẨM / DỰ ÁN / BÀI VIẾT */
        function openProductModal(name, driveId, oldPrice, newPrice, discount) {
            const modal = document.getElementById('detailModal');
            document.getElementById('modalTitle').textContent = name;
            document.getElementById('modalBody').innerHTML = `
                <div class="relative rounded-lg overflow-hidden bg-slate-100 border border-slate-200">
                    <span class="flatsome-Badge-sale">${discount}</span>
                    <img 
                        src="https://lh3.googleusercontent.com/d/${driveId}=w1200" 
                        onerror="handleDriveImgError(this, '${driveId}', 'MAN REM DIEU MY')"
                        alt="${name}" 
                        class="w-full max-h-[420px] object-contain mx-auto"
                    >
                </div>
                <div class="flex flex-wrap items-baseline gap-3">
                    <span class="text-sm text-slate-500">Đơn giá ưu đãi:</span>
                    <del class="text-sm text-slate-400">${oldPrice}</del>
                    <span class="text-lg font-extrabold text-saleRed">${newPrice}</span>
                </div>
                <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                    Sản phẩm được <strong>Màn Rèm Diệu My</strong> may đo và lắp đặt hoàn thiện theo kích thước thực tế tại công trình ở Đà Nẵng. Miễn phí mang mẫu tận nhà, đo đạc và lắp đặt.
                </p>
                <div class="flex flex-wrap gap-2.5 pt-2">
                    <button type="button" onclick="closeDetailModal(); prefillQuote('${name.replace(/'/g, "\\'")}')" class="flex-1 bg-primary hover:bg-primaryDark text-white font-bold text-xs sm:text-sm py-3 px-4 rounded-lg">
                        Đăng Ký Báo Giá Mẫu Này
                    </button>
                    <a href="tel:0899922221" class="bg-saleRed hover:bg-red-700 text-white font-bold text-xs sm:text-sm py-3 px-4 rounded-lg inline-flex items-center gap-1.5">
                        <i class="fa-solid fa-phone"></i> 0899.922.221
                    </a>
                </div>
            `;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function openProjectModal(title, driveId, location, desc) {
            const modal = document.getElementById('detailModal');
            document.getElementById('modalTitle').textContent = title;
            document.getElementById('modalBody').innerHTML = `
                <div class="rounded-lg overflow-hidden bg-slate-100 border border-slate-200">
                    <img 
                        src="https://lh3.googleusercontent.com/d/${driveId}=w1200" 
                        onerror="handleDriveImgError(this, '${driveId}', 'DU AN THI CONG')"
                        alt="${title}" 
                        class="w-full max-h-[440px] object-contain mx-auto"
                    >
                </div>
                <p class="text-xs font-bold text-amber-600 uppercase"><i class="fa-solid fa-location-dot mr-1"></i>${location}</p>
                <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">${desc}</p>
                <div class="flex flex-wrap gap-2 pt-2">
                    <button type="button" onclick="closeDetailModal(); prefillQuote('${title.replace(/'/g, "\\'")}')" class="flex-1 bg-primary text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg">
                        Yêu Cầu Thi Công Tương Tự
                    </button>
                    <a href="https://zalo.me/0899922221" target="_blank" rel="noopener" class="bg-blue-600 text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg">
                        Tư Vấn Qua Zalo
                    </a>
                </div>
            `;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function openBlogModal(title, driveId, catName, excerpt) {
            const modal = document.getElementById('detailModal');
            document.getElementById('modalTitle').textContent = title;
            document.getElementById('modalBody').innerHTML = `
                <img 
                    src="https://lh3.googleusercontent.com/d/${driveId}=w1000" 
                    onerror="handleDriveImgError(this, '${driveId}', 'BAI VIET')"
                    alt="${title}" 
                    class="w-full max-h-[300px] object-cover rounded-lg"
                >
                <span class="inline-block text-xs font-bold text-amber-600 uppercase">${catName}</span>
                <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">${excerpt}</p>
                <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
                    Tại <strong>Màn Rèm Diệu My (71 Âu Cơ, Phường Liên Chiểu, Tp.Đà Nẵng)</strong>, chúng tôi cung cấp hơn 500+ mẫu vải rèm chống nắng, rèm cầu vồng Hàn Quốc, rèm cuốn, rèm gỗ, cửa lưới chống muỗi và chăn ga gối nệm với giá gốc tại xưởng. Quý khách vui lòng liên hệ Hotline/Zalo <strong>0899.922.221 - 0788.694.567</strong> để được nhân viên mang mẫu tận nhà tư vấn hoàn toàn miễn phí.
                </p>
            `;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /* XỬ LÝ GỬI FORM YÊU CẦU BÁO GIÁ (KHÔNG DÙNG ALERT) */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('quoteName').value.trim();
            const phone = document.getElementById('quotePhone').value.trim();
            const service = document.getElementById('quoteService').value;
            const address = document.getElementById('quoteAddress').value.trim() || 'Đà Nẵng';
            const note = document.getElementById('quoteNote').value.trim() || 'Tư vấn & mang mẫu tận nơi';

            const modal = document.getElementById('detailModal');
            document.getElementById('modalTitle').textContent = 'ĐÃ TIẾP NHẬN YÊU CẦU BÁO GIÁ';
            document.getElementById('modalBody').innerHTML = `
                <div class="p-4 rounded-xl bg-emerald-50 border border-emerald-200 text-emerald-900 space-y-2 text-xs sm:text-sm">
                    <p class="font-extrabold text-base text-emerald-700 flex items-center gap-2">
                        <i class="fa-solid fa-circle-check text-lg"></i>
                        <span>Cảm ơn ${name}! Màn Rèm Diệu My đã nhận yêu cầu.</span>
                    </p>
                    <p><strong>Số điện thoại / Zalo:</strong> ${phone}</p>
                    <p><strong>Hạng mục quan tâm:</strong> ${service}</p>
                    <p><strong>Địa chỉ công trình:</strong> ${address}</p>
                    <p><strong>Ghi chú:</strong> ${note}</p>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">
                    Chuyên viên tư vấn của <strong>Màn Rèm Diệu My (0899.922.221 - 0788.694.567)</strong> sẽ liên hệ lại ngay để báo giá chi tiết và hẹn lịch mang mẫu tận nơi miễn phí cho quý khách.
                </p>
                <div class="flex flex-wrap gap-2 pt-2">
                    <a href="https://zalo.me/0899922221" target="_blank" rel="noopener" class="flex-1 bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg text-center">
                        Nhắn Zalo Ngay (0899.922.221)
                    </a>
                    <button type="button" onclick="closeDetailModal()" class="bg-slate-200 hover:bg-slate-300 text-slate-800 font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg">
                        Đóng
                    </button>
                </div>
            `;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.getElementById('quoteRequestForm').reset();
        }

        /* KHỞI TẠO TRANG WEB KHI TẢI XONG */
        window.onload = function () {
            renderRemProducts('all');
            renderAllOtherCategories();
            renderProjects();
            renderBlogs('all');
            resetBannerTimer();
        };
    </script>
</body>
</html>
