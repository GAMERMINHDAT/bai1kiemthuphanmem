Báo cáo thực hành chương 1
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

Báo cáo thực hành chương 2

1. Cài đặt lớp StudentAnalyzer

import java.util.List;

public class StudentAnalyzer {

    /**
     * Phân tích điểm số và trả về số lượng học sinh đạt loại Giỏi.
     * @param scores danh sách điểm số từ 0 đến 10
     * @return số học sinh đạt loại Giỏi (>= 8.0)
     */
    public int countExcellentStudents(List<Double> scores) {
        if (scores == null || scores.isEmpty()) {
            return 0;
        }

        int count = 0;

        for (Double score : scores) {
            if (score == null) continue;

            // Validate dữ liệu
            if (score >= 0 && score <= 10) {
                if (score >= 8.0) {
                    count++;
                }
            }
        }
        return count;
    }

    /**
     * Tính điểm trung bình hợp lệ (từ 0 đến 10)
     * @param scores danh sách điểm
     * @return điểm trung bình của các điểm hợp lệ
     */
    public double calculateValidAverage(List<Double> scores) {
        if (scores == null || scores.isEmpty()) {
            return 0;
        }

        double sum = 0;
        int validCount = 0;

        for (Double score : scores) {
            if (score == null) continue;

            if (score >= 0 && score <= 10) {
                sum += score;
                validCount++;
            }
        }

        if (validCount == 0) {
            return 0;
        }

        return sum / validCount;
    }
}

 2. Viết JUnit Test đầy đủ

import org.junit.jupiter.api.Test;
import static org.junit.jupiter.api.Assertions.*;
import java.util.Arrays;
import java.util.Collections;
import java.util.List;

public class StudentAnalyzerTest {

    StudentAnalyzer analyzer = new StudentAnalyzer();

    // =========================
    // Test countExcellentStudents
    // =========================

    @Test
    public void testCountExcellentStudents_NormalCase() {
        List<Double> scores = Arrays.asList(9.0, 8.5, 7.0, 11.0, -1.0);
        assertEquals(2, analyzer.countExcellentStudents(scores));
    }

    @Test
    public void testCountExcellentStudents_AllValid() {
        List<Double> scores = Arrays.asList(8.0, 8.2, 9.5, 10.0);
        assertEquals(4, analyzer.countExcellentStudents(scores));
    }

    @Test
    public void testCountExcellentStudents_EmptyList() {
        assertEquals(0, analyzer.countExcellentStudents(Collections.emptyList()));
    }

    @Test
    public void testCountExcellentStudents_BoundaryValues() {
        List<Double> scores = Arrays.asList(0.0, 10.0, 7.9);
        assertEquals(1, analyzer.countExcellentStudents(scores)); // chỉ có 10.0 >= 8
    }

    @Test
    public void testCountExcellentStudents_InvalidValuesOnly() {
        List<Double> scores = Arrays.asList(-5.0, 12.0, 20.0);
        assertEquals(0, analyzer.countExcellentStudents(scores));
    }

    // =========================
    // Test calculateValidAverage
    // =========================

    @Test
    public void testCalculateValidAverage_NormalCase() {
        List<Double> scores = Arrays.asList(9.0, 8.5, 7.0, 11.0, -1.0);
        // (9.0 + 8.5 + 7.0) / 3 = 8.166...
        assertEquals(8.17, analyzer.calculateValidAverage(scores), 0.01);
    }

    @Test
    public void testCalculateValidAverage_AllValid() {
        List<Double> scores = Arrays.asList(6.0, 8.0, 10.0);
        assertEquals(8.0, analyzer.calculateValidAverage(scores), 0.01);
    }

    @Test
    public void testCalculateValidAverage_EmptyList() {
        assertEquals(0, analyzer.calculateValidAverage(Collections.emptyList()), 0.01);
    }

    @Test
    public void testCalculateValidAverage_BoundaryValues() {
        List<Double> scores = Arrays.asList(0.0, 10.0);
        assertEquals(5.0, analyzer.calculateValidAverage(scores), 0.01);
    }

    @Test
    public void testCalculateValidAverage_InvalidValuesOnly() {
        List<Double> scores = Arrays.asList(-3.0, 15.0);
        assertEquals(0, analyzer.calculateValidAverage(scores), 0.01);
    }
}


 Bộ test này bao phủ:

- Trường hợp bình thường

- Biên (rỗng, 0, 10)

- Ngoại lệ (âm, >10)

3. Cấu trúc thư mục đề xuất
unit-test/
│
├── src/
│   └── StudentAnalyzer.java
│
├── test/
│   └── StudentAnalyzerTest.java
│
├── README.md
└── .gitignore

 4. Mẫu README.md

Bạn có thể copy chỉnh sửa:

# Student Analyzer - Unit Test with JUnit

##  Mục tiêu
- Viết chương trình Java phân tích điểm học sinh.
- Thực hành viết kiểm thử đơn vị bằng JUnit.
- Thực hành GitHub Issues và Commit workflow.

##  Chức năng
### 1. countExcellentStudents(List<Double> scores)
- Đếm số học sinh có điểm >= 8.0.
- Bỏ qua điểm < 0 hoặc > 10.
- Nếu danh sách rỗng → trả về 0.

### 2. calculateValidAverage(List<Double> scores)
- Tính trung bình các điểm hợp lệ (0–10).
- Nếu không có điểm hợp lệ → trả về 0.

##  Cấu trúc dự án


unit-test/
├── src/
├── test/
└── README.md


##  Cách chạy chương trình
- Mở project bằng IDE (IntelliJ / Eclipse).
- Đảm bảo đã thêm thư viện JUnit 5.
- Run file StudentAnalyzerTest.java.

##  Kiểm thử
- Kiểm thử các trường hợp:
  - Bình thường
  - Biên
  - Ngoại lệ

##  Sinh viên thực hiện
- Họ tên:Nguyễn Minh Đạt
- MSSV:BIT230085
- Lớp:23IT5
