# Báo cáo bài tập 2
---------------------------------
Phần 1 - Phân tích: Tại sao trong Spring Boot, khi thêm các thư viện thuộc hệ sinh thái Spring, chúng ta thường không cần ghi rõ số phiên bản (version)?

- Bởi vì Spring Boot quản lý phiên bản tập trung thông qua cơ chế BOM (Bill of Materials). Thay vì phải tự ghi phiên bản cho từng thư viện, Spring Boot sẽ tự động tra cứu từ BOM để lấy ra các phiên bản tương thích nhất với nhau, giúp tránh xung đột và giảm thiểu sai sót.