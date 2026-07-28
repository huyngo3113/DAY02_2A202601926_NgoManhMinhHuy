# 01 — Individual Problem Scan



| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian | Người cao tuổi hoảng sợ, bối rối khi nhận các cuộc gọi đe dọa (giả danh công an, viện kiểm sát, thông báo vi phạm) không biết cách xác minh tính đúng sai | Người cao tuổi, Con cái/Người thân | Mất 15–30 phút hoảng loạn; dễ bị thao túng chuyển tiền tiết kiệm hoặc làm theo yêu cầu của kẻ xấu |
| 2 | Pain từ người khác | Trẻ em học sinh bị dụ dỗ cung cấp thông tin cá nhân hoặc bấm vào đường link lạ do không nhận biết được rủi ro lừa đảo | Trẻ em, Phụ huynh | Phụ huynh khó theo dõi sát sao 24/7; chỉ phát hiện khi tài khoản game/mạng xã hội bị chiếm đoạt hoặc bị đe dọa |
| 3 | Tốn thời gian | Nhân viên hỗ trợ khách hàng phải tra cứu lại thông tin từ 3–4 hệ thống khác nhau để xử lý một yêu cầu phức tạp | Nhân viên CSKH, Khách hàng | Mất 8–10 phút/yêu cầu; kéo dài thời gian phản hồi và làm giảm chỉ số hài lòng của khách hàng |
| 4 | Lặp lại | Nhân viên kinh doanh phải nhập tay thông tin cuộc gọi, ghi chú họp và cập nhật trạng thái vào hệ thống quản lý sau mỗi cuộc gặp | Nhân viên Sale, Quản lý Sale | Mất 1–2 tiếng/ngày; thông tin cập nhật chậm 2–3 ngày hoặc dễ bị bỏ sót dữ liệu |
| 5 | Pain từ người khác | Kiểm thử viên phát hiện lỗi nhưng mô tả các bước thực hiện lại mập mờ, thiếu thông tin chi tiết và hình ảnh | Lập trình viên, Kiểm thử viên | Lập trình viên phải nhắn tin hỏi lại 2–3 lần; thời gian xử lý lỗi bị kéo dài gấp đôi |
| 6 | AI có thể tốt hơn | Bộ phận kế toán phải đối soát thủ công từng hóa đơn đầu vào dạng hình ảnh/PDF với đơn đặt hàng trên hệ thống | Kế toán viên, Kế toán trưởng | Mất 3–5 ngày cuối tháng để nhập liệu và so sánh; dễ sai sót do nhầm lẫn số liệu |
| 7 | Tốn thời gian | Chuyên viên pháp lý phải đọc từng điều khoản trong hợp đồng dài hàng chục trang để tìm các điều khoản rủi ro bất thường | Chuyên viên Pháp lý, Phòng Kinh doanh | Mất 4–6 tiếng/hợp đồng; làm chậm tiến độ ký kết hợp đồng hợp tác với đối tác |
| 8 | Lặp lại | Nhân viên phân tích dữ liệu phải chạy lại các câu lệnh và xuất file báo cáo định kỳ mỗi đầu tuần cho các phòng ban | Nhân viên phân tích, Quản lý | Mất 3–4 tiếng mỗi đầu tuần; công việc lặp đi lặp lại mang tính thao tác cơ học |
| 9 | AI có thể tốt hơn | Công cụ tìm kiếm tài liệu nội bộ không hiểu ngữ cảnh câu hỏi, chỉ tìm kiếm chính xác theo từ khóa | Nhân viên mới, Trưởng nhóm | Mất 15–20 phút/lần tìm kiếm; nhân viên thường phải nhắn tin hỏi trực tiếp đồng nghiệp |
| 10 | Tốn thời gian | Quản lý sản phẩm mất nhiều ngày tổng hợp và phân tích định tính hàng trăm phản hồi của người dùng từ nhiều kênh | Quản lý sản phẩm, Trưởng nhóm | Mất 1–2 ngày/đợt tổng hợp; khó phát hiện sớm các vấn đề nhức nhối nổi bật của người dùng |

Vì sao phần scan này mạnh:
- Scan rộng qua nhiều lăng kính và bối cảnh khác nhau (từ an toàn xã hội đến vận hành doanh nghiệp).
- Rõ ràng về đối tượng chịu ảnh hưởng và có dấu hiệu đo lường thực tế.
- Không bắt đầu bằng việc ấn định giải pháp công nghệ cụ thể.

---

## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Xác minh thông tin lừa đảo cho Người già & Trẻ em | Nỗi đau thực tế rất lớn, ảnh hưởng trực tiếp đến tài sản/tâm lý của nhóm đối tượng yếu thế | Khả năng cảnh báo kịp thời ngay trong lúc cuộc gọi/tin nhắn xảy ra |
| 2 | Tổng hợp Báo cáo tuần (Weekly Report) | Quy trình rõ ràng, diễn ra định kỳ, tốn nhiều thời gian của cấp quản lý | Đánh giá định tính chất lượng nhận xét "đủ tốt" |
| 3 | Khai thác dữ liệu phản hồi người dùng (User Feedback) | Ảnh hưởng trực tiếp đến quyết định cải tiến sản phẩm, thông tin rải rác | Dữ liệu đầu vào không đồng nhất từ nhiều nguồn khác nhau |

---

## Problem Card #1 — Xác minh thông tin lừa đảo cho Người cao tuổi & Trẻ em

**Problem 1 câu:**  
Người cao tuổi và trẻ em thường bối rối, hoảng loạn khi nhận các cuộc gọi/tin nhắn đe dọa lừa đảo do không thể tự xác minh tính đúng sai, trong khi người thân không thể túc trực 24/7 để hỗ trợ kịp thời.

**Actor:**  
* Actor chính: Người cao tuổi, Trẻ em (người dùng trực tiếp).
* Actor phụ: Con cái, Phụ huynh (người giám hộ/người xác minh).

**Thời điểm / bối cảnh:**  
Khi nhận được cuộc gọi, tin nhắn hoặc thông báo có dấu hiệu đe dọa, giục giã chuyển tiền hay yêu cầu cung cấp thông tin cá nhân khẩn cấp.

**Current workflow:**
1. Nạn nhân nhận cuộc gọi/tin nhắn đe dọa (giả danh công an, viện kiểm sát, nhà trường)
2. Nạn nhân hoảng sợ, không biết thông tin đúng hay sai
3. Cố gắng liên hệ cho người thân (con cái/bố mẹ) để hỏi
4. Người thân bận việc, không nghe máy hoặc không bắt máy kịp thời
5. Nạn nhân bị thao túng tâm lý, tự thực hiện theo hướng dẫn của kẻ gian (chuyển tiền/cung cấp mã OTP)
6. Sự việc xong xuôi mới phát hiện bị lừa đảo

**Bottleneck:**  
Bước 3 & 4 — Thời gian đứt gãy kết nối giữa nạn nhân và người thân trong khoảng 15 phút "vàng", khiến nạn nhân phải tự đưa ra quyết định trong trạng thái hoảng loạn.

**Impact:**  
Gây thiệt hại lớn về tài sản tích lũy (với người già) hoặc lộ gạt thông tin/tâm lý lo sợ kéo dài (với trẻ em). Tạo áp lực và cảm giác bất an thường trực cho người thân.

**Success metric:**  
* Phát tín hiệu cảnh báo đến người thân trong < 30 giây khi phát hiện dấu hiệu nghi vấn.
* Giảm tỷ lệ người dùng tự thực hiện giao dịch chuyển tiền/cung cấp thông tin lạ khi chưa có sự xác nhận xuống < 5%.

**Non-AI alternative:**  
* Dùng danh sách chặn số rác (Blacklist): Không ngăn chặn được các số điện thoại mới hoặc các kịch bản lừa đảo tinh vi biến đổi liên tục.
* Thỏa thuận quy tắc gia đình: Người già/trẻ em dễ quên hoặc bị kẻ xấu thao túng tâm lý làm cho hoảng loạn mà quên mất quy tắc.

**AI hypothesis:**  
AI đóng vai trò phân tích ngữ cảnh tin nhắn/cuộc gọi để nhận diện các kịch bản đe dọa lừa đảo phổ biến, tự động phát cảnh báo giọng nói địa phương dễ hiểu cho người dùng, đồng thời gửi thông báo khẩn cấp đến ứng dụng của người thân để hỗ trợ xác minh.

**Quick gut:**  
Workflow + Human-in-the-loop (Quy trình có con người xác nhận).

### Draft current workflow

```text

CURRENT STATE — Mất 15–30 phút (Rủi ro thiệt hại cao)

[1 Nhận cuộc gọi/tin nhắn đe dọa]
→ [2 Bối rối, hoảng sợ]
→ [3 Gọi cho người thân: Không bắt máy]  <-- điểm nghẽn đứt gãy
→ [4 Bị thao túng tâm lý & Làm theo hướng dẫn xấu]
→ [5 Phát hiện bị lừa thì đã muộn]
Draft future workflow
Plaintext
FUTURE STATE — Xử lý trong 1–2 phút (An toàn)

[1 Nhận cuộc gọi/tin nhắn có dấu hiệu bất thường]
→ [2 AI nhận diện kịch bản rủi ro & Phát cảnh báo bằng giọng nói]
→ [3 AI gửi thông báo ưu tiên cao đến ứng dụng của người thân]
→ [4 Người thân kiểm tra & Xác minh trực tiếp: Đúng/Sai]  <-- con người chốt quyết định
→ [5 Hệ thống hỗ trợ chặn/xử lý an toàn]

Trường hợp người thân chưa phản hồi: AI giữ nguyên trạng thái cảnh báo và hướng dẫn người dùng tạm thời không thao tác bất kỳ giao dịch nào.
Problem Card #2 — Tổng hợp Báo cáo tuần (Weekly Report)
Problem 1 câu:

Quản lý dự án và Trưởng nhóm mất nhiều giờ mỗi cuối tuần để thu thập, phân loại và tổng hợp báo cáo rải rác từ các thành viên, dẫn đến trễ tiến độ báo cáo cấp trên và thiếu thời gian phân tích chuyên sâu các rủi ro thực sự của dự án.

Actor:

Actor chính: Quản lý dự án (Project Manager), Trưởng nhóm (Team Lead).

Actor phụ: Thành viên trong team (người gửi báo cáo), Cấp quản lý cao hơn / Ban giám đốc (người đọc báo cáo).

Thời điểm / bối cảnh:

Thực hiện định kỳ vào thứ Sáu hàng tuần hoặc đầu tuần mới, khi cần tổng hợp tình hình hoạt động của toàn team để báo cáo cho cấp quản lý/khách hàng.

Current workflow:

Quản lý gửi nhắc nhở các thành viên nộp báo cáo tuần cá nhân (qua Slack/Zalo/Email).

Thành viên viết báo cáo không đồng nhất (người ngắn, người dài, người trễ hạn).

Quản lý đọc từng báo cáo cá nhân, nhặt lọc thông tin và chép tay vào một file tổng hợp chung.

Quản lý tự tính toán/đánh giá tiến độ, phát hiện các điểm nghẽn và dự báo rủi ro dựa trên cảm tính.

Quản lý viết phần nhận xét/tóm tắt tổng quan dành cho Ban giám đốc.

Gửi báo cáo hoàn chỉnh cho cấp trên (thường bị trễ deadline hoặc thiếu thông tin sâu).

Bottleneck:

Bước 3 & 5 — Quản lý tốn quá nhiều thời gian làm công việc cơ học (gom nhặt dữ liệu) và bị quá tải thông tin, dẫn đến việc viết phần nhận xét đánh giá tổng quan (Executive Summary) bị hời hợt hoặc trì hoãn.

Impact:

Mất 2–4 tiếng/tuần của cấp quản lý cao cấp chỉ cho công tác thao tác dữ liệu.

Rủi ro bỏ sót các cảnh báo nguy cơ trễ tiến độ (blockers) ẩn giấu trong báo cáo của nhân viên.

Báo cáo chậm trễ làm giảm độ linh hoạt trong việc đưa ra quyết định điều chỉnh của Ban giám đốc.

Success metric:

Giảm thời gian tổng hợp báo cáo tuần từ 3 tiếng xuống < 20 phút.

100% các rủi ro/điểm nghẽn nghiêm trọng (blockers) được tự động trích xuất và gắn cờ cảnh báo (flag).

Non-AI alternative:

Dùng biểu mẫu cố định (Form/Template): Nhân viên vẫn điền thiếu/đầy đủ tùy nghi, quản lý vẫn phải đọc thủ công từng biểu mẫu.

Quy định thưởng phạt deadline: Giải quyết được việc nộp đúng giờ nhưng không giải quyết được khâu đọc - tổng hợp - trích xuất thông tin.

AI hypothesis:

AI đóng vai trò tự động thu thập và đọc hiểu các báo cáo cá nhân (hoặc cập nhật công việc trên Jira/Trello/Chat), tự động nhóm các công việc theo từng mảng, trích xuất danh sách điểm nghẽn (blockers) và dự thảo sẵn phần Tóm tắt điều hành (Executive Summary) để Quản lý kiểm tra và duyệt.

Quick gut:

Workflow + Human-in-the-loop (AI tự động trích xuất & phác thảo → Quản lý duyệt & chỉnh sửa nội dung cuối cùng).

Draft current workflow
Plaintext
CURRENT STATE — Mất 3–4 tiếng (Dễ sót thông tin, trễ hạn)

[1 Nhắc nhở thành viên] 
→ [2 Thu thập báo cáo rải rác] 
→ [3 Đọc & Nhặt thông tin thủ công] <-- điểm nghẽn thao tác cơ học
→ [4 Tự tổng hợp & Đánh giá rủi ro] 
→ [5 Viết nhận xét tổng quan] <-- điểm nghẽn tốn não & thời gian
→ [6 Gửi báo cáo muộn]
Draft future workflow
Plaintext
FUTURE STATE — Xử lý trong 15–20 phút (Đồng bộ, chính xác)

[1 Thành viên nộp báo cáo hoặc cập nhật công việc trên hệ thống]
→ [2 AI thu thập, phân loại & Trích xuất điểm nghẽn (Blockers)]
→ [3 AI tự động tạo bản phác thảo Weekly Report + Executive Summary]
→ [4 Quản lý review, chỉnh sửa và chốt đánh giá] <-- con người duyệt
→ [5 Tự động xuất file & Gửi Ban giám đốc đúng hạn]
Problem Card #3 — Khai thác dữ liệu phản hồi người dùng (User Feedback)
Problem 1 câu:

Quản lý sản phẩm (PM) và đội ngũ phát triển bị ngợp trước hàng nghìn phản hồi rải rác từ nhiều kênh (Store reviews, Ticket hỗ trợ, Social, Survey), không thể tổng hợp thủ công để tìm ra đâu là vấn đề thực sự cần ưu tiên xử lý trong đợt nâng cấp tiếp theo.

Actor:

Actor chính: Quản lý sản phẩm (Product Manager), Chuyên viên trải nghiệm khách hàng (CX Specialist).

Actor phụ: Đội ngũ CSKH (nhận feedback), Đội ngũ kỹ thuật/Design (nhận yêu cầu cải tiến).

Thời điểm / bối cảnh:

Khi chuẩn bị lập kế hoạch tính năng cho đợt phát triển (Sprint Planning/Roadmap) hoặc sau khi vừa ra mắt một tính năng mới và cần đo lường phản ứng người dùng.

Current workflow:

Feedback đổ về rải rác trên App Store, Google Play, Email hỗ trợ, Fanpage, Trực tiếp trong App.

PM hoặc CSKH xuất dữ liệu ra các file Excel/Google Sheet riêng biệt.

Phân công người đọc từng dòng feedback, tự gán nhãn thủ công (ví dụ: "Lỗi thanh toán", "Giao diện xấu", "Tính năng thiếu").

Đếm số lượng theo cảm tính hoặc tạo bảng pivot cơ bản để báo cáo.

PM họp với team để chọn tính năng sửa dựa trên cảm tính hoặc ý kiến của người nói to nhất.

Bottleneck:

Bước 3 & 4 — Việc đọc và gán nhãn thủ công hàng ngàn dòng feedback mất nhiều ngày, dẫn đến dữ liệu bị phân tích chậm trễ, nhãn phân loại không đồng nhất giữa các nhân sự và dễ bỏ sót các xu hướng lỗi mới phát sinh.

Impact:

Mất 1–2 tuần mỗi đợt tổng hợp, làm chậm nhịp độ cải tiến sản phẩm.

Phát triển sai tính năng ưu tiên do phân tích cảm tính, gây lãng phí nguồn lực lập trình.

Người dùng bỏ đi (churn) vì các lỗi ức chế lặp đi lặp lại không được phát hiện và xử lý kịp thời.

Success metric:

Giảm thời gian tổng hợp và phân loại phản hồi từ 2 tuần xuống < 2 tiếng.

Nhận diện chính xác Top 5 nỗi đau lớn nhất của người dùng dựa trên dữ liệu định tính có bằng chứng thực tế đi kèm.

Non-AI alternative:

Tìm kiếm theo từ khóa (Keyword search): Rất dễ bỏ sót do người dùng dùng từ đồng nghĩa, viết tắt hoặc gõ sai chính tả (ví dụ: "lag", "giật", "chậm", "xoay xoay").

Mẫu khảo sát đóng (Multiple choice survey): Giới hạn góc nhìn của người dùng, không bắt được các sự cố ngoài kịch bản dự kiến.

AI hypothesis:

AI đóng vai trò gom nhóm ngữ cảnh (Clustering) và phân tích cảm xúc (Sentiment Analysis), tự động đọc hiểu toàn bộ feedback thô từ mọi nguồn, gán nhãn chủ đề chính xác và trích xuất ra các bài toán nổi bật kèm mức độ ảnh hưởng (severity) để PM ra quyết định.

Quick gut:

Workflow + Analytical Insight (AI phân tích & phân loại dữ liệu lớn → Cung cấp bảng điều khiển Insight cho con người định hướng).

Draft current workflow
Plaintext
CURRENT STATE — Mất 1–2 tuần (Dễ lệch hướng, tốn sức)

[1 Feedback đổ về rải rác nhiều nguồn]
→ [2 Gom file Excel thủ công]
→ [3 Đọc & Gán nhãn từng dòng feedback] <-- điểm nghẽn quá tải dữ liệu
→ [4 Đếm số lượng & Tổng hợp báo cáo] <-- điểm nghẽn thiếu góc nhìn sâu
→ [5 Ra quyết định làm sản phẩm dựa trên cảm tính]
Draft future workflow
Plaintext
FUTURE STATE — Xử lý trong 1–2 tiếng (Dựa trên dữ liệu chuẩn xác)

[1 Kết nối dữ liệu tự động từ các kênh Feedback về hệ thống]
→ [2 AI phân tích cảm xúc, gom nhóm chủ đề & Phát hiện xu hướng lỗi mới]
→ [3 AI xuất Dashboard Top Vấn Đề + Đề xuất mức độ ưu tiên]
→ [4 PM review góc nhìn, đào sâu vào bằng chứng & Chọn Roadmap] <-- con người chốt quyết định
→ [5 Chuyển bài toán sang cho team Kỹ thuật xử lý]
