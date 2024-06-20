Đây là project môn chuyên đề CNPM của thầy Lê Hà Thanh. Link: Tài liệu triển khai: https://drive.google.com/drive/folders/1Rb2Wff80fpQBTgVdlVikJwEs5b7LjoN3?usp=sharing

Các bước thực hiện:

Tạo Repository trên GitHub: Nếu bạn chưa có, tạo một repository mới trên GitHub.

Tạo thư mục .github/workflows: Trong repository của bạn, tạo một thư mục có tên là .github/workflows.

Tạo File Workflow: Bên trong thư mục .github/workflows, tạo một file YAML (ví dụ: ci-cd.yml) để định nghĩa workflow.

Định nghĩa các triggers: Xác định khi nào workflow sẽ chạy, ví dụ: khi có push hoặc pull request vào nhánh main.

Thiết lập các jobs: Định nghĩa các job mà bạn muốn thực hiện. Mỗi job sẽ chạy trên một hệ điều hành cụ thể (ví dụ: ubuntu-latest).

Thêm các steps vào mỗi job:

Checkout code: Sử dụng action actions/checkout để lấy code từ repository.

Thiết lập môi trường: Cài đặt các dependencies cần thiết (ví dụ: thiết lập Node.js hoặc các ngôn ngữ khác).

Chạy các lệnh build/test: Thực hiện build và chạy các test của bạn.

Triển khai: (Nếu cần) Triển khai ứng dụng của bạn lên môi trường staging/production.

Commit và Push file workflow: Commit và push file YAML lên repository của bạn.

Kiểm tra workflow: Sau khi push, kiểm tra tab "Actions" trên GitHub để xem workflow của bạn có chạy thành công không.
