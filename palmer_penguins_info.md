# Thông tin tổng quan về tập dữ liệu Palmer Penguins

- **Nguồn:** [UCI Palmer Penguins Dataset](https://archive.ics.uci.edu/dataset/690/palmer+penguins-3)
- **Số mẫu (num_instances):** 344
- **Số đặc trưng (num_features):** 7 (sử dụng cho phân tích ML)
- **Nhiệm vụ:** Phân loại (Classification)
- **Đặc trưng:** Multivariate (nhiều biến)
- **Kiểu dữ liệu:** Categorical, Integer, Float
- **Có giá trị thiếu:** Có (ký hiệu NaN)
- **Nhãn mục tiêu:** species (loài chim cánh cụt: Adelie, Chinstrap, Gentoo)
- **Năm thu thập:** 2007–2009
- **Các trường chính:**
    - species: Loài chim cánh cụt (Adelie, Chinstrap, Gentoo)
    - island: Đảo sinh sống (Biscoe, Dream, Torgersen)
    - bill_length_mm: Chiều dài mỏ (mm)
    - bill_depth_mm: Độ sâu mỏ (mm)
    - flipper_length_mm: Chiều dài vây (mm)
    - body_mass_g: Khối lượng cơ thể (g)
    - sex: Giới tính (Male, Female)
    - year: Năm khảo sát (2007, 2008, 2009)

## Ý nghĩa nhãn mục tiêu (species)
- Adelie: Loài Adelie
- Chinstrap: Loài Chinstrap
- Gentoo: Loài Gentoo

## Thông tin chi tiết về các trường (features)
| Tên trường         | Kiểu dữ liệu | Mô tả                                 | Đơn vị | Thiếu dữ liệu |
|--------------------|--------------|----------------------------------------|--------|---------------|
| species            | Categorical  | Loài chim cánh cụt                    |        | Không         |
| island             | Categorical  | Đảo sinh sống                         |        | Không         |
| bill_length_mm     | Float        | Chiều dài mỏ                          | mm     | Có            |
| bill_depth_mm      | Float        | Độ sâu mỏ                             | mm     | Có            |
| flipper_length_mm  | Integer      | Chiều dài vây                         | mm     | Có            |
| body_mass_g        | Integer      | Khối lượng cơ thể                     | g      | Có            |
| sex                | Categorical  | Giới tính (Male, Female)              |        | Có            |
| year               | Integer      | Năm khảo