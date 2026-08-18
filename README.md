# Track1 Day18 - MHV Họ và Tên

## 1. Thông tin cá nhân và nhóm

- MHV: `2A202601381`
- Họ và tên: `Lê Thị Thuý`
- Tên nhóm: `3duck`
- Thành viên:
  - `Lê Thị Thuý`
  - `Trần Thị Kiều Oanh`
  - `Giang Minh Phú`
- Case: Người học online lưu highlight và note trong bài học Marketing trên VLearn, sau đó muốn quay lại để ôn thi hoặc làm bài tập.

## 2. Hypothesis Problem

Khi người học muốn quay lại nội dung đã lưu để ôn thi hoặc làm bài tập, người học gặp khó khăn trong việc tìm và hiểu lại phần kiến thức cần xem vì note dài, nằm rải rác ở nhiều page và đôi khi thiếu context, dẫn đến mất thêm thời gian, phải mở lại tài liệu gốc hoặc bỏ qua việc review.

Evidence ban đầu cho thấy người học copy nội dung từ slide sang Notion, thêm giải thích cá nhân, sau đó phải mở nhiều page và scroll để tìm lại. Một người phải mở lại slide gốc để lấy context; nhu cầu review đã xuất hiện khi người học quay lại note để làm bài tập.

Vẫn chưa chứng minh được việc tìm và hiểu lại note là nguyên nhân chính khiến người học không review. Việc bỏ qua review có thể đến từ thiếu thời gian, quên hoặc ưu tiên học phần khác.

## 3. Ba solution hypotheses

Cả ba option cùng giải quyết task tìm, hiểu lại và review nội dung đã lưu. Common Context và content fixture được giữ nguyên: bài học `STP Marketing`, highlight về `Segmentation` và `Targeting`, cùng note cá nhân của learner.

| Thành phần | Option A — Review Hub | Option B — AI Review Note | Option C — AI Practice Prompt |
| --- | --- | --- | --- |
| **Solution mechanism** | Tập hợp highlight/note theo bài, thời gian và tag do user chọn | AI biến highlight/note thành bản review có cấu trúc: Key ideas, Questions, Don't understand, To review | AI tạo câu hỏi ôn tập và điểm cần xem lại từ nội dung user đã đánh dấu |
| **User làm gì?** | Mở trang Review, lọc nội dung và tự chọn phần cần xem | Xem bản AI tổng hợp, chỉnh sửa hoặc xác nhận nội dung | Trả lời câu hỏi, đánh dấu phần chưa chắc và mở lại context khi cần |
| **AI làm gì?** | Không sử dụng AI; chỉ sắp xếp và truy xuất nội dung | Tóm tắt, nhóm ý và chỉ ra phần có thể thiếu context | Sinh câu hỏi, phát hiện phần user trả lời chưa chắc và gợi ý nội dung liên quan |

### Option A - Review Hub

- Prototype: [Common Context](common-context.html)
- Prototype: [Option A - Review Hub](option-a-review-hub.html)

### Option B - AI Review Note

- Prototype: [Option B - AI Review Note](option-b-ai-review-note.html)

### Option C - AI Practice Prompt

- Prototype: [Option C - AI Practice Prompt](option-c-ai-practice-prompt.html)

## 4. Đóng góp của tôi trong nhóm

- Xây dựng Common Context cho cả ba option, gồm bài học STP Marketing, highlight, note cá nhân, tag và content fixture dùng chung.
- Xây dựng Option A - Review Hub với flow `Review Hub -> Result / User Decision`.
- Tạo các control cho Option A: lọc theo bài học, tag và thời gian; xem note; mở context gốc; đánh dấu đã review; để review sau; quay lại context.
- Góp phần chốt Human-AI decisions: Option A không dùng AI; user chủ động chọn và quyết định, hệ thống chỉ tập hợp và truy xuất nội dung.

## 5. Prototype Feedback

### Observation từ phiên tôi facilitate

- `[Tester có tự tìm được note hay không?]`
- `[Tester có cần mở lại context gốc không?]`
- `[Tester có hiểu các filter và nút hành động không?]`
- `[Tester gặp điểm dừng hoặc nhầm lẫn nào?]`

### Ba-feedback synthesis

1. `[Feedback 1 - observation cụ thể từ người test]`
2. `[Feedback 2 - observation cụ thể từ người test]`
3. `[Feedback 3 - observation cụ thể từ người test]`

### Next Change

`[Thay đổi tiếp theo dự kiến: ví dụ làm rõ tag, rút gọn danh sách note, hoặc đưa nút Mở context gốc ra gần hơn.]`

### Still Unproven

`[Chưa chứng minh được người học có thực sự review nhiều hơn khi note dễ tìm hơn hay không; vẫn có thể bỏ qua vì thiếu thời gian, quên hoặc ưu tiên việc khác.]`

## 6. AI Support Log

### AI đã giúp gì

- Hỗ trợ cấu trúc hóa evidence, Hypothesis Problem và ba solution hypotheses.
- Gợi ý cách tách ba option theo mức độ user-led, co-create và AI-led.
- Hỗ trợ tạo prototype HTML cho Common Context, Option A, Option B và Option C để nhóm có thể thao tác và test.

### AI sai hoặc hời hợt ở đâu

- Một số tên option trong Human-AI Decision Table ban đầu không khớp với ba Solution Options đã chốt.

### Tôi tự kiểm tra và sửa gì

- Đối chiếu lại tên và cơ chế của A/B/C để tránh thay đổi solution giữa các chặng.
