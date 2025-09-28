# Thuật Toán Thay Thế Khung Trang

## 📌 Giới thiệu
Đề tài này mô phỏng **ba thuật toán thay thế khung trang cơ bản** trong Hệ điều hành:
- **FIFO (First In First Out)**: Trang vào trước sẽ bị thay thế trước.
- **LRU (Least Recently Used)**: Trang ít được sử dụng gần đây nhất sẽ bị thay thế.
- **Optimal (MIN)**: Thay thế trang mà sẽ lâu nhất mới được sử dụng lại trong tương lai.

Chương trình được viết bằng **C++**, chạy tốt trên Visual Studio hoặc VS Code.

---

## ⚙️ Cách chạy chương trình
### 1. Clone project
```bash
git clone https://github.com/quyennc142-hub/SATANAS-THU-T-TO-N-THAY-TH-KHUNG-TRANG1.git
cd SATANAS-THU-T-TO-N-THAY-TH-KHUNG-TRANG1
```

### 2. Compile & Run (VS Code với MinGW)
```bash
g++ page_replacement.cpp -o page_replacement
./page_replacement
```

### 3. Hoặc chạy trên Visual Studio
- Mở `page_replacement.cpp` trong Visual Studio.  
- Nhấn **F5** để chạy.  

---

## 📥 Input
- Số lượng trang tham chiếu.  
- Dãy trang (page reference string).  
- Số khung trang (capacity).  

Ví dụ:
```
Nhập số lượng trang tham chiếu: 13
Nhập dãy trang: 7 0 1 2 0 3 0 4 2 3 0 3 2
Nhập số khung trang: 3
```

## 📤 Output
- Trạng thái khung trang sau mỗi lần thay thế.  
- Tổng số **page faults** cho từng thuật toán.  

Ví dụ:
```
=== FIFO ===
  7  .  .
  7  0  .
  7  0  1
  2  0  1
...
Tổng số Page Faults (FIFO): 9
```

---

## 📊 So sánh thuật toán
- **FIFO**: đơn giản, nhưng có thể gặp hiện tượng Belady’s anomaly.  
- **LRU**: hiệu quả hơn FIFO, nhưng cần thêm chi phí quản lý.  
- **Optimal**: ít page faults nhất, nhưng chỉ dùng để mô phỏng vì phải biết trước dãy tham chiếu.  

---

## 👨‍💻 Thành viên nhóm SATANAS
- Ngô Chí Quyển (Trưởng nhóm)  
- Đoàn Hoàng Hảo  
- Trần Trọng Nghĩa  
- Nguyễn Hải Duy  

*(Trong báo cáo Word sẽ có bảng phân công chi tiết hơn)*

---

## 🔗 Link
- [GitHub Repository](https://github.com/quyennc142-hub/SATANAS-THU-T-TO-N-THAY-TH-KHUNG-TRANG1)  
- [Video Demo](#) (nếu có)
