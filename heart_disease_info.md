# Thông tin tổng quan về tập dữ liệu Heart Disease

- **Nguồn:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)
- **Số mẫu (num_instances):** 303
- **Số đặc trưng (num_features):** 13 (sử dụng cho phân tích ML)
- **Nhiệm vụ:** Phân loại (Classification)
- **Đặc trưng:** Multivariate (nhiều biến)
- **Kiểu dữ liệu:** Categorical, Integer, Real
- **Có giá trị thiếu:** Có (ký hiệu NaN)
- **Nhãn mục tiêu:** num (diagnosis of heart disease, 0: không bệnh, 1-4: có bệnh)
- **Năm tạo:** 1989, cập nhật lần cuối: 2023
- **Các trường chính:**
    - age: Tuổi (năm)
    - sex: Giới tính (1 = nam, 0 = nữ)
    - cp: Loại đau ngực (1-4)
    - trestbps: Huyết áp lúc nghỉ (mm Hg)
    - chol: Cholesterol huyết thanh (mg/dl)
    - fbs: Đường huyết lúc đói > 120 mg/dl (1 = có, 0 = không)
    - restecg: Kết quả điện tâm đồ lúc nghỉ
    - thalach: Nhịp tim tối đa đạt được
    - exang: Đau thắt ngực khi gắng sức (1 = có, 0 = không)
    - oldpeak: ST chênh xuống do gắng sức so với lúc nghỉ
    - slope: Độ dốc đoạn ST khi gắng sức
    - ca: Số mạch máu chính (0-3) được nhuộm màu bằng huỳnh quang
    - thal: Thalassemia (3 = bình thường, 6 = khiếm khuyết cố định, 7 = khiếm khuyết hồi phục)
    - num: Chẩn đoán bệnh tim (0 = không, 1-4 = có)

## Ý nghĩa nhãn mục tiêu (num)
- 0: Không mắc bệnh tim
- 1, 2, 3, 4: Có mức độ mắc bệnh tim (thường gộp lại thành 1 nhóm "có bệnh" trong các bài toán phân loại nhị phân)

## Thông tin chi tiết về các trường (features)
| Tên trường | Kiểu dữ liệu | Mô tả | Đơn vị | Thiếu dữ liệu |
|------------|--------------|-------|--------|---------------|
| age        | Integer      | Tuổi  | năm    | Không         |
| sex        | Categorical  | Giới tính (1=nam, 0=nữ) | | Không |
| cp         | Categorical  | Loại đau ngực (1-4) | | Không |
| trestbps   | Integer      | Huyết áp lúc nghỉ | mm Hg | Không |
| chol       | Integer      | Cholesterol huyết thanh | mg/dl | Không |
| fbs        | Categorical  | Đường huyết lúc đói > 120 mg/dl (1=có, 0=không) | | Không |
| restecg    | Categorical  | Kết quả điện tâm đồ lúc nghỉ | | Không |
| thalach    | Integer      | Nhịp tim tối đa đạt được | | Không |
| exang      | Categorical  | Đau thắt ngực khi gắng sức (1=có, 0=không) | | Không |
| oldpeak    | Integer      | ST chênh xuống do gắng sức | | Không |
| slope      | Categorical  | Độ dốc đoạn ST khi gắng sức | | Không |
| ca         | Integer      | Số mạch máu chính (0-3) nhuộm màu | | Có |
| thal       | Categorical  | Thalassemia (3, 6, 7) | | Có |
| num        | Integer      | Chẩn đoán bệnh tim (0-4) | | Không |
