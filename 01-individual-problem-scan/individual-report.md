# 01 — Individual Problem Scan

**Học viên:** Đoàn Đình Đông

**Bối cảnh quan sát:** 4 mảng đời sống thật, không gói trong một môi trường.

| | Bối cảnh | Mô tả |
|---|---|---|
| **A** | Trợ giảng IELTS | Chấm bài và theo dõi tiến độ cho 2 lớp (~18 học viên) |
| **B** | Hồ sơ gọi vốn | Chuẩn bị deck, financial model, tài liệu due diligence cho nhà đầu tư |
| **C** | Chi tiêu cá nhân | Chi tiêu rải qua tiền mặt, nhiều app ngân hàng và ví điện tử |
| **D** | Quản lý cuộc sống | Lịch dạy, lịch học K3, deadline gọi vốn, giấy tờ cá nhân |

> **Kết quả Phase 3:** nhóm đã chọn **Card #1 — Chấm IELTS Writing** làm candidate problem để đào sâu.

---

# Phase 1 — Scan: 10 problems

| # | Bối cảnh | Lăng kính | Problem | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|---|
| 1 | A | Lặp lại | Chấm Writing và viết nhận xét 4 tiêu chí, phần lớn là gõ lại các lỗi cơ bản đã viết cho học viên khác | TA, học viên | ~30 phút/bài, ~18 bài/tuần; lỗi cơ bản lặp ở ~7/10 bài |
| 2 | A | AI có thể tốt hơn | Học viên không nhận ra mình lặp cùng pattern lỗi, vì mỗi bài được nhận xét rời rạc | Học viên | Cùng lỗi xuất hiện lại ở 3-4 bài liên tiếp |
| 3 | A | Pain từ người khác | Học viên hỏi lại "sao em chỉ được band này" vì nhận xét viết vội, quá ngắn | Học viên, TA | Hỏi lại 2-3 lần mỗi đợt trả bài |
| 4 | B | Lặp lại | Mỗi nhà đầu tư quan tâm một góc khác nên phải dựng lại một biến thể deck riêng | Người làm hồ sơ, founder | ~4-6 tiếng cho mỗi bộ hồ sơ |
| 5 | B | Tốn thời gian | Số liệu trong deck, financial model và báo cáo traction lệch nhau vì cập nhật ở thời điểm khác nhau | Founder, nhà đầu tư | Phát hiện lệch ngay trước buổi gặp |
| 6 | B | Pain từ người khác | Không ai nắm được đang nói chuyện với nhà đầu tư nào, tới bước nào, ai cần follow up | Founder, cả team | Có NĐT bị quên follow up hơn 2 tuần |
| 7 | C | Lặp lại | Cuối tháng mở từng app ngân hàng và ví điện tử, nhập tay giao dịch vào Excel | Tôi | ~60-90 phút/tháng, thường bỏ dở |
| 8 | C | Tốn thời gian | Không tách được chi cá nhân và khoản ứng trước cho công việc nên khó hoàn ứng | Tôi, kế toán | Vài khoản/tháng không đòi lại được |
| 9 | D | Lặp lại | Lịch dạy, lịch học K3 và deadline gọi vốn nằm ở 3 nơi khác nhau | Tôi, học viên bị đổi lịch | Trùng lịch 1-2 lần/tháng |
| 10 | D | Pain từ người khác | Giấy tờ cá nhân rải rác nên khi ai cần gấp phải lục lâu | Tôi, người yêu cầu giấy tờ | 15-30 phút mỗi lần tìm |

**Pattern chung xuyên 3 bối cảnh:** dữ liệu được tạo ra rời rạc, rồi phải gom lại thủ công về sau. Khác biệt duy nhất là bước gom có cần hiểu ngôn ngữ hay không — và đó chính là chỗ quyết định có cần AI hay không.

---

# Phase 2 — Top 3 Problem Cards

Chọn 3 bối cảnh khác nhau và 3 mức giải pháp khác nhau, để nhóm có nguyên liệu so sánh Rule / Workflow / Agent thay vì bàn ba biến thể của cùng một bài.

| Rank | Bối cảnh | Problem | Mức | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|---|---|
| 1 | A | Chấm IELTS Writing + nhận xét 4 tiêu chí (gộp #1, #2, #3) | Workflow | Baseline thời gian rõ nhất, lặp mỗi tuần nên đo trước/sau dễ, boundary người-máy tách được theo từng tiêu chí | "Nhận xét đủ tốt" đo bằng gì; trung tâm có cho phép đưa bài học viên lên tool AI ngoài không |
| 2 | B | Dựng hồ sơ gọi vốn cho từng NĐT (gộp #4, #5) | Rule → Workflow | Rủi ro uy tín cao, boundary AI rất rõ: được viết chữ, không được đụng vào số | Dữ liệu nhạy cảm, khó chia sẻ để nhóm validate |
| 3 | C | Tổng hợp chi tiêu cá nhân (gộp #7, #8) | No AI | Chứng minh **không cần AI vẫn là kết luận đúng** | Có đang bỏ sót phần thật sự cần AI không |

---

## ⭐ Problem Card #1 — Chấm IELTS Writing và viết nhận xét *(A)* — **bài nhóm chọn**

**Problem 1 câu:**
Học viên chờ 2-3 ngày mới nhận kết quả chấm Writing, trong khi TA mất ~30 phút/bài mà hơn nửa thời gian viết nhận xét là gõ lại những lỗi ngữ pháp/từ vựng cơ bản đã viết cho học viên khác.

**Actor:** TA IELTS chấm Writing cho 2 lớp (~18 học viên), báo cáo cho giáo viên chính.

**Thời điểm / bối cảnh:** Sau mỗi buổi có bài nộp. Trung tâm cam kết trả bài trong 2-3 ngày.

### Current workflow

```text
1. Nhận bài qua Zalo / Google Drive          (2')
2. Đọc lướt xác định band sơ bộ              (3')
3. Đọc kỹ, gạch lỗi ngữ pháp và từ vựng      (8')
4. Viết nhận xét theo 4 tiêu chí TR/CC/LR/GRA (12')  <-- BOTTLENECK
5. Chấm 4 tiêu chí và quy ra band tổng       (2')
6. Nhập điểm vào bảng theo dõi lớp           (1')
7. Gửi bài đã chấm lại cho học viên          (2')
```

**Bottleneck:** Bước 4 — viết nhận xét 4 tiêu chí, ~12 phút/bài.

Nhưng 12 phút đó **không đồng nhất**. Tách ra thì thấy rõ hai nửa khác hẳn nhau:

| Phần | Thời gian | Tính chất |
|---|---:|---|
| Nhận xét lỗi ngữ pháp / từ vựng cơ bản | ~7-8 phút | Lặp lại, gần như giống nhau giữa các bài |
| Nhận xét riêng theo nội dung bài (lập luận, ý tưởng) | ~4-5 phút | Không lặp, cần phán đoán của người chấm |

Đây là điểm quan trọng nhất của cả bài toán: bottleneck thật không phải "chấm bài" nói chung, mà là **nửa lặp lại** trong bước 4.

### Phân tích: 4 tiêu chí IELTS không giống nhau về độ mơ hồ

Đây là căn cứ để đặt boundary, thay vì nói chung chung "AI hỗ trợ chấm bài".

| Tiêu chí | Độ mơ hồ | AI làm được gì | Ai quyết định |
|---|---|---|---|
| **GRA** — Grammatical Range & Accuracy | **Thấp** — sai thì, thiếu mạo từ, sai word form có đúng/sai rõ ràng | Bóc tách gần hết lỗi, độ tin cậy cao | AI gạch lỗi, TA xác nhận |
| **LR** — Lexical Resource | Thấp–trung — lặp từ, collocation sai, dùng từ chưa tự nhiên | Phát hiện tốt lặp từ và collocation lạ | AI gợi ý, TA chốt |
| **CC** — Coherence & Cohesion | Trung — thiếu topic sentence, linking word dùng máy móc | Phát hiện được dấu hiệu cấu trúc | TA đánh giá |
| **TR** — Task Response | **Cao** — bài có trả lời đúng câu hỏi không, lập luận có đủ sức không | Yếu nhất. Bài viết trôi chảy nhưng lạc đề vẫn hay được AI đánh giá tốt | **TA quyết định, AI không đụng vào** |

Hệ quả trực tiếp:

- **Vì sao Workflow, không phải Agent:** các bước cố định, không có bước nào cần AI tự lập kế hoạch hay tự đổi thứ tự.
- **Vì sao band cuối phải do TA chấm:** TR là tiêu chí kéo band mạnh nhất nhưng lại là tiêu chí AI yếu nhất. Giao band cho AI là giao đúng phần nó dở nhất.
- **Vì sao không chỉ dùng Rule:** bank nhận xét mẫu xử lý được GRA và một phần LR, nhưng không viết được nhận xét bám nội dung riêng của từng bài.

**Impact:** ~9 tiếng/tuần cho 1 TA. Khi dồn bài thì chấm vội → nhận xét chung chung → học viên hỏi lại 2-3 lần mỗi đợt trả bài, và không nhận ra mình lặp cùng pattern lỗi qua nhiều bài liên tiếp.

### Success metric

Ba metric đầu đo hiệu quả. Metric thứ tư là **metric đối trọng** — để không tối ưu tốc độ mà làm hỏng chất lượng.

| Chỉ số | Hiện tại | Mục tiêu | Cách đo |
|---|---|---|---|
| Thời gian xử lý 1 bài | ~30 phút | Dưới 15 phút | Bấm giờ 10 bài trước và 10 bài sau |
| Thời gian học viên chờ trả bài | 2-3 ngày | Trong 24 giờ | Timestamp nộp → timestamp trả |
| Số lần học viên hỏi lại về nhận xét | 2-3 lần/đợt | Giảm còn dưới 1 | Đếm tin nhắn hỏi lại trong nhóm Zalo |
| **Độ lệch band giữa TA và giáo viên chính** khi cùng chấm mù 1 bài | ±0.5 band | **Không tăng** | Mỗi tuần lấy 2 bài chấm chéo, so band |

Metric thứ tư là cái chặn kịch bản xấu nhất: TA nhanh hơn vì trôi theo draft của AI mà không đọc kỹ bài nữa.

**Non-AI alternative:**
Bank nhận xét mẫu cho ~20 lỗi thường gặp + checklist 4 tiêu chí. Rẻ, không rủi ro, và giải được đúng phần GRA — tức khoảng một nửa bottleneck. Đây là phương án phải thử trước, và nếu nó đã đủ thì không cần AI.

**AI hypothesis:**
AI quét bài theo cấu trúc 4 tiêu chí, bóc tách lỗi GRA/LR và draft nhận xét nháp cho phần lặp lại. TA đọc bài, viết phần TR/CC bằng phán đoán của mình, và **giữ quyền chấm band cuối**.

**Quick gut:**

```text
[ ] No AI   [ ] Rule   [x] Workflow   [ ] Agent   [ ] Chưa biết
```

### Draft workflow

```text
CURRENT STATE — ~30 phút/bài, ~9 tiếng/tuần

[1 Nhận bài: 2'] → [2 Đọc lướt xác định band sơ bộ: 3'] → [3 Đọc kỹ + gạch lỗi: 8']
→ [4 Viết nhận xét TR/CC/LR/GRA: 12']   <-- BOTTLENECK (7-8' lặp lại + 4-5' riêng)
→ [5 Chấm 4 tiêu chí + quy band: 2'] → [6 Nhập điểm: 1'] → [7 Gửi trả: 2']


FUTURE STATE — ~14 phút/bài, ~4.2 tiếng/tuần

[1 Học viên nộp qua form chuẩn: 0' với TA]
→ [2 Rule: check word count, đủ 2 task, đúng format]        -- KHÔNG cần AI
→ [3 AI gạch lỗi GRA/LR + draft nhận xét phần lặp: 1']      -- AI chỉ làm nửa lặp lại
→ [4 TA đọc bài + xác nhận lỗi + tự viết nhận xét TR/CC: 10'] <-- HUMAN BOUNDARY
→ [5 TA chấm 4 tiêu chí và band cuối: 2']                   <-- TA giữ quyền quyết định
→ [6 Auto nhập điểm + gửi trả: 1']

Cắt được ~7 phút ở đúng phần lặp lại. Phần cần phán đoán vẫn giữ nguyên cho TA.

Boundary:
- AI KHÔNG chấm band, KHÔNG nhận xét Task Response, KHÔNG gửi bài cho học viên.
- AI chỉ gạch lỗi GRA/LR và draft nhận xét cho phần lỗi lặp lại.
- Bài phải ẩn danh trước khi xử lý nếu trung tâm yêu cầu.

Fallback:
- Nhận xét AI sai ngữ cảnh → TA xóa draft, viết tay như quy trình cũ.
- Nếu độ lệch band với giáo viên chính vượt ±0.5 trong 2 tuần liên tiếp → dừng dùng AI,
  quay về bank nhận xét mẫu.

Bottleneck mới: bước 4 (TA đọc và xác nhận). Chấp nhận được vì đó là điểm kiểm soát chất lượng.
```

### Rủi ro

| Rủi ro | Ai phát hiện | Cách chặn |
|---|---|---|
| TA trôi theo draft, không đọc kỹ bài | Giáo viên chính, qua chấm chéo | Metric độ lệch band; bắt buộc chấm chéo 2 bài/tuần |
| AI khen bài lạc đề vì viết trôi chảy | TA, ở bước 4 | AI không được đụng vào TR |
| AI bịa lỗi không có trong bài | TA, ở bước 4 | TA xác nhận từng lỗi trước khi giữ lại |
| Bài học viên là dữ liệu trung tâm, bị đưa ra tool ngoài | Không ai — nên phải chặn từ đầu | Xin phép trung tâm trước; ẩn danh bài trước khi xử lý |

---

## Problem Card #2 — Dựng hồ sơ gọi vốn cho từng nhà đầu tư *(B)*

**Problem 1 câu:** Mỗi nhà đầu tư mới phải dựng lại một biến thể hồ sơ riêng, và vì deck, financial model, báo cáo traction cập nhật ở thời điểm khác nhau nên số liệu lệch nhau — bị phát hiện ngay trong buổi gặp.

**Actor:** Người phụ trách hồ sơ gọi vốn. Người chịu hậu quả trực tiếp là founder.

**Current workflow:**

```text
1. NĐT yêu cầu tài liệu → 2. Lục bản deck mới nhất (30') → 3. Gom số liệu cập nhật (90')
→ 4. Sửa deck theo góc quan tâm của NĐT (120') → 5. Đối chiếu chéo deck/model/one-pager (60')
→ 6. Gửi + trả lời follow-up (30')
```

**Bottleneck:** Bước 3 và 5. Gốc rễ là **không có một nguồn số liệu chuẩn duy nhất**.

**Impact:** ~4-6 tiếng/bộ hồ sơ, nhưng vấn đề lớn hơn là **rủi ro uy tín** — NĐT thấy hai con số lệch nhau sẽ nghi ngờ toàn bộ phần còn lại, và không sửa được sau buổi gặp.

**Success metric:** Thời gian dựng hồ sơ ~5 tiếng → dưới 2 tiếng (bấm giờ 3 bộ tiếp theo); số điểm lệch số liệu về 0 trước khi gửi (checklist đối chiếu bắt buộc).

**Non-AI alternative:** **Single source of truth** — một file số liệu duy nhất, deck tham chiếu trực tiếp tới nó. Rule thuần, giải gần trọn vấn đề lệch số.

**AI hypothesis:** AI viết lại narrative theo góc quan tâm từng NĐT, và soát chéo số trong bản nháp với file chuẩn. **Tuyệt đối không sinh hay ước lượng số liệu tài chính.**

**Quick gut:** `[x] Rule (trước)  [x] Workflow (sau)`

**Vì sao chưa chọn làm #1:** Phần lớn giá trị đến từ Rule chứ không phải AI, nên ít nguyên liệu để nhóm bàn về AI. Thêm nữa dữ liệu tài chính nhạy cảm, nhóm không validate được trong 4 tiếng lab.

---

## Problem Card #3 — Tổng hợp chi tiêu cá nhân *(C)*

**Problem 1 câu:** Chi tiêu rải qua tiền mặt, nhiều app ngân hàng và ví điện tử nên cuối tháng mất 60-90 phút nhập tay mà vẫn không biết chính xác đã tiêu bao nhiêu, đặc biệt không tách được khoản ứng trước cho công việc.

**Actor:** Chính tôi. Ảnh hưởng gián tiếp tới kế toán khi hoàn ứng.

**Current workflow:**

```text
1. Chi tiêu qua nhiều kênh → 2. Cuối tháng mở từng app (20') → 3. Nhập tay vào Excel (40')
→ 4. Tự phân loại (20') → 5. Phát hiện sót khoản tiền mặt → 6. Bỏ dở hoặc chấp nhận số sai
```

**Bottleneck:** Bước 3-4. Vì nhàm nên thường bỏ dở, dẫn tới cả tháng không có số liệu.

**Impact:** Không đặt được hạn mức chi tiêu. Nghiêm trọng hơn: vài khoản ứng trước cho công việc mỗi tháng không đòi lại được vì không còn bằng chứng.

**Success metric:** 60-90 phút → dưới 15 phút/tháng; tỷ lệ giao dịch ghi nhận ~60% → trên 90% (đối chiếu với biến động số dư thật).

**Non-AI alternative:** (1) app quản lý chi tiêu tự đọc biến động số dư, (2) **mọi khoản chi công việc trả bằng một thẻ riêng**.

**Quick gut:** `[x] No AI`

**Vì sao KHÔNG cần AI:**

- Phân loại chi tiêu có tập nhãn cố định, đáp án khá rõ — ô *độ mơ hồ thấp + phức tạp thấp*, Rule đã đủ.
- App ngân hàng đã làm việc này bằng rule từ lâu. Không cần build lại cái đã có.
- Phần đau nhất — tách chi cá nhân với chi công việc — giải trọn bằng một quy tắc dùng thẻ riêng, chi phí bằng 0.
- Phần còn lại là tiền mặt **không để lại dữ liệu**. Đây là bài toán thiếu input, AI không giải được.

---

# Card pitch và kết quả

Card tôi pitch:

```text
Card #1 — Chấm IELTS Writing và viết nhận xét 4 tiêu chí.
```

Vì sao tôi chọn pitch card này:

- Baseline sạch nhất trong 3 card: ~30 phút/bài, ~18 bài/tuần, đo được ngay tuần sau.
- Bottleneck tách được thành **nửa lặp lại và nửa cần phán đoán** — nên boundary người-máy không phải nói suông mà chỉ được đúng vào tiêu chí nào giao AI, tiêu chí nào giữ cho TA.
- Có non-AI alternative thật (bank nhận xét mẫu) giải được khoảng một nửa bottleneck, nên nhóm buộc phải tranh luận Rule trước rồi mới tới Workflow.
- Cả nhóm đều từng đi học nên hiểu domain, validate nhanh được với bạn bè đang luyện IELTS.

**Kết quả Phase 3:** nhóm chọn Card #1 làm candidate problem để đào sâu.

Lý do nhóm đưa ra khi chọn:

```text
- Workflow rõ và lặp đều nên đo trước/sau được trong phạm vi lab.
- Actor cụ thể, không phải "người dùng nói chung".
- Bottleneck là một bước cụ thể, lại còn tách được thành hai nửa khác tính chất.
- Có thể so sánh đủ No AI / Rule / Workflow / Agent, không mặc định chọn AI.
- Dễ validate: nhóm hỏi được người đang luyện IELTS và người từng chấm bài.
```

Câu hỏi tôi muốn nhóm challenge tiếp ở Phase 4-6:

```text
1. Bank nhận xét mẫu (Rule thuần) giải được bao nhiêu phần trăm? Nếu đã 70-80%
   thì nhóm có đang thêm AI vào chỉ vì muốn dùng AI không?
2. Nếu AI đưa sẵn nhận xét nháp, TA có bị trôi theo draft và đọc bài cẩu thả hơn không?
   Metric độ lệch band có đủ để bắt được điều đó không?
3. Bài viết của học viên là dữ liệu của trung tâm. Có được phép đưa lên tool AI bên ngoài không?
   Nếu không thì bài toán còn khả thi không?
4. Có bước nào thật sự cần AI tự quyết bước tiếp theo không? Nếu không thì Workflow là đủ,
   không cần Agent.
```

Câu hỏi tôi đã đặt cho bài của bạn khác khi nghe pitch:

```text
- Bạn đã vẽ được workflow hiện tại chưa, hay mới chỉ có cảm giác là nó chậm?
- Bottleneck là một BƯỚC cụ thể hay là cảm giác chung về cả quy trình?
- Bỏ AI ra, chỉ fix quy trình thôi thì giải được bao nhiêu phần trăm?
- Nếu AI sai ở bước đó thì ai phát hiện, và phát hiện sau bao lâu?
```

---

# Ghi chú nguồn số liệu và giả định

| Số liệu | Nguồn | Cần làm gì |
|---|---|---|
| 12 phút cho bước viết nhận xét | Ước lượng, chưa tách bước | **Cần đo** — con số quan trọng nhất của Card #1 |
| Tỷ lệ 7-8 phút lặp / 4-5 phút riêng | **Ước lượng thô** | Đo trên 5 bài — đây là căn cứ cho toàn bộ thiết kế boundary |
| ~30 phút/bài, ~18 bài/tuần | Ước lượng từ trải nghiệm | Bấm giờ 10 bài |
| Lỗi cơ bản lặp ở ~7/10 bài | Quan sát định tính | Đếm trên 10 bài gần nhất |
| Độ lệch band ±0.5 với giáo viên chính | **Chưa từng đo** | Chấm mù 2 bài với giáo viên chính để lấy baseline |
| ~4-6 tiếng/bộ hồ sơ gọi vốn | Ước lượng | Bấm giờ bộ tiếp theo |
| Tỷ lệ ghi nhận ~60% giao dịch | Ước lượng thô | Đối chiếu với biến động số dư thật |
| Toàn bộ số ở phần FUTURE workflow | **Giả định**, chưa chạy thử | Là target, không phải kết quả đo |

Giả định chưa kiểm chứng:

- **Quan trọng nhất** — giả định trung tâm cho phép đưa bài viết của học viên qua tool AI bên ngoài. Nếu không, phải chuyển sang phương án chạy nội bộ hoặc ẩn danh bài trước khi xử lý. Cần hỏi trước khi làm pilot.
- Giả định TA vẫn đọc kỹ bài dù đã có nhận xét nháp. Đây là rủi ro hành vi, phải theo dõi bằng metric độ lệch band.
- Giả định nhận xét nháp của AI đủ sát để sửa nhanh hơn tự viết. Nếu phải viết lại hơn 70% draft trong 2 tuần liên tiếp thì quay về bank nhận xét mẫu.
- Giả định AI đủ tin cậy ở GRA/LR. Cần kiểm bằng cách so lỗi AI gạch với lỗi TA gạch trên 5 bài, đếm số lỗi bịa và số lỗi bỏ sót.

---

# Tự kiểm Phase 1-2

- [x] 10 problems (đủ ngưỡng xét bonus +3), trải 4 bối cảnh và đủ 4 lăng kính.
- [x] Mỗi problem có actor và dấu hiệu thật.
- [x] Top 3 đến từ 3 bối cảnh và 3 mức giải pháp khác nhau.
- [x] Mỗi card đủ 9 field + workflow trước/sau.
- [x] Metric có hiện trạng, mục tiêu, cách đo — không viết "nhanh hơn".
- [x] Có **metric đối trọng** để chặn việc tối ưu tốc độ làm hỏng chất lượng.
- [x] Có một card kết luận **không cần AI** (Card #3).
- [x] Boundary chỉ được đúng tiêu chí nào giao AI, tiêu chí nào giữ cho người.
- [x] Ghi rõ giả định và số liệu chưa kiểm chứng.
- [ ] Đã bấm giờ thật để thay số ước lượng — *cần làm trước Phase 4*.
- [ ] Đã hỏi trung tâm về quyền đưa bài học viên qua tool AI — *chặn pilot nếu chưa có*.

---

*Day 02 Lab — 01 Individual Problem Scan*
