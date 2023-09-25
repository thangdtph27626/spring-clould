# Spring clould

Vậy là bạn đã nghe nói về Spring Cloud và cách nó có thể giúp xây dựng các ứng dụng dựa trên microservice. Trước khi bạn tự mình dùng thử Spring Cloud, hãy đọc thêm về framework này, mối quan hệ của nó với Spring Boot, các tính năng của nó, v.v.

Chúng ta sẽ đơn giản hóa những kiến ​​thức cơ bản về Spring Cloud để bạn có thể cải thiện kết quả phát triển và tạo ra nhiều ứng dụng thành công hơn.

## Spring Cloud là gì?

- Spring Cloud cung cấp các công cụ để Developers  nhanh chóng xây dựng một số pattern phổ biến trong hệ thống phân tán. Việc phối hợp các hệ thống phân tán dẫn đến các pattern tấm nồi hơi và việc sử dụng Spring Cloud các Developers  có thể nhanh chóng xây dựng các Service  và ứng dụng triển khai các pattern đó

Nói cách khác, Spring Cloud là một framework để xây dựng các ứng dụng đám mây và microservice mạnh mẽ.

Nó có thể giúp các Developers  giải quyết các vấn đề khi chuyển sang môi trường phân tán—môi trường điện toán nơi các thành phần được trải rộng trên nhiều máy tính khác nhau.

Các Developers  có thể sử dụng Spring Cloud cho:

- Quản lý cấu hình

- Định tuyến thông minh

- Khám phá Service 

- Bộ ngắt mạch

- Xe buýt điều khiển

- Phân phối sessions

- Khóa toàn cầu

- Mã thông báo một lần

- Bầu cử lãnh đạo

- Khám phá Service  qua Netflix Eureka, phần mềm trung gian dựa trên API REST để khám phá các ứng dụng web

- Cân bằng tải thông qua Ribbon cân bằng tải phía máy khách, cho phép các Developers  quản lý hành vi của máy khách HTTP và TPC

- Khả năng chịu lỗi thông qua Spring Cloud Netflix Hystrix

- Quản lý định tuyến trong kiến ​​trúc microservice thông qua máy chủ ứng dụng Zuul

 Spring Cloud cho phép các Developers  xây dựng ứng dụng cho trình duyệt internet, thiết bị di động và Internet of Things (IoT) thông qua cổng API.

![image](https://github.com/thangdtph27626/spring-clould/assets/109157942/b0c35903-4c54-49dc-9e55-1087aad2760d)

 ## Spring Cloud giải quyết được những vấn đề gì?

 Ngày càng có nhiều Developers  sử dụng microservice để xây dựng ứng dụng. Cách tiếp cận phần mềm này chia các thành phần của ứng dụng thành các Service  nhỏ hoạt động độc lập - còn được gọi là ranh giới Service .

Spring Cloud giúp các Developers  xây dựng kiến ​​trúc vi Service  thành công bằng cách tự động hóa các tác vụ quản trị và cải thiện khả năng chịu lỗi.

Việc thảo luận về mối quan hệ giữa Spring Boot và Spring Cloud cũng rất quan trọng:

- Spring Boot là framework Java mã nguồn mở giúp tạo ra các microservice. Nó cho phép các Developers  tập trung vào mã thay vì thiết lập và định cấu hình môi trường microservice. Nó cũng cung cấp các công cụ phát triển khác nhau giúp ứng dụng thành công hơn.

- Spring Cloud là một thành phần của Spring Boot. Nó cho phép các Developers  chia nhỏ và tạo ra các mẫu phức tạp trong môi trường phân tán. Nó cũng tập trung quản lý cấu hình và cung cấp bảo mật cao hơn Spring Boot nguồn mở.

- Cả Spring Boot và Spring Cloud đều là một phần của Spring Framework. Các Developers  thường sẽ sử dụng cả hai công nghệ để tạo và duy trì các Service  vi mô.

## Cách sử dụng spring Cloud 

Bạn có thể bắt đầu một dự án Spring Cloud mới bằng cách truy cập vào start.spring.io. Tại đây, bạn có thể chọn phiên bản Spring Boot và dự án Spring Cloud mà bạn muốn thực hiện.

Điều đó sẽ thêm phiên bản có liên quan của Spring Cloud BOM (bill of materials)—một dự án với một loạt các phần phụ thuộc được xác định trước—vào tệp Maven hoặc Gradle của bạn.

Maven và Gradle là 'build tools' tự động hóa các tác vụ liên quan đến việc chuyển đổi mã nguồn ứng dụng của bạn thành một tạo phẩm có thể xuất bản.

Các Developers  có thể tự chuyển đổi mã nguồn ứng dụng, nhưng đây là một quá trình lâu dài và tốn nhiều công sức, đòi hỏi phải biên dịch nhiều mã.

Bạn có thể thấy Spring Boot và Spring Cloud bổ sung cho nhau, vì vậy chúng tôi khuyên bạn nên hiểu cả hai trước khi bắt đầu một dự án mới.

Nếu bạn muốn thêm Spring Cloud vào ứng dụng Spring Boot hiện có, bạn sẽ cần phải quyết định phiên bản Spring Cloud chính xác để sử dụng.

## Tính năng Spring Cloud

Dưới đây là một số tính năng của Spring Cloud:

### Spring Cloud Config
Spring Cloud Config (hoặc Spring Cloud Config Server) cung cấp hỗ trợ phía máy khách và máy chủ để cấu hình trong hệ thống phân tán.

Nó cung cấp cho các Developers  một vị trí tập trung để xử lý các thuộc tính ứng dụng bên ngoài trên các môi trường. Cấu hình đám mây mùa xuân:

- Cung cấp API dựa trên tài nguyên HTTP cho các cặp tên-giá trị hoặc nội dung YAML
- Có thể mã hóa/giải mã các giá trị thuộc tính đối xứng hoặc bất đối xứng
- Nhúng vào ứng dụng Spring Boot

### Spring Cloud Stream

Spring Cloud Stream xây dựng các vi dịch vụ hướng sự kiện có thể mở rộng thông qua hệ thống nhắn tin dùng chung. Nó hỗ trợ triển khai chất kết dính cho các nền tảng như:

- RabbitMQ
- Apache Kafka
- Amazon Kinesis

### Spring Cloud Netflix
Spring Cloud Netflix đi kèm với tích hợp Netflix OSS cho các ứng dụng Spring Boot. Nó liên kết và tự động cấu hình Môi trường mùa xuân và các thành ngữ mô hình lập trình khác.

### Spring Cloud Gateway 
Spring Cloud Gateway là thư viện để tạo cổng API trên Spring WebFlux, cho phép các Developers  định tuyến tới API và cải thiện khả năng phục hồi, số liệu, bảo mật và giám sát.

Các tính năng của Spring Cloud Gateway bao gồm:

- Tích hợp bộ ngắt mạch
- Vị ngữ và lọc văn bản
- Viết lại đường dẫn
- Giới hạn tỷ lệ yêu cầu
  
### Spring Cloud Bus

Spring Cloud Bus kết nối các nút hệ thống phân tán với một trình trung chuyển tin nhắn, cho phép các Developers  truyền đi các thay đổi cấu hình và hướng dẫn quản lý.

Các tính năng khác của Spring Cloud bao gồm:
- Spring Cloud Sleuth
- Spring Cloud Contract
- Spring Cloud Data Flow

### Spring Cloud security

Vì Spring Boot là một framework mã nguồn mở nên nó có thể làm tăng nguy cơ xảy ra các lỗ hổng bảo mật. Sử dụng Spring Cloud kết hợp với Spring Boot có thể đảm bảo an toàn cho việc phát triển ứng dụng.

Dưới đây là một số tính năng bảo mật của Spring Cloud:

- Spring Cloud sử dụng mô hình khai báo mà các Developers  có thể định cấu hình tập trung hoặc bên ngoài khi triển khai hệ thống các thành phần từ xa.

- Developers  có thể chuyển tiếp mã thông báo SSO từ dịch vụ giao diện người dùng sang dịch vụ phụ trợ bằng máy chủ proxy Zuul

- Developers  có thể chuyển tiếp mã thông báo giữa máy chủ tài nguyên này và máy chủ tài nguyên khác

- Developers  có thể định cấu hình xác thực xuôi dòng bằng máy chủ proxy Zuul
