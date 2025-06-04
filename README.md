# CS14003 - Project 2: Decision Tree Classifiers

## 📚 Giới thiệu
Đây là đồ án môn học CS14003, xây dựng và đánh giá cây quyết định (Decision Tree) trên ba bộ dữ liệu thực tế sử dụng thư viện scikit-learn:
- **Heart Disease** (nhị phân): Dự đoán có/không mắc bệnh tim.
- **Palmer Penguins** (đa lớp): Dự đoán loài chim cánh cụt.
- **Bộ dữ liệu bổ sung**: Tự chọn, ≥ 300 mẫu, ≥ 2 lớp.

## 🗂️ Cấu trúc workspace
- `project2.ipynb`: Notebook chính, thực hiện toàn bộ quy trình tiền xử lý, huấn luyện, đánh giá và trực quan hóa cây quyết định cho các bộ dữ liệu.
- `requirements.txt`: Danh sách các thư viện Python cần thiết để chạy notebook.
- `heart_disease_info.md`: Thông tin chi tiết về bộ dữ liệu Heart Disease (nguồn, mô tả các trường, ý nghĩa nhãn...).
- `DA2.md`: Đề bài chi tiết, yêu cầu kỹ thuật, tiêu chí chấm điểm và hướng dẫn nộp bài.

## 🚀 Hướng dẫn sử dụng
1. **Cài đặt môi trường**
   - Tạo virtual environment (khuyến nghị):
     ```powershell
     python -m venv venv
     .\venv\Scripts\activate
     ```
   - Cài đặt các thư viện cần thiết:
     ```powershell
     pip install -r requirements.txt
     ```
   - Cài đặt phần mềm Graphviz cho Windows và thêm vào PATH để vẽ cây quyết định:
     - Tải tại: https://graphviz.gitlab.io/_pages/Download/Download_windows.html
     - Thêm `C:\Program Files\Graphviz\bin` vào biến môi trường PATH.

2. **Chạy notebook**
   - Mở `project2.ipynb` bằng Jupyter Notebook hoặc VSCode.
   - Chạy tuần tự từng cell để thực hiện các bước:
     - Chuẩn bị dữ liệu, chia train/test, trực quan hóa phân bố lớp.
     - Huấn luyện và vẽ cây quyết định cho từng tỷ lệ.
     - Đánh giá mô hình (classification report, confusion matrix).
     - Phân tích ảnh hưởng của độ sâu cây đến độ chính xác.
     - Lặp lại quy trình cho Palmer Penguins và bộ dữ liệu bổ sung.
     - So sánh, tổng hợp kết quả.

3. **Báo cáo**
   - Viết báo cáo phân tích, nhận xét, tổng hợp kết quả vào file PDF theo hướng dẫn trong `DA2.md`.
   - Đảm bảo tất cả biểu đồ/trực quan nằm trong notebook.
   - Nộp bài đúng định dạng yêu cầu.

## 📝 Tài liệu tham khảo
- UCI Heart Disease Dataset: https://archive.ics.uci.edu/dataset/45/heart+disease
- Palmer Penguins Dataset: https://archive.ics.uci.edu/dataset/690/palmer+penguins-3
- scikit-learn: https://scikit-learn.org
- Graphviz: https://graphviz.gitlab.io

## ⚠️ Lưu ý
- Đảm bảo cài đặt đúng các thư viện và phần mềm Graphviz để tránh lỗi khi vẽ cây quyết định.
- Nếu sử dụng AI hỗ trợ, ghi rõ prompt trong phụ lục báo cáo.
- Không đạo văn, gian lận.

---
**Mọi thắc mắc về đề bài, xem chi tiết trong file `DA2.md`.**
