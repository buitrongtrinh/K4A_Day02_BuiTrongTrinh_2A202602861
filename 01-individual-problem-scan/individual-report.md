# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Bùi Trọng Trịnh
- Mã học viên: 2A202602861
- Vai trò / bối cảnh: Sinh viên tham gia các lab và dự án nhóm
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Nhận, chia nhỏ và theo dõi task trong các buổi học/lab.
  - Tìm tài liệu, quyết định cũ và file mẫu trong chat/Google Drive.
  - Phối hợp với thành viên, tổng hợp tiến độ và review bài nộp.

---

## Phase 0 — Worked Example

Đã đọc `02-deliverable-example.md`. Các điểm rút ra trước khi scan:

- Nhóm chỉ chọn candidate problem sau khi nghe nhiều góc nhìn; chưa vội chọn solution.
- Problem tốt phải có actor, workflow, bottleneck, baseline và impact đo được.
- Workflow tương lai cần chỉ rõ Rule, AI, người review, boundary và fallback.
- Rule hoặc Workflow vẫn là lựa chọn tốt nếu giải quyết được bài toán với rủi ro thấp hơn Agent.

**Self-check Phase 0:**

- [x] Hiểu sự khác nhau giữa candidate problem và Problem Statement.
- [x] Hiểu cần validate, research, vẽ workflow và làm metric trước khi chốt giải pháp.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại + Tốn thời gian | Tổng hợp tiến độ nhóm từ chat, bảng task và file thành một update chung | Người điều phối, cả nhóm | Mất 35–45 phút mỗi tuần; thường phải hỏi lại 2–3 thành viên |
| 2 | Tốn thời gian | Tìm lại quyết định hoặc link tài liệu cũ trong nhiều đoạn chat | Tất cả thành viên | Mỗi lần tìm mất 10–15 phút; xảy ra khoảng 2–3 lần/tuần/người |
| 3 | Pain từ người khác | Thành viên không rõ task cần nộp ở format nào | Thành viên mới, người review | Có 2–3 câu hỏi lặp lại mỗi lần giao bài; dễ thiếu file hoặc mục bắt buộc |
| 4 | Lặp lại | Nhắc deadline nhưng không kèm trạng thái và việc cần làm tiếp theo | Người điều phối, người trễ task | Nhắc 2–3 lần/deadline; một task từng trễ khoảng 1 ngày |
| 5 | AI có thể tốt hơn | Tóm tắt tài liệu dài để tìm phần liên quan đến bài lab | Sinh viên đọc tài liệu | Tài liệu dài 20–40 trang; mất 30–45 phút để tìm phần cần đọc |
| 6 | Tốn thời gian | So sánh nhiều phiên bản bài làm trong Drive trước khi merge | Người review, người viết | Mất 20–30 phút/lần; từng comment nhầm vào bản cũ |
| 7 | Pain từ người khác | Sau họp nhóm, action item không có owner và deadline rõ | Cả nhóm | Bỏ sót khoảng 1–2 việc sau mỗi 2–3 buổi họp |
| 8 | Lặp lại | Chuẩn bị standup/update theo cùng một format | Thành viên nhóm | Mất 5–10 phút/người; lặp lại 2–3 lần/tuần |
| 9 | AI có thể tốt hơn | Gom câu hỏi lặp lại của nhóm thành FAQ có nguồn dẫn | Người học, người hỗ trợ | Một số câu hỏi xuất hiện lại 2–4 lần ở các kênh khác nhau |
| 10 | Tốn thời gian | Kiểm tra checklist bài nộp thủ công trước khi gửi | Người nộp, người review | Mất 15–20 phút/bài; thường phát hiện 1–2 lỗi ngay trước deadline |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: “Tôi là sinh viên làm lab và dự án nhóm, thường dùng chat, Drive và bảng task. Hãy gợi ý thêm problem theo bốn lăng kính; mỗi ý phải có actor, workflow và cách đo, không đề xuất trợ lý AI toàn năng.”
- Ý dùng được: Tìm quyết định cũ, trích action item sau họp và kiểm tra checklist bài nộp.
- Ý bỏ vì không phải pain thật: “AI tự quản lý toàn bộ dự án” và “AI tự chấm điểm bài làm”, vì chưa có bằng chứng nhu cầu và rủi ro quyết định sai cao.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tổng hợp tiến độ nhóm từ chat, bảng task và file thành một update chung | Lặp lại hằng tuần, workflow rõ và có baseline 35–45 phút; impact ảnh hưởng trực tiếp đến deadline | Update cần những field nào để người đọc không phải hỏi lại; input từ chat có đủ không |
| 2 | Tìm lại quyết định hoặc link tài liệu cũ trong nhiều đoạn chat | Nhiều thành viên gặp; bottleneck rõ ở search và xác minh ngữ cảnh; có thể đo thời gian tìm | Quyền truy cập và chất lượng metadata của chat/Drive |
| 3 | Kiểm tra checklist bài nộp thủ công trước khi gửi | Tiêu chí kiểm tra khá rõ; dễ thử bằng checklist/script; có phương án không dùng AI | Checklist thay đổi theo từng lab; cần đo việc bỏ sót cảnh báo |

### 2.2. Problem Cards chi tiết

---

#### Problem Card #1 — Tổng hợp tiến độ nhóm

~~~text
Problem 1 câu:
Mỗi tuần người điều phối mất 35–45 phút gom trạng thái từ chat, bảng task và file để viết một update chung, nhưng vẫn thiếu context hoặc phải hỏi lại thành viên.

Actor:
Người điều phối nhóm sinh viên.

Thời điểm / bối cảnh:
Trước buổi sync hằng tuần hoặc trước khi gửi update cho mentor/giảng viên.

Current workflow 3-7 bước:
1. Mở bảng task và lọc các việc đang làm/quá hạn.
2. Đọc chat để tìm thay đổi, blocker và quyết định mới.
3. Mở các file thành viên đã cập nhật để đối chiếu.
4. Nhắn hỏi lại 2–3 thành viên khi trạng thái chưa rõ.
5. Viết update theo format của nhóm.
6. Gửi lên kênh chung và sửa nếu có người phản hồi.

Bottleneck:
Bước 2–4: phải nối thông tin rời rạc và phân biệt trạng thái cũ/mới.

Impact:
Mất 35–45 phút mỗi tuần; update có thể trễ 30–60 phút và người đọc vẫn phải hỏi lại owner của task.

Success metric:
Giảm thời gian chuẩn bị xuống ≤20 phút/update; ít nhất 90% task trong update có owner và trạng thái; không tăng số câu hỏi xác minh sau khi gửi.

Non-AI alternative:
Chuẩn hóa một form update bắt buộc gồm task, owner, trạng thái, blocker và link; dùng một bảng task duy nhất.

AI hypothesis:
AI đọc dữ liệu đã gom, trích trạng thái/blocker/decision và draft update có link nguồn; người điều phối kiểm tra trước khi gửi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
~~~

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

~~~text
CURRENT STATE — 35–45 phút

[1 mở bảng task: 5'] → [2 đọc chat: 15'] → [3 đối chiếu file: 10']
→ [4 hỏi lại owner: 5–10'] → [5 viết update: 10']  <-- bottleneck

FUTURE STATE — 15–20 phút

[1 form/bảng chuẩn hóa: 3'] → [2 gom input + link: 2']
→ [3 AI trích xuất + draft: 2'] → [4 điều phối review: 10']  <-- human boundary
→ [5 gửi update: 2']

Fallback: nếu thiếu nguồn, AI đánh dấu “chưa xác minh”; điều phối hỏi owner và sửa bằng tay.
~~~

---

#### Problem Card #2 — Tìm quyết định và tài liệu cũ

~~~text
Problem 1 câu:
Thành viên nhóm mất 10–15 phút mỗi lần tìm quyết định hoặc link tài liệu cũ vì thông tin nằm rải rác trong nhiều thread và folder.

Actor:
Thành viên cần tiếp tục một task đã có trao đổi trước đó.

Thời điểm / bối cảnh:
Khi bắt đầu task mới hoặc cần kiểm tra lý do của một quyết định.

Current workflow 3-7 bước:
1. Nhớ một vài keyword.
2. Search trong chat và Drive.
3. Mở nhiều kết quả gần giống nhau.
4. Đọc thread để kiểm tra ngữ cảnh và thời điểm.
5. Hỏi nhóm nếu chưa chắc kết quả nào là bản cuối.

Bottleneck:
Đọc và xác minh ngữ cảnh sau khi search.

Impact:
Mất 10–15 phút/lần, khoảng 2–3 lần/tuần/người; có nguy cơ dùng lại quyết định hoặc file cũ.

Success metric:
Tìm được một nguồn phù hợp trong ≤3 phút ở ít nhất 80% lần thử; 100% câu trả lời có link nguồn để người dùng tự kiểm tra.

Non-AI alternative:
Quy ước đặt tên file, pin decision log và tạo index theo tuần.

AI hypothesis:
AI tóm tắt các kết quả phù hợp và xếp hạng theo thời gian/ngữ cảnh, nhưng chỉ trả lời trong phạm vi nguồn được cấp.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
~~~

**Draft workflow Card #2**:

~~~text
CURRENT STATE — 10–15 phút

[1 nhớ keyword: 1'] → [2 search chat/Drive: 4'] → [3 đọc nhiều thread: 5']
→ [4 xác minh với nhóm: 2–5']  <-- bottleneck

FUTURE STATE — 4–6 phút

[1 search/index: 1'] → [2 AI tóm tắt kèm link: 2']
→ [3 thành viên kiểm tra nguồn: 2–3']  <-- human boundary

Fallback: không đủ bằng chứng thì trả về danh sách nguồn, không tạo câu trả lời kết luận.
~~~

---

#### Problem Card #3 — Kiểm tra checklist bài nộp

~~~text
Problem 1 câu:
Người nộp mất 15–20 phút kiểm tra thủ công nhiều yêu cầu định dạng và nội dung trước deadline, nhưng vẫn có thể bỏ sót một mục.

Actor:
Sinh viên chuẩn bị nộp bài lab hoặc deliverable nhóm.

Thời điểm / bối cảnh:
Trong 1–2 giờ cuối trước hạn nộp, khi phải đối chiếu README, file và rubric.

Current workflow 3-7 bước:
1. Đọc lại README/rubric.
2. Mở từng file trong repo.
3. Đối chiếu tên file, section và link.
4. Sửa lỗi rồi kiểm tra lại từ đầu.
5. Gửi bài và chờ thành viên khác xác nhận.

Bottleneck:
Đối chiếu lặp lại giữa rubric và nhiều file.

Impact:
Mất 15–20 phút/bài; trong hai lần gần đây có ít nhất một lỗi format được phát hiện sau vòng kiểm đầu.

Success metric:
Hoàn tất kiểm tra trong ≤8 phút; không bỏ sót field bắt buộc trong 5 bài thử; mọi cảnh báo có link tới mục kiểm tra.

Non-AI alternative:
Checklist Markdown và script kiểm tra tên file/section bắt buộc.

AI hypothesis:
AI đọc rubric và nội dung bài để gợi ý các mục có nguy cơ thiếu; không tự kết luận đạt/không đạt.

Quick gut:
[x] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
~~~

**Draft workflow Card #3**:

~~~text
CURRENT STATE — 15–20 phút

[1 đọc rubric: 3'] → [2 mở file: 7'] → [3 đối chiếu: 5']
→ [4 sửa và kiểm lại: 5']  <-- bottleneck

FUTURE STATE — 5–8 phút

[1 checklist/script: 1'] → [2 kiểm tra file/section: 2']
→ [3 người nộp xem cảnh báo: 3–5']  <-- human boundary

Fallback: checklist và script vẫn là nguồn kiểm chính; nếu cảnh báo mơ hồ, người review đọc rubric bằng tay.
~~~

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

~~~text
Tổng hợp tiến độ nhóm từ chat, bảng task và các file thành một bản update chung.
~~~

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

~~~text
Đây là việc lặp lại hằng tuần, có bottleneck cụ thể là nối thông tin phân mảnh và có baseline 35–45 phút. Nếu giảm thời gian chuẩn bị xuống ≤20 phút mà vẫn giữ ít nhất 90% task có owner/trạng thái, nhóm sẽ gửi update đúng hạn và giảm việc hỏi lại. Người điều phối vẫn review và chịu trách nhiệm với nội dung cuối.
~~~

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

~~~text
1. Nếu chuẩn hóa form và một bảng task đã giảm phần lớn thời gian, phần AI còn lại có thực sự cần không?
2. Làm sao kiểm tra AI không thêm lỗi hoặc làm tăng số lần người đọc phải hỏi lại?
~~~

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Problem dễ bị mở rộng thành “tự động hóa toàn bộ báo cáo”; input từ chat có thể thiếu hoặc mâu thuẫn.
- Tôi sửa gì: Thu hẹp AI vào trích xuất và draft từ dữ liệu đã gom; bắt buộc link nguồn, đánh dấu phần chưa xác minh và giữ người điều phối review.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
