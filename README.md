# Hướng dẫn build APK

## Cách 1: Dùng Android Studio (khuyên dùng)
1. Cài Android Studio
2. Mở thư mục `tien-an-apk` này
3. Đợi Gradle sync xong
4. Build → Build Bundle(s) / APK(s) → Build APK(s)
5. File APK nằm trong `app/build/outputs/apk/`

## Cách 2: Dùng dòng lệnh (nếu đã cài Android SDK)
```bash
cd tien-an-apk
./gradlew assembleDebug
```

## Lưu ý
- App sẽ có thư mục riêng trong bộ nhớ máy.
- Dữ liệu localStorage được lưu trong private storage của app, không bị mất khi xóa trình duyệt.
- Có thể cài APK trực tiếp (cần bật “Unknown sources”).

## Icon
Hiện đang dùng icon mặc định. Bạn có thể thay icon trong Android Studio nếu muốn.
