# PlexGIF

Cắt một đoạn video rồi xuất ra GIF. Ứng dụng macOS.

**[⬇︎ Tải bản mới nhất](https://github.com/mrkunvo/plexgif-releases/releases/latest)** — tải file `.dmg`, kéo PlexGIF vào Applications.

Repo này chỉ chứa **bản phát hành**. Mã nguồn để riêng.

## Dùng thế nào

1. Kéo thả video vào cửa sổ — ProRes 422 HQ, H.264, H.265, MP4, MOV, MXF, MKV…
2. Tua tới chỗ cần, bấm `[` đặt điểm IN, `]` đặt điểm OUT (hoặc kéo hai tay nắm tím trên thanh thời gian).
3. Bật nút lặp để xem đi xem lại đúng đoạn vừa cắt.
4. Cột phải chọn **Cao** (1080p · 25 fps), **Trung bình** (720p · 12,5 fps) hay **Thấp** (480p · 12,5 fps) — cần khác thì chỉnh tay kích thước, FPS, chất lượng.
5. Bấm **Xuất GIF**.

App đã mang sẵn ffmpeg bên trong, không cần cài thêm gì.

## Lần mở đầu tiên

App chưa mua chứng chỉ Apple Developer nên macOS chặn lần đầu. Chuột phải vào PlexGIF trong Applications → **Open** → **Open**. Hoặc chạy một lần trong Terminal:

```bash
xattr -dr com.apple.quarantine /Applications/PlexGIF.app
```

## Yêu cầu

macOS 12 trở lên, Mac chip Apple Silicon (M1/M2/M3/M4).

---

PlexGIF dùng [ffmpeg](https://ffmpeg.org) (GPL v3) để mã hoá GIF, phát hành kèm theo trong app.

Tạo bởi Kun Vo — [mrkunvo.com](https://mrkunvo.com)
