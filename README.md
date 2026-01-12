BÁO CÁO THỰC HÀNH
Ứng dụng các công cụ kiểm thử phần mềm và mô hình ngôn ngữ lớn trong dự án nhóm
1. Mục tiêu báo cáo

Báo cáo này nhằm tổng hợp quá trình học tập, thực hành và áp dụng các công cụ kiểm thử phần mềm trong dự án nhóm. Sinh viên được trang bị kỹ năng:

Sử dụng các công cụ kiểm thử phổ biến trong thực tế.

Viết tài liệu, lập kế hoạch và báo cáo kiểm thử.

Vận dụng công cụ vào dự án nhóm một cách độc lập, không phụ thuộc hoàn toàn vào nội dung lý thuyết.

Tiếp cận xu hướng mới thông qua việc ứng dụng mô hình ngôn ngữ lớn (LLM) trong kiểm thử.

2. Phạm vi và nội dung thực hành
2.0. Bài tập thực hành tuần 1 – Làm quen GitHub và đánh giá giao diện người dùng

Mục tiêu:

Làm quen với việc quản lý mã nguồn và tài liệu bằng GitHub.

Tập thói quen ghi chép, báo cáo kết quả thực hành thông qua file README.md.

Trải nghiệm và đánh giá chất lượng giao diện người dùng (UI/UX) của một ứng dụng thực tế.

Nội dung thực hiện:

Sinh viên tạo một repository cá nhân / nhóm trên GitHub.

Tạo file README.md để làm báo cáo tổng hợp cho toàn bộ môn học.

Các sản phẩm của từng bài thực hành được lưu trữ và cập nhật thường xuyên trong repository.

Sinh viên truy cập website https://cantunsee.space/ để trải nghiệm kiểm tra khả năng quan sát và đánh giá giao diện.

Thực hiện chơi game nhằm đạt điểm số cao nhất có thể.

Chụp ảnh màn hình kết quả, trong đó có dấu hiệu cá nhân (ví dụ: tài khoản đã đăng nhập trên trình duyệt Chrome).

Đưa hình ảnh kết quả và mô tả ngắn gọn lên GitHub repository.

Mô tả kết quả minh họa:

Hình ảnh cho thấy kết quả trò chơi với số điểm đạt được là 5680, xếp hạng Beginner, thời gian hoàn thành khoảng 00:02:43.

Giao diện sử dụng phong cách pixel, màu sắc tương phản cao, giúp người dùng tập trung vào mục tiêu chính.

Có các nút chia sẻ kết quả (Post, Share) và phần đăng ký email để nhận thống kê.

Ý nghĩa bài thực hành:

Giúp sinh viên hiểu tầm quan trọng của trải nghiệm người dùng trong phần mềm.

Rèn luyện kỹ năng ghi nhận kết quả, chụp minh chứng và báo cáo.

Làm nền tảng cho các bài thực hành kiểm thử giao diện tự động ở các tuần sau.

2.1. Kiểm thử đơn vị – JUnit

Các bài thực hành tập trung vào các nhóm công cụ chính sau:

2.1. Kiểm thử đơn vị – JUnit

Mục tiêu:

Viết test case cho từng hàm / module nhỏ.

Kiểm tra tính đúng đắn của logic xử lý.

Nội dung thực hiện:

Tạo project Maven/Gradle.

Viết lớp test cho các lớp nghiệp vụ.

Sử dụng annotation: @Test, @BeforeEach, @AfterEach.

Đánh giá kết quả test thông qua báo cáo pass/fail.

Kết quả đạt được:

Hiểu cách xây dựng unit test tự động.

Giảm lỗi logic khi phát triển.

2.2. Kiểm thử tích hợp – Postman

Mục tiêu:

Kiểm tra hoạt động của các API.

Đảm bảo các module giao tiếp đúng dữ liệu.

Nội dung thực hiện:

Tạo collection request (GET, POST, PUT, DELETE).

Viết test script kiểm tra status code, dữ liệu trả về.

Chạy test theo collection.

Kết quả đạt được:

Đảm bảo API hoạt động ổn định.

Phát hiện lỗi tích hợp sớm.

2.3. Kiểm thử giao diện – Cypress / Playwright

Mục tiêu:

Tự động hóa thao tác người dùng trên giao diện web.

Nội dung thực hiện:

Viết kịch bản click, nhập liệu, kiểm tra hiển thị.

Chạy test trên trình duyệt.

Kết quả đạt được:

Phát hiện lỗi giao diện và luồng nghiệp vụ.

Tiết kiệm thời gian test thủ công.

2.4. Kiểm thử hiệu năng – JMeter / k6

Mục tiêu:

Đánh giá khả năng chịu tải của hệ thống.

Nội dung thực hiện:

Thiết lập số lượng người dùng ảo.

Đo thời gian phản hồi, throughput, error rate.

Kết quả đạt được:

Xác định điểm nghẽn hiệu năng.

Đề xuất phương án tối ưu.

2.5. Kiểm thử an toàn – OWASP ZAP Proxy

Mục tiêu:

Phát hiện lỗ hổng bảo mật cơ bản.

Nội dung thực hiện:

Quét tự động website/API.

Phân tích cảnh báo: XSS, SQL Injection, cấu hình sai.

Kết quả đạt được:

Nâng cao nhận thức về an toàn thông tin.

2.6. Kiểm thử tĩnh mã nguồn – SonarQube

Mục tiêu:

Đánh giá chất lượng mã nguồn.

Nội dung thực hiện:

Phân tích code: code smell, bug, security issue.

Theo dõi độ bao phủ test (coverage).

Kết quả đạt được:

Cải thiện chất lượng và khả năng bảo trì.

2.7. Quản lý lỗi – GitHub Issues / Jira

Mục tiêu:

Quản lý lỗi có hệ thống.

Nội dung thực hiện:

Tạo issue: mô tả lỗi, bước tái hiện, mức độ ưu tiên.

Theo dõi trạng thái xử lý.

Kết quả đạt được:

Nâng cao kỹ năng làm việc nhóm.

2.8. Viết tài liệu và báo cáo kiểm thử

Tài liệu gồm:

Test Plan

Test Case

Test Report

Bug Report

Kỹ năng đạt được:

Viết tài liệu chuyên nghiệp.

Trình bày rõ ràng, logic.

2.9. Ứng dụng mô hình ngôn ngữ lớn (LLM)

Mục tiêu:

Tìm hiểu công nghệ kiểm thử hiện đại.

Ứng dụng:

Sinh test case tự động.

Phân tích log lỗi.

Gợi ý kịch bản kiểm thử.

Lợi ích:

Tăng năng suất.

Hỗ trợ học tập nhanh.

3. Đánh giá chung

Ưu điểm:

Tiếp cận công cụ thực tế.

Phát triển kỹ năng làm việc nhóm.

Tư duy kiểm thử toàn diện.

Khó khăn:

Cài đặt môi trường phức tạp.

Thiếu kinh nghiệm ban đầu.

4. Kết luận

Chương trình thực hành giúp sinh viên nâng cao năng lực thực hành, hiểu quy trình kiểm thử phần mềm và làm quen với công nghệ hiện đại. Đây là nền tảng quan trọng cho công việc thực tế sau này.

5. Tài liệu tham khảo

JUnit Documentation

Postman Documentation

Cypress / Playwright

JMeter / k6

OWASP ZAP

SonarQube

GitHub / Jira
