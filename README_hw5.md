# INS3064 - Introduction to SQL
## Homework 5: University Queries

- **Họ và tên:** Đỗ Thùy Linh
- **Mã sinh viên:** 24071506
- **Môn học:** INS3064 (Hệ thống thông tin quản lý)

---

### 📂 Cấu trúc nộp bài Homework 5
- `homework_w5.zip`: File nén chứa mã nguồn SQL của bài tập.
  - `university_queries.sql`: Gói gọn 10 câu truy vấn SQL hoàn chỉnh tương tác với cơ sở dữ liệu `university_db` từ Homework 4. Mỗi câu lệnh đều có đầy đủ comment mô tả mục đích và kết quả mẫu (Expected Output) dạng bảng.

---

### 🎥 Video Demo Presentation
Video trình bày trực tiếp thao tác chạy truy vấn SQL, giải thích code và kiểm tra kết quả thực tế trên phpMyAdmin (OBS Recording):
- **Link Video YouTube:** https://youtu.be/sMaLgfHRn1Q
- **Playlist môn học:** `INS3064 — Homework — Đỗ Thùy Linh`

---

### 📝 Danh sách 10 câu truy vấn trong `university_queries.sql`
1. **Basic SELECT:** Lấy toàn bộ danh sách sinh viên (`students`).
2. **WHERE với toán tử so sánh:** Lọc sinh viên có điểm GPA lớn hơn 3.50.
3. **WHERE với AND/OR:** Lọc học phần theo khoa và điều kiện số tín chỉ.
4. **ORDER BY:** Sắp xếp danh sách sinh viên theo thứ tự bảng chữ cái họ tên (`full_name ASC`).
5. **LIMIT:** Giới hạn hiển thị tốp 3 sinh viên có điểm GPA cao nhất.
6. **LIKE:** Tìm kiếm học phần theo từ khóa trong tiêu đề (`title LIKE '%Cơ sở%'`).
7. **Aggregate — SUM:** Tính tổng số tín chỉ của tất cả các học phần trong bảng `courses`.
8. **Aggregate với GROUP BY + HAVING:** Nhóm các học phần theo khoa và lọc các khoa có nhiều hơn 1 học phần.
9. **JOIN (2 bảng):** Kết hợp bảng `courses` và `instructors` để hiển thị tên môn học kèm theo họ tên giảng viên phụ trách.
10. **JOIN (3 bảng trở lên):** Kết nối bảng `enrollments`, `students`, và `courses` để liệt kê sinh viên đã đăng ký học phần nào và đạt điểm số bao nhiêu.
