<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Z-Freelan.com</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4897ff;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #3a7acc;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: 500;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        .section h2 {
            color: #333;
            font-weight: 700;
        }
        .feature-grid, .freelancer-grid, .job-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .card {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .card h3 {
            margin-top: 0;
            color: #4897ff;
            font-weight: 500;
        }
        .form-section {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
        }
        .form-section input, .form-section textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-family: 'Roboto', sans-serif;
        }
        .form-section button {
            background-color: #4897ff;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-family: 'Roboto', sans-serif;
            font-weight: 500;
        }
        .form-section button:hover {
            background-color: #3a7acc;
        }
        footer {
            background-color: #4897ff;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .chat-support {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #4897ff;
            color: white;
            padding: 10px 20px;
            border-radius: 20px;
            cursor: pointer;
            font-family: 'Roboto', sans-serif;
            font-weight: 500;
        }
    </style>
</head>
<body>
    <header>
        <h1>Z-Freelan.com</h1>
        <p>Beta version</p>
    </header>

    <nav>
        <a href="#home">Trang chủ</a>
        <a href="#projects">Dự án</a>
        <a href="#freelancers">Freelancer</a>
        <a href="#business">Doanh nghiệp</a>
        <a href="#contracts">Hợp đồng</a>
        <a href="#login">Đăng nhập</a>
        <a href="#apply">Ứng tuyển</a>
        <a href="#progress">Tiến độ & Thu nhập</a>
        <a href="#community">Cộng đồng</a>
        <a href="#profile">Cá nhân</a>
    </nav>

    <div class="container">
        <div class="section" id="home">
            <h2>Nền tảng Freelancer cho Gen Z và sinh viên</h2>
            <p>Hợp tác, kiếm tiền, ký hợp đồng & nhận thanh toán chỉ trong vài cú nhấp chuột</p>
            <div class="feature-grid">
                <div class="card">
                    <h3>Giao diện hiện đại</h3>
                    <p>Phong cách trẻ trung, trực quan, dễ sử dụng cho Gen Z.</p>
                </div>
                <div class="card">
                    <h3>Hợp đồng điện tử</h3>
                    <p>Tạo và ký hợp đồng chỉ trong 1 phút, xác thực bằng OTP và lưu trữ an toàn.</p>
                </div>
                <div class="card">
                    <h3>Escrow trung gian</h3>
                    <p>Bảo vệ cả đôi bên, chỉ giải ngân khi dự án hoàn thành đúng yêu cầu.</p>
                </div>
            </div>
        </div>

        <div class="section" id="projects">
            <h2>Dự án nổi bật</h2>
            <div class="job-grid">
                <div class="card">
                    <h3>Thiết kế CV cá nhân cho sinh viên năm 1</h3>
                    <p>Thiết kế sáng tạo, giúp nổi bật kỹ năng mềm và hoạt động ngoại khóa.</p>
                </div>
                <div class="card">
                    <h3>Thiết kế poster sự kiện cho CLB Đại học</h3>
                    <p>Dành cho freelancer sinh viên năm 2 yêu thích thiết kế và tổ chức sự kiện.</p>
                </div>
                <div class="card">
                    <h3>Viết bài blog chia sẻ kinh nghiệm học tập</h3>
                    <p>Dự án dành cho sinh viên năm 3 chuyên ngành marketing hoặc truyền thông.</p>
                </div>
                <div class="card">
                    <h3>Phát triển website portfolio cá nhân</h3>
                    <p>Phù hợp sinh viên năm 4 ngành CNTT đang chuẩn bị ra trường.</p>
                </div>
            </div>
        </div>

        <div class="section" id="freelancers">
            <h2>Freelancer tiêu biểu</h2>
            <div class="freelancer-grid">
                <div class="card">
                    <h3>Nguyễn Hoàng Long - Năm 1</h3>
                    <p>Chuyên viết content TikTok, slogan ngắn, phong cách Gen Z cá tính.</p>
                </div>
                <div class="card">
                    <h3>Trần Thị Mai - Năm 2</h3>
                    <p>Thiết kế banner, poster và infographics bằng Canva, Photoshop.</p>
                </div>
                <div class="card">
                    <h3>Phạm Quang Duy - Năm 3</h3>
                    <p>Lập trình web (HTML/CSS/JS), từng làm việc với dự án landing page startup.</p>
                </div>
                <div class="card">
                    <h3>Lê Minh Châu - Năm 4</h3>
                    <p>Viết kịch bản, video voiceover, MC online - từng hợp tác với 3 kênh Youtube.</p>
                </div>
            </div>
        </div>

        <div class="section" id="apply">
            <h2>Ứng tuyển công việc</h2>
            <div class="form-section">
                <input type="text" placeholder="Họ và tên">
                <input type="email" placeholder="Email">
                <input type="text" placeholder="Link portfolio">
                <textarea placeholder="Giới thiệu ngắn về bản thân"></textarea>
                <button>Gửi ứng tuyển</button>
                <p style="color: green; display: none;">✅ Ứng tuyển thành công! Chúng tôi sẽ liên hệ sớm nhất.</p>
            </div>
        </div>

        <div class="section" id="login">
            <h2>Đăng nhập tài khoản</h2>
            <div class="form-section">
                <input type="email" placeholder="Email">
                <input type="password" placeholder="Mật khẩu">
                <button>Đăng nhập</button>
            </div>
        </div>

        <div class="section" id="progress">
            <h2>Theo dõi tiến độ & thu nhập</h2>
            <div class="job-grid">
                <div class="card">
                    <h3>Dự án: Viết bài cho Highlands Coffee</h3>
                    <p>Trạng thái: Đang thực hiện (75%)</p>
                    <p>Deadline: 25/07/2025</p>
                    <p>Thu nhập dự kiến: 2.500.000 VNĐ</p>
                </div>
                <div class="card">
                    <h3>Dự án: Dựng video Big C</h3>
                    <p>Trạng thái: Đã hoàn thành ✅</p>
                    <p>Thanh toán: Đã nhận 100% - 3.000.000 VNĐ</p>
                    <p>Ngày hoàn thành: 12/07/2025</p>
                </div>
                <div class="card">
                    <h3>Dự án: Thiết kế Landing Page</h3>
                    <p>Trạng thái: Đang chờ phản hồi từ khách hàng...</p>
                    <p>Thu nhập dự kiến: 4.000.000 VNĐ</p>
                </div>
            </div>
        </div>

        <div class="section" id="contracts">
            <h2>Thông tin Hợp đồng điện tử</h2>
            <div class="card">
                <p><strong>Người thuê:</strong> Nguyễn Văn A</p>
                <p><strong>Freelancer:</strong> Trần Thị B</p>
                <p><strong>Dịch vụ:</strong> Thiết kế banner quảng cáo</p>
                <p><strong>Giá trị:</strong> 2.000.000 VNĐ</p>
                <p><strong>Thanh toán:</strong> Qua escrow, giải ngân khi hoàn thành và được xác nhận.</p>
                <button>Ký hợp đồng ngay</button>
            </div>
        </div>

        <div class="section" id="community">
            <h2>Cộng đồng Z-Freelan</h2>
            <div class="feature-grid">
                <div class="card">
                    <h3>Chia sẻ kinh nghiệm freelance</h3>
                    <p>Cùng nhau học hỏi và chia sẻ trải nghiệm làm việc thực tế, những lần deal giá, trễ deadline và cách vượt qua.</p>
                </div>
                <div class="card">
                    <h3>Hỏi đáp & hỗ trợ</h3>
                    <p>Đặt câu hỏi, trao đổi kiến thức, chia sẻ tài nguyên giữa các thành viên cộng đồng freelancer trẻ.</p>
                </div>
                <div class="card">
                    <h3>Cuộc thi & sự kiện cộng đồng</h3>
                    <p>Tham gia mini game, talkshow trực tuyến và các buổi kết nối giữa freelancer và doanh nghiệp.</p>
                </div>
            </div>
        </div>

        <div class="section" id="profile">
            <h2>Thông tin cá nhân</h2>
            <div class="card">
                <p><strong>Họ và tên:</strong> Nguyễn Văn Freelancer</p>
                <p><strong>Email:</strong> freelancer@email.com</p>
                <p><strong>Kỹ năng:</strong> Thiết kế đồ họa, viết nội dung, dựng video</p>
                <p><strong>Giới thiệu:</strong> Sinh viên năm 3 chuyên ngành Truyền thông, yêu thích làm việc tự do và luôn tìm kiếm các dự án sáng tạo.</p>
                <p><strong>Liên kết mạng xã hội:</strong> <a href="#">Facebook</a> | <a href="#">LinkedIn</a> | <a href="#">Github</a></p>
                <button>Chỉnh sửa thông tin</button>
            </div>
        </div>
    </div>

    <div class="chat-support">💬 Hỗ trợ</div>

    <footer>
        <p>© 2025 Z-Freelan.com — Nền tảng freelancer dành riêng cho Gen Z & sinh viên Việt</p>
    </footer>
</body>
</html>
