---
artifact: 3 — Outline 5 mục cho slide deck Analysis Report
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 3 — Dựng slide deck (15 phút)
time: 10 phút outline + 5 phút build slide
input: 1-research-notes.md + 2-comparison-table.md + screenshots/ + prompts/08-analysis-report.md
nop-cuoi: Có gián tiếp — outline này dùng làm cốt cho `analysis-report.pdf` (deliverable bắt buộc)
---

# 3 — Outline 5 mục cho slide deck (S1 → S5 với S5 mở rộng 8 sub-mục)

Mục tiêu: dựng outline đầy đủ cho slide deck Analysis Report ngay trong file markdown — viết hết nội dung 5 mục ở đây trước, sau đó copy sang slide (pptx / Keynote / Google Slides). Không build slide trước khi outline xong.

Lý do làm bước này: dựng thẳng slide từ log dễ bị thiếu mục hoặc bị "đẹp ngoài rỗng trong". Outline markdown ép nhóm trả lời từng câu hỏi trước khi nghĩ về thiết kế slide. Khi giảng viên / nhóm khác hỏi "vì sao bạn xếp Sản phẩm A là Promising?" — câu trả lời đã có sẵn trong outline.

Quy tắc: mỗi nhận định trong outline phải nối được về bằng chứng cụ thể (ảnh / log / số liệu công khai). Nếu một sub-mục để trống → quay lại `1-research-notes.md` đào thêm trước khi sang slide.

## Quy trình 15 phút

```text
2 phút  — Đọc lại 2-comparison-table.md để có context
8 phút  — Điền outline 5 mục (S1 → S5)
4 phút  — Riêng cho S5: mở rộng 8 sub-mục (S5.1 → S5.8)
1 phút  — Đối chiếu bảng kiểm trước khi build slide
```

> Sau 15 phút outline + đối chiếu, mới mở pptx / Google Slides / Keynote và copy nội dung sang. Slide deck export thành `analysis-report.pdf` ở cùng folder này.

---

## Thông tin chung của báo cáo

- **Mã 2 thành viên + tên**: [A20-XXXXXX (Quỳnh) + A20-YYYYYY (Đồng đội)]
- **Ngành chọn**: A — Tìm kiếm
- **Nhiệm vụ chung đã test**: Tìm kiếm thông tin và phân tích độ tin cậy output sản phẩm AI.
- **Sản phẩm A** (tên + URL): Perplexity — https://www.perplexity.ai
- **Sản phẩm B** (tên + URL): ChatGPT — https://chat.openai.com
- **Câu prompt chính xác đã dùng**: "Tìm kiếm thông tin về tính năng sản phẩm AI và so sánh điểm mạnh / điểm yếu của nó."

---

## S1 — Product Moment (slide 1-2)

Mục đích: định danh rõ 2 sản phẩm, nhiệm vụ chung, điểm gặp đầu (entry point).

### S1.1 — Bảng so sánh nhanh

| Yếu tố | Sản phẩm A | Sản phẩm B |
|---|---|---|
| Tên + URL | Perplexity — https://www.perplexity.ai | ChatGPT — https://chat.openai.com |
| Entry point (trang đầu nhìn thấy gì) | Trang AI search với khối Try Computer, hướng đến truy vấn nghiên cứu. | Giao diện chat trực tiếp với ô nhập prompt và Recent chats. |
| Ý định người dùng (vào để làm gì) | Nghiên cứu, tìm câu trả lời có dẫn nguồn. | Chat nhanh, hỏi đáp tổng quát, tạo nội dung. |
| Surface chính (chat / form / canvas / IDE / khác) | Search / QA form với kết quả và Sources bên cạnh. | Chat interface. |
| Có cần đăng nhập / paywall ngay không | Có thể dùng free, nhưng nhiều tính năng nâng cao yêu cầu Pro/Max. | Có Free, nhưng nhiều gói nâng cao (Go/Plus/Pro). |

### S1.2 — Bằng chứng (ảnh tham chiếu)

- `screenshots/product-A-1-entry.png` — entry Perplexity hiển thị logo, khối Try Computer và các prompt gợi ý.
- `screenshots/product-B-1-entry.png` — entry ChatGPT hiển thị ô chat và Recent chats. 

### S1.3 — Nhận định so sánh entry point (2-3 câu)

Perplexity tạo ấn tượng nghiên cứu hơn với giao diện tìm kiếm và nguồn tham chiếu ngay từ đầu, còn ChatGPT thân thiện với người dùng chat thông thường, phù hợp cho tương tác nhanh nhưng ít hướng dẫn kiểm chứng.

---

## S2 — Workflow Evidence (slide 3-4)

Mục đích: hiển thị luồng người dùng + 3 friction areas (Lens 3).

### S2.1 — Luồng người dùng (trước / trong / sau khi dùng AI)

```text
TRƯỚC khi gặp AI:
- Người dùng cần tìm thông tin hoặc giải pháp, thường bắt đầu từ web search hoặc prompt sẵn.

TRONG khi dùng Sản phẩm A:
1. Nhập truy vấn vào hộp search/AI.
2. Đọc câu trả lời và kiểm tra Sources ở bên.
3. Dùng link nguồn nếu muốn xác thực thêm.

TRONG khi dùng Sản phẩm B:
1. Mở chat và nhập prompt.
2. Nhận câu trả lời trực tiếp trong khung chat.
3. Nếu cần kiểm chứng, sao chép thông tin hoặc tìm nguồn thủ công.

SAU khi dùng AI:
- Xuất output ra tài liệu, copy-paste nội dung, hoặc tiếp tục hỏi follow-up trong chat. 
```

### S2.2 — 3 Friction Areas (Lens 3)

| Friction | Sản phẩm A | Sản phẩm B |
|---|---|---|
| **Physical load** (số click, tab, copy-paste) | Cần đọc thêm panel Sources, nhưng tất cả nằm trên một page. | Chỉ chat, ít thao tác; kiểm chứng cần thêm bước bên ngoài. |
| **Cognitive burden** (cần học prompt eng. / nhớ ngữ cảnh giữa lượt chat) | Hướng đến nghiên cứu nên người dùng dễ tập trung vào nguồn. | Giao diện chat đơn giản, nhưng người dùng phải tự đánh giá độ tin cậy. |
| **User workarounds** (nhóm phải tự làm gì để bù yếu điểm) | Mở nguồn để kiểm chứng khi nghi ngờ. | Phải dùng công cụ khác hoặc tìm link ngoài để đối chiếu. |

### S2.3 — Bằng chứng

- `screenshots/product-A-2-input.png` + `screenshots/product-A-3-output.png` — cho thấy input search và output có sources.
- `screenshots/product-B-2-input.png` + `screenshots/product-B-3-output.png` — cho thấy giao diện chat và output text, không rõ sources. 

### S2.4 — Nhận định: sản phẩm nào giảm friction tốt hơn? Tại sao? (3-4 câu)

Perplexity giảm friction kiểm chứng hơn nhờ panel Sources bên cạnh output, giúp người dùng không cần tách tab. ChatGPT giảm friction bắt đầu nhập và đọc nhanh, nhưng lại tạo friction khi cần xác minh thông tin vì không có citation ngay lập tức.

---

## S3 — Output & Trust (slide 5-6)

Mục đích: đánh giá chất lượng output + 6 tín hiệu đáng tin.

### S3.1 — Chất lượng output

- **Sản phẩm A**:
  - Output có **trả lời đúng câu hỏi** chính không? Có, cung cấp câu trả lời kèm các nguồn tham khảo.
  - Output có **bịa thông tin** không (hallucination)? Không thấy ngay trong ảnh, có thể kiểm chứng được bằng sources.
  - Output có **đầy đủ** hay nửa vời? Câu trả lời có cấu trúc rõ ràng, đủ điều kiện ban đầu. 
- **Sản phẩm B**:
  - Output có **trả lời đúng câu hỏi** chính không? Có, trả lời trực tiếp bằng văn bản.
  - Output có **bịa thông tin** không? Không thấy dấu hiệu rõ ràng trong ảnh, nhưng không có citation để đối chiếu.
  - Output có **đầy đủ** hay nửa vời? Câu trả lời dạng chat hơi ngắn hơn và chưa có phần kiểm chứng. 

### S3.2 — 6 Tín hiệu đáng tin (đối chiếu)

| Tín hiệu | Sản phẩm A | Sản phẩm B |
|---|---|---|
| 1. Dẫn nguồn (citation mở được, đúng nội dung) | Có | Không |
| 2. Disclaimer khi không chắc | Không rõ | Không rõ |
| 3. Fallback / dừng lại khi out-of-scope | Không rõ | Không rõ |
| 4. Consistency (chạy 2 lần cùng prompt) | Chưa kiểm tra | Chưa kiểm tra |
| 5. User control (sửa, dừng, regenerate, undo) | Có các nút action trên giao diện | Có các nút action chat nhưng không thấy source control |
| 6. Explanation (giải thích "vì sao AI nói thế") | Có nội dung giải thích đi kèm | Có nội dung trả lời thuyết phục |

### S3.3 — Nhận định: sản phẩm nào tạo trust mạnh hơn? Vì sao? (3-4 câu)

Perplexity tạo trust mạnh hơn nhờ hiển thị Sources kèm theo output, giúp người dùng dễ kiểm chứng ngay. ChatGPT có câu trả lời rõ ràng và dễ tiếp cận, nhưng thiếu tín hiệu citation khiến trust phụ thuộc vào cảm nhận người dùng.

---

## S4 — Business Signal (slide 7)

Mục đích: định vị 2 sản phẩm trên Cost-Capability-Speed + pricing pattern.

### S4.1 — Định vị tam giác (cho mỗi sản phẩm)

- **Sản phẩm A**: mạnh-đắt — model dưới mui xe: AI search tập trung nguồn và kiến thức; lý do: có gói Pro/Max và thông tin tham khảo. 
- **Sản phẩm B**: cân bằng — model dưới mui xe: chat AI phổ thông, cung cấp nhiều gói Free/Go/Plus/Pro cho nhiều mức dùng. 

### S4.2 — Pricing pattern

| Yếu tố | Sản phẩm A | Sản phẩm B |
|---|---|---|
| Mô hình giá | Freemium với Pro / Max | Freemium với Free / Go / Plus / Pro |
| Giá entry (free tier giới hạn gì) | Có free, giới hạn tính năng cao cấp | Free có giới hạn tốc độ hoặc chức năng |
| Giá trả phí (gói chính + giá) | Pro $17 / Max $167 | Go 132k / Plus 522.5k / Pro 2.849m |
| Paywall xuất hiện ở đâu (khi hết quota / tính năng nâng cao / etc.) | Nâng cấp để truy cập nhiều nguồn hơn | Nâng cấp để có ưu tiên tốc độ và tính năng mới |

### S4.3 — Nhận định: chiến lược kinh doanh của 2 sản phẩm khác nhau thế nào? (2-3 câu)

Perplexity định vị vào người dùng nghiên cứu và kiểm chứng cao, dùng giá trị nguồn để bán gói cao cấp. ChatGPT định vị rộng hơn với nhiều tier giá linh hoạt cho cả người dùng cá nhân và doanh nghiệp, ưu tiên trải nghiệm chat nhanh.

---

## S5 — Product Judgment (slide 8-12 — phần đậm nhất)

Mục đích: ra verdict + vận dụng 4 Lens + Spark/Loop/System + Niche/Feature Map + liên hệ Lab 1.

S5 mở rộng thành 8 sub-mục — bắt buộc xong **S5.1, S5.6, S5.7, S5.8**. Nhóm khá phải hoàn thành cả 8 sub-mục. Nhóm Đạt có thể ghi "không có nguồn công khai" cho 1-2 số liệu ở S5.2-S5.5 nhưng phải ghi rõ.

### S5.1 — Verdict (BẮT BUỘC)

- **Sản phẩm A**: Promising — Lý do: Có nguồn citation và workflow nghiên cứu, nhưng cần kiểm chứng thật kỹ để xác định độ chính xác. 
- **Sản phẩm B**: Promising — Lý do: Dễ dùng, phù hợp chat nhanh, nhưng thiếu citation nên trust yếu hơn khi dùng cho nghiên cứu. 

### S5.2 — User base + tăng trưởng

- **Sản phẩm A**: Không có số liệu công khai trong ảnh; cần tra thêm từ trang chủ hoặc báo chí. 
- **Sản phẩm B**: Không có số liệu công khai trong ảnh; cần tra thêm từ OpenAI hoặc báo cáo. 

> Không có nguồn công khai sau khi tra ở ảnh screenshot trong bài tập.

### S5.3 — Doanh thu / pricing power

- **Sản phẩm A**: Không có ARR/MRR công khai trong ảnh; pricing power nhờ thử nghiệm Pro/Max với người dùng nghiên cứu. 
- **Sản phẩm B**: Không có ARR/MRR công khai trong ảnh; pricing power đến từ hệ sinh thái OpenAI và nhiều tier giá khác nhau. 

### S5.4 — Moat phân tích (5 loại)

| Moat | Sản phẩm A | Sản phẩm B |
|---|---|---|
| Data (proprietary data flywheel) | Trung bình — có nguồn và content data, nhưng chưa rõ vòng feedback. | Trung bình — dựa trên mô hình OpenAI lớn, nhưng không có nguồn citation trực tiếp. |
| Network effects | Yếu / dễ bị copy — cạnh tranh nhiều sản phẩm search AI. | Trung bình — dựa trên hệ sinh thái OpenAI và người dùng rộng. |
| Switching cost (chi phí đổi sang sản phẩm khác) | Trung bình — nếu cần check nguồn khác có thể swap khá dễ. | Trung bình — người dùng quen chat có thể chuyển sang sản phẩm khác tương tự. |
| Brand | Trung bình — Perplexity là thương hiệu niche nghiên cứu. | Mạnh — ChatGPT là thương hiệu AI chat phổ thông. |
| Distribution (kênh tiếp cận user) | Trung bình — chủ yếu qua web, marketing trực tuyến. | Mạnh — dựa trên OpenAI và các nền tảng tích hợp rộng. |

### S5.5 — Data flywheel + feedback loop

- **Sản phẩm A**: Có cơ chế dùng user feedback và nguồn citation, nhưng chưa rõ loop compounding qua ảnh. 
- **Sản phẩm B**: Mô hình chat dựa trên dữ liệu OpenAI, loop có thể qua cập nhật sản phẩm nhưng ảnh không cho thông tin cụ thể. 

### S5.6 — Niche Down + AI Feature Map (BẮT BUỘC)

- **Sản phẩm A**:
  - Niche cụ thể (đối tượng người dùng + use case): Người dùng nghiên cứu/nhà phân tích cần câu trả lời kèm nguồn. 
  - AI Feature Map:
    - User Value: Cao — người dùng nhận được câu trả lời có dẫn nguồn. 
    - User Alignment: Cao — phù hợp với nhu cầu xác thực và nghiên cứu. 
    - Business Value: Trung bình — tốt cho người dùng chuyên sâu, chưa rõ lượng lớn. 
- **Sản phẩm B**:
  - Niche cụ thể: Người dùng muốn chat nhanh, tạo nội dung, hỏi đáp tổng quát. 
  - AI Feature Map:
    - User Value: Cao — trải nghiệm chat nhanh, tiện lợi. 
    - User Alignment: Cao — phù hợp với nhu cầu giao tiếp và hỏi đáp. 
    - Business Value: Cao — nhiều tier giá và mạnh thương hiệu OpenAI. 

### S5.7 — Spark → Loop → System (BẮT BUỘC)

- **Sản phẩm A**: Loop — có dấu hiệu xây dựng từ nguồn và citation, cần thêm dữ liệu thực tế để thành System. 
- **Sản phẩm B**: Spark / Loop — đã ở giai đoạn phổ biến, nhưng ảnh chưa rõ full feedback loop; dự báo 12 tháng tới tiếp tục mở rộng tính năng và tier. 

### S5.8 — Liên hệ Lab 1 (BẮT BUỘC)

- Sản phẩm A có rủi ro disruption tương tự case nghiên cứu công cụ tìm kiếm AI, khi nhiều startup cạnh tranh citation. 
- Sản phẩm B có rủi ro disruption tương tự case bigtech chat AI phổ thông, vì cạnh tranh nhiều dịch vụ chat thay thế. 
- Bài học rút từ Lab 1 áp dụng được cho 2 sản phẩm này thế nào? (2-3 câu): Định vị rõ niche và trust signal là quan trọng; sản phẩm phải vừa dễ dùng vừa cung cấp bằng chứng để khác biệt trong thị trường AI. 

---

## Bảng kiểm trước khi build slide

- [ ] S1 → S4 đã điền đầy đủ.
- [ ] S5.1 + S5.6 + S5.7 + S5.8 đã hoàn thành (4 sub-mục bắt buộc).
- [ ] S5.2 → S5.5 đã hoàn thành (hoặc đã ghi rõ "không có nguồn công khai" cho ô trống).
- [ ] Mỗi nhận định nối được về ảnh / log / số liệu cụ thể.
- [ ] Verdict ở S5.1 nhất quán với phân tích moat ở S5.4 và giai đoạn ở S5.7.
- [ ] 2 thành viên cùng đồng ý với toàn bộ outline.

---

## Sau khi xong outline

1. Mở pptx / Keynote / Google Slides / Figma.
2. Tạo 12-15 slide bám theo cấu trúc S1 → S5 ở trên (mỗi mục 1-3 slide).
3. **Mỗi slide có ít nhất 1 ảnh tham chiếu** (từ `screenshots/`).
4. Export PDF → lưu thành `analysis-report.pdf` trong cùng folder này.
5. Nếu dùng Google Slides công khai, lưu link vào `analysis-report-link.md` (tuỳ chọn).
6. 2 thành viên cùng copy `analysis-report.pdf` + `group-members.md` về repo cá nhân của mình.

> Tham khảo `prompts/08-analysis-report.md` nếu cần AI hỗ trợ build slide từ outline này.
