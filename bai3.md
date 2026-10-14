# Hướng dẫn Cài đặt Môi trường Lập trình Python với VS Code

## 1\. Giới thiệu công cụ

Trong quá trình học tập, chúng ta thường xuyên kết hợp giữa việc ghi chép tài liệu và viết mã nguồn. Dưới đây là bảng so sánh nhanh giữa hai công cụ hỗ trợ chính:

|Tiêu chí|StackEdit|VS Code (Visual Studio Code)|
|-|-|-|
|**Mục đích chính**|Soạn thảo tài liệu Markdown, ghi chú nhanh.|Môi trường phát triển tích hợp (IDE) toàn diện.|
|**Khả năng chạy code**|Hỗ trợ xem trước (Preview) tài liệu văn bản.|Chạy, gỡ lỗi (Debug) và quản lý mã nguồn trực tiếp.|
|**Hệ sinh thái**|Tích hợp đám mây (Google Drive, Dropbox).|Kho Extension phong phú (Python, Git, Docker).|

\---

## 2\. Các bước cài đặt cơ bản

### Bước 1: Khởi tạo biến môi trường

Trước khi bắt đầu, hãy đảm bảo bạn đã khai báo đúng tên biến `python\_path` trong hệ thống để tránh lỗi biên dịch.

### Bước 2: Kiểm tra phiên bản Python

Mở Terminal và chạy đoạn mã Python sau để xác minh hệ thống:

```python
import sys
import platform

def check\_environment():
    print(f"Python Version: {platform.python\_version()}")
    print(f"Execution Path: {sys.executable}")
    if sys.version\_info >= (3, 10):
        print("Trạng thái: Đạt chuẩn yêu cầu hệ thống.")
    else:
        print("Cảnh báo: Cần nâng cấp phiên bản Python!")

if \_\_name\_\_ == "\_\_main\_\_":
    check\_environment()
```

\---

## 3\. Danh sách kiểm tra tiến độ (Task List)

Hoàn thành các mốc công việc sau để kết thúc quá trình thiết lập:

* \[x] Tải và cài đặt phiên bản VS Code mới nhất từ trang chủ.
* \[ ] Cài đặt các Extension cốt lõi: **Python**, **Pylance**, và **GitLens**.
* \[ ] Cấu hình phím tắt và font chữ `Fira Code` cho Terminal.
* \[ ] Tạo repository trên GitHub để đồng bộ mã nguồn bài tập.

\---

\# Kết thúc tài liệu hướng dẫn cài đặt môi trường.

