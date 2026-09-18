# **BÀI 1: TỔNG QUAN VỀ MÁY TÍNH VÀ LẬP TRÌNH**

## **I. NỘI DUNG**
* Hệ thống máy tính
* Logic chương trình
* Chu trình phát triển chương trình
* Mã giả, lưu đồ
* Môi trường lập trình và người dùng
* Sự phát triển của các mô hình lập trình

---

## **II. HỆ THỐNG MÁY TÍNH**
Hệ thống máy tính là sự kết hợp các thành phần cần thiết để xử lý và lưu trữ dữ liệu.
* **Phần cứng (hardware):** Các thiết bị (devices) liên quan đến máy tính.
* **Phần mềm (software):**
  * Các chỉ thị máy tính (computer instruction) ra lệnh cho phần cứng biết phải làm gì.
  * Chương trình (program) - là tập hợp các chỉ thị.
  * Phần mềm ứng dụng (application software).
  * Phần mềm hệ thống (system software).

### **1/ CÁC HOẠT ĐỘNG CHÍNH**
* **Nhập (input):** Các mục dữ liệu (văn bản, số, hình ảnh, âm thanh, chuyển động vuốt chuột, ...) được đưa vào hệ thống máy tính và lưu trong bộ nhớ, nơi chúng được xử lý.
* **Xử lý (processing):** Thực hiện các phép tính và phép so sánh với đầu vào bởi bộ xử lý trung tâm (CPU).
* **Xuất (output):** Thông tin thu được sau khi xử lý đầu vào được gửi đến máy in, màn hình, hoặc các thiết bị lưu trữ để mọi người có thể xem, diễn giải và sử dụng.

### **2/ BỘ NHỚ MÁY TÍNH**
Bộ nhớ máy tính (computer memory) là nơi lưu trữ các chương trình và các mục dữ liệu của máy tính.
* **Bộ nhớ trong (vùng lưu trữ tạm thời):**
  * Bộ nhớ truy cập ngẫu nhiên (RAM) lưu trữ các chương trình đang chạy và các mục dữ liệu đang được sử dụng.
  * Nội dung chứa trên đó bị mất khi máy tính tắt.
* **Bộ nhớ ngoài (vùng lưu trữ lâu dài):**
  * Thiết bị lưu trữ vĩnh viễn – như ổ cứng, thẻ nhớ.
  * Nội dung chứa trên đó không bị mất khi máy tính tắt.

---

## **III. CHƯƠNG TRÌNH MÁY TÍNH**
* **Logic của chương trình máy tính:** Chuỗi các chỉ thị được viết theo một trình tự xác định nhằm dẫn đến kết xuất chính xác.
* **Mã chương trình (program code) hay mã nguồn (source code):** Tập hợp các chỉ thị hay các câu lệnh của một chương trình được viết bằng ngôn ngữ lập trình.
* **Ngôn ngữ lập trình (programming language):** Dùng để viết mã cho chương trình máy tính.
* **Lỗi trong lập trình:**
  * **Lỗi cú pháp (syntax error):** Làm cho mã chương trình không thể biên dịch hoàn chỉnh.
  * **Lỗi logic (logic error):** Làm cho kết xuất của chương trình không chính xác.

---

## **IV. CHU TRÌNH PHÁT TRIỂN CHƯƠNG TRÌNH**
Gồm 7 bước thực hiện tuần hoàn:
1. **Tìm hiểu vấn đề:** Hiểu và xác định yêu cầu của người dùng.
2. **Lập logic chương trình:** Xác định các hoạt động và trình tự của chúng để dẫn đến giải pháp cho vấn đề.
3. **Viết mã:** Sử dụng ngôn ngữ lập trình để viết mã nguồn.
4. **Dịch mã:** Sử dụng trình dịch để chuyển mã nguồn thành ngôn ngữ máy.
5. **Kiểm thử:** Chạy chương trình với nhiều mẫu đầu vào để kiểm tra tính chính xác của kết xuất.
6. **Đóng gói:** Gom các tập tin chương trình thành một gói để dễ dàng cài đặt, phân phối.
7. **Bảo trì:** Duy trì hoặc thực hiện các thay đổi sau khi chương trình được sử dụng.

---

## **V. MÃ GIẢ, LƯU ĐỒ**
* **Mã giả (pseudocode):**
  * Trình bày logic chương trình dạng văn bản với sự kết hợp của ngôn ngữ tự nhiên và các cấu trúc lập trình đơn giản.
  * Giúp logic chương trình dễ hiểu, dễ chuyển đổi sang ngôn ngữ lập trình.
* **Lưu đồ / Sơ đồ khối (flowchart):**
  * Thể hiện logic chương trình dạng hình ảnh với các hình khối và mũi tên.
  * Giúp logic chương trình được trực quan hóa, dễ theo dõi và phân tích.

### **1/ TỪ KHÓA VÀ KÝ HIỆU (Mã giả - Lưu đồ)**
* **Bắt đầu, kết thúc:** `start`, `stop`, `begin`, `end` (Lưu đồ: Hình oval).
* **Khai báo, khởi tạo biến:** `declarations`, `<kiểu> <tên biến>` (Lưu đồ: Hình chữ nhật hoặc biểu tượng chuẩn bị).
* **Nhập:** `input <tên biến>`, `get`, `read` (Lưu đồ: Hình bình hành).
* **Xuất:** `output <tên biến> [<hằng>]`, `print`, `write` (Lưu đồ: Hình bình hành).
* **Xử lý:** `<biểu thức gán>`, `set <biểu thức gán>`, `compute`, `calculate` (Lưu đồ: Hình chữ nhật).
* **Điều hướng:** (Lưu đồ: Các mũi tên nối).
<img width="1362" height="787" alt="image" src="https://github.com/user-attachments/assets/1529c006-1294-4623-9ff0-3c0bf2b7ff8b" />


---

## **VI. MÔI TRƯỜNG LẬP TRÌNH VÀ NGƯỜI DÙNG**
Môi trường lập trình và người dùng là các công cụ và cách thức cho phép lập trình viên viết chương trình và người dùng thực thi chương trình.
* **Lập logic chương trình:** Viết mã giả, vẽ lưu đồ bằng tay hoặc phần mềm.
* **Viết mã chương trình:** Bằng các trình soạn thảo.
* **Thực thi chương trình:** Với đầu vào từ nhiều thiết bị.
* **Kết xuất của chương trình:** Với đầu ra là văn bản, hình ảnh, âm thanh, ...

### **1/ MÔI TRƯỜNG LẬP TRÌNH**
* **Môi trường phát triển tích hợp (IDE):**
  * Cung cấp trình soạn thảo mã nguồn, trình biên dịch, trình gỡ lỗi và các công cụ khác như quản lý phiên bản, thiết kế giao diện đồ họa người dùng.
  * Ví dụ: Visual Studio, Code::Blocks, Eclipse, ...
* **Trình soạn thảo mã nguồn của IDE có nhiều tính năng:**
  * Làm nổi bật các thành phần của ngôn ngữ lập trình với các màu khác nhau.
  * Làm nổi bật các lỗi cú pháp.
  * Hoàn thành câu lệnh tự động.
  * Thi hành từng câu lệnh.

### **2/ MÔI TRƯỜNG NGƯỜI DÙNG**
* **Môi trường dòng lệnh:** Người dùng tương tác với chương trình thông qua cửa sổ dòng lệnh của hệ điều hành.
* **Môi trường giao diện đồ họa người dùng (GUI):** Người dùng tương tác với chương trình thông qua cửa sổ giao diện của chương trình.

---

## **VII. SỰ PHÁT TRIỂN CỦA CÁC MÔ HÌNH LẬP TRÌNH**
Chương trình máy tính hiện đại được viết từ những năm 1940.
* **Các ngôn ngữ lập trình cấp thấp (Ngôn ngữ máy, Hợp ngữ):** Làm việc với bộ nhớ thông qua địa chỉ, phải ghi nhớ các mã khó liên quan đến kiến trúc máy tính.
* **Các ngôn ngữ lập trình cấp cao (C, C++, Java, Python):** Làm việc với bộ nhớ thông qua tên biến, tựa ngôn ngữ tự nhiên dễ học và dễ viết.
* **Lập trình hướng thủ tục (procedural programming):** Tập trung vào các thủ tục tương ứng với các nhiệm vụ của chương trình.
* **Lập trình hướng đối tượng (object-oriented programming):** Tập trung vào các đối tượng của chương trình.
