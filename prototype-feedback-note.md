# Prototype Feedback Note — Option B

## 1. Thông tin phiên test

* **Người facilitate:** Lê Thị Thuý
* **Tester/context:** Lê Thị Linh — người học sử dụng VLearn, thường lưu highlight để quay lại làm bài tập hoặc ôn tập.
* **Ngày/giờ:** 19/08/2026 — bổ sung giờ test
* **Option được test:** B — AI Review Note
* **Prototype/link:** `option-b-ai-review-note.html`
* **Task giao cho tester:** Xem bản review do AI tổng hợp từ highlight/note, kiểm tra nguồn, chỉnh sửa một nội dung và quyết định xác nhận hoặc bỏ qua bản review.

## 2. Observation table

| Observation                              | Note                                                                                                                                                              |
| ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **First action**                         | Tester đọc phần `Key ideas` trước, sau đó chuyển sang phần `Questions` và `Don't understand`.                                                                     |
| **Chỗ dừng, do dự hoặc hiểu sai**        | Tester dừng ở một ý do AI viết vì không nhớ mình từng highlight nội dung đó với mục đích gì. Tester chưa muốn xác nhận trước khi kiểm tra nguồn.                  |
| **Evidence được đọc hay bỏ qua**         | Tester đọc bản review trước, nhưng mở source khi gặp một ý chưa chắc chắn. Một số mục ít liên quan bị lướt qua.                                                   |
| **Cách tester sửa hoặc lấy lại control** | Tester mở nguồn, đối chiếu với highlight gốc rồi sửa lại wording trong bản review. Tester bỏ qua một mục được cho là chưa cần ôn.                                 |
| **Option được chọn**                     | B                                                                                                                                                                 |
| **Lý do và trade-off**                   | Tester nhận thấy bản review giúp tiết kiệm thời gian tổng hợp và dễ nhìn hơn các highlight rời rạc. Đổi lại, tester phải kiểm tra AI có diễn giải đúng hay không. |
| **Evidence chống lại kỳ vọng của nhóm**  | Tester không xác nhận toàn bộ bản review chỉ vì nội dung được trình bày rõ. Source và khả năng chỉnh sửa vẫn cần thiết để tester tin tưởng kết quả AI.            |

## 3. OBSERVED
### Tester đã làm hoặc nói gì?

* Tester đọc phần tóm tắt trước khi mở tài liệu gốc.
* Tester tập trung vào `Key ideas` và `Don't understand` nhiều hơn thông tin thời gian tạo highlight.
* Khi gặp nội dung chưa chắc chắn, tester mở source thay vì chấp nhận trực tiếp bản AI.
* Tester chỉnh sửa một ý và bỏ qua nội dung chưa cần thiết.
* Tester không xác nhận toàn bộ bản review ngay trong lần đầu đọc.

### Trích dẫn hoặc evidence quan trọng

* Tester từng nói rằng đôi khi không nhớ highlight được tạo vì nội dung quan trọng hay vì chưa hiểu.
* Tester phải đọc lại context để khôi phục ý nghĩa của highlight.
* Việc tester đối chiếu nguồn cho thấy bản AI chưa được xem là evidence cuối cùng.
* Hành động chỉnh sửa cho thấy tester muốn giữ quyền quyết định đối với note cá nhân.

## 4. INTERPRETED

### Nhóm nghĩ điều đó có thể có nghĩa gì?

* Bản review có cấu trúc có thể giảm công sức tổng hợp các highlight rời rạc.
* Việc tester mở nguồn trước khi xác nhận có thể cho thấy độ tin cậy và khả năng truy xuất source quan trọng hơn độ ngắn của bản tóm tắt.
* Các nhóm `Key ideas`, `Questions`, `Don't understand` có thể giúp tester nhớ lại mục đích của từng highlight.
* Khả năng sửa và bỏ qua có thể làm tester cảm thấy AI hỗ trợ thay vì kiểm soát nội dung.

### Điều không nên kết luận vội

* Tester đọc nhanh bản review không chứng minh họ đã hiểu nội dung.
* Tester sửa một mục không có nghĩa AI thường xuyên tạo nội dung sai.
* Không thể kết luận Option B tiết kiệm thời gian nếu chưa đo thời gian so với cách review hiện tại.
* Việc tester thích cấu trúc không chứng minh họ sẽ quay lại sử dụng bản review sau này.
* Chưa biết tester có muốn AI tự động tạo review sau mỗi bài học hay chỉ tạo khi được yêu cầu.

## 5. DECIDED — NEXT CHANGE

### Quyết định sau phiên test

* **Quyết định:** Giữ Option B nhưng tăng khả năng kiểm tra và chỉnh sửa.
* **Lý do:** Tester sử dụng được bản review và nhận thấy nội dung dễ theo dõi, nhưng chưa tin tưởng hoàn toàn nếu thiếu source.
* **Người phụ trách thay đổi:** Thành viên phụ trách Option B
* **Trạng thái:** Chưa làm

### Chọn hướng Next Change phù hợp

* [ ] Giữ một option và sửa interaction.
* [x] Kết hợp hai options nhưng giữ một cơ chế chính rõ ràng.
* [ ] Bỏ một option vì tester không hiểu hoặc option không tạo khác biệt.
* [ ] Sửa cả ba rồi test người tiếp theo.

### Thay đổi cụ thể
Kết hợp cơ chế bản review của Option B với khả năng xem context rõ ràng của Option A:

* Mỗi ý AI tạo phải có nút `Xem nguồn`.
* Khi mở source, highlight liên quan được làm nổi bật.
* Cho phép sửa, xóa hoặc chuyển mục giữa `Key ideas`, `Questions`, `Don't understand` và `To review`.
* Thêm nhãn `AI đề xuất` cho nội dung chưa được user xác nhận.
* Chỉ chuyển sang trạng thái `Đã xác nhận` khi tester chủ động chọn.
* Không tự động thay thế note gốc của user bằng nội dung AI.

### Điều sẽ test lại

Quan sát xem tester có hiểu nội dung nào do AI tạo, có kiểm tra source trước khi xác nhận và có sử dụng chức năng chỉnh sửa để biến bản review thành note của mình hay không.

## 6. STILL UNPROVEN

* Chưa biết bản review AI có thực sự giảm thời gian ôn tập.
* Chưa biết các nhóm nội dung do AI tạo có phù hợp với cách học của nhiều người.
* Chưa biết tester có thường xuyên kiểm tra source hay sẽ dần tin AI mà bỏ qua bước này.
* Chưa biết AI có xác định đúng nội dung `Chưa hiểu` từ highlight và note.
* Chưa biết việc chỉnh sửa bản review có tạo thêm công việc tương đương việc tự ghi note.
* Chưa biết Option B có giúp nhớ lâu hơn hay chỉ giúp nội dung dễ đọc hơn.

## 7. Tóm tắt một câu

Tester đọc bản review AI để nắm nhanh nội dung nhưng vẫn mở source và chỉnh sửa trước khi xác nhận, điều này có thể cho thấy Option B giúp giảm công sức tổng hợp nhưng cần khả năng kiểm chứng mạnh, vì vậy nhóm sẽ kết hợp bản review với source và control rõ ràng, nhưng vẫn chưa biết lợi ích tiết kiệm thời gian có lớn hơn công sức kiểm tra AI hay không.
