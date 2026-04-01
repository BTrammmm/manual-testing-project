# BUG REPORT

## BUG01
- Title: Không login được dù nhập đúng thông tin
- Steps:
  1. Nhập đúng email và password
  2. Click login
- Expected: Đăng nhập thành công
- Actual: Không phản hồi
- Severity: High
- Priority: High

## BUG02
- Title: Không hiển thị lỗi khi bỏ trống
- Steps:
  1. Không nhập gì
  2. Click login
- Expected: Hiển thị lỗi bắt buộc
- Actual: Không có thông báo
- Severity: Medium
- Priority: Medium

## BUG03
- Title: Cho phép nhập SQL Injection
- Steps:
  1. Nhập ' OR 1=1 --
  2. Click login
- Expected: Không đăng nhập
- Actual: Có thể bypass login
- Severity: Critical
- Priority: High
