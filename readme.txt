thêm 1 dòng code từ trên remote repository.
Đây là các lệnh Git phổ biến được sử dụng trong các tình huống khác nhau:

Bắt đầu là "working area" (xem thêm: hướng dẫn trợ giúp git)
   clone             Sao chép một kho lưu trữ vào một thư mục mới
   init              Tạo một kho lưu trữ Git trống hoặc khởi động lại một kho hiện có

làm việc với current change (xem thêm: git help daily)
   add               Add nội dung tệp vào staged
   mv                Move hoặc rename tệp, thư mục hoặc liên kết biểu tượng
   restore           Restore Khôi phục các tệp cây làm việc
   rm                Remove Xóa tệp khỏi cây làm việc và khỏi chỉ mục
   sparse-checkout   Khởi tạo và sửa đổi sparse-checkout

kiểm tra history và status (xem thêm: bản sửa đổi git trợ giúp)
   bisect            Sử dụng tìm kiếm nhị phân để tìm commit đã tạo ra lỗi
   diff              Hiển thị các thay đổi giữa các commit, commit và working tree, v.v.
   grep              In các dòng khớp với một mẫu
   log               Hiển thị nhật ký commit
   show              Hiển thị nhiều loại đối tượng khác nhau
   status            Hiển thị trạng thái cây làm việc

phát triển, đánh dấu và điều chỉnh lịch sử chung của bạn
   branch            Danh sách, tạo hoặc xóa các chi nhánh
   commit            Ghi lại các thay đổi đối với kho lưu trữ
   merge             Kết hợp hai hoặc nhiều lịch sử phát triển với nhau
   rebase            Reapply commits on top of another base tip
   reset             Đặt lại HEAD hiện tại về trạng thái được chỉ định
   switch            Chuyển đổi branches
   tag               Tạo, liệt kê, xóa hoặc xác minh đối tượng tag được ký bằng GPG

cộng tác (xem thêm: git help workflow)
   fetch             Tải xuống các đối tượng và tham chiếu từ một kho lưu trữ khác
   pull              Tìm nạp từ và tích hợp với một kho lưu trữ khác hoặc một chi nhánh cục bộ
   push              Cập nhật các tham chiếu từ xa cùng với các đối tượng liên quan
