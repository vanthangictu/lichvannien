# Lịch Vạn Niên (Android)

App WebView bọc trang lịch trong `app/src/main/assets/index.html` (giao diện tờ lịch vàng, chi tiết ngày, lịch tháng, đổi ngày, văn khấn, ghi chú, bói).

## Cách 1: Android Studio
1. Mở thư mục này bằng Android Studio (Hedgehog trở lên), chờ Gradle sync.
2. Build > Build APK(s). File: `app/build/outputs/apk/debug/app-debug.apk`.
3. Chép file sang điện thoại, bật "Cài từ nguồn không xác định" rồi cài.

## Cách 2: GitHub Actions (không cần cài gì)
Đẩy thư mục này lên một repo GitHub, vào tab Actions > Build APK > Run workflow,
tải file `LichVanNien-debug-apk` ở mục Artifacts.

Sửa giao diện: chỉnh `app/src/main/assets/index.html`.
