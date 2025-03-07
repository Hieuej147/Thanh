<!DOCTYPE html>
<html lang="en">
<head>


    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DocFlow_NHT - Đánh giá</title>
    <style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Arial', sans-serif;
      }
      
      body {
        background-color: #f5f5f5;
      }
      
      .header {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 20px;
        background-color: #e6f0ff;
      }
      
      .logo {
        display: flex;
        align-items: center;
        font-weight: bold;
        font-size: 20px;
      }
      
      .search-bar {
        display: flex;
        align-items: center;
        background-color: #e0e0e0;
        border-radius: 20px;
        padding: 5px 15px;
        width: 300px;
      }
      
      .search-icon {
        margin-left: auto;
      }
      
      .nav-links {
        display: flex;
        gap: 20px;
      }
      
      .main-content {
        background-image: url('flowers-background.jpg');
        background-size: cover;
        min-height: 70vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        padding: 20px;
        position: relative;
      }
      
      .feedback-container {
        background-color: rgba(255, 255, 255, 0.9);
        padding: 30px;
        border-radius: 10px;
        text-align: center;
        width: 80%;
        max-width: 600px;
      }
      
      .thank-you-message {
        font-size: 24px;
        margin-bottom: 30px;
      }
      
      .rating-title {
        font-size: 28px;
        font-weight: bold;
        margin-bottom: 20px;
      }
      
      .stars {
        display: flex;
        justify-content: center;
        gap: 10px;
        margin-bottom: 30px;
      }
      
      .star {
        font-size: 36px;
        color: #ffd700;
      }
      
      .star:nth-child(4) {
        color: #ffa500;
      }
      
      .star:nth-child(5) {
        color: #ff4500;
      }
      
      .feedback-title {
        font-size: 28px;
        font-weight: bold;
        margin-bottom: 20px;
      }
      
      .feedback-textarea {
        width: 100%;
        height: 120px;
        padding: 10px;
        border-radius: 5px;
        border: 1px solid #ccc;
        margin-bottom: 20px;
        background-color: rgba(173, 216, 255, 0.3);
      }
      
      .footer {
        background-color: #e6f0ff;
        padding: 20px;
        display: flex;
        justify-content: space-around;
      }
      
      .footer-section {
        font-size: 14px;
      }
      
      .footer-title {
        font-weight: bold;
        margin-bottom: 5px;
      }
      
      .social-icons {
        display: flex;
        gap: 10px;
        margin-top: 10px;
      }
      
      .social-icon {
        width: 24px;
        height: 24px;
      }
      
      .profile-pic {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        object-fit: cover;
      }
    </style>






    <meta charset="utf-8"/>
    <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
    <title>Feedback Page</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
</head>
<body class="bg-blue-100 font-roboto">
    <header class="bg-blue-200 p-4 flex justify-between items-center">
        <div class="flex items-center">
            <i class="fas fa-book fa-2x"></i>
            <span class="ml-2 text-xl font-bold">DOCFLOW_NHT</span>
        </div>
        <div class="flex items-center space-x-4">
            <div class="relative">
                <input class="p-2 rounded-md" placeholder="Search" type="text"/>
                <button class="absolute right-0 top-0 mt-2 mr-2">
                    <i class="fas fa-search"></i>
                </button>
            </div>
            <button class="bg-blue-300 px-4 py-2 rounded-md">BOOKS</button>
            <button class="bg-blue-300 px-4 py-2 rounded-md">DOWNLOAD</button>
            <i class="fas fa-bell fa-lg"></i>
            <img alt="User profile picture" class="rounded-full" height="40" src="https://storage.googleapis.com/a1aa/image/YNX-DEab0wn1v68jd-JzWpIWQsO50zL9T0oTBf4jXAk.jpg" width="40"/>
        </div>
    </header>
    <main class="flex flex-col items-center py-8" style="background-image: url('https://placehold.co/1200x800'); background-size: cover;">
        <div class="bg-white bg-opacity-90 p-8 rounded-lg shadow-lg text-center max-w-lg">
            <p class="text-lg mb-4">Cảm ơn bạn vì đã đưa ra đánh giá, chúng tôi rất vui khi nhận được phản hồi từ bạn!</p>
            <h2 class="text-xl font-bold mb-2">ĐÁNH GIÁ</h2>
            <div class="flex justify-center mb-4">
                <i class="fas fa-star text-yellow-400 text-2xl"></i>
                <i class="fas fa-star text-yellow-400 text-2xl"></i>
                <i class="fas fa-star text-yellow-400 text-2xl"></i>
                <i class="fas fa-star text-yellow-400 text-2xl"></i>
                <i class="fas fa-star text-red-400 text-2xl"></i>
            </div>
            <h2 class="text-xl font-bold mb-2">PHẢN HỒI</h2>
            <div class="bg-blue-300 bg-opacity-50 p-4 rounded-lg">
                <textarea class="w-full p-2 rounded-md" placeholder="Write your feedback here..." rows="4"></textarea>
            </div>
        </div>
    </main>
    <footer class="bg-[#c3cfe2] p-4 mt-8">
  <div class="footer">
    <div class="footer-section">
      <div class="footer-title">LIÊN HỆ:</div>
      <div>BLOG.</div>
      <div>VỀ CHÚNG TÔI.</div>
    </div>
    
    <div class="footer-section">
      <div class="footer-title">TRỢ GIÚP:</div>
      <div>CÂU HỎI THƯỜNG GẶP.</div>
      <div>PHÒNG TIN TỨC.</div>
    </div>
    
    <div class="footer-section">
      <div class="footer-title">PHẢN HỒI.</div>
      <div>ĐÁNH GIÁ.</div>
      <div class="social-icons">
        <div>f</div>
        <div>♫</div>
        <div>G</div>
        <div>in</div>
      </div>
    </div>
    
    <div class="footer-section">
      <div class="footer-title">TRỢ GIÚP:</div>
      <div>CÂU HỎI THƯỜNG GẶP.</div>
      <div>PHÒNG TIN TỨC.</div>
    </div>
    
    <div class="footer-section">
      <div class="footer-title">ĐIỀU KHOẢN.</div>
      <div>CHÍNH SÁCH HỢP PHÁP</div>
      <div>COOKIES.</div>
    </div>
  </div>
    </footer>
</body>
</html>
