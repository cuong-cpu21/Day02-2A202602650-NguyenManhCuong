# 02 — Group Problem Statement
## Chủ đề: Xác định yêu cầu hiện hành của bài tập từ nhiều nguồn

> Bản nháp phân tích để nhóm rà soát. Research sản phẩm đã đối chiếu nguồn chính thức ngày 12/09/2026. Đã tổng hợp 15 cards từ 5 thành viên; chưa có biên bản đồng thuận, dữ liệu phỏng vấn gốc, baseline kiểm chứng hoặc kết quả pilot. Problem Statement v0/v1 bên dưới là bản dự thảo trước validation, cần cập nhật sau quan sát thực tế; không phải kết luận đã được kiểm chứng.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò được phân công |
|---|---|---|---|
| 1 | Nguyễn Mạnh Cường | 2A202602650 | Điều phối hội tụ, tổng hợp báo cáo và trình bày |
| 2 | Nguyễn Hồng Thái | 2A202602894 | Phỏng vấn, quan sát người dùng và thu thập bằng chứng |
| 3 | Trần Mạnh Tùng | 2A202602879 | Research giải pháp hiện có và phương án không AI |
| 4 | Đinh Hoàng Đức | 2A202602795 | Workflow trước/sau, điểm can thiệp AI và fallback |
| 5 | Phan Đại Cương | 2A202602510 | Thiết kế đo lường, tổng hợp kết quả và phản biện quyết định |

### Phân công công việc và đầu ra

Đây là kế hoạch thực hiện, không phải ghi nhận các thành viên đã hoàn thành. Chưa đặt ngày giờ bàn giao vì nhóm chưa cung cấp hạn nộp; dùng các mốc phụ thuộc dưới đây.

| Thành viên | Công việc cụ thể | Đầu ra và mục báo cáo | Mốc bàn giao / phối hợp |
|---|---|---|---|
| Nguyễn Mạnh Cường | Thu Top 3 của từng người; điều phối pitch, gom cụm, chấm điểm và ghi ý kiến khác nhau; tổng hợp v0/v1 theo bằng chứng; chuẩn bị phần trình bày | Phase 3: biên bản và bảng score thật; Phase 5.3/6.2: PS cập nhật; bản báo cáo nhóm thống nhất | Thu candidates trước khi chốt bài; tổng hợp sau khi nhận validation, research, workflow và số đo; quyết định cuối do cả nhóm xác nhận |
| Nguyễn Hồng Thái | Tuyển 3 sinh viên để quan sát/phỏng vấn; xin phép dùng thông báo đã ẩn thông tin riêng tư; hỏi về assignment thật, ghi quote và tín hiệu phản bác; phối hợp TA xác minh yêu cầu | Phase 4.1: ba bản ghi P01–P03, nguồn bằng chứng, sự cố thật nếu có; ghi rõ điều chưa xác minh | Thống nhất biểu mẫu với Phan Đại Cương trước quan sát; chuyển dữ liệu và quote cho Cường, Đức sau từng phiên |
| Trần Mạnh Tùng | Rà research Canvas, Classroom, MyStudyLife; đối chiếu chức năng với nguồn chính thức; xây phương án checklist do giảng viên/TA cập nhật để làm đối chứng | Phase 4.2: bảng so sánh có link, phạm vi đã/chưa kiểm tra; mẫu checklist không AI và câu trả lời vì sao cần thêm giải pháp | Hoàn thiện đối chứng trước pilot; chuyển tiêu chí so sánh cho Đức và Phan Đại Cương |
| Đinh Hoàng Đức | Vẽ workflow thực tế từ quan sát của Thái; thiết kế workflow đề xuất, nguồn/phiên bản, xử lý mâu thuẫn; phân biệt Rule, AI và người; chuẩn bị mẫu đầu ra để thử thủ công | Phase 5.1–5.2 và 6.0–6.1: sơ đồ/bảng bước, bottleneck, handoff, boundary, fallback và so sánh các mức giải pháp | Dựng bản giả thuyết trước, sửa theo quan sát; bàn giao kịch bản và checklist mẫu trước pilot; chưa cần code ứng dụng |
| Phan Đại Cương | Chuẩn bị biểu mẫu bấm giờ và cách tính metric; cùng Thái ghi số liệu; đối chiếu kết quả với nguồn được TA xác nhận; so cách hiện tại, checklist và workflow; phản biện chất lượng kết luận | Bảng metric ở Phase 5.2; kết quả pilot nếu đã chạy; Phase 6.3: đề xuất Go/Not Yet/No-Go có căn cứ, lỗi và giới hạn | Chốt cách đo trước quan sát; báo số liệu sau thử nghiệm; gửi kết luận đề xuất cho cả nhóm trước khi Cường hoàn thiện báo cáo |

**Việc chung của cả 5 người:** mỗi người đưa Top 3 cá nhân, tham gia pitch/challenge, rà nguồn và xác nhận quyết định chung; reflection do từng người tự ghi theo đóng góp thực tế. Nhóm 5 người có thể có 15 candidates trước khi gom trùng; ghi đúng số nhận được, không dựng hoặc ép thành 9–12 để khớp mẫu nhóm 3–4 người.

**Thứ tự phối hợp:** thu candidates và chốt hướng → Thái thu bằng chứng, Tùng research, Đức dựng workflow; Phan Đại Cương thống nhất cách đo → cập nhật workflow và thử thủ công nếu đủ dữ liệu → cả nhóm thảo luận quyết định → Cường tổng hợp, cả nhóm rà soát trước nộp.

**Người review trong pilot:** sinh viên tham gia kiểm tra checklist của mình; Thái hỗ trợ lấy xác nhận từ giảng viên/TA khi nguồn mâu thuẫn; Phan Đại Cương đối chiếu kết quả với đáp án đã xác minh. Phân công nội bộ không thay thế sự đồng ý của người tham gia hoặc xác nhận của TA.

**Candidate đang nghiên cứu:** Sinh viên phải đối chiếu yêu cầu và cập nhật của cùng một bài tập trên LMS, email và chat nhưng khó xác định thông tin nào còn hiệu lực, khiến việc chốt checklist nộp bài mất công và có nguy cơ sai.

Đây là chủ đề hiện nhóm đang nghiên cứu và phân công công việc theo yêu cầu của Nguyễn Mạnh Cường. Repo cá nhân đã được cung cấp và tổng hợp tại Phase 3; biên bản pitch/score của cả nhóm chưa được cung cấp; việc đã chọn hướng làm báo cáo không đồng nghĩa đã xác nhận pain hoặc quyết định Go triển khai.

## Phase 3 — Tổng hợp 15 candidates từ bài cá nhân của 5 thành viên

### 3.1. Nguồn đối chiếu và Top 3 từng người

Bản tổng hợp này được lập từ file của các thành viên do Cường cung cấp repo, không phải biên bản ghi lại một buổi pitch đã diễn ra. Đã đọc đủ 15 Problem Cards; giữ C1–C15 để truy vết. “Card muốn pitch nhất” là lựa chọn tác giả ghi trong file, không đồng nghĩa cả nhóm đã bỏ phiếu chọn.

| Nguồn | Thành viên | Bản đọc |
|---|---|---|
| S-LOCAL | Nguyễn Mạnh Cường | [Bản cá nhân được cập nhật cùng commit với báo cáo này](../01-individual-problem-scan/individual-report.md) |
| S-THAI | Nguyễn Hồng Thái | [individual-report.md tại d889649](https://github.com/thaijaor/Day02-2A202602894-NguyenHongThai/blob/d889649a7a06cca995dd36add3440f028016d989/01-individual-problem-scan/individual-report.md) |
| S-TUNG | Trần Mạnh Tùng | [individual-report.md tại 1c28d26](https://github.com/manhtungai247/K4B-Day02-AI-Product-Labs/blob/1c28d261a27ffdce50e65a325bde29b19f851424/01-individual-problem-scan/individual-report.md) |
| S-DUC | Đinh Hoàng Đức | [individual-report.md tại d1e3250](https://github.com/ducdh205/K4B-Day02-2A202602795-DinhHoangDuc/blob/d1e3250d34ea1e12059c99b9ec7fec42ae1f58ab/01-individual-problem-scan/individual-report.md) |
| S-CUONG | Phan Đại Cương | [individual-report.md tại 0818f92](https://github.com/cuongphanhp/K4B-Day02-AI-Product-Labs/blob/0818f92671f15db13df5fd41dbd3ebf8a9bf2254/01-individual-problem-scan/individual-report.md) |

Các liên kết bốn repo được cố định theo commit đã đọc; thay đổi sau đó trên nhánh main không tự thay bằng chứng của bản này. Bốn file group-report.md ở những commit này vẫn là mẫu trống, nên chưa có kết quả validation hoặc quyết định chung bổ sung từ đó.

| ID | Thành viên / card | Candidate — diễn đạt theo vấn đề | Actor | Bottleneck | Nguồn / lựa chọn pitch cá nhân |
|---|---|---|---|---|---|
| C1 | Nguyễn Mạnh Cường #1 | Xác định yêu cầu hiện hành của bài tập từ nhiều nguồn | Sinh viên nhận cùng bài từ nhiều nguồn | Đối chiếu hiệu lực, thẩm quyền và phạm vi cập nhật | S-LOCAL; muốn pitch nhất |
| C2 | Nguyễn Mạnh Cường #2 | Kiểm tra môi trường trước khi làm lab | Học viên Python/Windows | Phân biệt lỗi môi trường với code | S-LOCAL |
| C3 | Nguyễn Mạnh Cường #3 | Phát hiện sai tài khoản GitHub trước khi push | Học viên có nhiều tài khoản | Xác định tài khoản có quyền repo | S-LOCAL |
| C4 | Nguyễn Hồng Thái #1 | Ôn tập tổng hợp kiến thức trước kỳ kiểm tra | Học viên AI20K ôn thi | Nối kiến thức từ note, notebook, slide thành mạch | S-THAI; muốn pitch nhất |
| C5 | Nguyễn Hồng Thái #2 | Đọc hiểu tài liệu/paper kỹ thuật tiếng Anh | Học viên chưa vững nền ML | Dừng tra thuật ngữ/ký hiệu làm đứt mạch đọc | S-THAI |
| C6 | Nguyễn Hồng Thái #3 | Tìm và tổng hợp tài liệu cho bài tập lớn | Học viên làm báo cáo | Lọc nguồn và sắp ý thành dàn bài | S-THAI |
| C7 | Trần Mạnh Tùng #1 | Đánh giá chất lượng và phát hiện ảo giác Chatbot/RAG | Sinh viên AI kiểm định RAG | Đọc đối chiếu câu trả lời với nguồn | S-TUNG; muốn pitch nhất |
| C8 | Trần Mạnh Tùng #2 | Lọc và khử trùng lặp ảnh/video trước gán nhãn | Người phụ trách dữ liệu CV | Xem/lọc thủ công nhiều khung hình tương đồng | S-TUNG |
| C9 | Trần Mạnh Tùng #3 | Đồng bộ tài liệu API Spec giữa AI và Mobile/Frontend | Nhóm backend và bên tích hợp | Tài liệu viết tay lệch schema thực tế | S-TUNG |
| C10 | Đinh Hoàng Đức #1 | Khó theo dõi thông báo chính thức và hướng dẫn cập nhật của chương trình | Học viên VinAI theo mô tả tác giả | Tìm/đối chiếu nhiều nguồn, xác định thông tin chính thức mới nhất | S-DUC; muốn pitch nhất; tên card gốc: “Kênh thông báo và hướng dẫn realtime cho học viên VinAI” |
| C11 | Đinh Hoàng Đức #2 | Sắp xếp lịch họp nhóm | Nhóm học tập | Tổng hợp giờ rảnh từ nhiều tin nhắn | S-DUC |
| C12 | Đinh Hoàng Đức #3 | Ghi chép và phân loại chi tiêu cá nhân | Sinh viên tự quản lý chi tiêu | Phân loại từng giao dịch thủ công | S-DUC |
| C13 | Phan Đại Cương #1 | Tổng hợp thông tin nhiều nguồn để lập kế hoạch học tập | Sinh viên quản lý nhiều task | Tổng hợp, phân tích ưu tiên và lập kế hoạch | S-CUONG; muốn pitch nhất; tên gốc bắt đầu “AI Agent tự động thu thập…” |
| C14 | Phan Đại Cương #2 | Tìm lại thông tin học tập và deadline từ nhiều nền tảng | Sinh viên học/làm nhóm | Tìm kiếm và xác thực thông tin | S-CUONG |
| C15 | Phan Đại Cương #3 | Theo dõi tiến độ và ưu tiên công việc học tập của nhóm | Nhóm sinh viên | Tổng hợp trạng thái để chọn việc tiếp theo | S-CUONG |

C10/C13 được diễn đạt lại theo pain thay vì lấy tên giải pháp làm problem; ý gốc và nguồn vẫn được giữ. Không sửa bài của các thành viên. C1 là Card #1 hiện tại của Cường, không tạo candidate riêng từ bản cũ.

### 3.2. Gom cụm từ 15 cards

| Cụm | Candidates | Điểm chung | Phân biệt cần giữ |
|---|---|---|---|
| A — Thông tin học tập nhiều nguồn | C1, C10, C13, C14 | Phải tìm, tổng hợp và xác thực thông tin trước khi hành động | C1 tập trung hiệu lực; C10 gồm thông báo toàn chương trình; C13 gồm kế hoạch tuần; C14 gồm tìm lại tài liệu |
| B — Đọc hiểu và tổng hợp kiến thức | C4, C5, C6 | Biến tài liệu thành hiểu biết/đầu ra học tập | Ôn thi, đọc paper và viết báo cáo có đầu ra khác nhau; không gộp thành một sản phẩm bao trùm |
| C — Chất lượng và phối hợp kỹ thuật | C2, C3, C7, C8, C9 | Giảm thao tác kiểm tra hoặc sai lệch trong dự án kỹ thuật | Đây là cụm theo bối cảnh, không phải 5 bài trùng nhau; C9 có bài học về nguồn chuẩn áp dụng được cho C1 |
| D — Điều phối và ghi nhận công việc | C11, C12, C15 | Tổng hợp dữ liệu thủ công trước khi quyết định | Lịch họp, giao dịch và tiến độ là ba domain riêng; mỗi bài cần metric riêng |

Mỗi candidate xuất hiện đúng một lần trong bảng phân cụm chính: 4 + 3 + 5 + 3 = 15. Điểm giao nhau giữa C9 và C1 là tài liệu có thể lệch nguồn hiện hành, nhưng không dùng thời gian của C9 làm baseline cho C1.

### 3.3. Shortlist phân tích sau đọc repo

| ID shortlist | Nguồn candidates | Hướng đào sâu | Lý do giữ | Giới hạn |
|---|---|---|---|---|
| S1 | C1, C10, C13, C14 | Xác định yêu cầu hiện hành của một assignment từ nhiều nguồn | Có tín hiệu liên quan ở bài của ba thành viên; đầu ra kiểm được; phạm vi đã được Cường chọn để làm báo cáo | Chưa có cặp thông báo mâu thuẫn và đáp án TA xác nhận; không đồng nhất mất thông báo với xung đột phiên bản |
| S2 | C4, tham chiếu C5/C6 | Nối kiến thức nhiều nguồn để ôn kiểm tra | Là card Thái muốn pitch, workflow rõ và có ước lượng công đọc/nối | Cần đo hiểu bài, không chỉ tốc độ tạo outline; tài liệu tự ghi số ước lượng và có tổng giờ chưa nhất quán |
| S3 | C7 | Đối chiếu câu trả lời RAG với nguồn để đánh giá chất lượng | Là card Tùng muốn pitch, có tiêu chí nguồn và người review | Chưa có benchmark/nhãn độc lập; kiểm mỗi câu được AI gắn cờ có thể bỏ sót lỗi không bị gắn cờ |

**Vì sao chưa đưa các card khác vào shortlist:** C2/C3 có thể xử lý bằng kiểm tra môi trường/quyền; C8 cần dữ liệu ảnh và nhãn ca biên; C9 có phương án nguồn schema chuẩn đáng thử trước AI; C11 có thể dùng poll; C12/C15 có thể bắt đầu bằng bảng dữ liệu chung. Đây là đánh giá phạm vi cho buổi lab, không phải kết luận các pain đó không tồn tại.

**Bảy câu shortlist cho S1:** actor là sinh viên có cùng assignment ở nhiều nguồn; workflow sáu bước; bottleneck là đối chiếu hiệu lực; impact đo được nhưng chưa đo; before/after đã mô tả; so sánh được bốn mức giải pháp; phạm vi nhập tay một bài phù hợp thử trong lab. Bài cá nhân cho thấy các thành viên có trải nghiệm liên quan, chưa chứng minh cả nhóm hiểu sâu mọi nhánh.

### 3.4. Chấm điểm tham khảo và hướng tiếp tục

Điểm dưới đây là đánh giá sơ bộ có AI hỗ trợ từ tài liệu, thang 1–5; không phải điểm các thành viên đã chấm hoặc biểu quyết. Dùng để nhóm challenge, sửa và ký nhận sau. Tiêu chí evidence đánh giá bằng chứng hiện có, không đánh giá sức hấp dẫn của ý tưởng.

| Shortlist | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| S1 | 5 | 5 | 2 | 4 | 4 | 5 | 4 | 29 |
| S2 | 5 | 4 | 2 | 3 | 4 | 5 | 3 | 26 |
| S3 | 5 | 5 | 2 | 4 | 3 | 5 | 2 | 26 |

**Căn cứ theo từng tiêu chí:**

- S1: actor và sáu bước cụ thể (5/5); evidence chỉ là tự thuật liên quan, chưa có xung đột thật (2); metric xác định được nhưng chưa baseline (4); bản thử nhập tay khả thi nhưng cần dữ liệu (4); đủ phương án đối chứng (5); ba thành viên mô tả pain liên quan nhưng chưa xác nhận năng lực toàn nhóm (4).
- S2: actor ôn thi rõ (5); các bước rõ nhưng tổng giờ chưa khớp (4); số tự ước lượng (2); đo chất lượng hiểu bài còn khó (3); thử outline được trong lab (4); có process fix/Rule/Workflow/Agent để so (5); chủ yếu bài của Thái cung cấp ngữ cảnh, chưa có xác nhận các thành viên khác (3).
- S3: actor QA và workflow đối chiếu rõ (5/5); chưa có log/benchmark (2); metric lỗi đo được nếu có nhãn độc lập (4); phụ thuộc tập mẫu và người chấm (3); so được bốn mức (5); nguồn hiện chủ yếu từ Tùng (2).

**Hướng tiếp tục theo yêu cầu người học: S1, giữ C1 làm phát biểu problem chính.** C10 củng cố nhu cầu xác định thông tin chính thức; C14 bổ sung tìm/xác thực; C13 cho thấy bối cảnh đa nguồn nhưng phần ưu tiên/lập lịch tuần được loại khỏi scope. Giữ điểm AI ở trích và gợi ý cập nhật, người học/TA xác nhận hiệu lực. Đây là tổng hợp bằng tài liệu, chưa phải kết luận validation hoặc đồng thuận được ghi biên bản.

**Vì sao chưa ưu tiên S2/S3:** S2 đòi hỏi phép đo hiểu kiến thức ngoài tốc độ đọc; S3 cần benchmark và nguồn kiểm định chưa được cung cấp. S1 có nhiều góc nhìn thành viên liên quan hơn và phù hợp hướng đang làm, nhưng không được dùng điểm tham khảo để bỏ qua tín hiệu phản bác.

**Câu hỏi challenge lấy từ các bài cá nhân:**

- Thái (S-THAI, mục 2.3): metric về hiểu bài/tra lại có khách quan không, và template note có đủ không?
- Đức (S-DUC, mục 2.3): một kênh chính thức có đủ chưa; làm sao tránh tóm tắt sai deadline?
- Tùng (S-TUNG, mục 2.3): ai kiểm định AI chấm AI, và thiên kiến của judge ảnh hưởng thế nào?
- Phan Đại Cương (S-CUONG, mục 2.3): giới hạn nguồn ở đâu; Workflow đã đủ hay cần Agent?
- Cường (S-LOCAL, mục 2.3): có cập nhật thật không, và còn tiết kiệm sau khi tính nhập/review không?

Đây là câu hỏi đã được viết trong repo, không ghi thành lời trao đổi trực tiếp đã diễn ra. Cần cả nhóm xác nhận score, khác biệt ý kiến và quyết định chung.

## Phase 4 — Quick Validation + Research

### 4.1. Pain point, bằng chứng và kiểm chứng

**Pain point chính:** “Tôi đã tìm thấy thông tin của bài tập, nhưng chưa biết thông tin đó còn đúng hay đã bị thay đổi.”

| Thành phần | Mô tả cụ thể | Cần chứng minh bằng gì? |
|---|---|---|
| Actor | Sinh viên có cùng một assignment được thông báo trên ít nhất hai kênh | Assignment và các nguồn thực tế |
| Trigger | Bắt đầu làm, nhận cập nhật hoặc chuẩn bị nộp | Một tình huống gần đây, có ngày |
| Việc cần hoàn thành | Chốt deadline, file bắt buộc, giới hạn nội dung và nơi nộp | Checklist đối chiếu được với nguồn có thẩm quyền |
| Bottleneck | Xác định thông báo nào sửa phần nào, có áp dụng cho đúng lớp/nhóm không | Lịch sử cập nhật và câu hỏi xác nhận |
| Impact giả định | Tốn thời gian đối chiếu, hỏi lại; có thể bỏ sót hoặc theo bản cũ | Thời gian đo, yêu cầu bị bỏ sót, sự cố thật |
| Pain cần tách riêng | Biết rõ deadline nhưng trì hoãn | Nếu đây là nguyên nhân chính thì hướng nghiên cứu hiện tại không phù hợp |

**Phân khúc và số mẫu:** validation ban đầu dự kiến 3 người: 2 sinh viên có assignment ở nhiều nguồn và 1 người chỉ dùng LMS cập nhật nhất quán làm đối chứng định tính. Không chỉ chọn người đã gặp sự cố. Pilot so sánh hiệu quả ở Phase 6 là bước sau, dự kiến 5 sinh viên thuộc phân khúc nhiều nguồn; hai con số phục vụ hai giai đoạn, không phải số người đã khảo sát.

**Nhật ký bằng chứng hiện có:**

| Nguồn | Số người/mẫu | Tín hiệu hỗ trợ | Giới hạn / phản bác | Hệ quả |
|---|---:|---|---|---|
| Trao đổi Day 02 với Nguyễn Mạnh Cường | 1 người, 1 tình huống | Câu hỏi thật: “có phần làm code cá nhân không ?” | Chỉ chứng minh cần làm rõ yêu cầu; không có bằng chứng deadline đổi hoặc nộp sai | Cần quan sát riêng giả thuyết xung đột phiên bản |
| Tài liệu phân tích người học cung cấp | 1 tài liệu | Nêu hướng version conflict, source tracking và human confirmation | Các số 6 phút, 45 giây, điểm 8/10 và ví dụ Marketing là minh họa, không phải khảo sát của nhóm | Không dùng các số này làm baseline hoặc quote khách hàng |
| S-DUC — Card #1 | Bài ghi 4/10 người bỏ lỡ thông báo trong 2 tuần | Tự thuật về kiểm tra nhiều kênh và thông tin chính thức | Chưa nhận phiếu hỏi, ngày hỏi hoặc phản hồi từng người; chưa biết có xung đột phiên bản | Tín hiệu do thành viên báo cáo, cần xin bằng chứng gốc; không coi là mẫu phỏng vấn do bản tổng hợp này thực hiện |
| S-CUONG — Cards #1/#2 | 1 bài cá nhân | Tự thuật 30–60 phút/tuần lập kế hoạch và 10–20 phút/lần tìm lại | Không có log bấm giờ; đơn vị và phạm vi khác thao tác xác nhận một assignment | Hỗ trợ pain phân tán; không dùng làm T0 của S1 |
| S-THAI — Scan #9 | 1 mục trong bài cá nhân | Tự ước lượng tìm thông báo 2–3 lần/tuần | Không nằm trong Top 3 của Thái; chưa có log hoặc ví dụ mâu thuẫn | Bằng chứng bổ sung, không đổi card pitch của tác giả |
| Interview nhóm có dữ liệu gốc | Chưa nhận | Có tự thuật trong S-DUC như trên | Chưa có quote độc lập/biên bản để kiểm tra | Thái bổ sung dữ liệu đã có hoặc thực hiện quan sát theo kịch bản |
| Survey/poll nhóm có dữ liệu gốc | Chưa nhận | Chưa có bản trả lời kèm theo | Không thể xác nhận mẫu từ một dòng tự thuật | Xin nguồn S-DUC trước khi quyết định cần khảo sát thêm |
| Pilot có kết quả cung cấp | 0 | Chưa nhận kết quả | Chưa biết hiệu quả | Quyết định đề xuất: Not Yet |

**Rà chất lượng số liệu nguồn trước khi dùng:**

- Thái tự ghi số liệu là ước lượng. Card ôn tập nêu 5–6 giờ nhưng các bước cộng 6,5 giờ; future cộng 2 giờ 50 phút, ghi xấp xỉ 3 giờ. Không chọn một số rồi coi là baseline đã đo.
- Tùng Card RAG ghi 150 phút nhưng các bước 10 + 120 + 15 + 15 = 160 phút; mục tiêu trên 95% phát hiện lỗi chưa có benchmark xác nhận. Không kế thừa lời khẳng định “100%” của phương án API thành bảo đảm.
- Phan Đại Cương Card #1 ghi 60 phút nhưng các bước cộng 65; Card #2 nêu 10–20 phút trong impact nhưng workflow ghi 25; mục tiêu dưới 3 phút và future 8 phút chưa thống nhất phạm vi. Cần tác giả xác nhận trước khi dùng số.
- Đức Card #1 future 5 phút bao gồm công ban tổ chức review và gửi thông báo, khác actor/phạm vi với thời gian sinh viên kiểm tra mỗi ngày. Chưa thể kết luận tiết kiệm từ hai số đó.
- Những điểm này không phủ nhận pain; chúng là lý do giữ số liệu nguồn ở mức tự thuật/ước lượng và đo baseline riêng cho S1. Bài của thành viên chỉ được tham chiếu, không bị sửa trong repo của họ.

**Kịch bản phỏng vấn/quan sát đề xuất — 3 người, khoảng 10–15 phút/người:**

1. Xin phép ghi chép; chỉ sử dụng thông báo học tập đã ẩn thông tin cá nhân.
2. Hỏi: “Bạn mở assignment gần nhất và tìm deadline, các file bắt buộc, giới hạn bài và nơi nộp giúp mình.”
3. Bấm giờ từ lúc bắt đầu tìm đến lúc người tham gia chốt câu trả lời; ghi số nguồn mở, lần hỏi người khác và trường không xác định được.
4. Hỏi: “Lần gần nhất yêu cầu thay đổi là khi nào? Bạn phát hiện bằng cách nào? Cho xem thông báo nếu có.”
5. Hỏi: “Nếu hai nguồn khác nhau, bạn xác nhận với ai? Lần đó có hậu quả thực tế gì?”
6. Hỏi: “Trong bốn tuần gần đây có bao nhiêu bài và bao nhiêu lần cần đối chiếu cập nhật? Có lần nào biết deadline nhưng vẫn trì hoãn không?”
7. Hoàn tất quan sát cách làm hiện tại và ghi baseline trước khi giới thiệu phương án hỗ trợ. Nếu cho xem mẫu để lấy ý kiến thì chỉ ghi nhận phản hồi định tính; không dùng lượt xem thử này làm phép đo so sánh vì người tham gia đã biết đáp án. Pilot có đổi thứ tự ở Phase 6.

**Form ghi nhận ngay trong báo cáo:**

| Mã | Assignment / số nguồn | Thời gian tìm / chờ xác nhận | Trường thiếu/sai | Mâu thuẫn thật? | Quote nguyên văn | Xác nhận của giảng viên/TA |
|---|---|---|---|---|---|---|
| P01 | Chưa thu thập | Chưa đo | Chưa xác định | Chưa xác định | Chưa có | Chưa có |
| P02 | Chưa thu thập | Chưa đo | Chưa xác định | Chưa xác định | Chưa có | Chưa có |
| P03 | Chưa thu thập | Chưa đo | Chưa xác định | Chưa xác định | Chưa có | Chưa có |

**Insight từ tổng hợp repo:** Cường, Đức và Phan Đại Cương có mô tả liên quan tới yêu cầu/thông tin đa nguồn; Đức nêu nhu cầu xác nhận thông tin mới nhất và chính thức. Tuy vậy, chưa có bộ thông báo mâu thuẫn cùng một assignment để kiểm tra, nên evidence mới hỗ trợ pain liên quan, chưa xác nhận tần suất hoặc nguyên nhân “phiên bản mới nhất”. Cần ưu tiên xin nguồn tự thuật của Đức trước khi bổ sung mẫu.

### 4.2. Research giải pháp đã có

Đã kiểm tra trang chính thức ngày 12/09/2026; đây là mô tả công khai của nhà cung cấp, chưa phải kiểm thử trực tiếp sản phẩm. Không suy ra tính năng không tồn tại chỉ vì trang giới thiệu không nêu.

| Giải pháp / nguồn | Bước đã hỗ trợ theo nguồn | Điểm mạnh | Điều còn phải kiểm tra | Bài học |
|---|---|---|---|---|
| [Canvas — Instructure](https://www.instructure.com/canvas) | Ứng dụng sinh viên có to-do, calendar và nộp bài; ứng dụng giảng viên cho đổi due date | Tập trung công việc và thông báo trong môi trường lớp | Đối chiếu một cập nhật ngoài Canvas với thông tin trong Canvas trên cùng assignment chưa được xác minh trong nghiên cứu này | Nếu thông tin chính thức đã được cập nhật đủ trong LMS, lợi ích bổ sung có thể thấp |
| [Google Classroom — Google for Education](https://edu.google.com/workspace-for-education/products/classroom/) | Trang giới thiệu nêu interactive to-do lists và automatic due dates | Hỗ trợ tổ chức công việc trong lớp | Chưa kiểm thử tình huống email/chat ngoài lớp mâu thuẫn với assignment | Không dùng chức năng nhắc hạn làm điểm khác biệt chính |
| [MyStudyLife](https://mystudylife.com/) | Theo dõi bài tập, nhắc việc, AI study coach; trang liệt kê đồng bộ lịch gồm Canvas và Blackboard | Bao phủ nhiều nhu cầu lập kế hoạch học tập | Phạm vi sync và khả năng truy vết/giải quyết mâu thuẫn giữa nguồn chưa kiểm thử; không khẳng định sản phẩm thiếu tính năng này | Phải so sánh trên cùng bộ thông báo và tính cả công đưa dữ liệu vào |
| Bảng yêu cầu chuẩn do giảng viên/TA duy trì — phương án quy trình do nhóm đề xuất | Ghi một dòng cho mỗi assignment và lịch sử thay đổi | Ít công cụ, người có thẩm quyền chịu trách nhiệm cập nhật | Cần biết người phụ trách có duy trì đều không | Đây là đối chứng bắt buộc trước khi chọn AI |

**Research takeaway:** các công cụ đã phục vụ lập kế hoạch và deadline. Khoảng khác biệt cần thử là giúp đối chiếu yêu cầu có nguồn, phát hiện bản thay đổi và giữ nguyên trạng thái chưa chắc. Chưa có căn cứ khẳng định đây là khoảng trống thị trường, sinh viên sẽ trả tiền hoặc đối thủ không làm được.

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow giả định

```text
Sinh viên nhận bài → tìm các nguồn → trích thông tin → đối chiếu hiệu lực [bottleneck]
→ hỏi giảng viên/TA nếu chưa rõ [handoff] → chốt checklist
```

| Bước | Actor | Input → Output | Thời gian / tần suất | Handoff / rủi ro |
|---|---|---|---|---|
| 1. Xác định bài | Sinh viên | Môn/lớp/tên bài → đúng assignment | t1, chưa đo; mỗi lần chốt yêu cầu | Nhầm bài cùng tên hoặc lớp khác |
| 2. Tìm nguồn | Sinh viên | LMS/email/chat → tập thông báo | t2, chưa đo | Nguồn bị bỏ sót |
| 3. Trích yêu cầu | Sinh viên | Thông báo → các trường cần nộp | t3, chưa đo | Thiếu file, giờ hoặc múi giờ |
| 4. Đối chiếu phiên bản | Sinh viên | Giá trị + tác giả + thời điểm → bản hiện hành hoặc mâu thuẫn | t4, chưa đo | Bottleneck; mới hơn không đồng nghĩa có thẩm quyền hơn |
| 5. Xác nhận | Sinh viên và giảng viên/TA | Câu hỏi + nguồn → xác nhận hoặc chưa giải quyết | t5 thao tác và w5 chờ, chưa đo | Handoff; AI không thể thay người có thẩm quyền |
| 6. Lập checklist | Sinh viên | Các trường đã xác nhận → checklist | t6, chưa đo | Ghi nhầm hoặc dùng checklist cũ |

Tổng thời gian thao tác T0 = t1 + ... + t6. Thời gian chờ W0 = w5, báo riêng; tần suất phải đo theo số assignment thực tế trong bốn tuần gần nhất.

**Bottleneck:** đối chiếu một thông báo với đúng assignment, phạm vi áp dụng và nguồn có thẩm quyền. Nếu mọi thông báo nhất quán, bước này có thể rất ngắn; nếu cần hỏi TA, thời gian chờ có thể lớn hơn công đọc tài liệu.

### 5.2. Future workflow đề xuất

```text
1. Sinh viên chọn đúng bài và đưa các nguồn liên quan đã ẩn dữ liệu riêng tư
→ 2. Rule kiểm tra metadata, nguồn trùng và mã bài
→ 3. AI trích từng yêu cầu kèm nguyên văn/nguồn
→ 4. Rule so giá trị; AI gợi ý liên hệ giữa các cập nhật
→ 5. Sinh viên review; hỏi TA khi mâu thuẫn [human boundary / handoff]
→ 6. Sinh viên xác nhận checklist, lưu dấu thời điểm và bộ nguồn đã kiểm tra

Có cập nhật mới → quay lại bước 2–5 cho trường bị ảnh hưởng; giữ lịch sử cũ.
Fallback: trích sai/thiếu nguồn → mở nguồn gốc, sửa tay;
chưa xác nhận được → giữ “cần xác minh”, không chốt deadline thay người dùng.
```

Thời gian mỗi bước f1–f6 và thời gian chờ W1 đều chưa đo. F1 phải tính cả công chọn, sao chép, ẩn thông tin và nhập nguồn; F5 phải tính công review/sửa. Tổng T1 = f1 + ... + f6. Không dùng riêng thời gian model trả lời để tuyên bố tiết kiệm.

**Bản ghi mỗi trường:** mã bài/lớp; tên trường; giá trị gốc; giá trị chuẩn hóa nếu đủ dữ kiện; trích dẫn; nguồn; tác giả/vai trò; thời điểm thông báo; thời điểm thu thập; phạm vi áp dụng; người xác nhận và thời điểm xác nhận.

**Quy tắc hiệu lực và độ tin cậy:**

- Timestamp mới hơn chỉ là tín hiệu. Tin của sinh viên không tự ghi đè thông báo giảng viên.
- Cập nhật phải đúng assignment, lớp/nhóm và trường được sửa. Đổi deadline không tự xóa yêu cầu file trong bản trước.
- “Tuần sau”, thiếu múi giờ hoặc thiếu thời điểm gốc phải ghi chưa rõ; không tự đoán ngày.
- Một nguồn không nhắc appendix chưa đủ để kết luận appendix bị bỏ; phân biệt thiếu thông tin với hai chỉ dẫn trái nhau.
- “Có nguồn, chờ duyệt”: đã trích được thông tin nhưng người học chưa xác nhận.
- “Mâu thuẫn”: có giá trị/chỉ dẫn không tương thích cần xác minh.
- “Có thể cũ”: có ứng viên cập nhật liên quan nhưng chưa xác nhận bản nào thay thế.
- “Thiếu thông tin”: không có dữ liệu đủ để trả lời.
- “Đã xác nhận”: người học ghi nhận đã đối chiếu; nếu có mâu thuẫn, phải lưu căn cứ từ giảng viên/TA hoặc quy định chính thức.
- Không dùng điểm confidence của model làm bằng chứng đúng. Mọi trạng thái chỉ có giá trị với tập nguồn đã cung cấp và thời điểm kiểm tra.

**Before/after — mục tiêu thử nghiệm, chưa phải kết quả:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---|---|---|
| Thời gian thao tác | T0 chưa đo | Trung vị giảm ít nhất 30% so với cách hiện tại và không chậm hơn checklist chuẩn | Tính từ tìm/nhập nguồn đến chốt, gồm cả sửa lỗi |
| Thời gian chờ TA | W0 chưa đo | W1 báo riêng, không mặc định giảm | Ghi lúc hỏi và lúc nhận xác nhận |
| Sai/thiếu trường bắt buộc | Chưa đo | Không có trường bắt buộc sai/thiếu trong checklist cuối của mẫu pilot | Đối chiếu đáp án do người có thẩm quyền xác nhận |
| Mâu thuẫn bị bỏ sót | Chưa đo | Phát hiện toàn bộ mâu thuẫn đã gán nhãn trong mẫu nhỏ | Ghi TP/FN/FP và mẫu số; báo thêm cảnh báo sai |
| Truy vết nguồn | Chưa đo | Mọi trường được điền có trích dẫn kiểm được | Mở từng nguồn, so nội dung |
| Số bước | 6 bước mô hình hóa, chưa quan sát | 6 bước; tự động hỗ trợ bước 2–4 | Đếm trên phiên thử; không coi ít bước là mục tiêu chính |
| Bước con người thao tác | 6 trong mô hình trước | Ít nhất bước 1,5,6; tăng nếu phải sửa | Nhật ký thao tác và thời gian thực |
| Risk mới | Tự đọc nhầm | Tin AI quá mức, ghép nhầm bài, bỏ nguồn | Review song song, chưa rõ thì hỏi TA |

**Quy ước tính thống nhất:** tính trung vị thời gian theo từng phương án; mức giảm = (median(T0) − median(T1)) / median(T0), chỉ tính khi median(T0) > 0. Đối chiếu thêm median(T1) ≤ median(Tc). Báo thời gian chờ và công vận hành checklist riêng; không tuyên bố tiết kiệm tổng thể nếu chỉ chuyển công từ sinh viên sang TA.

**Chấm chất lượng:** ghi số trường đúng/sai/thiếu trên tổng trường bắt buộc, đồng thời ghi cả lỗi bản nháp AI và lỗi còn lại sau review. TP là mâu thuẫn báo đúng, FN là mâu thuẫn bỏ sót, FP là cảnh báo sai. Nếu mẫu không có mâu thuẫn thật thì chỉ số phát hiện mâu thuẫn là “chưa đánh giá được”, không ghi đạt 100%; cần bổ sung mẫu phù hợp trước khi kết luận. “Chưa rõ” chỉ được tính đúng khi đáp án độc lập cũng chưa xác định được; nếu đáp án đã có mà hệ thống bỏ trống thì tính thiếu. Case mô phỏng chỉ báo riêng để kiểm tra hành vi.

### 5.3. Problem Statement v0 — dự thảo trước validation

| Field | Nội dung |
|---|---|
| Actor | Sinh viên nhận thông tin cùng một assignment từ ít nhất hai nguồn, đặc biệt khi có cập nhật. Mức độ phổ biến của pain chưa được xác nhận. |
| Workflow | Tìm thông báo, đọc yêu cầu, đối chiếu và lập checklist. Khi chưa rõ, hỏi bạn hoặc giảng viên/TA. |
| Bottleneck | Thông tin rải rác và các cập nhật khó ghép thành yêu cầu hiện hành. Cần quan sát xem mất công nhất ở tìm nguồn hay xác nhận hiệu lực. |
| Impact | Có thể mất thời gian hoặc bỏ sót phần nộp. Chưa có số đo hay bằng chứng nộp trễ do nguyên nhân này. |
| Success Metric | Đo T0/T1, số trường sai/thiếu và khả năng phát hiện mâu thuẫn. Các mục tiêu ở bảng trên cần nhóm chốt trước thử nghiệm. |
| Boundary | Chỉ hỗ trợ đọc yêu cầu của bài tập đã được người học chọn. Người có thẩm quyền xác nhận yêu cầu, người học xác nhận checklist. |

**Phản biện và sửa đề xuất:** v0 đã theo C1 hiện tại nhưng còn thiếu quy tắc hiệu lực, điểm AI can thiệp và trách nhiệm xác nhận. V1 bổ sung các chi tiết này, phạm vi văn bản nhập tay và cách đo tính cả công nhập/review. V0/v1 là hai mức đặc tả của cùng chủ đề, không quay lại Card #1 cũ và chưa phải insight rút ra từ phỏng vấn.

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp

- Độ mơ hồ: cao ở ngôn ngữ cập nhật và phạm vi áp dụng; kết quả cuối vẫn phải đối chiếu được, không phải câu trả lời sáng tạo.
- Độ phức tạp: cao trong trường hợp nhiều nguồn và phiên bản phụ thuộc nhau; workflow triển khai vẫn giới hạn, có các nhánh biết trước.
- Suy luận: AI có thể hỗ trợ trích nghĩa; mức độ phức tạp không tự tạo nhu cầu Agent.

### 6.1. So sánh trên cùng bài toán

| Mức | Phương án | Khi nào đủ | Rủi ro | Lựa chọn |
|---|---|---|---|---|
| No AI / process fix | Giảng viên/TA duy trì bảng yêu cầu chuẩn có ngày cập nhật | Một nguồn được duy trì đầy đủ | Phụ thuộc người cập nhật | Đối chứng ưu tiên |
| Rule | Form trường cố định, kiểm tra thiếu, so ngày/giá trị và lưu lịch sử | Đầu vào đã cấu trúc | Regex khó hiểu ngữ cảnh cập nhật tự do | Dùng cho chuẩn hóa/kiểm tra |
| Workflow | Nguồn nhập tay → AI trích có nguồn → Rule so → người review | Nhiều thông báo tự do nhưng đường xử lý xác định | Bịa trường, bỏ nguồn, review tốn công | Đề xuất thử nếu validation đạt |
| Agent | Tự tìm qua tài khoản, lập kế hoạch tra cứu và cập nhật task | Chỉ cân nhắc nếu pilot chứng minh cần truy tìm động | Quyền dữ liệu rộng, hành động sai, khó kiểm soát | Chưa chọn |

**5 câu hỏi chốt:**

1. **Rule giải 70–80% case không?** Chưa có tập case nên chưa thể nói tỷ lệ. Cần thử Rule/checklist và AI trên cùng bộ nguồn; nếu Rule đủ thì chọn Rule.
2. **Đi thẳng hay rẽ nhánh?** Có nhánh thiếu nguồn, trùng bài, thông tin mới và mâu thuẫn. Các nhánh này có thể thiết kế trước trong workflow.
3. **Có cần Agent tự lập kế hoạch/gọi tool?** Chưa. Pilot dùng nội dung người học tự cung cấp và một trình tự cố định.
4. **AI sai ai phát hiện, sửa bao lâu?** Sinh viên review nguồn trước khi dùng; người đánh giá đối chiếu đáp án độc lập. Thời gian sửa phải đo; pilot đặt giới hạn một lượt sửa, nếu vẫn chưa rõ thì xử lý thủ công/hỏi TA.
5. **Có hạ mức không?** Có. Khi một nguồn chuẩn đáp ứng đủ, dùng bảng checklist; khi đầu vào cấu trúc, dùng Rule; chỉ giữ AI cho phần chứng minh được lợi ích.

**Mức đề xuất: Workflow có Rule + AI extraction + người xác nhận.** Chọn theo dạng đầu vào tự do và nhu cầu giữ nguồn. Chưa có kết quả chứng minh vượt phương án đơn giản hơn, nên lựa chọn này là giả thuyết thử nghiệm.

### 6.2. Problem Statement v1 — dự thảo đã thu hẹp

> Với sinh viên nhận các cập nhật cho cùng một assignment từ nhiều kênh, bước đối chiếu thông báo để chốt yêu cầu hiện hành có thể gây mất công và sai sót. Nhóm sẽ kiểm chứng một workflow hỗ trợ trích yêu cầu có nguồn, phát hiện thay đổi/mâu thuẫn và để người học xác nhận, so với cách hiện tại và checklist chuẩn.

| Field | Nội dung |
|---|---|
| Actor | Sinh viên có ít nhất hai nguồn liên quan cùng assignment, đặc biệt khi có cập nhật. Không mặc định mọi sinh viên đều gặp pain này. |
| Workflow | Tập hợp nguồn → trích các trường → đối chiếu hiệu lực → xác nhận → chốt checklist. Khi có cập nhật, review lại trường bị ảnh hưởng. |
| Bottleneck | Xác định chỉ dẫn nào còn áp dụng với đúng lớp/bài, dựa trên nội dung, thẩm quyền và lịch sử; timestamp không đủ để kết luận. |
| Impact | Thời gian thao tác, thời gian chờ và số trường sai/thiếu; hậu quả nộp sai chỉ ghi nếu có sự cố thật. |
| Success Metric | Baseline chưa đo. Mục tiêu pilot: giảm trung vị thời gian thao tác ít nhất 30% so với hiện tại, không chậm hơn checklist chuẩn; không sai/thiếu trường bắt buộc trong mẫu cuối; phát hiện đủ mâu thuẫn đã gán nhãn, báo cảnh báo sai; mọi trường có nguồn. |
| Boundary — làm | Pilot một assignment/lượt từ văn bản do người học chọn; trích deadline kèm timezone nếu có, deliverables, định dạng, giới hạn, nơi nộp, cá nhân/nhóm; giữ lịch sử và trạng thái. |
| Boundary — không làm | Không đọc tự động toàn bộ inbox/chat; không xử lý thông báo miệng chưa có xác nhận; chưa tích hợp OCR hoặc LMS API; không tự quyết deadline, sửa lịch, gửi tin hay nộp bài. |
| AI intervention point | Sau khi chọn nguồn và trước so sánh/duyệt: trích trường + trích dẫn, gợi ý thông báo có liên quan. Rule kiểm tra cấu trúc/giá trị; người học xử lý phần chưa chắc. |
| Mức chọn | Workflow thử nghiệm, vì các bước và nhánh đã biết; không cần quyền tự hành của Agent. |
| Rủi ro và review | Ghép nhầm assignment, cập nhật sai phạm vi hoặc chốt sai deadline. Người học mở nguồn; mâu thuẫn cần căn cứ từ giảng viên/TA; người đánh giá dùng đáp án độc lập. |

### 6.3. Final decision — đề xuất để nhóm xác nhận

| Câu hỏi | Yes / Not Yet / No | Lý do |
|---|---|---|
| Actor + workflow rõ? | Yes ở mức giả thuyết | Có phân khúc và mô hình sáu bước; cần quan sát để xác nhận |
| Baseline + metric đo được? | Not Yet | Có định nghĩa và cách đo nhưng chưa có dữ liệu |
| Data/input đủ? | Not Yet | Chưa có bộ assignment thật được phép dùng và đáp án |
| AI sai, hậu quả chấp nhận được? | Not Yet | Có thiết kế review; chưa kiểm chứng khả năng phát hiện lỗi |
| Có người review/owner? | Yes — đã phân công nội bộ | Cường tổng hợp; Thái thu bằng chứng và liên hệ TA; Phan Đại Cương đối chiếu kết quả. Người tham gia và TA cung cấp xác nhận độc lập chưa được tuyển/xác nhận |
| Có cách non-AI đơn giản hơn? | Yes | Checklist nguồn chuẩn và Rule là đối chứng |

**Decision đề xuất: Not Yet.** Các bài cá nhân của Cường, Đức và Phan Đại Cương bổ sung tín hiệu về thông tin đa nguồn, nhưng chưa có dữ liệu gốc xác nhận mâu thuẫn phiên bản của cùng assignment. Tuy nhiên, ví dụ trong tài liệu không chứng minh tần suất xung đột, lợi ích đo được hoặc sẵn sàng dùng. Research đối thủ cũng chưa chứng minh khoảng trống. Cần validation trước khi Go xây sản phẩm; nhóm vẫn có thể tiến hành quan sát và thử thủ công để thu thập bằng chứng.

**Cần làm trước khi chốt:**

1. Cả nhóm rà 15 cards, bốn cụm và ba shortlist đã tổng hợp từ repo; xác nhận hoặc sửa điểm tham khảo, bổ sung biên bản đồng thuận. Không cần thu lại Top 3 đã có.
2. Phỏng vấn/quan sát tối thiểu 2–3 người hoặc survey 5–10 người; ưu tiên 3 phiên quan sát có assignment thật.
3. Nhận bộ nguồn đã ẩn dữ liệu cá nhân, xác định người có thẩm quyền làm đáp án.
4. Đo baseline; kiểm tra pain do đối chiếu cập nhật hay do trì hoãn.
5. Nhóm chốt mục tiêu pilot và quyết định cuối theo dữ liệu; xác nhận người tham gia/TA phối hợp với các reviewer nội bộ đã được phân công.

**Pilot nhỏ nhất nếu validation ủng hộ:**

- Đề xuất 5 sinh viên trong phân khúc, mỗi người xử lý 3 assignment chưa biết đáp án và có độ khó tương đương; mỗi assignment dùng một trong 3 phương án. Đổi thứ tự phương án và luân phiên gán bộ bài giữa người tham gia; không cho cùng người xử lý lại một bài đã biết đáp án. Tổng dự kiến 15 lượt, 5 lượt/phương án; báo giới hạn mẫu nhỏ và khả năng khác biệt độ khó còn sót lại.
- So ba cách: hiện tại (T0), checklist chuẩn không AI (Tc) và workflow hỗ trợ (T1). Giữ cùng phạm vi yêu cầu và quyền truy cập thông tin. Tính cả công chuẩn bị/nhập nguồn; công giảng viên/TA tạo và cập nhật checklist là chi phí vận hành đối chứng, phải báo riêng theo bài. Công chuẩn bị đáp án để chấm cả ba cách ghi riêng, không cung cấp đáp án cho người tham gia ngoài nội dung của phương án đang thử.
- Dùng xử lý thủ công hoặc công cụ AI hiện có theo bộ nguồn đã chọn; chưa cần code ứng dụng.
- Đáp án do giảng viên/TA hoặc người đánh giá được họ xác nhận lập trước. Nếu chưa xác minh được một trường, đáp án hợp lệ là “chưa rõ”, không đoán.
- Ba nhóm số chính: thời gian thao tác/chờ; trường sai hoặc bỏ sót; TP/FN/FP khi phát hiện mâu thuẫn. Kiểm tra truy vết nguồn là điều kiện bổ sung.
- Case mô phỏng như hai deadline khác nhau chỉ dùng kiểm tra hành vi, gắn nhãn “synthetic”; tách hoàn toàn khỏi bằng chứng nhu cầu và tần suất pain.
- Trong pilot, một lỗi deadline bị hệ thống chốt sai hoặc một nguồn bị bịa là lý do dừng, sửa và kiểm tra lại trước khi dùng. Qua mẫu nhỏ không có nghĩa hệ thống không bao giờ sai.

**Điều kiện đề xuất Go:** dữ liệu thật cho thấy pain lặp lại, workflow giảm công sau khi tính nhập/review và đạt ngưỡng chất lượng đã chốt. Mẫu nhỏ chỉ cho phép Go thử tiếp, chưa đủ để triển khai rộng.

**Điều kiện No-Go hoặc đổi hướng:** người dùng chủ yếu chỉ cần một LMS; thông tin đã nhất quán; pain chủ yếu do trì hoãn; hoặc checklist chuẩn đạt cùng độ chính xác với ít công hơn. Khi đó dùng process fix/Rule và ghi nhận lý do loại AI.

**Exit / rollback:** giữ lại nguồn gốc và bản người dùng đã xác nhận. Nếu trích sai, thiếu nguồn hoặc có cập nhật chưa giải quyết thì bỏ kết quả chưa duyệt, quay về đối chiếu thủ công; checklist đã xác nhận trước đó phải được đánh dấu cần kiểm tra lại nếu có cập nhật liên quan.

## Checklist trước khi nộp

- [x] Có đủ tên/mã của 5 thành viên và vai trò được phân công.
- [ ] Cập nhật đóng góp thực tế sau khi thực hiện; không coi phân công là hoàn thành.
- [x] Có 15 cards có nguồn, cluster, shortlist và score tham khảo kèm lý do.
- [ ] Có biên bản pitch/challenge và đồng thuận thực tế của cả nhóm.
- [ ] Có interview/survey thật với quote hoặc dữ liệu có nguồn.
- [x] Có research ba sản phẩm với link chính thức và giới hạn kết luận.
- [x] Có workflow trước/sau, bottleneck, handoff, boundary và fallback ở mức thiết kế.
- [ ] Có thời gian baseline và số đo thử nghiệm; hiện mới có cách đo/mục tiêu.
- [x] Có PS v0/v1 dự thảo và so sánh No AI/Rule/Workflow/Agent.
- [ ] Cập nhật PS sau validation và xác nhận quyết định chung; bổ sung người tham gia/TA xác minh đáp án. Reviewer nội bộ đã có phân công.

## Cách đóng gói

Bản nhóm có thể nằm toàn bộ trong file này. Sơ đồ, bảng dữ liệu và ghi chép phỏng vấn có thể đặt trực tiếp tại các mục tương ứng; ảnh/ghi âm/tài liệu phụ nếu có mới cần file đính kèm đã được phép chia sẻ. Mỗi thành viên đưa cùng bản nhóm cuối vào repo cá nhân; reflection vẫn viết riêng theo đóng góp thực tế.
