# 01 — Individual Problem Scan

**Trạng thái:** Card #1 là giả thuyết đang kiểm chứng; số đo còn thiếu được ghi trong từng metric.

## Thông tin cá nhân

- Họ và tên: Nguyễn Mạnh Cường
- Mã học viên: 2A202602650
- Vai trò / bối cảnh: Học viên tham gia AI Product Labs, thường làm bài thực hành và dự án phần mềm trên Windows.
- Công việc hằng tuần:
  - Đọc yêu cầu bài học trên LMS và trong repository.
  - Clone repository, cài môi trường và chạy bài thực hành.
  - Kiểm tra kết quả bằng test hoặc checklist của bài.
  - Commit và push bài lên GitHub.
  - Trao đổi với AI hoặc bạn học khi gặp lỗi hay chưa rõ bước tiếp theo.

---

## Phase 1 — Scan 5+ problems

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian / AI có thể tốt hơn | Người học phải tổng hợp yêu cầu từ nhiều tài liệu. Hướng đào sâu: khi cùng bài tập có cập nhật ở LMS/email/chat, người học khó xác định yêu cầu nào còn hiệu lực. | Sinh viên nhận thông tin cùng một assignment từ ít nhất hai nguồn | Trong Day 02 có 1 tình huống cần làm rõ yêu cầu, gồm câu hỏi có phần code cá nhân hay không. Đây chưa phải bằng chứng có deadline mâu thuẫn; tần suất cập nhật, sai sót và thời gian đối chiếu chưa đo. |
| 2 | Lặp lại / Tốn thời gian | Mỗi repository có thể yêu cầu phiên bản Python, virtual environment và lệnh chạy khác nhau; người học khó biết lỗi đến từ môi trường hay code. | Học viên làm nhiều lab Python trên Windows | Hai lab gần đây dùng ít nhất 2 phiên bản Python khác nhau (3.12.8 và 3.11.9); đã có 1 phiên không gọi được cả `python` lẫn `py`. |
| 3 | Tốn thời gian | Hướng dẫn dùng công cụ dòng lệnh không có sẵn trên máy khiến người học dừng giữa chừng và phải tìm lệnh thay thế. | Học viên Windows làm theo hướng dẫn terminal | Đã có 1 lần lệnh `rg` không tồn tại và phải đổi sang `Select-String` của PowerShell. Thời gian gián đoạn chưa được đo. |
| 4 | AI có thể tốt hơn / Tốn thời gian | Sau khi cài môi trường thành công, người học vẫn khó xác định bài đã hoàn thành thật hay còn thiếu hàm, test hoặc bước xác minh nào. | Học viên đang hoàn thiện bài lập trình | Một lab đã cài dependency và import thành công nhưng test từng còn `2 passed, 7 failed`; chưa có bằng chứng cuối cùng `9 passed`. |
| 5 | Lặp lại / Tốn thời gian | Khi máy lưu nhiều tài khoản GitHub, người học có thể push bằng nhầm tài khoản và không biết lỗi 403 là do quyền truy cập. | Học viên có từ 2 tài khoản GitHub trở lên | Đã có 1 lần push lỗi HTTP 403 do tài khoản active không sở hữu repo; sau khi chuyển sang `cuong-cpu21`, cùng thao tác push đã thành công. |

**AI đã dùng ở Phase 1:**

- Prompt đã hỏi: Mở rộng chủ đề, xác định pain point và chọn vấn đề phù hợp để làm bài Day 02.
- Ý dùng được: hiểu yêu cầu lab, thiết lập môi trường, xác minh bài hoàn thành và lỗi khi nộp GitHub.
- Cập nhật hướng nghiên cứu: từ “cần làm gì” sang “yêu cầu nào còn hiệu lực”; giữ nguyên giới hạn bằng chứng ban đầu, không coi ví dụ xung đột deadline là sự cố đã xảy ra.
- Ý bỏ vì chưa phải pain thật: nhận đơn bán hàng qua chat, quyết toán chuyến đi và nhập nguyên liệu cho quán; chưa có bằng chứng người học trực tiếp gặp.

**Self-check Phase 1:**

- [x] Đủ 5 dòng, mỗi dòng có actor và dấu hiệu cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không mô tả chung chung kiểu “mất nhiều thời gian”
- [ ] Bổ sung thời gian thực tế bằng cách bấm giờ hoặc xem lại log

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Xác định yêu cầu hiện hành của bài tập từ nhiều nguồn | Thu hẹp từ problem #1; có bước đối chiếu hiệu lực rõ, đo được công tìm/kiểm tra, lỗi và mâu thuẫn bỏ sót. | Chưa chứng minh pain phiên bản; cần so với bảng yêu cầu chuẩn do giảng viên/TA cập nhật. |
| 2 | Khó xác định và sửa đúng vấn đề môi trường của từng repository | Đã lặp lại ở nhiều lab; có workflow rõ; ảnh hưởng trực tiếp đến khả năng bắt đầu làm bài. | Chưa đo tần suất và tổng thời gian mất trong một tháng. |
| 3 | Push bài bằng nhầm tài khoản GitHub dẫn đến lỗi quyền truy cập | Có sự cố thật và kết quả trước/sau rõ; bottleneck cụ thể; giải pháp kiểm chứng nhanh. | Pain có thể không đủ lớn với người chỉ dùng một tài khoản GitHub. |

### 2.2. Problem Cards chi tiết

---

#### Problem Card #1 — Xác định yêu cầu hiện hành của bài tập từ nhiều nguồn

```text
Problem 1 câu:
Sinh viên phải đối chiếu các thông báo của cùng một assignment trên LMS,
email và chat để xác định yêu cầu còn hiệu lực trước khi chốt checklist nộp bài.
Đây là giả thuyết cần kiểm chứng bằng assignment và cập nhật thật.

Actor:
Sinh viên có cùng một bài tập được thông báo ở ít nhất hai nguồn,
đặc biệt khi deadline hoặc yêu cầu được cập nhật.

Thời điểm / bối cảnh:
Khi bắt đầu bài, nhận cập nhật hoặc chuẩn bị nộp; cần chốt deadline,
file bắt buộc, giới hạn nội dung và nơi nộp.

Current workflow 3-7 bước:
1. Xác định đúng môn, lớp/nhóm và assignment.
2. Tìm các thông báo liên quan trên LMS/email/chat.
3. Trích deadline, file bắt buộc, giới hạn và nơi nộp.
4. Đối chiếu nội dung, tác giả, thời điểm và phạm vi cập nhật.
5. Hỏi giảng viên/TA nếu chưa rõ hoặc có mâu thuẫn.
6. Chốt checklist kèm nguồn và thời điểm xác nhận.

Bottleneck:
Đã tìm thấy thông tin nhưng không biết nó còn áp dụng hay đã được thay đổi.
Thông báo mới hơn chưa chắc có thẩm quyền hơn; cập nhật có thể chỉ sửa một trường.

Impact:
Có thể tốn công đối chiếu, chờ xác nhận và làm theo bản cũ hoặc bỏ sót yêu cầu.
Chưa có bằng chứng định lượng về tần suất, thời gian hoặc sự cố nộp sai.

Success metric:
Baseline: chưa đo; câu hỏi về phần code chỉ hỗ trợ pain hiểu yêu cầu.
Đo T0 (cách hiện tại) và T1 (workflow hỗ trợ) từ tìm/nhập nguồn đến chốt checklist,
gồm công ẩn thông tin, review và sửa lỗi; ghi riêng thời gian chờ TA.
Mục tiêu pilot đề xuất: trung vị thời gian thao tác giảm ít nhất 30% so với
cách hiện tại, không chậm hơn checklist chuẩn; không sai/thiếu trường bắt buộc
trong mẫu cuối; phát hiện đủ mâu thuẫn được gán nhãn, báo cả cảnh báo sai.
Mọi trường có trích dẫn kiểm được. Đối chiếu đáp án do giảng viên/TA xác nhận;
kết quả mẫu nhỏ không chứng minh hệ thống luôn đúng.

Non-AI alternative:
Giảng viên/TA duy trì một bảng yêu cầu chuẩn cho mỗi assignment có lịch sử
cập nhật. Nếu bảng này đã đủ và ít công hơn, ưu tiên cách đó.

AI hypothesis:
AI trích yêu cầu có nguyên văn/nguồn và gợi ý các cập nhật liên quan;
Rule so giá trị, giữ lịch sử và kiểm tra trường thiếu. Sinh viên đối chiếu nguồn,
hỏi TA khi mâu thuẫn và xác nhận checklist; AI không tự quyết deadline.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1:**

```text
CURRENT STATE — thời gian cần đo

[Xác định bài] → [Tìm nguồn] → [Trích yêu cầu]
→ [Đối chiếu hiệu lực] <-- bottleneck
→ [Hỏi giảng viên/TA] <-- handoff → [Chốt checklist]

FUTURE STATE — mục tiêu giảm ít nhất 30% công thao tác; chưa đo

[Sinh viên chọn bài + nhập nguồn] → [Rule kiểm metadata/trùng nguồn]
→ [AI trích yêu cầu có nguồn] → [Rule so + AI gợi ý cập nhật]
→ [Sinh viên review, hỏi TA nếu cần] <-- human boundary / handoff
→ [Sinh viên xác nhận checklist]

T0/T1 tính đủ công tìm/nhập nguồn và sửa; thời gian chờ TA báo riêng.
Cập nhật mới → review lại trường bị ảnh hưởng, giữ lịch sử.

Fallback: nguồn thiếu/mâu thuẫn → giữ “cần xác minh” và hỏi giảng viên/TA.
Trích sai → mở nguồn, sửa tay. Không dùng timestamp mới hơn làm kết luận cuối.
Phạm vi thử: văn bản được cung cấp cho một assignment; không tự đọc inbox/chat,
không tự sửa lịch hoặc nộp bài. Chỉ xác nhận trong tập nguồn đã kiểm tra.
```

---

#### Problem Card #2 — Kiểm tra môi trường trước khi làm lab

```text
Problem 1 câu:
Học viên làm nhiều repository Python trên Windows bị gián đoạn vì không biết
phiên bản Python, virtual environment và dependency hiện tại đã đúng chưa.

Actor:
Học viên làm bài lập trình Python trên Windows.

Thời điểm / bối cảnh:
Sau khi clone repository hoặc quay lại dự án trong một terminal mới.

Current workflow 3-7 bước:
1. Đọc hướng dẫn cài đặt.
2. Thử chạy python hoặc py.
3. Tạo hoặc kích hoạt virtual environment.
4. Cài dependency.
5. Chạy test hoặc chương trình.
6. Đọc lỗi và thử xác định do môi trường hay code.

Bottleneck:
Phân biệt lỗi môi trường với lỗi triển khai bài tập và chọn đúng lệnh sửa.

Impact:
Người học chưa bắt đầu được phần chính, thử nhiều lệnh và có thể cài nhầm
phiên bản hoặc cài package ra ngoài virtual environment.

Success metric:
Hiện trạng: đã gặp ít nhất 2 yêu cầu phiên bản Python khác nhau và 1 phiên
không gọi được python/py; thời gian chưa đo. Mục tiêu: xác định đầy đủ Python,
venv và dependency trong dưới 2 phút, trước khi sửa code.

Non-AI alternative:
Một script/checklist cố định kiểm tra phiên bản Python, đường dẫn interpreter,
trạng thái venv và dependency.

AI hypothesis:
AI chỉ hỗ trợ giải thích lỗi chưa được checklist nhận diện, dựa trên README
và output thực tế; các kiểm tra xác định dùng rule.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — thời gian cần đo

[Đọc README] → [Thử các lệnh Python] → [Cài môi trường]
→ [Chạy bài] → [Phân loại lỗi bằng tay] <-- bottleneck

FUTURE STATE — mục tiêu kiểm tra dưới 2 phút

[Đọc yêu cầu repo] → [Chạy preflight theo rule] → [Hiện mục thiếu + cách xử lý]
→ [Học viên duyệt rồi thực hiện] <-- human boundary → [Chạy lại preflight/test]

Fallback: lỗi không khớp rule thì giữ nguyên log, đọc hướng dẫn chính thức hoặc
hỏi trợ giảng; không tự động thay phiên bản hay xóa môi trường.
```

---

#### Problem Card #3 — Phát hiện sai tài khoản GitHub trước khi push

```text
Problem 1 câu:
Học viên có nhiều tài khoản GitHub có thể nộp bài thất bại vì terminal đang
xác thực bằng tài khoản không có quyền với repository đích.

Actor:
Học viên dùng từ hai tài khoản GitHub trên cùng máy.

Thời điểm / bối cảnh:
Sau khi commit và chuẩn bị push bài lên repository cá nhân hoặc repository lớp.

Current workflow 3-7 bước:
1. Kiểm tra hoặc tạo commit.
2. Chạy git push.
3. Nhận lỗi HTTP 403.
4. Kiểm tra remote và tài khoản đang xác thực.
5. Chuyển sang tài khoản có quyền.
6. Push lại và kiểm tra trạng thái tracking.

Bottleneck:
Nhận ra lỗi thuộc tài khoản xác thực/quyền repository, thay vì tên người tạo
commit hoặc nội dung code.

Impact:
Nộp bài bị gián đoạn; người học có thể chỉnh cấu hình không liên quan.

Success metric:
Hiện trạng: đã có 1 lần push thất bại HTTP 403 rồi thành công sau khi đổi tài khoản.
Mục tiêu: trong 3 lượt nộp tiếp theo, phát hiện tài khoản không phù hợp trước khi
push và không có lượt push thất bại do nhầm tài khoản.

Non-AI alternative:
Pre-push checklist kiểm tra remote, tài khoản đang xác thực và quyền push vào repo.
Owner khác tên tài khoản không đồng nghĩa thiếu quyền: collaborator có thể được cấp quyền;
chỉ đổi tài khoản khi xác định tài khoản hiện tại không có quyền cần thiết.

AI hypothesis:
AI có thể giải thích thông báo lỗi, nhưng phần phát hiện chính có thể giải quyết
bằng rule xác định.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — thời gian cần đo

[Commit] → [Push] → [Nhận 403] <-- bottleneck
→ [Tìm nguyên nhân] → [Đổi tài khoản] → [Push lại]

FUTURE STATE — mục tiêu kiểm tra dưới 1 phút

[Commit] → [Kiểm tra remote] → [Kiểm tra tài khoản active và quyền push]
→ [Học viên xác nhận đổi tài khoản] <-- human boundary
→ [Push] → [Xác minh branch tracking]

Fallback: nếu tài khoản đúng nhưng vẫn thiếu quyền, dừng push và kiểm tra quyền
repository hoặc liên hệ người quản lý repository.
```

---

### 2.3. Card muốn pitch nhất

**Card tôi muốn pitch nhất:**

```text
Card #1 — Xác định yêu cầu hiện hành của bài tập từ nhiều nguồn.
```

**Vì sao:**

```text
Day 02 cho thấy tôi cần làm rõ yêu cầu; từ tín hiệu này, tôi muốn kiểm chứng
vấn đề hẹp hơn: “đã tìm thấy thông tin nhưng không biết bản nào còn hiệu lực”.
Card có bước đối chiếu cụ thể, đầu ra kiểm tra được và phương án không AI rõ.
Tôi chọn để pitch và nghiên cứu, chưa khẳng định pain xung đột đã được chứng minh
hoặc toàn nhóm đã chốt; hướng này tương ứng C1 / shortlist S1 trong báo cáo nhóm.
```

**Câu hỏi tôi muốn nhóm challenge:**

```text
Có assignment thật nào có cập nhật/mâu thuẫn, và pain xảy ra bao nhiêu lần?
Bảng yêu cầu chuẩn đã đủ chưa; AI còn tiết kiệm công sau khi tính nhập và review?
Khi nguồn mâu thuẫn, ai xác nhận; làm sao phân biệt thiếu thông tin với bị thay thế?
```

**AI phản biện Card:**

- Điểm yếu AI chỉ ra: câu hỏi về phần code không chứng minh xung đột phiên bản; chưa có baseline; nguồn mới hơn chưa chắc đúng hơn; checklist chuẩn có thể đủ.
- Cập nhật trong bản nháp có AI hỗ trợ: thu hẹp actor và bottleneck, phân biệt bằng chứng với giả thuyết, tính công nhập/review, giữ nguồn và người xác nhận.

### Self-check nộp phần 01

- [x] Có 5 problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
- [x] Đã bổ sung họ tên và mã học viên
- [ ] Bổ sung thời gian baseline sau khi đo
- [ ] Kiểm chứng giả thuyết Card #1 bằng assignment và cập nhật thật
