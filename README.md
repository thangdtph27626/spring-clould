# Spring clould

Vậy là bạn đã nghe nói về Spring Cloud và cách nó có thể giúp xây dựng các ứng dụng dựa trên microservice. Trước khi bạn tự mình dùng thử Spring Cloud, hãy đọc thêm về framework này, mối quan hệ của nó với Spring Boot, các tính năng của nó, v.v.

Chúng ta sẽ đơn giản hóa những kiến ​​thức cơ bản về Spring Cloud để bạn có thể cải thiện kết quả phát triển và tạo ra nhiều ứng dụng thành công hơn.

## Spring Cloud là gì?

- Spring Cloud cung cấp các công cụ để nhà phát triển nhanh chóng xây dựng một số pattern phổ biến trong hệ thống phân tán. Việc phối hợp các hệ thống phân tán dẫn đến các pattern tấm nồi hơi và việc sử dụng Spring Cloud các nhà phát triển có thể nhanh chóng xây dựng các Service  và ứng dụng triển khai các pattern đó

Nói cách khác, Spring Cloud là một framework để xây dựng các ứng dụng đám mây và microservice mạnh mẽ.

Nó có thể giúp các nhà phát triển giải quyết các vấn đề khi chuyển sang môi trường phân tán—môi trường điện toán nơi các thành phần được trải rộng trên nhiều máy tính khác nhau.

Các nhà phát triển có thể sử dụng Spring Cloud cho:

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

- Cân bằng tải thông qua Ribbon cân bằng tải phía máy khách, cho phép các nhà phát triển quản lý hành vi của máy khách HTTP và TPC

- Khả năng chịu lỗi thông qua Spring Cloud Netflix Hystrix

- Quản lý định tuyến trong kiến ​​trúc microservice thông qua máy chủ ứng dụng Zuul

 Spring Cloud cho phép các nhà phát triển xây dựng ứng dụng cho trình duyệt internet, thiết bị di động và Internet of Things (IoT) thông qua cổng API.

![image](https://github.com/thangdtph27626/spring-clould/assets/109157942/b0c35903-4c54-49dc-9e55-1087aad2760d)

 ## Spring Cloud giải quyết được những vấn đề gì?

 Ngày càng có nhiều nhà phát triển sử dụng microservice để xây dựng ứng dụng. Cách tiếp cận phần mềm này chia các thành phần của ứng dụng thành các Service  nhỏ hoạt động độc lập - còn được gọi là ranh giới Service .

Spring Cloud giúp các nhà phát triển xây dựng kiến ​​trúc vi Service  thành công bằng cách tự động hóa các tác vụ quản trị và cải thiện khả năng chịu lỗi.

Việc thảo luận về mối quan hệ giữa Spring Boot và Spring Cloud cũng rất quan trọng:

- Spring Boot là framework Java mã nguồn mở giúp tạo ra các microservice. Nó cho phép các nhà phát triển tập trung vào mã thay vì thiết lập và định cấu hình môi trường microservice. Nó cũng cung cấp các công cụ phát triển khác nhau giúp ứng dụng thành công hơn.

- Spring Cloud là một thành phần của Spring Boot. Nó cho phép các nhà phát triển chia nhỏ và tạo ra các mẫu phức tạp trong môi trường phân tán. Nó cũng tập trung quản lý cấu hình và cung cấp bảo mật cao hơn Spring Boot nguồn mở.

- Cả Spring Boot và Spring Cloud đều là một phần của Spring Framework. Các nhà phát triển thường sẽ sử dụng cả hai công nghệ để tạo và duy trì các Service  vi mô.

## Cách sử dụng spring Cloud 

Bạn có thể bắt đầu một dự án Spring Cloud mới bằng cách truy cập vào start.spring.io. Tại đây, bạn có thể chọn phiên bản Spring Boot và dự án Spring Cloud mà bạn muốn thực hiện.

Điều đó sẽ thêm phiên bản có liên quan của Spring Cloud BOM (bill of materials)—một dự án với một loạt các phần phụ thuộc được xác định trước—vào tệp Maven hoặc Gradle của bạn.

Maven và Gradle là 'build tools' tự động hóa các tác vụ liên quan đến việc chuyển đổi mã nguồn ứng dụng của bạn thành một tạo phẩm có thể xuất bản.

Các nhà phát triển có thể tự chuyển đổi mã nguồn ứng dụng, nhưng đây là một quá trình lâu dài và tốn nhiều công sức, đòi hỏi phải biên dịch nhiều mã.

Bạn có thể thấy Spring Boot và Spring Cloud bổ sung cho nhau, vì vậy chúng tôi khuyên bạn nên hiểu cả hai trước khi bắt đầu một dự án mới.

Nếu bạn muốn thêm Spring Cloud vào ứng dụng Spring Boot hiện có, bạn sẽ cần phải quyết định phiên bản Spring Cloud chính xác để sử dụng.

## Tính năng Spring Cloud


