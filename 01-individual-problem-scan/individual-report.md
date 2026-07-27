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

```text
1. Nạn nhân nhận cuộc gọi/tin nhắn đe dọa (giả danh công an, viện kiểm sát, nhà trường)
2. Nạn nhân hoảng sợ, không biết thông tin đúng hay sai
3. Cố gắng liên hệ cho người thân (con cái/bố mẹ) để hỏi
4. Người thân bận việc, không nghe máy hoặc không bắt máy kịp thời
5. Nạn nhân bị thao túng tâm lý, tự thực hiện theo hướng dẫn của kẻ gian (chuyển tiền/cung cấp mã OTP)
6. Sự việc xong xuôi mới phát hiện bị lừa đảo
