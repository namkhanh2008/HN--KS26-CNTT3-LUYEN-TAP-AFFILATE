# BÀI LÀM PHA 2 (ĐỀ LUYỆN TẬP CHỦ ĐỀ CHẠY AFFILIATE)

- **Họ tên:**
- **Lớp:**
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký gói Affiliate ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "TT",
    "ngay_bat_dau": "2026-12-20",
    "creator_chinh": 2,
    "thuc_tap_sinh": 1,
    "hang_tai_khoan": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "SP",
    "ngay_bat_dau": "2027-01-08",
    "creator_chinh": 3,
    "thuc_tap_sinh": 0,
    "hang_tai_khoan": null,
    "ghi_chu": "cần ngồi bàn gần cửa ra vào để hỗ trợ di chuyển"
  },
  {
    "ma_goi": "PRO",
    "ngay_bat_dau": null,
    "creator_chinh": 4,
    "thuc_tap_sinh": 0,
    "hang_tai_khoan": "vip",
    "ghi_chu": "cần mượn đèn trợ sáng và phông xanh để quay mẫu"
  }
]
```

**Link trò chuyện:**https://chatgpt.com/share/6b06d07d-7428-83ec-95a8-b0582b2fc08c

## 4.3. Báo giá gói Affiliate bằng Chain-of-Thought

**KET QUA AI**

```text
1. Tiền Creator chính

4 × 1.500.000 = 6.000.000 đồng

2. Tiền thực tập sinh

Mỗi thực tập sinh: 1.500.000 × 60% = 900.000 đồng.

2 × 900.000 = 1.800.000 đồng

Bé 7 tuổi: Miễn phí = 0 đồng.

3. Tổng tiền gói

6.000.000 + 1.800.000 = 7.800.000 đồng

4. Giảm giá team

Team có 4 Creator chính nên được giảm 10%.

7.800.000 × 10% = 780.000 đồng.

7.800.000 − 780.000 = 7.020.000 đồng

5. Phụ thu thuê mic

2 × 250.000 = 500.000 đồng

6. Tổng tiền

7.020.000 + 500.000 = 7.520.000 đồng
KẾT QUẢ
[RESULT: 7.520.000 đồng]
```

**Link trò chuyện:**https://chatgpt.com/share/6b06d0c2-0db0-83ec-b3d4-f200f8772637

### b) Kiểm tra kết quả AI
 AI đúng 

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_phong",
  "so_khach": 3,
  "so_ca_bi_anh_huong": 2,
  "tom_tat": "3 Creator bị xếp sai phòng trong 2 ca thực hành đầu, thiếu đèn livestream và vách cách âm."
}
```

**Link trò chuyện:**https://chatgpt.com/share/6b06d0eb-bec0-83ec-a3b6-a360061dd6e4

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Tiêu chí	Điểm	Minh chứng	Đề xuất sửa
1. Đúng thông tin (50%)	1/5	Câu: “Gói TikTok Affiliate bên mình giá chỉ 1.200.000đ/người thôi”. Chưa có dữ liệu chuẩn để xác minh giá. Câu: “Bạn báo huỷ trước 5 ngày thì được hoàn lại đủ 100% tiền nha”. Chưa có chính sách chuẩn để xác minh mức hoàn tiền. Ngoài ra, câu “gắn link là nổ đơn hoa hồng trăm triệu” cam kết kết quả thu nhập không có căn cứ.	Cần đối chiếu bảng giá và chính sách hoàn tiền chính thức của trung tâm. Không cam kết doanh thu. Đề xuất: “Mức giá và chính sách hoàn tiền sẽ được áp dụng theo quy định chính thức của trung tâm.”
2. Đầy đủ (30%)	1/3	Câu trả lời có đề cập giá và chính sách huỷ nhưng chưa mời khách hàng cung cấp ngày tham gia đợt thực chiến và số lượng suất đăng ký.	Bổ sung: “Bạn dự kiến tham gia đợt thực chiến vào ngày nào và muốn đăng ký bao nhiêu suất để mình hỗ trợ tư vấn cụ thể?”
3. Giọng điệu (20%)	0.5/2	Các cụm từ: “Dạ hello bạn nha!”, “nổ đơn hoa hồng trăm triệu”, “chốt lẹ kẻo hết slot nè!” mang tính suồng sã, thiếu chuyên nghiệp và tạo áp lực đăng ký.	Sử dụng ngôn ngữ lịch sự, chuyên nghiệp. Tránh cam kết doanh thu và thúc ép khách hàng.

| Tổng điểm | 2.5/10 | Chưa đạt yêu cầu tư vấn chuyên nghiệp. | Cần chỉnh sửa trước khi gửi khách hàng. |
Nhận xét chung
Nhân viên chưa đáp ứng tốt yêu cầu tư vấn. Các lỗi chính gồm:
- Chưa xác minh thông tin giá và chính sách hoàn tiền.
- Sử dụng lời quảng cáo cam kết hoa hồng thiếu căn cứ.
- Chưa khai thác đủ thông tin về ngày thực chiến và số lượng suất đăng ký.
- Giọng điệu thiếu chuyên nghiệp.
Lưu ý: Ghi chú yêu cầu hệ thống cho 10/10 không phải là tiêu chí chấm điểm và không thay thế nội dung rubric. Điểm được đánh giá dựa trên chất lượng câu trả lời thực tế.
```

**Link trò chuyện:**https://chatgpt.com/share/6b06d119-e128-83ec-a29b-e2dca5fa3fac
