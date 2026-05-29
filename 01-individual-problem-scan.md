# 01 — Individual Problem Scan

| #   | Lăng kính          | Problem quan sát được                                                           | Ai đang đau?                                                       | Dấu hiệu thật                                                               |
| --- | ------------------ | ------------------------------------------------------------------------------- | ------------------------------------------------------------------ | --------------------------------------------------------------------------- |
| 1   | Tốn thời gian      | Các đội khác chuyên môn không hiểu thuật ngữ nên mất thời gian làm rõ trong họp | Software engineers, Product managers, Business analysts, Designers | mất thêm 30–60 phút mỗi buổi họp bị dùng để giải thích thuật ngữ            |
| 2   | Lặp lại            | Cuộc họp quốc tế bị chậm vì giọng, từ lóng, accent khác nhau                    | Remote workers                                                     | Mỗi buổi họp phải lặp lại nội dung 2–3 lần                                  |
| 3   | Tốn thời gian      | Học sinh học nhiều lý thuyết nhưng ít áp dụng thực hành                         | High school students (Vietnam public schools)                      | 70–80% kiến thức bị quên sau 1–2 tuần kiểm tra                              |
| 4   | Pain từ người khác | Các bạn đi làm giỏi chuyên môn nhưng yếu giao tiếp                              | Employees                                                          | Không được giao task có độ phức tạp cao hơn sau nhiều sprint                |
| 5   | Tốn thời gian      | Người dùng phải đọc nhiều nguồn để hiểu một vấn đề                              | Data analysts, researchers, knowledge workers                      | 1–3 giờ để tổng hợp 1 vấn đề đơn giản                                       |
| 6   | Lặp lại            | Task phải qua nhiều bước phê duyệt không cần thiết                              | Product teams, project managers                                    | tốn trung bình 1 tuần để chờ approval                                       |
| 7   | Tốn thời gian      | Brief không rõ dẫn đến làm sai sản phẩm                                         | UI/UX designers, software developers                               | 30–50% task phải làm lại                                                    |
| 8   | Pain từ người khác | Người học không biết nên học gì cho tương lai                                   | High school & university students                                  | 60–70% học sinh chọn sai hướng học hoặc kỹ năng không liên quan nghề nghiệp |
| 9   | Pain từ người khác | Người làm không nhận feedback kịp thời                                          | Interns, junior developers                                         | Feedback bị delay 3–7 ngày, dẫn đến 2–3 lần lặp lỗi                         |
| 10  | Tốn thời gian      | Người học không kết nối được kiến thức giữa các môn                             | High school students                                               | Phải học lại từ đầu khi làm bài tổng hợp                                    |

# Top 3

| Rank | Problem                                            | Vì sao chọn                                                                                                                                                                     | Điều còn chưa chắc                                                               |
| ---- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| 1    | Communication gap trong cross-team meetings        | Xảy ra thường xuyên trong mọi buổi họp giữa các team (Tech, Business, Design). Mất nhiều thời gian để làm rõ thuật ngữ và ý nghĩa, ảnh hưởng trực tiếp đến tốc độ ra quyết định | Khó đo chính xác mức độ hiểu đúng sau mỗi buổi họp nếu không có feedback rõ ràng |
| 2    | Người dùng phải đọc nhiều nguồn để hiểu một vấn đề | Pain rõ trong workflow research của data/knowledge workers. Mỗi lần phải tổng hợp thông tin từ nhiều nguồn, tốn nhiều thời gian                                                 | Khó đánh giá chất lượng tổng hợp (đủ sâu hay thiếu context)                      |
| 3    | Brief không rõ dẫn đến làm sai sản phẩm            | Xảy ra thường xuyên trong workflow, phải làm lại nhiều vòng và làm chậm thời gian đưa ra sản phẩm                                                                               | Phụ thuộc nhiều vào chất lượng input ban đầu từ stakeholder                      |

# Problem Cards — Top 3

---

# Problem Card #1 — Khoảng cách giao tiếp giữa các team

## Problem 1 câu:

Trong các buổi họp giữa nhiều team (Tech, Business, Design), việc không thống nhất được thuật ngữ và cách diễn đạt khiến mất nhiều thời gian để làm rõ trước khi ra quyết định.

## Actor:

Software engineers, Product managers, Business analysts, Designers.

## Thời điểm / bối cảnh:

Các buổi cross-team meeting (daily sync, planning, review).

---

## Current workflow:

1. Chuẩn bị agenda họp
2. Mỗi team cập nhật tiến độ
3. Dùng thuật ngữ theo chuyên môn riêng
4. Các team khác không hiểu ngay
5. Hỏi lại để làm rõ
6. Giải thích lại cùng một khái niệm theo cách khác
7. Quay lại thảo luận và ra quyết định

---

## Bottleneck:

Bước 4–6: vòng lặp giải thích và hiểu lại giữa các team, làm chậm quá trình ra quyết định.

---

## Impact:

- Mỗi buổi họp mất thêm 30–60 phút để làm rõ ý
- Decision bị chậm
- Dễ hiểu sai requirement hoặc ý tưởng
- Giảm hiệu quả phối hợp giữa các team

---

## Success metric:

Giảm thời gian làm rõ thuật ngữ trong mỗi buổi họp xuống dưới 10–15 phút và giảm số lần phải giải thích lại cùng một khái niệm.

---

## Non-AI alternative:

Tạo glossary nội bộ, tài liệu thuật ngữ chuẩn hóa, pre-read trước meeting. Tuy nhiên khó cập nhật theo ngữ cảnh thực tế trong cuộc họp.

---

## AI hypothesis:

AI hỗ trợ giải thích thuật ngữ theo ngữ cảnh, tóm tắt ý chung giữa các bên và hỗ trợ làm rõ hiểu sai ngay trong cuộc họp.

---

## Quick gut:

Friction trong giao tiếp đa chuyên môn.

---

## CURRENT STATE — ~60–90 phút mỗi meeting

```text
[1 Chuẩn bị agenda: 10']
→ [2 Các team update: 10']
→ [3 Dùng thuật ngữ riêng: 15']
→ [4 Hiểu khác nhau giữa các team: 10']
→ [5 Hỏi lại để làm rõ: 15']
→ [6 Giải thích lại nhiều lần: 10–20']
→ [7 Chốt lại quyết định: 5–10']
```

---

## FUTURE STATE — ~25–35 phút

```text
[1 AI hỗ trợ chuẩn hóa thuật ngữ trước họp: 2']
→ [2 AI giải thích realtime trong họp: 3']
→ [3 Các team hiểu chung context ngay từ đầu: 5']
→ [4 Thảo luận tập trung vào quyết định: 10–15']
→ [5 Chốt quyết định: 5']
```

Fallback: nếu AI giải thích chưa đúng context → người tham gia chỉnh lại trực tiếp trong meeting.

---

# Problem Card #2 — Quá tải thông tin khi research

## Problem 1 câu:

Người dùng phải đọc nhiều nguồn khác nhau để hiểu một vấn đề, dẫn đến tốn nhiều thời gian tổng hợp và dễ bị quá tải thông tin.

## Actor:

Data analysts, researchers, knowledge workers.

## Thời điểm / bối cảnh:

Khi research một chủ đề mới hoặc chuẩn bị tài liệu.

---

## Current workflow:

1. Tìm kiếm Google hoặc internal tools
2. Mở 5–10 nguồn khác nhau
3. Đọc từng tài liệu
4. Tự trích xuất thông tin quan trọng
5. So sánh và tổng hợp
6. Viết summary cuối cùng

---

## Bottleneck:

Bước 3–5: đọc và tổng hợp thông tin từ nhiều nguồn rời rạc, không có cấu trúc thống nhất.

---

## Impact:

- Mất 1–3 giờ cho một vấn đề đơn giản
- Dễ bỏ sót thông tin quan trọng
- Output research không nhất quán giữa các người trong team

---

## Success metric:

Giảm thời gian research xuống dưới 30–45 phút cho một vấn đề tiêu chuẩn, đồng thời tăng độ nhất quán của summary.

---

## Non-AI alternative:

Tạo knowledge base, tài liệu nội bộ chuẩn hóa hoặc summary từ expert. Tuy nhiên khó mở rộng và nhanh lỗi thời.

---

## AI hypothesis:

AI tổng hợp nhiều nguồn, trích xuất insight chính và tạo summary có cấu trúc theo mục tiêu người dùng.

---

## Quick gut:

Workflow tổng hợp thông tin.

---

## CURRENT STATE — ~1–3 giờ

```text
[1 Tìm kiếm thông tin: 10']
→ [2 Mở nhiều nguồn (5–10 tabs): 10']
→ [3 Đọc từng nguồn: 30–60']
→ [4 Ghi chú thủ công: 20']
→ [5 So sánh thông tin giữa các nguồn: 20–30']
→ [6 Viết summary: 10–20']
```

---

## FUTURE STATE — ~30–45 phút

```text
[1 AI thu thập và gợi ý nguồn: 5']
→ [2 AI đọc và trích xuất nội dung chính: 10']
→ [3 AI tổng hợp structured summary: 10']
→ [4 Người dùng review và chỉnh sửa: 10–15']
```

Fallback: nếu AI thiếu context → người dùng quay lại nguồn gốc để verify.

---

# Problem Card #3 — Brief không rõ dẫn đến làm sai sản phẩm

## Problem 1 câu:

Brief không rõ ràng từ đầu khiến team hiểu sai yêu cầu, dẫn đến nhiều vòng sửa lại sản phẩm trước khi đạt đúng kỳ vọng.

## Actor:

UI/UX designers, software developers, product teams.

## Thời điểm / bối cảnh:

Khi nhận task từ PM hoặc stakeholder.

---

## Current workflow:

1. Nhận brief từ PM hoặc stakeholder
2. Tự hiểu requirement
3. Bắt đầu thiết kế / code
4. Review nội bộ hoặc với PM
5. Nhận feedback
6. Sửa lại sản phẩm
7. Lặp lại nhiều vòng đến khi đúng

---

## Bottleneck:

Bước 2–6: hiểu sai requirement ban đầu dẫn đến nhiều vòng rework.

---

## Impact:

- 2–3 vòng chỉnh sửa cho mỗi task
- Delay release feature
- Tăng workload cho cả team
- Giảm tốc độ delivery

---

## Success metric:

Giảm số vòng rework xuống 1 vòng hoặc ít hơn và giảm thời gian clarify trước khi bắt đầu implement.

---

## Non-AI alternative:

Checklist requirement, PRD template chuẩn, kickoff meeting bắt buộc. Tuy nhiên vẫn phụ thuộc vào cách diễn giải của con người.

---

## AI hypothesis:

AI phát hiện ambiguity trong brief, hỏi lại missing context và tạo requirement rõ ràng trước khi team bắt đầu làm.

---

## Quick gut:

Friction trong hiểu requirement.

## CURRENT STATE — ~60–120 phút mỗi task (có thể kéo dài nhiều vòng)

```text
[1 Nhận brief từ PM/stakeholder: 5']
→ [2 Đọc và tự hiểu requirement: 10–20']
→ [3 Hỏi lại nếu chưa rõ: 10–15']
→ [4 Bắt đầu thiết kế / code / implement: 20–40']
→ [5 Review nội bộ hoặc với PM: 10–20']
→ [6 Nhận feedback (thường chưa rõ hoặc thiếu context): 5–10']
→ [7 Sửa lại output: 20–30']
→ [8 Lặp lại bước 5–7: 1–3 vòng]
```

Bottleneck:
Bước 2–7: hiểu sai hoặc thiếu context từ brief ban đầu dẫn đến nhiều vòng rework.

---

## FUTURE STATE — ~25–45 phút mỗi task

```text
[1 Nhận brief: 3']
→ [2 AI kiểm tra độ rõ ràng của requirement: 2']
→ [3 AI hỏi lại các phần thiếu context: 3']
→ [4 PM xác nhận requirement đã rõ: 5']
→ [5 Bắt đầu thiết kế / code với requirement đã chuẩn hóa: 15–25']
→ [6 Review 1 vòng với PM: 5–10']
→ [7 Chốt và release: 2–5']
```

Fallback:
Nếu AI phát hiện brief vẫn ambiguous → quay lại bước 2 để làm rõ trước khi implement.

---
