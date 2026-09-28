# Kế hoạch Tuần 1 và Ngày 1 – Senior Java Developer

Dựa trên lộ trình 6 tháng và khung 8 giờ/ngày, tuần đầu tiên tập trung vào 3 mục tiêu chính:

1. Thiết lập nền tảng bản sắc Senior: trách nhiệm, tư duy thiết kế, tính kỷ luật học tập.
2. Thiết lập môi trường và workflow học tập: Git, Java, Maven/Gradle, Docker, project mẫu.
3. Bắt đầu xây nền tảng kiến thức và dự án cá nhân: Java core, System Design, microservices cơ bản.

---

## 1) Mục tiêu của Tuần 1

### Mục tiêu học tập
- Hoàn thành 1 buổi đọc và nhắc lại tuyên bố bản sắc Senior mỗi ngày.
- Thiết lập môi trường học tập: Git, JDK 17+, IntelliJ IDEA, Maven/Gradle, Docker Desktop.
- Nắm vững nền tảng Java core: OOP, collections, exception, streams, generics.
- Hiểu khái niệm System Design cơ bản: scalability, latency, throughput, load balancer, database, caching.
- Bắt đầu hoàn thiện Product Service cơ bản trong dự án microservices.

### Kết quả đầu ra của tuần
- Có 1 repository Git sạch, có cấu trúc rõ ràng.
- Hoàn thành 3–5 bài thực hành Java cơ bản.
- Viết 1 bài note kỹ thuật ngắn hoặc blog đầu tiên.
- Xây dựng được mô hình sơ bộ Product Service với API REST đơn giản.

---

## 2) Khung thời gian học theo ngày (8 giờ/ngày)

| Thời gian | Hoạt động | Ghi chú |
|---|---|---|
| 5:30–6:00 | Đọc tuyên bố bản sắc, nhắc lại mục tiêu ngày | Không dùng điện thoại |
| 6:00–7:30 | Block 1: Lý thuyết sâu | System Design / Java Core |
| 7:30–8:00 | Ăn sáng, nghỉ ngắn | |
| 8:00–12:00 | Làm việc tại công ty | Áp dụng tư duy trong công việc |
| 12:00–13:00 | Ăn trưa, nghỉ ngơi | Không học |
| 13:00–14:30 | Block 2: Thực hành Java / coding | LeetCode / mini lab |
| 14:30–14:45 | Nghỉ ngắn | Đi bộ, uống nước |
| 14:45–16:15 | Block 3: Dự án cá nhân | Product Service |
| 16:15–16:30 | Nghỉ ngắn | |
| 16:30–18:00 | Block 4: Học chuyên sâu | Docker / Git / Java Boot |
| 18:00–19:00 | Ăn tối, nghỉ ngơi | |
| 19:00–20:30 | Block 5: Viết tài liệu / blog / review | Dạy lại kiến thức |
| 20:30–21:00 | Nhật ký, tổng kết | Ghi XP và học được gì |
| 21:00–21:30 | Đọc sách kỹ thuật / light reading | |
| 21:30–22:00 | Thư giãn, chuẩn bị ngủ | |

---

## 3) Lịch học Tuần 1

### Thứ 2 – Thiết lập nền tảng và bản sắc Senior
- 6:00–7:30: Đọc lại tuyên bố bản sắc Senior Java Developer. Ghi ra 3 hành vi mình sẽ thực hiện trong tuần.
- 13:00–14:30: Java Core: OOP, class, object, inheritance, abstraction, encapsulation, polymorphism.
- 14:45–16:15: Khởi tạo dự án Product Service bằng Spring Boot, chuẩn bị cấu trúc package.
- 16:30–18:00: Thiết lập Git, GitHub, JDK 17, Maven/Gradle, IntelliJ IDEA, Docker Desktop.
- 19:00–20:30: Viết note: “Tôi là Senior Java Developer như thế nào trong thực tế?”
- 20:30–21:00: Nhật ký và đánh dấu XP.

### Thứ 3 – Nền tảng Java và design thinking
- 6:00–7:30: System Design cơ bản: scalability, availability, latency, throughput, database selection.
- 13:00–14:30: Java Collections, Map/List/Set, equals/hashCode, streams, lambda.
- 14:45–16:15: Tạo entity Product, repository, controller REST API đầu tiên.
- 16:30–18:00: Docker cơ bản: container, image, dockerfile, docker compose, chạy local PostgreSQL.
- 19:00–20:30: Viết 1 bài blog ngắn: “Java Streams trong thực tế như thế nào?”
- 20:30–21:00: Nhật ký.

### Thứ 4 – Java thực chiến và API đầu tiên
- 6:00–7:30: Clean Architecture cơ bản: entities, use cases, adapters, service layer.
- 13:00–14:30: Exception handling, validation, DTO, mapper.
- 14:45–16:15: Hoàn thiện CRUD Product API: getAll, getById, create, update, delete.
- 16:30–18:00: PostgreSQL + Spring Data JPA cấu hình cơ bản, migration schema.
- 19:00–20:30: Review code của mình, kiểm tra naming conventions, architecture boundaries.
- 20:30–21:00: Nhật ký.

### Thứ 5 – Testing và chất lượng code
- 6:00–7:30: Testing fundamentals: unit test, integration test, TDD.
- 13:00–14:30: JUnit 5 + Mockito, viết test cho Product Service.
- 14:45–16:15: Thêm validation, test controller và service.
- 16:30–18:00: Cài đặt Lombok, mapstruct hoặc manual mapper; review code smell.
- 19:00–20:30: Viết ADR hoặc note thiết kế: “Tại sao Product Service nên tách service layer?”
- 20:30–21:00: Nhật ký.

### Thứ 6 – System Design & Dự án đầu tiên
- 6:00–7:30: System Design: API Gateway, database, cache, load balancer, message queue.
- 13:00–14:30: LeetCode 2 bài: array/string hoặc hashmap.
- 14:45–16:15: Thêm cài đặt pagination, sorting, API query cho Product.
- 16:30–18:00: Tạo Docker Compose để chạy app + db; test local end-to-end.
- 19:00–20:30: Viết blog ngắn: “Microservices trong thực tế bắt đầu từ đâu?”
- 20:30–21:00: Nhật ký.

### Thứ 7 – Review và tổng kết tuần
- 6:00–7:30: Ôn tập: hệ thống kiến thức tuần 1, mục tiêu đã đạt được gì.
- 13:00–14:30: Ôn lại các bài lab Java, sửa lỗi và note lại cách giải quyết.
- 14:45–16:15: Kiểm tra lại dự án Product Service và chuẩn bị commit tuần.
- 16:30–18:00: Tối ưu project structure, README đầu tiên và hướng dẫn chạy project.
- 19:00–20:30: Viết recap tuần: 3 kiến thức mới, 3 lỗi đã sửa, 3 cải tiến cho tuần sau.
- 20:30–21:00: Nhật ký và tự đánh giá tín nhiệm tuần.

### Chủ nhật – Nghỉ/light recovery
- Nghỉ thật sự ít nhất 1 buổi trong tuần.
- Nếu còn sức, dành 1–2 giờ để đọc nhẹ, không học quá tải.
- Khi nghỉ, hãy reset tâm trí, ngủ đủ và chuẩn bị cho tuần 2.

---

## 4) Kế hoạch Ngày 1 (chi tiết thực thi)

### Mục tiêu ngày 1
- Đọc và hiểu bản sắc Senior Java Developer.
- Thiết lập môi trường học tập cơ bản.
- Bắt đầu học Java Core và kiến thức thiết kế hệ thống.
- Khởi tạo project Product Service đầu tiên.

### Lịch ngày 1

#### 5:30–6:00 – Tuyên bố bản sắc
- Đọc to phiên bản chính của `../../senior-java-developer-identity-statement.md`.
- Chọn 3 hành vi mà mình sẽ thực hiện hôm nay.
- Ghi ra câu: “Hôm nay, tôi sẽ làm gì để xứng đáng với bản sắc Senior?”

#### 6:00–7:30 – Block 1: System Design + Java Core
- Học khái niệm cơ bản:
  - Scalability
  - Availability
  - Latency vs throughput
  - Database vs cache
  - Load balancer
- Java Core:
  - OOP: class, object, encapsulation, inheritance, polymorphism.
  - Collection: ArrayList, HashMap, LinkedList, Set.
  - Exception handling.

#### 7:30–8:00 – Nghỉ, ăn sáng
- Ăn sáng, đi bộ ngắn, không lướt điện thoại quá lâu.

#### 8:00–12:00 – Làm việc tại công ty
- Chú ý quan sát cách team design, review code, và giải quyết issue.
- Ghi nhận 1 kỹ thuật hoặc quyết định thiết kế mà bạn thấy có giá trị.

#### 12:00–13:00 – Nghỉ trưa
- Không học quá tải, ưu tiên nghỉ phục hồi.

#### 13:00–14:30 – Block 2: Thực hành Java
- Viết 1 mini exercise Java:
  - class `Product` với fields và methods.
  - `ArrayList` + `HashMap` example.
  - exception handling sample.
- Tạo file `notes/java-core-day1.md` hoặc `lessons-learned.md` nếu muốn lưu ghi chú.

#### 14:45–16:15 – Dự án cá nhân: Product Service
- Tạo project Spring Boot đầu tiên.
- Cấu trúc:
  - `controller`
  - `service`
  - `entity`
  - `repository`
  - `dto`
- Tạo entity `Product` đầu tiên.
- Tạo API `GET /products` trả về danh sách rỗng hoặc mẫu dữ liệu.

#### 16:30–18:00 – Docker + Git + Environment
- Cài đặt / kiểm tra:
  - Java 17
  - Maven hoặc Gradle
  - IntelliJ IDEA
  - Docker
  - GitHub account
- Tạo repository GitHub cho dự án đầu tiên.
- Thêm file `.gitignore`, `README.md`, `docker-compose.yml` sơ bộ.

#### 19:00–20:30 – Viết tài liệu / dạy lại
- Ghi 1 bài blog ngắn:
  - “Hôm nay tôi học được gì về Java Core và thiết kế hệ thống?”
- Mục tiêu: viết để người khác hiểu, không chỉ lưu cho mình.

#### 20:30–21:00 – Nhật ký và review
- Trả lời 5 câu hỏi:
  1. Hôm nay tôi học được gì?
  2. Hôm nay tôi đã hành động như Senior ở đâu?
  3. Ở đâu tôi còn tư duy như Mid?
  4. Ngày mai tôi sẽ cải thiện điều gì?
  5. Tổng XP hôm nay là bao nhiêu?

---

## 5) Checklist hoàn thành Ngày 1

- [ ] Đọc tuyên bố bản sắc Senior Java Developer.
- [ ] Chọn 3 hành vi Senior mình sẽ thực hành hôm nay.
- [ ] Thiết lập môi trường Java/Git/Docker.
- [ ] Viết 1 bài Java Core mini exercise.
- [ ] Khởi tạo project Spring Boot Product Service.
- [ ] Thiết kế cơ bản package và entity Product.
- [ ] Ghi nhật ký cuối ngày.
- [ ] Commit lần đầu lên GitHub.

---

## 6) Tiêu chí thành công cho Tuần 1

- Có ít nhất 1 commit mỗi ngày hoặc 5 commit trong tuần.
- Có 1 dự án Product Service chạy local được.
- Có 3 bài note / blog ngắn đã viết.
- Có 2 bài Java exercise hoặc tutorial đã làm xong.
- Có nhật ký học tập tuần + review bản sắc mỗi ngày.

---

## 7) Gợi ý thực thi để không kiệt sức

- Dùng Pomodoro 50/10: 50 phút tập trung, 10 phút nghỉ.
- Không học quá 3 block liên tiếp mà không nghỉ.
- Nếu cảm thấy mệt, giảm bớt lượng lý thuyết, ưu tiên thực hành và ngủ đủ.
- Mỗi tối, review 3 điều: học được gì, sai ở đâu, cải thiện ngày mai.

---

## 8) Mục tiêu tuần 2

- Tăng tốc Java Web và Spring Boot.
- Hoàn thiện Product Service CRUD.
- Thêm JPA, DTO, validation, test.
- Bắt đầu làm quen với Docker Compose và PostgreSQL.

Bắt đầu từ đây: ngày 1 không cần hoàn hảo, chỉ cần có tiến bộ thật sự và tạo thói quen đúng. Nền móng của một Senior được xây từ những ngày đều đặn, không phải từ một lần bùng nổ.
