# Group Report — Day 02

**Candidate problem nhóm chọn:** Chấm IELTS Writing và viết nhận xét 4 tiêu chí.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|--------------------|
| 1   | Đoàn Đình Đông | 2A202601900| Chủ bài toán (TA IELTS, người nắm workflow thật) |
| 2   | Bùi Tiến Phát | 2A202601861 | Thành viên  (Hỗ trợ phân tích quy trình)|
| 3   | Dương Hải Long| 01607| Thành viên (Đóng góp ý tưởng về giải pháp)|
| 4   | Nguyễn Phú Cường|2A202601771 |Thành viên, phản biện, khảo sát, hỗ trợ làm nội dung |


# Phase 3 — Nhật ký hội tụ

## 3.1 — Trình bày top 3

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh |
|---|---|---|---|---|---|
| 1 | Đông | Chấm IELTS Writing + nhận xét 4 tiêu chí | TA, học viên luyện thi | Viết nhận xét 4 tiêu chí, 12'/bài | Workflow rõ, baseline sạch |
| 2 | Đông | Dựng hồ sơ gọi vốn cho từng NĐT | Người làm hồ sơ, founder | Gom số liệu + đối chiếu chéo tài liệu | Rủi ro cao, nhưng data nhạy cảm |
| 3 | Đông | Tổng hợp chi tiêu cá nhân | Cá nhân | Nhập tay + phân loại cuối tháng | Nhiều khả năng không cần AI |
| 4 | Cường | Viết nhận xét cuối tháng cho học sinh | Giáo viên | Suy nghĩ và gõ nhận xét (10-20 phút/em), bí từ và lặp từ | Workflow rõ ràng, dễ đo lường (10-20p/em), AI sinh văn bản tốt. |
| 5 | Cường | Tạo ra các bộ đề kiểm tra khác nhau | Giáo viên | Trộn đề thủ công (1-2 tiếng), dễ nhầm lẫn và chênh lệch độ khó | Bài toán ngốn công sức, tác động lớn, kết hợp Workflow/Rule và AI. |
| 6 | Cường | Trả lời tin nhắn lặp lại của phụ huynh | Giáo viên | Lặp lại việc tra cứu thông tin cũ và gõ trả lời nhiều lần | Vấn đề phổ biến, phù hợp phân tích Rule vs Agent/Chatbot. |
| 7 | Phát | Đọc hiểu slide bài giảng dài trước và sau buổi học | Học viên | Tự tra mạng tìm ví dụ giải thích các khái niệm khó (20 phút) | Cần thiết nhưng giải pháp thủ công vẫn ổn |
| 8 | Phát | Tìm lại các tài liệu cũ bị trôi trên Discord | Học viên | Tìm kiếm và lọc kết quả tìm kiếm thủ công (10 phút) | Phổ biến, hợp làm chatbot tìm kiếm bằng AI |
| 9 | Phát | Tổng hợp chi tiêu cá nhân cuối tháng | Học viên | Mất 60-90 phút/tháng để nhập tay vào ghi chú | Nhiều khả năng không cần AI, dùng thẻ cố định là đủ |
| 10 | Long | Điền thông tin cá nhân vào biểu mẫu | Người dùng phổ thông | Lặp lại hàng tuần, hơi mất thời gian | Cần AI để tăng tốc |
| 11 | Long | Người mới hỏi lại quy trình onboarding | HR, mentor |	Lặp lại nhiều lần | Mất thời gian, gây mệt mỏi |
| 12 | Long | Chuẩn bị recap sau mỗi meeting | Nhân viên văn phòng | Quá nhiều thông tin cần ghi | Mất rất nhiều công sức|

## 3.2 — Gom trùng / cluster

| Cluster | Candidates | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Đọc và nhận xét bài viết của người khác | #1, #4, #7, | Đọc một bản nháp rồi viết lại đánh giá theo bộ tiêu chí cố định | Có phần lặp và phần cần phán đoán, tách được |
| B. Gom dữ liệu rời rạc rồi viết lại cho người khác đọc | #2, #12 | Nhiều nguồn cập nhật lệch nhau, phải hợp nhất thủ công | Thường Rule giải được phần lớn |
| C. Nhập liệu và phân loại lặp lại | #3, #9, #10| Tập nhãn cố định, độ mơ hồ thấp | Rule hoặc tool có sẵn thường đủ |
| D. Tìm lại thông tin cũ | #5, #6, #8, #11 | Thông tin nằm rải nhiều nơi, đặt tên không thống nhất | Thường là vấn đề tổ chức, không phải vấn đề AI |

## 3.3 — Shortlist

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Chấm IELTS Writing | Có người trong nhóm nắm workflow thật; bottleneck là một bước cụ thể; đo trước/sau được trong lab | Dữ liệu bài học viên thuộc trung tâm, chưa rõ có được đưa qua tool ngoài không |
| Viết nhận xét cuối tháng cho học sinh | Nỗi đau phổ biến, đo lường rõ ràng (10-20p/em), phù hợp với thế mạnh tạo ngôn ngữ của AI | Nguy cơ AI bịa thông tin, phụ huynh có thể đánh giá là máy móc thiếu nhân văn |
| Tìm lại tài liệu trôi trên Discord | Vấn đề lặp lại liên tục, gây mất thời gian của cả lớp | Giới hạn quyền đọc tin nhắn và bảo mật Discord API |
| Chuẩn bị recap sau mỗi cuộc họp | Quá nhiều thông tin cần ghi, mất rất nhiều công sức, cần tool hỗ trợ | Ảo dữ liệu, ghi sai báo cáo |

## 3.4 — Score để đồng thuận

Chấm 1-5.

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Chấm IELTS Writing | 5 | 5 | 4 | 5 | 5 | 5 | 5 | **34** |
| Viết nhận xét cuối tháng cho học sinh | 5 | 4 | 4 | 5 | 4 | 4 | 4 | **30** |
| Tìm tài liệu trôi trên Discord | 4 | 4 | 4 | 4 | 4 | 4 | 4 | **28** |
| Chuẩn bị recap sau mỗi cuộc họp | 4 | 4 | 5 | 4 | 4 | 3 | 3 | **27** |

Candidate nhóm chọn:

Chấm IELTS Writing và viết nhận xét 4 tiêu chí.
```

Vì sao chọn:

- Có thành viên đang làm TA nên nắm workflow thật, không phải suy đoán.
- Actor cụ thể: TA chấm Writing cho 2 lớp (~18 học viên), không phải "người dùng nói chung".
- Bottleneck là **một bước cụ thể** (viết nhận xét, 12'/bài), lại còn tách được thành nửa lặp lại và nửa cần phán đoán.
- Có baseline thời gian và lặp hằng tuần nên đo trước/sau được ngay.
- So sánh được đủ No AI / Rule / Workflow / Agent — có phương án non-AI thật để tranh luận.
- Cả nhóm từng đi học nên validate nhanh được với bạn bè đang luyện IELTS.

Vì sao không chọn các candidate còn lại:

- **Hồ sơ gọi vốn:** rủi ro và độ khó hay, nhưng dữ liệu tài chính nhạy cảm nên nhóm không validate được trong 4 tiếng. Thêm nữa phần lớn giá trị đến từ Rule chứ không phải AI, ít nguyên liệu bàn về AI.
- **Chi tiêu cá nhân:** gần như chắc chắn kết luận "không cần AI", nên làm cả buổi sẽ không đủ chiều sâu để so sánh các mức.
- **Viết nhận xét cuối tháng cho học sinh:** Bài toán rất sát thực tế, nhưng việc chuẩn bị dữ liệu mẫu (điểm, thái độ của từng học sinh) ngay tại lab sẽ mất nhiều công sức giả lập. Hơn nữa, chất lượng của một đoạn "nhận xét" thường phụ thuộc nhiều vào cảm nhận cá nhân, khó đo lường độ chính xác (metric) một cách rạch ròi như việc lệch band điểm của bài thi IELTS.


Nếu có disagreement, nhóm xử lý thế nào:

- Ai không đồng ý: Nguyễn Phú Cường
- Lý do: Việc chấm IELTS Writing đòi hỏi đánh giá logic và tư duy, bắt buộc phải do con người (giáo viên/TA) làm. Giao cho AI sẽ làm giảm độ chính xác và mất đi tính chuyên môn
- Nhóm phản biện và chốt: Nhóm hoàn toàn đồng ý với Cường rằng việc quyết định điểm số và nhận xét nội dung (Task Response, Coherence) phải do con người làm. Tuy nhiên, khi mổ xẻ workflow, nhóm chỉ ra phần tốn thời gian nhất lại là việc lặp đi lặp lại thao tác gạch lỗi ngữ pháp, từ vựng cơ bản (GRA/LR). Nhóm thống nhất thiết lập Boundary rõ ràng: AI KHÔNG chấm bài, chỉ làm "trợ lý nháp" gạch lỗi vụn vặt. TA vẫn là người duyệt lỗi cuối cùng, viết nhận xét tư duy và chốt band điểm. Sau khi phân định rạch ròi giới hạn của AI, Cường đã đồng ý


---


# Phase 4 — Validation + Research

## 4.1 — Quick validation


Câu hỏi phỏng vấn dùng chung:

```text
Với người chấm bài:
1. Lần gần nhất bạn chấm một bài Writing là khi nào, mất bao lâu?
2. Trong 4 tiêu chí, tiêu chí nào bạn viết nhận xét mất thời gian nhất?
3. Bạn có hay viết lại cùng một nhận xét cho nhiều học viên không? Khoảng bao nhiêu phần trăm?
4. Nếu có công cụ gạch sẵn lỗi ngữ pháp, bạn có tin và dùng không? Vì sao?

Với người học:
1. Bạn thường chờ bao lâu để nhận kết quả chấm?
2. Nhận xét bạn nhận được có đủ rõ để biết phải sửa gì không?
3. Bạn có nhận ra mình lặp cùng một lỗi qua nhiều bài không?
4. Nếu nhận kết quả trong 1 tiếng nhưng nhận xét ngắn hơn, bạn có chọn không?
```

Kết quả:

| Nguồn | Số người / mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---|---|---|---|
| Interview người chấm bài | 0 | | | |
| Interview / poll người học | 2 | Chờ lâu (1-2 ngày). Nhận xét cực ngắn, chung chung. Hay lặp lỗi cũ. <br> ![Minh chứng 1](../01-individual-problem-scan/01-individual-problem-scan-workflow-card-1.png) <br> ![Minh chứng 2](../01-individual-problem-scan/01-individual-problem-scan-workflow-card-2.png) | Không chấp nhận đổi chất lượng nhận xét lấy tốc độ trả bài nhanh (1 tiếng). | Giữ nguyên trọng tâm vào chất lượng. AI chỉ hỗ trợ gạch lỗi ngữ pháp, không thay thế TA viết nhận xét chung chung. |
| Log / lịch sử chat / bảng điểm thật | 0 | | | |


Insight sau validation:


1. Vấn đề cốt lõi của người học không nằm ở việc trả bài chậm, mà nằm ở chất lượng phản hồi. Họ thà đợi 1-2 ngày còn hơn nhận bài sớm (trong 1 tiếng) mà nhận xét hời hợt, chung chung.
2. Việc nhận xét cực ngắn ở hiện tại dẫn đến hệ quả là học viên không biết cách sửa và liên tục lặp lại lỗi cũ ở các bài sau.
3. Điều này khẳng định hướng giải quyết của nhóm là ĐÚNG ĐẮN: Dùng AI xử lý các lỗi vụn vặt tốn thời gian (GRA/LR), và bắt buộc TA phải là người duyệt cuối để viết nhận xét nội dung chi tiết (Task Response) nhằm đảm bảo chất lượng.


## 4.2 — Research giải pháp đã có


> Nhóm phải tự mở lại từng link và tự kiểm trước khi dùng. Không trích số liệu chưa verify.


| Nguồn / tool | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| HyperWrite IELTS Essay Checker | https://www.hyperwriteai.com/aitools/ielts-essay-checker | Chấm cả 4 tiêu chí và cho band từng tiêu chí — tức chồng lên toàn bộ bước 5 và 6 của workflow | Có sẵn, dùng ngay, không phải build | Chấm luôn cả band, đúng phần nhóm muốn giữ cho TA | Phần "AI chấm IELTS" đã là hàng phổ thông. Không cần build lại, nhưng cũng không dùng nguyên trạng vì nó vượt boundary nhóm đặt |
| IELTS Online Preparation — Writing Evaluator | https://www.ieltsonlinepreparation.com/writing-evaluator | Band + feedback tức thì cho Task 1 và Task 2 | Nhanh, miễn phí, học viên tự dùng được | Không gắn vào quy trình lớp: TA vẫn phải nhập điểm, theo dõi tiến độ, trả bài | Giá trị nhóm tạo ra không nằm ở model, nằm ở chỗ ghép AI vào workflow của TA |
| ETS e-rater — how it works | https://www.ets.org/erater/how.html | Engine chấm tự động dùng trong thi chuẩn hóa | Có cơ chế **advisory flag**: tự đánh dấu bài lạc đề hoặc bất thường để **đẩy về người xem lại** | Chính ETS cũng không để máy tự quyết với bài bị flag | Xác nhận thiết kế của nhóm: bài nghi lạc đề phải đẩy về người, AI không được kết luận |
| ETS — nghiên cứu đánh giá advisory flags | https://www.ets.org/research/policy_research_reports/publications/report/2016/jwnv.html | Đo độ tin cậy của từng loại flag | Có bằng chứng: các flag hoạt động **không đồng đều** | Không phải cảnh báo tự động nào cũng đáng tin | Không tin tuyệt đối vào cảnh báo của máy; vẫn cần người kiểm |
| LLM và automated essay scoring cho người học tiếng Anh | https://www.sciencedirect.com/science/article/pii/S2666920X24000353 | Nghiên cứu validity và reliability khi dùng LLM chấm bài của English language learner | Đúng đối tượng học viên của nhóm | Nhóm phải tự đọc và tự trích kết luận, không trích qua tóm tắt | Nguồn học thuật gần nhất với bài toán — đọc trước khi chốt quyết định |
| Systematic literature review về AES | https://pmc.ncbi.nlm.nih.gov/articles/PMC8460059/ | Tổng quan hạn chế của automated essay scoring | Chỉ ra AES yếu ở nội dung/ngữ nghĩa và dễ bị "gaming" bằng văn mẫu | Là tổng quan, không phải kết quả cho riêng IELTS | Củng cố lý do giữ Task Response cho người chấm |
| Grammarly | https://www.grammarly.com/ | Chỉ bước gạch lỗi ngữ pháp và từ vựng | Đã rất tốt ở đúng phần nhóm định giao cho AI | Không biết tiêu chí IELTS, không cho band | Phần GRA/LR có thể dùng tool sẵn, không cần tự làm |


**Research takeaway - phần này đã làm nhóm sửa lại cách nghĩ:**

1. AI chấm IELTS Writing KHÔNG phải ý tưởng mới. Có hàng chục tool miễn phí cho band
   trong 30 giây. Vậy câu hỏi của nhóm không còn là "AI có chấm được không"
   mà là "NÊN để AI chấm tới đâu".


2. Điều đáng chú ý: gần như mọi tool sẵn có đều làm đúng cái nhóm quyết định KHÔNG làm —
   chấm band thay người. Nhóm không đi theo vì band phụ thuộc nặng vào Task Response,
   mà đó là tiêu chí AI yếu nhất.


3. Nghiên cứu AES chỉ ra đúng điểm yếu nhóm đã dự đoán: yếu ở nội dung và ngữ nghĩa,
   dễ bị gaming bằng văn mẫu, và bài lạc đề cần được flag để người xem lại.
   Ngay cả ETS cũng thiết kế theo hướng máy flag → người quyết.


4. Hệ quả: phương án thay thế mạnh hơn nhóm tưởng. Học viên có thể tự dùng tool miễn phí
   để tự soát lỗi trước khi nộp — cách này không tốn gì và giảm tải cho TA ngay từ đầu vào.
   Nhóm phải so sánh với phương án này, không chỉ so với hiện trạng.


---

# Phase 5 — Workflow + Problem Statement

## 5.1 — Current workflow bản nhóm

| Bước | Actor | Input | Output | Thời gian | Handoff | Ghi chú |
|---|---|---|---|---|---|---|
| 1 | Học viên | Đề bài | File bài nộp | — | HV → TA | Nộp qua Zalo hoặc Drive, không thống nhất |
| 2 | TA | File bài | Hàng chờ chấm | 2'/bài | — | Bài dồn lại, thường chấm theo đợt cuối tuần |
| 3 | TA | Bài viết | Band ước lượng sơ bộ | 3'/bài | — | |
| 4 | TA | Bài viết | Bài đã gạch lỗi GRA/LR | 8'/bài | — | Lỗi cơ bản lặp ở ~7/10 bài |
| 5 | TA | Bài đã gạch lỗi | Nhận xét TR/CC/LR/GRA | **12'/bài** | — | **BOTTLENECK** |
| 6 | TA | Nhận xét | Điểm 4 tiêu chí + band tổng | 2'/bài | — | |
| 7 | TA | Band | Bảng theo dõi lớp | 1'/bài | TA → GV chính | |
| 8 | TA | Bài + nhận xét | Bài đã chấm | 2'/bài | TA → HV | |

Bottleneck chính:


Bước 5 — viết nhận xét 4 tiêu chí, 12 phút/bài.

Tách ra thì 12 phút đó gồm hai nửa khác hẳn nhau:
- ~7-8 phút: nhận xét lỗi ngữ pháp/từ vựng cơ bản, lặp gần như giống nhau giữa các bài
- ~4-5 phút: nhận xét riêng theo nội dung bài, cần phán đoán của người chấm

Đây là điểm quan trọng nhất: bottleneck không phải "chấm bài" nói chung,
mà là NỬA LẶP LẠI trong bước 5.

**Một quan sát riêng của nhóm — khoảng cách giữa thời gian xử lý và thời gian chờ:**

Thời gian TA thật sự xử lý 1 bài:  ~30 phút
Thời gian học viên thật sự chờ:    2-3 ngày

Chênh lệch đó KHÔNG đến từ việc chấm chậm, mà từ việc bài nằm trong hàng chờ
(bước 2) cho tới khi TA gom đủ một đợt mới chấm.

Hệ quả cho thiết kế: giảm thời gian xử lý từ 30 xuống 14 phút KHÔNG tự động
cho ra trả bài trong 24 giờ. Muốn đạt metric đó phải đồng thời đổi cách gom bài —
chấm rải trong tuần thay vì dồn cuối tuần. Đây là phần fix quy trình, không cần AI.
``
## 5.2 — Future workflow bản nhóm


FUTURE STATE — ~14 phút/bài


[1 HV nộp qua form chuẩn]                                  -- Rule: gom một đầu mối
→ [2 Rule: check word count, đủ 2 task, đúng format]       -- Rule, tự động, không cần AI
→ [3 Rule: chấm rải trong tuần thay vì dồn cuối tuần]      -- fix quy trình, giải phần lead time
→ [4 AI gạch lỗi GRA/LR + draft nhận xét phần lặp: 1']     -- AI, chỉ làm nửa lặp lại
→ [5 TA đọc bài, xác nhận lỗi, tự viết nhận xét TR/CC: 10'] <-- HUMAN BOUNDARY
→ [6 TA chấm 4 tiêu chí và band cuối: 2']                   <-- TA giữ quyền quyết định
→ [7 Auto nhập điểm + gửi trả: 1']
BOUNDARY — AI được và không được làm gì:
✓ Được: gạch lỗi ngữ pháp/từ vựng, draft nhận xét cho phần lỗi lặp lại
✗ Không: chấm band, nhận xét Task Response, gửi bài cho học viên,
         kết luận bài có lạc đề hay không (chỉ được flag để TA xem)
FALLBACK:
- Nhận xét AI sai ngữ cảnh → TA xóa draft, viết tay như quy trình cũ.
- Độ lệch band với giáo viên chính vượt ±0.5 trong 2 tuần liên tiếp → dừng AI,
  quay về bank nhận xét mẫu.
- TA phải viết lại hơn 70% draft trong 2 tuần liên tiếp → hạ về Rule.
BOTTLENECK MỚI: bước 5 (TA đọc và xác nhận).
Chấp nhận được, vì đó chính là điểm kiểm soát chất lượng.
```
Before/after impact:

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Số bước | 8 | 7 | Không chỉ giảm bước, mà giảm effort ở bước nặng nhất |
| Tổng thời gian xử lý/bài | ~30 phút | ~14 phút | Cắt đúng ~7 phút ở nửa lặp lại của bước 5 |
| Thời gian học viên chờ | 2-3 ngày | Trong 24 giờ | Đến từ **fix quy trình** (chấm rải), không phải từ AI |
| Số bước thủ công | 7/8 | 3/7 | TA vẫn đọc bài, viết TR/CC và chấm band |
| Bottleneck chính | Viết nhận xét 4 tiêu chí | TA đọc và xác nhận | Human boundary, cố ý giữ |
| Risk mới | Không có | AI bịa lỗi; TA trôi theo draft | Chặn bằng metric độ lệch band + chấm chéo 2 bài/tuần |
| Risk mới | Không có | Dữ liệu bài học viên ra tool ngoài | **Chặn bằng việc xin phép trung tâm trước khi pilot** |

## 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | TA IELTS chấm Writing cho 2 lớp (~18 học viên/tuần), báo cáo cho giáo viên chính. |
| **Workflow** | Học viên nộp bài → TA xếp hàng chờ → đọc lướt ước lượng band → đọc kỹ gạch lỗi → viết nhận xét 4 tiêu chí → chấm band → nhập điểm → gửi trả. |
| **Bottleneck** | Viết nhận xét 4 tiêu chí, 12 phút/bài, trong đó ~7-8 phút là gõ lại các lỗi ngữ pháp/từ vựng cơ bản đã viết cho học viên khác. |
| **Impact** | ~9 tiếng/tuần cho 1 TA. Khi dồn bài thì chấm vội, nhận xét chung chung, học viên hỏi lại 2-3 lần mỗi đợt ảnh hưởng đến tiến độ và không nhận ra mình lặp cùng pattern lỗi. Học viên chờ 2-3 ngày mỗi bài. |
| **Success Metric** | Thời gian xử lý 30 → dưới 15 phút/bài; thời gian chờ 2-3 ngày → trong 24 giờ; số lần hỏi lại 2-3 → dưới 1 lần/đợt; **độ lệch band giữa TA và giáo viên chính không vượt ±0.5**. |
| **Boundary** | AI không chấm band, không nhận xét Task Response, không gửi bài cho học viên. AI chỉ gạch lỗi GRA/LR và draft nhận xét phần lặp lại. |
---

# Phase 6 — Rule / Workflow / Agent + Decision

## 6.0 — Ma trận độ phù hợp

Bài toán của nhóm nằm ở ô nào:

Bài toán KHÔNG nằm gọn một ô. Tách theo 4 tiêu chí IELTS thì thấy rõ:


                    | Độ mơ hồ thấp        | Độ mơ hồ cao
--------------------|----------------------|---------------------------
Độ phức tạp thấp    | GRA, LR              | TR, CC
                    | → Rule hoặc AI hỗ trợ| → Workflow có AI hỗ trợ,
                    |   là đủ              |   hoặc giữ cho người
--------------------|----------------------|---------------------------
Độ phức tạp cao     | (không có phần nào)  | (không có phần nào)
```

Vì sao:

- **GRA** (sai thì, thiếu mạo từ, sai word form): có đúng/sai rõ ràng → độ mơ hồ thấp. Input là một bài viết, output là danh sách lỗi → độ phức tạp thấp.
- **LR** (lặp từ, collocation sai): độ mơ hồ thấp–trung, vẫn có chuẩn tương đối rõ.
- **CC, TR** (bài có trả lời đúng câu hỏi không, lập luận đủ sức không): nhiều cách viết đều chấp nhận được → độ mơ hồ cao.
- **Không phần nào rơi vào ô phức tạp cao.** Workflow tuyến tính, không có bước nào phụ thuộc kết quả bước trước để đổi hướng.
Tự kiểm nhanh:

| Câu hỏi | Trả lời | Suy ra |
|---|---|---|
| Output khác nhau mỗi lần vẫn chấp nhận được không? | Với GRA/LR: không. Với TR/CC: có | Bài toán hỗn hợp, phải tách |
| Cần phối hợp 3+ bước hoặc 3+ nguồn dữ liệu không? | Không — một bài viết, một bộ tiêu chí | độ phức tạp thấp |
| AI có cần tự quyết định bước tiếp theo không? | Không — thứ tự cố định | **Rule/Workflow là đủ, không cần Agent** |
## 6.1 — So sánh No AI / Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Học viên tự dùng tool miễn phí soát lỗi trước khi nộp; TA chấm rải trong tuần thay vì dồn cuối tuần | Đủ để giải phần **lead time** 2-3 ngày và giảm lỗi cơ bản ngay từ đầu vào | Không giảm được thời gian TA viết nhận xét | **Chọn — làm trước, vì chi phí bằng 0** |
| **Rule** | Bank ~20 nhận xét mẫu cho lỗi thường gặp + checklist 4 tiêu chí + check format tự động | Đủ nếu bank phủ được phần lớn lỗi GRA lặp lại | Không viết được nhận xét bám nội dung riêng từng bài | **Chọn — làm trước AI, để đo xem còn lại bao nhiêu** |
| **Workflow** | Rule check format → AI gạch lỗi GRA/LR và draft nhận xét phần lặp → TA xác nhận, viết TR/CC → TA chấm band | Hợp vì các bước cố định, AI chỉ đảm nhiệm một bước ngôn ngữ có độ mơ hồ thấp | AI bịa lỗi; TA trôi theo draft; dữ liệu học viên ra ngoài | **Chọn — nhưng chỉ sau khi No AI + Rule đã chạy và vẫn còn nghẽn** |
| **Agent** | Agent tự đọc bài, tự quyết cần kiểm gì, tự tra band descriptor, tự chấm và tự gửi trả | Chỉ cần nếu workflow có nhiều nhánh và AI phải tự đổi bước tiếp theo | Không có bước nào cần tự lập kế hoạch. Giao band cho AI là giao đúng phần nó yếu nhất | **Không chọn** |

Mức chọn:
Workflow — nhưng theo thứ tự: No AI → Rule → rồi mới tới Workflow.
Vì sao chọn Workflow:
- Bottleneck nằm ở một bước ngôn ngữ cụ thể mà AI làm tốt (gạch lỗi GRA/LR).
- Các bước cố định, không cần AI tự lập kế hoạch.
- TA vẫn xác nhận từng lỗi và chấm band nên rủi ro kiểm soát được.
- Research xác nhận hướng này: ngay cả ETS cũng thiết kế theo kiểu máy flag, người quyết.
Vì sao không chọn mức đơn giản hơn:
- No AI và Rule **giải được một phần, nhưng không phải phần lớn nhất**. Chúng xử lý được lead time và phần lỗi GRA phổ biến, nhưng không viết được nhận xét bám nội dung riêng của từng bài — mà đó là thứ khiến học viên hỏi lại.
- Tuy nhiên nhóm **không bỏ qua** hai mức này: đây là điều kiện phải chạy trước để biết AI còn phải giải bao nhiêu. Nếu Rule đã giảm hơn 50% thời gian bước 5, nhóm dừng ở Rule.
Vì sao không chọn Agent:

- Không có bước nào cần AI tự quyết định bước tiếp theo.
- Band phụ thuộc nặng vào Task Response — tiêu chí AI yếu nhất. Giao quyền chấm cho Agent là giao đúng phần nó dở nhất.
- Rủi ro tăng mạnh (tự gửi bài cho học viên) mà không thêm giá trị tương ứng.
## 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | TA IELTS chấm Writing cho 2 lớp (~18 học viên/tuần), báo cáo cho giáo viên chính. |
| **Workflow** | HV nộp → TA xếp hàng chờ → đọc lướt ước lượng band → đọc kỹ gạch lỗi → viết nhận xét 4 tiêu chí → chấm band → nhập điểm → gửi trả. |
| **Bottleneck** | Viết nhận xét 4 tiêu chí (12'/bài), trong đó ~7-8 phút là gõ lại lỗi GRA/LR cơ bản đã viết cho học viên khác. Riêng thời gian chờ 2-3 ngày đến từ việc dồn bài, không phải từ tốc độ chấm. |
| **Impact** | ~9 tiếng/tuần/TA. Chấm vội → nhận xét chung chung → HV hỏi lại 2-3 lần/đợt và không thấy pattern lỗi lặp của mình. |
| **Success Metric** | Xử lý 30 → dưới 15 phút/bài. Chờ 2-3 ngày → trong 24 giờ. Hỏi lại 2-3 → dưới 1 lần/đợt. **Đối trọng: độ lệch band TA vs giáo viên chính không vượt ±0.5** (chấm chéo mù 2 bài/tuần). |
| **Boundary** | AI **được** gạch lỗi GRA/LR, draft nhận xét phần lặp, flag bài nghi lạc đề. AI **không được** chấm band, nhận xét Task Response, kết luận bài lạc đề, gửi bài cho học viên. |
| **AI intervention point** | Sau khi bài qua check format tự động, trước khi TA viết nhận xét — tức chen vào giữa bước 4 và 5 của workflow cũ. |
| **Mức chọn** | Workflow. Triển khai theo thứ tự No AI → Rule → Workflow, chỉ lên mức sau khi mức trước đã chạy và vẫn còn nghẽn. |
| **Rủi ro & người thật kiểm tra** | *Rủi ro:* AI bịa lỗi không có trong bài; AI khen bài lạc đề vì viết trôi chảy; TA trôi theo draft nên đọc cẩu thả; bài học viên ra tool ngoài. *Người kiểm:* TA xác nhận từng lỗi trước khi giữ lại và tự chấm band; giáo viên chính chấm chéo mù 2 bài/tuần để bắt trường hợp TA trôi theo AI. |


## 6.3 — Final decision


| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor và workflow đã rõ chưa? | **Yes** | Có thành viên đang làm TA, vẽ được workflow 8 bước với thời gian từng bước |
| Baseline và success metric đã đo được chưa? | **Not Yet** | Các con số hiện là ước lượng. Chưa bấm giờ, chưa đo độ lệch band |
| Có data/input đủ dùng chưa? | **Not Yet** | Có bài viết, nhưng **chưa xin phép trung tâm** đưa bài học viên qua tool AI ngoài |
| Nếu AI sai, hậu quả có chấp nhận được không? | **Yes** | TA vẫn chấm band và xác nhận từng lỗi. Sai thì sửa được, không như bài gọi vốn |
| Có người review/owner vận hành không? | **Yes** | TA review từng bài; giáo viên chính chấm chéo để kiểm chính TA |
| Có cách non-AI đơn giản hơn không? | **Yes — và chưa thử** | Chấm rải trong tuần + bank nhận xét mẫu. Research còn cho thấy HV tự dùng tool miễn phí soát trước khi nộp |


Decision:


```text
NOT YET — có 2 gate cụ thể. Gỡ xong cả hai thì Go ở scope nhỏ.
```


Lý do:


- Hai câu trả lời "Not Yet" ở trên đều là **chặn thật**, không phải chi tiết nhỏ: chưa có baseline đo được thì không chứng minh được cải thiện; chưa có quyền dùng dữ liệu thì pilot là vi phạm.
- Câu cuối quan trọng nhất: **có cách non-AI đơn giản hơn và nhóm chưa thử**. Chọn Go ngay lúc này sẽ đúng vào lỗi "quyết định vì muốn làm AI".
- Đây không phải do dự. Đây là Go có điều kiện, với hai gate đo được và mốc thời gian 2 tuần.


**Gate 1 — Quyền dùng dữ liệu (chặn cứng)**


```text
Hỏi trung tâm: bài viết của học viên có được đưa qua công cụ AI bên ngoài không?
- Nếu KHÔNG  → No-Go cho phương án dùng tool ngoài.
               Chuyển sang: ẩn danh bài trước khi xử lý, hoặc chỉ làm phần Rule.
- Nếu CÓ     → qua gate 1.
```


**Gate 2 — Thử phương án rẻ trước (2 tuần)**


```text
Tuần 1: đo baseline thật.
  - Bấm giờ 10 bài, tách riêng thời gian bước 5.
  - Đo tỷ lệ thời gian nhận xét lặp / nhận xét riêng.
  - Chấm chéo mù 2 bài với giáo viên chính để lấy baseline độ lệch band.


Tuần 2: chạy No AI + Rule.
  - Chấm rải trong tuần thay vì dồn cuối tuần → đo lại thời gian chờ của học viên.
  - Dùng bank ~20 nhận xét mẫu → đo lại thời gian bước 5.


Điều kiện qua gate:
- Nếu Rule đã giảm bước 5 xuống dưới 6 phút → DỪNG Ở RULE, không cần AI.
- If step 5 is still above 9 minutes → pass gate 2, initiate Workflow pilot.
```


Nếu qua cả 2 gate, pilot nhỏ nhất:


```text
- Phạm vi: 1 lớp, 10 bài, trong 1 tuần.
- Cách chạy: bán thủ công. TA paste bài (đã ẩn danh) vào prompt chuẩn theo 4 tiêu chí.
  AI trả về danh sách lỗi GRA/LR + nhận xét nháp cho phần lặp.
- TA xác nhận từng lỗi, tự viết TR/CC, tự chấm band.
- Đo: thời gian bước 5; % draft phải viết lại; số lỗi AI bịa; số lỗi AI bỏ sót;
  độ lệch band với giáo viên chính.


Rollback:
- TA phải viết lại hơn 70% draft trong 2 tuần liên tiếp → về Rule.
- Độ lệch band vượt ±0.5 trong 2 tuần liên tiếp → dừng AI ngay.
- AI bịa lỗi không có trong bài quá 1 lần/10 bài → dừng, đổi cách prompt hoặc đổi tool.
```
