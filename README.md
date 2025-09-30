# Task 1: Thực hiện 3 thay đổi để cải thiện hiệu suất
- Update time mỗi một giây thay vì gọi liên tục trong Update
- Sử dụng Object Pooling cho các normal item thay vì Instantiate và Destroy
- Xóa bỏ các prefab không dùng đến khỏi folder Resource.
- tất cả các task đã được comment //TODO: để dễ tìm kiếm
# Task 5: Các ý kiến tổ chức lại project.
- Hạn chế asset trong Resource sẽ ảnh hưởng đến load game thay vào đó có thể dùng Addressable
- Phần Gen new item nên chuyển sang Factory pattern để dễ quản lý, mở rộng.
- Tối ưu canvas UI nên chia ra nhiều canvas nhỏ và sử dụng atlas texture
- Áp dụng SOLID trong việc tổ chức code và 1 số pattern phổ biến như Singleton, Observer, StateMachine thay vì switch case
# phần code thuật toán
- input và output chưa rõ ràng(ví dụ test1 input: string N với length 1<=N<=10e6...)
- không được submit task nhiều lần. nên được submit task nhiều lần để có thuật toán chuẩn nhất rồi mới submit tổng cả bài test.
