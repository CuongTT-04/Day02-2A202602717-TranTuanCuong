# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Trần Tuấn Cường
- Mã học viên: 2A202602717
- Nhóm: Người cao tuổi
- Candidate problem nhóm chọn: Khó khăn khi thực hiện thủ tục hành chính công trực tuyến của người lớn tuổi

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 5 problems có số liệu thật và gần gũi với đời sống của mình. | Đóng góp 5 bài toán thực tế vào kho ý tưởng ban đầu của nhóm. |
| Pitch Problem Card | Pitch chi tiết Problem Card #3 (Tối ưu hóa CV theo JD cho sinh viên). | Đưa bài toán CV vào danh sách thảo luận để nhóm cùng mổ xẻ, phản biện. |
| Challenge bài của bạn khác | Đặt câu hỏi chất vấn về tính khả thi và rủi ro: "Nếu người già bấm nhầm hoặc AI nhận diện sai các thông tin thì ai chịu trách nhiệm?". | Giúp nhóm nhận diện sớm rủi ro pháp lý và bảo mật. |
| Gom trùng / cluster | Cùng nhóm phân loại các candidate thành các cụm đề tài. | Giúp nhóm thu gọn các ý tưởng rời rạc thành các hướng giải quyết rõ ràng. |
| Chọn candidate problem | Phân tích và biểu quyết chọn đề tài người già làm thủ tục công vì nỗi đau xã hội lớn hơn bài toán cá nhân. | Nhóm đạt đồng thuận 100% chọn 1 bài toán duy nhất có impact cao. |
| Validation / research | Tìm hiểu khả năng ứng dụng Voice AI tiếng Việt theo vùng miền. | Gợi ý cách áp dụng các voice AI như giọng Bắc, Trung, Nam phụ thuộc vào khu vực mà người dùng xác nhận. |
| Workflow nhóm | Góp ý xây dựng Current State (chỉ ra bottleneck đọc thuật ngữ và chụp ảnh) và Future State có chốt chặn con người. | Đảm bảo workflow của nhóm có Human Boundary rõ ràng và có nhánh Fallback an toàn. |
| Problem Statement | Phản biện các trường thông tin trong Problem Statement, đặc biệt là chuẩn hóa 3 metric định lượng và ranh giới Boundary. | Giúp nhóm có bản Problem Statement chặt chẽ, không bị mơ hồ về mục tiêu đo lường. |
| Rule / Workflow / Agent | Trực tiếp phân tích ma trận độ phù hợp, trả lời 5 câu hỏi chốt và lập luận kiên quyết chọn **Workflow**, bác bỏ **Agent**. | Định hình kiến trúc giải pháp an toàn, tránh bẫy "làm Agent vì trends" vi phạm bảo mật dữ liệu công dân. |
| Decision | Xây dựng kế hoạch thử nghiệm pilot nhỏ nhất (15-20 người cao tuổi làm thủ tục BHYT) và thiết lập 3 mốc dừng (Rollback/Exit). | Chốt quyết định **Go** có căn cứ kỹ thuật và phương án thoái lui an toàn nếu AI thất bại. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu ấn rõ nhất của tôi nằm ở toàn bộ nội dung phân tích Phase 6 (Rule / Workflow / Agent + Decision) trong file group-report.md. Tôi là người trực tiếp xây dựng ma trận đánh giá, lập luận kiên quyết giữ mô hình Workflow có Human-in-the-loop và thiết lập các tiêu chí định lượng cho đợt thử nghiệm pilot cũng như cơ chế dừng (Rollback) an toàn.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| **Scan** | Gợi ý các góc nhìn vấn đề gần gũi với sinh viên năm cuối (nghiên cứu, tìm việc, đời sống). | Giúp cấu trúc lại vấn đề đọc tài liệu học tập quá dài và khó khăn khi khớp CV với JD. | Gợi ý vài ý tưởng quá vĩ mô và chung chung (như "AI giải quyết nạn thất nghiệp toàn cầu"). | Loại bỏ các ý chung chung, chọn 5 bài toán cụ thể có số liệu đo lường thực tế (vouchers, tin giả, CV). |
| **Problem Card** | Phản biện điểm yếu của Top 3 Problem Cards và định dạng khung thẻ (Box card). | Gợi ý các mốc thời gian baseline thực tế (thời gian sửa CV 135 phút, kiểm tra tin giả 25 phút) và công thức STAR. | AI có xu hướng phóng đại khả năng tự động hóa, cho rằng AI có thể tự viết 100% CV mà không cần người kiểm tra. | Bổ sung Human Boundary nghiêm ngặt: AI chỉ gợi ý khung và bóc tách từ khóa, ứng viên phải tự đối soát nội dung thật. |
| **Workflow** | Chuyển đổi mô tả các bước Current/Future workflow thành sơ đồ cú pháp Mermaid. | Tạo cú pháp Mermaid nhanh chóng, chuẩn xác và phân chia màu sắc cho Bottleneck, Human Boundary, Fallback. | Ban đầu vẽ theo chiều ngang (`direction LR`) khiến sơ đồ bị ép dẹp và khó đọc trên màn hình; gộp bước đọc đối soát và nộp hồ sơ. | Yêu cầu vẽ lại theo chiều dọc (`direction TB`), tách riêng bước đối soát bằng giọng đọc TTS to rõ trước khi ấn nộp. |
| **Research** | Tìm kiếm các giải pháp/công nghệ trợ lý dịch vụ công và hỗ trợ người cao tuổi hiện có. | Tổng hợp nhanh các công nghệ nhận diện giọng nói tiếng Việt và các mô hình chatbot hành chính công. | Đưa ra một số số liệu thống kê về tỷ lệ thành công của dịch vụ công không có nguồn kiểm chứng chính thức (dễ bị hallucination). | Lọc bỏ số liệu không xác thực, chỉ giữ lại các case study thực tế và bài học về việc giao diện phải tối giản cho người già. |
| **Problem Statement** | Phản biện bảng Problem Statement v0/v1 để tìm các điểm còn mơ hồ về Metric và Boundary. | Chỉ ra điểm nghẽn lớn nhất của người già không phải là thiếu mạng mà là rào cản thao tác bàn phím và thuật ngữ pháp lý. | AI đề xuất các metric định tính mơ hồ, khó đo lường (như "giúp người già vui vẻ và tự tin hơn"). | Chuẩn hóa thành 3 metric định lượng rõ ràng: rút ngắn thời gian từ 60' xuống < 15', tỷ lệ hồ sơ hợp lệ tăng lên >= 85%, tỷ lệ tự làm >= 60%. |
| **Rule / Workflow / Agent** | Thảo luận và phản biện ma trận so sánh giữa 3 cấp độ Rule, Workflow và Agent. | Cung cấp khung 5 câu hỏi chốt giúp phân định rạch ròi giữa Workflow xác định và Agent tự động. | AI ban đầu thiên vị đề xuất làm "Autonomous Agent thông minh đa năng" để tạo ấn tượng công nghệ. | Kiên quyết bác bỏ Agent vì rủi ro vi phạm bảo mật dữ liệu công dân (PII, OTP) và trách nhiệm pháp lý; chốt chọn Workflow có Human-in-the-loop. |
| **Decision** | Lên kế hoạch cho kịch bản thử nghiệm pilot nhỏ nhất và các điều kiện dừng (Rollback/Exit). | Gợi ý phương pháp thử nghiệm bán tự động (Wizard of Oz) với nhóm mẫu 15-20 người cao tuổi. | Tiêu chí dừng (rollback) ban đầu AI đưa ra quá chung chung và cảm tính ("khi người dùng cảm thấy không thích"). | Định lượng cụ thể 3 mốc dừng: tỷ lệ OCR sai số CCCD > 10%, thời gian sửa lỗi > 45 phút, hoặc chi phí API > 2.000 VNĐ/lượt. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Sau khi bàn bạc và được đóng góp ý kiến với nhóm, các top 3 problems của các bạn khác đều là những vấn đề đã và đang xảy ra với cuộc sống của các thành viên. Từ đó, họ mong muốn có 1 công cụ phù hợp để giải quyết các vấn đề đó, từ đó có thể giúp giảm bớt áp lực và tăng cường hiệu quả trong công việc và cuộc sống. Dấu ấn đóng góp rõ nhất của tôi trong artifact cuối của nhóm chính là toàn bộ nội dung phân tích ở Phase 6 (Rule/Workflow/Agent và Quyết định Go/No-Go). Tôi là người trực tiếp xây dựng bảng so sánh 3 cấp độ giải pháp, vạch rõ điểm can thiệp của AI (chỉ xử lý giọng nói và tiền kiểm ảnh giấy tờ) cũng như thiết lập các chỉ số định lượng cụ thể cho đợt thử nghiệm pilot nhỏ nhất. Trong quá trình hoàn thiện Problem Statement cho bài toán thủ tục công của người lớn tuổi, tôi thấy điều khó nhất chính là việc xác định ranh giới (Boundary) của giải pháp thay vì chỉ đặt ra các con số Metric. Metric về thời gian hay tỷ lệ hoàn thành tuy khó ước lượng chính xác nhưng vẫn có thể đo lường và hiệu chỉnh dần qua các đợt chạy thử nghiệm pilot. Ngược lại, Boundary đòi hỏi nhóm phải có sự tỉnh táo cao độ để đặt ra lằn ranh đỏ: AI chỉ được phép dừng lại ở mức hỗ trợ nhận diện giọng nói và rà soát ảnh chụp giấy tờ, tuyệt đối không được tự động bấm nộp hồ sơ hay can thiệp vào mã OTP của công dân. Việc kiên quyết giữ người thật ở khâu kiểm soát cuối cùng (Human-in-the-loop) chính là yếu tố sống còn để bảo đảm an toàn dữ liệu và tính pháp lý của toàn bộ quy trình. Nếu có cơ hội làm lại hoặc đào sâu hơn nữa, tôi sẽ đề xuất nhóm phỏng vấn trực tiếp 1-2 người cao tuổi ngay từ Phase 4 thay vì chỉ dựa vào số liệu khảo sát thứ cấp, nhằm kiểm chứng chính xác hơn rào cản ngữ điệu vùng miền trước khi chốt giải pháp.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

