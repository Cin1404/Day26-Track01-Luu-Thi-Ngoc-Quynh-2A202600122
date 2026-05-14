---
artifact: 2 — Bảng so sánh 2 sản phẩm theo 5 mục
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Chuyển giao Phase 2 → Phase 3 (5 phút)
time: 5 phút
input: 1-research-notes.md + screenshots/
nop-cuoi: Không — file trung gian (đầu vào cho `3-FINAL-analysis-outline.md`)
---

# 2 — Bảng so sánh 2 sản phẩm theo 5 mục slide deck

Mục tiêu: gộp toàn bộ quan sát ở Bước 1 thành **một bảng so sánh nén** — cùng cấu trúc 5 mục mà slide deck cuối sẽ dùng. Sau bước này, nhóm có "khung xương" của slide deck.

Lý do làm bước này: nhảy thẳng từ log sang slide dễ bị bỏ sót mục. Bảng so sánh ép nhóm trả lời từng mục cho cả 2 sản phẩm song song — phát hiện ngay nếu mục nào còn thiếu bằng chứng.

Quy tắc: mỗi ô của bảng dài tối đa 2 câu. Nếu ô nào để trống → quay lại `1-research-notes.md` đào thêm trước khi sang Bước 3.

## Quy trình 5 phút

```text
3 phút  — Điền bảng so sánh 5 mục (5 dòng × 2 cột)
1 phút  — Đánh dấu ô nào còn thiếu bằng chứng
1 phút  — Quyết định: cần test thêm hay đủ để sang slide?
```

---

## Phần A — Bảng so sánh 5 mục

| Mục | Sản phẩm A | Sản phẩm B |
|---|---|---|
| **S1 — Product Moment**<br><sup>Entry point + ý định người dùng + surface chính (chat / form / canvas / IDE)</sup> | Perplexity mở ra trang search/AI với logo và khối Try Computer, dành cho workflow nghiên cứu. | ChatGPT mở ra giao diện chat quen thuộc và Recent chats, phù hợp với người dùng cần nhanh chóng nhập prompt. |
| **S2 — Workflow Evidence**<br><sup>Trước / trong / sau khi dùng AI. Friction chính (số click, tab, copy-paste, load mental)</sup> | Dùng search prompt và đọc output + sources trên cùng một màn hình, cần xem thêm panel nguồn. | Dùng chat trực tiếp, ít bước lựa chọn, nhưng nếu cần kiểm chứng phải tự tìm nguồn. |
| **S3 — Output &amp; Trust**<br><sup>Chất lượng output + dẫn nguồn + disclaimer + control cho người dùng</sup> | Output có nguồn rõ ràng với panel Sources 10 nguồn, giúp kiểm tra độ tin cậy. | Output có cấu trúc tốt nhưng không thấy citation trong ảnh, nên trust dựa vào nội dung. |
| **S4 — Business Signal**<br><sup>Pricing + giới hạn / paywall + định vị Cost-Capability-Speed (rẻ-nhanh hay mạnh-đắt)</sup> | Freemium với Pro $17 và Max $167, định vị hướng nghiên cứu/enterprise. | Freemium rộng với Free, Go 132k, Plus 522.5k, Pro 2.849m, định vị cân bằng giữa dùng nhanh và trả phí. |
| **S5 — Product Judgment**<br><sup>Verdict 1 dòng: Strong / Promising / Weak / At Risk + lý do</sup> | Promising — có nguồn và workflow nghiên cứu, nhưng cần kiểm chứng thêm chất lượng thực tế. | Promising — dễ dùng và phổ biến, nhưng thiếu nguồn rõ ràng nên trust cần củng cố. |

---

## Phần B — Đối chiếu 3 friction areas (nén từ Lens 3)

- **Physical load** (số click / tab / lần copy-paste): Perplexity có panel nguồn nên người dùng xem thêm thông tin, ChatGPT chỉ cần nhập prompt và đọc chat.
- **Cognitive burden** (cần học prompt engineering / có hint sẵn / có nhớ ngữ cảnh giữa lượt chat): Perplexity hỗ trợ use case và nguồn, giảm gánh nặng xác thực; ChatGPT trực quan nhưng người dùng phải tự đánh giá độ chính xác.
- **User workarounds** (nhóm phải tự làm gì để bù yếu điểm — vd: prompt lại 3 lần, copy sang công cụ khác): Perplexity cần mở nguồn kiểm chứng; ChatGPT có thể phải dùng thêm công cụ khác để đối chiếu. 

---

## Phần C — Đối chiếu 6 trust signals (nén cho mục S3)

| Tín hiệu đáng tin | Sản phẩm A | Sản phẩm B |
|---|---|---|
| 1. Dẫn nguồn (citation) — link mở được, đúng nội dung | Có | Không |
| 2. Disclaimer khi không chắc ("không tìm được", "có thể sai") | Không rõ | Không rõ |
| 3. Fallback / dừng lại khi out-of-scope | Không rõ | Không rõ |
| 4. Consistency — chạy 2 lần cùng prompt, output có giống không | Chưa kiểm tra | Chưa kiểm tra |
| 5. User control — sửa lại, dừng, regenerate, undo | Một phần | Một phần |
| 6. Explanation — giải thích "tại sao AI nói thế" (nếu có) | Có | Có |

---

## Phần D — Định vị 2 sản phẩm trên Cost-Capability-Speed (cho mục S4)

- **Sản phẩm A nghiêng về**: mạnh-đắt — lý do 1 câu: Perplexity định vị vào nghiên cứu chuyên sâu với gói Pro/Max và nguồn tham chiếu.
- **Sản phẩm B nghiêng về**: cân bằng — lý do 1 câu: ChatGPT cung cấp Free và nhiều gói trả phí, phù hợp cho nhiều đối tượng. 

---

## Phần E — Verdict sơ bộ (cho mục S5.1)

- **Sản phẩm A — verdict sơ bộ**: Promising
  - Lý do 1 câu: Có nguồn rõ ràng và workflow nghiên cứu, nhưng cần kiểm chứng thêm chất lượng thực tế.
- **Sản phẩm B — verdict sơ bộ**: Promising
  - Lý do 1 câu: Giao diện chat thân thiện và giá linh hoạt, nhưng thiếu nguồn công khai nên trust cần củng cố.

---

## Bảng kiểm trước khi sang Bước 3

- [ ] Mỗi ô của bảng so sánh 5 mục có ít nhất 1-2 câu, không trống.
- [ ] Mỗi nhận định đều có thể chỉ về ảnh / log trong `1-research-notes.md` làm bằng chứng.
- [ ] Đã định vị cả 2 sản phẩm trên Cost-Capability-Speed.
- [ ] Đã có verdict sơ bộ cho cả 2 sản phẩm.
- [ ] Còn ô nào thiếu bằng chứng → đã đánh dấu để Phase 3 đào thêm.

Sang `3-FINAL-analysis-outline.md` để dựng outline 5 mục đầy đủ (với S5 mở rộng 8 sub-mục) trước khi build slide.
