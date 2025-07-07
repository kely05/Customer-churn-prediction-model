Dự án này xây dựng một mô hình học máy nhằm dự đoán khả năng rời bỏ của khách hàng dựa trên các đặc điểm như độ tuổi, thu nhập, số năm sử dụng dịch vụ

Mục tiêu :
Dự đoán khả năng rời bỏ (churn) của khách hàng.

Phân tích các đặc trưng ảnh hưởng đến churn.

Đánh giá hiệu suất mô hình

Mô tả dữ liệu
Một số cột dữ liệu thường dùng trong mô hình:

Cột dữ liệu	Ý nghĩa
Age	Tuổi của khách hàng
Tenure	Số năm sử dụng dịch vụ
Balance	Số dư tài khoản
NumOfProducts	Số lượng sản phẩm khách hàng đang dùng
IsActiveMember	Tình trạng hoạt động (1 = có, 0 = không)
Gender, Geography	Dữ liệu định danh (được mã hóa one-hot)
Exited	Mục tiêu: 1 = đã rời, 0 = còn ở lại
