# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Hoàng Lê Nguyên
- Mã học viên: 2A202602472
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Intern vận hành dự án tại một công ty công nghệ
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
	- Theo dõi tiến độ task của team trên Notion và Slack
	- Chuẩn bị agenda, ghi biên bản và theo dõi action item sau các buổi họp
	- Tổng hợp thông tin để gửi cập nhật hằng tuần cho supervisor
	- Thu thập và phân loại feedback từ khách hàng/người dùng thử

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Tổng hợp tiến độ dự án từ Slack và Notion để gửi supervisor | Tôi và project team | 2 lần/tuần, mỗi lần 35-45 phút; tuần qua phải hỏi lại 3 người vì cập nhật thiếu deadline |
| 2 | Tốn thời gian | Tìm lại quyết định và link tài liệu cũ trong nhiều kênh làm việc | Tôi và project team | 3-4 lần/tuần, mỗi lần 8-12 phút; có 2 lần dùng nhầm phiên bản tài liệu |
| 3 | Lặp lại | Viết biên bản sau các buổi họp nội bộ | Tôi và người tham dự cuộc họp | 1-2 buổi/tuần, khoảng 25 phút/buổi; một biên bản tuần trước gửi muộn 1 ngày |
| 4 | Tốn thời gian | Theo dõi task quá hạn và hỏi từng owner về lý do | Tôi và các task owner | Khoảng 20 phút/lần, 2 lần/tuần; 3 task được phát hiện trễ sau deadline dự kiến |
| 5 | AI có thể tốt hơn | Biến ghi chú cuộc họp thành checklist công việc có owner và deadline | Project team 5-7 người | Có 6-10 ý ghi chú/buổi nhưng thường chỉ 3-4 ý được chuyển thành task rõ ràng |
| 6 | Pain từ người khác | Nhận brief từ các team khác thiếu thông tin hoặc sai format | Tôi và người phụ trách yêu cầu | 4-6 brief/tháng; mỗi brief phải hỏi lại trung bình 2 lần trước khi xử lý |
| 7 | Pain từ người khác | Supervisor phải hỏi lại trạng thái từng task trước buổi báo cáo | Supervisor và tôi | 2 lần/tuần; mỗi lần mất khoảng 15 phút để gom câu trả lời từ các owner |
| 8 | AI có thể tốt hơn | Tóm tắt phản hồi người dùng thử thành các nhóm insight | Product team | Đợt khảo sát gần nhất có 42 phản hồi; tôi mất 70 phút để đọc và nhóm thủ công |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Hãy phản biện danh sách các việc hằng tuần của một intern vận hành dự án; việc nào là pain có actor, workflow và metric rõ?"
- Ý dùng được: Tách việc "quản lý nhóm kém" thành các bước cụ thể như thu thập cập nhật, kiểm tra deadline và viết summary.
- Ý bỏ vì không phải pain thật: Tự động quản lý toàn bộ dự án và chatbot trả lời mọi câu hỏi; phạm vi quá rộng và supervisor vẫn cần quyết định trực tiếp.

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tổng hợp tiến độ dự án từ Slack và Notion để gửi supervisor | Workflow lặp lại 2 lần/tuần; mất 35-45 phút; bottleneck và người chịu trách nhiệm rõ | Các owner có chịu cập nhật theo một form thống nhất không |
| 2 | Biến ghi chú cuộc họp thành checklist công việc | Có đầu vào sẵn; dễ đo số action item rõ ràng; project team cùng hưởng lợi | AI có phân biệt được ý tưởng với task thật không |
| 3 | Tóm tắt phản hồi người dùng thử thành nhóm insight | Có dữ liệu cụ thể và pain lớn 70 phút/lần; output có thể kiểm tra lại | Số đợt feedback chưa nhiều để chứng minh nhu cầu thường xuyên |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tổng hợp tiến độ dự án

```text
Problem 1 câu: Mỗi tuần tôi mất 35-45 phút gom tiến độ dự án từ các owner qua Slack và Notion, nhưng vẫn phải hỏi lại vì nhiều cập nhật thiếu trạng thái hoặc deadline.

Actor: Intern vận hành dự án hỗ trợ project team 5-7 người.

Thời điểm / bối cảnh: Chiều thứ Tư và chiều thứ Sáu trước khi gửi update cho supervisor.

Current workflow 3-7 bước:
1. Mở bảng task trên Notion và lọc các việc sắp đến hạn.
2. Nhắn từng owner xin trạng thái mới nhất qua Slack.
3. Đọc tin nhắn và tìm link/file được nhắc đến.
4. Cập nhật bảng task và đánh dấu task có nguy cơ trễ.
5. Viết summary gửi cho supervisor.

Bottleneck: Bước 2-3, gom và chuẩn hóa câu trả lời từ nhiều kênh; mất khoảng 25 phút.

Impact: 70-90 phút/tuần của tôi; supervisor nhận update muộn và khó biết task nào cần hỗ trợ.

Success metric: Giảm thời gian tổng hợp mỗi lần từ 40 phút xuống dưới 15 phút; ít nhất 90% task có status và deadline rõ; đo trong 2 tuần thử nghiệm.

Non-AI alternative: Dùng một form cập nhật cố định trước mỗi buổi review, chỉ một bảng task và checklist bắt buộc.

AI hypothesis: AI đọc các câu trả lời đã được thu thập trong form, chuẩn hóa thành status/deadline/risk và tạo draft summary; tôi kiểm tra từng task trước khi gửi supervisor.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 40 phút

[1 Mở bảng: 5'] → [2 Hỏi 5 người: 15'] → [3 Đọc chat/link: 10'] → [4 Cập nhật bảng + viết summary: 10']  <-- bottleneck

FUTURE STATE — 14 phút

[1 Form cập nhật: 3'] → [2 AI chuẩn hóa + draft: 2'] → [3 Tôi review từng task: 7'] → [4 Gửi summary: 2']  <-- human boundary

Fallback: nếu AI thiếu hoặc hiểu sai status, tôi mở câu trả lời gốc, sửa trên bảng và hỏi lại thành viên trước khi gửi.
```

File đính kèm: [01-individual-problem-scan-workflow-card-1.svg](01-individual-problem-scan-workflow-card-1.svg)

---

#### Problem Card #2 — Biến ghi chú cuộc họp thành checklist công việc

```text
Problem 1 câu: Sau mỗi buổi họp dự án, team có nhiều ghi chú nhưng tôi mất khoảng 25 phút để biến chúng thành các task có owner và deadline rõ.

Actor: Intern ghi biên bản và project team 5-7 người.

Thời điểm / bối cảnh: Ngay sau buổi họp sprint hoặc buổi sync nội bộ.

Current workflow 3-7 bước:
1. Ghi nhanh ý chính trong lúc họp.
2. Đọc lại và xóa phần trùng lặp.
3. Tách ý tưởng, quyết định và việc cần làm.
4. Gán owner/deadline cho từng việc.
5. Gửi biên bản để các owner xác nhận.

Bottleneck: Bước 3-4, xác định đâu là action item và điền owner/deadline; mất khoảng 15 phút.

Impact: 25 phút/buổi và có khoảng 1-2 task bị bỏ sót hoặc không có owner.

Success metric: Giảm thời gian xử lý note xuống dưới 10 phút; 100% task trong biên bản có owner; kiểm tra qua 3 buổi họp.

Non-AI alternative: Dùng template biên bản với ba mục cố định: quyết định, action item, vấn đề mở.

AI hypothesis: AI phân loại ghi chú và đề xuất task, owner, deadline để người ghi biên bản xác nhận; AI không tự giao việc.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 25 phút

[1 Ghi note: 10'] → [2 Đọc lại: 5'] → [3 Tách task + gán người: 10']  <-- bottleneck

FUTURE STATE — 9 phút

[1 Nhập note: 2'] → [2 AI phân loại: 2'] → [3 Người ghi xác nhận: 5']  <-- human boundary

Fallback: Ý nào không đủ ngữ cảnh được đưa vào mục "cần xác nhận", không tự biến thành task.
```

File đính kèm: [01-individual-problem-scan-workflow-card-2.svg](01-individual-problem-scan-workflow-card-2.svg)

---

#### Problem Card #3 — Tóm tắt phản hồi người dùng thử

```text
Problem 1 câu: Sau mỗi đợt người dùng thử, tôi mất khoảng 70 phút đọc 42 phản hồi và nhóm thủ công thành các insight để báo cáo cho product team.

Actor: Intern phụ trách tổng hợp feedback cho product team.

Thời điểm / bối cảnh: Trong 1-2 ngày sau mỗi đợt user testing hoặc khảo sát sản phẩm.

Current workflow 3-7 bước:
1. Xuất 42 câu trả lời từ công cụ khảo sát.
2. Đọc từng câu và đánh dấu chủ đề.
3. Gom các câu có ý giống nhau.
4. Đếm tần suất và chọn trích dẫn tiêu biểu.
5. Viết báo cáo feedback cho product team.

Bottleneck: Bước 2-3, đọc và nhóm các câu trả lời tự do; mất khoảng 45 phút.

Impact: 70 phút sau mỗi đợt feedback; báo cáo thường bị lùi 1 ngày và dễ bỏ sót ý kiến ít gặp.

Success metric: Giảm thời gian sơ bộ từ 70 phút xuống 25 phút; giữ lại 100% phản hồi trong dữ liệu gốc; người phụ trách xác nhận các nhóm insight.

Non-AI alternative: Tạo bộ tag cố định trong spreadsheet và dùng COUNTIF cho các câu trả lời có từ khóa rõ.

AI hypothesis: AI gom các phản hồi theo chủ đề và tạo bản tóm tắt có trích dẫn; người phụ trách kiểm tra lại số lượng và câu gốc trước khi báo cáo.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 70 phút

[1 Xuất dữ liệu: 5'] → [2 Đọc 42 câu: 45'] → [3 Gom chủ đề + đếm: 15'] → [4 Viết báo cáo: 5']  <-- bottleneck

FUTURE STATE — 25 phút

[1 Xuất dữ liệu: 5'] → [2 AI nhóm + draft: 5'] → [3 Kiểm tra câu gốc/số lượng: 12'] → [4 Viết báo cáo: 3']  <-- human boundary

Fallback: Nếu nhóm insight không hợp lý, dùng bộ tag cố định để phân loại thủ công và giữ nguyên file phản hồi gốc.
```

File đính kèm: [01-individual-problem-scan-workflow-card-3.svg](01-individual-problem-scan-workflow-card-3.svg)

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Tổng hợp tiến độ dự án từ Slack và Notion
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Tôi muốn pitch bài này vì workflow xảy ra hai lần mỗi tuần, actor là tôi và các task owner, và thời gian hiện tại có thể đo được là 35-45 phút/lần. Tôi muốn kiểm tra xem pain thật nằm ở việc hỏi cập nhật hay ở việc thiếu một format cập nhật thống nhất.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Nếu bắt buộc các task owner cập nhật qua một form cố định, pain còn lại bao nhiêu phần?
2. Metric "status đúng" sẽ được kiểm tra thế nào để không chỉ đo việc AI viết summary nhanh hơn?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Problem ban đầu dễ bị hiểu thành xây agent tự theo dõi mọi kênh làm việc; dữ liệu thiếu cấu trúc và quyền truy cập cũng là rủi ro.
- Tôi sửa gì: Thu hẹp thành workflow dùng form cập nhật làm đầu vào, AI chỉ chuẩn hóa và draft summary. Tôi giữ quyền review task và không cho AI tự nhắn supervisor hoặc tự giao việc.

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
