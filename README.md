<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Công ty TNHH Xây Dựng Toàn Thắng</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .hero-section {
            background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://images.unsplash.com/photo-1541888946425-d81bb19240f5?q=80&w=2070&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
        }
        .scroll-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: none;
            z-index: 100;
        }
    </style>
</head>
<body class="bg-gray-50">

    <!-- Header -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center space-x-2">
                <!-- SVG Logo -->
                <svg width="40" height="40" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 2L2 7V21H22V7L12 2Z" fill="#1D4ED8"/>
                    <path d="M12 2L22 7V12L12 7V2Z" fill="#3B82F6"/>
                    <path d="M20 19H4V9L12 4L20 9V19Z" fill="white"/>
                    <path d="M9 18V14H15V18" fill="#3B82F6"/>
                    <text x="50%" y="65%" font-family="Inter, sans-serif" font-size="6" font-weight="bold" fill="#1D4ED8" text-anchor="middle">TT</text>
                </svg>
                <span class="text-xl font-bold text-gray-800">TOÀN THẮNG</span>
            </a>
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="text-gray-600 hover:text-blue-600">Trang chủ</a>
                <a href="#about" class="text-gray-600 hover:text-blue-600">Giới thiệu</a>
                <a href="#services" class="text-gray-600 hover:text-blue-600">Dịch vụ</a>
                <a href="#projects" class="text-gray-600 hover:text-blue-600">Dự án</a>
                <a href="#contact" class="text-gray-600 hover:text-blue-600">Liên hệ</a>
            </div>
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-gray-600 hover:text-blue-600 focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white">
            <a href="#home" class="block py-2 px-4 text-sm text-gray-600 hover:bg-blue-50">Trang chủ</a>
            <a href="#about" class="block py-2 px-4 text-sm text-gray-600 hover:bg-blue-50">Giới thiệu</a>
            <a href="#services" class="block py-2 px-4 text-sm text-gray-600 hover:bg-blue-50">Dịch vụ</a>
            <a href="#projects" class="block py-2 px-4 text-sm text-gray-600 hover:bg-blue-50">Dự án</a>
            <a href="#contact" class="block py-2 px-4 text-sm text-gray-600 hover:bg-blue-50">Liên hệ</a>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="home" class="hero-section h-[60vh] md:h-[80vh] flex items-center justify-center text-white">
            <div class="text-center px-4">
                <h1 class="text-4xl md:text-6xl font-extrabold mb-4 leading-tight">CÔNG TY TNHH XÂY DỰNG TOÀN THẮNG</h1>
                <p class="text-lg md:text-2xl font-light mb-8">Kiến tạo giá trị - Xây dựng tương lai</p>
                <a href="#contact" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-full transition duration-300 transform hover:scale-105">
                    Liên Hệ Tư Vấn
                </a>
            </div>
        </section>

        <!-- About Us Section -->
        <section id="about" class="py-20 bg-white">
            <div class="container mx-auto px-6">
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div>
                        <h2 class="text-3xl font-bold text-gray-800 mb-4">Về Chúng Tôi</h2>
                        <div class="w-24 h-1 bg-blue-600 mb-6"></div>
                        <p class="text-gray-600 mb-4">
                            <strong>Công ty TNHH Xây Dựng Toàn Thắng</strong>, với mã số doanh nghiệp 0800285643, tự hào là một trong những đơn vị uy tín trong lĩnh vực xây dựng tại Hải Dương và các tỉnh lân cận.
                        </p>
                        <p class="text-gray-600 mb-6">
                            Với phương châm "Uy tín - Chất lượng - Tiến độ", chúng tôi cam kết mang đến cho khách hàng những công trình bền vững, thẩm mỹ và tối ưu về chi phí. Đội ngũ kỹ sư, kiến trúc sư và công nhân của chúng tôi luôn làm việc với tinh thần trách nhiệm cao nhất.
                        </p>
                        <div class="flex space-x-8">
                            <div class="text-center">
                                <i class="fas fa-hard-hat text-4xl text-blue-600"></i>
                                <p class="mt-2 font-semibold">An Toàn Lao Động</p>
                            </div>
                            <div class="text-center">
                                <i class="fas fa-building-shield text-4xl text-blue-600"></i>
                                <p class="mt-2 font-semibold">Chất Lượng Vượt Trội</p>
                            </div>
                            <div class="text-center">
                                <i class="fas fa-handshake text-4xl text-blue-600"></i>
                                <p class="mt-2 font-semibold">Đối Tác Tin Cậy</p>
                            </div>
                        </div>
                    </div>
                    <div>
                        <img src="https://images.unsplash.com/photo-1579958223485-a411a51136c8?q=80&w=1887&auto=format&fit=crop" alt="Đội ngũ kỹ sư Toàn Thắng" class="rounded-lg shadow-xl w-full h-auto object-cover">
                    </div>
                </div>
            </div>
        </section>

        <!-- Services Section -->
        <section id="services" class="py-20">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Dịch Vụ Của Chúng Tôi</h2>
                <div class="w-24 h-1 bg-blue-600 mx-auto mb-12"></div>
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Service Item 1 -->
                    <div class="bg-white p-8 rounded-lg shadow-lg transform hover:-translate-y-2 transition duration-300">
                        <i class="fas fa-home-user text-5xl text-blue-600 mb-4"></i>
                        <h3 class="text-xl font-bold mb-2">Xây Dựng Dân Dụng</h3>
                        <p class="text-gray-600">Thi công nhà ở, biệt thự, chung cư với chất lượng và tiến độ đảm bảo.</p>
                    </div>
                    <!-- Service Item 2 -->
                    <div class="bg-white p-8 rounded-lg shadow-lg transform hover:-translate-y-2 transition duration-300">
                        <i class="fas fa-industry text-5xl text-blue-600 mb-4"></i>
                        <h3 class="text-xl font-bold mb-2">Xây Dựng Công Nghiệp</h3>
                        <p class="text-gray-600">Xây dựng nhà xưởng, kho bãi, khu công nghiệp theo tiêu chuẩn quốc tế.</p>
                    </div>
                    <!-- Service Item 3 -->
                    <div class="bg-white p-8 rounded-lg shadow-lg transform hover:-translate-y-2 transition duration-300">
                        <i class="fas fa-compass-drafting text-5xl text-blue-600 mb-4"></i>
                        <h3 class="text-xl font-bold mb-2">Thiết Kế Kiến Trúc</h3>
                        <p class="text-gray-600">Cung cấp các giải pháp thiết kế sáng tạo, tối ưu công năng sử dụng.</p>
                    </div>
                    <!-- Service Item 4 -->
                    <div class="bg-white p-8 rounded-lg shadow-lg transform hover:-translate-y-2 transition duration-300">
                        <i class="fas fa-screwdriver-wrench text-5xl text-blue-600 mb-4"></i>
                        <h3 class="text-xl font-bold mb-2">Sửa Chữa & Cải Tạo</h3>
                        <p class="text-gray-600">Nâng cấp, cải tạo các công trình cũ, mang lại diện mạo mới hiện đại.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-20 bg-white">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-gray-800 mb-4 text-center">Dự Án Tiêu Biểu</h2>
                <div class="w-24 h-1 bg-blue-600 mx-auto mb-12"></div>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Project Item 1 -->
                    <div class="group relative overflow-hidden rounded-lg shadow-lg">
                        <img src="https://images.unsplash.com/photo-1580587771525-78b9dba3b914?q=80&w=1974&auto=format&fit=crop" alt="Dự án biệt thự hiện đại" class="w-full h-72 object-cover transform group-hover:scale-110 transition duration-500">
                        <div class="absolute inset-0 bg-black bg-opacity-50 flex items-end p-6">
                            <h3 class="text-white text-xl font-bold">Biệt Thự Hiện Đại - Ecopark</h3>
                        </div>
                    </div>
                    <!-- Project Item 2 -->
                    <div class="group relative overflow-hidden rounded-lg shadow-lg">
                        <img src="https://images.unsplash.com/photo-1564013799919-ab600027ffc6?q=80&w=2070&auto=format&fit=crop" alt="Dự án nhà phố thương mại" class="w-full h-72 object-cover transform group-hover:scale-110 transition duration-500">
                        <div class="absolute inset-0 bg-black bg-opacity-50 flex items-end p-6">
                            <h3 class="text-white text-xl font-bold">Nhà Phố Thương Mại - Times City</h3>
                        </div>
                    </div>
                    <!-- Project Item 3 -->
                    <div class="group relative overflow-hidden rounded-lg shadow-lg">
                        <img src="https://images.unsplash.com/photo-1572095750849-d9c7cb387588?q=80&w=1964&auto=format&fit=crop" alt="Dự án nhà xưởng công nghiệp" class="w-full h-72 object-cover transform group-hover:scale-110 transition duration-500">
                        <div class="absolute inset-0 bg-black bg-opacity-50 flex items-end p-6">
                            <h3 class="text-white text-xl font-bold">Nhà Xưởng KCN Nam Sách</h3>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Contact Section -->
        <section id="contact" class="py-20 bg-gray-100">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-gray-800 mb-4 text-center">Liên Hệ Với Chúng Tôi</h2>
                <div class="w-24 h-1 bg-blue-600 mx-auto mb-12"></div>
                <div class="bg-white p-8 rounded-lg shadow-lg max-w-4xl mx-auto">
                   <div class="grid md:grid-cols-2 gap-8">
                       <div>
                           <h3 class="text-xl font-bold text-gray-800 mb-4">Thông tin liên hệ</h3>
                           <p class="text-gray-600 mb-4">
                               <strong>CÔNG TY TNHH XÂY DỰNG TOÀN THẮNG</strong>
                           </p>
                           <div class="flex items-start space-x-4 mb-4">
                               <i class="fas fa-map-marker-alt text-blue-600 mt-1"></i>
                               <p class="text-gray-600">Số nhà 150, Đường Ngô Quyền, Phường Tân Bình, Thành phố Hải Dương, Tỉnh Hải Dương, Việt Nam</p>
                           </div>
                           <div class="flex items-center space-x-4 mb-4">
                               <i class="fas fa-phone-alt text-blue-600"></i>
                               <a href="tel:+84904649333" class="text-gray-600 hover:text-blue-600">+84 904 649 333</a>
                           </div>
                           <div class="flex items-center space-x-4 mb-4">
                               <i class="fas fa-envelope text-blue-600"></i>
                               <a href="mailto:admin@thanglongdih.website" class="text-gray-600 hover:text-blue-600">admin@thanglongdih.website</a>
                           </div>
                           <div class="flex items-center space-x-4">
                               <i class="fas fa-globe text-blue-600"></i>
                               <a href="https://www.thanglongdih.website/" target="_blank" class="text-gray-600 hover:text-blue-600">www.thanglongdih.website</a>
                           </div>
                           <p class="text-gray-600 mt-4">
                               <strong>Người đại diện:</strong> Ông Đoàn Văn Ánh
                           </p>
                       </div>
                       <div>
                            <h3 class="text-xl font-bold text-gray-800 mb-4">Gửi yêu cầu tư vấn</h3>
                            <form action="#" method="POST">
                                <div class="mb-4">
                                    <input type="text" placeholder="Họ và Tên" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
                                </div>
                                <div class="mb-4">
                                    <input type="email" placeholder="Email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
                                </div>
                                <div class="mb-4">
                                    <input type="tel" placeholder="Số điện thoại" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500">
                                </div>
                                <div class="mb-4">
                                    <textarea placeholder="Nội dung yêu cầu" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                                </div>
                                <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-md transition duration-300">
                                    Gửi Yêu Cầu
                                </button>
                            </form>
                       </div>
                   </div>
                </div>
            </div>
        </section>

    </main>
    
    <!-- Footer -->
    <footer class="bg-gray-800 text-white">
        <div class="container mx-auto px-6 py-10">
            <div class="grid md:grid-cols-3 gap-8">
                <div>
                    <h4 class="text-lg font-bold mb-4">CÔNG TY TNHH XÂY DỰNG TOÀN THẮNG</h4>
                    <p class="text-gray-400">Đối tác tin cậy cho mọi công trình. Chúng tôi kiến tạo những không gian sống và làm việc chất lượng, bền vững với thời gian.</p>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Liên kết nhanh</h4>
                    <ul>
                        <li class="mb-2"><a href="#about" class="text-gray-400 hover:text-white">Giới thiệu</a></li>
                        <li class="mb-2"><a href="#services" class="text-gray-400 hover:text-white">Dịch vụ</a></li>
                        <li class="mb-2"><a href="#projects" class="text-gray-400 hover:text-white">Dự án</a></li>
                        <li class="mb-2"><a href="#contact" class="text-gray-400 hover:text-white">Liên hệ</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold mb-4">Theo dõi chúng tôi</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white text-2xl"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white text-2xl"><i class="fab fa-youtube"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white text-2xl"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-6 text-center text-gray-500 text-sm">
                <p>&copy; 2024 Công ty TNHH Xây Dựng Toàn Thắng. All Rights Reserved.</p>
            </div>
        </div>
    </footer>
    
    <!-- Scroll to Top Button -->
    <button id="scroll-to-top" class="scroll-to-top bg-blue-600 hover:bg-blue-700 text-white w-12 h-12 rounded-full shadow-lg flex items-center justify-center">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script>
        // JavaScript for mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                mobileMenu.classList.add('hidden'); // Hide mobile menu on click
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // JavaScript for scroll to top button
        const scrollToTopButton = document.getElementById('scroll-to-top');

        window.onscroll = function() {
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                scrollToTopButton.style.display = "block";
            } else {
                scrollToTopButton.style.display = "none";
            }
        };

        scrollToTopButton.addEventListener('click', () => {
            window.scrollTo({top: 0, behavior: 'smooth'});
        });
    </script>

</body>
</html>
