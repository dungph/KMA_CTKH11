# Lý do chọn đề tài

Với thực trạng hiện nay đó là công việc quản lý diễn ra trên giấy tờ, nhưng khối lượng dữ liệu thì ngày một lớn. Vì vậy phần mềm "Quản lý hiệu thuốc" ra đời nhằm giải quyết những khó khăn trên giúp cho công việc quản lí trở nên đơn giản, hiệu quả và chính xác hơn bằng việc tự động hóa quá trình quản lý các yếu tố liên quan như thuốc, hóa đơn, nhân viên, khách hàng…

# Phạm vi đề tài

Phân tích, thiết kế hệ thống quản lý nhà thuốc áp dụng cho nhà thuốc WG2.

# Yêu cầu đề tài

Hoạt động nhóm, hiểu được cách thức, phương pháp phân tích, thiết kế một hệ thống thông tin. Từ đó nắm bắt quy trình quản lý của nhà thuốc, phân tích, thiết kế hệ thống thông tin quản lý thông minh, hiện đại theo yêu cầu của nhà thuốc.


# 1. Khảo sát hệ thống

## 1.1. Giới thiệu sơ bộ hệ thống

Nhà thuốc WG2 bắt đầu hoạt động từ tháng 08/2016 do bà Nguyễn Thị Am là chủ của hàng,với mục đích cung cấp các dịch vụ phục vụ cho nhu cầu chữa bệnh cho khách hàng một cách thuận tiện nhất. Nhà thuốc WG2 là nơi chuyên cung cấp các mặt hàng thuốc, thực phẩm chức năng, mĩ phẩm, dụng cụ y khoa nhằm phục vụ tốt nhất cho nhu cầu khám chữa bệnh của quý khách hàng. Với đội ngũ cán bộ 6 dược sĩ luôn học hỏi cập nhập các kiến thức chuyên môn với mong muốn được tư vấn cho khách hàng sử dụng thuốc đúng và hiệu quả. Nhà thuốc thiết lập và mở ra hệ thống website nhằm cung cấp thêm giải pháp hỗ trợ cho quý khách hàng trong việc tìm kiếm và mua các sản phẩm có bán tại Nhà thuốc. Nhà thuốc đã và đang hoạt động cung cấp thuốc trong và ngoài khu vực Hà Nội. Hiện nay với quy mô ngày càng mở rộng trong tình hình dịch bệnh hiện nhà thuốc bán lẻ tại cửa hàng và bán thuốc trực tuyến thông qua website. 

Địa chỉ của nhà thuốc tại: số 142, đường Chiến Thắng, xã Tân Triều, huyện Thanh Trì, thành phố Hà Nội với quy mô là 90 m2

## 1.2. Đánh giá hiện trạng hệ thống

### 1.2.1. Đánh giá nghiệp vụ

Các thành phần trong hệ thống nhà thuốc: 

- Quản lý kho thuốc
- Quản lý bán thuốc
- Quản lý tài chính
- Quản lý nhân sự

#### Quản lý kho thuốc 

Nhà thuốc tổ chức lưu trữ, sắp xếp thông tin về thuốc được nhập từ các nhà cung cấp thuốc sau khi được kiểm duyệt. Tuỳ theo từng thời điểm hay dựa theo nhu cầu bổ sung thuốc của kho và trình lên người quản lý. Nếu được chấp nhận sẽ tiến hành kí hợp đồng với nhà cung cấp. Sau khi kí hợp đồng mua thuốc, dược sĩ sẽ chịu trách nhiệm nhận thuốc từ nhà sản xuất, thanh toán hóa đơn nhập thuốc và báo cáo lên cán bộ cấp trên. 



#### Quản lý bán thuốc

Khi khách hàng có yêu cầu mua thuốc: 

- Nếu khách hàng đến mua thuốc lẻ thì nhân viên bán hàng sau khi nắm bắt được tình hình bệnh lý và khai thác dấu hiệu bệnh của khách hàng. Nhân viên bán thuốc sẽ chuẩn đoán bệnh và tư vấn cho khách hàng nên dùng loại thuốc gì (công dụng, thành phần, nước sản xuất, giá thành ) nếu khách hàng đồng ý thí nhân viên bán hàng sẽ viết hoá đơn bán hàng và hướng dẫn cách sử dụng thuốc và tránh những thứ không nên ăn trong quá trình chữa bệnh của khách hàng.
- Nếu khách khách hàng mua thuốc theo đơn thì dược sĩ sẽ kiểm tra ngày tháng của đơn thuốc, nếu quá 1 tuần thì bệnh nhân đi kháo lại và lấy đơn thuốc khác. Ngược lại kiểm tra trong kệ thuốc nếu đáp ứng được loại thuốc nào thì dược sĩ sẽ tạo hoá đơn bán hàng chuyển cho khách hàng và ghi lại vào sổ quản lý, còn các loại thuốc mà không đáp ứng được thì nhân viên bán hàng sẽ hẹn khách hàng đến mua thuốc trong thời gian sớm nhất có thể hoặc giới thiệu cho khách hàng đến mua ở những cửa hàng có uy tín khác.

Các thông tin trên hoá đơn bán hàng bao gồm: số hoá đơn, tên khách, địa chỉ khách, ngày lập, tổng số tiền, số tiền đã thanh toán, còn nợ, hạn trả nợ. các thông tin chi tiết về thuốc bán bao gồm: Tên thuốc, đơn vị tính, số lượng, đơn giá, thành tiền khi thanh toán cửa hàng sẽ lập một phiếu thu tương ứng với hoá đơn mua thuốc trên phiếu thu có ghi rõ: số phiếu thu, số hoá đơn, ngày lập, người lập, số tiền, ghi chú. Một bản sao của hoá đơn bán hàng (phiếu xuất ) sẽ được lưu lại để tiện cho quá trình quản lý, còn một bản giao cho khách hàng để tiện cho việc bảo hành trả nợ nếu có của khách hàng sau này cửa hàng quản lý khách hàng bằng cách cập nhật thông tin về khách hàng. Các thông tin về khách hàng bao gồm: mã khách, họ tên khách, địa chỉ, số điện thoại, email. 

#### Quản lý tài chính

Thu, chi của cửa hàng được nhân viên ghi vào sổ, tổng hợp lại vào mỗi ngày, tuần, tháng.

Sau khi kết thúc ca làm việc, nhân viên bán hàng tổng hợp doanh thu, thực thu và bàn giao cho người quản lý.

Người quản lý sẽ nhận báo cáo về doanh thu sau mỗi ngày và hệ thống lại doanh thu của cửa hàng.

Người quản lý phê duyệt ngân sách để dược sĩ nhận thuốc từ nhà sản xuất. Và nhận lại báo cáo sau mỗi lần nhân viên nhập thuốc.

#### Quản lý nhân sự:

Người quản lý sẽ quản lý nhân viên khi nhân viên đến cửa hàng và khi nhân viên kết thúc giờ làm việc.

Người quản lý chịu trách nhiệm tính tổng giờ làm, tính lương, lập phiếu chi và trả lương cho nhân viên.

### 1.2.2. Quy tắc quản lý

Đối với dược sĩ

- Làm việc đúng giờ.
- Thái độ trung thực, thân thiện với khách hàng.
- Đơn bán thuốc ghi đầy đủ, rõ ràng.
- Thống kê đầy đủ doanh số bán hàng, lượng thuốc tồn kho và báo cáo cho quản lý.

Quản lý

- Không được lạm quyền.
- Nắm bắt được lượng tồn kho để có kế hoạch nhập thuốc.        

### 1.2.3. Đánh giá hiện trạng

#### 1.2.4.1. Ưu điểm

Hệ thống đơn giản, dễ làm quen. 

#### 1.2.4.2. Nhược điểm

Do hệ thống làm việc trên sổ sách, không thông qua máy tính nên có một số bất cập: 

- Quản lý kho, tra cứu thuốc khó khăn, tốn nhiều thời gian.
- Phụ thuộc hoàn toàn vào con người, dễ phát sinh các sai sót.
- Khó kiểm soát thông tin về khách hàng,nhà cung cấp và thông tin về hàng hoá của cửa hàng.
- Khó thống kê tình trạng bán hàng, khó đưa ra giải pháp phát triển, nâng cao hiệu quả bán hàng.

## 1.3. Xác định yêu cầu hệ thống

### 1.3.1. Yêu cầu về chức năng

#### 1.3.1.1. Đăng nhập

| Tên chức năng     | Đăng nhập                                                    |
| :---------------- | ------------------------------------------------------------ |
| Đối tượng sử dụng | Nhân viên bán thuốc, Quản lý                                 |
| Điều kiện đầu vào | Nhân viên đã có tên trong danh sách nhân viên                |
| Nội dung          | Cho phép người dùng đăng nhập vào hệ thống                   |
| Cách xử lý        | 1. Người dùng chọn tên và nhập mật khẩu. Nhấn nút đăng nhập<br />2. Hệ thống kiểm tra dữ liệu người dùng. Nếu thành công thì chuyển sang trang quản lý người dùng. Nếu thất bại thì in ra thông báo. |
| Kết quả           | Đăng nhập thành công hoặc thất bại                           |
| Ghi chú           |                                                              |

#### 1.3.1.2. Đăng xuất

| Tên chức năng     | Đăng xuất                                                    |
| :---------------- | ------------------------------------------------------------ |
| Đối tượng sử dụng | Nhân viên bán thuốc, Quản lý                                 |
| Điều kiện đầu vào | Đã đăng nhập thành công                                      |
| Nội dung          | Cho phép người dùng đăng xuất khỏi hệ thống                  |
| Cách xử lý        | 1. Người dùng nhấn nút đăng xuất<br />2. Hệ thống đăng xuất, hiển thị trang đăng nhập. |
| Kết quả           | Đăng xuất thành công.                                        |
| Ghi chú           |                                                              |

#### 1.3.1.3. Tìm kiếm thuốc

| Tên chức năng     | Tìm kiếm thuốc                                               |
| :---------------- | ------------------------------------------------------------ |
| Đối tượng sử dụng | Nhân viên bán thuốc, quản lý                                 |
| Điều kiện đầu vào | Không                                                        |
| Nội dung          | Tìm kiếm thuốc theo thông tin cho trước                      |
| Cách xử lý        | 1. Người dùng nhấn vào thanh tìm kiếm<br />2. Người dùng nhập vào ít nhất một thông tin về mã thuốc, tên thuốc, hoạt chất, nhóm thuốc, nhà cung cấp<br />3. Hệ thống tìm kiếm trong cơ sở dữ liệu các loại thuốc tương ứng, in ra màn hình.<br />4. Nếu người dùng đã đăng nhập, hiển thị mục "Tạo đơn hàng" trên mỗi mục. Chuyển đến trang "Bán thuốc" với loại thuốc tương ứng. |
| Kết quả           | Hiển thị danh sách thuốc tìm được (các thông tin về thuốc, vị trí đặt thuốc) |
| Ghi chú           | Các thông tin về thuốc: Mã thuốc, tên thuốc, hoạt chất, nhóm thuốc, nhà cung cấp, ngày hết hạn, đơn giá, lượng tồn kho. |

#### 1.3.1.4. Bán thuốc

| Tên chức năng     | Bán thuốc                                                    |
| :---------------- | ------------------------------------------------------------ |
| Đối tượng sử dụng | Nhân viên bán thuốc                                          |
| Điều kiện đầu vào | Người dùng đã đăng nhập hệ thống                             |
| Nội dung          | Tạo hóa đơn bán thuốc                                        |
| Cách xử lý        | 1. Người dùng chọn mục "Bán thuốc/Bán thuốc"<br />2. Người dùng tìm kiếm thuốc tại thanh tìm kiếm, chọn loại thuốc tìm được (kèm số lượng).  Nếu số lượng thuốc không đủ, in thông báo ra màn hình<br />3. Hệ thống hiển thị thông tin đơn hàng: Loại thuốc, đơn giá, thành tiền, tổng hóa<br />đơn, thuế, số tiền khách đưa, số tiền trả lại, người lập hóa đơn, thông tin liên hệ.<br />4. Người dùng nhấn vào nút "Hoàn thành", hệ thống lưu hóa đơn, giảm số lượng<br />các loại thuốc ghi trong hóa đơn và tăng số tiền trong kho tương ứng với giá trị hóa đơn. |
| Kết quả           | Tạo hóa đơn thành công hoặc thất bại                         |
| Ghi chú           |                                                              |

#### 1.3.1.5. Nhập thuốc

| Tên chức năng     | Nhập thuốc                                                   |
| :---------------- | ------------------------------------------------------------ |
| Đối tượng sử dụng | Quản lý                                                      |
| Điều kiện đầu vào | Người dùng đã đăng nhập hệ thống                             |
| Nội dung          | Tạo hóa đơn nhập thuốc                                       |
| Cách xử lý        | 1. Người dùng chọn mục "Kho thuốc/Nhập thuốc"<br />2. Nhập các thông tin về thuốc, số lượng và nhấn vào nút "Nhập"<br />3. Hệ thống lưu hóa đơn, tăng số lượng thuốc theo biểu mẫu nhập. |
| Kết quả           | Nhập thành công hoặc thất bại                                |
| Ghi chú           | Thông tin về thuốc: Mã thuốc, tên thuốc, hoạt chất, nhóm thuốc, nhà cung cấp, ngày hết hạn, đơn giá. |

#### 1.3.1.6. Tạo khoản chi

| Tên chức năng     | Tạo khoản chi                                                |
| :---------------- | ------------------------------------------------------------ |
| Đối tượng sử dụng | Quản lý                                                      |
| Điều kiện đầu vào | Người dùng đã đăng nhập vào hệ thống                         |
| Nội dung          | Tạo khoản chi                                                |
| Cách xử lý        | 1. Người dùng chọn mục "Tài chính/Tạo khoản chi"<br />2. Nhập số tiền và nội dung khoản chi. Nếu số tiền vượt quá số tiền<br />trong kho thì thông báo ra màn hình và yêu cầu người dùng nhập số tiền nhỏ hơn.<br />3. Người dùng nhấn vào nút "Rút". Hệ thống trừ số tiền tương ứng. |
| Kết quả           | Rút thành công hoặc thất bại                                 |
| Ghi chú           |                                                              |

#### 1.3.1.7. Quản lý nhân viên

| Tên chức năng     | Quản lý nhân viên                                            |
| :---------------- | ------------------------------------------------------------ |
| Đối tượng sử dụng | Quản lý, Quản trị viên                                       |
| Điều kiện đầu vào | Người dùng đã đăng nhập vào hệ thống                         |
| Nội dung          | Chỉnh sửa thông tin nhân viên                                |
| Cách xử lý        | 1. Người dùng chọn mục "Nhân viên"<br />2. Hệ thống in ra danh sách thông tin nhân viên và nút "Tạo mới nhân viên".<br />3. Nếu người dùng nhấn nút tạo mới, hệ thống tạo một nhân viên mới vào cuối<br />danh sách cho người dùng nhập thông tin. Nếu người dùng là Quản lý thì không được thay đổi chức vụ của nhân viên<br />4. Người dùng nhấn "Lưu", hệ thống lưu các chỉnh sửa của người dùng. |
| Kết quả           | Chỉnh sửa thành công hoặc thất bại                           |
| Ghi chú           | Thông tin nhân viên bao gồm: Tên nhân viên, giới tính, năm sinh, chức vụ (Nhân viên bán hàng hoặc/và Quản lý). |

#### 1.3.1.8. Thống kê kho thuốc

| Tên chức năng     | Thống kê kho thuốc                                           |
| :---------------- | ------------------------------------------------------------ |
| Đối tượng sử dụng | Nhân viên bán hàng, Quản lý                                  |
| Điều kiện đầu vào | Người dùng đã đăng nhập vào hệ thống                         |
| Nội dung          | Thống kê lượng tồn kho                                       |
| Cách xử lý        | 1. Người dùng chọn trang "Kho thuốc/Thống kê"<br />2. Hệ thống tính toán, đưa ra danh sách các loại thuốc<br />3. Nếu người dùng chọn mục "Số lượng", đưa ra thông tin các loại thuốc đã hết/sắp hết số lượng.<br />4. Nếu ngời dùng chọn mục "Hạn sử dụng", đưa ra thông tin các loại thuốc đã quá hạn/sắp hết hạn. |
| Kết quả           | Danh sách các loại thuốc tìm được.                           |
| Ghi chú           | Các thông tin về thuốc: Mã thuốc, tên thuốc, hoạt chất, nhóm thuốc, nhà cung cấp, ngày hết hạn, đơn giá, lượng tồn kho. |

#### 1.3.1.9. Thống kê hóa đơn

| Tên chức năng     | Thống kê hóa đơn                                             |
| :---------------- | ------------------------------------------------------------ |
| Đối tượng sử dụng | Nhân viên bán hàng, quản lý                                  |
| Điều kiện đầu vào | Người dùng đã đăng nhập vào hệ thống                         |
| Nội dung          | Đưa ra danh sách hóa đơn trong khoảng thời gian cho trước.   |
| Cách xử lý        | 1. Người dùng chọn trang "Bán thuốc/Hóa đơn"<br />2. Người dùng chọn khoảng thời gian thống kê và nhấn nút "Thống kê"<br />3. Hệ thống truy vấn, in ra danh sách hóa đơn trong khoảng thời gian đã nhập. |
| Kết quả           | Danh sách hóa đơn                                            |
| Ghi chú           | Thông tin trong danh sách bao gồm: Mã hóa đơn, thời gian tạo, số tiền, người lập hóa đơn. |

#### 1.3.1.10. Thống kê tài chính

| Tên chức năng     | Thống kê tài chính                                           |
| :---------------- | ------------------------------------------------------------ |
| Đối tượng sử dụng | Nhân viên bán hàng, Quản lý                                  |
| Điều kiện đầu vào | Người dùng đã đăng nhập vào hệ thống                         |
| Nội dung          | Thống kê lượng tiền vào/ra trong khoảng thời gian cho trước. |
| Cách xử lý        | 1. Người dùng chọn trang "Tài chính/Thống kê"<br />2. Người dùng chọn khoảng thời gian thống kê, nhập khoảng thời gian thống kê.<br />3. Hệ thống tìm kiếm các khoản chi, hóa đơn bán hàng trong khoảng thời gian đã nhập, hiển thị ra màn hình. |
| Kết quả           | Lượng tiền vào/ra trong khoảng thời gian đã nhập, danh sách các hóa đơn, khoản chi trong thời gian tương ứng. |
| Ghi chú           |                                                              |

### 1.3.2. Yêu cầu phi chức năng

- Tuân thủ các nguyên tắc kế toán.
- Hệ thống chạy nhanh, ổn định, chính xác.
- Giao diện dễ sử dụng
- Quá trình thao tác, xử lý nhanh
- Đảm bảo an toàn, chính xác
- Phải đưa ra được các thông tin cần thiết về quầy thuốc, loại thuốc
- Các phiếu nhập, xuất phải đưa ra được các thông tin cụ thể như: số phiếu, tên khách hàng, địa chỉ, tên thuốc, đơn giá… 
- Báo cáo phải xác định được chính xác về quá trình nhập, xuất, tồn kho…
- Quá trình cập nhật, sửa, xóa dễ dàng

# 2. Thiết kế hệ thống

## 2.1. Tiến độ thời gian.

Thời gian thiết kế: 2 tháng

Thời gian thi công, kiểm thử, triển khai: 2 tháng

## 2.2 Nhân lực

Nhóm bao gồm 5 thành viên tham gia trao đổi, đóng góp trên tất cả các công đoạn phân tích, thiết kế và phát triển.

## 2.3 Thiết bị

Máy chủ linux, thiết bị hiển thị tương tác với người dùng: trình duyệt web trên máy tính, trình duyệt web trên điện thoại.

## 2.4. Kinh phí

## 2.5. Nền tảng

Công cụ quản lý mã nguồn: Git - Phần mềm quản lý mã nguồn phổ biến và dễ sử dụng, giúp nhiều thành viên trong nhóm dễ dàng làm chung trong dự án.

Cơ sở dữ liệu quan hệ mã nguồn mở Postgres cho tốc độ cao.

Ngôn ngữ lập trình Rust cho tốc độ cao, tiêu tốn ít tài nguyên hệ thống, ngăn chặn lỗi về bộ nhớ, luồng, ... Giúp tăng trải nghiệm người dùng và hỗ trợ nhóm phát triển. Giao diện web sử dụng Html, Css được xử lý bởi máy chủ.

Kiểm thử được hỗ trợ trực tiếp bởi Rust, kiểm thử chạy tự động trên hệ thống Github Action.

## 2.6. Đặc tả hệ thống

### 2.6.1. Biểu đồ usecase

#### 2.6.1.1. Usecase tổng quát

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/usecase/general.png)

#### 2.6.1.2. Usecase bán hàng

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/usecase/pos.png)

#### 2.6.1.3. Usecase quản lý thuốc

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/usecase/medicine_manage.png)

#### 2.6.1.4. Usecase quản lý hóa đơn bán hàng

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/usecase/bills.png)

#### 2.6.1.5. Usecase quản lý nhân viên

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/usecase/staff.png)

#### 2.6.1.6. Usecase quản lý tài chính

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/usecase/finance.png)



### 2.6.2. Biểu đồ lớp

### 2.6.3. Biểu đồ trình tự

#### 2.6.3.1. Biểu đồ trình tự đăng nhập

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/session_login.drawio.png)

#### 2.6.3.2. Biểu đồ trình tự đăng xuất

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/session_signout.drawio.png)

#### 2.6.3.3. Biểu đồ trình tự bán hàng

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/pos_sequence.drawio.png)

#### 2.6.3.4. Biểu đồ trình tự kiểm tra hóa đơn bán hàng

![bill_check.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/bill_check.drawio.png)

#### 2.6.3.5. Biểu đồ trình tự hủy hóa đơn bán hàng

![bill_cancel.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/bill_cancel.drawio.png)

#### 2.6.3.6. Biểu đồ trình tự thống kê hóa đơn bán hàng

![bill_statistic.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/bill_statistic.drawio.png)

#### 2.6.3.7. Biểu đồ trình tự tìm kiếm sản phẩm

![product_find.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/product_find.drawio.png)

#### 2.6.3.8. Biểu đồ trình tự sửa thông tin sản phẩm

![product_data_change.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/product_data_change.drawio.png)

#### 2.6.3.9. Biểu đồ trình tự nhập sản phẩm

![product_import.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/product_import.drawio.png)

#### 2.6.3.10. Biểu đồ trình tự xuất sản phẩm

![product_export.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/product_export.drawio.png)

#### 2.6.3.11. Biểu đồ trình tự thống kê sản phẩm

![product_statistic.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/product_statistic.drawio.png)

#### 2.6.3.12. Biểu đồ trình tự kiểm tra tài chính

![finance_check.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/finance_check.drawio.png)

#### 2.6.3.13. Biểu đồ trình tự tạo phiếu thu

![finance_in.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/finance_in.drawio.png)

#### 2.6.3.14. Biểu đồ trình tự tạo phiếu chi

![finance_out.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/finance_out.drawio.png)

#### 2.6.3.15. Biểu đồ trình tự thống kê tài chính

![finance_statistic.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/finance_statistic.drawio.png)

#### 2.6.3.16. Biểu đồ trình tự tạo nhân viên mới

![staff_new.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/staff_new.drawio.png)

#### 2.6.3.17. Biểu đồ trình tự sửa thông tin nhân viên

![staff_change_info.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/staff_change_info.drawio.png)

#### 2.6.3.18. Biểu đồ trình tự danh sách nhân viên

![staff_list.drawio](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sequence/staff_list.drawio.png)





### 2.6.4. Biểu đồ hoạt động

#### 2.6.4.1. Biểu đồ hoạt động bán hàng

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/activity/pos.drawio.png)

#### 2.6.4.2. Biểu đồ hoạt động kiểm tra đơn hàng

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/activity/bill_check.drawio.png)

#### 2.6.4.3. Biểu đồ hoạt động hủy đơn hàng

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/activity/bill_cancel.drawio.png)

#### 2.6.4.4. Biểu đồ hoạt động thống kê bán hàng

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/activity/bill_statistic.drawio.png)

#### 2.6.4.5. Biểu đồ hoạt động nhập hàng

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/activity/product_import.drawio.png)

#### 2.6.4.6. Biểu đồ hoạt động sửa thông tin sản phẩm

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/activity/product_change_info.drawio.png)

#### 2.6.4.7. Biểu đồ hoạt động tạo phiếu thu

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/activity/finance_in.drawio.png)

#### 2.6.4.8. Biểu đồ hoạt động thêm nhân viên mới

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/activity/staff_new.drawio.png)

#### 2.6.4.9. Biểu đồ hoạt động thay đổi thông tin nhân viên

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/activity/staff_change_info.drawio.png)



### 2.6.5. Biểu đồ thành phần

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/components.drawio.png)

### 2.6.6. Biểu đồ triển khai

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/deploy.drawio.png)

### 2.6.7. Cơ sở dữ liệu

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/sql.png)

### 2.6.8. Giao diện phần mềm

#### 2.6.8.1. Giao diện đăng nhập

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/login.jpg)

#### 2.6.8.2. Giao diện bán hàng

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/pos.png)

#### 2.6.8.3. Giao diện quản lý sản phẩm

![](https://raw.githubusercontent.com/dungph/KMA_CTKH11/main/diagram/product_management.jpg)
