# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 05
- **Họ tên:**Đỗ Duy Thành
- **Lớp:**CNTT2
- **Link repository Pha2:**https://github.com/ZaxDontCare/HN-KS26-CNTT2_PromptAI_H02_Pha1_Pha2
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**ChatGPT

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé xem phim ra JSON

**KET QUA AI**

```text
```
[
  {
    "loai_ve": "P2D",
    "ngay_chieu": "2026-12-24",
    "ve_nguoi_lon": 2,
    "ve_tre_em": 1,
    "loai_ghe": "thuong",
    "ghi_chu": null
  },
  {
    "loai_ve": "P3D",
    "ngay_chieu": "2027-01-01",
    "ve_nguoi_lon": 3,
    "ve_tre_em": 0,
    "loai_ghe": null,
    "ghi_chu": "1 người hay chóng mặt, cần ngồi gần lối ra"
  },
  {
    "loai_ve": "GOLD",
    "ngay_chieu": null,
    "ve_nguoi_lon": 4,
    "ve_tre_em": 0,
    "loai_ghe": "doi",
    "ghi_chu": "1 bạn đi xe lăn"
  }
]
```
```

**Link trò chuyện:**https://chatgpt.com/share/6b079dba-8308-83ec-a0c9-54d450d318d4

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
**1. Tiền vé người lớn**

5 người lớn × 130.000 = **650.000 đồng**

**2. Tiền vé trẻ em**

- Trẻ em cao 1,1 m: 130.000 × 70% = 91.000 đồng
- Trẻ em cao 1,25 m: 130.000 × 70% = 91.000 đồng
- Bé cao 0,9 m: Miễn phí (ngồi cùng người lớn).

Tổng tiền vé trẻ em = 91.000 × 2 = **182.000 đồng**

**3. Tiền vé trước giảm giá**

650.000 + 182.000 = **832.000 đồng**

**4. Giảm giá nhóm**

Nhóm có 5 người lớn nên được giảm 10%.

832.000 × 10% = 83.200 đồng

Tiền vé sau giảm = 832.000 − 83.200 = **748.800 đồng**

**5. Tiền combo**

3 × 75.000 = **225.000 đồng**

**6. Tổng tiền**

748.800 + 225.000 = **973.800 đồng**

[RESULT: 973.800 đồng]
```

**Link trò chuyện:**https://chatgpt.com/share/6b079e4d-7ca0-83ec-9a90-2d5b64938fd6

### b) Kiểm tra kết quả AI

Đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{\
&#x20; "loai_su_co": "khac",\
&#x20; "so_khach": 4,\
&#x20; "so_dem_bi_anh_huong": null,\
&#x20; "tom_tat": "Hai suất chiếu tại phòng 3 đều bị mất tiếng hơn 15 phút giữa phim."\
}
```

**Link trò chuyện:**https://chatgpt.com/share/6b079ec3-7ef4-83ec-9095-964119f09bd6

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
| Tiêu chí             | Điểm       | Minh chứng                                                                                                                     | Đề xuất sửa                                                  |
| -------------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| Đúng thông tin (50%) | 0/5        | Giá vé báo 80.000 đồng, sai giá chuẩn 90.000 đồng. Chính sách hoàn tiền trước 2 tiếng là sai; dưới 3 giờ không được hoàn tiền. | Báo đúng giá 90.000 đồng/vé và chính sách huỷ theo quy định. |
| Đầy đủ (30%)         | 0/3        | Chỉ trả lời về giá và huỷ vé, không mời khách cung cấp ngày đi, số lượng khách để đặt vé.                                      | Bổ sung lời mời khách cung cấp ngày đi và số lượng vé.       |
| Giọng điệu (20%)     | 0.5/2      | Dùng từ suồng sã như "rẻ xỉu", "nè", "nha".                                                                                    | Sử dụng ngôn ngữ lịch sự, chuyên nghiệp hơn.                 |
| **Tổng điểm**        | **0.5/10** |                                                                                                                                |                                                              |
```

**Link trò chuyện:**https://chatgpt.com/share/6b079f00-7ccc-83ec-9587-36a1ef0cef4b
