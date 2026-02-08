# vncalendar

---

## I. Giới thiệu

vncalendar là một thư viện Python phục vụ việc tính toán và tra cứu Lịch Vạn Sự Việt Nam, bao gồm chuyển đổi Âm – Dương lịch, Can Chi, ngày Hoàng Đạo / Hắc Đạo, các ngày kỵ truyền thống và 24 Tiết Khí.

Thư viện được xây dựng dựa trên:
- Lịch Vạn Sự truyền thống Việt Nam
- Thuật toán tính Âm lịch của Hồ Ngọc Đức

---

## II. Chức năng chính

### 2.1. Xử lý ngày tháng
- Kiểm tra năm nhuận
- Tính số ngày trong tháng, trong năm
- Cộng, trừ ngày
- Tính thứ trong tuần
- Tính tuổi chính xác theo ngày sinh

### 2.2. Chuyển đổi lịch
- Chuyển từ Dương lịch sang Âm lịch
- Chuyển từ Âm lịch sang Dương lịch
- Hỗ trợ tháng nhuận âm lịch

### 2.3. Can Chi
- Can Chi năm
- Can Chi tháng
- Can Chi ngày

### 2.4. Tốt – Xấu (Vạn Sự)
- Xác định ngày Hoàng Đạo / Hắc Đạo
- Kiểm tra các ngày xấu:
  - Tam Nương
  - Nguyệt Phá
  - Sát Chủ
  - Thọ Tử
  - Vãng Vong
  - Nguyệt Kỵ
  - Đại Bại
- Xác định Giờ Hoàng Đạo

### 2.5. Tiết Khí
- Xác định tiết khí của một ngày bất kỳ
- Tính thời điểm bắt đầu chính xác của từng tiết khí
- Danh sách đầy đủ 24 tiết khí trong năm

### 2.6. Thông tin Vạn Sự tổng hợp
- Trả về thông tin đầy đủ của một ngày theo Dương lịch hoặc Âm lịch

---

## III. Cấu trúc thư viện

### 3.1. Lớp Date
Xử lý các phép toán liên quan đến ngày tháng và JDN.

### 3.2. VanSu.SolarAndLunar
Chuyển đổi giữa lịch Dương và lịch Âm.

### 3.3. VanSu.CanChi
Tính Can Chi cho năm, tháng và ngày.

### 3.4. VanSu.TotXau
Xử lý ngày tốt – xấu, giờ Hoàng Đạo và các ngày kỵ.

### 3.5. VanSu.TietKhi
Tính toán 24 tiết khí dựa trên kinh độ Mặt Trời.

### 3.6. VanSu.getInfo
Tổng hợp toàn bộ thông tin Vạn Sự của một ngày.

---

## IV. Độ chính xác và phạm vi sử dụng

- Múi giờ mặc định: UTC+7 (Việt Nam)
- Thuật toán dựa trên thiên văn học
- Phù hợp cho:
  - Ứng dụng lịch
  - Công cụ tra cứu Vạn Sự
  - Nghiên cứu lịch truyền thống

---

## V. Lưu ý

- Thư viện không sử dụng thư viện bên thứ ba
- Kết quả mang tính tham khảo theo lịch truyền thống Việt Nam

---

## VI. Bản quyền và nguồn tham khảo

- Lịch Vạn Sự truyền thống (bản in tại TP. Hồ Chí Minh)
- Thuật toán Âm lịch: Hồ Ngọc Đức  
  https://lyso.vn/co-ban/thuat-toan-tinh-am-lich-ho-ngoc-duc-t2093/

---

## VII. Tác giả

Họ tên: Hoàng Đức Tùng  
Email: hoangdtung2021@gmail.com  
Facebook: https://www.facebook.com/hoangductung.keocon/
