# TurboTV — Repo TEST (chỉ Long dùng, không phải repo chính)

# TurboTV — Repo (Cydia / Sileo / Zebra)

Repo của **TurboTV** — app xem YouTube 1080p cho iPhone/iPad cũ (từ iOS 5 trở lên): iPad mini 1, iPad mini 2, iPhone và iPod touch. Dùng được với **Cydia, Sileo và Zebra** (cùng 1 URL source).

## Thêm source

**Nhập đúng URL này** (có dấu `/` cuối, KHÔNG phải link github.com):

```
https://twosix11d.github.io/turboasi4n-test/
```

- **Cydia:** Sources → Edit → Add, dán URL → Add Source.
- **Sileo:** Sources → dấu `+`, dán URL → Add Source, rồi Refresh.
- **Zebra:** Sources → Add, dán URL → Add.

Rồi vào repo **TurboTV** và cài **TurboTV 1.17.19**.

## Tải trực tiếp file .deb

[debs/com.bun.tubepro_1.17.19_iphoneos-arm.deb](debs/com.bun.tubepro_1.17.19_iphoneos-arm.deb) (3691190 byte, MD5 `4b3a552a7b56095003ee8492ac0a52d8`)

Chép file .deb sang iPad rồi mở bằng Filza → Cài đặt → Respring.

Nếu cài bằng lệnh `dpkg -i` mà icon chưa hiện thì respring 1 lần.

## Phiên bản hiện có

| Gói | Phiên bản | Có gì mới |
|---|---|---|
| com.bun.tubepro (TurboTV) | 1.17.19 | Sửa lỗi đăng nhập Google "Không lấy được mã kích hoạt" (tự thử lại bằng quyền cũ khi Google từ chối quyền mới, tự thử lại khi mạng chập chờn); sửa dock theme kính sáng hết khung trắng vuông quanh dock, giọt nước hết che mất icon tab "Bạn"; AI thêm nhà cung cấp Muse (chọn là tự điền sẵn địa chỉ + model, chỉ cần dán key) và đổi model mặc định Gemini thành gemini-3.8-flash; gửi log GitHub lỗi thì ghi rõ lý do trong file log. |

Các bản trước: 1.17.9 (sửa lỗi cài đặt trên Cydia; icon hiện lại trên màn hình chính sau khi cài); 1.17.8 (sửa nút răng cưa mất tác dụng; gợi ý video liên quan lên ngay dưới video; chống văng trên máy cũ 32-bit); 1.17.5 (sửa lỗi lúc xem được lúc báo lỗi; đăng nhập Google hết im lặng; menu phát, màn Cài đặt riêng, vuốt xuống thu nhỏ video, nhấn giữ phát nhanh 2x, Shorts tải nhanh hơn, mini player thẻ nổi); 1.17.4 (dùng được trên iPhone/iPod touch); 1.17.3 (sửa lỗi lúc xem được lúc báo lỗi; sửa phát nền im khi bấm Home); 1.17.2 (Back thu nhỏ mini player; lặp lại video; bấm Home tự vào hình trong hình); 1.17.1 (thêm mục ủng hộ); 1.17 (live 1080p, mở trang kênh, hẹn giờ tắt video, 10 ngôn ngữ).

## Tính năng chính

- Xem YouTube 1080p (tự hạ chất lượng khi mạng yếu)
- Live 1080p, mở trang kênh, Shorts đầy đủ nội dung
- Mini player trong app + hình trong hình (PiP, iOS 9+)
- Phát âm thanh dưới nền, hẹn giờ tắt 15–90 phút
- Lặp lại video, lịch sử xem (mở lại đúng vị trí)
- 4 theme, 10 ngôn ngữ, đăng nhập Google

## Ủng hộ / Donate

TurboTV là app miễn phí. Nếu thấy hữu ích, ủng hộ nhà phát triển qua PayPal: [paypal.me/turboasi4n](https://paypal.me/turboasi4n) — hoặc quét mã VietQR:

![Mã VietQR](https://twosix11d.github.io/turboasi4n-test/vietqr.png)

## English summary

TurboTV is a YouTube app for old iPhones and iPads (iOS 5 and up) — 1080p playback, mini player, picture-in-picture, background audio, sleep timer, Google sign-in, 10 languages. Add this source in Cydia, Sileo or Zebra: `https://twosix11d.github.io/turboasi4n-test/` — then install TurboTV 1.17.19. Free app; donations via [paypal.me/turboasi4n](https://paypal.me/turboasi4n) or the VietQR code above.
