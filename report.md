## Lý do chọn đề tài

​	Với thực trạng hiện nay đó là công việc quản lý diễn ra trên giấy tờ, nhưng khối lượng dữ liệu thì ngày một lớn. Vì vậy chúng tôi xây dựng một phần mềm "Quản lý hiệu thuốc" ra đời nhằm mục đích giải quyết những khó khăn trên giúp cho công việc quản lí trở nên đơn giản, hiệu quả và chính xác hơn bằng việc tự động hóa quá trình quản lý các yếu tố liên quan như thuốc, hóa đơn, nhân viên, khách hàng…

## Phạm vi đề tài

​	Phân tích, thiết kế hệ thống quản lý nhà thuốc áp dụng cho nhà thuốc WG2.

## Yêu cầu đề tài

​	Hoạt động nhóm, hiểu được cách thức, phương pháp phân tích, thiết kế một hệ thống thông tin. Từ đó nắm bắt quy trình quản lý của nhà thuốc, phân tích, thiết kế hệ thống thông tin quản lý thông minh, hiện đại theo yêu cầu của nhà thuốc.


## 1. Khảo sát hệ thống

### 1. 1. Giới thiệu sơ bộ hệ thống

​	Nhà thuốc WG2 bắt đầu hoạt động từ tháng 08/2016 do bà Nguyễn Thị Am là chủ của hàng,với mục đích cung cấp các dịch vụ phục vụ cho nhu cầu chữa bệnh cho khách hàng một cách thuận tiện nhất. Nhà thuốc WG2 là nơi chuyên cung cấp các mặt hàng thuốc, thực phẩm chức năng, mĩ phẩm, dụng cụ y khoa nhằm phục vụ tốt nhất cho nhu cầu khám chữa bệnh của quý khách hàng. Với đội ngũ cán bộ 6 dược sĩ luôn học hỏi cập nhập các kiến thức chuyên môn với mong muốn được tư vấn cho khách hàng sử dụng thuốc đúng và hiệu quả. Nhà thuốc thiết lập và mở ra hệ thống website nhằm cung cấp thêm giải pháp hỗ trợ cho quý khách hàng trong việc tìm kiếm và mua các sản phẩm có bán tại Nhà thuốc. Nhà thuốc đã và đang hoạt động cung cấp thuốc trong và ngoài khu vực Hà Nội. Hiện nay với quy mô ngày càng mở rộng trong tình hình dịch bệnh hiện nhà thuốc bán lẻ tại cửa hàng và bán thuốc trực tuyến thông qua website. 

​	Địa chỉ của nhà thuốc tại: số 142, đường Chiến Thắng, xã Tân Triều, huyện Thanh Trì, thành phố Hà Nội với quy mô là 90 m2

### 1. 2. Đánh giá hiện trạng hệ thống

#### 1.2.1. Đánh giá nghiệp vụ

Các thành phần trong hệ thống nhà thuốc: 

- Quản lý kho thuốc
- Quản lý bán thuốc
- Quản lý tài chính
- Quản lý nhân sự

##### Quản lý kho thuốc 

Nhà thuốc tổ chức lưu trữ, sắp xếp thông tin về thuốc được nhập từ các nhà cung cấp thuốc sau khi được kiểm duyệt. Tuỳ theo từng thời điểm hay dựa theo nhu cầu bổ sung thuốc của kho và trình lên người quản lý. Nếu được chấp nhận sẽ tiến hành kí hợp đồng với nhà cung cấp. Sau khi kí hợp đồng mua thuốc, dược sĩ sẽ chịu trách nhiệm nhận thuốc từ nhà sản xuất, thanh toán hóa đơn nhập thuốc và báo cáo lên cán bộ cấp trên. 



##### Quản lý bán thuốc

​	Khi khách hàng có yêu cầu mua thuốc: 

- Nếu khách hàng đến mua thuốc lẻ thì nhân viên bán hàng sau khi nắm bắt được tình hình bệnh lý và khai thác dấu hiệu bệnh của khách hàng. Nhân viên bán thuốc sẽ chuẩn đoán bệnh và tư vấn cho khách hàng nên dùng loại thuốc gì (công dụng, thành phần, nước sản xuất, giá thành ) nếu khách hàng đồng ý thí nhân viên bán hàng sẽ viết hoá đơn bán hàng và hướng dẫn cách sử dụng thuốc và tránh những thứ không nên ăn trong quá trình chữa bệnh của khách hàng.
- Nếu khách khách hàng mua thuốc theo đơn thì dược sĩ sẽ kiểm tra ngày tháng của đơn thuốc, nếu quá 1 tuần thì bệnh nhân đi kháo lại và lấy đơn thuốc khác. Ngược lại kiểm tra trong kệ thuốc nếu đáp ứng được loại thuốc nào thì dược sĩ sẽ tạo hoá đơn bán hàng chuyển cho khách hàng và ghi lại vào sổ quản lý, còn các loại thuốc mà không đáp ứng được thì nhân viên bán hàng sẽ hẹn khách hàng đến mua thuốc trong thời gian sớm nhất có thể hoặc giới thiệu cho khách hàng đến mua ở những cửa hàng có uy tín khác.

​	Các thông tin trên hoá đơn bán hàng bao gồm: số hoá đơn, tên khách, địa chỉ khách, ngày lập, tổng số tiền, số tiền đã thanh toán, còn nợ, hạn trả nợ. các thông tin chi tiết về thuốc bán bao gồm: Tên thuốc, đơn vị tính, số lượng, đơn giá, thành tiền khi thanh toán cửa hàng sẽ lập một phiếu thu tương ứng với hoá đơn mua thuốc trên phiếu thu có ghi rõ: số phiếu thu, số hoá đơn, ngày lập, người lập, số tiền, ghi chú. Một bản sao của hoá đơn bán hàng (phiếu xuất ) sẽ được lưu lại để tiện cho quá trình quản lý, còn một bản giao cho khách hàng để tiện cho việc bảo hành trả nợ nếu có của khách hàng sau này cửa hàng quản lý khách hàng bằng cách cập nhật thông tin về khách hàng. Các thông tin về khách hàng bao gồm: mã khách, họ tên khách, địa chỉ, số điện thoại, email. 

##### Quản lý tài chính

​	Thu, chi của cửa hàng được nhân viên ghi vào sổ, tổng hợp lại vào mỗi ngày, tuần, tháng.

​	Sau khi kết thúc ca làm việc, nhân viên bán hàng tổng hợp doanh thu, thực thu và bàn giao cho người quản lý.

​	Người quản lý sẽ nhận báo cáo về doanh thu sau mỗi ngày và hệ thống lại doanh thu của cửa hàng.

​	Người quản lý phê duyệt ngân sách để dược sĩ nhận thuốc từ nhà sản xuất. Và nhận lại báo cáo sau mỗi lần nhân viên nhập thuốc.

##### Quản lý nhân sự:

​	Người quản lý sẽ quản lý nhân viên khi nhân viên đến cửa hàng và khi nhân viên kết thúc giờ làm việc.

​	Người quản lý chịu trách nhiệm tính tổng giờ làm, tính lương, lập phiếu chi và trả lương cho nhân viên.

#### 1.2.2. Quy tắc quản lý

​	Đối với dược sĩ

- Làm việc đúng giờ.
- Thái độ trung thực, thân thiện với khách hàng.
- Đơn bán thuốc ghi đầy đủ, rõ ràng.
- Thống kê đầy đủ doanh số bán hàng, lượng thuốc tồn kho và báo cáo cho quản lý.

​	Quản lý

- Không được lạm quyền.
- Nắm bắt được lượng tồn kho để có kế hoạch nhập thuốc.        

#### 1.2.3. Đánh giá hiện trạng

##### 1.2.4.1. Ưu điểm

​	Hệ thống đơn giản, dễ làm quen. 

##### 1.2.4.2. Nhược điểm

​	Do hệ thống làm việc trên sổ sách, không thông qua máy tính nên có một số bất cập: 

- Quản lý kho, tra cứu thuốc khó khăn, tốn nhiều thời gian.
- Phụ thuộc hoàn toàn vào con người, dễ phát sinh các sai sót.
- Khó kiểm soát thông tin về khách hàng,nhà cung cấp và thông tin về hàng hoá của cửa hàng.
- Khó thống kê tình trạng bán hàng, khó đưa ra giải pháp phát triển, nâng cao hiệu quả bán hàng.

### 1.3. Xác định yêu cầu hệ thống

#### 1.3.1. Yêu cầu về chức năng

| Chức năng              | Đầu vào                                                      | Đầu ra                                                       |
| ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Tìm kiếm thuốc         | Một trong các thông tin: Mã thuốc, tên thuốc, hoạt chất, nhóm thuốc, nhà cung cấp | Danh sách thuốc tìm được                                     |
| Tạo hóa đơn bán thuốc  | Danh sách mã thuốc, số lượng                                 | In hóa đơn gồm: Tên thuốc, đơn giá, số lượng, thành tiền     |
| Tạo hóa đơn nhập thuốc | Danh sách mã thuốc, ngày hết hạn, đơn giá, số lượng, nhà cung cấp | In hóa đơn: Tên thuốc, đơn giá, số lượng, thành tiền, nhà cung cấp |
| Tạo khoản chi          | Số tiền, Thông tin khoản chi                                 | Lưu thông tin khoản chi                                      |
| Chỉnh sửa nhân viên    | Mã nhân viên, các thông tin cá nhân, ngày làm việc, hệ số lương, các vị trí làm việc | Thêm nhân viên mới/Chỉnh sửa thông tin nhân viên             |
| Thống kê kho thuốc     | Các điều kiện lọc (khoảng thời gian, ngày hết hạn, ...)      | Thống kê kho thuốc                                           |
| Thống kê hóa đơn       | Các điều kiện lọc (Thông tin khách hàng, khoảng thời gian, ...) | Thông tin hóa đơn theo điều kiện                             |
| Thống kê tài chính     | Khoảng thời gian thống kê                                    | Báo cáo thu, chi, thuế trong khoảng thời gian đã cho         |

#### 1.3.2. Yêu cầu phi chức năng

- Hệ thống chạy nhanh, ổn định, chính xác.
- Giao diện dễ sử dụng
- Quá trình thao tác, xử lý nhanh
- Đảm bảo an toàn, chính xác
- Phải đưa ra được các thông tin cần thiết về quầy thuốc, loại thuốc
- Các phiếu nhập, xuất phải đưa ra được các thông tin cụ thể như: số phiếu, tên khách hàng, địa chỉ, tên thuốc, đơn giá… 
- Báo cáo phải xác định được chính xác về quá trình nhập, xuất, tồn kho…
- Quá trình cập nhật, sửa, xóa dễ dàng

### 1.4. Lập kế hoạch thực hiện

#### 1.4.1. Tiến độ thời gian. 

#### 1.4.2. Nhân lực (Phân công công việc, hỗ trợ, họp nhóm)

#### 1.4.3. Thiết bị (Phần cứng, Phần mềm, Yêu cầu kỹ thuật)

#### 1.4.4. Kinh phí (10 điểm)

#### 1.4.5. Nền tảng (Công cụ phát triển: CSDL, Ngôn ngữ, Công cụ kiểm thử,... )

#### 1.4.6. Đặc tả hệ thống (UML)
