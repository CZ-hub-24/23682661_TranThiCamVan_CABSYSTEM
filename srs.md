## 1. Stakeholders

| Stakeholder | Vai trò / Mối quan tâm đối với hệ thống |
|---|---|
| **Khách hàng (Customer)** | Sử dụng dịch vụ đặt xe: đăng ký/đăng nhập, đặt xe, theo dõi chuyến đi, thanh toán, xem lịch sử và đánh giá tài xế. |
| **Tài xế (Driver)** | Nhận hoặc từ chối chuyến, cập nhật trạng thái hoạt động và trạng thái chuyến đi, cung cấp thông tin vị trí và quản lý hồ sơ/phương tiện. |
| **Nhân viên vận hành (Operation Staff)** | Quản lý khách hàng, tài xế, phương tiện và chuyến đi; theo dõi chuyến đang diễn ra, hỗ trợ xử lý lỗi và tra cứu lịch sử giao dịch. |
| **Ban lãnh đạo / Ban giám đốc (Management)** | Đưa ra yêu cầu và định hướng phát triển hệ thống; theo dõi báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. |
| **Nhà cung cấp thanh toán (Payment Provider)** | Hệ thống bên ngoài được tích hợp với CAB System để xử lý các giao dịch thanh toán điện tử. |
| **Nhà cung cấp dịch vụ thông báo (Notification Provider)** | Hỗ trợ gửi thông báo cho khách hàng và tài xế; có thể mở rộng thêm các kênh hoặc nhà cung cấp thông báo trong tương lai. |
| **Business Analyst (BA)** | Xác định phạm vi, tác nhân, quy trình nghiệp vụ, yêu cầu chức năng/phi chức năng, quy tắc nghiệp vụ, trường hợp ngoại lệ và làm rõ các yêu cầu chưa xác định. |
| **Nhóm phát triển (Development Team)** | Xây dựng và triển khai CAB System dựa trên các yêu cầu đã được BA làm rõ với các bên liên quan. |

## 2. Stakeholder Matrix

Ma trận dưới đây đánh giá mức độ quan tâm (Interest) và mức độ ảnh hưởng (Power) của từng stakeholder đối với dự án, làm cơ sở xác định cách thức trao đổi và mức độ ưu tiên khi thu thập/xác nhận yêu cầu.

### Stakeholder Matrix - CAB System

| | **Low Interest** | **High Interest** |
|---|---|---|
| **High Power** | **Keep Satisfied** <br><br> • Nhà cung cấp thanh toán | **Manage Closely** <br><br> • Ban lãnh đạo <br> • Nhân viên vận hành |
| **Low Power** | **Monitor** <br><br> • Nhà cung cấp thông báo | **Keep Informed** <br><br> • Khách hàng <br> • Tài xế |

### Cách tiếp cận Stakeholder

| Stakeholder | Quadrant | Cách tiếp cận |
|---|---|---|
| **Ban lãnh đạo** | Manage Closely | Trao đổi thường xuyên, xác nhận mục tiêu kinh doanh và các chỉ số báo cáo. |
| **Nhân viên vận hành** | Manage Closely | Thu thập chi tiết nghiệp vụ vận hành hằng ngày, xác nhận quy trình xử lý ngoại lệ. |
| **Khách hàng** | Keep Informed | Thu thập kỳ vọng trải nghiệm sử dụng, thông báo tiến độ khi cần. |
| **Tài xế** | Keep Informed | Thu thập kỳ vọng về quy trình nhận chuyến và cập nhật trạng thái. |
| **Nhà cung cấp thanh toán** | Keep Satisfied | Xác nhận chuẩn tích hợp và yêu cầu bảo mật giao dịch. |
| **Nhà cung cấp thông báo** | Monitor | Xác nhận các kênh thông báo hỗ trợ và khả năng mở rộng. |

## 3. Business Goals

Các Business Goals của dự án CAB System được xác định dựa trên những vấn đề của hệ thống hiện tại và kỳ vọng phát triển lâu dài của doanh nghiệp.

| ID | Business Goal | Mô tả |
|---|---|---|
| **BG-01** | Tự động hóa quy trình đặt và phân công xe | Giảm việc phân công tài xế thủ công bằng cách tự động tìm và ưu tiên tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành. |
| **BG-02** | Nâng cao trải nghiệm khách hàng | Cho phép khách hàng đặt xe, theo dõi trạng thái chuyến đi, biết tài xế đã nhận chuyến, thời gian dự kiến tài xế đến, xem lịch sử chuyến và đánh giá tài xế. |
| **BG-03** | Quản lý tập trung quy trình chuyến đi và thanh toán | Quản lý xuyên suốt quá trình từ tạo yêu cầu đặt xe, thực hiện chuyến, tính cước đến thanh toán và lưu trữ thông tin giao dịch. |
| **BG-04** | Nâng cao hiệu quả vận hành | Cung cấp công cụ cho nhân viên vận hành quản lý khách hàng, tài xế, phương tiện và chuyến đi; theo dõi hoạt động và hỗ trợ xử lý các trường hợp phát sinh. |
| **BG-05** | Hỗ trợ quản lý và ra quyết định | Cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ chuyến hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. |
| **BG-06** | Đảm bảo khả năng phục vụ khi nhu cầu tăng cao | Xây dựng hệ thống hoạt động ổn định khi tải tăng và cho phép các thành phần của hệ thống mở rộng độc lập. |
| **BG-07** | Xây dựng nền tảng có khả năng phát triển lâu dài | Cho phép bổ sung loại dịch vụ, phương thức thanh toán, nhà cung cấp thông báo và thay đổi một số thành phần kỹ thuật mà không phải xây dựng lại toàn bộ ứng dụng. |

## 4. MVP Modules

MVP tập trung vào các module cần thiết để CAB System có thể vận hành được quy trình đặt xe cốt lõi trong giai đoạn đầu.

| ID | Module | Chức năng chính |
|---|---|---|
| **M01** | Authentication & User Management | Đăng ký, đăng nhập, cập nhật thông tin cá nhân; xác thực người dùng và quản lý quyền truy cập. |
| **M02** | Customer Booking | Cho phép khách hàng nhập điểm đón, điểm đến, chọn loại xe và gửi yêu cầu đặt xe. |
| **M03** | Driver & Vehicle Management | Quản lý hồ sơ tài xế, thông tin phương tiện, vị trí và trạng thái sẵn sàng nhận chuyến. |
| **M04** | Driver Matching & Assignment | Tìm và ưu tiên tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và tiêu chí vận hành; tiếp tục tìm tài xế khác nếu tài xế từ chối hoặc không phản hồi. |
| **M05** | Trip Management & Tracking | Quản lý vòng đời chuyến đi và các trạng thái như tài xế nhận chuyến, đến điểm đón, đón khách, đang di chuyển và hoàn thành chuyến. |
| **M06** | Fare & Payment | Tính số tiền phải trả sau chuyến đi; hỗ trợ thanh toán tiền mặt và thanh toán điện tử thông qua nhà cung cấp bên ngoài. |
| **M07** | Notification | Gửi thông báo về các sự kiện quan trọng như tiếp nhận yêu cầu, tài xế nhận chuyến, tài xế đến điểm đón, hoàn thành chuyến và kết quả thanh toán. |
| **M08** | Operations & Administration | Cho phép nhân viên vận hành quản lý khách hàng, tài xế, phương tiện và chuyến đi; theo dõi chuyến đang diễn ra và hỗ trợ xử lý các trường hợp lỗi. |

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

## 6. Business Process Modeling

### 6.1. Business Process Overview

Quy trình nghiệp vụ cốt lõi của hệ thống CAB mô tả vòng đời của một chuyến xe, gồm các bước:

**Tạo yêu cầu đặt xe → Tìm kiếm và phân công tài xế → Xác nhận chuyến → Thực hiện chuyến → Tính cước → Thanh toán → Hoàn tất chuyến → Đánh giá**

Đây là quy trình nghiệp vụ chính xuyên suốt các chức năng của hệ thống. Các chức năng như quản lý tài khoản, quản lý vận hành, thông báo và báo cáo đóng vai trò hỗ trợ cho quy trình này.

---

### 6.2. Business Process Diagram

```mermaid
flowchart TD
    A([Start]) --> B[Khách hàng đăng nhập]
    B --> C[Nhập điểm đón, điểm đến<br/>và chọn loại xe]
    C --> D[Gửi yêu cầu đặt xe]
    D --> E[Hệ thống tiếp nhận yêu cầu]
    E --> F[Tìm tài xế phù hợp]

    F --> G{Có tài xế phù hợp?}

    G -- Không --> H[Thông báo không tìm được tài xế]
    H --> Z([End])

    G -- Có --> I[Gửi yêu cầu đến tài xế]
    I --> J{Tài xế chấp nhận?}

    J -- Không phản hồi / Từ chối --> K[Tìm tài xế phù hợp khác]
    K --> G

    J -- Có --> L[Phân công tài xế cho chuyến]
    L --> M[Thông báo khách hàng:<br/>Tài xế đã nhận chuyến]
    M --> N[Hiển thị thông tin tài xế<br/>và thời gian dự kiến đến]

    N --> O[Tài xế di chuyển đến điểm đón]
    O --> P[Tài xế cập nhật:<br/>Đã đến điểm đón]
    P --> Q[Thông báo khách hàng:<br/>Tài xế đã đến]

    Q --> R[Tài xế đón khách]
    R --> S[Tài xế cập nhật:<br/>Đã đón khách]
    S --> T[Tài xế thực hiện chuyến đi]
    T --> U[Tài xế cập nhật:<br/>Hoàn thành chuyến]

    U --> V[Hệ thống tính cước chuyến đi]
    V --> W{Phương thức thanh toán?}

    W -- Tiền mặt --> X[Khách hàng thanh toán<br/>bằng tiền mặt]
    W -- Điện tử --> Y[Thanh toán qua<br/>nhà cung cấp bên ngoài]

    Y --> AA{Thanh toán thành công?}

    AA -- Không --> AB[Thông báo thanh toán thất bại]
    AB --> AC[Xử lý lại theo chính sách doanh nghiệp]
    AC --> Y

    AA -- Có --> AD[Thông báo thanh toán thành công]

    X --> AE[Hoàn tất chuyến]
    AD --> AE

    AE --> AF[Khách hàng xem lịch sử chuyến<br/>và số tiền phải trả]
    AF --> AG[Khách hàng đánh giá tài xế]
    AG --> Z([End])
```

---

### 6.3. Các bên tham gia trong Business Process

| Actor / Stakeholder | Vai trò trong quy trình |
|---|---|
| **Khách hàng** | Tạo yêu cầu đặt xe, theo dõi chuyến đi, thực hiện thanh toán, xem lịch sử chuyến và đánh giá tài xế. |
| **Hệ thống CAB** | Tiếp nhận yêu cầu, tìm và phân công tài xế, quản lý trạng thái chuyến, tính cước, hỗ trợ xử lý thanh toán và gửi thông báo. |
| **Tài xế** | Nhận hoặc từ chối chuyến, di chuyển đến điểm đón, đón khách, cập nhật trạng thái và hoàn thành chuyến đi. |
| **Nhà cung cấp thanh toán** | Xử lý giao dịch thanh toán điện tử và trả kết quả giao dịch cho hệ thống CAB. |
| **Nhân viên vận hành** | Theo dõi các chuyến đang diễn ra, kiểm tra trạng thái tài xế và hỗ trợ xử lý các trường hợp chuyến bị lỗi. |

---

### 6.4. Business Process ↔ Business Requirement

| Business Requirement | Bước quy trình liên quan |
|---|---|
| **BR01 – Xây dựng nền tảng đặt xe trực tuyến** | Xuyên suốt quy trình từ tạo yêu cầu đặt xe đến hoàn tất chuyến. |
| **BR02 – Hỗ trợ số lượng lớn người dùng** | Xuyên suốt quy trình khi hệ thống phục vụ đồng thời nhiều khách hàng và tài xế. |
| **BR03 – Tự động hóa việc tìm và phân công tài xế** | Tìm tài xế → Gửi yêu cầu đến tài xế → Kiểm tra phản hồi → Tìm tài xế khác khi cần → Phân công tài xế. |
| **BR04 – Quản lý toàn bộ quy trình chuyến xe** | Tạo yêu cầu → Phân công tài xế → Thực hiện chuyến → Hoàn thành chuyến → Đánh giá. |
| **BR05 – Cung cấp khả năng theo dõi chuyến đi** | Cập nhật trạng thái chuyến → Thông báo trạng thái cho khách hàng → Xem lịch sử chuyến. |
| **BR06 – Hỗ trợ tính cước và thanh toán** | Hoàn thành chuyến → Tính cước → Chọn phương thức thanh toán → Xử lý thanh toán → Xác nhận kết quả. |
| **BR07 – Quản lý thông báo** | Gửi thông báo tại các sự kiện quan trọng trong quá trình đặt và thực hiện chuyến. |
| **BR08 – Hỗ trợ quản lý và vận hành tập trung** | Theo dõi chuyến đang diễn ra → Kiểm tra trạng thái tài xế → Hỗ trợ xử lý chuyến bị lỗi. |
| **BR09 – Cung cấp báo cáo hoạt động** | Sử dụng dữ liệu chuyến đi, thanh toán và hoạt động tài xế để phục vụ báo cáo. |
| **BR10 – Đảm bảo tính ổn định và khả năng mở rộng** | Áp dụng xuyên suốt quy trình để hệ thống tiếp tục hoạt động ổn định khi nhu cầu tăng cao hoặc một thành phần gặp lỗi. |
| **BR11 – Đảm bảo an toàn và bảo mật dữ liệu** | Xác thực người dùng, kiểm soát truy cập và bảo vệ dữ liệu cá nhân, vị trí, phương tiện và giao dịch trong quá trình vận hành. |
| **BR12 – Hỗ trợ phát triển và mở rộng trong tương lai** | Hỗ trợ bổ sung loại dịch vụ, phương thức thanh toán, nhà cung cấp thông báo và thay đổi thành phần kỹ thuật trong tương lai. |


## 7. Functional Requirements

| ID | Module | Functional Requirement | Mô tả |
|---|---|---|---|
| **FR01** | Quản lý tài khoản & xác thực | Đăng ký tài khoản khách hàng | Hệ thống cho phép khách hàng đăng ký tài khoản. |
| **FR02** | Quản lý tài khoản & xác thực | Đăng ký/tạo tài khoản tài xế | Hệ thống cho phép tài xế tự đăng ký hoặc được nhân viên vận hành tạo tài khoản. |
| **FR03** | Quản lý tài khoản & xác thực | Đăng nhập | Hệ thống cho phép khách hàng và tài xế đăng nhập trước khi sử dụng các chức năng yêu cầu tài khoản. |
| **FR04** | Quản lý tài khoản & xác thực | Cập nhật thông tin cá nhân | Hệ thống cho phép khách hàng cập nhật thông tin cá nhân. |
| **FR05** | Quản lý tài xế & phương tiện | Cập nhật hồ sơ, phương tiện và trạng thái hoạt động | Hệ thống cho phép tài xế cập nhật hồ sơ, thông tin phương tiện và trạng thái sẵn sàng nhận chuyến. |
| **FR06** | Đặt xe | Nhập thông tin chuyến | Hệ thống cho phép khách hàng nhập điểm đón, điểm đến và lựa chọn loại xe. |
| **FR07** | Đặt xe | Tạo yêu cầu đặt xe | Hệ thống cho phép khách hàng gửi yêu cầu đặt xe. |
| **FR08** | Đặt xe | Tiếp nhận yêu cầu | Hệ thống tiếp nhận và ghi nhận yêu cầu đặt xe của khách hàng. |
| **FR09** | Tìm kiếm & phân công tài xế | Xác định tài xế phù hợp | Hệ thống xác định tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành. |
| **FR10** | Tìm kiếm & phân công tài xế | Ưu tiên tài xế | Hệ thống ưu tiên tài xế phù hợp và gần khách hàng. |
| **FR11** | Tìm kiếm & phân công tài xế | Gửi yêu cầu đến tài xế | Hệ thống gửi yêu cầu chuyến đến tài xế phù hợp. |
| **FR12** | Tìm kiếm & phân công tài xế | Xử lý phản hồi tài xế | Hệ thống ghi nhận việc tài xế chấp nhận hoặc từ chối chuyến. |
| **FR13** | Tìm kiếm & phân công tài xế | Tìm tài xế thay thế | Khi tài xế không phản hồi hoặc từ chối, hệ thống tiếp tục tìm tài xế khác mà không yêu cầu khách hàng tạo lại yêu cầu. |
| **FR14** | Tìm kiếm & phân công tài xế | Thông báo không tìm được tài xế | Khi không tìm được tài xế phù hợp, hệ thống thông báo rõ ràng cho khách hàng. |
| **FR15** | Quản lý chuyến đi | Cập nhật trạng thái chuyến | Hệ thống cho phép tài xế cập nhật trạng thái: đã đến điểm đón, đã đón khách, đang di chuyển và hoàn thành chuyến. |
| **FR16** | Quản lý chuyến đi | Cập nhật vị trí tài xế | Hệ thống lưu vị trí tài xế để hỗ trợ tìm tài xế gần khách hàng và dự kiến thời gian đến. |
| **FR17** | Quản lý chuyến đi | Theo dõi chuyến | Hệ thống cho phép khách hàng theo dõi trạng thái hiện tại của chuyến đi. |
| **FR18** | Quản lý chuyến đi | Hiển thị thông tin tài xế | Hệ thống hiển thị thông tin tài xế đã nhận chuyến và thời gian dự kiến tài xế đến. |
| **FR19** | Tính cước & thanh toán | Tính tiền chuyến đi | Hệ thống xác định số tiền khách hàng phải trả dựa trên loại dịch vụ và thông tin chuyến đi. |
| **FR20** | Tính cước & thanh toán | Thanh toán tiền mặt | Hệ thống hỗ trợ khách hàng thanh toán bằng tiền mặt. |
| **FR21** | Tính cước & thanh toán | Thanh toán điện tử | Hệ thống hỗ trợ thanh toán điện tử thông qua nhà cung cấp thanh toán bên ngoài. |
| **FR22** | Tính cước & thanh toán | Xử lý thanh toán thất bại | Khi giao dịch điện tử thất bại, hệ thống thông báo cho khách hàng và cho phép xử lý lại theo chính sách doanh nghiệp. |
| **FR23** | Thông báo | Thông báo cho khách hàng | Hệ thống thông báo khi yêu cầu được tiếp nhận, tài xế nhận chuyến, tài xế đến điểm đón, chuyến hoàn thành và có kết quả thanh toán. |
| **FR24** | Thông báo | Thông báo cho tài xế | Hệ thống thông báo cho tài xế về chuyến mới và các thay đổi liên quan đến chuyến đang thực hiện. |
| **FR25** | Lịch sử & đánh giá | Xem lịch sử chuyến đi | Hệ thống cho phép khách hàng xem lịch sử các chuyến đi. |
| **FR26** | Lịch sử & đánh giá | Xem số tiền phải trả | Hệ thống cho phép khách hàng xem số tiền phải trả của chuyến đi. |
| **FR27** | Lịch sử & đánh giá | Đánh giá tài xế | Hệ thống cho phép khách hàng đánh giá tài xế sau khi hoàn thành chuyến. |
| **FR28** | Quản trị & vận hành | Quản lý khách hàng, tài xế và phương tiện | Nhân viên vận hành có thể quản lý thông tin khách hàng, tài xế và phương tiện. |
| **FR29** | Quản trị & vận hành | Quản lý và theo dõi chuyến đi | Nhân viên vận hành có thể quản lý chuyến đi và theo dõi các chuyến đang diễn ra. |
| **FR30** | Quản trị & vận hành | Kiểm tra trạng thái tài xế | Nhân viên vận hành có thể kiểm tra trạng thái hoạt động của tài xế. |
| **FR31** | Quản trị & vận hành | Hỗ trợ xử lý chuyến bị lỗi | Nhân viên vận hành có thể hỗ trợ xử lý các trường hợp chuyến bị lỗi. |
| **FR32** | Quản trị & vận hành | Tra cứu lịch sử giao dịch | Nhân viên vận hành có thể tra cứu lịch sử giao dịch. |
| **FR33** | Quản trị & vận hành | Phân quyền quản trị | Hệ thống kiểm soát quyền để nhân viên thông thường không thể thực hiện các thao tác nhạy cảm. |
| **FR34** | Báo cáo | Báo cáo hoạt động | Hệ thống cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. |

## 8. Non-Functional Requirements

| ID | Category | Non-Functional Requirement | Mô tả |
|---|---|---|---|
| **NFR01** | Performance & Scalability | Hoạt động ổn định khi tải cao | Hệ thống phải duy trì hoạt động ổn định vào các thời điểm nhu cầu sử dụng tăng cao. |
| **NFR02** | Scalability | Mở rộng độc lập các thành phần | Các thành phần của hệ thống phải có khả năng mở rộng độc lập khi tải tăng. |
| **NFR03** | Reliability | Cô lập lỗi giữa các thành phần | Lỗi xảy ra ở chức năng thanh toán hoặc thông báo không được làm toàn bộ hệ thống đặt xe ngừng hoạt động. |
| **NFR04** | Maintainability & Deployability | Triển khai chức năng độc lập | Các chức năng mới phải có khả năng được triển khai từng phần và hạn chế ảnh hưởng đến các chức năng đang hoạt động. |
| **NFR05** | Security | Xác thực người dùng | Khách hàng và tài xế phải được xác thực trước khi sử dụng các chức năng yêu cầu tài khoản. |
| **NFR06** | Security | Kiểm soát quyền truy cập | Các thao tác quản trị phải được kiểm soát quyền truy cập để ngăn người không có quyền thực hiện các thao tác nhạy cảm. |
| **NFR07** | Security & Privacy | Bảo vệ dữ liệu | Thông tin cá nhân, thông tin phương tiện, dữ liệu vị trí và dữ liệu giao dịch phải được bảo vệ. |
| **NFR08** | Security & Privacy | Không lưu thông tin thanh toán nhạy cảm | CAB System không được lưu trực tiếp thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán. |
| **NFR09** | Auditability | Lưu vết thao tác quan trọng | Hệ thống phải lưu vết các thao tác quan trọng để hỗ trợ kiểm tra và xử lý khi xảy ra sự cố. |
| **NFR10** | Extensibility | Mở rộng loại dịch vụ | Kiến trúc hệ thống phải cho phép bổ sung các loại dịch vụ mới trong tương lai mà không phải xây dựng lại toàn bộ ứng dụng. |
| **NFR11** | Extensibility | Mở rộng phương thức thanh toán | Hệ thống phải có khả năng bổ sung các phương thức thanh toán mới trong tương lai. |
| **NFR12** | Extensibility | Mở rộng kênh và nhà cung cấp thông báo | Hệ thống phải cho phép bổ sung các kênh hoặc nhà cung cấp thông báo mới mà không phải thay đổi toàn bộ hệ thống. |
| **NFR13** | Maintainability | Khả năng thay đổi thành phần kỹ thuật | Kiến trúc phải đủ linh hoạt để có thể thay đổi một số thành phần kỹ thuật mà không phải xây dựng lại toàn bộ ứng dụng. |

## 9. Business Rules

| ID | Business Rule | Mô tả |
|---|---|---|
| **BRU01** | Xác thực người dùng | Khách hàng và tài xế phải được xác thực trước khi sử dụng các chức năng yêu cầu tài khoản. |
| **BRU02** | Điều kiện tài xế nhận chuyến | Tài xế phải ở trạng thái sẵn sàng để được hệ thống xem xét khi tìm và phân công chuyến. |
| **BRU03** | Lựa chọn tài xế phù hợp | Hệ thống tìm tài xế dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành khác. |
| **BRU04** | Ưu tiên tài xế | Hệ thống ưu tiên tài xế phù hợp và gần khách hàng. |
| **BRU05** | Xử lý khi tài xế không nhận chuyến | Nếu tài xế không phản hồi hoặc từ chối, hệ thống tiếp tục tìm tài xế khác mà không yêu cầu khách hàng tạo lại yêu cầu. |
| **BRU06** | Không tìm được tài xế | Nếu không tìm được tài xế phù hợp, hệ thống phải thông báo rõ ràng cho khách hàng. |
| **BRU07** | Cập nhật trạng thái chuyến | Tài xế cập nhật trạng thái chuyến gồm: đã đến điểm đón, đã đón khách, đang di chuyển và hoàn thành chuyến. |
| **BRU08** | Thời điểm tính cước | Hệ thống xác định số tiền khách hàng phải trả sau khi chuyến đi hoàn thành. |
| **BRU09** | Cơ sở tính cước | Số tiền phải trả được xác định dựa trên loại dịch vụ và thông tin chuyến đi. |
| **BRU10** | Phương thức thanh toán | Khách hàng có thể thanh toán bằng tiền mặt hoặc phương thức thanh toán điện tử. |
| **BRU11** | Thanh toán điện tử | Thanh toán điện tử được xử lý thông qua nhà cung cấp thanh toán bên ngoài. |
| **BRU12** | Bảo vệ thông tin thanh toán | Thông tin nhạy cảm của thẻ hoặc tài khoản thanh toán không được lưu trực tiếp trong CAB System. |
| **BRU13** | Thanh toán thất bại | Nếu thanh toán điện tử thất bại, hệ thống phải thông báo cho khách hàng và cho phép xử lý lại theo chính sách doanh nghiệp. |
| **BRU14** | Đánh giá tài xế | Khách hàng chỉ có thể đánh giá tài xế sau khi chuyến đi hoàn thành. |
| **BRU15** | Phân quyền quản trị | Các thao tác quản trị nhạy cảm chỉ được thực hiện bởi người dùng có quyền phù hợp. |
| **BRU16** | Cách tính cước | **Cần làm rõ:** Công thức và quy tắc tính cước cụ thể chưa được doanh nghiệp chốt. |
| **BRU17** | Tiêu chí ưu tiên tài xế | **Cần làm rõ:** Các tiêu chí và thứ tự ưu tiên tài xế cụ thể chưa được doanh nghiệp chốt. |
| **BRU18** | Thời gian phản hồi của tài xế | **Cần làm rõ:** Thời gian tài xế phải phản hồi yêu cầu chuyến chưa được xác định. |
| **BRU19** | Chính sách hủy chuyến | **Cần làm rõ:** Điều kiện và cách xử lý khi hủy chuyến chưa được xác định. |
| **BRU20** | Xử lý mất kết nối mạng | **Cần làm rõ:** Cách xử lý khi khách hàng hoặc tài xế mất kết nối chưa được xác định. |
| **BRU21** | Thời gian lưu trữ dữ liệu | **Cần làm rõ:** Thời gian lưu trữ dữ liệu của hệ thống chưa được xác định. |

## 10. Exception Cases & Open Questions

### 10.1. Các trường hợp ngoại lệ

| ID | Quy trình | Trường hợp ngoại lệ | Cách xử lý |
|---|---|---|---|
| **EX01** | Tìm tài xế | Không tìm được tài xế phù hợp | Hệ thống thông báo rõ ràng cho khách hàng rằng không tìm được tài xế. |
| **EX02** | Tìm tài xế | Tài xế được đề xuất không phản hồi | Hệ thống tiếp tục tìm tài xế phù hợp khác mà không yêu cầu khách hàng tạo lại yêu cầu. |
| **EX03** | Tìm tài xế | Tài xế từ chối chuyến | Hệ thống tiếp tục tìm tài xế phù hợp khác mà không yêu cầu khách hàng tạo lại yêu cầu. |
| **EX04** | Thanh toán | Thanh toán điện tử thất bại | Hệ thống thông báo cho khách hàng và cho phép xử lý lại theo chính sách của doanh nghiệp. |
| **EX05** | Chuyến đi | Chuyến đi xảy ra lỗi | Nhân viên vận hành kiểm tra và hỗ trợ xử lý trường hợp chuyến bị lỗi. |
| **EX06** | Kết nối | Khách hàng hoặc tài xế mất kết nối mạng | Cách xử lý cụ thể chưa được xác định và cần xác nhận thêm với khách hàng. |
| **EX07** | Bảo mật | Người dùng chưa được xác thực | Hệ thống không cho phép khách hàng hoặc tài xế sử dụng các chức năng yêu cầu tài khoản khi chưa được xác thực. |
| **EX08** | Quản trị | Nhân viên không có quyền thực hiện thao tác nhạy cảm | Hệ thống kiểm soát quyền truy cập và ngăn các thao tác quản trị không được phép. |

### 10.2. Những điểm còn chưa rõ cần xác nhận với khách hàng

| ID | Chủ đề | Điểm chưa rõ | Câu hỏi cần xác nhận |
|---|---|---|---|
| **OQ01** | Tính cước | Cách tính tiền chuyến chưa được chốt. | Cước được tính dựa trên những yếu tố nào và công thức tính cụ thể như thế nào? |
| **OQ02** | Ưu tiên tài xế | Tiêu chí ưu tiên tài xế chưa được xác định đầy đủ. | Hệ thống ưu tiên tài xế dựa trên khoảng cách, thời gian chờ, trạng thái hoạt động hay các tiêu chí nào khác? |
| **OQ03** | Phản hồi tài xế | Chưa xác định thời gian tài xế phải phản hồi yêu cầu chuyến. | Tài xế có bao nhiêu thời gian để chấp nhận hoặc từ chối trước khi hệ thống chuyển sang tài xế khác? |
| **OQ04** | Hủy chuyến | Chính sách hủy chuyến chưa được chốt. | Ai được phép hủy chuyến, được hủy ở thời điểm nào và có áp dụng phí hủy hay không? |
| **OQ05** | Mất kết nối mạng | Chưa xác định cách xử lý khi khách hàng hoặc tài xế mất kết nối. | Hệ thống xử lý trạng thái chuyến và cập nhật dữ liệu như thế nào khi mất kết nối mạng? |
| **OQ06** | Lưu trữ dữ liệu | Chưa xác định thời gian lưu trữ dữ liệu. | Dữ liệu khách hàng, chuyến đi, vị trí, giao dịch và log cần được lưu trong bao lâu? |
| **OQ07** | Thanh toán thất bại | Chính sách xử lý lại thanh toán điện tử chưa được quy định cụ thể. | Khách hàng được phép thử thanh toán lại bao nhiêu lần và trong khoảng thời gian nào? |
| **OQ08** | Tìm tài xế | Chưa xác định giới hạn của quá trình tìm tài xế. | Hệ thống tiếp tục tìm tài xế trong bao lâu hoặc tối đa bao nhiêu tài xế trước khi thông báo thất bại? |
| **OQ09** | Vị trí tài xế | Chưa xác định tần suất cập nhật vị trí tài xế. | Vị trí tài xế được cập nhật với tần suất bao nhiêu để hỗ trợ tìm tài xế và dự kiến thời gian đến? |
| **OQ10** | Phân quyền quản trị | Chưa xác định chi tiết các vai trò và quyền quản trị. | Có những vai trò quản trị nào và mỗi vai trò được phép thực hiện những chức năng nào? |

## 11. ERD — CAB System MVP

ERD dưới đây mô hình hóa các thực thể dữ liệu chính cần thiết cho CAB System MVP, dựa trên quy trình đặt xe, phân công tài xế, thực hiện chuyến, thanh toán và đánh giá.

```mermaid
erDiagram

    USER {
        int user_id PK
        string username
        string password
        string role
        string status
        datetime created_at
    }

    CUSTOMER {
        int customer_id PK
        int user_id FK
        string full_name
        string phone
        string email
        string address
    }

    DRIVER {
        int driver_id PK
        int user_id FK
        string full_name
        string phone
        string license_number
        string status
        boolean available
        decimal latitude
        decimal longitude
    }

    VEHICLE {
        int vehicle_id PK
        int driver_id FK
        string license_plate
        string vehicle_type
        string brand
        string model
        string status
    }

    TRIP {
        int trip_id PK
        int customer_id FK
        int driver_id FK
        int vehicle_id FK
        string pickup_location
        string destination
        string trip_status
        datetime request_time
        datetime start_time
        datetime end_time
        decimal fare
    }

    PAYMENT {
        int payment_id PK
        int trip_id FK
        string payment_method
        decimal amount
        string payment_status
        string transaction_ref
        datetime payment_time
    }

    RATING {
        int rating_id PK
        int trip_id FK
        int customer_id FK
        int driver_id FK
        int score
        string comment
        datetime created_at
    }

    NOTIFICATION {
        int notification_id PK
        int user_id FK
        int trip_id FK
        string notification_type
        string message
        string status
        datetime created_at
    }

    USER ||--o| CUSTOMER : has
    USER ||--o| DRIVER : has

    DRIVER ||--o{ VEHICLE : owns

    CUSTOMER ||--o{ TRIP : books
    DRIVER ||--o{ TRIP : accepts
    VEHICLE ||--o{ TRIP : used_for

    TRIP ||--o{ PAYMENT : has
    TRIP ||--o| RATING : receives
    TRIP ||--o{ NOTIFICATION : generates

    CUSTOMER ||--o{ RATING : gives
    DRIVER ||--o{ RATING : receives

    USER ||--o{ NOTIFICATION : receives
```

### Main Entities

| Entity | Vai trò |
|---|---|
| **USER** | Lưu thông tin tài khoản, xác thực và vai trò người dùng trong hệ thống. |
| **CUSTOMER** | Lưu thông tin khách hàng sử dụng dịch vụ đặt xe. |
| **DRIVER** | Lưu hồ sơ tài xế, trạng thái hoạt động, trạng thái sẵn sàng và vị trí hiện tại. |
| **VEHICLE** | Lưu thông tin phương tiện của tài xế. |
| **TRIP** | Lưu thông tin yêu cầu đặt xe và toàn bộ thông tin liên quan đến chuyến đi. |
| **PAYMENT** | Lưu thông tin giao dịch thanh toán của chuyến đi. |
| **RATING** | Lưu đánh giá của khách hàng dành cho tài xế sau khi hoàn thành chuyến. |
| **NOTIFICATION** | Lưu thông tin các thông báo liên quan đến chuyến đi được gửi cho người dùng. |

## 12. Use Case Diagram — CAB System MVP

Use Case Diagram dưới đây mô tả các actor chính và các chức năng mà họ tương tác với trong phạm vi CAB System MVP.

```mermaid
flowchart LR

    %% Actors
    C[Khách hàng]
    D[Tài xế]
    O[Nhân viên vận hành]
    P[Nhà cung cấp thanh toán]
    N[Nhà cung cấp thông báo]

    subgraph CAB["CAB System"]

        UC01([Đăng ký tài khoản])
        UC02([Đăng nhập])
        UC03([Cập nhật thông tin cá nhân])

        UC04([Đặt xe])
        UC05([Theo dõi chuyến đi])
        UC06([Xem lịch sử chuyến đi])
        UC07([Đánh giá tài xế])

        UC08([Quản lý hồ sơ & phương tiện])
        UC09([Cập nhật trạng thái hoạt động])
        UC10([Nhận / từ chối chuyến])
        UC11([Cập nhật trạng thái chuyến])

        UC12([Tìm & phân công tài xế])

        UC13([Tính cước])
        UC14([Thanh toán])
        UC15([Xử lý thanh toán thất bại])

        UC16([Gửi thông báo])

        UC17([Quản lý khách hàng])
        UC18([Quản lý tài xế])
        UC19([Quản lý phương tiện])
        UC20([Quản lý chuyến đi])
        UC21([Theo dõi chuyến đang diễn ra])
        UC22([Xử lý chuyến bị lỗi])
        UC23([Tra cứu lịch sử giao dịch])
        UC24([Phân quyền quản trị])
        UC25([Báo cáo hoạt động])

    end

    %% Customer
    C --- UC01
    C --- UC02
    C --- UC03
    C --- UC04
    C --- UC05
    C --- UC06
    C --- UC07
    C --- UC14

    %% Driver
    D --- UC02
    D --- UC08
    D --- UC09
    D --- UC10
    D --- UC11

    %% Operations
    O --- UC17
    O --- UC18
    O --- UC19
    O --- UC20
    O --- UC21
    O --- UC22
    O --- UC23
    O --- UC24
    O --- UC25

    %% External providers
    P --- UC14
    P --- UC15

    N --- UC16

    %% Include-like relationships
    UC04 -. include .-> UC12
    UC12 -. include .-> UC16
    UC10 -. include .-> UC16
    UC11 -. include .-> UC16

    UC14 -. include .-> UC13
    UC14 -. include .-> UC16
    UC15 -. include .-> UC16

    UC20 -. include .-> UC11
```

### Main Actors

| Actor | Vai trò |
|---|---|
| **Khách hàng** | Đăng ký, đăng nhập, đặt xe, theo dõi chuyến, thanh toán, xem lịch sử và đánh giá tài xế. |
| **Tài xế** | Quản lý hồ sơ/phương tiện, cập nhật trạng thái hoạt động, nhận hoặc từ chối chuyến và cập nhật trạng thái chuyến. |
| **Nhân viên vận hành** | Quản lý khách hàng, tài xế, phương tiện, chuyến đi, theo dõi hoạt động, xử lý sự cố và xem báo cáo. |
| **Nhà cung cấp thanh toán** | Xử lý giao dịch thanh toán điện tử cho CAB System. |
| **Nhà cung cấp thông báo** | Hỗ trợ gửi thông báo đến khách hàng và tài xế. |

## 13. Acceptance Criteria

| ID | Functional Requirement | Acceptance Criteria |
|---|---|---|
| **AC01** | **FR01 – Đăng ký tài khoản khách hàng** | Khách hàng cung cấp đầy đủ thông tin bắt buộc thì tài khoản được tạo thành công; nếu thông tin không hợp lệ, hệ thống thông báo lỗi và không tạo tài khoản. |
| **AC02** | **FR02 – Đăng ký/tạo tài khoản tài xế** | Tài xế có thể tự đăng ký hoặc được nhân viên vận hành tạo tài khoản thành công khi thông tin hợp lệ. |
| **AC03** | **FR03 – Đăng nhập** | Khách hàng hoặc tài xế nhập thông tin đăng nhập hợp lệ thì được xác thực và truy cập hệ thống; nếu không hợp lệ, hệ thống thông báo lỗi. |
| **AC04** | **FR04 – Cập nhật thông tin cá nhân** | Khách hàng có thể chỉnh sửa và lưu lại thông tin cá nhân; hệ thống ghi nhận thay đổi thành công. |
| **AC05** | **FR05 – Cập nhật hồ sơ, phương tiện và trạng thái hoạt động** | Tài xế có thể cập nhật hồ sơ, thông tin phương tiện và chuyển sang trạng thái sẵn sàng nhận chuyến; hệ thống ghi nhận thay đổi. |
| **AC06** | **FR06 – Nhập thông tin chuyến** | Khách hàng có thể nhập điểm đón, điểm đến và lựa chọn loại xe trước khi gửi yêu cầu đặt xe. |
| **AC07** | **FR07 – Tạo yêu cầu đặt xe** | Khi thông tin chuyến hợp lệ, khách hàng gửi yêu cầu và hệ thống tạo yêu cầu đặt xe thành công. |
| **AC08** | **FR08 – Tiếp nhận yêu cầu** | Sau khi yêu cầu được tạo, hệ thống tiếp nhận và ghi nhận yêu cầu để bắt đầu quá trình tìm tài xế. |
| **AC09** | **FR09 – Xác định tài xế phù hợp** | Khi có yêu cầu đặt xe, hệ thống xác định tài xế phù hợp dựa trên vị trí, trạng thái sẵn sàng và các tiêu chí vận hành. |
| **AC10** | **FR10 – Ưu tiên tài xế** | Trong các tài xế phù hợp, hệ thống ưu tiên tài xế phù hợp và gần khách hàng. |
| **AC11** | **FR11 – Gửi yêu cầu đến tài xế** | Khi xác định được tài xế phù hợp, hệ thống gửi yêu cầu chuyến đến tài xế đó. |
| **AC12** | **FR12 – Xử lý phản hồi tài xế** | Hệ thống ghi nhận chính xác việc tài xế chấp nhận hoặc từ chối yêu cầu chuyến. |
| **AC13** | **FR13 – Tìm tài xế thay thế** | Khi tài xế không phản hồi hoặc từ chối, hệ thống tự động tiếp tục tìm tài xế khác mà không yêu cầu khách hàng tạo lại yêu cầu. |
| **AC14** | **FR14 – Thông báo không tìm được tài xế** | Khi không còn tài xế phù hợp, hệ thống thông báo rõ ràng cho khách hàng. |
| **AC15** | **FR15 – Cập nhật trạng thái chuyến** | Tài xế có thể cập nhật các trạng thái đã đến điểm đón, đã đón khách, đang di chuyển và hoàn thành chuyến; hệ thống ghi nhận trạng thái tương ứng. |
| **AC16** | **FR16 – Cập nhật vị trí tài xế** | Hệ thống ghi nhận vị trí tài xế để hỗ trợ tìm tài xế gần khách hàng và dự kiến thời gian đến. |
| **AC17** | **FR17 – Theo dõi chuyến** | Khách hàng có thể xem trạng thái hiện tại của chuyến trong quá trình thực hiện. |
| **AC18** | **FR18 – Hiển thị thông tin tài xế** | Sau khi có tài xế nhận chuyến, khách hàng xem được thông tin tài xế và thời gian dự kiến tài xế đến. |
| **AC19** | **FR19 – Tính tiền chuyến đi** | Sau khi chuyến hoàn thành, hệ thống xác định số tiền khách hàng phải trả dựa trên loại dịch vụ và thông tin chuyến đi. |
| **AC20** | **FR20 – Thanh toán tiền mặt** | Khi khách hàng chọn thanh toán tiền mặt, hệ thống hỗ trợ ghi nhận phương thức thanh toán của chuyến. |
| **AC21** | **FR21 – Thanh toán điện tử** | Khi khách hàng chọn thanh toán điện tử, hệ thống gửi yêu cầu đến nhà cung cấp thanh toán bên ngoài để xử lý giao dịch. |
| **AC22** | **FR22 – Xử lý thanh toán thất bại** | Khi giao dịch điện tử thất bại, hệ thống thông báo cho khách hàng và cho phép xử lý lại theo chính sách doanh nghiệp. |
| **AC23** | **FR23 – Thông báo cho khách hàng** | Khách hàng nhận được thông báo khi yêu cầu được tiếp nhận, tài xế nhận chuyến, tài xế đến điểm đón, chuyến hoàn thành và có kết quả thanh toán. |
| **AC24** | **FR24 – Thông báo cho tài xế** | Tài xế nhận được thông báo khi có chuyến mới hoặc có thay đổi liên quan đến chuyến đang thực hiện. |
| **AC25** | **FR25 – Xem lịch sử chuyến đi** | Khách hàng có thể xem danh sách và thông tin các chuyến đi đã được lưu trong lịch sử. |
| **AC26** | **FR26 – Xem số tiền phải trả** | Khách hàng có thể xem số tiền phải trả của chuyến đi sau khi hệ thống tính cước. |
| **AC27** | **FR27 – Đánh giá tài xế** | Sau khi chuyến hoàn thành, khách hàng có thể gửi đánh giá cho tài xế và hệ thống ghi nhận đánh giá. |
| **AC28** | **FR28 – Quản lý khách hàng, tài xế và phương tiện** | Nhân viên vận hành có thể xem và quản lý thông tin khách hàng, tài xế và phương tiện theo quyền được cấp. |
| **AC29** | **FR29 – Quản lý và theo dõi chuyến đi** | Nhân viên vận hành có thể xem thông tin và theo dõi các chuyến đang diễn ra. |
| **AC30** | **FR30 – Kiểm tra trạng thái tài xế** | Nhân viên vận hành có thể kiểm tra trạng thái hoạt động hiện tại của tài xế. |
| **AC31** | **FR31 – Hỗ trợ xử lý chuyến bị lỗi** | Khi chuyến gặp lỗi, nhân viên vận hành có thể truy cập thông tin liên quan để hỗ trợ xử lý. |
| **AC32** | **FR32 – Tra cứu lịch sử giao dịch** | Nhân viên vận hành có thể tra cứu lịch sử giao dịch được lưu trong hệ thống. |
| **AC33** | **FR33 – Phân quyền quản trị** | Người dùng chỉ được thực hiện các chức năng quản trị phù hợp với quyền được cấp; các thao tác không được phép phải bị hệ thống ngăn chặn. |
| **AC34** | **FR34 – Báo cáo hoạt động** | Hệ thống cung cấp báo cáo về số lượng chuyến, doanh thu, tỷ lệ hoàn thành, tỷ lệ hủy và hiệu quả hoạt động của tài xế. |

## 14. Requirements Traceability Matrix

| BG | BR | BPM/Module | FR | UC | AC |
|---|---|---|---|---|---|
| **BG01** | BR01 | Quản lý tài khoản & xác thực | FR01 – Đăng ký tài khoản khách hàng | UC01 | AC01 |
| **BG01** | BR01 | Quản lý tài khoản & xác thực | FR02 – Đăng ký/tạo tài khoản tài xế | UC01 | AC02 |
| **BG01** | BR01 | Quản lý tài khoản & xác thực | FR03 – Đăng nhập | UC02 | AC03 |
| **BG02** | BR05 | Quản lý tài khoản & xác thực | FR04 – Cập nhật thông tin cá nhân | UC03 | AC04 |
| **BG01** | BR01 | Quản lý tài xế & phương tiện | FR05 – Cập nhật hồ sơ, phương tiện và trạng thái hoạt động | UC08, UC09 | AC05 |
| **BG02** | BR04 | Đặt xe | FR06 – Nhập thông tin chuyến | UC04 | AC06 |
| **BG02** | BR04 | Đặt xe | FR07 – Tạo yêu cầu đặt xe | UC04 | AC07 |
| **BG02** | BR04 | Đặt xe | FR08 – Tiếp nhận yêu cầu | UC04 | AC08 |
| **BG01** | BR03 | Tìm kiếm & phân công tài xế | FR09 – Xác định tài xế phù hợp | UC12 | AC09 |
| **BG01** | BR03 | Tìm kiếm & phân công tài xế | FR10 – Ưu tiên tài xế | UC12 | AC10 |
| **BG01** | BR03 | Tìm kiếm & phân công tài xế | FR11 – Gửi yêu cầu đến tài xế | UC12 | AC11 |
| **BG01** | BR03 | Tìm kiếm & phân công tài xế | FR12 – Xử lý phản hồi tài xế | UC10 | AC12 |
| **BG01** | BR03 | Tìm kiếm & phân công tài xế | FR13 – Tìm tài xế thay thế | UC12 | AC13 |
| **BG01** | BR03 | Tìm kiếm & phân công tài xế | FR14 – Thông báo không tìm được tài xế | UC12, UC16 | AC14 |
| **BG03** | BR04 | Quản lý chuyến đi | FR15 – Cập nhật trạng thái chuyến | UC11 | AC15 |
| **BG01** | BR03 | Quản lý chuyến đi | FR16 – Cập nhật vị trí tài xế | UC12 | AC16 |
| **BG02** | BR05 | Quản lý chuyến đi | FR17 – Theo dõi chuyến | UC05 | AC17 |
| **BG02** | BR05 | Quản lý chuyến đi | FR18 – Hiển thị thông tin tài xế | UC05 | AC18 |
| **BG03** | BR06 | Tính cước & thanh toán | FR19 – Tính tiền chuyến đi | UC13 | AC19 |
| **BG03** | BR06 | Tính cước & thanh toán | FR20 – Thanh toán tiền mặt | UC14 | AC20 |
| **BG03** | BR06 | Tính cước & thanh toán | FR21 – Thanh toán điện tử | UC14 | AC21 |
| **BG03** | BR06 | Tính cước & thanh toán | FR22 – Xử lý thanh toán thất bại | UC15 | AC22 |
| **BG02** | BR07 | Thông báo | FR23 – Thông báo cho khách hàng | UC16 | AC23 |
| **BG02** | BR07 | Thông báo | FR24 – Thông báo cho tài xế | UC16 | AC24 |
| **BG02** | BR05 | Lịch sử & đánh giá | FR25 – Xem lịch sử chuyến đi | UC06 | AC25 |
| **BG02** | BR05 | Lịch sử & đánh giá | FR26 – Xem số tiền phải trả | UC06 | AC26 |
| **BG02** | BR04 | Lịch sử & đánh giá | FR27 – Đánh giá tài xế | UC07 | AC27 |
| **BG04** | BR08 | Quản trị & vận hành | FR28 – Quản lý khách hàng, tài xế và phương tiện | UC17, UC18, UC19 | AC28 |
| **BG04** | BR08 | Quản trị & vận hành | FR29 – Quản lý và theo dõi chuyến đi | UC20, UC21 | AC29 |
| **BG04** | BR08 | Quản trị & vận hành | FR30 – Kiểm tra trạng thái tài xế | UC18, UC21 | AC30 |
| **BG04** | BR08 | Quản trị & vận hành | FR31 – Hỗ trợ xử lý chuyến bị lỗi | UC22 | AC31 |
| **BG04** | BR08 | Quản trị & vận hành | FR32 – Tra cứu lịch sử giao dịch | UC23 | AC32 |
| **BG06** | BR11 | Quản trị & vận hành | FR33 – Phân quyền quản trị | UC24 | AC33 |
| **BG05** | BR09 | Báo cáo | FR34 – Báo cáo hoạt động | UC25 | AC34 |
