# BUG REPORT

## BUG01
- Title: Không login được dù nhập đúng
- Steps:
  1. Nhập đúng tài khoản
  2. Click login
- Expected: Đăng nhập thành công
- Actual: Không phản hồi
- Severity: High

## BUG02
- Title: Không báo lỗi khi bỏ trống
- Steps:
  1. Không nhập gì
  2. Click login
- Expected: Hiển thị lỗi
- Actual: Không có gì
- Severity: Medium
  
## BUG03
- Title: Cho phép SQL Injection khi login
- Severity: Critical
