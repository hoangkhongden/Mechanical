# Cylinder Elbow Steam Engine

## 📖 Giới thiệu dự án
Đây là dự án thiết kế, lắp ráp và mô phỏng mô hình **Cylinder Elbow Steam Engine** (Động cơ hơi nước xi-lanh khuỷu). Dự án bao gồm toàn bộ quá trình từ dựng hình 3D từng chi tiết (Part), lắp ráp cụm máy (Assembly), mô phỏng chuyển động động học (Simulation), mô phỏng phân rã tháo lắp (Presentation), và xuất bản vẽ kỹ thuật 2D tiêu chuẩn.

## 🛠 Phần mềm thiết kế
*   **Autodesk Inventor Professional:** Dựng hình khối 3D, Lắp ráp, Mô phỏng, Phân rã.
*   **Autodesk AutoCAD:** Đọc và tinh chỉnh không gian bản vẽ kỹ thuật 2D.

## 📂 Cấu trúc tệp tin (File Structure)
Dự án này bao gồm các nhóm dữ liệu sau:

### 1. Dữ liệu thiết kế 3D (Inventor CAD Files)
*   **Các file `.ipt`**: Bao gồm toàn bộ chi tiết đơn lẻ của mô hình (Base, Flywheel, Piston, Cylinder Tube, Shaft, v.v.).
*   **File `.iam`**: Bản lắp ráp tổng thể (Assembly) liên kết các chi tiết và thiết lập hệ thống chuyển động.
*   **File `.ipn`**: Môi trường trình diễn (Presentation) chứa không gian phân rã chi tiết (Exploded view).

### 2. Bản vẽ kỹ thuật 2D (Drawings & PDFs)
*   **File `.dwg`**: Bản vẽ 2D gốc chứa hệ thống kích thước.
*   **Bản vẽ lắp ráp (Assembly Drawing).pdf**: Bản vẽ thể hiện hình chiếu tổng thể, mặt cắt cụm, đánh bóng (Balloon) và bảng kê vật tư (BOM) để dễ dàng xem trước mà không cần cài phần mềm CAD.
*   **Bản vẽ chi tiết (Detail Drawing).pdf**: Bản vẽ bóc tách ghi đầy đủ kích thước phục vụ gia công chế tạo.

### 3. Mô phỏng & Trình diễn (Simulations)
*   **Video Mô phỏng hoạt động**: Ghi lại chu trình vận hành động học thực tế (Piston trượt tịnh tiến, Bánh đà quay).
*   **Video Bóc tách tháo lắp**: Quá trình phân rã (Exploded view) từ cụm máy hoàn chỉnh ra từng chi tiết rời để hướng dẫn lắp ráp.

## 🚀 Hướng dẫn mở dự án
1. Clone repository hoặc tải toàn bộ thư mục này về máy tính (Download ZIP).
2. Trích xuất tất cả các file vào cùng một thư mục chung.
3. Để tương tác với mô hình 3D, hãy mở file Assembly chính (`.iam`) bằng phần mềm Autodesk Inventor.
4. Để xem hoạt ảnh tháo rời, mở file `.ipn`.

---
*Dự án được thiết kế và hoàn thiện bởi [Nguyễn Văn Huy Hoàng - Mechatronics Undergraduate in HCMUT]*
*Chú ý: Repo chỉ mang tính tham khảo để học tập. Không được lấy để làm quy chuẩn, tác giả sẽ không chịu trách nhiệm.
