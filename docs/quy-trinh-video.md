# Kho truyện E-WIT thành video luyện shadowing tiếng Anh

Tài liệu sống: ghi mọi điều đã chốt và câu hỏi còn mở. Cập nhật mỗi khi có quyết định mới.

## Mục tiêu

- Kho khoảng 500 truyện nội tâm tiếng Việt, viết lại bằng tiếng Anh tự nhiên như người bản xứ.
- Mỗi truyện thành một video: chia câu, có IPA, nền trơn, logo E-WIT nhỏ ở góc dưới, audio ElevenLabs.
- Người xem dùng video để luyện shadowing (nghe và nói đuổi theo).
- Logo và câu khẩu hiệu đầu/cuối video phải thay được với chi phí thấp (tách bộ nhận diện khỏi nội dung).

## Dữ liệu

| Mục | Vị trí |
|---|---|
| File truyện gốc (Google Doc) | 1RScN4Yah56dYYYdwziHpiDQRPY4NsBFgGxhqBQuYa1E |
| Google Sheet "Kho truyện nội tâm - danh mục và bộ vai giọng" | 1NdOus5DQqDXw6H3SJogxYyNgHw1dOrgkdAiNRAKzRtk (trong thư mục Tài liệu học tập) |

Các tab của Sheet:

| Tab | Nội dung |
|---|---|
| Danh mục truyện | Mã, tên, tên gốc, chủ đề, kiểu truyện, số từ (công thức), nhân vật và vai, vai có giọng, cần lưu ý, ghi chú làm sạch |
| Nội dung truyện | Toàn văn tiếng Việt đã làm sạch; bình luận ngoài truyện ở cột riêng (không đưa vào video) |
| Đối chiếu Anh - Việt | Tên tiếng Anh, Bản nháp (Claude), Dung edit, Bản tiếng Anh chính thức, truyện tiếng Việt (công thức), số câu, trạng thái |
| Quy ước văn phong | Các quy ước viết tiếng Anh, có ví dụ trước/sau |
| Bản tiếng Anh | Mỗi dòng một câu của bản chính thức: mã, câu số, vai, câu, IPA, ghi chú |
| Bộ vai giọng | V1 đến V8, mô tả, dùng cho, mã giọng ElevenLabs, thông số, số truyện dùng, đoạn thử giọng |
| Thống kê | Tổng truyện, số từ, số truyện theo kiểu |

## Đã chốt

### Làm sạch dữ liệu (mẫu 60 truyện)

- Còn 59 truyện sau khi gộp hoặc bỏ bản trùng; mã mới NT001 đến NT059 theo thứ tự file gốc.
- Tách truyện lồng nhau (NT015, NT039, NT045, NT047); tách bình luận ra cột riêng.
- Bài học rút ra không đưa vào video (vẫn còn trong file gốc).
- Tên truyện làm rõ khi cần, tên gốc giữ ở cột riêng.

### Bộ giọng: giữ 8 vai

| Mã | Vai |
|---|---|
| V1 | Người kể chuyện E-WIT (giọng thương hiệu, có trong mọi truyện) |
| V2 | Bậc trí tuệ nam |
| V3 | Bậc trí tuệ nữ / người già |
| V4 | Đàn ông trưởng thành |
| V5 | Phụ nữ trưởng thành |
| V6 | Thanh niên |
| V7 | Trẻ em |
| V8 | Quyền uy |

Quy tắc gán vai: con vật mượn vai người theo tính cách; tối đa 3 vai có giọng ngoài V1; không mô phỏng giọng người thật; lời thần linh có thể chuyển thành lời kể gián tiếp; mỗi mã giọng ElevenLabs gắn cố định với một vai.

### Truyện nhạy cảm

- NT051, NT052 (định kiến dân tộc): bản tiếng Anh viết lại trung tính, bỏ quốc tịch; bản tiếng Việt giữ nguyên để đối chiếu.
- NT040 (cốt truyện phim, bạo lực): đề xuất không làm video.
- Các truyện khác có ghi chú ở cột "Cần lưu ý".

### Quy trình viết bản tiếng Anh

1. Claude viết bản nháp; trạng thái "Chờ Dung edit".
2. Dung sửa ở cột "Dung edit".
3. Claude viết bản chính thức theo góp ý của Dung và tab "Quy ước văn phong"; trạng thái "Chờ chốt chính thức".
4. Người dùng đổi trạng thái thành "Chính thức". Chỉ bản chính thức được tách câu, gắn vai, làm IPA ở tab "Bản tiếng Anh".

Bản của Dung dùng để học văn phong; Claude phải tự viết như người bản xứ, tên truyện đặt theo cách người bản xứ hiểu ngay.

### Quy ước văn phong (tóm tắt, bản đầy đủ ở tab Sheet)

- Viết thành đoạn liền mạch; mỗi lượt thoại một đoạn; lời một người nói liên tiếp gộp một cặp ngoặc kép.
- Giữ đủ sắc thái tiếng Việt và câu hỏi tu từ của bản gốc.
- Thì tiếp diễn cho hành động đang diễn ra; lời thoại dùng dạng rút gọn (can't, we've).
- Chọn cách nói tự nhiên, không dịch từng chữ; làm rõ logic khi bản Việt ngầm hiểu.
- Tuổi viết bằng số; hai người con dùng older/younger.
- Thống nhất tiếng Anh Mỹ: chính tả, từ vựng, IPA.

### Truyện mẫu đã có bản chính thức (chờ chốt)

NT005 The Wise Old Owl, NT055 Through the Train Window, NT058 The Old Woman Who Always Cried.

### ElevenLabs

- Thử giọng trên gói Free (đủ credit cho 8 vai x 3 ứng viên).
- Khi đăng video: gói Starter (có quyền thương mại).
- Khi chạy hàng loạt: Creator (khoảng 5 tháng cho 500 truyện) hoặc Pro một tháng rồi hạ gói. Kiểm tra lại giá ở elevenlabs.io/pricing trước khi mua.
- Ước tính khoảng 1.000 đến 1.100 credit mỗi truyện (suy luận, chưa đo thực tế).
- API key để trong secrets của môi trường, không dán vào chat.

## Câu hỏi còn mở

1. Trình độ người học mục tiêu: A2-B1 hay B1-B2? Quyết định độ dài câu và cách chọn từ.
2. Thêm 3 cột cho shadowing ở tab "Bản tiếng Anh" và làm thử trên 3 truyện mẫu:
   - Ngắt nhịp và nhấn (ví dụ: "The MORE he SAW, / the LESS he SPOKE.")
   - IPA nối âm: dạng yếu (and /ən/, to /tə/, can /kən/), nối âm, flap t. IPA hiện tại là IPA từng từ riêng lẻ, chưa phù hợp shadowing.
   - Ngữ điệu và cảm xúc từng câu (cũng dùng để điều chỉnh ElevenLabs).
3. Câu dài trên khoảng 15 từ có tách đôi không (ví dụ NT058 câu 8).
4. Cấu trúc mỗi câu trong video: nghe tự nhiên, shadow ở tốc độ chậm, khoảng lặng để tự nói lại.
5. Cuối video có tổng kết 2-3 mẫu câu dùng lại được không.
6. Thứ tự viết các truyện còn lại và số truyện mỗi lượt (đề xuất 5-8).
7. Bộ nhận diện thương hiệu: logo PNG nền trong, audio khẩu hiệu đầu/cuối, font, màu nền; lưu một thư mục Drive riêng.
8. IPA nên lấy từ từ điển phát âm thay vì viết tay (cài thư viện từ bên ngoài đã bị hệ thống chặn; cần người dùng cho phép).

## Bước tiếp theo theo kế hoạch

1. Người dùng chọn 8 giọng trên ElevenLabs, điền mã vào tab "Bộ vai giọng".
2. Chốt bản chính thức 3 truyện mẫu và các cột shadowing.
3. Chuẩn bị bộ nhận diện thương hiệu.
4. Viết skill truyện thành video, chạy thử 3 truyện mẫu rồi mới chạy cả lô.
