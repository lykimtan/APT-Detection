# APT-Detection

├── data/ # Chứa dữ liệu (raw, processed)
├── notebooks/ # Các file Jupyter Notebook để EDA và thử nghiệm nhanh
├── src/ # Mã nguồn chính của dự án
│ ├── preprocessing/ # Tiền xử lý dữ liệu (chuẩn hóa, tạo sequence)
│ ├── models/ # Định nghĩa kiến trúc CNN, LSTM, Autoencoder
│ ├── training/ # Script huấn luyện và tuning
│ └── evaluation/ # Đánh giá mô hình (Matrix, ROC curve, v.v.)
├── scripts/ # Các script chạy nhanh (train.py, predict.py)
├── config/ # Lưu tham số cấu hình (hyperparameters, paths)
├── models_saved/ # Lưu trữ các trọng số mô hình (.h5, .pth)
├── reports/ # Kết quả, biểu đồ, logs
├── requirements.txt # Các thư viện cần thiết
└── README.md # Hướng dẫn sử dụng dự án
