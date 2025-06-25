# Thông tin tổng quan về tập dữ liệu Dry Bean

- **Nguồn:** [UCI Dry Bean Dataset](https://archive.ics.uci.edu/dataset/602/dry+bean+dataset)
- **Số mẫu (num_instances):** 13,611
- **Số đặc trưng (num_features):** 16 (không tính nhãn)
- **Nhiệm vụ:** Phân loại (Classification)
- **Đặc trưng:** Multivariate (nhiều biến)
- **Kiểu dữ liệu:** Numeric (số thực)
- **Có giá trị thiếu:** Không
- **Nhãn mục tiêu:** Class (loại hạt đậu)
- **Năm tạo:** 2020
- **Các trường chính (features):**
    - Area: Diện tích (số pixel)
    - Perimeter: Chu vi (pixel)
    - MajorAxisLength: Độ dài trục lớn (pixel)
    - MinorAxisLength: Độ dài trục nhỏ (pixel)
    - AspectRation: Tỷ lệ trục lớn/trục nhỏ
    - Eccentricity: Độ lệch tâm
    - ConvexArea: Diện tích lồi (pixel)
    - EquivDiameter: Đường kính tương đương (pixel)
    - Extent: Tỷ lệ diện tích/diện tích hình chữ nhật bao quanh
    - Solidity: Tỷ lệ diện tích/diện tích lồi
    - roundness: Độ tròn
    - Compactness: Độ nén
    - ShapeFactor1: Hệ số hình dạng 1
    - ShapeFactor2: Hệ số hình dạng 2
    - ShapeFactor3: Hệ số hình dạng 3
    - ShapeFactor4: Hệ số hình dạng 4
    - Class: Nhãn loại hạt đậu (target)

## Ý nghĩa nhãn mục tiêu (Class)
- BEANS: Loại hạt đậu khô, gồm 7 lớp:
    - SEKER
    - BARBUNYA
    - BOMBAY
    - CALI
    - HOROZ
    - SIRA
    - DERMASON

## Thông tin chi tiết về các trường (features)
| Tên trường        | Kiểu dữ liệu | Mô tả                                      | Đơn vị   | Thiếu dữ liệu |
|-------------------|--------------|---------------------------------------------|----------|---------------|
| Area              | Numeric      | Diện tích                                  | pixel    | Không         |
| Perimeter         | Numeric      | Chu vi                                     | pixel    | Không         |
| MajorAxisLength   | Numeric      | Độ dài trục lớn                            | pixel    | Không         |
| MinorAxisLength   | Numeric      | Độ dài trục nhỏ                            | pixel    | Không         |
| AspectRation      | Numeric      | Tỷ lệ trục lớn/trục nhỏ                    |          | Không         |
| Eccentricity      | Numeric      | Độ lệch tâm                                |          | Không         |
| ConvexArea        | Numeric      | Diện tích lồi                              | pixel    | Không         |
| EquivDiameter     | Numeric      | Đường kính tương đương                     | pixel    | Không         |
| Extent            | Numeric      | Tỷ lệ diện tích/diện tích hình chữ nhật    |          | Không         |
| Solidity          | Numeric      | Tỷ lệ diện tích/diện tích lồi              |          | Không         |
| roundness         | Numeric      | Độ tròn                                    |          | Không         |
| Compactness       | Numeric      | Độ nén                                     |          | Không         |
| ShapeFactor1      | Numeric      | Hệ số hình dạng 1                          |          | Không         |
| ShapeFactor2      | Numeric      | Hệ số hình dạng 2                          |          | Không         |
| ShapeFactor3      | Numeric      | Hệ số hình dạng 3                          |          | Không         |
| ShapeFactor4      | Numeric      | Hệ số hình dạng 4                          |          | Không         |
| Class             | Categorical  | Loại hạt đậu (SEKER, BARBUNYA, ...)        |          | Không         |
