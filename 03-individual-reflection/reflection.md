# 03 — Individual Reflection

---

## 1. Tôi đã tham gia vào phần nào trong buổi làm việc nhóm?

| Hoạt động | Tôi đã làm gì? | Kết quả / Ảnh hưởng tới sản phẩm nhóm |
|---|---|---|
| **Scan cá nhân** | Thực hiện quan sát và lập danh sách 9 bài toán thực tế từ đời sống, học tập và làm việc văn phòng. | Đóng góp 3 bài toán candidate vào danh sách chung của nhóm. |
| **Pitch Problem Card** | Trình bày ngắn gọn Problem Card #1 về bài toán "Tổng hợp báo cáo tiến độ tuần của nhóm". | Nêu rõ actor, baseline 90 phút và điểm nghẽn ở bước viết narrative cho nhóm hiểu. |
| **Challenge bài của bạn khác** | Đặt câu hỏi phản biện bài toán "Tóm tắt cuộc họp" và "FAQ Support Bot" của các thành viên khác. | Giúp nhóm nhận ra rủi ro về chất lượng file âm thanh họp và độ phức tạp khi làm Bot. |
| **Gom trùng / Cluster** | Phân loại 12 candidate thành 4 nhóm chủ đề chính (A, B, C, D). | Giúp nhóm nhìn ra pattern chung ở nhóm bài toán "Báo cáo & Tổng hợp". |
| **Chọn candidate problem** | Cùng nhóm chấm điểm theo 7 tiêu chí và thảo luận chọn Candidate 1. | Đạt được 100% sự đồng thuận chọn bài toán báo cáo tiến độ tuần. |
| **Validation / Research** | Thực hiện phỏng vấn nhanh 1 trưởng nhóm và tìm hiểu các công cụ hiện có (Jira Reports, Slack AI). | Rút ra bài học: Dùng Rule cho số liệu thô, dùng AI cho phần narrative. |
| **Workflow nhóm** | Cùng vẽ và tinh chỉnh sơ đồ Before/After Workflow (90' ──► 20'). | Xác định rõ ranh giới kiểm duyệt (Human boundary) ở bước Leader review. |
| **Problem Statement** | Tham gia xây dựng các trường dữ liệu cho Problem Statement v0 và v1. | Đảm bảo metric đo lường và rủi ro được định nghĩa cụ thể, không bị mơ hồ. |
| **Rule / Workflow / Agent** | So sánh 3 phương án và phân tích vị trí bài toán trên ma trận độ phù hợp với AI. | Giúp nhóm chốt phương án **Workflow** thay vì sa vào làm Agent quá phức tạp. |
| **Decision** | Cùng nhóm đánh giá 6 câu hỏi kiểm tra và chốt quyết định GO. | Xây dựng kế hoạch Pilot nhỏ nhất (MVP) cho 2 tuần tiếp theo. |

---

## 2. Bảng đánh giá việc sử dụng AI trong quá trình làm lab

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **Scan cá nhân** | Hỏi gợi ý thêm các góc nhìn bài toán quan sát được. | Gợi ý mở rộng các lăng kính quan sát công việc hàng ngày. | Đưa ra một số ý tưởng chung chung kiểu "Trợ lý AI toàn năng". | Bỏ các ý chung chung, giữ lại các bài toán có trải nghiệm thật và đo lường được. |
| **Problem Card** | Phản biện tính cụ thể của Problem Card ban đầu. | Chỉ ra metric thời gian ban đầu còn thiếu baseline đo lường. | Đôi khi tự động nhảy ngay sang đề xuất giải pháp AI Agent phức tạp. | Hạ mức giải pháp về Workflow đơn giản, tập trung làm rõ điểm nghẽn viết narrative. |
| **Workflow** | Gợi ý cú pháp vẽ sơ đồ luồng dữ liệu ASCII / Mermaid. | Giúp số hóa sơ đồ luồng công việc đẹp mắt và dễ đọc. | Chưa thể hiện rõ bước nào do con người kiểm tra (Boundary). | Bổ sung thêm nút kiểm duyệt (Human Review & Fallback strategy) vào sơ đồ. |
| **Research** | Tìm kiếm các bài viết / tool đã giải quyết bài toán tương tự. | Gợi ý tên các công cụ như Fellow.ai, Slack AI để tham khảo pattern. | Đưa ra một số thông số tính năng không chính xác nếu không có link verify. | Tự truy cập trang web chính thức của tool để kiểm chứng thông tin thực tế. |
| **Problem Statement** | Kiểm tra xem các trường thông tin trong PS v0 đã chặt chẽ chưa. | Đặt câu hỏi phản biện giúp phát hiện ranh giới Boundary chưa rõ. | Viết lại câu chữ bị mang tính quảng cáo ("tối ưu vượt bậc", "thông minh"). | Sửa lại bằng các chỉ số định lượng cụ thể (từ 90 phút xuống dưới 20 phút). |
| **Rule / Workflow / Agent** | Hỏi về điểm khác biệt cốt lõi giữa Workflow và Agent trong bài toán cụ thể. | Giải thích rõ ranh giới khi nào cần Agent tự quyết định hành vi. | Có xu hướng tư vấn nâng cấp lên Agent để "ngầu" hơn. | Giữ nguyên quyết định chọn Workflow để đảm bảo an toàn và tính khả thi trong lab. |
| **Decision** | Gợi ý tiêu chí cho kịch bản thử nghiệm nhỏ nhất (Pilot). | Gợi ý cách đo lường thời gian thực tế ở bước chỉnh sửa bản nháp. | Không đánh giá được bối cảnh nguồn lực thực tế của nhóm. | Tự thiết lập kế hoạch Pilot 2 tuần với nhóm 4 người thực tế. |

---

## 3. Phản tư (Reflection) các câu hỏi mở

### 1. Tôi học được gì khi nghe top 3 problems của các bạn khác trong nhóm?
> Khi nghe bài của các bạn khác, tôi học được rằng mỗi người đều có những điểm nghẽn rất thực tế trong công việc hàng ngày (như việc nghe lại ghi âm cuộc họp hay trả lời câu hỏi FAQ lặp đi lặp lại). Việc lắng nghe giúp tôi mở rộng góc nhìn và hiểu rằng một bài toán AI tốt không nhất thiết phải là bài toán quá lớn, mà là bài toán có workflow và baseline rõ ràng.

### 2. Nhóm có lúc nào bị tình trạng "Solution-first" (Nghĩ giải pháp trước khi hiểu bài toán) không?
> Có. Ở đầu buổi thảo luận, nhóm từng có xu hướng muốn xây dựng một "Agent AI tự động 100% tự nhắn tin giục báo cáo và tự gửi email". Tuy nhiên, sau khi quay lại phân tích kỹ Workflow hiện tại và đặt câu hỏi về Boundary/Rủi ro khi AI gửi sai thông tin, nhóm đã kịp thời "kéo phanh" để lùi về phương án Workflow hỗ trợ sinh bản nháp (Draft narrative), giữ con người làm bước duyệt cuối.

### 3. Tôi có thay đổi ý kiến sau khi bị các bạn khác trong nhóm challenge không?
> Có. Ban đầu tôi nghĩ bài toán báo cáo tuần cần phải bao gồm cả việc tự động vẽ biểu đồ số liệu. Nhưng sau khi được các bạn trong nhóm challenge và kiểm chứng qua phỏng vấn nhanh, tôi nhận ra phần số liệu đã có biểu đồ tự động từ Dashboard, điểm nghẽn thực sự khiến leader mất thời gian nhất là bước **viết đoạn văn narrative tóm tắt tiến độ & rủi ro**. Nhóm đã thu hẹp phạm vi bài toán đúng trọng tâm hơn.

### 4. Tôi đóng góp gì thật sự vào artifact cuối cùng của nhóm?
> Tôi đóng góp trực tiếp vào việc để xuất Candidate 1 (bài toán được chọn), xây dựng sơ đồ Before/After Workflow, và đề xuất ranh giới kiểm duyệt (Human-in-the-loop) để đảm bảo AI không tự động gửi báo cáo khi chưa có sự xác nhận của Leader.

### 5. Điều khó khăn nhất khi viết Problem Statement là gì?
> Điều khó nhất là định nghĩa trường **Success Metric** và **Boundary** sao cho thật cụ thể. Rất dễ rơi vào bẫy viết chung chung như "giúp làm báo cáo nhanh hơn" hoặc "giúp báo cáo tốt hơn". Nhóm phải ép mình đưa ra con số baseline hiện tại (90 phút/tuần) và mục tiêu sau cải thiện (dưới 20 phút/tuần) kèm điều kiện biên AI không được làm gì.

### 6. Nếu được làm lại buổi lab này, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?
> Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở bước Research giải pháp đã có (Phase 4). Tôi muốn nhóm dành thêm thời gian dùng thử thực tế các tính năng tóm tắt báo cáo có sẵn của Jira/Slack để chỉ ra chính xác hơn những điểm mà các công cụ hiện tại chưa giải quyết được, từ đó làm rõ hơn giá trị độc bản của giải pháp nhóm đề xuất.

---

## 4. Bảng tự kiểm cuối bài (Self-Check Checklist)

- [x] **[12đ cá nhân]** Cá nhân có 9+ problems scan và top 3 Problem Cards rõ ràng.
- [x] **[12đ cá nhân]** Đã pitch rõ bài toán của mình và challenge các bài toán của bạn khác đúng trọng tâm.
- [x] **[Điểm nhóm]** Nhóm có nhật ký hội tụ từ 12 candidates về 1 bài toán chuẩn xác.
- [x] **[15đ nhóm]** Nhóm có sơ đồ Workflow trước/sau (Before/After) kèm phân tích tác động cụ thể.
- [x] **[20đ nhóm]** Nhóm có Problem Statement v0/v1 đầy đủ các trường thông tin, metric và boundary rõ ràng.
- [x] **[15đ nhóm]** Nhóm có bảng so sánh chi tiết giữa No AI / Rule / Workflow / Agent.
- [x] **[10đ nhóm]** Nhóm có quyết định GO rõ ràng kèm lý do và kế hoạch Pilot thử nghiệm nhỏ nhất.
- [x] **[10đ cá nhân]** Reflection cá nhân thể hiện trung thực vai trò trong nhóm, cách dùng AI, điều học được và bài học rút ra.
- [x] **[6đ cá nhân]** Tự giải thích được mạch logic: *Problem ──► Workflow ──► Metric ──► Boundary ──► AI Suitability*.

---
*Báo cáo Phản tư Cá nhân (Individual Reflection) — Day 02 Lab*
