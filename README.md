Dự án này xây dựng một mô hình học máy nhằm dự đoán khả năng rời bỏ của khách hàng dựa trên các đặc điểm như độ tuổi, thu nhập, số năm sử dụng dịch vụ

- Mục tiêu :
  Dự đoán khả năng rời bỏ (churn) của khách hàng.

  Phân tích các đặc trưng ảnh hưởng đến churn.

  Đánh giá hiệu suất mô hình

- Mô tả dữ liệu
  một số cột dữ liệu thường dùng trong mô hình:

  Age:	Tuổi của khách hàng

  Tenure:	Số năm sử dụng dịch vụ

  Balance:	Số dư tài khoản

  NumOfProducts:	Số lượng sản phẩm khách hàng đang dùng

  IsActiveMember:	Tình trạng hoạt động (1 = có, 0 = không)

  Gender, Geography:	Dữ liệu định danh (được mã hóa one-hot)

  Exited:	Mục tiêu: 1 = đã rời, 0 = còn ở lại

- Thông tin mô hình
  Loại mô hình: Mạng nơ-ron nhân tạo (Keras Sequential)

  Đầu vào: 13 đặc trưng

  Lớp ẩn: 2 lớp sử dụng hàm kích hoạt ReLU

  Lớp đầu ra: Hàm kích hoạt Sigmoid (phân loại nhị phân)

  Hàm mất mát: binary_crossentropy

  Bộ tối ưu: adam

  link mở: https://colab.research.google.com/github/nguyenhson03/Customer-churn-prediction-model/blob/main/Mohinhkhachhang.ipynb#scrollTo=B7GhjmFLQH_g
