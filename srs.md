## 1. STAKEHOLDERS

| STT | Stakeholder | Vai trò |
|-----|-------------|---------|
| 1 | Khách hàng | Người sử dụng hệ thống để đăng ký tài khoản, đăng nhập, cập nhật thông tin cá nhân, đặt xe, theo dõi chuyến đi, thanh toán và đánh giá tài xế. |
| 2 | Tài xế | Người nhận và thực hiện chuyến xe; cập nhật thông tin cá nhân, phương tiện, trạng thái hoạt động và trạng thái chuyến đi. |
| 3 | Nhân viên vận hành | Quản lý và giám sát hoạt động của hệ thống; quản lý khách hàng, tài xế, phương tiện và chuyến đi; hỗ trợ xử lý các trường hợp phát sinh. |
| 4 | Ban lãnh đạo doanh nghiệp | Theo dõi tình hình hoạt động thông qua các báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. |
| 5 | Nhà cung cấp dịch vụ thanh toán | Cung cấp dịch vụ thanh toán điện tử cho hệ thống CAB System. |
| 6 | Nhà cung cấp dịch vụ thông báo | Cung cấp các kênh gửi thông báo đến khách hàng và tài xế. |
| 7 | Business Analyst (BA) | Làm rõ các yêu cầu với các bên liên quan, xác định phạm vi, tác nhân, quy trình nghiệp vụ, yêu cầu chức năng, yêu cầu phi chức năng và các quy tắc nghiệp vụ. |
| 8 | Nhóm phát triển hệ thống | Phân tích, thiết kế, xây dựng và triển khai hệ thống dựa trên các yêu cầu đã được xác định trong tài liệu SRS. |

## 2. STAKEHOLDER MATRIX

| Stakeholder | Power | Interest | Expectation / Need | Management Strategy |
|---|---|---|---|---|
| Khách hàng | Cao | Cao | Đặt xe nhanh, dễ dàng; theo dõi chuyến đi; biết thông tin tài xế; thanh toán và đánh giá tài xế. | Manage Closely |
| Tài xế | Cao | Cao | Nhận chuyến phù hợp; biết thông tin chuyến; cập nhật trạng thái và vị trí; quản lý hồ sơ và phương tiện. | Manage Closely |
| Nhân viên vận hành | Cao | Cao | Quản lý khách hàng, tài xế, phương tiện, chuyến đi và xử lý các trường hợp phát sinh. | Manage Closely |
| Ban lãnh đạo doanh nghiệp | Cao | Trung bình | Theo dõi số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. | Keep Satisfied |
| Nhà cung cấp dịch vụ thanh toán | Cao | Trung bình | Cung cấp dịch vụ thanh toán điện tử ổn định và an toàn. | Keep Satisfied |
| Nhà cung cấp dịch vụ thông báo | Trung bình | Trung bình | Đảm bảo gửi thông báo liên quan đến đặt xe, chuyến đi và thanh toán. | Keep Informed |
| Business Analyst (BA) | Cao | Cao | Làm rõ yêu cầu, quy trình nghiệp vụ và các vấn đề chưa được xác định. | Manage Closely |
| Nhóm phát triển hệ thống | Cao | Cao | Có yêu cầu rõ ràng để phân tích, thiết kế, xây dựng và triển khai hệ thống. | Manage Closely |

## 3. BUSINESS GOALS

| ID | Business Goal | Description | Expected Outcome |
|---|---|---|---|
| BG01 | Đơn giản hóa quy trình đặt xe | Cung cấp nền tảng giúp khách hàng nhập điểm đón, điểm trả, chọn loại xe và thực hiện đặt xe một cách nhanh chóng, thuận tiện. | Khách hàng có thể đặt xe dễ dàng và giảm thời gian thực hiện đặt xe. |
| BG02 | Tự động hóa việc phân công tài xế | Hệ thống tự động tìm kiếm và phân công tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành. | Giảm thao tác thủ công và tăng hiệu quả phân công chuyến xe. |
| BG03 | Theo dõi và quản lý chuyến xe | Cho phép khách hàng theo dõi trạng thái chuyến đi, thông tin tài xế và thời gian dự kiến đến; đồng thời hỗ trợ nhân viên vận hành quản lý các chuyến đang hoạt động. | Tăng khả năng kiểm soát và minh bạch trong quá trình phục vụ khách hàng. |
| BG04 | Hỗ trợ thanh toán linh hoạt | Hỗ trợ thanh toán bằng tiền mặt hoặc thanh toán điện tử thông qua nhà cung cấp dịch vụ thanh toán bên ngoài. | Tạo sự thuận tiện cho khách hàng và đảm bảo kết quả thanh toán được cập nhật trên hệ thống. |
| BG05 | Nâng cao chất lượng dịch vụ | Cho phép khách hàng đánh giá chuyến đi sau khi hoàn thành và cung cấp thông tin để theo dõi hiệu suất tài xế. | Có cơ sở để đánh giá và cải thiện chất lượng dịch vụ. |
| BG06 | Hỗ trợ quản lý và vận hành | Cung cấp chức năng quản lý khách hàng, tài xế, phương tiện, chuyến xe, trạng thái tài xế và lịch sử giao dịch. | Nhân viên vận hành có thể quản lý hoạt động của hệ thống hiệu quả hơn. |
| BG07 | Cung cấp báo cáo hoạt động | Hỗ trợ thống kê số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu suất tài xế. | Hỗ trợ doanh nghiệp theo dõi tình hình hoạt động và đưa ra quyết định quản lý. |
| BG08 | Đảm bảo an toàn và khả năng mở rộng | Bảo vệ dữ liệu người dùng, phương tiện, vị trí và giao dịch; đồng thời thiết kế hệ thống có khả năng mở rộng khi bổ sung dịch vụ hoặc nhà cung cấp mới. | Hệ thống hoạt động ổn định, an toàn và có thể phát triển trong tương lai. |

