# CS14003 - Project 2: Decision Tree Classifiers

## 📘 Mô tả

Trong đồ án này, bạn sẽ xây dựng cây quyết định (decision trees) trên các tập dữ liệu thực tế sử dụng thư viện `scikit-learn`. Bạn sẽ làm việc với ba tập dữ liệu:

1. **Heart Disease (nhị phân)**  
   - Phân loại có/không mắc bệnh tim.
   - 303 mẫu, nhãn: 0 hoặc 1.

2. **Palmer Penguins (đa lớp)**  
   - Phân loại loài chim cánh cụt.
   - 344 mẫu, nhãn: Adelie, Chinstrap, Gentoo.

3. **Tập dữ liệu bổ sung (do nhóm tự chọn)**  
   - Tối thiểu 300 mẫu, có nhãn.
   - Có thể là đa lớp hoặc nhị phân.

---

## 📋 Yêu cầu kỹ thuật

### 1. Chuẩn bị dữ liệu

- Sử dụng features và labels để tạo:
  - `feature_train`, `label_train`
  - `feature_test`, `label_test`
- Chia tập dữ liệu theo tỷ lệ:
  - **40/60**, **60/40**, **80/20**, **90/10** (train/test).
  - Tổng cộng **16 tập con**.
- Sử dụng `shuffle` và chia theo **stratified**.
- Trực quan hóa phân phối lớp trong tất cả tập.

### 2. Xây dựng cây quyết định

- Dùng `DecisionTreeClassifier` của `scikit-learn`.
- Tham số `criterion='entropy'` (thông tin gain).
- Huấn luyện mô hình trên từng tập train.
- Trực quan hóa cây bằng `Graphviz`.

### 3. Đánh giá mô hình

- Dự đoán tập test tương ứng.
- Tạo báo cáo:
  - `classification_report`
  - `confusion_matrix`
- Diễn giải và đưa ra nhận xét về hiệu quả.

### 4. Độ sâu và độ chính xác

- Chỉ thực hiện trên tập chia **80/20**.
- Thử các giá trị `max_depth`: `None`, 2, 3, 4, 5, 6, 7.
- Mỗi giá trị:
  - Trực quan hóa cây.
  - Ghi lại `accuracy_score`.
- Trình bày kết quả dạng bảng:

| max_depth | None | 2 | 3 | 4 | 5 | 6 | 7 |
|-----------|------|---|---|---|---|---|---|
| Accuracy  |      |   |   |   |   |   |   |

- Vẽ biểu đồ và đưa ra nhận xét.

### 5. Lặp lại cho các tập dữ liệu còn lại

- Áp dụng **toàn bộ quy trình trên** cho:
  - Tập Palmer Penguins.
  - Tập dữ liệu bổ sung.
- Với dữ liệu phân loại, sử dụng **One-hot encoding**.

### 6. Phân tích so sánh

- So sánh hiệu quả mô hình giữa 3 tập.
- Phân tích theo:
  - Số lớp.
  - Số đặc trưng.
  - Số lượng mẫu.
- Trình bày bằng bảng và biểu đồ.

---

## 📑 Báo cáo

### 1. Nội dung cần có

- Thông tin thành viên: MSSV, Họ tên.
- Bảng phân công công việc:
  - Ghi rõ phần việc và % hoàn thành.
  - Tính điểm theo tỷ lệ phần trăm đóng góp.
- Tự đánh giá.
- Tất cả biểu đồ/trực quan trong `.ipynb`.
- Kết quả thống kê và phân tích trình bày trong file báo cáo.
- Xuất báo cáo sang PDF, **không bị cắt hình/biểu đồ**.
- Tài liệu tham khảo (nếu có).

---

## 🧾 Nộp bài

- Gộp toàn bộ báo cáo + source code vào file `.zip/.rar/.7z`.
- Đặt tên file: `MSSV1_MSSV2_MSSV3_MSSV4.zip`.
- Nếu file > 25MB:
  - Ưu tiên nén báo cáo và source.
  - Hình ảnh/lớn có thể đẩy lên Google Drive kèm link.

---

## 📝 Chấm điểm

### Tổng quan

| Tiêu chí                                  | Điểm |
|-------------------------------------------|------|
| Phân tích Heart Disease                   | 30%  |
| Phân tích Palmer Penguins                 | 30%  |
| Phân tích dữ liệu bổ sung                 | 30%  |
| Phân tích so sánh 3 tập dữ liệu           | 5%   |
| Notebook rõ ràng, format chuẩn            | 5%   |
| **Tổng cộng**                             | 100% |

### Chi tiết từng tập dữ liệu

| Tiêu chí                                          | Điểm |
|--------------------------------------------------|------|
| Chuẩn bị dữ liệu                                 | 30%  |
| Cài đặt cây quyết định                           | 20%  |
| Đánh giá hiệu suất (report, confusion matrix)    | 20%  |
| Độ sâu & độ chính xác (biểu đồ, bảng, nhận xét)  | 30%  |

---

## ⚠️ Lưu ý

- Đây là **bài tập nhóm**, mỗi nhóm **4 người**.
- Thời gian: khoảng **3 tuần**.
- Nếu sử dụng AI (ChatGPT...), phải ghi rõ prompt trong **Phụ lục**.
- **Đạo văn, gian lận → 0 điểm toàn khóa học.**

---

## 🔗 Tài liệu tham khảo

- UCI Heart Disease Dataset: [Link](https://archive.ics.uci.edu/dataset/45/heart+disease)
- Palmer Penguins Dataset: [Link](https://archive.ics.uci.edu/dataset/690/palmer+penguins-3)
- scikit-learn: [https://scikit-learn.org](https://scikit-learn.org)

