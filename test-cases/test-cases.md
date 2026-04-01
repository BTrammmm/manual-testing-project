# TEST CASES – LOGIN SYSTEM

## Chức năng: Đăng nhập hệ thống

| ID | Test Case | Steps | Expected Result | Priority |
|----|----------|------|----------------|----------|
| TC01 | Login với tài khoản hợp lệ | Nhập đúng email & password | Đăng nhập thành công | High |
| TC02 | Sai mật khẩu | Nhập đúng email, sai password | Hiển thị lỗi | High |
| TC03 | Sai email | Nhập sai email | Hiển thị lỗi | High |
| TC04 | Bỏ trống tất cả | Không nhập gì | Báo lỗi bắt buộc | High |
| TC05 | Bỏ trống password | Nhập email, bỏ password | Báo lỗi | High |
| TC06 | Bỏ trống email | Nhập password, bỏ email | Báo lỗi | High |
| TC07 | Email sai định dạng | Nhập abc123 | Báo lỗi email | Medium |
| TC08 | Password quá ngắn | Nhập < 6 ký tự | Báo lỗi | Medium |
| TC09 | Password quá dài | Nhập > 50 ký tự | Báo lỗi | Low |
| TC10 | Nhập khoảng trắng | Nhập "   " | Báo lỗi | Medium |
| TC11 | SQL Injection | Nhập ' OR 1=1 -- | Không login | High |
| TC12 | XSS script | Nhập <script>alert(1)</script> | Không thực thi script | High |
| TC13 | Login nhiều lần sai | Sai 5 lần liên tiếp | Bị khóa tài khoản | Medium |
| TC14 | Session sau login | Login thành công | Duy trì session | High |
| TC15 | Logout | Click logout | Thoát hệ thống | High |
| TC16 | Quay lại sau logout | Nhấn back | Không vào lại được | Medium |
| TC17 | Refresh sau login | Reload trang | Vẫn đăng nhập | Medium |
| TC18 | Login trên nhiều tab | Login 2 tab | Hoạt động bình thường | Low |
| TC19 | Case sensitivity | Email viết HOA/thường | Vẫn login đúng | Low |
| TC20 | Nhập ký tự đặc biệt | !@#$%^ | Không lỗi hệ thống | Low |
