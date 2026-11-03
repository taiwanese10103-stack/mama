# mama<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>卡多摩風格母嬰用品網 - 呵護寶寶的每一步</title>
    <!-- 引入 Tailwind CSS 樣式 -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-gray-50 font-sans text-gray-800">

    <!-- 頂部公告列 -->
    <div class="bg-pink-600 text-white text-xs md:text-sm py-2 px-4 text-center font-medium">
        🎉 歡慶開幕！全館滿 $1,500 免運費 ｜ 註冊會員立即領取 $100 元孕媽咪首購折價券
    </div>

    <!-- 導覽列 Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 py-3 flex items-center justify-between">
            <!-- Logo -->
            <div class="flex items-center space-x-2">
                <span class="text-2xl font-black text-pink-600 tracking-wider">👶 卡多摩好寶貝</span>
            </div>
            
            <!-- 搜尋列 (桌面版) -->
            <div class="hidden md:flex items-center flex-1 max-w-md mx-8">
                <div class="relative w-full">
                    <input type="text" placeholder="搜尋 幫寶適尿布、亞培奶粉、推車..." class="w-full pl-4 pr-10 py-2 border border-gray-300 rounded-full focus:outline-none focus:border-pink-500 text-sm">
                    <button class="absolute right-3 top-2.5 text-gray-400 hover:text-pink-600">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>

            <!-- 會員與購物車 -->
            <div class="flex items-center space-x-6">
                <a href="#" class="hidden sm:flex items-center space-x-1 text-sm text-gray-600 hover:text-pink-600">
                    <i class="fa-regular fa-user"></i>
                    <span>會員專區</span>
                </a>
                <a href="#" class="relative text-gray-600 hover:text-pink-600 flex items-center space-x-1">
                    <i class="fa-solid fa-cart-shopping text-xl"></i>
                    <span class="bg-pink-600 text-white text-xs rounded-full h-5 w-5 flex items-center justify-center font-bold">3</span>
                </a>
            </div>
        </div>

        <!-- 導覽分類列 (模仿卡多摩的多層次分類) -->
        <nav class="bg-pink-50 border-t border-pink-100 hidden md:block">
            <div class="max-w-7xl mx-auto px-4 flex space-x-8 text-sm font-semibold text-gray-700 py-2.5">
                <a href="#" class="text-pink-600 hover:text-pink-700">🔥 本月強檔DM</a>
                <a href="#" class="hover:text-pink-600">🤱 孕媽咪專區</a>
                <a href="#" class="hover:text-pink-600">🍼 奶粉 / 營養副食品</a>
                <a href="#" class="hover:text-pink-600">🧷 紙尿褲 / 濕紙巾</a>
                <a href="#" class="hover:text-pink-600">🚗 推車 / 安全座椅</a>
                <a href="#" class="hover:text-pink-600">🛁 沐浴 / 照護清潔</a>
                <a href="#" class="hover:text-pink-600">🧸 玩具 / 恩典教具</a>
            </div>
        </nav>
    </header>

    <!-- 主視覺 Banner (Hero Section) -->
    <section class="max-w-7xl mx-auto px-4 my-6">
        <div class="bg-gradient-to-r from-pink-400 to-rose-300 rounded-2xl p-8 md:p-12 text-white flex flex-col md:flex-row items-center justify-between shadow-md">
            <div class="max-w-lg mb-6 md:mb-0">
                <span class="bg-white text-pink-600 text-xs px-3 py-1 rounded-full font-bold uppercase tracking-wide">限時特惠月</span>
                <h1 class="text-3xl md:text-5xl font-black mt-3 leading-tight">呵護寶貝成長 <br>媽媽省錢好幫手</h1>
                <p class="mt-3 text-pink-100 text-sm md:text-base">人氣尿布、大牌奶粉超低特惠價，滿額再送精美安撫玩具！</p>
                <button class="mt-6 bg-white text-pink-600 font-bold px-6 py-3 rounded-full shadow hover:bg-pink-50 transition">立即搶購特惠</button>
            </div>
            <div class="bg-white/20 p-6 rounded-2xl backdrop-blur-sm text-center">
                <div class="text-2xl font-black">🎁 孕媽咪專屬好禮</div>
                <p class="text-sm mt-2 text-pink-100">憑媽媽手冊免費兌換試用包禮盒</p>
                <button class="mt-4 bg-pink-700 text-white px-4 py-2 rounded-lg text-sm font-bold hover:bg-pink-800 transition">免費登記</button>
            </div>
        </div>
    </section>

    <!-- 熱門商品網格 (Product Grid) -->
    <main class="max-w-7xl mx-auto px-4 my-10">
        <div class="flex justify-between items-center mb-6">
            <h2 class="text-2xl font-black text-gray-800 border-l-4 border-pink-600 pl-3">🔥 媽咪熱推明星商品</h2>
            <a href="#" class="text-sm text-pink-600 font-semibold hover:underline">查看全部 &gt;</a>
        </div>

        <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
            <!-- 商品卡片 1 -->
            <div class="bg-white rounded-xl shadow-sm hover:shadow-md transition p-4 flex flex-col justify-between border border-gray-100">
                <div>
                    <div class="bg-gray-100 h-48 rounded-lg mb-3 flex items-center justify-center text-gray-400 font-medium">
                        [尿布商品圖片]
                    </div>
                    <span class="text-xs bg-pink-100 text-pink-600 px-2 py-0.5 rounded font-semibold">熱銷爆款</span>
                    <h3 class="font-bold text-gray-800 mt-2 text-sm line-clamp-2">幫寶適 一幫到底拉拉褲/紙尿褲 箱購特惠</h3>
                </div>
                <div class="mt-4">
                    <div class="flex items-baseline space-x-2">
                        <span class="text-pink-600 font-black text-lg">$1,299</span>
                        <span class="text-gray-400 text-xs line-through">$1,699</span>
                    </div>
                    <button class="w-full mt-3 bg-pink-600 text-white py-2 rounded-lg text-sm font-bold hover:bg-pink-700 transition">加入購物車</button>
                </div>
            </div>

            <!-- 商品卡片 2 -->
            <div class="bg-white rounded-xl shadow-sm hover:shadow-md transition p-4 flex flex-col justify-between border border-gray-100">
                <div>
                    <div class="bg-gray-100 h-48 rounded-lg mb-3 flex items-center justify-center text-gray-400 font-medium">
                        [奶粉商品圖片]
                    </div>
                    <span class="text-xs bg-yellow-100 text-yellow-700 px-2 py-0.5 rounded font-semibold">營養首選</span>
                    <h3 class="font-bold text-gray-800 mt-2 text-sm line-clamp-2">亞培 恩美力 / 心美力幼兒成長奶粉 900g</h3>
                </div>
                <div class="mt-4">
                    <div class="flex items-baseline space-x-2">
                        <span class="text-pink-600 font-black text-lg">$850</span>
                        <span class="text-gray-400 text-xs line-through">$980</span>
                    </div>
                    <button class="w-full mt-3 bg-pink-600 text-white py-2 rounded-lg text-sm font-bold hover:bg-pink-700 transition">加入購物車</button>
                </div>
            </div>

            <!-- 商品卡片 3 -->
            <div class="bg-white rounded-xl shadow-sm hover:shadow-md transition p-4 flex flex-col justify-between border border-gray-100">
                <div>
                    <div class="bg-gray-100 h-48 rounded-lg mb-3 flex items-center justify-center text-gray-400 font-medium">
                        [推車商品圖片]
                    </div>
                    <span class="text-xs bg-purple-100 text-purple-700 px-2 py-0.5 rounded font-semibold">外出必備</span>
                    <h3 class="font-bold text-gray-800 mt-2 text-sm line-clamp-2">Combi 輕量雙向嬰幼兒手推車 (多色可選)</h3>
                </div>
                <div class="mt-4">
                    <div class="flex items-baseline space-x-2">
                        <span class="text-pink-600 font-black text-lg">$7,990</span>
                        <span class="text-gray-400 text-xs line-through">$9,900</span>
                    </div>
                    <button class="w-full mt-3 bg-pink-600 text-white py-2 rounded-lg text-sm font-bold hover:bg-pink-700 transition">加入購物車</button>
                </div>
            </div>

            <!-- 商品卡片 4 -->
            <div class="bg-white rounded-xl shadow-sm hover:shadow-md transition p-4 flex flex-col justify-between border border-gray-100">
                <div>
                    <div class="bg-gray-100 h-48 rounded-lg mb-3 flex items-center justify-center text-gray-400 font-medium">
                        [洗護商品圖片]
                    </div>
                    <span class="text-xs bg-green-100 text-green-700 px-2 py-0.5 rounded font-semibold">草本溫和</span>
                    <h3 class="font-bold text-gray-800 mt-2 text-sm line-clamp-2">慕之恬廊 寶寶免用水潔淨露 / 慕斯雙效組</h3>
                </div>
                <div class="mt-4">
                    <div class="flex items-baseline space-x-2">
                        <span class="text-pink-600 font-black text-lg">$699</span>
                        <span class="text-gray-400 text-xs line-through">$1,200</span>
                    </div>
                    <button class="w-full mt-3 bg-pink-600 text-white py-2 rounded-lg text-sm font-bold hover:bg-pink-700 transition">加入購物車</button>
                </div>
            </div>
        </div>
    </main>

    <!-- 頁尾 Footer -->
    <footer class="bg-white border-t border-gray-200 mt-16 py-8 text-sm text-gray-500">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <p class="font-bold text-gray-700 mb-2">卡多摩風格母嬰用品網 ｜ 致力於給寶寶最好的呵護</p>
            <p>&copy; 2026 Baby Shop Demo. Hosted on GitHub Pages.</p>
        </div>
    </footer>

</body>
</html>
