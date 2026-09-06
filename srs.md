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

## 4. MVP MODULES

| ID | Module | Main Functions | Main Stakeholders |
|---|---|---|---|
| MVP01 | Quản lý tài khoản | Đăng ký, đăng nhập, quản lý thông tin cá nhân của khách hàng và tài xế. | Khách hàng, Tài xế |
| MVP02 | Đặt xe | Nhập điểm đón, điểm trả, chọn loại xe và gửi yêu cầu đặt xe. | Khách hàng |
| MVP03 | Tìm kiếm và phân công tài xế | Tìm tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành; tự động tiếp tục tìm tài xế khác nếu tài xế từ chối hoặc không phản hồi. | Khách hàng, Tài xế, Nhân viên vận hành |
| MVP04 | Quản lý chuyến xe | Nhận chuyến, chấp nhận/từ chối chuyến và cập nhật trạng thái: đã đến điểm đón, đã đón khách, đang di chuyển và hoàn thành chuyến. | Tài xế, Nhân viên vận hành |
| MVP05 | Theo dõi chuyến xe | Theo dõi trạng thái chuyến, vị trí/thông tin tài xế và thời gian dự kiến đến. | Khách hàng |
| MVP06 | Thanh toán | Tính cước chuyến đi và hỗ trợ thanh toán bằng tiền mặt hoặc thanh toán điện tử. | Khách hàng, Nhà cung cấp thanh toán |
| MVP07 | Thông báo | Gửi thông báo về việc đặt xe, phân công tài xế, tài xế đến điểm đón, hoàn thành chuyến và kết quả thanh toán. | Khách hàng, Tài xế |
| MVP08 | Đánh giá chuyến đi | Cho phép khách hàng đánh giá chuyến đi sau khi hoàn thành. | Khách hàng |
| MVP09 | Quản lý vận hành | Quản lý khách hàng, tài xế, phương tiện, chuyến xe, trạng thái tài xế và lịch sử giao dịch. | Nhân viên vận hành |
| MVP10 | Báo cáo | Thống kê số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu suất tài xế. | Nhân viên vận hành, Ban lãnh đạo |

## 5. BUSINESS REQUIREMENTS

| ID | Business Requirement | Description | Priority |
|---|---|---|---|
| BR01 | Quản lý tài khoản khách hàng | Khách hàng có thể đăng ký, đăng nhập và quản lý thông tin cá nhân. | Must Have |
| BR02 | Đặt xe | Khách hàng nhập điểm đón, điểm trả và lựa chọn loại xe để đặt chuyến. | Must Have |
| BR03 | Phân công tài xế | Hệ thống tìm và phân công tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành. | Must Have |
| BR04 | Quản lý chuyến xe | Tài xế có thể nhận, chấp nhận hoặc từ chối chuyến và cập nhật trạng thái chuyến xe. | Must Have |
| BR05 | Theo dõi chuyến xe | Khách hàng có thể theo dõi trạng thái chuyến, thông tin tài xế và thời gian dự kiến đến. | Must Have |
| BR06 | Thanh toán | Hệ thống hỗ trợ thanh toán bằng tiền mặt hoặc thanh toán điện tử thông qua nhà cung cấp bên ngoài. | Must Have |
| BR07 | Thông báo | Hệ thống gửi thông báo về đặt xe, phân công tài xế, tài xế đến, hoàn thành chuyến và kết quả thanh toán. | Must Have |
| BR08 | Đánh giá chuyến đi | Khách hàng có thể đánh giá chuyến xe sau khi hoàn thành. | Should Have |
| BR09 | Quản lý tài xế | Nhân viên vận hành có thể quản lý thông tin, phương tiện và trạng thái hoạt động của tài xế. | Must Have |
| BR10 | Quản lý khách hàng | Nhân viên vận hành có thể quản lý thông tin khách hàng. | Must Have |
| BR11 | Quản lý chuyến xe | Nhân viên vận hành có thể theo dõi các chuyến đang hoạt động và xử lý các vấn đề phát sinh. | Must Have |
| BR12 | Quản lý giao dịch | Hệ thống hỗ trợ lưu trữ và tra cứu lịch sử giao dịch. | Must Have |
| BR13 | Báo cáo hoạt động | Hệ thống cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu suất tài xế. | Should Have |
| BR14 | Bảo mật dữ liệu | Hệ thống phải bảo vệ dữ liệu cá nhân, thông tin phương tiện, vị trí và giao dịch của người dùng. | Must Have |
| BR15 | Phân quyền truy cập | Hệ thống kiểm soát quyền truy cập dựa trên vai trò của người dùng. | Must Have |
| BR16 | Khả năng mở rộng | Hệ thống có khả năng mở rộng khi bổ sung dịch vụ, phương thức thanh toán hoặc nhà cung cấp thông báo mới. | Should Have |
| BR17 | Tính ổn định | Hệ thống phải hoạt động ổn định khi nhu cầu đặt xe tăng cao. | Must Have |

## 6. BUSINESS PROCESS MODELING

### 6.1 Customer Booking Process

| Step | Actor | Business Process |
|---|---|---|
| 1 | Customer | Đăng nhập vào hệ thống. |
| 2 | Customer | Nhập điểm đón và điểm trả. |
| 3 | Customer | Chọn loại xe và gửi yêu cầu đặt xe. |
| 4 | CAB System | Tiếp nhận yêu cầu đặt xe. |
| 5 | CAB System | Tìm kiếm tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành. |
| 6 | CAB System | Gửi yêu cầu chuyến xe đến tài xế phù hợp. |
| 7 | Driver | Chấp nhận hoặc từ chối chuyến xe. |
| 8 | CAB System | Nếu tài xế từ chối hoặc không phản hồi, tiếp tục tìm tài xế khác. |
| 9 | CAB System | Thông báo kết quả phân công cho khách hàng. |
| 10 | Customer | Theo dõi thông tin và trạng thái chuyến xe. |

### 6.2 Trip Management Process

| Step | Actor | Business Process |
|---|---|---|
| 1 | Driver | Nhận và chấp nhận chuyến xe. |
| 2 | Driver | Di chuyển đến điểm đón. |
| 3 | Driver | Cập nhật trạng thái đã đến điểm đón. |
| 4 | Driver | Đón khách và cập nhật trạng thái đã đón khách. |
| 5 | Driver | Di chuyển đến điểm trả. |
| 6 | Driver | Cập nhật trạng thái đang di chuyển. |
| 7 | Driver | Hoàn thành chuyến xe. |
| 8 | CAB System | Cập nhật trạng thái chuyến xe thành hoàn thành. |
| 9 | CAB System | Tính cước chuyến đi. |

### 6.3 Payment Process

| Step | Actor | Business Process |
|---|---|---|
| 1 | CAB System | Tính số tiền cần thanh toán sau khi chuyến xe hoàn thành. |
| 2 | Customer | Chọn phương thức thanh toán. |
| 3 | Customer | Thanh toán bằng tiền mặt hoặc thanh toán điện tử. |
| 4 | Payment Provider | Xử lý giao dịch thanh toán điện tử. |
| 5 | CAB System | Nhận kết quả giao dịch. |
| 6 | CAB System | Thông báo kết quả thanh toán cho khách hàng. |
| 7 | CAB System | Cho phép thực hiện lại giao dịch nếu thanh toán thất bại theo chính sách. |

### 6.4 Driver Assignment Process

| Step | Actor | Business Process |
|---|---|---|
| 1 | CAB System | Nhận yêu cầu đặt xe từ khách hàng. |
| 2 | CAB System | Kiểm tra các tài xế đang sẵn sàng. |
| 3 | CAB System | Xác định tài xế phù hợp dựa trên vị trí và tiêu chí vận hành. |
| 4 | CAB System | Gửi yêu cầu chuyến xe cho tài xế. |
| 5 | Driver | Chấp nhận hoặc từ chối yêu cầu. |
| 6 | CAB System | Nếu tài xế từ chối hoặc không phản hồi, tiếp tục tìm tài xế khác. |
| 7 | CAB System | Nếu tìm được tài xế, xác nhận phân công chuyến. |
| 8 | CAB System | Nếu không tìm được tài xế, thông báo cho khách hàng. |

### 6.5 Notification Process

| Step | Trigger | Notification |
|---|---|---|
| 1 | Khách hàng đặt xe | Thông báo yêu cầu đặt xe. |
| 2 | Tài xế được phân công | Thông báo thông tin tài xế cho khách hàng. |
| 3 | Tài xế đến điểm đón | Thông báo cho khách hàng. |
| 4 | Chuyến xe hoàn thành | Thông báo hoàn thành chuyến. |
| 5 | Thanh toán hoàn tất | Thông báo kết quả thanh toán. |
| 6 | Có chuyến mới | Thông báo cho tài xế. |
| 7 | Có thay đổi chuyến xe | Thông báo cho tài xế. |

### 6.6 Post-Trip Rating Process

| Step | Actor | Business Process |
|---|---|---|
| 1 | CAB System | Xác nhận chuyến xe đã hoàn thành. |
| 2 | Customer | Nhận yêu cầu đánh giá chuyến đi. |
| 3 | Customer | Đánh giá chuyến xe. |
| 4 | CAB System | Lưu kết quả đánh giá. |
| 5 | Operations Staff | Sử dụng thông tin đánh giá để theo dõi chất lượng dịch vụ. |

## 7. SYSTEM SCOPE

### 7.1 In Scope

| ID | Scope | Description |
|---|---|---|
| SC01 | User Account Management | Quản lý đăng ký, đăng nhập và thông tin tài khoản của khách hàng và tài xế. |
| SC02 | Vehicle Management | Quản lý thông tin phương tiện của tài xế. |
| SC03 | Booking Management | Cho phép khách hàng tạo yêu cầu đặt xe với điểm đón, điểm trả và loại xe. |
| SC04 | Driver Matching | Tìm kiếm và phân công tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành. |
| SC05 | Trip Management | Quản lý quá trình thực hiện chuyến xe và cập nhật trạng thái chuyến. |
| SC06 | Trip Tracking | Cho phép khách hàng theo dõi trạng thái chuyến và thông tin tài xế. |
| SC07 | Payment Management | Tính cước và hỗ trợ thanh toán tiền mặt hoặc thanh toán điện tử thông qua nhà cung cấp bên ngoài. |
| SC08 | Notification Management | Gửi thông báo liên quan đến đặt xe, tài xế, chuyến xe và thanh toán. |
| SC09 | Rating Management | Cho phép khách hàng đánh giá chuyến xe sau khi hoàn thành. |
| SC10 | Operations Management | Hỗ trợ nhân viên vận hành quản lý khách hàng, tài xế, phương tiện và chuyến xe. |
| SC11 | Transaction Management | Quản lý và tra cứu lịch sử giao dịch. |
| SC12 | Reporting | Cung cấp báo cáo về chuyến xe, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu suất tài xế. |
| SC13 | Security and Access Control | Kiểm soát quyền truy cập và bảo vệ dữ liệu người dùng, phương tiện, vị trí và giao dịch. |

### 7.2 Out of Scope

| ID | Out of Scope | Description |
|---|---|---|
| OS01 | Lưu trữ thông tin thanh toán nhạy cảm | CAB System không trực tiếp lưu trữ thông tin thẻ hoặc tài khoản thanh toán nhạy cảm. |
| OS02 | Xử lý thanh toán trực tiếp | Việc xử lý giao dịch thanh toán điện tử được thực hiện thông qua nhà cung cấp dịch vụ thanh toán bên ngoài. |
| OS03 | Cung cấp dịch vụ thông báo | CAB System sử dụng nhà cung cấp dịch vụ thông báo bên ngoài thay vì tự xây dựng hệ thống thông báo riêng. |

## 8. ACTORS

| ID | Actor | Description | Main Responsibilities |
|---|---|---|---|
| A01 | Customer | Người sử dụng dịch vụ đặt xe của CAB System. | Đăng ký, đăng nhập, đặt xe, theo dõi chuyến, thanh toán và đánh giá chuyến đi. |
| A02 | Driver | Người thực hiện các chuyến xe được hệ thống phân công. | Quản lý thông tin cá nhân và phương tiện, cập nhật trạng thái hoạt động, nhận chuyến và cập nhật trạng thái chuyến xe. |
| A03 | Operations Staff | Nhân viên vận hành và quản lý hoạt động của hệ thống. | Quản lý khách hàng, tài xế, phương tiện, chuyến xe, trạng thái tài xế và lịch sử giao dịch. |
| A04 | Payment Provider | Nhà cung cấp dịch vụ thanh toán điện tử bên ngoài. | Xử lý giao dịch thanh toán điện tử và trả kết quả giao dịch cho CAB System. |
| A05 | Notification Provider | Nhà cung cấp dịch vụ thông báo bên ngoài. | Hỗ trợ gửi các thông báo liên quan đến đặt xe, chuyến xe và thanh toán. |

## 9. FUNCTIONAL REQUIREMENTS

### 9.1 Customer Functional Requirements

| ID | Functional Requirement | Description | Priority |
|---|---|---|---|
| FR-C01 | Register Account | Hệ thống cho phép khách hàng đăng ký tài khoản. | Must Have |
| FR-C02 | Login | Hệ thống cho phép khách hàng đăng nhập vào hệ thống. | Must Have |
| FR-C03 | Manage Profile | Khách hàng có thể xem và cập nhật thông tin cá nhân. | Must Have |
| FR-C04 | Create Booking | Khách hàng nhập điểm đón, điểm trả và chọn loại xe để tạo yêu cầu đặt xe. | Must Have |
| FR-C05 | View Driver Information | Khách hàng có thể xem thông tin tài xế được phân công. | Must Have |
| FR-C06 | Track Trip | Khách hàng có thể theo dõi trạng thái chuyến xe. | Must Have |
| FR-C07 | View Estimated Arrival Time | Khách hàng có thể xem thời gian dự kiến tài xế đến điểm đón. | Should Have |
| FR-C08 | View Trip History | Khách hàng có thể xem lịch sử các chuyến xe đã thực hiện. | Should Have |
| FR-C09 | Make Payment | Khách hàng có thể thanh toán bằng tiền mặt hoặc thanh toán điện tử. | Must Have |
| FR-C10 | Receive Notifications | Khách hàng nhận được thông báo về đặt xe, tài xế, chuyến xe và thanh toán. | Must Have |
| FR-C11 | Rate Trip | Khách hàng có thể đánh giá chuyến xe sau khi hoàn thành. | Should Have |

### 9.2 Driver Functional Requirements

| ID | Functional Requirement | Description | Priority |
|---|---|---|---|
| FR-D01 | Login | Tài xế có thể đăng nhập vào hệ thống. | Must Have |
| FR-D02 | Manage Profile | Tài xế có thể quản lý thông tin cá nhân. | Must Have |
| FR-D03 | Manage Vehicle | Tài xế có thể cung cấp và quản lý thông tin phương tiện. | Must Have |
| FR-D04 | Update Availability | Tài xế có thể cập nhật trạng thái sẵn sàng hoặc không sẵn sàng nhận chuyến. | Must Have |
| FR-D05 | Receive Trip Request | Tài xế nhận yêu cầu chuyến xe từ hệ thống. | Must Have |
| FR-D06 | Accept Trip | Tài xế có thể chấp nhận yêu cầu chuyến xe. | Must Have |
| FR-D07 | Reject Trip | Tài xế có thể từ chối yêu cầu chuyến xe. | Must Have |
| FR-D08 | Update Trip Status | Tài xế cập nhật trạng thái chuyến: đã đến điểm đón, đã đón khách, đang di chuyển và hoàn thành. | Must Have |
| FR-D09 | Update Location | Hệ thống nhận thông tin vị trí của tài xế để hỗ trợ theo dõi và phân công chuyến. | Must Have |
| FR-D10 | Receive Notifications | Tài xế nhận thông báo về chuyến xe mới và các thay đổi liên quan đến chuyến. | Must Have |

### 9.3 Driver Matching and Assignment Functional Requirements

| ID | Functional Requirement | Description | Priority |
|---|---|---|---|
| FR-M01 | Find Available Drivers | Hệ thống tìm kiếm các tài xế đang sẵn sàng nhận chuyến. | Must Have |
| FR-M02 | Match Driver | Hệ thống lựa chọn tài xế phù hợp dựa trên vị trí và tiêu chí vận hành. | Must Have |
| FR-M03 | Assign Trip | Hệ thống gửi yêu cầu chuyến xe đến tài xế phù hợp. | Must Have |
| FR-M04 | Retry Driver Assignment | Nếu tài xế từ chối hoặc không phản hồi, hệ thống tiếp tục tìm tài xế khác. | Must Have |
| FR-M05 | Notify No Driver Available | Nếu không tìm được tài xế phù hợp, hệ thống thông báo cho khách hàng. | Must Have |

### 9.4 Payment Functional Requirements

| ID | Functional Requirement | Description | Priority |
|---|---|---|---|
| FR-P01 | Calculate Fare | Hệ thống tính cước dựa trên loại dịch vụ và thông tin chuyến đi. | Must Have |
| FR-P02 | Cash Payment | Hệ thống hỗ trợ thanh toán bằng tiền mặt. | Must Have |
| FR-P03 | Electronic Payment | Hệ thống hỗ trợ thanh toán điện tử thông qua nhà cung cấp bên ngoài. | Must Have |
| FR-P04 | Process Payment Result | Hệ thống tiếp nhận và cập nhật kết quả thanh toán. | Must Have |
| FR-P05 | Handle Payment Failure | Hệ thống thông báo khi thanh toán thất bại và cho phép thử lại theo chính sách. | Should Have |

### 9.5 Notification Functional Requirements

| ID | Functional Requirement | Description | Priority |
|---|---|---|---|
| FR-N01 | Booking Notification | Gửi thông báo khi yêu cầu đặt xe được tiếp nhận. | Must Have |
| FR-N02 | Driver Assignment Notification | Gửi thông báo khi tài xế được phân công. | Must Have |
| FR-N03 | Driver Arrival Notification | Gửi thông báo khi tài xế đến điểm đón. | Must Have |
| FR-N04 | Trip Completion Notification | Gửi thông báo khi chuyến xe hoàn thành. | Must Have |
| FR-N05 | Payment Notification | Gửi thông báo về kết quả thanh toán. | Must Have |
| FR-N06 | Driver Trip Notification | Gửi thông báo cho tài xế khi có chuyến mới hoặc thay đổi chuyến. | Must Have |

### 9.6 Operations Functional Requirements

| ID | Functional Requirement | Description | Priority |
|---|---|---|---|
| FR-O01 | Manage Customers | Nhân viên vận hành có thể quản lý thông tin khách hàng. | Must Have |
| FR-O02 | Manage Drivers | Nhân viên vận hành có thể quản lý thông tin và trạng thái tài xế. | Must Have |
| FR-O03 | Manage Vehicles | Nhân viên vận hành có thể quản lý thông tin phương tiện. | Must Have |
| FR-O04 | Manage Trips | Nhân viên vận hành có thể theo dõi và quản lý các chuyến xe. | Must Have |
| FR-O05 | Monitor Active Trips | Nhân viên vận hành có thể theo dõi các chuyến xe đang hoạt động. | Must Have |
| FR-O06 | View Transaction History | Nhân viên vận hành có thể tra cứu lịch sử giao dịch. | Must Have |
| FR-O07 | Manage Access Roles | Hệ thống hỗ trợ phân quyền truy cập theo vai trò. | Must Have |

### 9.7 Reporting Functional Requirements

| ID | Functional Requirement | Description | Priority |
|---|---|---|---|
| FR-R01 | Trip Report | Hệ thống cung cấp báo cáo số lượng chuyến xe. | Should Have |
| FR-R02 | Revenue Report | Hệ thống cung cấp báo cáo doanh thu. | Should Have |
| FR-R03 | Completion Rate Report | Hệ thống cung cấp tỷ lệ hoàn thành chuyến xe. | Should Have |
| FR-R04 | Cancellation Rate Report | Hệ thống cung cấp tỷ lệ hủy chuyến. | Should Have |
| FR-R05 | Driver Performance Report | Hệ thống cung cấp thông tin về hiệu suất tài xế. | Should Have |

## 10. BUSINESS RULES

| ID | Business Rule | Description |
|---|---|---|
| BRL01 | Customer must be authenticated | Khách hàng phải đăng nhập trước khi sử dụng các chức năng đặt xe. |
| BRL02 | Booking requires trip information | Một yêu cầu đặt xe phải có điểm đón, điểm trả và loại xe. |
| BRL03 | Driver must be available | Chỉ tài xế đang ở trạng thái sẵn sàng mới được hệ thống xem xét để phân công chuyến. |
| BRL04 | Driver matching is based on operational criteria | Hệ thống lựa chọn tài xế dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành. |
| BRL05 | Reassignment after rejection | Nếu tài xế từ chối hoặc không phản hồi, hệ thống phải tiếp tục tìm tài xế khác mà khách hàng không cần đặt lại chuyến. |
| BRL06 | No driver available | Nếu không tìm được tài xế phù hợp, hệ thống phải thông báo cho khách hàng. |
| BRL07 | Trip status follows the trip lifecycle | Trạng thái chuyến xe được cập nhật theo quá trình thực hiện: đã đến điểm đón → đã đón khách → đang di chuyển → hoàn thành. |
| BRL08 | Fare is calculated after trip completion | Hệ thống tính cước dựa trên loại dịch vụ và thông tin chuyến đi khi chuyến xe được hoàn thành. |
| BRL09 | Multiple payment methods | Khách hàng có thể thanh toán bằng tiền mặt hoặc thanh toán điện tử. |
| BRL10 | External payment processing | Thanh toán điện tử được xử lý thông qua nhà cung cấp dịch vụ thanh toán bên ngoài. |
| BRL11 | Sensitive payment data is not stored | CAB System không trực tiếp lưu trữ thông tin thẻ hoặc tài khoản thanh toán nhạy cảm. |
| BRL12 | Payment failure handling | Khi thanh toán thất bại, hệ thống phải thông báo cho khách hàng và cho phép thực hiện lại theo chính sách. |
| BRL13 | Rating after completed trip | Khách hàng chỉ thực hiện đánh giá sau khi chuyến xe đã hoàn thành. |
| BRL14 | Role-based access | Quyền truy cập vào các chức năng quản lý phải được kiểm soát dựa trên vai trò của người dùng. |
| BRL15 | Driver location is used for matching and tracking | Thông tin vị trí tài xế được sử dụng để hỗ trợ phân công và theo dõi chuyến xe. |
| BRL16 | Notifications are triggered by business events | Hệ thống gửi thông báo khi xảy ra các sự kiện như phân công tài xế, tài xế đến điểm đón, hoàn thành chuyến và kết quả thanh toán. |

## 11. NON-FUNCTIONAL REQUIREMENTS

| ID | Category | Non-Functional Requirement | Description | Priority |
|---|---|---|---|---|
| NFR01 | Performance | System Performance | Hệ thống phải hoạt động ổn định khi có nhu cầu đặt xe cao. | Must Have |
| NFR02 | Scalability | System Scalability | Hệ thống phải có khả năng mở rộng các thành phần độc lập khi số lượng người dùng và chuyến xe tăng. | Should Have |
| NFR03 | Reliability | Fault Isolation | Sự cố của một thành phần không được làm ảnh hưởng đến toàn bộ hệ thống. | Must Have |
| NFR04 | Availability | System Availability | Hệ thống cần duy trì khả năng phục vụ khách hàng và tài xế trong quá trình sử dụng dịch vụ. | Must Have |
| NFR05 | Security | Authentication | Hệ thống phải xác thực người dùng trước khi cho phép truy cập các chức năng yêu cầu đăng nhập. | Must Have |
| NFR06 | Security | Access Control | Hệ thống phải kiểm soát quyền truy cập dựa trên vai trò của người dùng. | Must Have |
| NFR07 | Security | Data Protection | Hệ thống phải bảo vệ dữ liệu cá nhân, thông tin phương tiện, vị trí và giao dịch của người dùng. | Must Have |
| NFR08 | Security | Sensitive Payment Data | Hệ thống không được trực tiếp lưu trữ thông tin thẻ hoặc tài khoản thanh toán nhạy cảm. | Must Have |
| NFR09 | Auditability | Audit Log | Hệ thống phải ghi nhận các hoạt động quan trọng để phục vụ kiểm tra và truy vết khi cần thiết. | Should Have |
| NFR10 | Maintainability | Independent Components | Các thành phần của hệ thống nên có khả năng triển khai và mở rộng độc lập. | Should Have |
| NFR11 | Extensibility | New Services | Hệ thống phải có khả năng mở rộng để hỗ trợ các dịch vụ mới trong tương lai. | Should Have |
| NFR12 | Extensibility | New Payment Providers | Hệ thống phải có khả năng tích hợp thêm các nhà cung cấp dịch vụ thanh toán mới. | Should Have |
| NFR13 | Extensibility | New Notification Providers | Hệ thống phải có khả năng tích hợp thêm các nhà cung cấp dịch vụ thông báo mới. | Should Have |

## 12. EXCEPTION CASES

| ID | Exception Case | Condition | System Behavior |
|---|---|---|---|
| EC01 | No Driver Available | Không tìm được tài xế phù hợp cho yêu cầu đặt xe. | Hệ thống thông báo cho khách hàng rằng hiện không có tài xế phù hợp. |
| EC02 | Driver Rejects Trip | Tài xế từ chối yêu cầu chuyến xe. | Hệ thống tiếp tục tìm kiếm và phân công tài xế khác. Khách hàng không cần đặt lại chuyến. |
| EC03 | Driver Does Not Respond | Tài xế không phản hồi yêu cầu chuyến xe. | Hệ thống tiếp tục tìm kiếm tài xế khác. |
| EC04 | Payment Failure | Giao dịch thanh toán điện tử không thành công. | Hệ thống thông báo lỗi thanh toán và cho phép khách hàng thực hiện lại theo chính sách. |
| EC05 | Invalid Booking Information | Thông tin đặt xe không đầy đủ hoặc không hợp lệ. | Hệ thống yêu cầu khách hàng kiểm tra và bổ sung thông tin trước khi gửi yêu cầu. |
| EC06 | Driver Becomes Unavailable | Tài xế không còn ở trạng thái sẵn sàng trong quá trình phân công. | Hệ thống loại tài xế khỏi danh sách phân công và tìm tài xế phù hợp khác. |
| EC07 | Trip Cannot Be Completed | Chuyến xe gặp vấn đề khiến tài xế không thể hoàn thành chuyến. | Hệ thống cập nhật trạng thái phù hợp và chuyển thông tin cho nhân viên vận hành xử lý. |
| EC08 | Notification Failure | Việc gửi thông báo đến khách hàng hoặc tài xế thất bại. | Hệ thống ghi nhận lỗi và xử lý thông qua cơ chế thông báo phù hợp của hệ thống. |
| EC09 | Unauthorized Access | Người dùng cố truy cập chức năng không thuộc quyền của mình. | Hệ thống từ chối truy cập và chỉ cho phép sử dụng các chức năng được phân quyền. |
| EC10 | System Component Failure | Một thành phần của hệ thống gặp sự cố. | Hệ thống cô lập lỗi để hạn chế ảnh hưởng đến các thành phần khác. |

## 13. OPEN QUESTIONS / TBD

| ID | Open Question / TBD | Description | Status |
|---|---|---|---|
| TBD01 | Fare Calculation | Cần xác định công thức và các yếu tố cụ thể dùng để tính cước chuyến xe. | TBD |
| TBD02 | Driver Priority | Cần xác định rõ cách ưu tiên tài xế khi có nhiều tài xế phù hợp. | TBD |
| TBD03 | Driver Response Time | Cần xác định thời gian tối đa tài xế được phép phản hồi yêu cầu chuyến xe. | TBD |
| TBD04 | Cancellation Policy | Cần xác định chính sách và điều kiện hủy chuyến đối với khách hàng và tài xế. | TBD |
| TBD05 | Network Failure Handling | Cần xác định cách hệ thống xử lý khi khách hàng hoặc tài xế mất kết nối mạng trong quá trình sử dụng. | TBD |
| TBD06 | Data Retention | Cần xác định thời gian lưu trữ dữ liệu khách hàng, tài xế, chuyến xe và giao dịch. | TBD |
| TBD07 | Payment Retry Policy | Cần xác định số lần và điều kiện cho phép khách hàng thử lại khi thanh toán thất bại. | TBD |
| TBD08 | Notification Failure Handling | Cần xác định cơ chế xử lý khi thông báo không thể gửi đến khách hàng hoặc tài xế. | TBD |

## 14. ENTITY MODEL

### 14.1 Main Entities

| Entity | Description |
|---|---|
| Customer | Lưu thông tin khách hàng sử dụng dịch vụ đặt xe. |
| Driver | Lưu thông tin tài xế thực hiện chuyến xe. |
| Vehicle | Lưu thông tin phương tiện của tài xế. |
| Booking | Lưu thông tin yêu cầu đặt xe của khách hàng. |
| Trip | Lưu thông tin và trạng thái chuyến xe được thực hiện. |
| Payment | Lưu thông tin và trạng thái thanh toán của chuyến xe. |
| Notification | Lưu thông tin các thông báo được gửi đến khách hàng hoặc tài xế. |
| Rating | Lưu thông tin đánh giá của khách hàng sau chuyến xe. |
| Transaction | Lưu thông tin giao dịch liên quan đến thanh toán. |

### 14.2 Entity Attributes

| Entity | Main Attributes |
|---|---|
| Customer | CustomerID, Name, Phone, Email, Address, AccountStatus |
| Driver | DriverID, Name, Phone, Email, LicenseNumber, AvailabilityStatus, Location |
| Vehicle | VehicleID, DriverID, VehicleType, LicensePlate, VehicleStatus |
| Booking | BookingID, CustomerID, PickupLocation, DropoffLocation, VehicleType, BookingStatus, CreatedAt |
| Trip | TripID, BookingID, DriverID, PickupLocation, DropoffLocation, TripStatus, StartTime, EndTime, Fare |
| Payment | PaymentID, TripID, PaymentMethod, Amount, PaymentStatus, PaymentTime |
| Notification | NotificationID, UserID, NotificationType, Message, NotificationStatus, CreatedAt |
| Rating | RatingID, TripID, CustomerID, DriverID, Score, Comment, CreatedAt |
| Transaction | TransactionID, PaymentID, Amount, TransactionStatus, TransactionTime |

### 14.3 Entity Relationships

| Relationship | Description |
|---|---|
| Customer - Booking | Một Customer có thể tạo nhiều Booking. |
| Booking - Trip | Một Booking được xử lý thành một Trip khi chuyến xe được xác nhận. |
| Driver - Vehicle | Một Driver có thể được gắn với một hoặc nhiều Vehicle theo thông tin quản lý phương tiện. |
| Driver - Trip | Một Driver có thể thực hiện nhiều Trip. |
| Trip - Payment | Một Trip có thông tin thanh toán tương ứng. |
| Trip - Rating | Một Trip có thể có đánh giá từ Customer sau khi hoàn thành. |
| Customer - Rating | Customer tạo Rating cho Trip đã hoàn thành. |
| User - Notification | Customer hoặc Driver có thể nhận nhiều Notification. |
| Payment - Transaction | Payment có thể liên quan đến Transaction được xử lý bởi nhà cung cấp thanh toán. |

### 14.4 Entity Relationship Overview

```text
Customer
   │
   │ creates
   ▼
Booking
   │
   │ becomes
   ▼
Trip ◄──────── Driver ────────► Vehicle
 │
 ├──────────► Payment ─────────► Transaction
 │
 └──────────► Rating
                  ▲
                  │
               Customer

Customer / Driver
        │
        ▼
   Notification

## 15. USE CASES

### 15.1 Danh sách Use Case

| Mã | Use Case | Actor chính | Mô tả |
|---|---|---|---|
| UC01 | Đăng ký tài khoản | Khách hàng | Khách hàng tạo tài khoản để sử dụng hệ thống. |
| UC02 | Đăng nhập | Khách hàng, Tài xế | Người dùng đăng nhập vào hệ thống để sử dụng các chức năng được phân quyền. |
| UC03 | Quản lý thông tin cá nhân | Khách hàng, Tài xế | Người dùng xem và cập nhật thông tin cá nhân. |
| UC04 | Quản lý phương tiện | Tài xế, Nhân viên vận hành | Quản lý thông tin phương tiện của tài xế. |
| UC05 | Đặt xe | Khách hàng | Khách hàng nhập điểm đón, điểm trả, chọn loại xe và gửi yêu cầu đặt xe. |
| UC06 | Tìm kiếm tài xế | Hệ thống | Hệ thống tìm tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành. |
| UC07 | Nhận yêu cầu chuyến xe | Tài xế | Tài xế nhận thông tin yêu cầu chuyến xe từ hệ thống. |
| UC08 | Chấp nhận/Từ chối chuyến | Tài xế | Tài xế quyết định chấp nhận hoặc từ chối yêu cầu chuyến xe. |
| UC09 | Phân công tài xế | Hệ thống | Hệ thống phân công tài xế phù hợp cho yêu cầu đặt xe. |
| UC10 | Theo dõi chuyến xe | Khách hàng | Khách hàng theo dõi trạng thái chuyến và thông tin tài xế. |
| UC11 | Cập nhật trạng thái chuyến | Tài xế | Tài xế cập nhật trạng thái chuyến trong quá trình thực hiện. |
| UC12 | Tính cước | Hệ thống | Hệ thống tính cước dựa trên loại dịch vụ và thông tin chuyến đi. |
| UC13 | Thanh toán | Khách hàng | Khách hàng thanh toán bằng tiền mặt hoặc thanh toán điện tử. |
| UC14 | Gửi thông báo | Hệ thống | Hệ thống gửi thông báo đến khách hàng hoặc tài xế khi có sự kiện liên quan. |
| UC15 | Đánh giá chuyến xe | Khách hàng | Khách hàng đánh giá chuyến xe sau khi hoàn thành. |
| UC16 | Quản lý khách hàng | Nhân viên vận hành | Nhân viên vận hành quản lý thông tin khách hàng. |
| UC17 | Quản lý tài xế | Nhân viên vận hành | Nhân viên vận hành quản lý thông tin và trạng thái tài xế. |
| UC18 | Quản lý chuyến xe | Nhân viên vận hành | Nhân viên vận hành theo dõi và quản lý các chuyến xe. |
| UC19 | Xem lịch sử giao dịch | Nhân viên vận hành | Nhân viên vận hành tra cứu lịch sử giao dịch. |
| UC20 | Xem báo cáo | Nhân viên vận hành | Nhân viên vận hành xem các báo cáo về chuyến xe, doanh thu và hiệu suất tài xế. |

### 15.2 Use Case chính của hệ thống

| Use Case | Actor | Luồng chính |
|---|---|---|
| Đặt xe | Khách hàng | Đăng nhập → Nhập điểm đón/trả → Chọn loại xe → Gửi yêu cầu → Hệ thống tìm tài xế → Xác nhận tài xế. |
| Phân công tài xế | Hệ thống, Tài xế | Tìm tài xế phù hợp → Gửi yêu cầu → Tài xế chấp nhận → Phân công chuyến. |
| Thực hiện chuyến xe | Tài xế | Đến điểm đón → Đón khách → Di chuyển → Hoàn thành chuyến. |
| Thanh toán | Khách hàng, Hệ thống, Nhà cung cấp thanh toán | Tính cước → Chọn phương thức → Thanh toán → Nhận kết quả → Cập nhật trạng thái. |
| Đánh giá chuyến xe | Khách hàng | Chuyến xe hoàn thành → Khách hàng đánh giá → Hệ thống lưu đánh giá. |
| Quản lý vận hành | Nhân viên vận hành | Quản lý khách hàng → Quản lý tài xế → Quản lý phương tiện → Theo dõi chuyến → Xem giao dịch và báo cáo. |

### 15.3 Luồng Use Case đặt xe

```text
Khách hàng
    │
    ▼
Đăng nhập
    │
    ▼
Nhập điểm đón + điểm trả
    │
    ▼
Chọn loại xe
    │
    ▼
Gửi yêu cầu đặt xe
    │
    ▼
Hệ thống tìm tài xế
    │
    ▼
Có tài xế phù hợp?
   / \
  Có  Không
  │     │
  ▼     ▼
Gửi yêu  Thông báo
cầu      không có
  │      tài xế
  ▼
Tài xế chấp nhận?
   / \
  Có  Không
  │     │
  ▼     ▼
Phân công   Tìm tài xế khác
tài xế
  │
  ▼
Thông báo khách hàng
  │
  ▼
Theo dõi chuyến xe
| ID   | Chức năng                  | Tiêu chí nghiệm thu                                                                                                                      |
| ---- | -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| AC01 | Đăng ký tài khoản          | Khách hàng có thể đăng ký tài khoản với thông tin hợp lệ và hệ thống tạo tài khoản thành công.                                           |
| AC02 | Đăng nhập                  | Khách hàng và tài xế có thể đăng nhập bằng thông tin tài khoản hợp lệ. Nếu thông tin không hợp lệ, hệ thống phải thông báo lỗi.          |
| AC03 | Quản lý thông tin cá nhân  | Khách hàng và tài xế có thể xem và cập nhật thông tin cá nhân của mình.                                                                  |
| AC04 | Quản lý phương tiện        | Tài xế hoặc nhân viên vận hành có thể thêm, cập nhật và quản lý thông tin phương tiện.                                                   |
| AC05 | Đặt xe                     | Khách hàng có thể nhập điểm đón, điểm trả và loại xe để tạo yêu cầu đặt xe thành công.                                                   |
| AC06 | Phân công tài xế           | Hệ thống tìm kiếm và phân công tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành.                             |
| AC07 | Từ chối chuyến             | Khi tài xế từ chối hoặc không phản hồi yêu cầu, hệ thống tiếp tục tìm tài xế khác mà không yêu cầu khách hàng đặt lại chuyến.            |
| AC08 | Không có tài xế            | Nếu không tìm được tài xế phù hợp, hệ thống phải thông báo cho khách hàng.                                                               |
| AC09 | Theo dõi chuyến xe         | Khách hàng có thể xem trạng thái chuyến xe và thông tin tài xế sau khi chuyến được phân công.                                            |
| AC10 | Cập nhật trạng thái chuyến | Tài xế có thể cập nhật trạng thái theo đúng quy trình: **đã đến điểm đón → đã đón khách → đang di chuyển → hoàn thành**.                 |
| AC11 | Tính cước                  | Khi chuyến xe hoàn thành, hệ thống tính và hiển thị cước phí của chuyến xe.                                                              |
| AC12 | Thanh toán                 | Khách hàng có thể thanh toán bằng tiền mặt hoặc phương thức thanh toán điện tử được hỗ trợ.                                              |
| AC13 | Thanh toán thất bại        | Khi thanh toán điện tử thất bại, hệ thống phải thông báo cho khách hàng và cho phép thực hiện lại theo chính sách của hệ thống.          |
| AC14 | Bảo mật thanh toán         | Hệ thống CAB không lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán.                                                   |
| AC15 | Thông báo                  | Hệ thống gửi thông báo khi có các sự kiện quan trọng như phân công tài xế, tài xế đến điểm đón, hoàn thành chuyến và kết quả thanh toán. |
| AC16 | Đánh giá chuyến xe         | Sau khi chuyến xe hoàn thành, khách hàng có thể đánh giá và nhận xét về chuyến đi.                                                       |
| AC17 | Quản lý khách hàng         | Nhân viên vận hành có thể xem và quản lý thông tin khách hàng theo quyền được cấp.                                                       |
| AC18 | Quản lý tài xế             | Nhân viên vận hành có thể quản lý thông tin, trạng thái hoạt động và phương tiện của tài xế.                                             |
| AC19 | Quản lý chuyến xe          | Nhân viên vận hành có thể theo dõi và quản lý các chuyến xe, bao gồm chuyến đang hoạt động và chuyến đã hoàn thành.                      |
| AC20 | Quản lý giao dịch          | Nhân viên vận hành có thể xem lịch sử giao dịch và trạng thái thanh toán.                                                                |
| AC21 | Báo cáo                    | Hệ thống cung cấp các báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu suất tài xế.                            |
| AC22 | Phân quyền                 | Người dùng chỉ được truy cập các chức năng phù hợp với vai trò của mình.                                                                 |
| AC23 | Bảo vệ dữ liệu             | Thông tin cá nhân, thông tin phương tiện, vị trí và thông tin giao dịch phải được bảo vệ khỏi truy cập trái phép.                        |
| AC24 | Ổn định hệ thống           | Hệ thống vẫn phải hoạt động ổn định khi nhu cầu đặt xe tăng cao và khi một thành phần gặp sự cố.                                         |
