### Nhóm môn Big Data Applications: Machine Learning at Scale

## 1. Thành viên: 

	Đào Văn Thắng       18133050
	Trần Minh Tú Trung  18133060
	Đặng Ngọc Sơn       18133046

## 2. Giới thiệu sơ lược về project

**- Tên project :** Phân tích và dự đoán mức lương ở Mỹ có trên 50k đô la hay không.

**- Link project:** Imbalanced Classification with the Adult Income Dataset

**- Tập dữ liệu:** adult-all.csv 

**- Link tập dữ liệu:** [data]( https://drive.google.com/file/d/1fQDwdXQbGJ84Ud9wOJ9fYDYHUoqYOHWt/view?usp=sharing)

***- Mô tả ngắn gọn về project mà nhóm muốn giải quyết: sử dụng Pyspark và thư viện Machine learning: Pyspark.MLlib với các thuật toán để dự đoán lương của người lao động.***

***- Mô tả ngắn gọn về tập dữ liệu: Tập dữ liệu về các chi tiết cá nhân để dự đoán xem một cá nhân sẽ kiếm được nhiều hơn hay ít hơn 50.000 đô la mỗi năm.***
- Gồm có 48,842 dòng và 15 cột.

	+ Age: Tuổi của người lao động

	+ Workclass: Tổ chức hoạt động.

	+ Final Weight (fnlwgt): Trọng số cuối - Được tính từ 3 yếu tố:
					+ Dân số từ 16 tuổi trở lên mỗi tiểu bang.
					+ Nguồn gốc Tây Ban Nha theo độ tuổi và giới tính.
					+ Kiểm soát theo chủng tộc, tuổi và giới tính.

	+ Education: Trình độ học vấn.

	+ Education-num:  Số lượng bằng cấp.

	+ Marital-status:  Tình trạng hôn nhân.

	+ Occupation: Nghề nghiệp của người lao động.

	+ Relationship: Mối quan hệ của người lao động.

	+ Race: Sắc tộc.

	+ Sex: Giới tính.

	+ Capital-gain: Lương được tăng.

	+ Captital-loss: Lương bị giảm.

	+ Hours-per-week: Số giờ làm việc trong một tuần.

	+ Native-country: Quê hương của người lao động.

## 3. Giải pháp

	- Nhóm dự định dùng những phương pháp, thuật toán nào để giải quyết bài toán đó?
	
	   Nhóm dự định sử dụng Random Forest để dự đoán tệp dữ liệu và phương pháp thử cross validation.

## 4. Thực nghiệm

	- Tiền xử lý : Kiểm tra các cột có giá trị "?" chuyển đổi các dòng NA thành 'NA', tách dữ liệu, thêm cột , xóa cột, ... Chuyển đổi kiểu dữ liệu.

	- Thuật toán: Những thuật toán Classification và đánh giá mô hình chọn thuật toán tốt nhất cho bài toán.

	- Chạy các thuật toán về Classification 

## 5. Phác thảo kế hoạch làm việc (plan)

	- Hiểu về tập dữ liệu và vấn đề cần giải quyết.

	- Import dữ liệu và tiền xử lý dữ liệu.

	- Xử lý dữ liệu phân loại.

	- Tìm và xử lý dữ liệu outliers(nếu có).

	- Training dữ liệu trên các mô hình Classification.

	- Chọn mô hình có kết quả tốt nhất.

	- Tinh chỉnh siêu tham số của mô hình.
