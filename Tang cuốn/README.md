# Winding Drum (Tang Cuốn)

## 📖 Giới thiệu dự án
Dự án thiết kế, bóc tách và lắp ráp mô hình **Winding Drum** (Tang cuốn cáp). Quá trình thực hiện bao gồm việc dựng mô hình 3D (CAD) cho từng chi tiết riêng lẻ từ các hình chiếu 2D rời rạc, sau đó xây dựng bản lắp ráp hoàn chỉnh (Assembly) cùng hệ thống bản vẽ kỹ thuật đạt chuẩn. Mối ghép động giữa trục quay, bạc lót (đồng thau) và thân tang cuốn được thiết lập với dung sai tiêu chuẩn.

## 🛠 Phần mềm thiết kế
*   **Autodesk Inventor Professional:** Dựng hình 3D (Part), mô phỏng lắp ghép không gian (Assembly) và bóc tách cụm (Presentation).
*   **Autodesk AutoCAD:** Vẽ, hiệu chỉnh chi tiết và trình bày hệ thống bản vẽ 2D.

## 📂 Cấu trúc tệp tin (File Structure)
Dự án bao gồm các tệp dữ liệu sau:

### 1. Dữ liệu thiết kế 3D (Inventor CAD Files)
*   **Các file `.ipt`**: Chứa mô hình 3D của các chi tiết cấu thành (Tấm chân đế, Giá đỡ trục, Trục, Tang cuốn, Bạc lót). Các chi tiết tiêu chuẩn (Vis ISO 4018, Đệm phẳng) được gọi trực tiếp từ Content Center.
*   **File `.iam`**: Bản lắp ráp tổng thể, định vị chính xác vị trí và ràng buộc chuyển động giữa các cụm chi tiết (Ví dụ: Trục quay lồng không trong bạc lót).
*   **File `.ipn`**: Môi trường phân rã (Exploded view), biểu diễn thứ tự tháo lắp của cụm Tang cuốn.

### 2. Bản vẽ kỹ thuật 2D (Drawings & PDFs)
*   **File `.dwg`**: Bản vẽ Autocad 2D gốc chứa hệ thống hình chiếu, mặt cắt, kích thước và yêu cầu kỹ thuật chi tiết.
*   **Bản vẽ lắp ráp (Assembly Drawing).pdf**: Hình chiếu tổng thể và mặt cắt qua cụm lắp ráp, thể hiện rõ nguyên lý làm việc, hệ thống đường dẫn (Balloon) và bảng kê vật tư (BOM).
*   **Bản vẽ chi tiết (Detail Drawing).pdf**: Bản vẽ bóc tách từng chi tiết với đầy đủ dung sai kích thước, độ nhám bề mặt và dung sai hình học phục vụ gia công.

## 🚀 Hướng dẫn sử dụng
1. Tải toàn bộ thư mục dự án về máy tính.
2. Để xem chi tiết mô hình khối và kết cấu lắp ghép, hãy mở tệp `.iam` bằng Autodesk Inventor.
3. Để kiểm tra quy trình tháo lắp, mở tệp `.ipn` bằng Autodesk Inventor.
4. Có thể xem nhanh các bản vẽ kỹ thuật thông qua các tệp `.pdf` bằng bất kỳ trình duyệt hoặc phần mềm đọc PDF nào.

---
*Dự án được thiết kế và hoàn thiện bởi [Nguyễn Văn Huy Hoàng - Mehchatronics Undergraduate in HCMUT]*
