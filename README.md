# 📐 MathMatrix - Nền Tảng Luyện Thi Toán Chuẩn GDPT Mới (2018)

> **MathMatrix** là hệ thống luyện thi môn Toán theo định dạng mới của Bộ Giáo dục & Đào tạo, tích hợp ma trận đề kiểm tra định kỳ (Giữa kỳ, Cuối kỳ các khối 10, 11, 12), đề thi thử Tốt nghiệp THPT, kỳ thi V-SAT và ĐGNL.

---

## 🌟 Điểm nổi bật & Tính năng chính

1. **Chuẩn hóa chương trình GDPT mới (2018):**
   - Loại bỏ hoàn toàn chuyên đề **Số phức**.
   - Bổ sung đầy đủ các chuyên đề nền tảng: **Dãy số, Cấp số cộng, Cấp số nhân**, **Hình học không gian cổ điển**, **Lượng giác & Phương trình lượng giác**.
2. **Cấu trúc đề thi định dạng 3 Phần của Bộ GD&ĐT:**
   - **Phần I:** Trắc nghiệm nhiều phương án lựa chọn (12 câu - mỗi câu 0.25đ).
   - **Phần II:** Trắc nghiệm Đúng - Sai (4 câu, mỗi câu 4 ý a, b, c, d).
     - *Đề Giữa kỳ / Cuối kỳ:* Mỗi ý đúng được **0.25 điểm** (chia đều).
     - *Đề Tốt nghiệp THPT:* Thang lũy tiến chính thức của Bộ (Đúng 1 ý: **0.1đ** | 2 ý: **0.25đ** | 3 ý: **0.5đ** | 4 ý: **1.0đ**).
   - **Phần III:** Trắc nghiệm Trả lời ngắn (6 câu - mỗi câu 0.5đ).
3. **Quy tắc Điểm trung bình (GPA):**
   - **Chỉ tính điểm trung bình (GPA) khi luyện đề Tốt nghiệp THPT**. Điểm thi Giữa kỳ, V-SAT lưu riêng vào lịch sử để không làm lệch đánh giá năng lực thi tốt nghiệp của học sinh.
4. **Phân quyền Giáo viên & Học sinh (RBAC):**
   - **Giáo viên:** Kiểm duyệt học sinh xin vào lớp, theo dõi tiến độ cả lớp, tạo phòng thi Online (Live Exam Room).
   - **Học sinh:** Được duyệt vào lớp sẽ xem được lý thuyết tóm tắt do giáo viên upload, tự luyện đề theo ma trận, xem lại lịch sử làm bài.
   - **Bảo mật:** Bảng xếp hạng lớp ẩn danh thông tin cá nhân của các bạn cùng lớp (`Nguyễn V** T***`).
5. **Chuẩn hiển thị công thức Toán:**
   - Sử dụng `\dfrac` thay cho `\frac` giúp phân số hiển thị to rõ, sắc nét, không bị co nhỏ trên mọi thiết bị.
   - Hỗ trợ hiển thị bảng biến thiên (BBT) và đồ thị toán học trực quan.

---

## 🚀 Hướng dẫn Đẩy lên GitHub & Kích hoạt GitHub Pages (Miễn phí)

### Bước 1: Khởi tạo Git & Commit trên máy tính
Mở PowerShell hoặc Terminal tại thư mục dự án và chạy:
```bash
git init
git add .
git commit -m "feat: initial commit MathMatrix GDPT 2018"
```

### Bước 2: Tạo Repository trên GitHub
1. Truy cập [github.com](https://github.com) và đăng nhập.
2. Bấm vào dấu `+` ở góc trên bên phải $\to$ chọn **New repository**.
3. Đặt tên Repository (ví dụ: `mathmatrix`).
4. Chọn chế độ **Public**, không cần tick chọn "Add a README file" (vì đã có sẵn).
5. Bấm **Create repository**.

### Bước 3: Đẩy mã nguồn lên GitHub
Sao chép URL của repository vừa tạo và chạy các lệnh sau (thay thế URL bằng link của bạn):
```bash
git branch -M main
git remote add origin https://github.com/tamtt48/mathmatrix.git
git push -u origin main
```

### Bước 4: Kích hoạt Website Online qua GitHub Pages
1. Trên giao diện Repository tại GitHub, vào mục **Settings** (biểu tượng bánh răng).
2. Ở thanh bên trái, chọn tab **Pages**.
3. Tại mục **Build and deployment** $\to$ **Branch**:
   - Chọn nhánh: `main`.
   - Chọn thư mục: `/ (root)`.
4. Bấm **Save**.
5. Sau 1 - 2 phút, GitHub sẽ cấp cho bạn một đường link website chạy trực tuyến miễn phí dạng:
   $$\text{https://tamtt48.github.io/mathmatrix/}$$

---

## 💻 Trải nghiệm Local (Trên máy tính cá nhân)

Không cần cài đặt phức tạp, bạn có thể:
- Click đúp trực tiếp vào file `index.html` để mở trên trình duyệt.
- Hoặc dùng lệnh Node.js nếu có sẵn:
  ```bash
  npx serve .
  ```

---

## 🎨 Bộ màu & Phong cách thiết kế
* **Phong cách:** Playful Neobrutalism (Viền mực than dập nổi, góc bo mềm mại, nền giấy thi chống mỏi mắt).
* **Bảng màu chủ đạo:**
  * Background: `#FEFBF1` (Giấy kem ấm)
  * Viền & Chữ: `#1E2342` (Deep Ink)
  * Primary: `#4F46E5` (Indigo Logic)
  * Action: `#FF6542` (Coral Accent)
  * Tốt nghiệp / GPA: `#F59E0B` (Trophy Gold)
  * Thành công: `#10B981` (Emerald)

---

## 📄 Bản quyền & Đóng góp
Dự án được xây dựng phục vụ cộng đồng giáo viên và học sinh ôn thi môn Toán theo chương trình GDPT 2018. Mọi đóng góp xin vui lòng tạo Issue hoặc Pull Request trên GitHub.
