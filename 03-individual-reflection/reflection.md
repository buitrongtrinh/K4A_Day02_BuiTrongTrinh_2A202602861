# 03 — Individual Reflection

> Reflection cá nhân của Bùi Trọng Trịnh. Vai trò chính: Workflow và AI suitability.

## Thông tin cá nhân

- Họ và tên: Bùi Trọng Trịnh
- Mã học viên: 2A202602861
- Nhóm: Nhóm Day 02 — Phúc Thắng, Gia Bảo, Hoàng Minh, Trọng Trịnh, Minh Hiếu
- Candidate problem nhóm chọn: Cuối tháng, ERP Engineer mất khoảng 2.5–3.5 giờ để đối chiếu weekly report và GitHub commits rồi viết lại thành báo cáo cho quản lý không dùng GitHub.

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 10 vấn đề trong bối cảnh lab/dự án nhóm, trong đó có việc tổng hợp tiến độ từ chat, bảng task và file. | Có thêm một candidate để nhóm so sánh; tôi nhận ra pattern chung là thông tin phân tán rồi phải viết lại thành update. |
| Pitch Problem Card | Tôi pitch candidate “tổng hợp tiến độ nhóm” với baseline 35–45 phút/tuần, bottleneck ở bước đối chiếu nguồn và viết update. | Giúp nhóm có một candidate gần với monthly report để so sánh, đồng thời làm rõ metric và phương án không dùng AI. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi: nếu dùng template đã gom được task thì AI còn cần làm gì, và ai kiểm tra claim/source khi AI draft sai. | Nhóm không chọn Agent tự lấy dữ liệu và tự gửi báo cáo; human review được đưa vào workflow bắt buộc. |
| Gom trùng / cluster | Tôi hỗ trợ gom các candidate về nhóm “tổng hợp update/narrative”, “tìm đúng thông tin” và “Rule/process trước”. | Nhóm thấy monthly report, group update và weekly report có cùng pattern nhưng monthly report có impact và source data rõ hơn. |
| Chọn candidate problem | Tôi challenge việc chọn group update vì impact nhỏ hơn, sau đó đồng ý chọn monthly report ERP nếu data pilot được ẩn thông tin nhạy cảm. | Quyết định cuối có điều kiện và có group update làm phương án dự phòng. |
| Validation / research | Tôi hỗ trợ kiểm tra xem baseline, source data và claim trong research có đủ để đưa vào workflow; không tự nhận phần phỏng vấn/poll của Gia Bảo. | Group report ghi rõ số liệu monthly report hiện mới là ước lượng, cần bấm giờ pilot; các link research được dùng để tham khảo pattern, không thay cho evidence nội bộ. |
| Workflow nhóm | Tôi vẽ current workflow 6 bước và future workflow gồm Rule/template → map source → AI draft → ERP Engineer review → gửi. | Làm rõ bottleneck ở đối chiếu/viết narrative, AI intervention point, human boundary và fallback về template + checklist. |
| Problem Statement | Tôi phản biện để PS không viết thành “tự động hóa báo cáo toàn bộ”, mà giới hạn ở draft từ weekly report và commit/PR đã chọn. | PS v1 có boundary, source link cho từng claim, owner review và metric dưới 45 phút. |
| Rule / Workflow / Agent | Tôi lập luận Rule phù hợp cho việc map field/checklist, Workflow phù hợp cho AI draft, còn Agent không cần vì luồng có thể định trước. | Nhóm chọn Workflow pilot, không cấp quyền cho Agent tự đọc nhiều tool hoặc tự gửi báo cáo. |
| Decision | Tôi đề xuất decision chỉ là Go cho pilot bán thủ công, với dữ liệu đã ẩn thông tin nhạy cảm và có rollback. | Quyết định gắn với điều kiện pass/fail: thời gian, source coverage, claim sai/sót và câu hỏi xác minh. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

~~~text
Phần workflow before/after và bảng Rule–Workflow–Agent là đóng góp rõ nhất của tôi.
Tôi cũng giúp nhóm đặt human boundary ở bước ERP Engineer kiểm từng claim, số liệu và source link trước khi gửi.
~~~

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm problem theo bốn lăng kính sau khi tôi tự scan. | Gợi ý thêm các việc lặp lại như tìm quyết định cũ, action item và checklist. | Nhiều ý quá rộng như AI quản lý toàn bộ dự án, không có actor hoặc baseline cụ thể. | Tôi giữ các ý có workflow và số đo; bỏ ý chưa có pain thật hoặc có rủi ro quá lớn. |
| Problem Card | Phản biện actor, bottleneck, metric và phương án non-AI. | Giúp tôi nhận ra card “tổng hợp tiến độ” phải tách bước gom dữ liệu khỏi bước viết narrative. | AI mặc định đề xuất tự động hóa end-to-end và chưa hỏi data có đủ hay không. | Tôi thu hẹp intervention vào draft, yêu cầu source link và giữ người điều phối/engineer review. |
| Workflow | Gợi ý cách biểu diễn workflow before–after bằng các bước có thời gian. | Giúp so sánh nhanh current state với Rule/template → AI draft → human review. | AI không tự biết thời gian ước lượng và dễ bỏ qua bước xác minh dữ liệu. | Tôi dùng thời gian từ group report làm baseline tạm thời, đánh dấu cần đo lại và thêm fallback. |
| Research | Gợi ý các tool/pattern để nhóm kiểm tra như GitHub Projects, Jira Automation và Slack AI. | Giúp mở rộng danh sách hướng có sẵn trước khi nhóm quyết định build gì. | Một số mô tả chung chung và không đủ làm evidence cho pain của ERP Engineer. | Tôi kiểm tra lại bằng link tài liệu chính thức, chỉ dùng research để rút pattern; không dùng số liệu chưa verify. |
| Problem Statement | Đọc ngược PS v0 và hỏi field nào còn solution-first hoặc mơ hồ. | Giúp thấy boundary “không tự gửi, không tự lấy dữ liệu công ty ngoài bộ đã chọn” cần viết rõ hơn. | AI thường đề xuất metric kiểu “nhanh hơn/tốt hơn”, chưa gắn baseline và cách đo. | Tôi sửa thành dưới 45 phút/report, 100% claim có source và không tăng câu hỏi xác minh. |
| Rule / Workflow / Agent | So sánh cùng một bài toán ở ba mức Rule, Workflow và Agent. | AI giúp liệt kê ưu/nhược điểm và chỉ ra Agent chỉ đáng dùng khi có nhiều nhánh, tool và quyền truy cập. | AI có xu hướng làm Agent nghe hấp dẫn dù workflow này vẫn tuyến tính. | Tôi chọn Workflow có Rule ở input và human review; ghi rõ lý do không chọn Agent. |
| Decision | Dùng AI như một người phản biện cho điều kiện Go và rollback. | Giúp tôi bổ sung các failure case như claim không có source, bịa task và lộ dữ liệu nhạy cảm. | AI thiên về kết luận Go nếu thấy metric rõ, nhưng chưa cân nhắc quyền truy cập dữ liệu thật. | Tôi đổi thành Go có điều kiện cho pilot bán thủ công và đặt exit khi draft sai hoặc không ẩn được dữ liệu. |

---

## 3. Reflection câu hỏi mở

Khi nghe top 3 problems của các bạn, tôi thấy nhiều pain khác nhau đều quay về việc gom thông tin rời rạc rồi viết lại cho một người không trực tiếp làm công việc đó. Ban đầu tôi nghiêng về group update vì đó là vấn đề tôi có trải nghiệm rõ, nhưng sau khi so sánh thì monthly report ERP có baseline lớn hơn và source data cụ thể hơn. Tôi đã challenge nhóm ở điểm nếu template và checklist đã giải quyết được phần gom field thì chưa thể mặc định AI là cần thiết. Điều khó nhất khi viết Problem Statement không phải là mô tả metric, mà là đặt boundary để AI không được tự lấy dữ liệu hoặc tự gửi báo cáo. Tôi đóng góp nhiều nhất ở workflow before–after và cách tách Rule, AI draft và human review thành các bước riêng. Tôi cũng học được rằng Agent không phải lựa chọn mặc định cho workflow có nhiều nguồn; nếu thứ tự bước vẫn biết trước thì Workflow có kiểm soát phù hợp hơn. AI hữu ích khi giúp tôi nhìn thấy các failure case, nhưng các con số baseline và chất lượng claim vẫn phải do nhóm tự kiểm. Vì validation nội bộ chưa đủ mạnh và baseline monthly report còn là ước lượng, tôi không xem quyết định Go là triển khai chính thức. Nhóm chỉ nên Go với một pilot nhỏ dùng dữ liệu đã ẩn thông tin nhạy cảm và đo lại thời gian thật. Nếu làm lại, tôi sẽ yêu cầu nhóm ghi evidence/link cho từng đóng góp sớm hơn và challenge mạnh hơn về quyền truy cập GitHub trước khi bàn đến giải pháp AI.

---

## 4. Tự kiểm cuối bài

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
