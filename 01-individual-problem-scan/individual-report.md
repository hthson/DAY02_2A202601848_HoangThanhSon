# 01 — Individual Problem Scan

---

## Phase 1 — Individual Scan

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (Evidence / Impact) |
|---|---|---|---|---|
| 1 | Lặp lại | Mỗi cuối tuần phải thu thập tin nhắn, file cập nhật và ghi chú từ các thành viên để tổng hợp báo cáo tiến độ tuần của nhóm. | Team Leader, các thành viên trong nhóm | Phải copy-paste, đọc lướt nhiều kênh chat và phân loại thủ công công việc. |
| 2 | Tốn thời gian | Đọc và tóm tắt tài liệu đề cương học tập / báo cáo nghiên cứu dài (20-30 trang) trước khi họp hoặc ôn thi. | Sinh viên, Nhân viên văn phòng | Rất khó trích xuất nhanh các ý chính và danh sách việc cần làm. |
| 3 | Tốn thời gian | Nghe lại file ghi âm cuộc họp online kéo dài 1-2 tiếng để viết Meeting Recap và phân công danh sách công việc (Action Items). | Thư ký cuộc họp, Team Leader | Dễ bỏ sót các thỏa thuận quan trọng hoặc deadline được giao. |
| 4 | Pain từ người khác | Lên kế hoạch ăn uống, lịch trình đi lại và tính toán phân chia chi phí chuyến đi cho nhóm đông người. | Trưởng nhóm | Nhập liệu thủ công từng hóa đơn lẻ và giải quyết thắc mắc về tiền bạc. |
| 5 | AI có thể tốt hơn | Tìm lại các quyết định cũ, thông báo quan trọng hoặc file tài liệu bị trôi trong các kênh chat nhóm (Discord / Zalo / Slack). | Thành viên nhóm, Nhân viên | Search từ khóa truyền thống không hiểu ngữ cảnh câu hỏi. |
| 6 | Lặp lại | Thu thập và nhập liệu thông tin chi tiêu từ hình ảnh hóa đơn / tin nhắn ngân hàng vào sổ theo dõi chi tiêu cá nhân hoặc quỹ nhóm. | Người quản lý quỹ | Gõ lại từng số tiền, ngày tháng và tên món đồ thủ công. |
| 7 | Pain từ người khác | Trả lời lặp đi lặp lại các câu hỏi của thành viên mới về quy trình làm việc, mẫu file nộp bài và tài liệu hướng dẫn nhóm. | Team Leader, Mentor | Trả lời 5-8 lần/tuần. Tốn thời gian tìm lại link cũ và gõ lại cùng một câu trả lời. |
| 8 | AI có thể tốt hơn | Lập lịch biểu công việc tuần và sắp xếp thứ tự ưu tiên khi có quá nhiều deadline bài tập/dự án trùng nhau. | Sinh viên | Loay hoay sắp xếp lịch nhưng vẫn bị quá tải hoặc quên công việc quan trọng. |
| 9 | Tốn thời gian | Đọc và rà soát toàn bộ yêu cầu đề bài đồ án / hợp đồng để lập danh sách kiểm tra (Checklist) các tiêu chí không được bỏ sót. | Sinh viên | Dễ bỏ sót các yêu cầu phụ hoặc quy chuẩn trình bày. |

---

## Phase 2 — Top 3 Problem Cards & Draft Workflow

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Mỗi cuối tuần phải thu thập tin nhắn, file cập nhật và ghi chú từ các thành viên để tổng hợp báo cáo tiến độ tuần của nhóm | Workflow rõ ràng, diễn ra đều đặn mỗi tuần, tốn thời gian cố định (90 phút), đo lường được metric chính xác. | Mức độ AI draft narrative có phản ánh đúng thực tế công việc của nhóm hay không. |
| 2 | Đọc và tóm tắt tài liệu đề cương học tập / báo cáo nghiên cứu dài (20-30 trang) trước khi họp hoặc ôn thi | Pain point lớn về lượng đọc hiểu văn bản, tần suất gặp thường xuyên trước kỳ thi/buổi họp. | Khả năng AI bảo toàn chính xác các thuật ngữ chuyên ngành trong tài liệu. |
| 3 | Nghe lại file ghi âm cuộc họp online kéo dài 1-2 tiếng để viết Meeting Recap và phân công danh sách công việc (Action Items) | Pain point thực tế của người làm thư ký/leader sau các buổi họp dài, dễ bị trễ phân công việc. | Chất lượng âm thanh file ghi âm có ảnh hưởng đến độ chính xác khi AI tóm tắt hay không. |

---

### Problem Card #1 (RANK 1) — Tổng hợp Báo cáo Tiến độ Tuần của Nhóm

```text
┌─────────────────────────────────────────────────────────────────────────┐
│ PROBLEM CARD #1                                                         │
│                                                                         │
│ Problem 1 câu: Mỗi cuối tuần Leader tốn 90 phút gom dữ liệu rải rác    │
│ (tin nhắn, file nốt, bảng theo dõi) để viết báo cáo tiến độ, trong đó   │
│ bước tổng hợp narrative bị nghẽn và dễ trễ deadline.                   │
│                                                                         │
│ Ai chịu ảnh hưởng? Team Leader, Giáo viên hướng dẫn / Quản lý           │
│                                                                         │
│ Workflow hiện tại:                                                      │
│ 1. Lấy thông tin từ bảng công việc → 2. Đọc tin nhắn cập nhật           │
│ → 3. Gom nốt cá nhân → 4. Viết narrative báo cáo → 5. Format & Gửi      │
│                                                                         │
│ Bước nghẽn nhất: Viết narrative & tổng hợp rủi ro (35 phút/lần)         │
│                                                                         │
│ Đo thành công bằng gì? Giảm thời gian tổng hợp từ 90 phút → 20 phút/tuần│
│                                                                         │
│ Quick gut: [x] Workflow  [ ] Rule  [ ] Agent  [ ] No AI                 │
└─────────────────────────────────────────────────────────────────────────┘
```

#### Chi tiết Problem Card #1:
* **Problem 1 câu:** Trưởng nhóm mất 90 phút mỗi cuối tuần để thu thập dữ liệu công việc rải rác từ các kênh chat và file ghi chú nhằm tổng hợp báo cáo tiến độ, trong đó bước phân tích thông tin và viết đoạn văn tóm tắt tiến độ/rủi ro tốn thời gian nhất và dễ bị trễ deadline.
* **Actor:** Team Leader / Người quản lý nhóm nhỏ.
* **Thời điểm / bối cảnh:** Tối Chủ Nhật hoặc sáng Thứ Hai hàng tuần trước buổi báo cáo tiến độ với Quản lý/Giảng viên.
* **Current workflow (7 bước):**
  1. Mở bảng theo dõi công việc (Trello/Google Sheets) để xem danh sách việc hoàn thành & tồn đọng (15 phút).
  2. Đọc lại các tin nhắn cập nhật công việc trong kênh chat nhóm (15 phút).
  3. Gom các nốt ghi chú cá nhân và báo cáo lẻ của các thành viên (15 phút).
  4. Mở file tài liệu báo cáo tuần cũ và chép dữ liệu thô vào (10 phút).
  5. Viết đoạn narrative tóm tắt: công việc đã hoàn thành, vấn đề đang nghẽn, dự kiến tuần tới (35 phút - **Bottleneck**).
  6. Kiểm tra lại thông tin và chỉnh sửa định dạng văn bản (5 phút).
  7. Gửi báo cáo qua email hoặc đăng lên kênh thông báo chung (5 phút).
* **Bottleneck:** Bước 5 (Viết narrative tiến độ & rủi ro) tốn 35 phút vì phải tổng hợp dữ liệu thô thành đoạn văn đánh giá có logic và rõ ràng.
* **Impact:** Mất 90 phút/tuần cho 1 leader. Báo cáo gửi chậm khiến người quản lý/giảng viên không nắm kịp rủi ro để hỗ trợ.
* **Success metric:** 
  * Giảm tổng thời gian làm báo cáo từ **90 phút xuống dưới 20 phút/tuần**.
  * Giảm thời gian viết narrative từ **35 phút xuống còn 3-5 phút (chỉ cần người review chỉnh sửa)**.
  * 100% báo cáo nộp đúng hạn.
* **Non-AI alternative:** Dùng Google Forms / Sheets Template bắt buộc mọi người tự điền. *Hạn chế:* Dữ liệu thu được rời rạc, khô cứng và vẫn cần leader tự đọc rồi gọt giũa thành văn bản hoàn chỉnh.
* **AI hypothesis:** Sử dụng AI Workflow tự động thu thập thông tin cập nhật, cấu trúc lại dữ liệu thô và sinh bản nháp narrative (Draft narrative). Leader chỉ cần review, chỉnh sửa và gửi.
* **Quick gut:** **Workflow** (Tự động hóa gom dữ liệu + AI hỗ trợ viết bản nháp ở bước nghẽn).

#### Draft Workflow trước & sau cho Problem #1:

##### Current State (Hiện tại — 90 phút)
```text
[1. Xem bảng công việc: 15'] 
   ─► [2. Đọc tin nhắn nhóm: 15'] 
   ─► [3. Gom nốt cá nhân: 15'] 
   ─► [4. Gom dữ liệu thô: 10'] 
   ─► [5. Viết narrative & rủi ro: 35'] ◄── (BOTTLENECK)
   ─► [6. Định dạng văn bản: 5'] 
   ─► [7. Gửi báo cáo: 5']
```

##### Future State (Tương lai — 20 phút)
```text
[1. Auto-pull dữ liệu cập nhật: 2'] 
   ─► [2. AI cấu trúc & phân tích: 1'] 
   ─► [3. AI sinh bản nháp narrative: 2'] 
   ─► [4. Leader Review & Chỉnh sửa: 13'] ◄── (HUMAN BOUNDARY / REVIEW)
   ─► [5. Leader duyệt & Gửi: 2']

* Fallback Strategy: Nếu AI draft không đạt yêu cầu → Leader dùng lại template báo cáo truyền thống và tự tổng hợp thủ công.
```

---

### Problem Card #2 (RANK 2) — Đọc & Tóm tắt Tài liệu / Báo cáo Dài 

```text
┌─────────────────────────────────────────────────────────────────────────┐
│ PROBLEM CARD #2                                                         │
│                                                                         │
│ Problem 1 câu: Người học/Nhân viên tốn 45-60 phút để đọc lướt và trích  │
│ xuất ý chính từ tài liệu đề cương / báo cáo dài (20-30 trang) trước     │
│ buổi họp hoặc kỳ thi.                                                   │
│                                                                         │
│ Ai chịu ảnh hưởng? Sinh viên, Nhân viên văn phòng                       │
│                                                                         │
│ Workflow hiện tại:                                                      │
│ 1. Mở file tài liệu PDF/Word → 2. Đọc lướt từng chương                  │
│ → 3. Ghi chép nốt các ý chính → 4. Lập danh sách câu hỏi / Checklist    │
│                                                                         │
│ Bước nghẽn nhất: Đọc lướt và trích xuất ý chính (30 phút)              │
│                                                                         │
│ Đo thành công bằng gì? Giảm thời gian đọc trích xuất từ 60' xuống 15'   │
│                                                                         │
│ Quick gut: [ ] Workflow  [ ] Rule  [x] AI Assistant / Workflow  [ ] Agent│
└─────────────────────────────────────────────────────────────────────────┘
```

#### Chi tiết Problem Card #2:
* **Problem 1 câu:** Người học/Nhân viên văn phòng mất 45-60 phút đọc một tài liệu dài 20-30 trang để nắm ý chính và danh sách việc cần làm trước buổi họp hoặc kỳ thi, dẫn đến việc tốn quá nhiều thời gian đọc lướt thụ động.
* **Actor:** Sinh viên / Nhân viên văn phòng.
* **Thời điểm / bối cảnh:** Trước các buổi họp giao ban, họp thảo luận chuyên môn hoặc các đợt ôn tập môn học.
* **Current workflow:**
  1. Mở file tài liệu (PDF / Word) dài 20-30 trang (2 phút).
  2. Đọc lướt từng phần, từng chương để tìm kiếm từ khóa quan trọng (30 phút - **Bottleneck**).
  3. Ghi chép thủ công các tóm tắt và định nghĩa chính ra sổ nốt (15 phút).
  4. Lập danh sách các câu hỏi cần làm rõ hoặc việc cần thực hiện (10 phút).
* **Bottleneck:** Bước 2 — Đọc lướt văn bản dài để lọc ra ý chính giữa rất nhiều thông tin diễn giải phụ.
* **Impact:** Mất 45-60 phút cho mỗi tài liệu. Nếu có nhiều tài liệu trước buổi họp, người đọc bị quá tải nhận thức và dễ bỏ sót thông tin cốt lõi.
* **Success metric:** 
  * Giảm thời gian đọc và nắm bắt ý chính từ **60 phút xuống 15 phút/tài liệu**.
  * 100% các ý chính (Key takeaways) và danh sách việc cần làm (Action Items) được trích xuất đầy đủ.
* **Non-AI alternative:** Đọc phần Kết luận (Conclusion) hoặc Tóm tắt (Executive Summary) ở đầu/cuối tài liệu. *Hạn chế:* Nhiều tài liệu không có sẵn bản tóm tắt hoặc viết quá chung chung.
* **AI hypothesis:** Dùng AI hỗ trợ đọc hiểu văn bản dài, tự động phân tích cấu trúc tài liệu và xuất bản tóm tắt phân loại theo các đề mục cốt lõi + danh sách Action Items.
* **Quick gut:** **AI Assistant / Workflow** (AI tóm tắt cấu trúc & trích xuất ý chính, người đọc rà soát và kiểm chứng lại).

#### Draft Workflow trước & sau cho Problem #2:

##### Current State (Hiện tại — 57 phút)
```text
[1. Mở file tài liệu: 2'] ──► [2. Đọc lướt từng chương: 30'] ◄── (BOTTLENECK)
   ──► [3. Ghi chép tóm tắt: 15'] ──► [4. Lập danh sách việc: 10']
```

##### Future State (Tương lai — 15 phút)
```text
[1. Tải tài liệu lên công cụ AI: 1'] 
   ──► [2. AI phân tích & Sinh Executive Summary + Key Points: 2'] 
   ──► [3. Người đọc xem AI Summary để nắm khung tổng thể: 5'] 
   ──► [4. Người đọc soi kỹ các đoạn trọng yếu trong file gốc: 7'] ◄── (HUMAN REVIEW)
```

---

### Problem Card #3 (RANK 3) — Nghe lại & Tóm tắt Meeting Recap 

```text
┌─────────────────────────────────────────────────────────────────────────┐
│ PROBLEM CARD #3                                                         │
│                                                                         │
│ Problem 1 câu: Thư ký/Leader tốn 40-50 phút nghe lại ghi âm cuộc họp để │
│ tổng hợp Meeting Recap và danh sách công việc được phân công.            │
│                                                                         │
│ Ai chịu ảnh hưởng? Thư ký cuộc họp, Team Leader, Thành viên dự họp      │
│                                                                         │
│ Workflow hiện tại:                                                      │
│ 1. Mở file ghi âm cuộc họp → 2. Nghe lại và tua các đoạn chính          │
│ → 3. Ghi chép ý chính → 4. Trích xuất danh sách việc & deadline        │
│ → 5. Gửi Recap cho nhóm                                                 │
│                                                                         │
│ Bước nghẽn nhất: Nghe lại và lọc ra danh sách phân công (25 phút)       │
│                                                                         │
│ Đo thành công bằng gì? Giảm thời gian làm Recap từ 45' xuống 12'/buổi    │
│                                                                         │
│ Quick gut: [ ] Workflow  [ ] Rule  [x] AI Assistant / Workflow  [ ] Agent│
└─────────────────────────────────────────────────────────────────────────┘
```

#### Chi tiết Problem Card #3:
* **Problem 1 câu:** Người ghi chép/Thư ký cuộc họp mất 40-50 phút nghe lại ghi âm cuộc họp 1-2 tiếng để tóm tắt các quyết định chính và lập danh sách phân công công việc (Action Items), dẫn đến việc gửi thông báo sau họp bị trễ.
* **Actor:** Thư ký cuộc họp / Team Leader.
* **Thời điểm / bối cảnh:** Sau mỗi buổi họp nhóm hoặc thảo luận kế hoạch công việc.
* **Current workflow:**
  1. Mở file ghi âm hoặc mở lại các bản nốt thô sau cuộc họp (5 phút).
  2. Nghe lại các đoạn thảo luận quan trọng và tua qua đoạn phụ (20 phút - **Bottleneck**).
  3. Lọc ra các quyết định đã được thống nhất trong buổi họp (10 phút).
  4. Lập danh sách công việc cần làm: Ai làm việc gì, deadline khi nào (10 phút).
  5. Format nội dung và gửi tin nhắn Recap vào kênh chat nhóm (5 phút).
* **Bottleneck:** Bước 2 & 3 — Nghe lại ghi âm và lọc ra thông tin chính xác giữa nhiều ý kiến thảo luận lộn xộn.
* **Impact:** Mất 40-50 phút/cuộc họp. Nếu không gửi Recap kịp thời, các thành viên dễ quên việc hoặc hiểu sai deadline được giao.
* **Success metric:** 
  * Giảm thời gian tổng hợp Recap từ **45 phút xuống còn 10-12 phút/buổi họp**.
  * 100% cuộc họp có Meeting Recap kèm danh sách Action Items rõ ràng gửi trong vòng 30 phút sau khi họp xong.
* **Non-AI alternative:** Yêu cầu một người vừa họp vừa gõ nốt trực tiếp. *Hạn chế:* Người gõ nốt dễ bị phân tâm, không tham gia thảo luận sâu được và nốt hay bị thiếu ý.
* **AI hypothesis:** Dùng AI chuyển đổi file ghi âm thành văn bản (Speech-to-Text) và tự động tóm tắt thành các mục chính: Quyết định đạt được, Danh sách công việc phân công (Action Items kèm người phụ trách).
* **Quick gut:** **Workflow / AI Assistant** (AI chuyển văn bản & tóm tắt, người thật rà soát lại trước khi gửi).

#### Draft Workflow trước & sau cho Problem #3:

##### Current State (Hiện tại — 50 phút)
```text
[1. Mở file ghi âm: 5'] ──► [2. Nghe lại & tua: 20'] ◄── (BOTTLENECK)
   ──► [3. Lọc quyết định: 10'] ──► [4. Lập danh sách việc: 10'] ──► [5. Gửi Recap: 5']
```

##### Future State (Tương lai — 12 phút)
```text
[1. Tải file ghi âm lên công cụ AI: 2'] 
   ──► [2. AI chuyển văn bản & Sinh Recap + Action Items: 2'] 
   ──► [3. Thư ký đọc rà soát & bổ sung chi tiết: 6'] ◄── (HUMAN REVIEW)
   ──► [4. Duyệt & Gửi tin nhắn Recap: 2']
```

---

## Phase 2.4 — Lựa chọn Card Muốn Pitch Nhất Với Nhóm

### Card tôi chọn để pitch: **Tổng hợp Báo cáo Tiến độ Tuần của Nhóm**

#### Lý do chọn:
1. **Tính thực tế & Phổ biến:** Đây là vấn đề quen thuộc diễn ra hàng tuần ở hầu hết các nhóm làm việc/đồ án. Vấn đề có actor rõ ràng, workflow dễ hình dung và đo lường được bằng thời gian cụ thể (90 phút → 20 phút).
2. **Cân bằng giữa Automation & AI:** Bài toán này thể hiện rõ ranh giới giữa việc dùng script/rule để thu thập dữ liệu và dùng AI để xử lý ngôn ngữ tự nhiên (viết bản nháp narrative).
3. **Phù hợp với thời lượng môn học:** Dễ xây dựng kịch bản thử nghiệm và thảo luận so sánh các phương án (No AI vs Rule vs Workflow vs Agent) ngay trong buổi lab.

#### Các câu hỏi tôi muốn nhóm challenge:
1. *Bản nháp narrative do AI viết có thực sự phản ánh được các rủi ro phi kỹ thuật (như thành viên bị ốm, thiếu nhân lực) hay không, hay vẫn cần con người tự bổ sung?*
2. *Nếu thông tin cập nhật từ các thành viên bị thiếu hoặc gửi muộn, workflow này sẽ xử lý thế nào để không tạo ra báo cáo sai sự thật?*
3. *Có nhất thiết phải dùng AI Workflow không, hay chỉ cần đặt một Rule nhắc nhở mọi người tự điền form vào mỗi tối Chủ Nhật?*
