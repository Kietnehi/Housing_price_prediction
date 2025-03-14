# Project Title

## Mô tả

Dự án này sử dụng các kỹ thuật học máy (Machine Learning) để giải quyết bài toán [mô tả vấn đề bạn đang giải quyết]. Mục tiêu là xây dựng và triển khai một mô hình học máy để dự đoán [hoặc phân loại, tùy thuộc vào vấn đề] với dữ liệu từ [dữ liệu, chẳng hạn như CSV, cơ sở dữ liệu, API, v.v.].

### Các bước trong dự án:
- Thu thập và tiền xử lý dữ liệu. ( Dữ liệu ở đây mình sử dụng là của Kaggle )
- Khám phá và phân tích dữ liệu (EDA).
- Xây dựng và huấn luyện các mô hình học máy.
- Đánh giá mô hình và tinh chỉnh tham số.
- Triển khai mô hình  ( Ở đây mình test trên nhiều Model có sẵn trong thư viện sklearn như LinearRegression,RandomForest,KneighborsRegressor , .... )
  Và ta được model tốt nhất là **XGBOOST**
## Các công nghệ sử dụng

- **Python**: Ngôn ngữ lập trình chính.
- **Pandas**: Xử lý và phân tích dữ liệu.
- **NumPy**: Các phép toán số học.
- **Matplotlib** và **Seaborn**: Trực quan hóa dữ liệu.
- **scikit-learn**: Các thuật toán học máy cơ bản và các công cụ hỗ trợ.
- **XGBoost** (nếu bạn sử dụng): Thư viện học máy mạnh mẽ cho các bài toán học máy.
- **Flask/Django** (nếu bạn triển khai mô hình): Framework web để triển khai API cho mô hình.

## Cài đặt

### Cài đặt môi trường:
Để chạy dự án này, bạn cần cài đặt các thư viện sau:
Trước khi chạy code bạn có thể dùng lệnh **pip install -r requirements.txt ** để cài các thư viện cần để chạy được code 
1. **Clone repository**:
   ```bash
   git clone [https://github.com/username/repository-name.git](https://github.com/Kietnehi/Housing_price_prediction.git)
   cd repository-name
