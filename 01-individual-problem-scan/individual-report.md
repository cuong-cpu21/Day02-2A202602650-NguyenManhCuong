# 01 — Individual Problem Scan

> Bản nháp dựa trên các sự cố đã thực sự xuất hiện khi làm những lab gần đây. Các mốc ghi “cần đo” chưa được xem là bằng chứng định lượng và cần bổ sung sau khi bấm giờ.

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
| 1 | Tốn thời gian / AI có thể tốt hơn | Khi bắt đầu lab mới, yêu cầu nằm ở LMS, README, worksheet và các file mẫu nên người học phải tự ghép lại để biết phần cá nhân, phần nhóm và file cần nộp. | Học viên mới bắt đầu bài lab | Trong Day 02, người học phải nhờ đọc repo để xác định “bây giờ làm gì”, sau đó hỏi thêm 1 lần xem có phần code cá nhân hay không. Thời gian chưa được bấm giờ. |
| 2 | Lặp lại / Tốn thời gian | Mỗi repository có thể yêu cầu phiên bản Python, virtual environment và lệnh chạy khác nhau; người học khó biết lỗi đến từ môi trường hay code. | Học viên làm nhiều lab Python trên Windows | Hai lab gần đây dùng ít nhất 2 phiên bản Python khác nhau (3.12.8 và 3.11.9); đã có 1 phiên không gọi được cả `python` lẫn `py`. |
| 3 | Tốn thời gian / Pain từ người khác | Hướng dẫn dùng công cụ dòng lệnh không có sẵn trên máy khiến người học dừng giữa chừng và phải tìm lệnh thay thế. | Học viên Windows làm theo hướng dẫn terminal | Đã có 1 lần lệnh `rg` không tồn tại và phải đổi sang `Select-String` của PowerShell. Thời gian gián đoạn chưa được đo. |
| 4 | AI có thể tốt hơn / Tốn thời gian | Sau khi cài môi trường thành công, người học vẫn khó xác định bài đã hoàn thành thật hay còn thiếu hàm, test hoặc bước xác minh nào. | Học viên đang hoàn thiện bài lập trình | Một lab đã cài dependency và import thành công nhưng test từng còn `2 passed, 7 failed`; chưa có bằng chứng cuối cùng `9 passed`. |
| 5 | Lặp lại / Tốn thời gian | Khi máy lưu nhiều tài khoản GitHub, người học có thể push bằng nhầm tài khoản và không biết lỗi 403 là do quyền truy cập. | Học viên có từ 2 tài khoản GitHub trở lên | Đã có 1 lần push lỗi HTTP 403 do tài khoản active không sở hữu repo; sau khi chuyển sang `cuong-cpu21`, cùng thao tác push đã thành công. |

**AI đã dùng ở Phase 1:**

- Prompt đã hỏi: Mở rộng chủ đề, xác định pain point và chọn vấn đề phù hợp để làm bài Day 02.
- Ý dùng được: hiểu yêu cầu lab, thiết lập môi trường, xác minh bài hoàn thành và lỗi khi nộp GitHub.
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
| 1 | Khó chuyển tài liệu lab thành danh sách việc và sản phẩm cần nộp | Xảy ra ngay đầu workflow; actor rõ; đo được thời gian và số yêu cầu bị bỏ sót; áp dụng cho nhiều môn học. | Checklist chuẩn của giảng viên có thể giải quyết đủ mà không cần AI. |
| 2 | Khó xác định và sửa đúng vấn đề môi trường của từng repository | Đã lặp lại ở nhiều lab; có workflow rõ; ảnh hưởng trực tiếp đến khả năng bắt đầu làm bài. | Chưa đo tần suất và tổng thời gian mất trong một tháng. |
| 3 | Push bài bằng nhầm tài khoản GitHub dẫn đến lỗi quyền truy cập | Có sự cố thật và kết quả trước/sau rõ; bottleneck cụ thể; giải pháp kiểm chứng nhanh. | Pain có thể không đủ lớn với người chỉ dùng một tài khoản GitHub. |

### 2.2. Problem Cards chi tiết

---

#### Problem Card #1 — Chuyển tài liệu lab thành checklist đúng

```text
Problem 1 câu:
Học viên bắt đầu lab phải tự đọc và ghép thông tin từ nhiều tài liệu để biết
chính xác việc cá nhân, việc nhóm và sản phẩm cần nộp.

Actor:
Học viên mới bắt đầu một bài lab.

Thời điểm / bối cảnh:
Ngay sau khi mở bài trên LMS hoặc clone repository.

Current workflow 3-7 bước:
1. Mở nội dung bài trên LMS.
2. Mở README và worksheet trong repository.
3. Tìm các phần nói về output và cách nộp.
4. Đối chiếu với các file mẫu.
5. Hỏi lại giảng viên, bạn học hoặc AI về điểm chưa rõ.
6. Tự viết danh sách việc cần làm.

Bottleneck:
Xác định yêu cầu nào bắt buộc, yêu cầu nào thuộc cá nhân hoặc nhóm,
và thông tin nào là bản mới nhất.

Impact:
Bắt đầu bài chậm và có nguy cơ làm thiếu phần hoặc làm sai phạm vi.

Success metric:
Hiện trạng: lần Day 02 phải đọc repo và hỏi thêm 1 lượt về phần code;
thời gian chưa được đo. Lần tiếp theo bấm giờ từ lúc mở tài liệu đến khi có
checklist. Mục tiêu: dưới 5 phút và không bỏ sót mục nào khi đối chiếu với
checklist chính thức của giảng viên.

Non-AI alternative:
Giảng viên cung cấp checklist một trang gồm việc cá nhân, việc nhóm, file nộp
và tiêu chí hoàn thành.

AI hypothesis:
AI trích yêu cầu thành checklist có dẫn lại file/đoạn nguồn, đồng thời đánh dấu
điểm mâu thuẫn hoặc chưa rõ để người học xác nhận.

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

[Mở LMS] → [Đọc README/worksheet] → [Tìm output và tiêu chí] <-- bottleneck
→ [Hỏi lại] → [Tự lập checklist]

FUTURE STATE — mục tiêu dưới 5 phút

[Chọn nguồn] → [Trích checklist kèm nguồn] → [Đánh dấu điểm mâu thuẫn]
→ [Học viên đối chiếu và xác nhận] <-- human boundary → [Bắt đầu làm]

Fallback: nếu nguồn thiếu hoặc mâu thuẫn, giữ nguyên trích dẫn và hỏi giảng viên;
không tự suy đoán yêu cầu.
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
Pre-push checklist hoặc rule so sánh owner của remote với các tài khoản GitHub
đã đăng nhập, sau đó hiển thị tài khoản cần chọn.

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

[Commit] → [Đọc owner của remote] → [So với tài khoản active]
→ [Học viên xác nhận đổi tài khoản] <-- human boundary
→ [Push] → [Xác minh branch tracking]

Fallback: nếu tài khoản đúng nhưng vẫn thiếu quyền, dừng push và kiểm tra quyền
repository hoặc liên hệ người quản lý repository.
```

---

### 2.3. Card muốn pitch nhất

**Card tôi muốn pitch nhất:**

```text
Card #1 — Chuyển tài liệu lab thành checklist đúng.
```

**Vì sao:**

```text
Pain xuất hiện ngay trong Day 02: người học phải đọc nhiều nguồn và hỏi lại để
biết việc cần làm và có phần code hay không. Workflow rõ, kết quả đo được bằng
thời gian tạo checklist và số yêu cầu bị bỏ sót. Chủ đề phù hợp để so sánh một
process fix đơn giản với workflow có AI.
```

**Câu hỏi tôi muốn nhóm challenge:**

```text
Nếu giảng viên cung cấp checklist chuẩn ngay từ đầu thì pain còn đủ lớn không?
AI tạo thêm giá trị gì so với checklist cố định, và làm sao tránh tóm tắt sai yêu cầu?
```

**AI phản biện Card:**

- Điểm yếu AI chỉ ra: chưa có thời gian baseline; checklist thủ công có thể đã giải quyết đủ vấn đề.
- Tôi sửa gì: ghi rõ cách bấm giờ, yêu cầu đối chiếu với nguồn và giữ phương án không AI để so sánh.

### Self-check nộp phần 01

- [x] Có 5 problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
- [ ] Bổ sung họ tên và mã học viên
- [ ] Bổ sung thời gian baseline sau khi đo
