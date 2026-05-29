# Phase 7 — Reflection cá nhân + Bảng chia việc nhóm

### Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Đưa ra 3 problems về giáo dục: học sinh thiếu định hướng, nhanh quên kiến thức, thiếu kết nối nghề | Đóng góp 3 ứng viên vào pool 12 problems |
| Pitch Problem Card | Pitch case "Học sinh thiếu định hướng" — ảnh hưởng số lượng lớn | Nhóm thảo luận sôi nổi về khả năng AI hiểu mục tiêu cá nhân |
| Challenge bài của bạn khác | Challenge An về "tối ưu FPS" — phần cứng giới hạn bao nhiêu %, software tối ưu thêm được không | An thừa nhận khó biết giới hạn cứng |
| Gom trùng / cluster | Giúp gom cluster "hướng dẫn ban đầu" — onboarding nhân viên mới và học sinh mới | Nhóm thấy pattern "người mới thiếu hướng dẫn" ở nhiều domain |
| Chọn candidate problem | Ủng hộ chọn "Tài liệu chất lượng thấp" — case của Hiếu có workflow rõ hơn, đo được | |
| Validation / research | Chia sẻ experience: "tài liệu học thiếu tiêu chí đánh giá" — tương tự tài liệu yêu cầu thiếu tiêu chí nghiệm thu | Nhóm thấy pattern "thiếu tiêu chí" ở cả giáo dục và phần mềm |
| Workflow nhóm | Đề xuất phương án dự phòng — "nhân viên có quyền từ chối gợi ý AI nếu thấy sai" | Nhóm thêm vào workflow: "Nhân viên từ chối → không bắt buộc" |
| Problem Statement | Đề xuất thêm "AI không viết tài liệu thay nhân viên" vào field Giới hạn | Nhóm đồng ý, thêm vào cả v0 và v1 |
| Rule / Workflow / Agent | Phân tích case giáo dục — problem "thiếu định hướng" có thể cần Agent (độ mơ hồ cao × phức tạp cao) | Giúp ma trận R/W/A có ví dụ thực tế cho ô cao-cao |
| Decision | Đồng ý Go, đề xuất "đào tạo lại nhân viên về cách dùng AI" nếu phụ thuộc quá | Nhóm thêm vào điều kiện dừng |

### Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi AI gợi ý problems từ bối cảnh giáo dục | AI gợi ý "theo dõi tiến độ học tập" — không phải pain tôi thấy | | Tôi bỏ, giữ lại problems từ trải nghiệm dạy học thật |
| Problem Card | Dùng AI phản biện card "học sinh thiếu định hướng" | AI chỉ ra: AI không hiểu thị trường lao động | AI gợi ý dùng survey phụ huynh — không giải quyết được gốc | Tôi thêm giả định "AI cần dữ liệu thị trường lao động thực tế" |
| Workflow | Không dùng | | | |
| Research | Hỏi AI về adaptive learning systems | AI liệt kê Khan Academy, Duolingo | AI không giải thích cơ chế bên trong | Tôi tự research thêm về spaced repetition |
| Problem Statement | Không dùng | | | |
| Rule / Workflow / Agent | Hỏi AI phân loại case giáo dục | AI xếp vào ô "độ mơ hồ cao × độ phức tạp cao" → có thể cần Agent | Tôi đồng ý nhưng thấy cần boundary rất rõ | |
| Decision | Không dùng | | | |

---

## Reflection (câu hỏi mở)

### Tôi học được gì khi nghe top 3 problems của các bạn khác?

Tôi học được cách “đóng khung pain” bằng **workflow + metric + tần suất lặp**. Ví dụ như case tài liệu BA của Hiếu: chỉ cần nêu được **2–3 vòng TL reject**, **3–5 lần dev hỏi lại**, và **% làm lại** là cả nhóm nhìn thấy chi phí thật và đo được khi pilot.

### Nhóm có lúc nào bị solution-first không?

Có. Có lúc nhóm nhắc “dùng ChatGPT kiểm tài liệu / chatbot” trước khi khóa rõ **bước nghẽn** trong workflow. Sau đó nhóm kéo lại bằng cách chốt phạm vi AI là **một bước kiểm** (sau BA viết, trước TL), không để AI “viết thay”.

### Tôi có thay đổi ý kiến sau khi bị challenge không?

Có. Ban đầu tôi nghiêng về framing “học nhiều môn”; sau khi bị challenge, tôi chốt lại gốc là **thiếu định hướng dài hạn + thiếu thực hành**, và đồng ý nhóm chọn bài BA vì **pilot đo được nhanh** hơn trong lab.

### Tôi đóng góp gì thật sự vào artifact cuối?

- Đưa 3 candidate problems về giáo dục vào pool và pitch 1 case để nhóm so sánh.
- Góp challenge theo hướng **đòi metric/điểm đo** và nhắc nhóm tránh solution-first.
- Đề xuất **boundary quan trọng**: “AI không viết tài liệu thay nhân viên/BA”, và cơ chế “người dùng có quyền từ chối gợi ý AI”.

### Điều khó nhất khi viết Problem Statement là gì?

Khó nhất là viết sao cho **đúng problem (pain)** mà không trượt sang “giải pháp AI”, đồng thời gắn được metric mơ hồ (chất lượng tài liệu) thành metric **hành vi đo được** (số vòng reject, số lần hỏi lại, % reopen/làm lại).

### Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

- Yêu cầu bóc rõ pain xảy ra **mỗi chu kỳ** hay chỉ thỉnh thoảng (để tránh chọn “edge case”).
- Đòi nêu “nút thắt” tốn thời gian nhất nằm ở đâu: TL reject hay dev Q&A hay họp.
- Ép kiểm tra “**không dùng AI** thì có cải thiện được không?” để chắc đây là problem thật, không phải “AI-washing”.
- Nếu baseline chưa có số liệu, bắt cam kết đo **2 chu kỳ** trước khi kết luận Go/No-go.
