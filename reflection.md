# Individual reflection - Lưu Thị Ngọc Quỳnh (2A202600122)

## 1. Role
Phụ trách các phần canvas, failure modes và dữ liệu của nhóm. Các output em trực tiếp tham gia hoàn thiện gồm slide, `SPEC.md` và `Quy tắc bảo vệ quyền lợi người tiêu dùng.txt`.

## 2. Đóng góp cụ thể
- Xây dựng canvas để làm rõ bài toán, nhóm người dùng, pain points và giá trị mà sản phẩm cần tạo ra.
- Tham gia viết và hoàn thiện `SPEC.md`, đặc biệt ở phần mô tả bài toán, phạm vi và các giả định quan trọng.
- Phân tích failure modes của chatbot để nhóm lường trước các trường hợp trả lời sai, trả lời quá chung chung hoặc gây hiểu nhầm cho người dùng.
- Thu thập, chọn lọc và tổng hợp dữ liệu phục vụ cho agent; trong đó có file `Quy tắc bảo vệ quyền lợi người tiêu dùng.txt` làm nguồn tham chiếu quan trọng cho phần trả lời liên quan đến quyền lợi người dùng.
- Hỗ trợ làm slide để trình bày rõ logic bài toán, hướng giải quyết và phần việc của nhóm trong buổi demo.

## 3. SPEC mạnh/yếu
- Mạnh nhất: phần failure modes giúp nhóm nhìn rõ các rủi ro thực tế khi triển khai chatbot, từ đó không chỉ nghĩ đến việc "chatbot trả lời được" mà còn nghĩ đến việc "chatbot trả lời có an toàn, đúng và hữu ích hay không".
- Mạnh nữa là phần dữ liệu giúp sản phẩm có nền tảng rõ ràng hơn, tránh việc câu trả lời hoàn toàn dựa trên suy đoán của model.
- Yếu nhất: canvas ban đầu vẫn còn bao quát nhiều nhu cầu nên phạm vi bài toán hơi rộng. Khi scope chưa đủ hẹp thì chatbot dễ trả lời chung chung và khó làm nổi bật một tình huống sử dụng thật sự sắc nét.

## 4. Đóng góp khác
- Chủ động nối phần canvas với phần slide để nội dung trình bày nhất quán hơn giữa bài toán, giải pháp và dữ liệu.
- Sắp xếp lại thông tin thu thập được theo hướng dễ đọc, dễ tra cứu để các bạn phụ trách logic chatbot và ingest dữ liệu có thể dùng thuận lợi hơn.
- Trong quá trình làm SPEC, em cũng góp ý để phần rủi ro và giới hạn của sản phẩm được thể hiện rõ hơn thay vì chỉ tập trung vào tính năng.

## 5. Điều học được
Qua phần việc của mình, em học được rằng chất lượng của một chatbot không chỉ đến từ model mà đến rất nhiều từ cách xác định bài toán và chuẩn bị dữ liệu. Nếu canvas chưa rõ thì sản phẩm dễ bị ôm đồm; nếu dữ liệu chưa sạch và chưa đúng trọng tâm thì chatbot rất dễ trả lời lan man hoặc thiếu căn cứ. Phần failure modes cũng giúp em hiểu rằng làm AI product phải luôn nghĩ trước các tình huống xấu, không chỉ nghĩ đến case đẹp khi demo.

## 6. Nếu làm lại
Nếu làm lại, em sẽ chốt scope hẹp hơn ngay từ đầu và tách rõ ưu tiên của từng nhóm người dùng để canvas sắc nét hơn. Em cũng sẽ chuẩn hóa dữ liệu sớm hơn, gắn nhãn theo từng chủ đề ngay lúc thu thập để các bước ingest và retrieval về sau đỡ mất thời gian chỉnh lại. Ngoài ra, em muốn chuyển các failure modes thành test cases cụ thể sớm hơn để nhóm có thể kiểm tra chất lượng chatbot ngay trong lúc phát triển.

## 7. AI giúp gì / AI sai gì
- **Giúp:** AI hỗ trợ em tóm tắt tài liệu nhanh hơn, gợi ý thêm các failure modes có thể xảy ra và giúp diễn đạt ý trong slide/SPEC mạch lạc hơn.
- **Sai/mislead:** với các nội dung liên quan đến quy định hoặc quyền lợi người dùng, AI đôi khi tạo ra câu chữ nghe hợp lý nhưng không bám sát nguồn gốc tài liệu. Vì vậy em rút ra rằng AI rất hữu ích để brainstorm và hỗ trợ viết, nhưng các phần liên quan đến dữ liệu và quy tắc vẫn phải đối chiếu lại với tài liệu gốc.
