# 1 Người Project

Dự án Build in Public dành cho những người làm việc độc lập (Solopreneurs). Công cụ đơn giản, hiệu quả, chi phí thấp.

## Giới thiệu

"1 Người" là một dự án cá nhân, hướng tới việc xây dựng các công cụ nhỏ gọn (Micro SaaS) phục vụ cho cộng đồng những người làm việc độc lập.

## Các dự án con (Sub-projects)

Dự án này bao gồm các trang web cho các sản phẩm con:

### 1. Tề Gia (`/tegia`)
Hệ điều hành số cho gia đình Việt. Quản lý tài chính, sự kiện, quan hệ và gia phả.
- **Demo:** `/tegia/demo`

### 2. Vibecode Kit (`/vibea`)
Bộ công cụ (Kit) và tài liệu hướng dẫn (Knowledge Base) để biến ý tưởng thành sản phẩm với sự hỗ trợ của AI, theo mô hình Partnership.
- **PP:** `/vibea/pp`

## Cấu trúc thư mục

```
/
├── index.html        # Trang chủ 1 Người
├── logo.png          # Logo dự án
├── tegia/            # Dự án Tề Gia
│   ├── index.html
│   └── demo/
└── vibea/            # Dự án Vibecode Kit
    ├── index.html
    └── pp/
```

## Cách chạy (Local Development)

Dự án này bao gồm các file HTML/CSS tĩnh (có thể có JS nhúng). Bạn có thể chạy bằng bất kỳ static web server nào.

Ví dụ sử dụng Python:

```bash
python3 -m http.server 8000
```

Sau đó truy cập:
- Trang chủ: `http://localhost:8000`
- Tề Gia: `http://localhost:8000/tegia`
- Vibecode Kit: `http://localhost:8000/vibea`
