# Cafe Analytics System

Hệ thống phân tích kinh doanh cafe tự động bằng Python.

## Công nghệ sử dụng
- Python 3.13
- Pandas — xử lý dữ liệu
- Matplotlib & Seaborn — trực quan hóa
- SQLite — database
- Scikit-learn — dự đoán ML
- SciPy — thống kê & A/B Testing

## Tính năng
- Đọc & làm sạch dữ liệu tự động
- Phân tích doanh thu theo ngày & sản phẩm
- A/B Testing so sánh hiệu quả
- Dự đoán doanh thu bằng Linear Regression
- Xuất Dashboard PNG & báo cáo Excel

## Cấu trúc dự án
cafe-analytics/
├── data/
│   ├── doanh_thu.csv
│   ├── data_ban.csv
│   └── cafe.db
├── notebooks/
│   └── phan_tich_cafe.ipynb
├── outputs/
│   ├── dashboard_final.png
│   └── bao_cao_final.xlsx
└── README.md

## Kết quả
- Tổng doanh thu 7 ngày phân tích
- Top sản phẩm bán chạy: Ca phe den
- Model dự đoán R² > 90%
- Dashboard 4 biểu đồ tự động xuất

## Tác giả
tongducmanh12345-lab