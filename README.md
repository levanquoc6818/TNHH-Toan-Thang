<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Công Ty Cổ Phần Phát Triển Nguồn Lực Thăng Long DIH</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts (Inter) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <style>
        /* Custom styles */
        body {
            font-family: 'Inter', sans-serif;
        }
        .hero-section {
            background-image: url('https://images.unsplash.com/photo-1504628599423-6b2f6de6f6e1?q=80&w=1920&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
        }
        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background-color: #3b82f6; /* blue-500 */
            margin: 8px auto 0;
            border-radius: 2px;
        }
        .order-card, .news-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .order-card:hover, .news-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <!-- Top Bar -->
        <div class="bg-blue-600 text-white text-sm py-2">
            <div class="container mx-auto px-4 flex justify-between items-center">
                <div class="flex items-center space-x-6">
                    <span class="hidden md:flex items-center"><i class="fas fa-phone mr-2"></i> +84 329 439 665</span>
                    <span class="hidden md:flex items-center"><i class="fas fa-envelope mr-2"></i> contact@thanglongdih.website</span>
                </div>
                <div class="flex items-center space-x-4">
                    <a href="#" class="hover:text-blue-200"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" class="hover:text-blue-200"><i class="fab fa-youtube"></i></a>
                    <input type="text" placeholder="Tìm kiếm..." class="hidden sm:block px-2 py-1 rounded-md text-gray-800 text-sm focus:outline-none focus:ring-2 focus:ring-blue-300">
                </div>
            </div>
        </div>

        <!-- Main Navigation -->
        <nav class="container mx-auto px-4 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center text-2xl font-bold text-blue-600">
                <!-- SVG Logo -->
                <svg class="w-10 h-10 mr-3" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="25" cy="25" r="22" stroke="#3B82F6" stroke-width="3"/>
                    <path d="M10 25C10 25 15 20 25 25C35 30 40 25 40 25" stroke="#3B82F6" stroke-width="3" stroke-linecap="round"/>
                    <path d="M25 10C25 10 20 15 25 25C30 35 25 40 25 40" stroke="#3B82F6" stroke-width="3" stroke-linecap="round"/>
                    <path d="M12.2474 13.9186C14.7352 23.3323 23.8291 35.1525 36.6022 36.3117" stroke="#fb923c" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                THĂNG LONG DIH
            </a>
            <div class="hidden lg:flex items-center space-x-6 font-medium text-gray-700">
                <a href="#" class="hover:text-blue-600">Trang Chủ</a>
                <a href="#about" class="hover:text-blue-600">Giới Thiệu</a>
                <a href="#orders" class="hover:text-blue-600">Đơn Hàng</a>
                <a href="#news" class="hover:text-blue-600">Tin Tức</a>
                <a href="#contact" class="hover:text-blue-600">Liên Hệ</a>
            </div>
            <button id="mobile-menu-button" class="lg:hidden text-gray-700 focus:outline-none">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </nav>

        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t">
            <a href="#" class="block px-4 py-3 text-gray-700 hover:bg-gray-100">Trang Chủ</a>
            <a href="#about" class="block px-4 py-3 text-gray-700 hover:bg-gray-100">Giới Thiệu</a>
            <a href="#orders" class="block px-4 py-3 text-gray-700 hover:bg-gray-100">Đơn Hàng</a>
            <a href="#news" class="block px-4 py-3 text-gray-700 hover:bg-gray-100">Tin Tức</a>
            <a href="#contact" class="block px-4 py-3 text-gray-700 hover:bg-gray-100">Liên Hệ</a>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="hero-section text-white h-[60vh] md:h-[80vh] flex items-center">
            <div class="container mx-auto px-4 text-center">
                <h1 class="text-4xl md:text-6xl font-extrabold mb-4 leading-tight" style="text-shadow: 2px 2px 4px rgba(0,0,0,0.5);">Chắp Cánh Ước Mơ Vươn Ra Thế Giới</h1>
                <p class="text-lg md:text-xl mb-8 max-w-3xl mx-auto" style="text-shadow: 1px 1px 2px rgba(0,0,0,0.5);">Chúng tôi là cầu nối đáng tin cậy, mang đến cơ hội việc làm chất lượng tại các quốc gia phát triển.</p>
                <a href="#orders" class="bg-orange-500 hover:bg-orange-600 text-white font-bold py-3 px-8 rounded-full text-lg transition duration-300 transform hover:scale-105">Xem Ngay Các Đơn Hàng</a>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-4">
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div>
                        <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1200&auto=format&fit=crop" alt="Về chúng tôi" class="rounded-lg shadow-xl w-full">
                    </div>
                    <div>
                        <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">Giới Thiệu Về Thăng Long DIH</h2>
                        <div class="w-20 h-1 bg-blue-500 mb-6"></div>
                        <p class="text-gray-600 mb-4 leading-relaxed">
                            Với nhiều năm kinh nghiệm trong lĩnh vực cung ứng và phát triển nguồn nhân lực, công ty chúng tôi tự hào là một trong những đơn vị hàng đầu tại Việt Nam. Sứ mệnh của chúng tôi là tạo ra cơ hội việc làm ổn định, thu nhập cao và môi trường làm việc an toàn cho người lao động Việt Nam tại nước ngoài.
                        </p>
                        <p class="text-gray-600 mb-6 leading-relaxed">
                            Chúng tôi cam kết đồng hành cùng người lao động từ quá trình đào tạo, hoàn thiện hồ sơ cho đến khi làm việc và trở về nước.
                        </p>
                        <a href="#" class="bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-6 rounded-lg transition duration-300">Tìm Hiểu Thêm</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Featured Orders Section -->
        <section id="orders" class="py-16 md:py-24">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 text-center mb-12 section-title">Đơn Hàng Nổi Bật</h2>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Order Card 1 -->
                    <div class="order-card bg-white rounded-lg shadow-lg overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1556911220-bff31c812dba?q=80&w=800&auto=format&fit=crop" alt="Chế biến thực phẩm" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <span class="text-sm bg-blue-100 text-blue-800 py-1 px-3 rounded-full">Nhật Bản</span>
                            <h3 class="text-xl font-bold my-3 text-gray-800">Đơn hàng chế biến thực phẩm tại Tokyo</h3>
                            <p class="text-gray-600 mb-4"><i class="fas fa-dollar-sign mr-2 text-green-500"></i>Lương: <span class="font-semibold">35-40 Triệu/Tháng</span></p>
                            <p class="text-gray-600 mb-4"><i class="fas fa-calendar-alt mr-2 text-red-500"></i>Hạn nộp: <span class="font-semibold">30/08/2025</span></p>
                            <a href="#" class="w-full text-center bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded-lg transition duration-300 block">Xem Chi Tiết</a>
                        </div>
                    </div>
                    <!-- Order Card 2 -->
                    <div class="order-card bg-white rounded-lg shadow-lg overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1541888946425-d81bb19240f5?q=80&w=800&auto=format&fit=crop" alt="Xây dựng" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <span class="text-sm bg-blue-100 text-blue-800 py-1 px-3 rounded-full">Đài Loan</span>
                            <h3 class="text-xl font-bold my-3 text-gray-800">Đơn hàng xây dựng, giàn giáo tại Đài Bắc</h3>
                            <p class="text-gray-600 mb-4"><i class="fas fa-dollar-sign mr-2 text-green-500"></i>Lương: <span class="font-semibold">30-35 Triệu/Tháng</span></p>
                            <p class="text-gray-600 mb-4"><i class="fas fa-calendar-alt mr-2 text-red-500"></i>Hạn nộp: <span class="font-semibold">15/09/2025</span></p>
                            <a href="#" class="w-full text-center bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded-lg transition duration-300 block">Xem Chi Tiết</a>
                        </div>
                    </div>
                    <!-- Order Card 3 -->
                    <div class="order-card bg-white rounded-lg shadow-lg overflow-hidden">
                        <img src="https://images.unsplash.com/photo-1562423214-45944114282c?q=80&w=800&auto=format&fit=crop" alt="Cơ khí" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <span class="text-sm bg-blue-100 text-blue-800 py-1 px-3 rounded-full">Hàn Quốc</span>
                            <h3 class="text-xl font-bold my-3 text-gray-800">Tuyển kỹ sư cơ khí làm việc tại Seoul</h3>
                            <p class="text-gray-600 mb-4"><i class="fas fa-dollar-sign mr-2 text-green-500"></i>Lương: <span class="font-semibold">45-55 Triệu/Tháng</span></p>
                            <p class="text-gray-600 mb-4"><i class="fas fa-calendar-alt mr-2 text-red-500"></i>Hạn nộp: <span class="font-semibold">25/08/2025</span></p>
                            <a href="#" class="w-full text-center bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded-lg transition duration-300 block">Xem Chi Tiết</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- News Section -->
        <section id="news" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 text-center mb-12 section-title">Tin Tức & Sự Kiện</h2>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                     <!-- News Card 1 -->
                     <div class="news-card bg-white rounded-lg overflow-hidden border">
                        <img src="https://images.unsplash.com/photo-1528164344705-47542687000d?q=80&w=800&auto=format&fit=crop" alt="Tin tức" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <p class="text-sm text-gray-500 mb-2">15 Tháng 6, 2025</p>
                            <h3 class="text-xl font-bold mb-3 text-gray-800 hover:text-blue-600"><a href="#">Những điều cần biết khi đi XKLĐ Nhật Bản 2025</a></h3>
                            <p class="text-gray-600 leading-relaxed line-clamp-3">
                                Thị trường xuất khẩu lao động Nhật Bản luôn là điểm đến hấp dẫn. Cùng tìm hiểu những thay đổi mới nhất về chính sách và chi phí...
                            </p>
                        </div>
                    </div>
                     <!-- News Card 2 -->
                     <div class="news-card bg-white rounded-lg overflow-hidden border">
                        <img src="https://images.unsplash.com/photo-1540575467063-178a50c2df87?q=80&w=800&auto=format&fit=crop" alt="Sự kiện" class="w-full h-48 object-cover">
                        <div class="p-6">
                             <p class="text-sm text-gray-500 mb-2">10 Tháng 6, 2025</p>
                            <h3 class="text-xl font-bold mb-3 text-gray-800 hover:text-blue-600"><a href="#">Công ty tổ chức lễ xuất cảnh cho đoàn bay tháng 6</a></h3>
                            <p class="text-gray-600 leading-relaxed line-clamp-3">
                                Buổi lễ diễn ra trong không khí ấm cúng, là lời động viên và chúc các bạn thực tập sinh lên đường may mắn, thành công...
                            </p>
                        </div>
                    </div>
                     <!-- News Card 3 -->
                     <div class="news-card bg-white rounded-lg overflow-hidden border">
                        <img src="https://images.unsplash.com/photo-1516975069153-a83b9e434316?q=80&w=800&auto=format&fit=crop" alt="Cẩm nang" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <p class="text-sm text-gray-500 mb-2">05 Tháng 6, 2025</p>
                            <h3 class="text-xl font-bold mb-3 text-gray-800 hover:text-blue-600"><a href="#">Cẩm nang học tiếng Nhật hiệu quả cho người mới bắt đầu</a></h3>
                            <p class="text-gray-600 leading-relaxed line-clamp-3">
                                Tiếng Nhật là chìa khóa quan trọng để hòa nhập. Bài viết này sẽ chia sẻ những phương pháp học tập hiệu quả đã được kiểm chứng...
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Partner Section -->
        <section class="py-12 bg-gray-100">
            <div class="container mx-auto px-4">
                <h2 class="text-2xl font-bold text-gray-700 text-center mb-8">Đối Tác Của Chúng Tôi</h2>
                <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12">
                    <img src="https://placehold.co/150x60/cccccc/999999?text=Partner+1" alt="Partner 1" class="h-12 grayscale hover:grayscale-0 transition duration-300">
                    <img src="https://placehold.co/150x60/cccccc/999999?text=Partner+2" alt="Partner 2" class="h-12 grayscale hover:grayscale-0 transition duration-300">
                    <img src="https://placehold.co/150x60/cccccc/999999?text=Partner+3" alt="Partner 3" class="h-12 grayscale hover:grayscale-0 transition duration-300">
                    <img src="https://placehold.co/150x60/cccccc/999999?text=Partner+4" alt="Partner 4" class="h-12 grayscale hover:grayscale-0 transition duration-300">
                    <img src="https://placehold.co/150x60/cccccc/999999?text=Partner+5" alt="Partner 5" class="h-12 grayscale hover:grayscale-0 transition duration-300">
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer id="contact" class="bg-gray-800 text-white pt-16 pb-8">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 mb-8">
                <!-- Column 1: About Company -->
                <div>
                    <h3 class="text-xl font-bold mb-4">CÔNG TY CP PHÁT TRIỂN NGUỒN LỰC THĂNG LONG DIH</h3>
                    <p class="text-gray-400 leading-relaxed">
                        Là đơn vị uy tín hàng đầu trong lĩnh vực xuất khẩu lao động, chúng tôi luôn nỗ lực vì tương lai của người lao động Việt Nam.
                    </p>
                    <div class="mt-4 flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-gray-700 hover:bg-blue-500 rounded-full flex items-center justify-center transition-colors"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="w-10 h-10 bg-gray-700 hover:bg-red-500 rounded-full flex items-center justify-center transition-colors"><i class="fab fa-youtube"></i></a>
                        <a href="#" class="w-10 h-10 bg-gray-700 hover:bg-blue-400 rounded-full flex items-center justify-center transition-colors"><i class="fab fa-twitter"></i></a>
                    </div>
                </div>
                <!-- Column 2: Quick Links -->
                <div>
                    <h3 class="text-xl font-bold mb-4">Liên Kết Nhanh</h3>
                    <ul class="space-y-2">
                        <li><a href="#about" class="text-gray-400 hover:text-white transition-colors">Về chúng tôi</a></li>
                        <li><a href="#orders" class="text-gray-400 hover:text-white transition-colors">Đơn hàng</a></li>
                        <li><a href="#news" class="text-gray-400 hover:text-white transition-colors">Tin tức</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">Chính sách bảo mật</a></li>
                    </ul>
                </div>
                <!-- Column 3: Contact Info -->
                <div>
                    <h3 class="text-xl font-bold mb-4">Thông Tin Liên Hệ</h3>
                    <ul class="space-y-3 text-gray-400">
                        <li class="flex items-start">
                            <i class="fas fa-map-marker-alt mt-1 mr-3 w-4 text-center"></i>
                            <span>61c, ngõ 66, tổ 5, Phố Ngọc Thụy, P. Ngọc Thuỵ, Q. Long Biên, Hà Nội</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone mr-3 w-4 text-center"></i>
                            <span>+84 329 439 665</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-envelope mr-3 w-4 text-center"></i>
                            <span>contact@thanglongdih.website</span>
                        </li>
                    </ul>
                </div>
                <!-- Column 4: Map -->
                <div>
                    <h3 class="text-xl font-bold mb-4">Vị Trí Văn Phòng</h3>
                     <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3723.655891392683!2d105.8643808759325!3d21.04642958731114!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3135a9b775e53381%3A0x35633342f2105151!2zNjZjIE5nLiA2NiBOZ-G7jWMgVGjhu6V5LCBOZ-G7jWMgVGjhu6V5LCBMb25nIEJpw6puLCBIw6AgTuG7mWksIFZp4buHdG5hbQ!5e0!3m2!1svi!2s!4v1718480983196!5m2!1svi!2s" width="100%" height="150" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" class="rounded-md"></iframe>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-6 text-center text-gray-500 text-sm">
                <p>&copy; 2025 THANGLONG DIH., JSC. All Rights Reserved. </p>
            </div>
        </div>
    </footer>
    
    <script>
        // JavaScript for mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        const mobileMenuLinks = mobileMenu.getElementsByTagName('a');
        for (let link of mobileMenuLinks) {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        }
    </script>
</body>
</html>
