# Báo cáo cá nhân — 2A202604117 Nguyễn Văn Minh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng checkpoint: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Văn Minh
- MSSV: 2A202604117
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhóm 4
- Link repo nhóm: https://github.com/ttm4623/K5-L3B-Day02-Nhom4-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi tự học một chương khó trong sách kỹ thuật (điều khiển tối ưu, RL) mà không có giảng viên kèm, tôi muốn được giảng lại đúng phần Toán nền mà chương đó giả định mình đã biết, để hiểu xong chương trong 1 buổi thay vì 2-3 ngày vì cứ phải nhảy ra tra lại Toán | Người tự học tài liệu kỹ thuật nặng về Toán (research student, engineer) | Mỗi chương phải dừng tra lại nền 2-3 lần, mỗi lần 15-30 phút (có khi hơn 30 phút nếu Toán khó), tổng 45-90+ phút/chương; chương khó mất 2-3 ngày; đã tự bỏ 2 buổi tối xây hệ thống học riêng để workaround; đã thử DeepTutor, bỏ vì không có bài giảng thật |
| 2 | Tốn thời gian | Khi agent build xong diagram Simulink đúng chức năng nhưng layout rối, tôi muốn dọn dây theo một chuẩn nhất quán, để mỗi lần đọc lại diagram (debug, review) không mất 30 phút đi dây lại | Người làm việc với diagram Simulink do agent sinh ra | 2-3 file/tuần x 30 phút dọn = 60-90 phút/tuần; đã dùng auto-arrange của MATLAB, vẫn xấu, thiếu quy tắc nhất quán, chỉ có tính năng dây không đi qua khối |
| 3 | Lặp lại | Khi đặt Xanh SM lúc 7h sáng đi học, tôi muốn biết bao lâu có tài xế nhận, để kịp đổi sang xe buýt nếu chờ lâu | Sinh viên đi học sáng | Khoảng 4 lần/tuần, chờ 3-12 phút; tuần trước 1 lần phải hủy đặt lại (lịch sử chuyến trong app) |
| 4 | Lặp lại | Khi đi VinBus tới trường, tôi muốn biết mấy phút nữa xe tới trạm theo tình hình thực tế, để không đứng chờ lâu hoặc lỡ chuyến | Người đi VinBus | Khoảng 5 lượt/tuần, chờ 10-20 phút/lượt; xe hay trễ so với lịch khi tắc đường; từng lỡ chuyến, chờ thêm khoảng 15 phút |
| 5 | Tốn thời gian | Khi vẽ figure cho bài journal bằng agent, tôi muốn figure sạch layout và nói đúng thông điệp cần truyền, để không mất 2-3 giờ mỗi lần sửa tay phần agent không tự sửa được | Người viết bài journal tự vẽ figure bằng agent | Khoảng 1 lần/tháng, mỗi lần phần lãng phí 2-3 giờ; đã dùng nhiều bộ style skill trên GitHub: cỡ chữ/format giờ ổn, còn sót legend che dữ liệu và AI không biết chỗ nào cần nhấn mạnh; cho agent xem hình thì tốn token mà vẫn không sửa được |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- AI (trợ lý phản biện) gợi ý thêm từ hồ sơ làm việc của tôi: quản lý kết quả thí nghiệm (nhiều folder tmp, file .npz rải rác) và kiến thức học xong bị mai một. Tôi chưa đưa vào top 5 vì hôm nay chưa kịp đo con số cho hai ý đó; nếu có thời gian sẽ bổ sung thành dòng 6-7.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tra lại Toán/Lý nền khi tự học sách khó | Bằng chứng dày nhất: có con số (45-90+ phút/chương), có workaround tự chế (2 buổi tối), đã thử tool thị trường (DeepTutor) và bỏ; dân số kiểm chứng có sẵn trong lớp (ai cũng tự học tài liệu Toán-heavy) | Chưa kiểm chứng với người khác — mới có trải nghiệm của tôi |
| 2 | Dọn dây Simulink sau khi agent build | Con số rõ (60-90 phút/tuần); đã dùng auto-arrange nên có cả dữ liệu "tool đã có mà không đủ" | Chưa từng gây nhầm dấu thật — impact chỉ là tốn thời gian + khó theo dõi |
| 3 | Dọn figure journal sau khi agent vẽ | Đã thử nhiều bộ style skill trên GitHub nên phần "tool đã giải gì, còn sót gì" là trải nghiệm trực tiếp | Tần suất thấp: 1 lần/tháng |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi tự học một chương khó trong sách kỹ thuật (điều khiển tối ưu, RL) mà không có giảng viên kèm, tôi muốn được giảng lại đúng phần Toán nền mà chương đó giả định mình đã biết, để hiểu xong chương trong 1 buổi thay vì 2-3 ngày |
| Actor | Người tự học tài liệu kỹ thuật nặng về Toán (research student, engineer) khi không có lớp học kèm |
| Thời điểm / bối cảnh | Tự học sách và paper điều khiển/RL vào buổi tối; chương khó giả định người đọc đã nắm nền Toán (giải tích, xác suất, quy hoạch động) mà tôi đã học nhưng quên hoặc chưa từng học sâu |
| Quy trình hiện tại (3–7 bước) | 1. Đọc chương → 2. Kẹt ở nền Toán → 3. Nhảy ra tra nguồn ngoài (sách khác, Google, ChatGPT) → 4. Quay lại đọc → 5. Lặp bước 2-4 thêm 1-2 lần → 6. Làm bài kiểm chứng |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 "tra nguồn ngoài": 15-30+ phút mỗi lần, 2-3 lần mỗi chương = 45-90+ phút/chapter, cộng thêm mất đà đọc vì phải nhảy ra vào |
| Impact (nếu không giải thì sao) | Chương khó kéo dài 2-3 ngày thay vì 1 buổi; phần Toán tra vội không ăn sâu, lần sau lại phải tra lại; kế hoạch ôn tập/thesis bị trễ |
| Success metric (baseline → target) | Baseline: 2-3 ngày/chương, trong đó 45-90+ phút là tra lại nền (tự bấm giờ 3 chương gần nhất). Target: 1 buổi/chapter, tổng thời gian tra lại dưới 15 phút. Cách đo: tự ghi thời gian từng chương trong 3-4 chương pilot |
| Phương án không dùng AI | Checklist nền tảng trước mỗi chương; học riêng Toán nền trước khi vào sách. Hạn chế: tôi không biết trước mình không biết gì — chương mới gợi ra đúng chỗ hổng lúc đang đọc |
| Giả thuyết về AI (nếu có) | Agent dò được chỗ hổng theo trạng thái người học rồi giảng lại đúng chỗ đó, thay vì tôi phải tự mò nguồn |
| Cảm nhận nhanh | Agent |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 2-3 ngày/chương khó

[Đọc chương: 30'] → [Kẹt nền Toán] → [Tra nguồn ngoài: 15-30'+, x2-3 lần] ← BOTTLENECK
→ [Quay lại đọc] → [Làm bài kiểm chứng]
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi agent build xong diagram Simulink đúng chức năng nhưng layout rối, tôi muốn dọn dây theo một chuẩn nhất quán, để mỗi lần đọc lại diagram không mất 30 phút đi dây lại |
| Actor | Người làm việc với diagram Simulink do agent sinh ra |
| Thời điểm / bối cảnh | Làm lab/mô hình điều khiển bằng agent + bộ tool MATLAB chính hãng; agent build đúng về chức năng nhưng không quan tâm thẩm mỹ |
| Quy trình hiện tại (3–7 bước) | 1. Nói agent build diagram → 2. Chạy/verify → 3. Kéo-thả dọn dây tay → 4. Đọc/review |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 dọn dây tay: 30 phút/file, 2-3 file/tuần = 60-90 phút/tuần |
| Impact (nếu không giải thì sao) | 60-90 phút/tuần mất vào việc thẩm mỹ; diagram rối khiến mỗi lần đọc lại để debug/review đều chậm hơn (chưa từng gây nhầm dấu — ghi trung thực: khó theo dõi chứ chưa gây lỗi) |
| Success metric (baseline → target) | Baseline: 60-90 phút/tuần dọn dây (2-3 file x 30 phút). Target: dưới 10 phút/tuần. Cách đo: đếm số file và tự bấm giờ trong 2 tuần |
| Phương án không dùng AI | Auto-arrange built-in của MATLAB — đã dùng: vẫn xấu, thiếu quy tắc nhất quán, chỉ có tính năng dây không đi qua khối |
| Giả thuyết về AI (nếu có) | Nếu nạp cho agent một bộ quy tắc layout nhất quán (kiểu JMAAB) thì có thể dọn được tự động |
| Cảm nhận nhanh | Rule/Workflow (quy tắc layout là cố định, deterministic) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 60-90 phút/tuần

[Agent build: nhanh] → [Chạy verify: nhanh] → [Dọn dây tay: 30'/file] ← BOTTLENECK → [Review]
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi vẽ figure cho bài journal bằng agent, tôi muốn figure sạch layout và nói đúng thông điệp cần truyền, để không mất 2-3 giờ mỗi lần sửa tay phần agent không tự sửa được |
| Actor | Người viết bài journal tự vẽ figure bằng agent |
| Thời điểm / bối cảnh | Chuẩn bị figure cho bản thảo journal (đang có 1 bài under review); vẽ plot xong phải đạt chuẩn tạp chí: khổ cột, cỡ chữ đọc được, legend không che dữ liệu |
| Quy trình hiện tại (3–7 bước) | 1. Nhờ agent vẽ plot từ dữ liệu → 2. Chạy, xem hình → 3. Sửa tay nhãn đè/legend che → 4. Nhờ agent sửa (agent không xem được hình; cho xem thì tốn token mà vẫn không sửa được) → 5. Sửa nốt bằng tay |
| Bottleneck (bước nào, mất bao nhiêu phút) | Vòng 3-5 "sửa layout + legend sau khi agent chạy xong": 2-3 giờ mỗi lần, khoảng 1 lần/tháng |
| Impact (nếu không giải thì sao) | 2-3 giờ lãng phí mỗi lần làm figure; deadline figure trễ; figure không nhấn đúng chỗ làm thông điệp bài báo yếu |
| Success metric (baseline → target) | Baseline: 2-3 giờ phần lãng phí mỗi lần làm figure (1 lần/tháng). Target: dưới 30 phút. Cách đo: tự bấm giờ trong 2 lần làm figure kế tiếp |
| Phương án không dùng AI | Đã dùng nhiều bộ style skill trên GitHub: cỡ chữ/format giờ "không quá tệ"; còn sót legend che dữ liệu và việc chọn chỗ nhấn mạnh |
| Giả thuyết về AI (nếu có) | Người chỉ định chỗ cần nhấn (thông điệp là phán quyết của người viết), AI thực thi style rule, người kiểm tra hình lần cuối |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 2-3 giờ lãng phí/lần (1 lần/tháng)

[Agent vẽ plot] → [Xem hình: xấu, nhãn đè, legend che]
→ [Sửa tay / nhờ agent sửa: không được] ← BOTTLENECK → [Sửa nốt tay: 2-3 giờ]
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: bằng chứng dày nhất (con số + workaround tự chế + đã thử tool thị trường), và là problem cả lớp khả năng cao cùng gặp vì ai cũng tự học tài liệu Toán-heavy
- Câu hỏi muốn nhóm phản biện: Các bạn có lần nào tự học chủ đề Toán-heavy mà phải dừng giữa chừng tra lại nền không? Mất bao lâu, mấy lần?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Ban đầu tôi pitch skill teach-loop (giải pháp) như problem — solution trá hình | Đồng ý | Viết lại thành Job Story không nhắc tên công cụ/skill |
| "Hỗ trợ rất nhiều" là lời khen, không phải bằng chứng; n=1, có thể lẫn biến (chương dễ hơn, mình giỏi hơn) | Đồng ý | Ghi như baseline cá nhân, đợi survey kiểm chứng với người khác |
| Hai dòng scan Xanh SM và VinBus tự mâu thuẫn (đổi sang xe buýt thì cũng chờ 10-20 phút không đoán trước được) | Đồng ý | Giữ trong scan làm candidate để loại có lập luận ở CP3, không đưa lên card |
| Bị cám dỗ mở rộng actor thành "sinh viên kỹ thuật" vì skill học gì cũng được — suy luận ngược từ giải pháp | Đồng ý | Actor giữ hẹp theo chỗ bằng chứng chạm tới: người tự học tài liệu Toán-heavy |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | *(điền sau buổi pitch nhóm)* | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | *(ghi phần survey mình đi hỏi)* | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Tự scan trước; sau đó dùng AI phản biện từng ý theo Mom Test; AI gợi ý thêm ý từ hồ sơ làm việc của tôi | Bắt được ý solution trá hình (teach-loop), bắt mâu thuẫn giữa 2 dòng scan | AI gộp "research" của tôi thành một khối mơ hồ | Tách thành 3-4 quy trình riêng: đọc paper, chạy thí nghiệm, tái hiện baseline, viết draft; tự chọn giữ/sửa dòng nào |
| CP2 Problem Card | Dùng AI phản biện card (bảng ở mục 3) | Chỉ đúng chỗ bottleneck mơ hồ, metric chưa đo được | AI định viết lại card thay tôi — không dùng | Tự viết lại bằng lời mình, chỉ lấy dữ liệu |
| CP4 Research | AI soạn bộ câu survey (tôi chọn/sửa câu), tra DeepTutor và app VinBus kèm link | Kiểm tra được VinBus app ĐÃ có tracking — cứu được 1 candidate yếu khỏi tốn công | Link phải tự mở lại kiểm tra theo luật | Dữ liệu survey từ người thật, ghi nguyên văn |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

- DeepTutor — https://github.com/HKUDS/DeepTutor (đã tự mở xem tính năng)
- VinBus App — Google Play: https://play.google.com/store/apps/details?id=vn.vinbus.app.prd (đã tự mở, thấy có "Xem thời gian chờ xe buýt" và "Theo dõi định vị xe buýt")
