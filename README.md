# IT108 - Session 09 - Bài3: Onboarding Lập trình viên mới

## 1. Phần 1: Báo cáo phân tích I/O (Input / Output)

Dưới đây là định nghĩa phân tích đầu vào (Input) dạng văn bản thô và đầu ra (Output) khi được trình duyệt/StackEdit render trực quan:

* **Input (Văn bản thô Markdown):**
  - Sử dụng các ký tự backtick đơn `` `code` `` cho Inline Code, backtick ba lần (```python ... ```) cho Code Block.
  - Sử dụng ký tự gạch ngang kết hợp dấu ngoặc vuông `[ ]` hoặc `[x]` cho Task List.
  - Sử dụng ký tự cột `|` và gạch ngang `-` để định hình cấu trúc bảng dữ liệu (Table).
* **Output (Giao diện hiển thị trực quan - Rendered):**
  - Các tên biến được đóng khung nổi bật với nền màu xám nhạt (Inline Code).
  - Các khối mã Python được làm nổi bật cú pháp màu sắc (Syntax Highlighting) theo từng hàm, từ khóa.
  - Hiển thị bảng so sánh gọn gàng, ngay ngắn cùng danh sách nhiệm vụ tương tác (có thể tích chọn hoàn thành).

---

## 2. Phần 2: Nội dung hoàn chỉnh cho tệp README.md

```markdown
# Tài liệu Hướng dẫn Cài đặt VS Code cho Lập trình viên Mới 

Chào mừng các bạn đến với nhóm phát triển! Tài liệu này hướng dẫn các bước thiết lập môi trường làm việc chuẩn hóa.

## 1. Sử dụng Biến và Lệnh Cơ Bản

Khi viết mã, bạn cần chú ý đến biến `user_name` và biến `api_endpoint` trong hệ thống. Để khởi động nhanh môi trường, hãy chạy lệnh `code .` ngay trong Terminal.

Dưới đây là một đoạn mã Python mẫu dùng để kiểm tra hệ thống:

```python
def check_environment(version):
    print(f"Đang kiểm tra phiên bản môi trường: {version}")
    if version >= "1.89":
        return "Môi trường đạt chuẩn!"
    return "Cần cập nhật ngay!"

check_environment("1.89")
