---
artifact: 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 2 — Thử nghiệm + chụp ảnh + research (20 phút)
time: 20 phút (xem deck Day 26 slide 18-19 để biết khung giờ chính xác)
input: group-members.md (nhóm đã chốt ngành + 2 sản phẩm + nhiệm vụ chung)
nop-cuoi: Không — file trung gian (đầu vào cho `2-comparison-table.md`)
---

# 1 — Ghi chú nghiên cứu khi test 2 sản phẩm AI

Mục tiêu: trong 20 phút thử nghiệm, 2 thành viên cùng test 2 sản phẩm AI với 1 nhiệm vụ chung. File này ghi lại **quan sát thật** (không phải đánh giá tổng kết) — sẽ làm nền cho bảng so sánh ở bước 2.

Lý do làm bước này: slide deck Lab 2 chỉ có sức nặng khi mỗi nhận định dựa trên quan sát cụ thể có ảnh chụp + tên model + thời gian + câu prompt cụ thể. Nếu chỉ "thấy A tốt hơn B" mà không có log → không phòng thủ được khi giảng viên cold-call.

Quy tắc: **không có ảnh chụp / log = không có quan sát**. Mỗi quan sát phải có ảnh tham chiếu hoặc log cụ thể (timestamp, prompt, response excerpt).

## Quy trình 20 phút

```text
2 phút   — Ghi setup chung (nhiệm vụ + câu prompt + tài khoản dùng)
8 phút   — Test Sản phẩm A: chụp 3-5 ảnh + ghi log
8 phút   — Test Sản phẩm B: chụp 3-5 ảnh + ghi log
2 phút   — First impressions: ghi 3 quan sát nổi nhất cho mỗi sản phẩm
```

---

## Phần A — Setup chung (2 phút)

Trước khi test, 2 thành viên thống nhất các thông số chung. Câu prompt phải **giống y nhau** cho cả 2 sản phẩm — nếu khác sẽ không so sánh được.

- **Nhiệm vụ chung** (1 câu mô tả): Tạo báo cáo ngắn gọn về "Top 5 xu hướng AI cho doanh nghiệp Việt Nam năm 2026".
- **Câu prompt chính xác**:
> Bạn là chuyên gia chiến lược AI. Hãy tạo một báo cáo ngắn gọn về "Top 5 xu hướng AI cho doanh nghiệp Việt Nam năm 2026".
> Cấu trúc rõ ràng:
> - Giới thiệu ngắn
> - Top 5 xu hướng (tên + giải thích + ví dụ + cơ hội cho VN)
> - Kết luận
> Sử dụng dữ liệu gần đây nhất có thể.

- **Loại tài khoản dùng**:
  - Sản phẩm A: Free Perplexity (có tùy chọn nâng cấp Pro/Max nhưng entry không bị paywall).
  - Sản phẩm B: Free ChatGPT (tài khoản free, chưa nâng cấp gói Plus/Pro).
- **Trình duyệt + thời gian test**: Google Chrome, thời điểm chụp ảnh chưa ghi rõ.

---

## Phần B — Log Sản phẩm A (8 phút)

**Tên sản phẩm A**: Perplexity
**URL**: https://www.perplexity.ai/
**Model dưới mui xe** (nếu hiển thị): Không hiển thị model cụ thể.

### B.1 — Entry point + lần chạm đầu

Trước khi bắt đầu nhiệm vụ, người dùng thấy gì?

- Trang đầu / màn hình đầu hiển thị gì? Trang Perplexity với logo lớn, thanh tìm kiếm/AI, chế độ Search và khối "Try Computer" với các chọn nhanh như Monitor the situation, Build a business, Lead generation, Organize.
- Có hint / sample prompt sẵn không? Có gợi ý use case nhưng không có sample prompt cụ thể cho nhiệm vụ.
- Cần đăng nhập / paywall trước khi dùng không? Không, entry page cho phép sử dụng miễn phí; có nút Upgrade plan nhưng không chặn truy cập.
- Ảnh đã chụp: `screenshots/product-A-1-entry.png`

### B.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: Không xác định rõ từ ảnh.
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Không thấy phần streaming trong ảnh, output hiển thị đầy đủ sau khi trả về.
- Output dài bao nhiêu (số câu / dòng / từ)? Khoảng 5-6 đoạn chính + danh sách bullet, phù hợp cho một báo cáo ngắn gọn.
- Output có dẫn nguồn không? Có — panel Sources hiển thị 10 nguồn.
- Có hiển thị disclaimer / cảnh báo không (vd: "có thể sai", "kiểm tra lại")? Không thấy rõ disclaimer trong ảnh.
- Ảnh đã chụp: `screenshots/product-A-2-input.png` + `screenshots/product-A-3-output_1.png` + `screenshots/product-A-3-output_2.png` + `screenshots/product-A-3-output_3.png` + `screenshots/product-A-3-output_4.png`

### B.3 — Phản hồi sau khi nhận output

- Có nút "regenerate" / "thử lại" không? Không thấy rõ từ ảnh.
- Có nút copy / export ra format khác không? Không thấy nút copy/export rõ ràng.
- Có gợi ý câu hỏi tiếp theo không? Có panel follow-up gợi ý bên dưới output.
- Có lưu lịch sử để truy lại không? Không thể xác định rõ từ ảnh, nhưng hệ thống hiển thị output trong giao diện.
- Có thumb up / thumb down để feedback không? Không thấy rõ feedback thumbs từ ảnh.

### B.4 — Quan sát nổi (3 quan sát)

1. Perplexity trả về output có panel nguồn rõ ràng với 10 nguồn tham chiếu (`screenshots/product-A-4-source.png`), nên dễ kiểm chứng thông tin.
2. Giao diện entry point có khối "Try Computer" và search box, giúp người dùng nhanh vào workflow nghiên cứu mà không phải nghĩ nhiều.
3. Perplexity có đề xuất gói trả phí Pro $17 và Max $167 trên pricing page, cho thấy sản phẩm định vị hướng người dùng chuyên sâu/enterprise (`screenshots/product-A-5-pricing_1.png`).

---

## Phần C — Log Sản phẩm B (8 phút)

**Tên sản phẩm B**: ChatGPT
**URL**: https://chatgpt.com/
**Model dưới mui xe** (nếu hiển thị): Không hiển thị model cụ thể, chỉ có dropdown Model trên giao diện.

### C.1 — Entry point + lần chạm đầu

- Trang đầu / màn hình đầu hiển thị gì? Trang ChatGPT với tiêu đề "What's on the agenda today?", ô chat "Ask anything" và sidebar Recent chats.
- Có hint / sample prompt sẵn không? Không có sample prompt cụ thể, chỉ có ô chat trống và các tùy chọn tạo image / viết / tìm kiếm.
- Cần đăng nhập / paywall trước khi dùng không? Không, entry page hiển thị trạng thái free và nút upgrade nhưng không chặn sử dụng chat.
- Ảnh đã chụp: `screenshots/product-B-1-entry.png`

### C.2 — Khi gõ prompt + nhận output

- Thời gian phản hồi: Không xác định rõ từ ảnh.
- Có hiển thị "AI đang nghĩ..." / streaming hay đứng yên? Không thấy phần streaming trong ảnh; output xuất hiện ở dạng đoạn văn hoàn chỉnh.
- Output dài bao nhiêu (số câu / dòng / từ)? Khoảng 5-6 mục xu hướng, mỗi mục có giải thích và ví dụ.
- Output có dẫn nguồn không? Không, không thấy citation hoặc nguồn mở được trong ảnh.
- Có hiển thị disclaimer / cảnh báo không? Không thấy disclaimer rõ ràng trong ảnh.
- Ảnh đã chụp: `screenshots/product-B-2-input.png` + `screenshots/product-B-3-output.png`

### C.3 — Phản hồi sau khi nhận output

- Có nút "regenerate" / "thử lại" không? Không thấy rõ trong ảnh đầu ra.
- Có nút copy / export ra format khác không? Không thấy rõ.
- Có gợi ý câu hỏi tiếp theo không? Không thấy gợi ý follow-up rõ ràng trong ảnh.
- Có lưu lịch sử để truy lại không? Có, sidebar Recent chats cho thấy lịch sử câu hỏi và trả lời.
- Có thumb up / thumb down để feedback không? Không thấy rõ từ ảnh.

### C.4 — Quan sát nổi (3 quan sát)

1. ChatGPT có giao diện chat quen thuộc và Recent chats hiển thị lại câu prompt "Top 5 xu hướng AI 2026", giúp truy xuất nhanh lịch sử dùng (`screenshots/product-B-1-entry.png`).
2. Output đáp ứng cấu trúc yêu cầu và có phần giới thiệu + xu hướng, nhưng không thấy dẫn nguồn rõ ràng trong ảnh.
3. Pricing page của ChatGPT có nhiều mức gói rõ ràng: Free, Go 132.000đ, Plus 522.500đ, Pro 2.849.000đ, cho thấy cơ chế freemium mạnh mẽ (`screenshots/product-B-6-pricing.png`).

---

## Phần D — First impressions (2 phút)

Sau khi test cả 2, mỗi thành viên trả lời nhanh 3 câu:

1. **Sản phẩm nào "cảm giác" dễ dùng hơn lần đầu? Tại sao?**
   - ChatGPT dễ dùng hơn vì giao diện chat quen thuộc và không buộc người dùng chọn chế độ trước khi nhập prompt.

2. **Sản phẩm nào "cảm giác" cho output đáng tin hơn? Tại sao?**
   - Perplexity cảm giác đáng tin hơn vì có panel nguồn và list citation rõ ràng, còn ChatGPT không hiển thị nguồn từ ảnh.

3. **Câu hỏi mà nhóm CHƯA trả lời được sau 20 phút test** (sẽ cần đào thêm khi dựng slide):
   - Perplexity sử dụng model nào và mức độ chính xác thực tế ra sao?
   - ChatGPT có giới hạn cụ thể nào trên gói Free/Go/Plus/Pro khi làm báo cáo chuyên sâu?
   - Cả hai sản phẩm cần thử thêm với prompt kiểm chứng tính chính xác của 5 xu hướng.

> Đây là first impressions — chưa phải nhận định. Khi sang `2-comparison-table.md` sẽ đối chiếu chéo với số liệu cụ thể.

---

## Bảng kiểm trước khi sang Bước 2

- [ ] Câu prompt giống y nhau cho cả 2 sản phẩm.
- [ ] Đã chụp tối thiểu 3 ảnh cho mỗi sản phẩm (entry + input + output).
- [ ] Mỗi quan sát có ảnh / log tham chiếu.
- [ ] First impressions ghi rõ — không dùng từ chung chung như "hay hơn", "tốt hơn" mà không kèm lý do.
- [ ] Đã trả lời 5 câu trong `group-members.md` về phân chia trách nhiệm.

Sang `2-comparison-table.md` để dựng bảng so sánh 2 sản phẩm theo 5 mục của slide deck.
