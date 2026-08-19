# Group Feedback Synthesis

> Hoàn thành sau khi nhóm có đủ ba bản Prototype Feedback Note từ ba thành viên. Chỉ tổng hợp evidence đã ghi nhận; tách pattern khỏi diễn giải.

## 1. Thông tin tổng hợp

* **Người tổng hợp:** Nhóm 3duck
* **Ngày tổng hợp:** 19/08/2026
* **Tester 1 / Option:** Trần Xuân Bách / Option A — User-led Review Hub
* **Tester 2 / Option:** Lê Thị Linh / Option B — AI Review Note
* **Tester 3 / Option:** Nguyễn Thị Tuyết Mai / Option C — AI Practice Prompt

## 2. Bảng so sánh ba feedback

| Nội dung                 | Feedback 1 — Option A                                                                         | Feedback 2 — Option B                                                                                        | Feedback 3 — Option C                                                                         | Pattern hoặc khác biệt                                                                                                                                                                                                           |
| ------------------------ | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **First action**         | Tester nhìn danh sách highlight và mở một nội dung để xem lại. Không dùng filter ngay từ đầu. | Tester đọc phần `Key ideas` trong bản AI Review trước, sau đó mới xem các nhóm nội dung khác.                | Tester đọc câu hỏi và thử tự suy nghĩ câu trả lời trước khi mở hint.                          | Cả ba trường hợp tester đều đi thẳng vào **nội dung chính** trước, thay vì sử dụng các chức năng phụ. A thiên về đọc lại, B thiên về xem tổng hợp, C thiên về recall.                                                            |
| **Breakdown chính**      | Tester do dự với filter và chưa rõ `Đã review` có nghĩa là đã đọc hay đã hiểu.                | Tester dừng ở một ý AI viết vì chưa chắc ý đó có đúng với highlight gốc hay không. Không muốn xác nhận ngay. | Tester chưa rõ câu hỏi được tạo từ highlight nào và chưa biết bước tiếp theo sau khi trả lời. | Friction chung là **thiếu context hoặc trạng thái chưa đủ rõ**. A gặp vấn đề về trạng thái review; B và C gặp vấn đề về sự liên kết giữa AI output và source gốc.                                                                |
| **Cách lấy lại control** | Tester mở context gốc, đọc phần trước/sau highlight rồi chọn `Review sau`.                    | Tester mở source, đối chiếu với highlight gốc, sửa wording hoặc bỏ một mục AI tạo.                           | Tester mở hint/context, kiểm tra lại rồi tự chọn `Đã hiểu` hoặc `Cần xem lại`.                | Cả ba đều dùng **source/context gốc để lấy lại control**. Tester không hoàn toàn dựa vào nội dung đã được hệ thống/AI xử lý.                                                                                                     |
| **Option được chọn**     | A                                                                                             | B                                                                                                            | C                                                                                             | Mỗi feedback test một option khác nhau nên chưa có evidence đủ mạnh để nói option nào được chọn nhiều hơn. Tuy nhiên, ba option thể hiện ba nhu cầu khác nhau: control, efficiency và active recall.                             |
| **Trade-off**            | Tester giữ quyền kiểm soát và tin nguồn gốc hơn, nhưng vẫn phải tự tìm và tự đọc nhiều.       | Tester tiết kiệm công tổng hợp, nhưng phải kiểm tra và chỉnh nội dung AI.                                    | Tester phải chủ động nhớ lại kiến thức, nhưng mất nhiều effort và thời gian hơn đọc review.   | Trade-off chung là **automation càng nhiều thì tester càng cần khả năng kiểm tra và lấy lại control**. A ít automation nhưng nhiều effort; B giảm effort nhưng có trust cost; C tăng learning effort nhưng có thể hỗ trợ recall. |

## 3. Pattern và khác biệt

### Pattern lặp lại

* **Source/context gốc quan trọng ở cả ba feedback.** Khi tester không chắc về nội dung, hành động recovery phổ biến là mở lại highlight hoặc context gốc để kiểm tra.
* Tester không muốn hệ thống hoặc AI tự quyết định thay hoàn toàn. Ở Option A, tester tự chọn trạng thái review; ở Option B, tester muốn sửa hoặc bỏ nội dung AI; ở Option C, tester tự xác nhận `Đã hiểu` hoặc `Cần xem lại`.

* Các chức năng chính được ưu tiên hơn chức năng phụ. Tester tập trung vào highlight ở A, `Key ideas` ở B và câu hỏi ở C; filter, metadata hoặc hint không phải first action.

* Trạng thái và bước tiếp theo cần rõ ràng hơn. `Đã review`, `Đã hiểu`, `Cần xem lại`, `Xác nhận` hoặc hành động sau khi trả lời đều có khả năng gây do dự nếu không có giải thích.

* Tester có xu hướng dùng AI như **công cụ hỗ trợ xử lý nội dung**, không phải nguồn cuối cùng thay thế tài liệu gốc.

### Khác biệt hoặc bất ngờ

* **Option A:** Tester không ưu tiên tag và filter như nhóm có thể kỳ vọng. Tester quan tâm tới việc mở lại đúng context hơn việc có nhiều cách phân loại highlight.

* **Option B:** Bản AI Review có thể giúp đọc nhanh hơn, nhưng tester không tự động tin nội dung chỉ vì nó được trình bày rõ ràng. Tester vẫn cần kiểm tra source.

* **Option C:** Tester không mở hint ngay mà thử tự trả lời trước. Điều này khác với kỳ vọng rằng user có thể sử dụng hint như một shortcut ngay từ đầu.

* Option C yêu cầu effort lớn hơn A và B. Điều này có thể là lợi thế khi mục tiêu là active recall nhưng cũng có thể trở thành friction khi người học chỉ có ít thời gian.

* Option A ít phụ thuộc AI nhất nhưng vẫn chưa giải quyết hoàn toàn việc người học quên lý do đã highlight.

* Option B và C tạo thêm giá trị từ AI theo hai cách khác nhau: B giảm công tổng hợp, còn C tạo hoạt động ôn tập chủ động. Hiện tại chưa có evidence cho thấy cách nào phù hợp hơn trong thực tế.

## 4. Một Next Change nhóm chốt

**Kết hợp Option B và Option C thành một flow review thống nhất, trong đó bản AI Review Note là màn hình chính và `Practice` là hành động tùy chọn; đồng thời mỗi nội dung AI tạo luôn có `Xem nguồn` để tester có thể quay lại highlight/context gốc giống cơ chế của Option A.**

Flow đề xuất:

`Saved Highlight/Note → AI Review Note → Xem nguồn / Chỉnh sửa → Practice nếu muốn → Đã hiểu / Cần xem lại`

Trong đó:

* AI Review Note giúp user xem nhanh nội dung đã lưu.
* Mỗi `Key idea`, `Question` hoặc nội dung AI tạo đều có source tương ứng.
* User có quyền sửa, bỏ hoặc xác nhận nội dung AI.
* `Practice` không bắt buộc; user chủ động chọn khi muốn active recall.
* Hint chỉ hiển thị khi user yêu cầu.
* `Đã hiểu` và `Cần xem lại` do user tự xác nhận.
* AI không tự kết luận mức độ hiểu của learner.

### Loại thay đổi

* [ ] Giữ một option và sửa interaction.
* [x] Kết hợp hai options nhưng giữ một cơ chế chính rõ ràng.
* [ ] Bỏ một option vì tester không hiểu hoặc option không tạo khác biệt.
* [ ] Sửa cả ba rồi test người tiếp theo.

## 5. Evidence nào dẫn tới quyết định này?

* **Evidence từ Feedback 1 — Option A:** Tester ưu tiên mở context gốc để nhớ lại lý do highlight và không sử dụng filter ngay từ đầu. Điều này cho thấy khả năng truy xuất nguồn quan trọng hơn việc thêm nhiều cơ chế tổ chức.

* **Evidence từ Feedback 2 — Option B:** Tester đọc bản AI Review trước nhưng khi gặp nội dung chưa chắc chắn thì mở source, đối chiếu với highlight và chỉnh lại nội dung thay vì xác nhận ngay. Điều này cho thấy AI summary có thể hữu ích nhưng phải đi kèm transparency và user control.

* **Evidence từ Feedback 3 — Option C:** Tester thử tự trả lời trước khi xem hint nhưng vẫn cần mở context để kiểm tra khi không chắc chắn. Điều này cho thấy practice có thể hỗ trợ recall nhưng nên là lựa chọn chủ động, không phải flow bắt buộc cho mọi lần review.

* **Evidence chung:** Cả ba feedback đều có hành vi quay lại context/source khi tester mất chắc chắn hoặc cần lấy lại control.

* **Evidence chung:** Tester không thể hiện nhu cầu để AI tự quyết định trạng thái cuối cùng. Hành động xác nhận, chỉnh sửa, review hoặc đánh dấu mức độ hiểu vẫn cần thuộc về learner.

## 6. Still Unproven sau ba feedback

Dù ba feedback cho thấy source transparency và user control xuất hiện lặp lại, nhóm vẫn chưa thể kết luận rằng solution mới sẽ làm người học review thường xuyên hơn hoặc cải thiện kết quả học tập.

* Chưa biết pattern mở source/context có lặp lại ở nhiều người học hơn hay không.

* Chưa biết user sẽ sử dụng bản AI Review thường xuyên hay chỉ dùng khi cần ôn thi hoặc làm bài tập.

* Chưa biết việc tổ chức highlight tốt hơn có làm user review thường xuyên hơn hay chỉ giúp tìm nội dung nhanh hơn.

* Chưa biết AI Review Note có tiết kiệm đủ thời gian để bù cho công sức kiểm tra và chỉnh sửa output của AI.

* Chưa biết AI Practice Prompt có cải thiện khả năng nhớ kiến thức hay chỉ làm quá trình review mất thêm thời gian.

* Chưa biết người học có chủ động chọn `Practice` khi tính năng này không bắt buộc hay không.
* Chưa biết số lượng câu hỏi và độ dài một phiên practice bao nhiêu là phù hợp.

* Chưa biết AI có tạo được câu hỏi đúng trọng tâm, đúng source và đúng độ khó một cách ổn định hay không.

* Chưa biết người học có tiếp tục sử dụng Notion hoặc công cụ khác dù hệ thống đã có AI Review Note.

* Chưa biết AI có tạo giá trị lớn hơn cách tổ chức note hoàn toàn user-led của Option A hay không.

* Chưa thể kết luận Option B + C tốt hơn từng option riêng lẻ nếu chưa test prototype kết hợp với tester mới.

### Giả thuyết cần test tiếp

**Nếu learner được xem một bản review AI có source rõ ràng và chỉ chuyển sang practice khi chủ động lựa chọn, họ có thể xử lý lại highlight nhanh hơn mà vẫn giữ quyền kiểm soát và không cảm thấy AI tạo thêm quá nhiều effort.**

Ở tester tiếp theo, nhóm cần quan sát:

1. User có mở source khi đọc AI Review hay không.
2. User có sửa hoặc bỏ nội dung AI hay không.
3. User có chủ động chọn `Practice` hay dừng ở bản review.
4. Nếu chọn Practice, user có thử trả lời trước khi xem hint hay không.
5. User có hiểu rõ `Đã hiểu` và `Cần xem lại` hay không.
6. Tổng flow có nhanh và dễ hiểu hơn ba option tách riêng hay không.

## 7. Kết luận ngắn của nhóm

**Sau ba feedback, nhóm nhận thấy pattern chính là tester cần truy cập source/context gốc và giữ quyền kiểm soát khi review nội dung, bất kể prototype là user-led hay AI-assisted. Nhóm sẽ kết hợp Option B và C thành một flow trong đó AI Review Note là cơ chế chính, Practice là lựa chọn chủ động và source luôn có thể kiểm tra, dựa trên việc tester ở cả ba feedback đều quay lại context khi chưa chắc chắn. Tuy nhiên, nhóm vẫn chưa thể kết luận solution này sẽ khiến người học review thường xuyên hơn, cải thiện khả năng ghi nhớ hoặc tạo giá trị lớn hơn cách tổ chức note user-led.**
