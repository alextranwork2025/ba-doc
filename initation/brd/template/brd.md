# TÀI LIỆU YÊU CẦU NGHIỆP VỤ

# 1. THÔNG TIN TÀI LIỆU

| Nội dung     | Thông tin                      |
| ------------ | ------------------------------ |
| Tên dự án    | [Tên dự án]                    |
| Tên tài liệu | Business Requirements Document |
| Mã tài liệu  | [BRD-XXX]                      |
| Phiên bản    | [1.0]                          |
| Ngày tạo     | [dd/mm/yyyy]                   |

## 1.1. Lịch sử thay đổi

| Phiên bản | Ngày cập nhật | Người cập nhật | Nội dung thay đổi              |
| --------- | ------------- | -------------- | ------------------------------ |
| 0.1       | [dd/mm/yyyy]  | [Họ tên]       | Khởi tạo tài liệu              |
| 1.0       | [dd/mm/yyyy]  | [Họ tên]       | Phê duyệt phiên bản chính thức |

## 1.2. Danh sách phê duyệt

| STT | Họ tên   | Vai trò   | Trạng thái   | Ngày xác nhận |
| --- | -------- | --------- | ------------ | ------------- |
| 1   | [Họ tên] | [Vai trò] | Chờ xác nhận | [dd/mm/yyyy]  |
| 2   | [Họ tên] | [Vai trò] | Chờ xác nhận | [dd/mm/yyyy]  |

# 2. THUẬT NGỮ VÀ TỪ VIẾT TẮT

| Thuật ngữ | Ý nghĩa                         |
| --------- | ------------------------------- |
| BRD       | Tài liệu yêu cầu nghiệp vụ      |
| BA        | Chuyên viên phân tích nghiệp vụ |
| UAT       | Kiểm thử chấp nhận người dùng   |
| FR        | Yêu cầu chức năng               |
| NFR       | Yêu cầu phi chức năng           |
| API       | Giao diện kết nối hệ thống      |
| MVP       | Phiên bản sản phẩm tối thiểu    |

# 3. TỔNG QUAN DỰ ÁN

## 3.1. Bối cảnh

Mô tả ngắn gọn bối cảnh hình thành dự án, tình trạng hiện tại và lý do doanh nghiệp cần triển khai hệ thống.

Ví dụ:

Hiện tại, doanh nghiệp đang quản lý thông tin bằng nhiều tệp Excel và phần mềm rời rạc. Dữ liệu chưa được đồng bộ, việc tổng hợp báo cáo mất nhiều thời gian và khó kiểm soát trách nhiệm của từng bộ phận.

## 3.2. Vấn đề hiện tại

| Mã    | Vấn đề         | Ảnh hưởng                          |
| ----- | -------------- | ---------------------------------- |
| PA-01 | [Mô tả vấn đề] | [Ảnh hưởng đến vận hành]           |
| PA-02 | [Mô tả vấn đề] | [Ảnh hưởng đến dữ liệu/người dùng] |

## 3.3. Mục tiêu dự án

| Mã     | Mục tiêu             | Kết quả mong đợi          |
| ------ | -------------------- | ------------------------- |
| OBJ-01 | [Mục tiêu nghiệp vụ] | [Kết quả có thể đo lường] |
| OBJ-02 | [Mục tiêu quản lý]   | [Kết quả có thể đo lường] |

## 3.4. Tiêu chí thành công

Dự án được xem là thành công khi:

- Các quy trình chính được triển khai trên hệ thống.
- Người dùng có thể thực hiện đầy đủ các nghiệp vụ thuộc phạm vi.
- Dữ liệu được quản lý tập trung và có phân quyền.
- Các báo cáo cần thiết được cung cấp đúng và đủ.
- Hệ thống được nghiệm thu và đưa vào sử dụng chính thức.

# 4. PHẠM VI DỰ ÁN

## 4.1. Phạm vi thực hiện

| STT | Phân hệ/Chức năng | Mô tả phạm vi |
| --- | ----------------- | ------------- |
| 1   | [Tên phân hệ]     | [Mô tả]       |
| 2   | [Tên phân hệ]     | [Mô tả]       |

## 4.2. Ngoài phạm vi

| STT | Nội dung ngoài phạm vi | Ghi chú                        |
| --- | ---------------------- | ------------------------------ |
| 1   | [Nội dung]             | [Lý do hoặc giai đoạn dự kiến] |
| 2   | [Nội dung]             | [Lý do hoặc giai đoạn dự kiến] |

# 5. CÁC BÊN LIÊN QUAN

| STT | Bên liên quan      | Vai trò             | Trách nhiệm                         |
| --- | ------------------ | ------------------- | ----------------------------------- |
| 1   | Ban lãnh đạo       | Phê duyệt           | Phê duyệt phạm vi và yêu cầu        |
| 2   | Đại diện nghiệp vụ | Người dùng chính    | Cung cấp và xác nhận yêu cầu        |
| 3   | Quản lý dự án      | Điều phối           | Theo dõi tiến độ và phạm vi         |
| 4   | Business Analyst   | Phân tích nghiệp vụ | Thu thập, phân tích và tài liệu hóa |
| 5   | Đội phát triển     | Xây dựng hệ thống   | Phát triển và sửa lỗi               |
| 6   | Đội kiểm thử       | Kiểm thử            | Kiểm tra chất lượng hệ thống        |

# 6. ĐỐI TƯỢNG SỬ DỤNG

| Mã vai trò | Vai trò       | Mô tả                    | Quyền chính                   |
| ---------- | ------------- | ------------------------ | ----------------------------- |
| ROLE-01    | Quản trị viên | Quản lý toàn bộ hệ thống | Cấu hình, phân quyền, tra cứu |
| ROLE-02    | Quản lý       | Phê duyệt và theo dõi    | Xem, duyệt, báo cáo           |
| ROLE-03    | Nhân viên     | Thực hiện nghiệp vụ      | Tạo, cập nhật, tra cứu        |
| ROLE-04    | Khách hàng    | Sử dụng cổng thông tin   | Xem và gửi thông tin          |

# 7. HIỆN TRẠNG NGHIỆP VỤ

## 7.1. Quy trình hiện tại

Mô tả quy trình đang được thực hiện trước khi triển khai hệ thống.

**Luồng tổng quát:**

[Bước 1] → [Bước 2] → [Bước 3] → [Bước 4]

## 7.2. Bảng mô tả quy trình hiện tại

| Bước | Vai trò thực hiện | Hoạt động   | Công cụ sử dụng      | Vấn đề   |
| ---- | ----------------- | ----------- | -------------------- | -------- |
| 1    | [Vai trò]         | [Hoạt động] | Excel/Email/Phần mềm | [Vấn đề] |
| 2    | [Vai trò]         | [Hoạt động] | [Công cụ]            | [Vấn đề] |

## 7.3. Điểm hạn chế

- Dữ liệu phân tán.
- Khó kiểm soát phiên bản.
- Thiếu lịch sử xử lý.
- Phê duyệt thủ công.
- Báo cáo chưa được tổng hợp tự động.
- Chưa có cơ chế phân quyền rõ ràng.

# 8. QUY TRÌNH ĐỀ XUẤT

## 8.1. Quy trình tương lai

Mô tả quy trình sau khi hệ thống được triển khai.

**Luồng đề xuất:**

[Người dùng tạo dữ liệu] → [Hệ thống kiểm tra] → [Quản lý phê duyệt] → [Hệ thống cập nhật trạng thái] → [Lưu lịch sử và báo cáo]

## 8.2. Bảng mô tả quy trình đề xuất

| Bước | Vai trò   | Hoạt động   | Xử lý của hệ thống | Kết quả   |
| ---- | --------- | ----------- | ------------------ | --------- |
| 1    | [Vai trò] | [Hoạt động] | [Xử lý]            | [Kết quả] |
| 2    | [Vai trò] | [Hoạt động] | [Xử lý]            | [Kết quả] |

## 8.3. Sơ đồ quy trình

Chèn một trong các sơ đồ sau:

- Business Process Model and Notation.
- Activity Diagram.
- Flowchart.
- Swimlane Diagram.

# 9. YÊU CẦU NGHIỆP VỤ

## 9.1. Danh sách yêu cầu nghiệp vụ

| Mã     | Tên yêu cầu   | Mô tả                     | Độ ưu tiên | Nguồn yêu cầu          |
| ------ | ------------- | ------------------------- | ---------- | ---------------------- |
| BR-001 | [Tên yêu cầu] | [Mô tả yêu cầu nghiệp vụ] | Cao        | [Phòng ban/người dùng] |
| BR-002 | [Tên yêu cầu] | [Mô tả yêu cầu nghiệp vụ] | Trung bình | [Phòng ban/người dùng] |

## 9.2. Chi tiết yêu cầu nghiệp vụ

### BR-001 – [Tên yêu cầu]

**Mục tiêu:**
[Mô tả mục tiêu của yêu cầu]

**Hiện trạng:**
[Mô tả cách nghiệp vụ đang được thực hiện]

**Mong muốn:**
[Mô tả kết quả nghiệp vụ mong muốn]

**Vai trò liên quan:**
[Danh sách vai trò]

**Điều kiện bắt đầu:**
[Điều kiện cần có để thực hiện]

**Luồng xử lý chính:**

1. [Vai trò] thực hiện [hoạt động].
2. Hệ thống kiểm tra [điều kiện].
3. Hệ thống thực hiện [xử lý].
4. [Vai trò] xác nhận hoặc phê duyệt.
5. Hệ thống cập nhật [trạng thái/kết quả].

**Luồng ngoại lệ:**

- Nếu [điều kiện lỗi], hệ thống [cách xử lý].
- Nếu [điều kiện không hợp lệ], hệ thống [thông báo].
- Nếu bị từ chối, dữ liệu chuyển sang trạng thái [trạng thái].

**Kết quả:**
[Mô tả kết quả sau khi hoàn thành]

**Độ ưu tiên:**
Cao / Trung bình / Thấp

# 10. MA TRẬN CHUYỂN TRẠNG THÁI

| Trạng thái hiện tại | Hành động | Trạng thái tiếp theo | Vai trò thực hiện |
| ------------------- | --------- | -------------------- | ----------------- |
| Nháp                | Gửi duyệt | Chờ duyệt            | Người tạo         |
| Chờ duyệt           | Phê duyệt | Đã phê duyệt         | Quản lý           |
| Chờ duyệt           | Từ chối   | Bị từ chối           | Quản lý           |
| Bị từ chối          | Chỉnh sửa | Nháp                 | Người tạo         |

# 11. YÊU CẦU PHÂN QUYỀN

| Chức năng     | Quản trị viên | Quản lý | Nhân viên        | Khách hàng |
| ------------- | ------------- | ------- | ---------------- | ---------- |
| Xem danh sách | Có            | Có      | Có giới hạn      | Không      |
| Tạo mới       | Có            | Có      | Có               | Không      |
| Chỉnh sửa     | Có            | Có      | Dữ liệu của mình | Không      |
| Xóa           | Có            | Không   | Không            | Không      |
| Phê duyệt     | Có            | Có      | Không            | Không      |
| Xuất báo cáo  | Có            | Có      | Có giới hạn      | Không      |

# 12. YÊU CẦU BÁO CÁO

| Mã     | Tên báo cáo       | Người sử dụng | Bộ lọc                | Nội dung              |
| ------ | ----------------- | ------------- | --------------------- | --------------------- |
| RP-001 | Báo cáo tổng hợp  | Quản lý       | Thời gian, trạng thái | Tổng hợp dữ liệu      |
| RP-002 | Báo cáo chi tiết  | Nhân viên     | Người phụ trách       | Chi tiết từng bản ghi |
| RP-003 | Báo cáo hiệu suất | Ban lãnh đạo  | Phòng ban, thời gian  | Chỉ số hiệu quả       |

## 12.1. Yêu cầu xuất báo cáo

- Xuất Excel.
- Xuất PDF.
- Cho phép lọc theo thời gian.
- Cho phép lọc theo trạng thái.
- Cho phép lọc theo người phụ trách.
- Dữ liệu báo cáo tuân thủ phân quyền.

# 13. YÊU CẦU THÔNG BÁO

| Mã       | Sự kiện                | Người nhận      | Kênh thông báo       | Nội dung                    |
| -------- | ---------------------- | --------------- | -------------------- | --------------------------- |
| NOTI-001 | Có yêu cầu chờ duyệt   | Người phê duyệt | Trong hệ thống/Email | Có yêu cầu mới cần xử lý    |
| NOTI-002 | Yêu cầu được phê duyệt | Người tạo       | Trong hệ thống/Email | Yêu cầu đã được phê duyệt   |
| NOTI-003 | Yêu cầu bị từ chối     | Người tạo       | Trong hệ thống/Email | Yêu cầu bị từ chối và lý do |

# 14. YÊU CẦU TÍCH HỢP

| Mã      | Hệ thống tích hợp   | Mục đích            | Dữ liệu trao đổi     | Phương thức       |
| ------- | ------------------- | ------------------- | -------------------- | ----------------- |
| INT-001 | [Tên hệ thống]      | [Mục đích]          | [Dữ liệu]            | API/File/Database |
| INT-002 | Email               | Gửi thông báo       | Người nhận, nội dung | SMTP/API          |
| INT-003 | Đăng nhập tập trung | Xác thực người dùng | Tài khoản, quyền     | SSO/OAuth         |

## 14.1. Nguyên tắc tích hợp

- Không tạo dữ liệu trùng lặp.
- Có cơ chế ghi nhận lỗi tích hợp.
- Có cơ chế thử lại khi kết nối thất bại.
- Có thể đối soát dữ liệu giữa các hệ thống.
- Dữ liệu trao đổi phải được bảo mật.

# 15. YÊU CẦU PHI CHỨC NĂNG

| Mã      | Nhóm yêu cầu      | Yêu cầu                                             |
| ------- | ----------------- | --------------------------------------------------- |
| NFR-001 | Hiệu năng         | Các trang thông thường phản hồi trong vòng [x] giây |
| NFR-002 | Khả năng chịu tải | Hỗ trợ tối thiểu [x] người dùng đồng thời           |
| NFR-003 | Bảo mật           | Dữ liệu phải được phân quyền và mã hóa phù hợp      |
| NFR-004 | Khả dụng          | Hệ thống hoạt động [99.x%] thời gian                |
| NFR-005 | Sao lưu           | Dữ liệu được sao lưu theo chu kỳ                    |
| NFR-006 | Khôi phục         | Có phương án khôi phục khi xảy ra sự cố             |
| NFR-007 | Nhật ký           | Lưu lịch sử đăng nhập và thao tác quan trọng        |
| NFR-008 | Tương thích       | Hỗ trợ các trình duyệt phổ biến                     |
| NFR-009 | Responsive        | Sử dụng được trên máy tính và thiết bị di động      |
| NFR-010 | Dễ sử dụng        | Giao diện rõ ràng, thống nhất và dễ thao tác        |

# 16. YÊU CẦU GIAO DIỆN

## 16.1. Nguyên tắc chung

- Giao diện sử dụng thống nhất.
- Ưu tiên tiếng Việt.
- Các nút hành động có tên rõ ràng.
- Trạng thái được thể hiện bằng màu sắc và nhãn.
- Có xác nhận trước các hành động quan trọng.
- Có thông báo rõ ràng khi thành công hoặc thất bại.
- Các trường bắt buộc phải được đánh dấu.

## 16.2. Danh sách màn hình

| Mã     | Tên màn hình          | Mục đích                   | Vai trò sử dụng |
| ------ | --------------------- | -------------------------- | --------------- |
| UI-001 | Đăng nhập             | Xác thực người dùng        | Tất cả          |
| UI-002 | Trang tổng quan       | Theo dõi số liệu tổng hợp  | Quản lý         |
| UI-003 | Danh sách [đối tượng] | Tra cứu và quản lý dữ liệu | Người dùng      |
| UI-004 | Chi tiết [đối tượng]  | Xem thông tin chi tiết     | Người dùng      |
| UI-005 | Tạo mới [đối tượng]   | Nhập dữ liệu mới           | Người dùng      |

# 17. RỦI RO DỰ ÁN

| Mã       | Rủi ro                          | Khả năng   | Mức ảnh hưởng | Biện pháp xử lý                          |
| -------- | ------------------------------- | ---------- | ------------- | ---------------------------------------- |
| RISK-001 | Yêu cầu thay đổi liên tục       | Cao        | Cao           | Thiết lập quy trình quản lý thay đổi     |
| RISK-002 | Dữ liệu đầu vào không đầy đủ    | Trung bình | Cao           | Rà soát và làm sạch dữ liệu              |
| RISK-003 | Người dùng chậm xác nhận        | Trung bình | Cao           | Chốt đầu mối và lịch xác nhận            |
| RISK-004 | Hệ thống tích hợp chưa sẵn sàng | Trung bình | Cao           | Chuẩn bị phương án nhập dữ liệu thay thế |
