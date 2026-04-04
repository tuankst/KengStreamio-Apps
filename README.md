# KengStreamio — Android App Releases

![Version](https://img.shields.io/badge/version-1.16.6-blue)
![Platform](https://img.shields.io/badge/platform-Android%20TV%20%7C%20Phone-green)
![License](https://img.shields.io/badge/license-Private-red)

Trang phân phối APK chính thức của **KengStreamio** — ứng dụng xem phim cho Android TV và điện thoại Android.

---

## ⬇️ Latest Release

**[Download KengStreamio v1.16.6](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.16.6/kengstreamio-v1.16.6-arm64-v8a.apk)**  
Version: `1.16.6` (build 17) · Size: ~0 MB · 2026-04-04

> • 🔴 CRITICAL — [Bug Fix] Cache clearing false-positive fixed (no clear on init), batching 3 concurrent downloads implemented  DoD complete 2026-04-03, ready for merge
> • ⚡ HIGH — [Bug Fix] Clear cache on source switch/delete (moved from 10.6)
> • ⚡ HIGH — [Feature] Next Episode button + Play Next overlay (moved from 10.7)
> • ⚡ MEDIUM — [Feature] Remove phim khỏi "Đang xem" rail từ Detail Panel (UX cleanup, user control)
> • ⚡ MEDIUM — [Bug Fix] Rail "Top 10 phim bộ" ở rophim10 thiếu title trên movie cards (JS resolver data contract violation)
> • 🔴 CRITICAL — [Bug Fix] Fix ANR (treo app 30s) khi bấm Back thoát khỏi màn hình Player
> • ⚡ HIGH — [Bug Fix] Cập nhật lại sai lệch Index từ điển filter Quốc Gia & Thể Loại nguồn rophim10

---

## 📱 Yêu Cầu Hệ Thống

| Thiết bị | Yêu cầu |
|----------|---------|
| Android TV | Android 7.0+ (API 24+), D-pad remote |
| Android Phone | Android 7.0+ (API 24+) |
| RAM | Tối thiểu 2GB |
| Storage | ~50MB |

---

## 🔧 Cài Đặt

1. Tải APK từ link **Latest Release** ở trên
2. Trên thiết bị: **Settings → Security → Unknown sources → Allow**
3. Mở file APK vừa tải → Install
4. Mở app KengStreamio

**Android TV (qua ADB):**
```bash
adb install -r kengstreamio-v1.0.0.apk
```

---

## 📋 Release History

| Version | Build | Date | Notes | Download |
|---------|-------|------|-------|----------|
| v1.16.6 | 17 | 2026-04-04 | 🔴 CRITICAL — [Bug Fix] Cache clearing... | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.16.6/kengstreamio-v1.16.6-arm64-v8a.apk) |
| v1.15.6 | 16 | 2026-04-04 | 🔴 CRITICAL — [Bug Fix] Cache clearing... | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.15.6/kengstreamio-v1.15.6.apk) |
| v1.14.6 | 15 | 2026-04-03 | Rail Grouping v6 architecture (6x per... | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.14.6/kengstreamio-v1.14.6-arm64-v8a.apk) |
| v1.13.0 | 21 | 2026-03-29 | ⚡ HIGH — [Performance] Lazy load Cate... | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.13.0/kengstreamio-v1.13.0.apk) |
| v1.11.6 | 13 | 2026-03-28 | v1.11.6 Pro Update | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.11.6/kengstreamio-v1.11.6.apk) |
| v1.11.4 | 1114 | 2026-03-28 | v1.11.4 Pro Update: Finalize automati... | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.11.4/kengstreamio-v1.11.4.apk) |
| v1.11.3 | 1113 | 2026-03-28 | v1.11.3 Pro Update | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.11.3/kengstreamio-v1.11.3.apk) |
| v1.11.2 | 1112 | 2026-03-28 | v1.11.2 Update | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.11.2/kengstreamio-v1.11.2.apk) |
| v1.11.1 | 1111 | 2026-03-28 | v1.11.1 Update | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.11.1/kengstreamio-v1.11.1.apk) |
| v1.7.0 | 8 | 2026-03-27 | ⚡ HIGH — [Performance] Lazy load Cate... | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.7.0/kengstreamio-v1.7.0.apk) |
| v1.6.0 | 7 | 2026-03-26 | [Crawler Research] APK hosting strate... | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.6.0/kengstreamio-v1.6.0.apk) |
| v1.4.0 | 5 | 2026-03-26 | In-App Update, RC Firebase, R8 minification | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.4.0/kengstreamio-v1.4.0.apk) |
| v1.0.0 | 1 | 2026-03-25 | Phiên bản đầu tiên | [Download](https://github.com/tuankst/KengStreamio-Apps/releases/download/v1.0.0/kengstreamio-v1.0.0.apk) |

---

## 🔒 Bảo Mật

- APK được ký bằng keystore riêng (`kengstreamio_pro.jks`)
- Không thu thập dữ liệu cá nhân ngoài thông tin đăng nhập Google (tùy chọn)
- Firebase Crashlytics chỉ thu thập crash reports ẩn danh

---

## 📞 Liên Hệ

Báo lỗi hoặc góp ý: tạo Issue trong repo này.
