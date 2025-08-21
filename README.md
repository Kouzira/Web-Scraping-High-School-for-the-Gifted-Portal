# Web-Scraping High-School for the Gifted Portal

##  Mục đích dự án
Dự án này nhằm tự động thu thập dữ liệu từ cổng thông tin của trường trung học chuyên (High-School for the Gifted). Mục tiêu có thể là:
 Trích xuất điểm chuyên môn, bảng xếp hạng học sinh.
 Định dạng và lưu lại dữ liệu dưới dạng Excel hoặc báo cáo để xử lý tiếp.

##  Tính năng chính
 **Thu thập dữ liệu tự động:** Sử dụng Jupyter Notebook để điều khiển quá trình scraping dễ dàng.
 **Xử lý báo cáo:** Kết quả được lưu lại trong các file Excel như:
    `Combined_Report.xlsx`
    `Combined_Report_Cleaned.xlsx`
    `Pass_Report.xlsx`
    `Failed_Report.xlsx`
    `Specialized_Scores.xlsx`
    `Specialized_Scores_By_Subject.xlsx`
 **Quản lý các trường hợp lỗi:** Có sẵn file `Failed_Report.xlsx` để ghi nhận các trường hợp không thu thập dữ liệu thành công.
 **Tích hợp ChromeDriver:** Chuẩn bị sẵn thư mục `chromedriver-win64` hỗ trợ chạy Selenium nếu cần điều khiển trình duyệt tự động.

##  Cài đặt và chuẩn bị môi trường
1. Clone repository:
   ```bash
   git clone https://github.com/Kouzira/Web-Scraping-High-School-for-the-Gifted-Portal.git
   cd Web-Scraping-High-School-for-the-Gifted-Portal
   ```
2. Thiết lập môi trường Python:
   ```bash
    pip install -r requirements.txt
   ```
