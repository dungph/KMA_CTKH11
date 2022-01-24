## <Tên đề tài>



Lý do chọn đề tài: Với thực trạng hiện nay đó là công việc quản lý diễn ra trên giấy tờ, nhưng khối lượng dữ liệu thì ngày một lớn, phần mềm “Quản lý hiệu thuốc” ra đời nhằm mục đích giải quyết những vướng mắc trên, giúp cho công việc quản lí trở nên đơn giản, hiệu quả và chính xác hơn bằng việc tự động hóa quá trình quản lý các yếu tố liên quan như thuốc, hóa đơn, nhân viên…. 

Phạm vi

Yêu cầu đề tài: 



## 1. Khảo sát hệ thống

### 1. 1. Giới thiệu sơ bộ hệ thống

Tên hệ thống: Nhà thuốc WG2

Địa chỉ: 142 Chiến Thắng, Hà Đông, Hà Nội

Chủ đơn vị: Bà Nguyễn Thị An

Quy mô: Cửa hàng bán lẻ

Cơ cấu tổ chức: Chủ cửa hàng, nhân viên quản lý, nhân viên bán hàng, dược sĩ

Cách thức hoạt động: Nhà thuốc là nơi lưu trữ thuốc phục vụ cho khách hàng. Nhân viên của nhà thuốc sẽ thực hiện việc quản lý kho thuốc, bán thuốc và thực hiện thống kê báo cáo lên người quản lý theo thời gian quy định. TODO

### 1. 2. Đánh giá hiện trạng hệ thống

#### 1. 2. 1. Đánh giá nghiệp vụ (Những nhiệm vụ của hệ thống)

Các thành phần trong hệ thống nhà thuốc: 

- Quản lý kho thuốc
- Quản lý bán thuốc
- Quản lý tài chính
- Quản lý nhân sự

Quản lý kho hàng: Nhà thuốc tổ chức lưu trữ, sắp xếp thông tin về thuốc được nhập từ các nhà cung cấp thuốc sau khi được kiểm duyệt. Tuỳ theo từng thời điểm hay dựa theo nhu cầu bổ sung thuốc của kho và trình lên người quản lý. Nếu được chấp nhận sẽ tiến hành kí hợp đồng với nhà cung cấp. Sau khi kí hợp đồng mua thuốc, dược sĩ sẽ chịu trách nhiệm nhận thuốc từ nhà sản xuất và thanh toán hóa đơn nhập thuốc. TODO

Quản lý bán hàng: 

- Khi khách hàng có yêu cầu mua thuốc: 
  - Nếu khách hàng đến mua thuốc lẻ thì nhân viên bán hàng sau khi năm bắt được tình hình bênh lý của khách hàng với sử hiểu biết của mình nhân viên bán thuốc sẽ chuẩn đoán bệnh và tư vấn cho khách hàng nên dùng loại thuốc gì (công dụng, thành phần, nước sản xuất, giá thành ) nếu khách hàng đồng ý thí nhân viên bán hàng sẽ viết hoá đơn bán hàng và hướng dẫn cách sử dụng thuốc cho khách hàng. 
  - Nếu khách khách hàng mua thuốc theo đơn thì nhân viên bán hàng sẽ kiểm tra trong kệ thuốc nếu đáp ứng được loại thuốc nào thì nhân viên bán thuốc sẽ viết hoá đơn bán hàng chuyển cho khách hàng, còn các loại thuốc mà không đáp ứng được thì nhân viên bán hàng sẽ hẹn khách hàng đến mua thuốc trong thời gian sớm nhất có thể hoặc giới thiệu cho khách hàng đến mua ở những cửa hàng có uy tín khác. 
- Các thông tin trên hoá đơn bán hàng bao gồm: số hoá đơn, tên khách, địa chỉ khách, ngay lập, tổng số tiền, số tiền đã thanh toán, còn nợ, hạn trả nợ. các thông tin chi tiết về thuốc bán bao gồm: Tên thuốc, đơn vị tính, số lượng, đơn giá, thành tiền khi thanh toán cửa hàng sẽ lập một phiếu thu tương ứng với hoá đơn mua thuốc trên phiếu thu có ghi rõ: số phiếu thu, số hoá đơn, ngày lập, người lập, số tiền, ghi chú. Một bản sao của Hoá đơn bán hàng (phiếu xuất ) sẽ được lưu lại để tiện cho quá trình quản lý, còn một bản giao cho khách hàng để tiện cho việc bảo hành trả nợ nếu có của khách hàng sau này cửa hàng quản lý khách hàng bằng cách cập nhật thông tin về khách hàng. Các thông tin về khách hàng bao gồm: mã khách, họ tên khách, địa chỉ, số điện thoại, email. 
- Sau khi kết thúc ca làm việc thì nhân viên bán hàng sẽ tổng hợp số tiền bán hàng và bàn giao cho người quản lý. 

Quản lý tài chính: Thu, chi của cửa hàng được nhân viên ghi vào sổ sau mỗi ngày. TODO

Quản lý nhân sự: được thực hiện bởi nhân viên quản lý. 

#### 1.2.2. Quy tắc quản lý: Những quy tắc mà đối tượng trong hệ thống phải tuân theo để đảm bảo đúng: 



#### 1.2.3. Đánh giá hiện trạng(ưu điểm, tồn tại)

##### 1.2.4.1. Ưu điểm

Hệ thống đơn giản, dễ làm quen. 

##### 1.2.4.2. Nhược điểm

Do hệ thống làm việc trên sổ sách, không thông qua máy tính nên có một số bất cập: 

- Quản lý kho, tra cứu thuốc khó khăn, tốn nhiều thời gian.
- Phụ thuộc hoàn toàn vào con người, dễ phát sinh các sai sót.
- Khó kiểm soát thông tin về khách hàng,nhà cung cấp và thông tin về hàng hoá của cửa hàng.
- Khó thống kê tình trạng bán hàng, khó đưa ra giải pháp phát triển, nâng cao hiệu quả bán hàng.

### 1.3. Xác định yêu cầu hệ thống

#### 1.3.1. Yêu cầu về chức năng (thực hiện các công việc gì), đưa ra dự kiến các chức năng của phần mềm (sản phẩm dự kiến)

| Chức năng              | Đầu vào                                                      | Đầu ra                                                       |
| ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Tìm kiếm thuốc         | Một trong các thông tin: Mã thuốc, Tên thuốc, Hoạt chất, Nhóm thuốc, Nhà cung cấp | Danh sách thuốc tìm được                                     |
| Tạo hóa đơn bán thuốc  | Danh sách mã thuốc, số lượng                                 | In hóa đơn gồm: Tên thuốc, đơn giá, số lượng, thành tiền     |
| Tạo hóa đơn nhập thuốc | Danh sách mã thuốc, ngày hết hạn, đơn giá, số lượng, nhà cung cấp. | In hóa đơn: Tên thuốc, đơn giá, số lượng, thành tiền, nhà cung cấp |
| Tạo khoản chi          | Số tiền, Thông tin khoản chi                                 |                                                              |
| Thêm nhân viên         | Thông tin cá nhân, ngày làm việc, hệ số lương, các vị trí làm việc. |                                                              |
| Chỉnh sửa nhân viên    | Mã nhân viên, các thông tin chỉnh sửa                        |                                                              |
| Thống kê kho thuốc     |                                                              |                                                              |
| Thống kê hóa đơn       |                                                              |                                                              |
| Thống kê tài chính     |                                                              |                                                              |

#### 1. 3. 2. Yêu cầu phi chức năng (những chức năng mà người dung mong muốn)

Giao diện đơn giản, hiệu quả, thông tin trả về hữu ích, tự động sửa những lỗi cơ bản của người dùng. 

Hệ thống chạy nhanh, ổn định, chính xác. 

### 1. 4. Lập kế hoạch thực hiện

#### 1. 4. 1. Tiến độ thời gian. 

#### 1. 4. 2. Nhân lực (Phân công công việc, hỗ trợ, họp nhóm)

#### 1. 4. 3. Thiết bị (Phần cứng, Phần mềm, Yêu cầu kỹ thuật)

#### 1. 4. 4. Kinh phí (10 điểm)

#### 1. 4. 5. Nền tảng (Công cụ phát triển: CSDL, Ngôn ngữ, Công cụ kiểm thử,... )

#### 1. 4. 6. Đặc tả hệ thống (UML)
