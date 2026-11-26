# Đóng gói Tập Nhà thành APK

Cần cài sẵn: Node.js 18+ và Android Studio.

1. Mở terminal trong thư mục này, chạy: `npm install`
2. Chạy: `npx cap add android`
3. Chạy: `npm run android` (mở Android Studio)
4. Trong Android Studio: Build > Build Bundle(s) / APK(s) > Build APK(s)
5. File nằm ở `android/app/build/outputs/apk/debug/app-debug.apk`. Chép vào điện thoại và cài (bật "Cài từ nguồn không xác định").

Sửa giao diện: chỉnh `www/index.html`, rồi chạy lại `npm run android`.
Lưu ý: phông chữ tải từ Google Fonts, khi không có mạng app dùng phông hệ thống.
