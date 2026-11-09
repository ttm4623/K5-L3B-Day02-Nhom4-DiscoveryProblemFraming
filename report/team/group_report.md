# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản tổng hợp từ bốn báo cáo cá nhân. Các báo cáo chưa ghi nhận biên bản họp CP3–CP6, phỏng vấn/survey hay quyết định chung; vì vậy những nội dung dưới đây là **đề xuất làm việc**, không khẳng định nhóm đã thực hiện hoặc đồng thuận. Nhóm cần xác nhận các mục được đánh dấu trước khi nộp.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhóm 4
- Thành viên: Triệu Tuấn Minh, Nguyễn Văn Minh, Phạm Ngọc Long, Nguyễn Công Huy (chi tiết trong `TEAM.md`)
- Candidate problem được đề xuất: Học viên K5 L3B mất thời gian đối chiếu yêu cầu nộp lab nằm rải rác trong nhiều tài liệu, nên cần một checklist thống nhất và các kiểm tra Rule cho lỗi hình thức.
- Quyết định cuối: **Not Yet** — chưa có kiểm chứng nhóm hoặc pilot để kết luận nhu cầu và hiệu quả.

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

Các ý dưới đây là top 3 trong từng báo cáo cá nhân, không phải biên bản pitch. Cột câu hỏi ghi câu hỏi trong bài cá nhân nếu có, kèm người hỏi khi đã được thành viên xác nhận; các ô còn lại chưa có ghi nhận.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Triệu Tuấn Minh | Khi ra trường, tôi muốn thi lái xe máy để đi lại và xin việc | Bản thân | Đi xe bus, ghi 45 phút ngồi trên xe | Chưa ghi nhận |
| 2 | Triệu Tuấn Minh | Khi đi học Vin, tôi muốn đi xe máy để bố mẹ đỡ lo và tự tin khi đi làm | Bản thân | Đi xe bus, ghi 45 phút ngồi trên xe | Chưa ghi nhận |
| 3 | Triệu Tuấn Minh | Khi đi học AI ở Vin, tôi muốn đi xe máy để thoải mái hơn khi ăn uống | Bản thân | Bước ăn trưa, ghi 60 phút; quan hệ với job chưa rõ | Chưa ghi nhận |
| 4 | Nguyễn Văn Minh | Khi tự học chương kỹ thuật khó, tôi muốn được giảng đúng phần Toán nền để hoàn thành chương trong một buổi | Người tự học tài liệu kỹ thuật nặng Toán | Tra cứu nguồn ngoài 45–90+ phút/chương | Có hỏi nhóm về số lần và thời gian phải tra lại; người hỏi chưa ghi. Phạm Ngọc Long hỏi: "Các chatbot hiện nay đã đủ để tóm tắt sách, tài liệu rồi, tại sao vấn đề vẫn hiện hữu?" |
| 5 | Nguyễn Văn Minh | Khi agent tạo diagram Simulink rối, tôi muốn dọn dây theo chuẩn để đọc/review nhanh hơn | Người dùng diagram Simulink do agent tạo | Dọn dây thủ công 30 phút/file | Chưa ghi nhận |
| 6 | Nguyễn Văn Minh | Khi làm figure cho bài journal bằng agent, tôi muốn sửa layout để không mất 2–3 giờ | Người viết bài journal dùng agent | Sửa layout/legend 2–3 giờ/lần | Chưa ghi nhận |
| 7 | Phạm Ngọc Long | Khi cuối tháng, tôi muốn biết tiền đã đi vào nhóm chi tiêu nào để quyết định khoản cần cắt | Cá nhân lập ngân sách | Thống kê chi tiêu thủ công, ghi 60 phút | Chưa ghi nhận |
| 8 | Phạm Ngọc Long | Khi chuẩn bị nộp lab lên GitHub/LMS, tôi muốn biết mục nào thiếu hoặc sai hình thức để không bị trừ điểm | Học viên K5 L3B nộp lab | Đối chiếu yêu cầu ở nhiều file, ghi 20 phút/lần | Người đề xuất hỏi: "Các bạn có gặp vấn đề tương tự như mình mỗi khi nộp bài không?" Triệu Tuấn Minh trả lời: "Các yêu cầu nộp bài lab không quá khó, tôi cảm thấy vấn đề này không áp dụng cho tôi" |
| 9 | Phạm Ngọc Long | Khi viết daily standup buổi sáng, tôi muốn tổng hợp việc từ commit và slide để không bỏ sót | Học viên phải nộp daily standup | Tra commit ở nhiều repo, ghi 20 phút/ngày (tổng 47 phút/sáng) | Không được pitch (người đề xuất pitch card soát bài); chưa ghi nhận |
| 10 | Nguyễn Công Huy | Khi làm project intent-classification, tôi muốn hiểu Bayesian Network và NLP để hoàn thành project | Bản thân | Đọc hiểu lý thuyết, 1–2 giờ | Hỏi nguyên nhân là thiếu nền lý thuyết hay chưa biết áp dụng; người hỏi chưa ghi |
| 11 | Nguyễn Công Huy | Khi viết nghiên cứu so sánh biến thể Gradient Descent, tôi muốn tìm nguồn để trích dẫn | Bản thân/người làm nghiên cứu | Tìm nguồn, khoảng 15–20 phút (quy trình nháp ghi 30 phút) | Chưa ghi nhận |
| 12 | Nguyễn Công Huy | Khi dùng lại công cụ sau thời gian dài, tôi muốn làm quen lại để hoàn thành bài C++ | Bản thân | Tìm hiểu/làm quen lại; thời lượng trong card và quy trình chưa nhất quán | Chưa ghi nhận |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Đi lại và sinh hoạt cá nhân | Triệu Tuấn Minh #1–#3 | Bất tiện khi đi học bằng bus, mong muốn tự chủ đi lại; cần tách vấn đề đi lại khỏi mục tiêu thi bằng và ăn uống. |
| B — Học tập, nghiên cứu và làm quen kiến thức/công cụ | Nguyễn Văn Minh #1; Nguyễn Công Huy #1–#3 | Mất thời gian tra nền, tìm nguồn hoặc khôi phục kiến thức/cách dùng công cụ; mức độ rõ và bằng chứng khác nhau. |
| C — Tác vụ học tập, báo cáo và vận hành | Phạm Ngọc Long #2–#3; Nguyễn Văn Minh #2–#3 | Kiểm tra, tổng hợp hoặc sửa đầu ra trước hạn nộp; một số phần có thể giải bằng checklist/Rule trước AI. |
| D — Quản lý cá nhân | Phạm Ngọc Long #1 | Thống kê chi tiêu; có quy trình và metric nháp nhưng dữ liệu tài chính nhạy cảm, cần kiểm tra giải pháp hiện có. |

### 2.3. Opportunity Solution Tree rút gọn

```text
OUTCOME: Học viên nộp bài lab đúng yêu cầu với ít thời gian kiểm tra hình thức hơn
├── Opportunity A: Yêu cầu và checklist cần tìm lại ở nhiều tài liệu
├── Opportunity B: Khó nhận ra thiếu heading, tên file hoặc link trước khi nộp
└── Opportunity C: Cần phân biệt lỗi hình thức có thể tự kiểm với lỗi nội dung cần người đọc
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- “Tạo chatbot/agent kiểm tra toàn bộ bài” — là giải pháp, chưa chứng minh cần AI.
- “Tự động nộp bài lên LMS” — hành động rủi ro, không nằm trong nhu cầu đã có bằng chứng.
- “Thống nhất checklist và script/GitHub Action” — là giải pháp dự kiến, không phải opportunity.

### 2.4. Chấm điểm shortlist (1–5)

Điểm là đánh giá sơ bộ từ các báo cáo cá nhân, không phải kết quả bỏ phiếu hay đồng thuận. “Pain có bằng chứng” và “nhóm hiểu domain” được chấm thận trọng do phần lớn là trải nghiệm n=1.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Kiểm tra checklist trước khi nộp lab (Long #2) | 4 | 5 | 3 | 4 | 5 | 5 | 4 | 30 |
| Tra lại Toán nền khi tự học sách kỹ thuật (Nguyễn Văn Minh #1) | 4 | 5 | 4 | 4 | 3 | 4 | 1 | 25 |
| Tổng hợp daily standup từ nhiều repo (Long #3) | 4 | 5 | 3 | 4 | 4 | 5 | 4 | 29 |

**Candidate được chọn:** Kiểm tra checklist trước khi nộp lab. Nhóm trưởng tự tổng hợp từ các báo cáo cá nhân và chọn; nhóm chưa có buổi thảo luận hoặc biểu quyết chung.

**Vì sao chọn:** Có actor và quy trình cụ thể, một bottleneck định lượng (20 phút đối chiếu/lần), bối cảnh nhóm/lớp gần với bài lab, và phương án No AI/Rule có thể thử ngay. Phạm vi cơ học như tên file/heading/link không đòi hỏi AI.

**Vì sao loại các candidate còn lại:** Daily standup cũng có quy trình và metric tốt nhưng mới là trải nghiệm cá nhân, script `git log` đã là phương án Rule hợp lý và chưa có dữ liệu so sánh người dùng. Vấn đề tự học Toán có bằng chứng cá nhân khá chi tiết nhưng domain hẹp, khó xác nhận nhóm có đủ người dùng thử và đánh giá chất lượng giải thích. Các candidate khác có impact/quy trình chưa rõ hoặc phạm vi rộng.

**Xử lý bất đồng (nếu có):** Khi Phạm Ngọc Long pitch, nhóm trưởng Triệu Tuấn Minh phản biện rằng yêu cầu nộp bài không quá khó và bản thân không gặp vấn đề này. Người đề xuất đã thu hẹp scope và cụ thể hóa actor, nhưng bất đồng về mức độ phổ biến của vấn đề chưa được giải quyết bằng dữ liệu; đây là lý do giả định Value (#1, #2 ở mục 3.1) cần kiểm chứng trước.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Học viên mất đáng kể thời gian vì phải đối chiếu yêu cầu ở nhiều file trước khi nộp | Value | 5 | 2 | Có |
| 2 | Lỗi hình thức xảy ra đủ thường xuyên để checklist dùng lại có giá trị | Value | 4 | 2 | Có |
| 3 | Một checklist gộp và các Rule đơn giản có thể giảm bước đối chiếu mà không làm tăng lỗi bị bỏ sót | Feasibility | 5 | 1 | Có |
| 4 | Học viên hiểu được kết quả kiểm tra và biết tự sửa lỗi được báo | Usability | 3 | 1 | Có |
| 5 | Tiêu chí hình thức có thể diễn đạt đủ rõ để kiểm tự động; đánh giá nội dung cần người | Feasibility | 4 | 2 | Có |
| 6 | Có thể thử giải pháp trong repo lớp mà không cần dữ liệu cá nhân hoặc quyền tích hợp LMS | Viability | 3 | 2 | Có |

*Điểm bằng chứng thấp phản ánh chưa có dữ liệu tập thể, không phải kết luận rằng giả định sai.*

Giả định nhóm kiểm chứng trong buổi này: Chưa có hoạt động hay kết quả kiểm chứng nhóm được ghi lại. Đề xuất ưu tiên kiểm chứng #1–#3 bằng quan sát thời gian và lỗi trên một số bài nộp thật.

### 3.2. Kiểm chứng

Cách đã dùng: Bốn báo cáo cá nhân có mô tả trải nghiệm và con số; chưa có ghi nhận phỏng vấn/survey/log tập thể cho candidate được chọn.

Interview snapshot (chưa có phỏng vấn được ghi nhận):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Chưa có dữ liệu |
| Câu nói đáng nhớ nhất (nguyên văn) | Chưa có dữ liệu |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Chưa có dữ liệu |
| Hiện đang xử lý bằng cách nào (workaround)? | Theo báo cáo cá nhân: mở README, CHECKPOINTS, RUBRIC, SUBMISSION rồi đối chiếu thủ công; đây là trải nghiệm của một người, chưa xác minh với người khác. |
| Mất bao lâu, bao lần? | Báo cáo cá nhân ghi đối chiếu 20 phút/lần, 5 lần/tuần và từng bị nhắc một lỗi hình thức; chưa có log/bằng chứng nhóm. |
| Insight / opportunity rút ra | Cần xác minh yêu cầu có thực sự khó tìm và lỗi hình thức có lặp lại ở các học viên khác không. |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Báo cáo cá nhân Phạm Ngọc Long, candidate checklist | 1 người, tự báo cáo | Có workflow 5 bước, bottleneck 20 phút/lần, target và workaround Rule được nêu | N=1; tổng 52 phút/lần là tự báo cáo, chưa có bản ghi thời gian độc lập |
| Ba báo cáo cá nhân còn lại | 3 người, không có dữ liệu checklist cùng candidate | Bối cảnh chung là bài tập/lab, có thể thuận tiện tuyển pilot trong lớp | Không xác nhận họ gặp cùng bottleneck hoặc muốn dùng checklist |
| Phản biện trong nhóm khi pitch (không tính là phỏng vấn vì là thành viên nhóm) | 1 người (nhóm trưởng) | Không có | Cho rằng yêu cầu nộp bài không quá khó và bản thân không gặp vấn đề này |
| Phỏng vấn/survey/log cho candidate này | 0 mẫu được ghi nhận | Chưa có | Chưa có dữ liệu để kết luận prevalence hoặc hiệu quả |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** Chưa có kiểm chứng, nên chưa thể ghi nhận thay đổi do bằng chứng. Trong bản đề xuất, thu hẹp phạm vi từ “kiểm tra bài” nói chung xuống kiểm tra hình thức (tên file, heading bắt buộc, link/đường dẫn); không tuyên bố đánh giá nội dung là đã giải quyết.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Yêu cầu/checklist hiện có của lớp | [CHECKPOINTS.md](../../CHECKPOINTS.md), [RUBRIC.md](../../RUBRIC.md), [SUBMISSION.md](../../SUBMISSION.md) | Cung cấp tiêu chí để học viên tự đối chiếu | Có sẵn, là nguồn chuẩn của yêu cầu | Tiêu chí nằm ở nhiều tài liệu; chưa đo được mức trùng lặp hoặc khó tìm | Trước hết lập danh mục yêu cầu và liên kết về nguồn chuẩn; không tạo bản sao dễ lỗi thời |
| Checklist gộp do cá nhân đề xuất | [Problem Card #2 của Phạm Ngọc Long](../individual/2A202604111_PhamNgocLong.md) | Hỗ trợ bước đối chiếu trước khi sửa và nộp | No AI, nhanh dựng thử; người nộp tự kiểm soát | Chưa được tạo hoặc thử; có nguy cơ bỏ sót khi tiêu chí thay đổi | Prototype bằng checklist thủ công trước khi viết automation |
| Static checks / Rule hoặc GitHub Action (ý tưởng, chưa được xây/test) | [Problem Card #2 của Phạm Ngọc Long](../individual/2A202604111_PhamNgocLong.md) | Kiểm tra tên file, heading, link có cấu trúc | Deterministic, dễ kiểm lại; có thể báo lỗi cụ thể | Không đánh giá được chất lượng lập luận/nội dung; link ngoài/LMS có thể không truy cập được | Chỉ tự động hóa tiêu chí rõ ràng; giữ bước đọc nội dung và submit cho con người |

Research trên đây là rà soát tài liệu và ý tưởng có sẵn trong repo, chưa phải khảo sát thị trường hoặc đánh giá công cụ bên ngoài.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

```text
[Mở tài liệu yêu cầu: 5']
→ [Đối chiếu từng mục: 20'] ← BOTTLENECK
→ [Kiểm tra tên file, tiêu đề, link, tài khoản commit: 10']
→ [Sửa, commit, push: 15']
→ [Nộp link LMS: 2']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Học viên | README, CHECKPOINTS, RUBRIC, SUBMISSION | Hiểu yêu cầu cần nộp | 5 phút/lần | Số liệu tự báo cáo |
| 2 | Học viên | Báo cáo và yêu cầu | Danh sách mục đạt/thiếu | 20 phút/lần | Bottleneck được nêu; yêu cầu rải rác |
| 3 | Học viên | File, tiêu đề, link, thông tin commit | Lỗi hình thức được phát hiện | 10 phút/lần | Số liệu tự báo cáo |
| 4 | Học viên | Các lỗi tìm được | Bản sửa đã commit/push | 15 phút/lần | Có thể thay đổi theo số lỗi |
| 5 | Học viên | Link repo | Bài nộp trên LMS | 2 phút/lần | Phần nộp cuối vẫn do người làm |

**Bottleneck chính:** Bước 2, đối chiếu yêu cầu thủ công: 20 phút/lần. Tổng quy trình 52 phút/lần (5+20+10+15+2; card cá nhân trước đó ghi nhầm tổng là 47 phút, đã sửa). Tần suất 5 lần/tuần, do mỗi ngày có 1 buổi lab. Số liệu vẫn là tự báo cáo của một người, cần bấm giờ khi pilot.

### 4.2. Quy trình tương lai

Đây là quy trình Rule/No AI được đề xuất để thử, chưa triển khai hoặc đo hiệu quả.

```text
[Mở checklist gộp có liên kết tới tài liệu nguồn: Rule]
→ [Tự tick các yêu cầu nội dung và tiêu chí cần đọc hiểu: con người]
→ [Chạy kiểm tra tên file / heading / link có cấu trúc: Rule, nếu đã cấu hình]
→ [Xem cảnh báo, sửa file và kiểm tra lại: con người]
→ [Commit, push và nộp link LMS: con người]
```

**Boundary:** Rule chỉ báo thiếu/sai dấu hiệu hình thức được cấu hình; không kết luận bài đạt chất lượng học thuật, không sửa nội dung, không commit/push hoặc nộp thay người dùng. Người nộp xác nhận nguồn yêu cầu còn hiệu lực và quyết định cuối.

**Phương án quay về khi Rule sai:** Bỏ qua cảnh báo không đúng, đối chiếu trực tiếp tài liệu nguồn và checklist thủ công; báo lỗi checklist/Rule cho người phụ trách repo.

### 4.3. Before / after

Các số sau là mục tiêu thử nghiệm, không phải kết quả đã đo. Thời gian tổng hiện tại là tổng các bước được kê (52 phút).

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 | 5 | Gộp việc tìm tiêu chí và kiểm tra hình thức; vẫn giữ người review, sửa và nộp |
| Tổng thời gian | 52 phút | Dưới 37 phút nếu bước đối chiếu giảm từ 20 xuống dưới 5 phút, các bước khác không đổi | Cần bấm giờ pilot, không coi là kết quả |
| Số bước thủ công | 5 | 4–5 | Tùy Rule có kiểm được file/heading/link; phần nội dung vẫn thủ công |
| Bottleneck chính | Đối chiếu yêu cầu, 20 phút/lần | Mục tiêu dưới 5 phút cho bước kiểm tra hình thức | Chưa kiểm chứng |
| Rủi ro mới phát sinh | Bỏ sót do nhiều nguồn; nhắc sửa | Checklist lỗi thời hoặc Rule báo nhầm/bỏ sót; xử lý bằng liên kết nguồn và review cuối của người nộp | Theo dõi trong pilot |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Học viên K5 L3B chuẩn bị nộp bài lab lên GitHub và LMS; bằng chứng hiện có chỉ từ một báo cáo cá nhân. |
| **Quy trình** | Mở tài liệu yêu cầu, đối chiếu các mục trong bài, kiểm tra tên file/tiêu đề/link/tài khoản commit, sửa và push, rồi nộp link LMS. |
| **Bottleneck** | Đối chiếu từng mục với yêu cầu rải rác trong nhiều file; cá nhân báo cáo 20 phút/lần. |
| **Impact** | Có thể tốn thời gian lặp lại trước mỗi lần nộp và phát sinh lỗi hình thức; một cá nhân báo cáo 5 lần/tuần và từng bị nhắc một lỗi. Chưa xác minh ở cấp nhóm/lớp. |
| **Success Metric** (baseline → target, cách đo) | Bước đối chiếu: 20 phút/lần → dưới 5 phút/lần; đã từng bị nhắc 1 lỗi hình thức (kỳ đo chưa rõ) → mục tiêu 0 lỗi bị nhắc trong pilot 2 tuần. Ghi thời gian và số lỗi thực tế ở từng lần nộp; baseline tổng quy trình 52 phút/lần (tự báo cáo). |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Bản v0 không cần AI. Checklist/Rule không tự đánh giá chất lượng nội dung, không sửa/commit/push/nộp bài. Học viên tự xác nhận mọi cảnh báo và chịu trách nhiệm nộp. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- Phản biện cá nhân: actor cần cụ thể, quy trình phải phản ánh việc thật, bottleneck là một bước, metric đo được và checklist/Rule có thể đủ. Báo cáo cá nhân cho biết đã thu hẹp actor và nêu workaround; chưa có phản biện từ nhóm khác được ghi lại.
- Phản biện trong nhóm: nhóm trưởng cho rằng yêu cầu nộp bài không quá khó và bản thân không gặp vấn đề này (xem mục 2.4). Nhóm chưa đồng thuận về mức độ phổ biến; cần kiểm chứng với học viên ngoài nhóm.
- Điểm đã sửa: tổng 47 phút trong card ghi nhầm, tổng đúng theo các bước là 52 phút.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **Thấp × Thấp** cho phạm vi kiểm tra hình thức bằng checklist/Rule.

Vì sao: Tiêu chí như tên file và heading có thể định nghĩa rõ và kiểm tra xác định. Đánh giá nội dung/đáp ứng rubric có độ mơ hồ cao hơn nên được giữ ngoài Rule, giao cho người đọc. Đây là phân loại đề xuất; chưa có pilot xác nhận.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Gom checklist vào một trang, liên kết về tài liệu yêu cầu gốc | Khi học viên có thể tự tick và thời gian đối chiếu giảm | Vẫn phụ thuộc người dùng nhớ tick đủ | Có, làm baseline |
| **Rule** | Kiểm tra tên file, heading bắt buộc và cấu trúc link; báo lỗi để người nộp tự sửa | Khi tiêu chí ổn định, có cấu trúc và pilot cho thấy checklist thủ công chưa đủ | Báo nhầm/bỏ sót; rule lỗi thời khi yêu cầu đổi | **Chọn cho thử nghiệm nhỏ, sau checklist** |
| **Workflow** | Chạy kiểm tra, trả danh sách cảnh báo và hướng dẫn sửa trước khi nộp | Khi quy trình lặp lại và cần nối nhiều bước kiểm tra | Tích hợp tăng độ phức tạp; người dùng có thể tin kết quả quá mức | Chưa chọn |
| **Agent** | Đọc bài, diễn giải rubric và tự quyết định bài đã đạt | Chỉ cân nhắc nếu có bằng chứng Rule không xử lý được và có cách đánh giá an toàn | Bịa/hiểu sai yêu cầu, bỏ sót lỗi nội dung, khó giải thích | Không chọn |

**Mức chọn:** Rule, theo hướng tuần tự: thử checklist No AI trước; chỉ tự động hóa tiêu chí cơ học nếu pilot xác nhận cần thiết. Quyết định cuối vẫn **Not Yet** cho tới khi có dữ liệu.

**Vì sao không chọn mức đơn giản hơn:** Chưa loại bỏ No AI — checklist gộp là baseline bắt buộc. Rule chỉ là bước tiếp theo nếu pilot cho thấy checklist chưa đủ và có tiêu chí cơ học ổn định; nếu checklist đạt metric thì dừng ở No AI.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Không áp dụng: giải pháp hiện chọn không dùng AI. Rule chỉ trả kết quả kiểm tra có/không theo tiêu chí cố định. |
| **Judgment** — con người cân nhắc, quyết định gì? | Học viên xác nhận yêu cầu hiện hành, xem cảnh báo, đánh giá nội dung và quyết định có sửa/nộp hay không. |
| **Action** — hành động cuối cùng là gì, ai làm? | Học viên sửa, commit/push và nộp bài. |
| **Outcome** — đo kết quả bằng gì? | Thời gian đối chiếu dưới 5 phút/lần và không bị nhắc lỗi hình thức trong pilot 2 tuần. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Không có input cho AI. Rule cần file bài và bộ tiêu chí hình thức có phiên bản; repo có tài liệu yêu cầu nhưng cần xác định tiêu chí nào kiểm được. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Ghi thời gian, cảnh báo sai/bỏ sót và lỗi bị nhắc sau từng lần nộp; người phụ trách cập nhật checklist/Rule. |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: card cá nhân chỉ mong biết mục thiếu/sai; bài nộp và quyết định cuối vẫn do học viên thực hiện. Thiết kế đề xuất hỗ trợ tự kiểm, không tự nộp.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: trong kiểm tra hình thức, bỏ sót có thể khiến lỗi đi tới bước chấm; báo nhầm làm mất thời gian sửa không cần thiết. Rule cần hiển thị tiêu chí và vị trí lỗi, luôn giữ checklist/review thủ công làm phương án dự phòng. Không dùng AI để tuyên bố bài “đạt”.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Học viên K5 L3B nộp lab qua repo GitHub và LMS; hiện chưa xác nhận được bao nhiêu học viên gặp vấn đề tương tự. |
| **Quy trình** | Tìm yêu cầu trong tài liệu lớp → đối chiếu nội dung và định dạng → sửa/commit/push → nộp link LMS. |
| **Bottleneck** | Đối chiếu thủ công tiêu chí hình thức nằm rải rác, cá nhân báo cáo 20 phút/lần. |
| **Impact** | Thời gian kiểm tra lặp lại và nguy cơ bị nhắc lỗi hình thức; impact hiện mới được một thành viên tự báo cáo. |
| **Success Metric** (baseline → target, cách đo) | Thời gian đối chiếu hình thức 20 phút → dưới 5 phút/lần; đã từng bị nhắc 1 lỗi hình thức (kỳ đo chưa rõ) → mục tiêu 0 lỗi bị nhắc trong pilot 2 tuần. Thu thời gian và lỗi trên từng lần nộp; baseline tổng quy trình 52 phút/lần (tự báo cáo). |
| **Boundary** | Không tự đánh giá chất lượng học thuật, không tự sửa nội dung, commit/push hoặc nộp thay. Học viên kiểm tra kết quả và quyết định cuối. |
| **AI intervention point** | Không dùng AI. Rule tùy chọn chỉ kiểm các cấu trúc xác định như tên file/heading/link. |
| **Mức chọn** | Rule (thử sau checklist No AI); quyết định triển khai là Not Yet. |
| **Rủi ro & người kiểm tra** | Rule có thể báo nhầm/bỏ sót hoặc lỗi thời; học viên đối chiếu tài liệu nguồn và người phụ trách repo kiểm tra/cập nhật quy tắc. |

**Thay đổi so với v0 và lý do:** Thu hẹp “kiểm tra bài” thành kiểm tra hình thức, tách phần có thể kiểm bằng Rule khỏi đánh giá nội dung của con người. Đây là chỉnh sửa dựa trên phạm vi đề xuất, chưa phát sinh từ phỏng vấn.

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Phạm vi | Kiểm tra thiếu mục hoặc sai hình thức trong bài lab | Chỉ kiểm tên file, heading, link/cấu trúc; nội dung do người đọc | Tránh hứa Rule/AI đánh giá chất lượng nội dung |
| Giải pháp | Checklist gộp và Rule là các hướng có thể thử | Checklist No AI trước, Rule chỉ khi pilot cần | Ưu tiên phương án đơn giản và đo được |
| Baseline | 20 phút đối chiếu; tổng 47 phút | Giữ 20 phút cho bước đối chiếu; tổng quy trình là 52 phút | Số tổng trong card ghi nhầm, sửa theo phép cộng các bước |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

Không có đầu ra AI trong phương án hiện tại. Các tiêu chí dưới đây đánh giá output của checklist/Rule; nếu sau này thêm AI cần định nghĩa bộ đánh giá riêng.

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Phát hiện lỗi cấu trúc | Bắt đúng tên file/heading/link thiếu trong bộ test có nhãn | Bỏ sót lỗi thuộc tiêu chí đã cấu hình |
| 2 | Cảnh báo có thể hành động | Nêu tiêu chí và vị trí cần kiểm tra, liên kết nguồn yêu cầu | Cảnh báo chung chung hoặc không truy được nguồn |
| 3 | Không gây sửa sai | Không yêu cầu sửa nội dung vốn đã đạt; người nộp có thể bỏ qua cảnh báo sai | Cảnh báo sai làm người dùng sửa/nộp sai |
| 4 | Tôn trọng boundary | Không tự sửa, commit/push hoặc nộp bài | Tự thực hiện hành động ngoài quyền được giao |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | TB | Một thành viên tự báo cáo 20 phút/lần và một lỗi bị nhắc; một thành viên khác (nhóm trưởng) cho biết không gặp vấn đề này; chưa có xác nhận từ học viên ngoài nhóm hoặc pilot. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp–TB | Checklist/Rule đơn giản nếu chỉ rõ tiêu chí; chưa có quan sát sử dụng, và cảnh báo mơ hồ có thể gây nhầm. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Thấp | Nguồn yêu cầu nằm trong repo; kiểm tra Markdown cơ bản khả thi. Chưa xác định hết tiêu chí nào ổn định hoặc cách kiểm link ngoài. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Thấp | Checklist/Rule không cần dữ liệu nhạy cảm hoặc dịch vụ trả phí; người phụ trách repo cần quản lý phiên bản và cập nhật khi rubric đổi. Không tích hợp tự nộp LMS. |

### 8.2. Kết luận

**Quyết định:** **Not Yet**

**Lý do:** Candidate có quy trình và bottleneck cá nhân khá cụ thể, nhưng chưa có kiểm chứng với người dùng ngoài nhóm; ngay trong nhóm, nhóm trưởng cho biết không gặp vấn đề này; chưa có prototype hoặc kết quả thử nghiệm. Chưa đủ cơ sở tuyên bố giá trị ở cấp nhóm/lớp.

**Nếu Go — pilot nhỏ nhất:** Chưa Go. Nếu nhóm xác nhận tiếp tục, thử checklist gộp thủ công với 3–5 học viên qua tối thiểu 5 lần nộp trong 2 tuần; ghi baseline và sau thử, thời gian kiểm tra, lỗi hình thức bị bỏ sót/báo nhầm. Chỉ làm Rule sau khi checklist chưa đạt mục tiêu.

**Nếu Not Yet — cần kiểm chứng gì trước:** Hỏi 3–5 học viên về lần nộp gần nhất, quan sát/thời gian hóa quy trình, xác nhận tần suất lỗi và đo lại từng bước của baseline. Sau đó chạy pilot checklist không AI và so sánh với ngưỡng đã định trước.

**Nếu No-Go — nên làm gì thay AI:** Duy trì tài liệu nguồn, thêm checklist tự kiểm tập trung và hướng dẫn liên kết tới tiêu chí gốc.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …): Sau pilot 2 tuần, nếu không giảm được thời gian đối chiếu từ 20 xuống dưới 5 phút/lần, hoặc có lỗi bị bỏ sót/tăng lỗi bị nhắc, không mở rộng Rule; quay lại checklist thủ công và xem lại problem/metric.

---

## 9. Hạn chế và hướng tiếp theo

- Báo cáo cá nhân chưa phải bằng chứng về đồng thuận CP3–CP6; cần nhóm xác nhận candidate và quyết định cuối.
- Chưa có snapshot phỏng vấn, survey, log thử nghiệm hoặc research độc lập về giải pháp bên ngoài.
- Các số liệu của candidate được chọn là tự báo cáo n=1 (52 phút/lần, 5 lần/tuần); một thành viên khác trong nhóm không gặp vấn đề này.
- Các candidate khác cũng có vấn đề dữ liệu: một số workflow chưa điền đủ actor/quy trình; một số số liệu giữa card và sơ đồ nháp không khớp.
- Bước tiếp theo: xác nhận nhóm chọn đề tài, phỏng vấn/quan sát học viên khác, đo baseline nhất quán, thử checklist No AI trước; chỉ triển khai Rule nếu pilot chứng minh có giá trị tăng thêm.

## 10. Tài liệu tham khảo

- [Báo cáo cá nhân — Triệu Tuấn Minh](../individual/2A202604123_TrieuTuanMinh.md)
- [Báo cáo cá nhân — Nguyễn Văn Minh](../individual/2A202604117_NguyenVanMinh.md)
- [Báo cáo cá nhân — Phạm Ngọc Long](../individual/2A202604111_PhamNgocLong.md)
- [Báo cáo cá nhân — Nguyễn Công Huy](../individual/2A202604086_NguyenCongHuy.md)
- [README.md](../../README.md), [CHECKPOINTS.md](../../CHECKPOINTS.md), [RUBRIC.md](../../RUBRIC.md), [SUBMISSION.md](../../SUBMISSION.md)
- [Worksheet — hướng dẫn chi tiết](../../docs/01-worksheet.md)
