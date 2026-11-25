# BÀI LÀM PHA 2 

- **Họ tên:** Nguyễn Bảo Huy
- **Lớp:** CNTT1
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** Gemini

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "SVT",
    "ngay_su_kien": "2026-12-20",
    "nguoi_lon": 2,
    "tre_em": 1,
    "loai_ve": "thuong",
    "vip": false,
    "ghi_chu": null
  },
  {
    "ma_goi": "FZ",
    "ngay_su_kien": "2027-01-05",
    "nguoi_lon": 3,
    "tre_em": 0,
    "loai_ve": null,
    "vip": false,
    "ghi_chu": "hỗ trợ xe lăn"
  },
  {
    "ma_goi": "VIP",
    "ngay_su_kien": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "loai_ve": "vip",
    "vip": true,
    "ghi_chu": "người khiếm thị cần hỗ trợ tìm chỗ"
  }
]
```

**Link trò chuyện:**

## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
Chi Tiết Tính Toán Giá Vé Sự Kiện Thể Thao

Dưới đây là phần suy luận và tính toán từng bước tổng số tiền nhóm cổ động viên cần thanh toán cho gói vé SVT – Sân Vận Động (giá gốc: 1.200.000 đồng/người lớn):

1. Tiền người lớn

Nhóm có 5 người lớn, mỗi người mua gói SVT giá 1.200.000 đồng.

Công thức: Tiền người lớn= 5  1.200.000 = 6.000.000(đồng)

2. Tiền trẻ em

Có 2 trẻ em trong độ tuổi từ 5 đến 11 (8 tuổi và 10 tuổi), mỗi bé tính 70% giá người lớn:

$\text{Giá vé trẻ em (5–11 tuổi)} = 1.200.000 \times 70\% = 840.000\text{ đồng/bé}$

$\text{Tiền cho 2 bé (8 và 10 tuổi)} = 2 \times 840.000 = 1.680.000\text{ đồng}$

Có 1 bé 3 tuổi (dưới 5 tuổi): miễn phí ($0\text{ đồng}$).

Tổng tiền trẻ em: 1.680.000 + 0 = 1.680.000(đồng)

3. Tiền vé

Tiền vé trước giảm giá bao gồm tiền người lớn cộng tiền trẻ em:

Tiền vé = 6.000.000 + 1.680.000 = 7.680.000(đồng)

4. Giảm giá nhóm

Nhóm có 5 người lớn (đạt điều kiện từ 5 người lớn trở lên) nên được giảm 5% trên tổng tiền vé:

Giảm giá nhóm = 7.680.000 X 5% = 384.000(đồng)

Tiền vé sau giảm = 7.680.000 - 384.000 = 7.296.000\text{ đồng}$

5. Phụ thu

Có 1 người lớn chọn khu ghế ưu tiên, phụ thu 300.000 đồng/người (không áp dụng giảm giá):

Phụ thu = 1x300.000 = 300.000 (đồng)

6. Tổng tiền

Tổng tiền bằng tiền vé sau giảm cộng phụ thu:

 Tổng tiền  = 7.296.000 + 300.000 = 7.596.000 (đồng)

[RESULT: 7.596.000 đồng]
```

**Link trò chuyện:**

### b) Kiểm tra kết quả AI

Đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_khieu_nai": "sai_khu_vuc",
  "ma_goi": "SVT",
  "ngay_su_kien": "2026-11-02",
  "so_khach": 2,
  "so_hiep_bi_anh_huong": 2,
  "tong_den_bu": 2000000,
  "can_duyet": true,
  "phuong_an_xu_ly": "hoàn 500.000 đồng/khách cho mỗi hiệp bị ảnh hưởng",
  "tom_tat": "Khán giả mua vé SVT bị xếp sai sang khu không mái che trong 2 hiệp đầu gặp trời mưa."
}
```

**Link trò chuyện:**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**
