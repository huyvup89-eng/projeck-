1. MÔ TẢ BÀI TOÁN:
Giới thiệu
Trong thời đại số, con người sử dụng rất nhiều ứng dụng khác nhau như học tập, giải trí, nghe nhạc, chơi game và làm việc. Mỗi người thường có những thói quen sử dụng thiết bị điện tử theo các khung giờ cố định trong ngày.
Mục tiêu của đề tài là xây dựng một mô hình Machine Learning có khả năng nhận diện và dự đoán hành vi của người dùng dựa trên dữ liệu lịch sử sử dụng thiết bị.
Mục tiêu
Xây dựng hệ thống có khả năng:
Nhận biết hoạt động của người dùng theo từng thời điểm.
Học các quy luật trong thói quen sử dụng ứng dụng.
Dự đoán hành vi tiếp theo của người dùng.
Input và Output
Input
Giờ sử dụng
Ứng dụng đang sử dụng
Thời lượng sử dụng
Output
Hành vi của người dùng:
oHọc tập
oGiải trí
oChơi game
oTập thể dục
oĂn uống
oNgủ nghỉ

2. DỮ LIỆU:
Nguồn dữ liệu
Dữ liệu được xây dựng mô phỏng dựa trên lịch sinh hoạt thực tế của người dùng trong một tuần.
Các thuộc tính
Thuộc tính	Ý nghĩa
hour	Thời gian trong ngày
app	Ứng dụng đang sử dụng
duration	Thời lượng sử dụng
result	Hành vi của người dùng
Tiền xử lý dữ liệu
Các giá trị dạng văn bản được chuyển thành dạng số bằng thư viện LabelEncoder của Scikit-Learn.
Ví dụ:
Giá trị gốc	Sau mã hóa
study	0
youtube	1
game	2
Sau khi mã hóa, dữ liệu được chia thành:
70% dữ liệu huấn luyện
30% dữ liệu kiểm tra

3. DEMO HỆ THỐNG:
Quy trình hoạt động:
1.Người dùng nhập dữ liệu mới.
2.Dữ liệu được mã hóa.
3.Mô hình Machine Learning xử lý.
4.Hệ thống đưa ra dự đoán hành vi.
Ví dụ:
Input:
Giờ: 20
Ứng dụng: game
Thời lượng: 30 phút
Output:
Hành vi dự đoán: Chơi game
Hệ thống cũng hỗ trợ:
Biểu đồ Accuracy
Cross Validation
Feature Importance
Cây quyết định trực quan

4. KẾT LUẬN VÀ HƯỚNG PHÁT TRIỂN:
Kết quả đạt được
Xây dựng thành công hệ thống nhận diện thói quen người dùng.
Áp dụng Machine Learning để dự đoán hành vi.
So sánh được hiệu quả giữa Decision Tree và Random Forest.
Trực quan hóa được quá trình học của mô hình.
Hạn chế
Dữ liệu còn ít và mang tính mô phỏng.
Chưa sử dụng dữ liệu thực tế từ điện thoại hoặc máy tính.
Chưa có khả năng học trực tuyến (online learning).
Hướng phát triển
Thu thập dữ liệu thực tế từ người dùng.
Bổ sung các thuộc tính:
oNgày trong tuần
oHành vi trước đó
oVị trí
Xây dựng ứng dụng dự đoán thói quen theo thời gian thực.
