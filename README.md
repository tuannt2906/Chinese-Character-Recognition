# Chinese-Character-Recognition

## Thông tin thành viên nhóm 8
- Lê Văn Bảo - 21020171
- Tống Minh Trí - 21020249
- Nguyễn Ngọc Tuấn - 21020237
- Nguyễn Văn Thuyên - 21020247

## Mục tiêu của repository
Repository trên là phần Implement của nhóm cho bài tập giữa kì môn Xử lý ảnh về bài toán nhận diện dữ nôm.

## Cài đặt và chạy code
- Nếu bạn muốn chạy thử thì bạn chỉ cần tải 2 file notebook về rồi tạo notebook trên kaggle rồi chạy.
- Lưu ý: 
    - Để có thể chạy nhanh thì nên chọn accelerator là GPU T4 x2.
    - Với notebook model3 thì việc huấn luyện sẽ tốn khoảng 7 tiếng.
    - Với notebook predict thì sẽ chạy xong khá nhanh.

## Cấu trúc của repository
Repo này có 2 file chính notebook và 1 file pdf là báo cáo của nhóm.
- Notebook model3 là notebook chứa mô hình, phương pháp xử lý ảnh, hàm loss, bộ tham số khi huấn luyện đem lại kết quả tốt nhất.
Nếu bạn muốn sử dụng các model đồ khác thì bạn có thể thay đổi cấu trúc của model để chạy.
- Notebook predict thực hiện suy luận dựa trên file checkpoint của model3 đã được lưu sau khi huấn luyện. 
- File Full_report.pdf là báo cáo của nhóm cho dự án này.

## Kết quả
Với notebook model3 thì cho độ chính xác khoảng 88% trên tập test.
