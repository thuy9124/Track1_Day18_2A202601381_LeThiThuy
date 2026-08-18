# Three Option Design Sheet

## 1. Hypothesis Problem

Khi người học muốn quay lại nội dung đã lưu để ôn thi hoặc làm bài tập, người học gặp khó khăn trong việc tìm và hiểu lại phần kiến thức cần xem vì note dài, nằm rải rác ở nhiều page và đôi khi thiếu context, dẫn đến mất thêm thời gian, phải mở lại tài liệu gốc hoặc bỏ qua việc review.

## 2. Những thứ giữ nguyên cho A/B/C

| Thành phần | Quyết định chung |
|---|---|
| Target user | Người học thường lưu note/highlight khi học online |
| Situation | Người học muốn quay lại nội dung đã lưu để ôn thi hoặc làm bài tập |
| Task | Tìm, hiểu lại và xác định phần kiến thức cần review |
| Desired outcome | Review đúng phần quan trọng với ít thời gian và công sức hơn |
| Content/data fixture | Bài học Marketing trên VLearn về STP Marketing, gồm highlight về Segmentation và Targeting cùng note cá nhân của learner |

## 3. Ba Solution Options

### Option A - User-led Review Hub

- Solution mechanism: Tập hợp highlight/note theo bài học, thời gian và tag do user chọn.
- User làm gì: Mở Review Hub, lọc nội dung, chọn note và mở context gốc.
- AI làm gì: Không sử dụng AI; hệ thống chỉ sắp xếp và truy xuất nội dung.
- Trigger: User chủ động mở Review khi cần.
- Trade-off chính: Dễ kiểm soát và ít suy diễn, nhưng user vẫn phải tự đọc và quyết định.
- Human-AI decision: Don’t Act. Hệ thống không tự diễn giải hoặc tự bắt đầu review.
- Prototype: [Common Context](common-context.html) và [Option A - Review Hub](option-a-review-hub.html)

### Option B - AI Review Note

- Solution mechanism: AI biến highlight/note thành bản review có cấu trúc gồm Key ideas, Questions, Don’t understand và To review.
- User làm gì: Xem bản AI tổng hợp, mở nguồn, chỉnh sửa, bỏ qua hoặc xác nhận.
- AI làm gì: Tóm tắt, nhóm ý và chỉ ra phần có thể thiếu context.
- Trigger: User chọn `Tạo bản review bằng AI` từ một bài hoặc nhóm highlight.
- Trade-off chính: Giảm công sức tổ chức, nhưng có rủi ro AI hiểu sai hoặc làm mất context.
- Human-AI decision: Ask/Act có kiểm soát. AI tạo bản nháp sau khi user yêu cầu; user phải preview và xác nhận.
- Prototype: [Option B - AI Review Note](option-b-ai-review-note.html)

### Option C - AI Practice Prompt

- Solution mechanism: AI tạo câu hỏi ôn tập và điểm cần xem lại từ nội dung user đã đánh dấu.
- User làm gì: Trả lời câu hỏi, đánh dấu phần chưa chắc và mở lại context khi cần.
- AI làm gì: Sinh câu hỏi, đưa gợi ý và liên kết về nội dung nguồn.
- Trigger: User bắt đầu phiên ôn tập hoặc nhận lời mời review sau khi học.
- Trade-off chính: Tăng khả năng chủ động ôn tập, nhưng có thể gây áp lực hoặc tạo câu hỏi không đúng nhu cầu.
- Human-AI decision: Ask trước khi bắt đầu và Act trong phạm vi câu hỏi đã được user chấp nhận.
- Prototype: [Option C - AI Practice Prompt](option-c-ai-practice-prompt.html)

## 4. Distance check

- A khác B vì A chỉ giúp user tập hợp và truy cập lại note/highlight, còn B dùng AI để diễn giải và cấu trúc lại nội dung.
- B khác C vì B tạo một bản review để user đọc và chỉnh sửa, còn C biến nội dung đã đánh dấu thành hoạt động hỏi - đáp để user tự kiểm tra.
- A khác C vì A do user chủ động khởi tạo và kiểm soát việc review, còn C dùng AI để chủ động kích hoạt hoặc dẫn dắt phiên ôn tập.

## 5. Human-AI Design decisions

| Human-AI decision | Option A | Option B | Option C |
|---|---|---|---|
| User làm gì? AI làm gì? | User lọc, chọn note và xem context. Hệ thống truy xuất nội dung. | User xem, sửa và xác nhận. AI tóm tắt và nhóm ý. | User trả lời, xem gợi ý và đánh dấu mức độ chắc chắn. AI tạo câu hỏi và liên kết nguồn. |
| AI Act / Ask / Don’t Act? | Don’t Act vì không dùng AI. | Ask trước khi tạo bản review; không tự lưu nếu user chưa xác nhận. | Ask trước khi bắt đầu; chỉ đưa câu hỏi trong nội dung user đã chọn. |
| Capability/limit | Hệ thống không tự giải thích hoặc đánh giá kiến thức. | AI chỉ dựa trên highlight/note đã chọn và có thể thiếu context. | Câu hỏi có thể chưa phù hợp với mục tiêu học; user có thể bỏ qua. |
| Evidence/uncertainty | Giữ nguyên nguồn, tiêu đề bài học và vị trí highlight. | Hiển thị nguồn và nói rõ khi chưa đủ context. | Hiển thị đoạn nguồn dùng để tạo câu hỏi và đáp án tham khảo. |
| Control/recovery | User preview, mở context gốc, đánh dấu đã review hoặc để review sau. | User sửa, xóa, bỏ qua hoặc quay về nội dung gốc. | User xem gợi ý, bỏ qua, mở nguồn, đánh dấu cần xem lại hoặc kết thúc phiên. |

## 6. Vẫn chưa được chứng minh

- Việc tìm note khó có phải nguyên nhân chính khiến user bỏ qua review hay không.
- User có chủ động dùng giải pháp AI cho vấn đề này hay không.
- AI Review Note có giúp tiết kiệm thời gian mà vẫn giữ đủ context hay không.
- AI Practice Prompt có giúp user review thường xuyên hơn hay chỉ tạo thêm áp lực.
- Các hành vi này có phổ biến ở nhiều người học khác hay chỉ đúng với nhóm người đã phỏng vấn.
