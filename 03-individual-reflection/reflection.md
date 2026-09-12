# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đinh Trường An
- Mã học viên: 2A202602393
- Nhóm: Nhóm bạn Nguyễn Đức Minh
- Candidate problem nhóm chọn: Khó nghĩ ra chiến lược marketing để đưa sản phẩm mới ra thị trường — Giải pháp AI Marketing Kit cho Seller nhỏ lẻ trên sàn TMĐT.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Đề xuất 8 bài toán dựa trên các vấn đề thực tiễn (hành chính, y tế, tiêu dùng). | Cung cấp danh sách đầu vào đa dạng để nhóm có dữ liệu đối chiếu trước khi thu hẹp phạm vi. |
| Pitch Problem Card | Trình bày 2 bài toán: "Chờ khám bệnh" và "Tập thể dục". | Hỗ trợ nhóm xác định tiêu chí đánh giá: bài toán cần có điểm nghẽn đo lường được và khả thi về mặt thu thập dữ liệu. |
| Challenge bài của bạn khác | Phản biện tính khả thi của bài "Nhận diện sâu bệnh" do khó khăn trong việc tiếp cận tập dữ liệu người dùng cuối. | Giúp nhóm loại trừ rủi ro thiếu dữ liệu kiểm chứng và quyết định tập trung vào bài AI Marketing Kit. |
| Chọn candidate problem | Đồng ý bình chọn cho bài AI Marketing Kit dựa trên tính khả thi thương mại và khả năng ứng dụng GenAI. | Giúp nhóm nhanh chóng đạt được đồng thuận để chuyển sang giai đoạn phân tích sâu. |
| Validation / research | Thực hiện phỏng vấn 3 người dùng thực tế (chủ shop online quy mô nhỏ) qua Zalo. | Trích xuất được insight cốt lõi: điểm nghẽn nằm ở tư duy định hướng concept, không phải thao tác đăng bài. |
| Workflow nhóm | Phân tích quy trình hiện tại (Current State) và xác định thời gian thắt cổ chai ở bước nghiên cứu concept. | Cung cấp dữ liệu để hoàn thiện sơ đồ quy trình với độ trễ 120-240 phút cho một tác vụ. |
| Problem Statement | Hỗ trợ tìm kiếm số liệu tham chiếu để thiết lập Success Metric (giảm thời gian từ 3-7 ngày xuống dưới 2 giờ). | Đảm bảo phần Problem Statement có tiêu chí nghiệm thu định lượng, rõ ràng. |
| Rule / Workflow / Agent | Bác bỏ phương án dùng Agent tự động nạp tiền và chạy quảng cáo dựa trên dữ liệu phỏng vấn người dùng. | Hướng nhóm đến quyết định sử dụng Workflow có chốt chặn kiểm duyệt (Human-in-the-loop). |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Đóng góp cụ thể nhất của tôi là ở khâu Validation (Phase 4). Thông qua phỏng vấn 3 chủ shop, tôi xác nhận được rủi ro tài chính nếu hệ thống tự động hóa quảng cáo; thông tin này làm cơ sở để nhóm quyết định chọn cấu trúc Workflow (có chốt chặn phê duyệt của con người) thay vì Agent tự trị.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan (Cá nhân) | Dùng LLM để mở rộng danh sách 5 chủ đề thành 8 bài toán. | Phân tích nhanh các góc nhìn khác nhau trong đời sống. | AI sinh ra một số bài toán ngoài khả năng kiểm chứng thực tế (ví dụ: tự động hóa kho bãi lớn). | Tôi tự lược bỏ các bài toán vĩ mô và chỉ giữ lại các vấn đề sát với bối cảnh cá nhân. |
| Validation (Nhóm) | **Không dùng** | - | - | Tự thu thập dữ liệu bằng cách phỏng vấn người dùng thực tế. Việc sử dụng AI sinh dữ liệu giả lập sẽ làm sai lệch kết quả đánh giá sản phẩm. |
| Workflow (Nhóm) | Dùng AI để định dạng dữ liệu thô thành bảng Markdown. | Tiết kiệm thời gian xử lý định dạng văn bản. | AI bỏ sót trường thông tin "Fallback" trong cấu trúc bảng. | Tôi đối chiếu với tài liệu gốc của lab và bổ sung thủ công cột Fallback để đảm bảo tính toàn vẹn của báo cáo. |
| Problem Statement | Tra cứu tỷ lệ chuyển đổi trung bình trên sàn TMĐT. | Cung cấp số liệu benchmark tham khảo. | AI đề xuất mức tăng tỷ lệ chuyển đổi thiếu thực tế (tăng lên 10%). | Dựa trên dữ liệu thực tiễn của TMĐT, tôi điều chỉnh mục tiêu xuống biên độ khả thi là 2.0% - 3.0%. |
| Rule / Workflow / Agent | Yêu cầu AI so sánh giữa Workflow và Agent cho bài toán này. | Liệt kê đầy đủ các ưu điểm của việc tự động hóa. | Khuyến nghị sử dụng Agent để tối ưu hóa toàn bộ quy trình. | Tôi bác bỏ khuyến nghị này do nó vi phạm nguyên tắc quản trị rủi ro tài chính của nhóm. Tôi bảo vệ phương án Workflow. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?

**Reflection:**

```text
Ban đầu, tôi đề xuất bài toán "Tập thể dục tại nhà" do tính phổ biến của nó. Tuy nhiên, khi đối chiếu với bài toán "AI Marketing Kit" của thành viên khác, tôi nhận thấy dự án Marketing có tác động kinh tế định lượng rõ ràng hơn và khai thác tốt năng lực xử lý đa phương thức (văn bản và hình ảnh) của công nghệ GenAI hiện tại. Do đó, tôi quyết định thay đổi quan điểm và đồng thuận với lựa chọn của nhóm. 

Trong giai đoạn thiết kế giải pháp, nhóm có xu hướng thiên vị công nghệ (solution-first) khi đề xuất xây dựng Agent tự động thực thi và quản lý ngân sách các chiến dịch quảng cáo. Với vai trò phụ trách khâu Validation, tôi đã đối chiếu ý tưởng này với kết quả phỏng vấn người dùng thực tế. Dữ liệu cho thấy các chủ shop quy mô nhỏ đặc biệt e ngại rủi ro mất kiểm soát ngân sách nếu giao quyền tự quyết tài chính cho AI. Dựa trên cơ sở này, tôi đã phản biện và thuyết phục nhóm loại bỏ phương án Agent. Nhóm sau đó thống nhất chuyển sang mô hình Workflow, thiết lập cấu trúc Human-in-the-loop để người dùng trực tiếp phê duyệt nội dung và ngân sách. Việc đóng góp vào quá trình xác định đúng giới hạn tự động hóa (Boundary) này là giá trị lớn nhất tôi mang lại cho dự án.
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
