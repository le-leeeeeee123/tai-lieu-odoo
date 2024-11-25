# Cấu hình nhặt hàng/tạo phiếu pick list
Chức năng này có mục đích cấu hình gom danh sách đơn theo tiêu chí tạo các picklist phù hợp cho việc nhặt hàng.

**Bước 1:** Vào menu ```Phiếu lấy/đóng hàng```
![alt text](./khovan/setpicklist1.png)
**Bước 2:** Chọn cấu hình nhặt hàng
![alt text](./khovan/setpicklist.png)
**Bước 3:** Hiển thị danh sách cấu hình nhặt hàng, người dùng muốn thêm mới chọn nút ```mới``` để cấu hình nhặt hàng
![alt text](./khovan/setpicklist-2.png)
**Bước 4:** Hiển thị màn hình thêm mới cấu hình nhặt hàng và các thông tin cần cấu hình gồm:
![alt text](./khovan/setpicklist-3.png)

Màu đỏ là các trường bắt buộc phải chọn
![alt text](./khovan/setpicklist1-1.png)

+ Kích hoạt điều kiện
+ Điều kiện chính theo: ![alt text](./khovan/setpicklistdieukienchinh.png)
+ Sản phẩm cần tạo phiếu riêng: Chọn sản phẩm
+ Khi điều kiện sản phẩm cần tạo phiếu riêng có chọn sản phẩm thì==> Điều kiện là đơn 1 sản phẩm: sẽ được check mặc định
+ Số đơn hàng tối đa: Nhập số lượng đơn hàng tối đa trong 1 phiếu picklist
+ Số lượng sku tối đa: Hiển thị số lượng sku tối đa trong 1 phiếu picklist
+ Số lượng sản phẩm tối đa: nhập số lượng sản phẩm tối đa trong 1 phiếu picklist
Chú ý: Check điều kiện ưu tiên từ cao đến thấp
`Số lượng sản phẩm tối đa>>Số lượng sku tối đa>>Số đơn hàng tối đa`

+Đơn vị vận chuyển
+Kho: chọn kho
+Kênh kinh doanh:chọn kênh
+Nguồn: chọn nguồn
+Nội dung điều kiện: tóm tắt lại các điều kiện đã set ở bên trên

**Bước 4:** Lưu thông tin: Lưu thông tin thành công, tạo cấu hình phiếu picklist thành công
**Khi có đơn được tạo , hệ thống sẽ dựa trên các cấu hình picklist để tạo ra danh sách picklist theo cấu hình mà người dùng đã khai báo trước đó**