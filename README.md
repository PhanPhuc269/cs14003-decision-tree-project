                                                           Project 2: Decision Tree Classifiers

1. Giới thiệu
Đồ án yêu cầu xây dựng và đánh giá cây quyết định (Decision Tree) trên ba bộ dữ liệu thực tế: Heart Disease dataset, Palmer Penguins dataset, Dry Bean dataset sử dụng thư viện scikit-learn.

2. Hướng dẫn chạy chương trình
  B1: Cài đặt thư viện và phần mềm 
   - Cài đặt các thư viện cần thiết:
     ```powershell
     pip install -r requirements.txt
     ```
   - Cài đặt phần mềm Graphviz cho Windows và thêm vào PATH để vẽ cây quyết định:
     - Tải tại: https://graphviz.gitlab.io/_pages/Download/Download_windows.html
     - Thêm `C:\Program Files\Graphviz\bin` vào biến môi trường PATH.

  B2: Chạy notebook
   - Mở `file.ipynb` bằng Jupyter Notebook hoặc VSCode:
      - File `Heart_Disease.ipynb` cho dataset Heart Disease.
      - File `Palmer_Penguins.ipynb` cho dataset Palmer Penguins.
      - File `Dry_Bean.ipynb` cho dataset Dry Bean.
   - Chạy tuần tự từng cell để thực hiện các bước:
     - Chuẩn bị dữ liệu: chia train/test, trực quan hóa phân bố lớp.
     - Huấn luyện và vẽ cây quyết định cho từng tỷ lệ.
     - Đánh giá mô hình (classification report, confusion matrix).
     - Lặp lại quy trình cho Palmer Penguins và bộ dữ liệu bổ sung.
    - Chạy Run All nếu muốn chạy tất cả các cell 1 lượt.

3. Tài liệu tham khảo
- UCI Heart Disease Dataset: https://archive.ics.uci.edu/dataset/45/heart+disease
- Palmer Penguins Dataset: https://archive.ics.uci.edu/dataset/690/palmer+penguins-3
- scikit-learn: https://scikit-learn.org
- Graphviz: https://graphviz.gitlab.io
