# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Công Huy
- MSSV: 2A202604086
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: Nhóm 4
- Link repo nhóm: https://github.com/ttm4623/K5-L3B-Day02-Nhom4-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Tốn thời gian|Khi tôi sử dụng lại một công cụ sau 1 khoảng thời gian không tiếp xúc|Bản thân|30-60 phút 1 lần, 1 lần/tháng|
| 2 |Cần đọc, tổng hợp nhiều thông tin|Khi học một kiến thức mới, có nhiều kiến thức liên quan cần tìm hiểu|Bản thân|2-3 giờ 1 lần, 3-4 lần/tuần|
| 3 |Pain từ người khác|Khi có ý định làm một việc, tôi thường quên mất việc đó|Bản thân|1-2 lần/tuần|
| 4 |Tốn thời gian|Khi tôi muốn tìm nguồn cho một thông tin quan trọng trong bài nghiên cứu|Team|10-15p/lần|
| 5 |Lặp lại|Khi tới công ty thực tập check-in|Bản thân|1-2 lần/tháng|
| 6 | | | | |
| 7 | | | | |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Tìm hiểu về một kiến thức mới|Pain thật, nhiều người gặp|Chất lượng nguồn cung cấp kiến thức khó đo|
| 2 |Tìm nguồn cho thông tin|Impact rộng|Phạm vi dữ liệu lớn|
| 3 |Quên cách sử dụng công cụ|Pain thật, nhiều người gặp||

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi tôi cần học một ngôn ngữ mới, để phục vụ cho việc học tập|
| Actor |Bản thân|
| Thời điểm / bối cảnh |Làm một project về intent-classification bằng python cho môn học ở trường|
| Quy trình hiện tại (3–7 bước) |1. Tìm hiểu vấn đề -> 2. Đọc hiểu lý thuyết về Bayesian network và NLP -> 3. Python code -> 4. Test -> 5. Report|
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 2, đọc hiểu lý thuyết về Bayesian network và NLP: khoảng 1-2 giờ|
| Impact (nếu không giải thì sao) | Không hiểu cách hoạt động. |
| Success metric (baseline → target) | Thơi gian tìm hiểu lý thuyết giảm từ 2 giờ xuống còn 1 giờ, vẫn đảm bảo lượng kiến thức tiếp thu được.|
| Phương án không dùng AI | Tìm và đọc hiểu các kiến thức về Bayesian network + NLP |
| Giả thuyết về AI (nếu có) | AI giải thích sơ về Bayesian network + NLP và soạn các bước thực hiện project|
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:
HIỆN TẠI - 310':

[1. Tìm hiểu về Intent-Classification: 10'] -> [2. Đọc hiểu kiến thức Bayesian network + NLP: 120'] <- BOTTLENECK 
-> [3. Python code: 120'] -> [4. Test: 30'] -> [5. Report: 30']

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi tôi cần tìm nguồn của thông tin đã sử dụng trong bài nghiên cứu so sánh tốc độ các biến thể thuật toán GD, để thực hiện trích dẫn. |
| Actor |Bản thân|
| Thời điểm / bối cảnh |Trong quá trình thực hiện nghiên cứu|
| Quy trình hiện tại (3–7 bước) | 1. Nghiên cứu về thuật toán GD và các biến thể -> 2. Trình bày lý thuyết theo format -> 3. Dự đoán -> 4. Thực nghiệm -> 5. Trích dẫn -> 6. Nộp bài|
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5, trích dẫn: khoảng 15-20p, tốn thời gian tìm nguồn|
| Impact (nếu không giải thì sao) | Paper bị reject|
| Success metric (baseline → target) | Lưu lại nguồn khi tìm được kiến thức cần thiết, giảm thời gian tìm nguồn từ 20p xuống 5p|
| Phương án không dùng AI | Search trên gg scholar|
| Giả thuyết về AI (nếu có) | AI trích nguyên văn từ nguồn đính kèm nguồn|
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:
HIỆN TẠI - 260':

[1. Nghiên cứu lý thuyết: 60'] -> [2. Trình bày theo format: 120'] -> [3. Dự đoán: 15'] -> [4. Thực nghiệm: 30'] -> [5. Trích dẫn: 30'] -> [6. Gửi bài: 5']



### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tôi quay lại sử dụng một công cụ đã một thời gian không sử dụng, để hoàn thành bài tập trên lớp|
| Actor |Bản thân|
| Thời điểm / bối cảnh | Hoàn thành bài tập code C++ của trường|
| Quy trình hiện tại (3–7 bước) | |
| Bottleneck (bước nào, mất bao nhiêu phút) | 1. Tìm hiểu bài tập C++ -> 2. Code bằng C++ -> 3. Lưu bài -> 4. Submit|
| Impact (nếu không giải thì sao) | Không được tính điểm|
| Success metric (baseline → target) | Thời gian tìm hiểu, làm quen lại giảm từ 60p xuống còn 30p|
| Phương án không dùng AI | Tìm kiến thức liên quan đến bài tập C++|
| Giả thuyết về AI (nếu có) | AI gợi ý hướng giải và code mẫu|
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại:
HIỆN TẠI - 50':

[1. Tìm hiểu bài tập C++: 10'] -> [2. Code bằng C++: 30'] -> [3. Lưu bài: 5'] -> [4. Submit: 5']

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Pain thật, nghiều người gặp
- Câu hỏi muốn nhóm phản biện: Làm thế nào để xác định rằng bottleneck thực sự nằm ở việc tìm hiểu lý thuyết NLP và Bayesian Network, chứ không phải do chưa biết cách áp dụng những kiến thức đó vào bài toán Intent Classification?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Chưa xác định nguyên nhân gây mất thời gian|Đồng ý một phần|Chia nhỏ thời gian nghiên cứu|
|Quy trình hiện tại lại chưa thể hiện việc lưu trữ nguồn ngay khi nghiên cứu lý thuyết|Đồng ý một phần|Bổ sung hoạt động lưu nguồn và trích dẫn|
|Bottleneck đang ghi toàn bộ quy trình 4 bước thay vì xác định bước thực sự gây tốn thời gian|Không đồng ý|Bổ sung thời gian làm quen lại vào workflow|
---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card |Trình bày Problem Card của mình, giải thích bối cảnh, bottleneck và giả thuyết sử dụng AI.|Nhận được góp ý giúp phát hiện điểm chưa rõ và cải thiện Problem Card.|
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Làm thế nào để xác định khoản chi tiêu nào thực sự cần cắt giảm, thay vì chỉ dựa vào số tiền đã chi nhiều nhất trong tháng?|Giúp bạn trình bày xem xét sâu hơn về tiêu chí lựa chọn khoản chi cần cắt giảm.|
| Nhận phản biện | Câu hỏi tôi nhận được:Làm thế nào để đảm bảo AI giải thích kiến thức Bayesian Network và NLP chính xác, đồng thời không khiến bạn phụ thuộc vào AI?| Tôi đã sửa gì:Tôi làm rõ cách kiểm chứng kiến thức bằng cách đối chiếu với tài liệu học thuật, thực hành code và tự giải thích lại nguyên lý. Đồng thời, bổ sung tiêu chí đánh giá mức độ tiếp thu kiến thức bên cạnh thời gian tìm hiểu.|
| Gom cluster / cây OST |Tham gia phân nhóm các Problem Card có điểm chung về nhu cầu, khó khăn và mục tiêu; xác định mối liên hệ giữa các vấn đề để xây dựng cây OST.|Giúp nhóm nhận diện các vấn đề chung và mối liên hệ giữa chúng.|
| Chọn candidate problem |Tham gia thảo luận, so sánh và lựa chọn vấn đề tiềm năng.|Nhóm xác định được vấn đề ưu tiên để tiếp tục nghiên cứu.|
| Kiểm chứng / research |Tìm kiếm thông tin, khảo sát hoặc kiểm tra giả định về vấn đề.|Có thêm bằng chứng để đánh giá vấn đề có thực sự tồn tại và đáng giải quyết hay không.|
| Quy trình nhóm |Tham gia xây dựng các bước thực hiện quy trình giải quyết vấn đề.|Giúp nhóm xác định các bước và công đoạn cần cải thiện.|
| Problem Statement |Tham gia xây dựng và chỉnh sửa câu mô tả vấn đề của nhóm.|Problem Statement rõ ràng hơn về đối tượng, nhu cầu và vấn đề cần giải quyết.|
| Mức can thiệp AI |Đề xuất công đoạn nên sử dụng AI và công đoạn cần con người kiểm soát.|Xác định vai trò phù hợp của AI trong quy trình.|
| Quyết định |Tham gia thảo luận và thống nhất phương án cuối cùng.|Nhóm thống nhất Problem Statement và hướng giải quyết.|

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan |Gợi ý các tình huống có thể phát triển thành Problem Card.|Đưa ra nhiều ý tưởng thuộc lập trình, ML và nghiên cứu.|Một số ý tưởng còn chung chung, chưa rõ vấn đề.|Chọn tình huống xuất phát từ trải nghiệm thực tế của bản thân.|
| CP2 Problem Card |Đánh giá và hoàn thiện các thành phần của Problem Card.|Phát hiện điểm thiếu nhất quán giữa Workflow, Bottleneck và Success Metric.|Đôi khi đưa ra giả định về thời gian và tác động chưa được kiểm chứng.|Điều chỉnh nội dung dựa trên trải nghiệm và thực tế công việc.|
| CP4 Research |Hỗ trợ tìm hiểu kiến thức và tài liệu nghiên cứu.|Giải thích nhanh NLP, Bayesian Network, Gradient Descent và gợi ý nguồn tham khảo.|Kiến thức đôi khi chưa đủ sâu, trích dẫn có thể thiếu chính xác.|Đối chiếu tài liệu gốc và kiểm tra độ tin cậy của nguồn.|
| CP5 Quy trình |Phân tích và đề xuất Workflow có AI hỗ trợ.|Phân chia công việc thành các bước và xác định công đoạn tốn thời gian.|Quy trình đề xuất có thể chưa phản ánh đúng thực tế.|Chỉ sử dụng AI ở những công đoạn thực sự cần thiết.|
| CP5–6 Problem Statement |Tổng hợp thông tin và xác định vấn đề cốt lõi.|Giúp diễn đạt vấn đề rõ ràng, có cấu trúc.|Có thể nhầm lẫn giữa biểu hiện và nguyên nhân.|Xác định lại vấn đề dựa trên trải nghiệm thực tế.|
| CP6 Mức can thiệp / quyết định |Đánh giá công đoạn nào nên sử dụng AI.|Gợi ý cách phân chia công việc giữa người và AI.|AI có thể sai hoặc khiến tôi phụ thuộc nếu sử dụng quá nhiều.|Ưu tiên AI hỗ trợ, còn việc kiểm chứng và quyết định cuối cùng do tôi thực hiện.|

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
|Khi nghe các bạn trình bày top 3 problems, tôi nhận ra mỗi người đều có những khó khăn và nhu cầu khác nhau. Một vấn đề tưởng chừng đơn giản nhưng có thể xuất phát từ nhiều nguyên nhân. Tôi học được cách xác định bottleneck, phân tích nguyên nhân và đặt ra tiêu chí đánh giá hiệu quả. Qua đó, tôi hiểu rằng cần tập trung tìm hiểu vấn đề trước khi nghĩ đến giải pháp.|
**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
|Trong quá trình thảo luận, nhóm đôi lúc tập trung vào việc tìm kiếm giải pháp sử dụng AI trước khi xác định rõ vấn đề cần giải quyết. Điều này có thể khiến nhóm bỏ qua nguyên nhân thực sự của vấn đề. Sau đó, nhóm nhận ra cần quay lại phân tích đối tượng, nhu cầu và những khó khăn hiện tại. Nhóm đã tập trung làm rõ Problem Statement trước khi lựa chọn giải pháp phù hợp.|
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
|Có. Trong Problem Card của mình, tôi đề xuất sử dụng AI để giải thích kiến thức Bayesian Network và NLP nhằm giảm thời gian tìm hiểu lý thuyết. Tuy nhiên, sau khi nhận được câu hỏi phản biện về việc làm thế nào đảm bảo AI cung cấp kiến thức chính xác và không khiến người học phụ thuộc, tôi nhận ra giả thuyết ban đầu còn thiếu bước kiểm chứng. Vì vậy, tôi bổ sung việc đối chiếu với tài liệu học thuật, thực hành code và tự đánh giá mức độ hiểu kiến thức.|
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
|Qua quá trình tìm kiếm thông tin và nghiên cứu vấn đề, tôi nhận ra rằng việc đưa ra giả thuyết ban đầu chưa đủ để khẳng định vấn đề thực sự tồn tại. Cần có thông tin và bằng chứng để kiểm chứng những nhận định đó. Điều này giúp tôi hiểu rằng kết quả nghiên cứu có thể khác với suy nghĩ ban đầu và nhóm cần sẵn sàng điều chỉnh hướng tiếp cận dựa trên bằng chứng thực tế.|
**6.5. Điều khó nhất khi viết Problem Statement là gì?**
|Điều khó nhất đối với tôi là xác định chính xác vấn đề cốt lõi và diễn đạt nó một cách ngắn gọn, rõ ràng. Ban đầu, tôi thường tập trung vào biểu hiện của vấn đề hoặc nghĩ đến giải pháp thay vì tìm hiểu nguyên nhân. Ngoài ra, việc xác định đúng đối tượng, nhu cầu và phạm vi vấn đề cũng cần được cân nhắc kỹ. Qua hoạt động này, tôi hiểu rằng một Problem Statement tốt cần mô tả đúng vấn đề, không nên đưa giải pháp vào quá sớm.|
**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
|Nếu được thực hiện lại, tôi sẽ chủ động chuẩn bị nhiều câu hỏi phản biện hơn và tìm hiểu kỹ vấn đề trước khi trình bày. Khi thảo luận, tôi sẽ tập trung đặt câu hỏi về nguyên nhân, tính cấp thiết và bằng chứng chứng minh vấn đề tồn tại. Đặc biệt, tôi muốn phản biện sâu hơn về success metric, tính khả thi của giải pháp và mức độ cần thiết khi sử dụng AI. Điều này sẽ giúp nhóm tránh lựa chọn giải pháp chỉ vì AI đang phổ biến mà chưa thực sự phù hợp với nhu cầu.|
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
|Theo tôi, đầu tiên cần xác định Problem để biết nhóm đang muốn giải quyết vấn đề gì. Tiếp theo, phân tích quy trình hiện tại để tìm ra bottleneck gây khó khăn cho người dùng. Từ đó, nhóm xây dựng Metric để đo lường hiệu quả trước và sau khi giải quyết vấn đề. Boundary giúp xác định phạm vi và giới hạn của vấn đề cần giải quyết. Sau đó, nhóm xác định mức độ can thiệp của AI, công đoạn nào AI hỗ trợ và công đoạn nào cần con người kiểm soát. Cuối cùng, dựa trên kết quả nghiên cứu, kiểm chứng và thảo luận, nhóm đưa ra quyết định về Problem Statement và hướng giải quyết phù hợp.|
---

## 7. Tài liệu tham khảo

-
