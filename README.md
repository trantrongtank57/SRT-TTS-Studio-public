<p align="center">
  <img src="docs/logo.png" alt="SRT TTS Studio" width="160">
</p>

<h1 align="center">SRT TTS Studio</h1>

<p align="center">
  Phần mềm Windows chuyển <b>phụ đề (SRT) · PDF · Word · TXT</b> thành giọng đọc (MP3),
  kèm bộ công cụ <b>lồng tiếng video, dịch thuật, nhân bản giọng nói và tải truyện</b>.
</p>

---

> ⚠️ **Đây là kho tài liệu công khai (public docs).** Mã nguồn của phần mềm **không** được
> phát hành tại đây. Kho này chỉ chứa **hướng dẫn sử dụng, nhật ký thay đổi và giới thiệu
> tính năng** dành cho người dùng cuối.

## Phần mềm làm được gì?

- **Đọc phụ đề & tài liệu thành audio** — nạp file `.srt` / `.ass` / `.vtt` / PDF / Word / TXT / EPUB
  và tạo file MP3 giọng đọc, canh đúng timeline phụ đề (chống chồng giọng).
- **Nhiều nguồn giọng** — Microsoft Edge TTS (hàng trăm giọng, miễn phí) và các nhà cung cấp
  tiếng Việt (FPT.AI, Vbee, Zalo AI, EverAI, MiniMax).
- **Nhân bản giọng nói (Voice Clone)** — RVC, VoxCPM, VieNeu-TTS, F5-TTS-Vietnamese, OmniVoice.
- **Lồng tiếng video tự động** — 1 click: tách lời (STT) → dịch → đọc → ghép vào video.
  Nhận cả **link YouTube / playlist / kênh**.
- **Dịch phụ đề & tài liệu sang tiếng Việt** — qua Claude / Gemini / OpenAI hoặc chạy **offline**.
- **Phân vai nhiều giọng** — tự nhận diện nhân vật (AI) hoặc theo cao độ giọng gốc.
- **Công cụ video** — OCR sub cứng, Speech-to-Text, nén video, ghép audio, sửa video hỏng.
- **Tải truyện (Webtoon / Manga)** — tải để đọc offline, chuyển định dạng, dịch & lồng chữ Việt.
- **Kiểm tra chất lượng (QC)** — tự phát hiện dòng đọc lỗi (câm/quá dài/thiếu chữ) và tạo lại.

## Điểm mới gần đây

- 📖 **Truyện chữ → Audiobook** — tải truyện chữ, dịch (nếu là truyện nước ngoài) rồi đọc thành audiobook `.m4b` có mục lục chương.
- 🎭 **Tag cảm xúc theo dòng** — thêm `[vui]`/`[giận]`/`[hét]`… vào đầu dòng, Edge TTS tự đổi tốc độ/cao độ; tag không bị đọc thành tiếng.
- 👄 **Khớp khẩu hình (Lip-sync)** — sau khi lồng tiếng, tự chỉnh miệng nhân vật khớp giọng mới (Wav2Lip + tùy chọn làm nét mặt).
- 📀 **Gộp nhiều tập → 1 audiobook** — nối các file final theo thứ tự, mỗi tập thành 1 chương trong `.m4b`.
- 📰 **Đọc bài báo / RSS / Wikipedia → Audio** — dán link là ra file nghe, có mục lục chương cho YouTube.
- ⬇ **Tải phụ đề YouTube** & 🔥 **gắn phụ đề cứng** — tải sub không cần dub, hoặc burn-in phụ đề vào video.
- 📱 **Theo dõi & điều khiển qua LAN** — xem tiến trình, tạm dừng/dừng và tải file thành phẩm từ điện thoại.
- 🎙🔍 **Soát đọc sai bằng STT** — Whisper nghe lại toàn bộ audio, bắt các dòng đọc thiếu/sai.

> Xem đầy đủ trong [Changelog](CHANGELOG.md).

## Tài liệu

- 📖 **[Hướng dẫn sử dụng đầy đủ](HUONG_DAN_SU_DUNG.md)** — từ cài đặt đến các tính năng nâng cao.
- 📝 **[Nhật ký thay đổi (Changelog)](CHANGELOG.md)** — các tính năng và sửa lỗi qua từng bản.

## Yêu cầu hệ thống

- Windows 10 / 11 (64-bit)
- Kết nối Internet lần đầu khởi động
- Một số tính năng nâng cao (voice clone, STT, dịch offline) cần cài thêm môi trường & model —
  xem mục Cài đặt trong [hướng dẫn sử dụng](HUONG_DAN_SU_DUNG.md).

## Cài đặt

Phần mềm được phát hành dưới dạng bộ cài `.msi` và bản chạy trực tiếp `.exe`.
Liên hệ tác giả để nhận bản cài đặt.

---

<p align="center"><sub>Bản quyền © tác giả. Tài liệu này phát hành công khai; phần mềm là sản phẩm độc quyền.</sub></p>
