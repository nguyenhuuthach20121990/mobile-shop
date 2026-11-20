Trò chuyện với Gemini
trong visual studio code, phím tắt dùng để tạo ghi chú và phím tắt để code tự động sắp xếp gọn gàng

Trong Visual Studio Code (VS Code), hai phím tắt này cực kỳ hữu dụng khi lập trình:

1. Phím tắt tạo / bật-tắt ghi chú (Comment)
   Ghi chú / bỏ ghi chú 1 dòng hoặc nhiều dòng đang chọn:

Windows / Linux: Ctrl + /

macOS: Cmd + /

Ghi chú theo khối (Block comment - ví dụ /_ ... _/):

Windows / Linux: Shift + Alt + A

macOS: Shift + Option + A

2. Phím tắt tự động sắp xếp / định dạng code gọn gàng (Format Document)
   Định dạng toàn bộ file hiện tại:

Windows / Linux: Shift + Alt + F

macOS: Shift + Option + F

Định dạng chỉ phần code đang bôi đen (Format Selection):

Windows / Linux: Ctrl + K rồi nhấn tiếp Ctrl + F (giữ Ctrl, bấm K, thả ra rồi bấm F)

macOS: Cmd + K rồi nhấn tiếp Cmd + F

Mẹo nhỏ để dùng mượt hơn
Chưa có trình định dạng (Formatter)? Khi bấm Shift + Alt + F lần đầu trên một loại ngôn ngữ (như Python, HTML, JS/TS, C++...), VS Code có thể hỏi chọn formatter hoặc báo chưa cài. Bạn có thể cài thêm extension như Prettier (cho JS/TS/HTML/CSS) hoặc Black / Ruff (cho Python) rồi đặt làm mặc định.

Tự động sắp xếp mỗi khi lưu: Mở Settings (Ctrl + , hoặc Cmd + ,), tìm Format On Save và bật dấu tích — mỗi lần nhấn Ctrl + S / Cmd + S, code sẽ tự căn chỉnh ngay.

Không nhớ phím tắt? Nhấn Ctrl + Shift + P (hoặc Cmd + Shift + P), gõ Format Document hoặc Toggle Line Comment để chạy trực tiếp.

các extentions cần thiết để cài trong visual studio code

Để sử dụng Visual Studio Code (VS Code) hiệu quả và mượt mà nhất, bạn không nên cài quá nhiều extension gây nặng máy mà chỉ cần tập trung vào các nhóm công cụ cốt lõi dưới đây:  
Syncfusion

1. Nhóm làm sạch & định dạng code (Bắt buộc nên có)
   Prettier - Code formatter: Tự động căn chỉnh lề, dấu ngoặc, khoảng trắng cực kỳ gọn gàng khi nhấn Shift + Alt + F hoặc khi lưu file. Hỗ trợ rất tốt cho JavaScript, TypeScript, HTML, CSS, JSON, Markdown.  
   Stackademic

- 1

ESLint: Tự động phát hiện lỗi cú pháp, biến chưa khai báo hoặc các quy tắc viết code chưa chuẩn trong JavaScript/TypeScript ngay khi bạn đang gõ.  
Rockstar Developer University

- 1

Error Lens: Hiển thị thông báo lỗi và cảnh báo trực tiếp ngay bên cạnh dòng code bị lỗi (thay vì chỉ gạch chân mờ mờ), giúp bạn nhận ra lỗi ngay lập tức.  
Rockstar Developer University

- 1

2. Nhóm tăng tốc độ gõ & giao diện trực quan
   Path Intellisense: Tự động gợi ý đường dẫn file và thư mục khi bạn gõ lệnh import hoặc nhúng ảnh/script, tránh gõ sai tên file.  
   John kilmister

Auto Rename Tag: Khi sửa tên thẻ mở trong HTML/XML/JSX (ví dụ sửa <div> thành <section>), thẻ đóng </div> sẽ tự động đổi theo.

Material Icon Theme: Thay đổi toàn bộ icon của thư mục và các loại file trong thanh Explorer trở nên trực quan, dễ phân biệt bằng màu sắc.

Indent-Rainbow: Tô màu nhẹ các cột thụt đầu dòng (tab/space), giúp dễ nhìn cấu trúc khối lệnh lồng nhau hơn.  
John kilmister

Code Spell Checker: Kiểm tra lỗi chính tả tiếng Anh cho tên biến, tên hàm và phần ghi chú (comment), hỗ trợ nhận diện cả kiểu viết camelCase hay snake_case.  
John kilmister

- 1

3. Nhóm quản lý Git & hỗ trợ AI
   GitLens: Mở rộng sức mạnh cho Git ngay trong VS Code — cho phép xem ai đã sửa dòng code nào, sửa vào lúc nào (Git Blame), và xem lịch sử thay đổi của từng file cực kỳ trực quan.  
   Rockstar Developer University

- 1

GitHub Copilot (hoặc Continue / Gemini Code Assist): Trợ lý AI gợi ý hoàn thành code tự động theo ngữ cảnh, giải thích đoạn code phức tạp hoặc hỗ trợ viết nhanh các đoạn mã lặp lại.  
Rockstar Developer University

4. Nhóm dành riêng cho lập trình Web & API
   Live Server: Tạo một máy chủ ảo chạy trên trình duyệt; mỗi khi bạn lưu file HTML/CSS/JS, trình duyệt sẽ tự động tải lại trang ngay lập tức.  
   Stackademic

Thunder Client (hoặc REST Client): Công cụ test API (gửi request GET, POST, PUT, DELETE...) trực tiếp bên trong VS Code mà không cần mở ứng dụng ngoài như Postman.  
Rockstar Developer University

- 1

5. Nhóm tiện ích mở rộng theo nhu cầu
   Rainbow CSV: Tô màu từng cột dữ liệu trong file .csv theo màu sắc khác nhau, giúp đọc dữ liệu dạng bảng trên VS Code dễ dàng như mở bảng tính.  
   John kilmister

- 1

Language Pack (Tiếng Việt): Nếu muốn chuyển toàn bộ giao diện menu của VS Code sang tiếng Việt, bạn có thể cài gói Vietnamese Language Pack for Visual Studio Code.

Mẹo nhỏ khi cài đặt:
Nếu bạn lập trình ngôn ngữ đặc thù (như Python, C/C++, Java, C#, PHP...), hãy gõ tên ngôn ngữ đó vào ô tìm kiếm Extensions (Ctrl + Shift + X) và cài gói extension chính chủ do Microsoft (hoặc tổ chức uy tín đứng đầu danh sách) phát hành để có đầy đủ tính năng gợi ý code và gỡ lỗi (Debug).  
Visual Studio

cấu trúc của 1 trang web gồm những gì, liệt kê các thẻ chính

Cấu trúc của một trang web gồm 2 lớp chính:

Về mặt kỹ thuật & dữ liệu (HTML): Khung tài liệu gồm khai báo <!DOCTYPE html>, thẻ gốc <html>, phần khai báo thông tin <head> (không hiển thị trực tiếp nội dung trang) và phần thân <body> (chứa toàn bộ giao diện và nội dung hiển thị cho người dùng).

Về mặt bố cục & ngữ nghĩa (Semantic HTML): Cách chia các khu vực chức năng trên trang như phần đầu trang, thanh điều hướng, nội dung chính, cột phụ và chân trang để trình duyệt, công cụ tìm kiếm (SEO) và trình đọc màn hình hiểu rõ ý nghĩa từng khối.

Bố cục ngữ nghĩa chuẩn trong HTML, do AI tạo
Bố cục ngữ nghĩa chuẩn trong HTML. Nguồn: Piscine / Getty Images

1. Khung xương cơ bản của một file HTML
   Mọi trang web chuẩn đều bắt đầu bằng cấu trúc nền tảng sau:

HTML

<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tiêu đề trang web</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Toàn bộ nội dung hiển thị nằm ở đây -->
  <script src="app.js"></script>
</body>
</html>
<!DOCTYPE html>: Khai báo chuẩn tài liệu HTML5 để trình duyệt hiển thị đúng chế độ chuẩn.

<html>: Thẻ bao trùm toàn bộ tài liệu HTML (thường có thuộc tính lang="vi" để xác định ngôn ngữ).

<head>: Chứa thông tin cấu hình và tài nguyên đi kèm:

<meta>: Khai báo bảng mã (charset="UTF-8" để hỗ trợ tiếng Việt có dấu), cấu hình hiển thị trên điện thoại (viewport), mô tả SEO...

<title>: Tên trang hiển thị trên tab trình duyệt và kết quả tìm kiếm.

<link>: Liên kết file CSS định dạng giao diện hoặc favicon.

<script>: Nhúng hoặc liên kết mã JavaScript xử lý tương tác (có thể đặt ở <head> với defer hoặc cuối <body>).

<body>: Chứa toàn bộ phần nội dung mà người dùng nhìn thấy và tương tác.

2. Các thẻ bố cục ngữ nghĩa (Semantic Layout) trong <body>
Thay vì dùng tràn lan <div>, HTML hiện đại ưu tiên dùng các thẻ có ngữ nghĩa rõ ràng:

Thẻ	Vai trò trên trang web
<header>	Phần đầu trang hoặc đầu một khối nội dung (thường chứa logo, tên thương hiệu, ô tìm kiếm hoặc tiêu đề giới thiệu).
<nav>	Thanh điều hướng chứa các liên kết menu chính dẫn tới các mục hoặc trang khác.
<main>	Nội dung cốt lõi, duy nhất của trang (mỗi trang chỉ nên có một thẻ <main>).
<section>	Nhóm các nội dung theo từng chủ đề hoặc khu vực chức năng (ví dụ: phần giới thiệu, bảng giá, danh sách tính năng).
<article>	Một đơn vị nội dung độc lập, có thể tách rời và tái sử dụng (ví dụ: một bài viết tin tức, bài blog, thẻ sản phẩm, bình luận).
<aside>	Nội dung phụ hoặc liên quan bổ trợ (ví dụ: thanh bên sidebar, bài viết liên quan, quảng cáo).
<footer>	Phần chân trang (thường chứa thông tin bản quyền, liên hệ, chính sách, sơ đồ trang).
<div> / <span>	Thẻ bao bọc chung không mang ngữ nghĩa riêng; <div> là thẻ khối (block), <span> là thẻ nội tuyến (inline). Dùng khi cần gom nhóm để styling/scripting mà không có thẻ ngữ nghĩa phù hợp.
3. Các thẻ nội dung & tương tác phổ biến
Bên trong các khối bố cục trên, nội dung chi tiết được tạo nên từ các nhóm thẻ chính sau:

Tiêu đề & văn bản:

<h1> đến <h6>: Hệ thống tiêu đề phân cấp (<h1> cho tiêu đề chính quan trọng nhất của trang).

<p>: Đoạn văn bản.

<a>: Liên kết chuyển trang hoặc nhảy tới mục (href="...").

<strong> / <em>: Nhấn mạnh nội dung quan trọng (<strong>) hoặc nhấn mạnh ngữ điệu (<em>).

Danh sách & bảng biểu:

<ul> / <ol> + <li>: Danh sách không thứ tự (<ul>) hoặc có thứ tự (<ol>), mỗi mục là một <li>.

<table>, <thead>, <tbody>, <tr>, <th>, <td>: Dựng bảng dữ liệu (hàng <tr>, ô tiêu đề <th>, ô dữ liệu <td>).

Hình ảnh & đa phương tiện:

<img>: Chèn hình ảnh (src là đường dẫn ảnh, alt là văn bản thay thế mô tả ảnh).

<figure> & <figcaption>: Gom nhóm hình ảnh/minh họa kèm chú thích.

<video> / <audio>: Nhúng video hoặc âm thanh.

Biểu mẫu & nút bấm:

<form>: Vùng chứa biểu mẫu nhập dữ liệu (đăng nhập, đăng ký, tìm kiếm, gửi liên hệ).

<label>, <input>, <textarea>, <select>, <button>: Ô nhập liệu, ô văn bản dài, danh sách chọn và nút thao tác.

cách tạo ghi chú trong body html

Trong HTML (kể cả bên trong <body>), bạn tạo ghi chú bằng cú pháp <!-- ... -->. Trình duyệt sẽ bỏ qua toàn bộ nội dung nằm giữa <!-- và --> khi hiển thị trang web, nhưng người dùng vẫn có thể xem được khi mở View Page Source hoặc DevTools.

1. Cú pháp cơ bản
Ghi chú trên một dòng:

HTML
<body>
  <!-- Phần đầu trang chứa tiêu đề chính -->
  <h1>Xin chào</h1>
</body>
Ghi chú trên nhiều dòng:

HTML
<body>
  <!--
    Khu vực giới thiệu sản phẩm:
    - Hiển thị ảnh đại diện
    - Nút mua ngay
  -->
  <section class="hero">
    <p>Nội dung hiển thị</p>
  </section>
</body>
Ẩn tạm thời một đoạn mã HTML (để kiểm tra hoặc giữ lại dùng sau):

HTML
<body>
  <p>Đoạn này vẫn hiển thị</p>
  <!--
  <button type="button">Nút tạm ẩn</button>
  -->
</body>
2. Các lưu ý quan trọng khi dùng ghi chú HTML
Không lồng ghi chú vào nhau: Bạn không thể đặt một cặp <!-- ... --> bên trong một cặp <!-- ... --> khác vì trình duyệt sẽ đóng ghi chú ở dấu --> đầu tiên gặp phải, làm lộ mã ra trang web.

Tránh viết chuỗi -- bên trong nội dung ghi chú: Theo chuẩn HTML, chuỗi hai dấu gạch ngang liên tiếp -- bên trong comment dễ gây lỗi phân tích cú pháp trên một số trình duyệt/công cụ.

Không ghi thông tin nhạy cảm: Đừng để mật khẩu, API key, token, đường dẫn nội bộ nhạy cảm hay ghi chú nghiệp vụ bí mật trong HTML comment vì ai cũng có thể đọc được mã nguồn phía client.

Ghi chú bên trong <script> hoặc <style>: Nếu bạn viết code JS hoặc CSS trực tiếp trong trang, hãy dùng cú pháp của ngôn ngữ đó (// hoặc /* ... */), không dùng <!-- ... -->.

3. Cách tạo nhanh trên VS Code
Bôi đen đoạn code trong <body> và nhấn Ctrl + / (Windows/Linux) hoặc Cmd + / (macOS) để tự động thêm hoặc gỡ <!-- ... -->.

position: relative

Trong CSS, position: relative đặt phần tử theo luồng tài liệu bình thường (normal flow) rồi cho phép dịch chuyển vị trí hiển thị của nó tương đối so với chính vị trí ban đầu thông qua các thuộc tính top, right, bottom, left (cũng như inset).

Điểm mấu chốt cần nhớ: dù phần tử có bị dịch chuyển đi đâu, "chỗ ngồi" ban đầu của nó trên trang vẫn được giữ nguyên, nên các phần tử xung quanh không bị đẩy hay xáo trộn.

1. Cách hoạt động cốt lõi
Vị trí ban đầu vẫn giữ chỗ: Nếu một hộp văn bản nằm ở vị trí A và bạn đặt position: relative; top: 20px; left: 30px;, hộp sẽ hiển thị lệch xuống dưới 20px và sang phải 30px so với vị trí A, nhưng khoảng trống tại A vẫn tồn tại như thể hộp chưa hề di chuyển.

Ý nghĩa của top / left khi dùng relative:

top: 20px; đẩy phần tử xuống dưới 20px (tính từ cạnh trên vị trí gốc).

left: 30px; đẩy phần tử sang phải 30px (tính từ cạnh trái vị trí gốc).

Dùng giá trị âm (ví dụ top: -10px;) sẽ đẩy ngược lại lên trên.

Mở khóa z-index: Phần tử có position: relative (khác static) có thể dùng z-index để điều chỉnh thứ tự xếp chồng trước/sau mà không cần đổi bố cục chính.

2. Hai tình huống sử dụng phổ biến nhất
a. Dịch chuyển nhẹ một phần tử mà không làm lệch layout xung quanh
CSS
.badge-icon {
  position: relative;
  top: -2px;
  left: 4px;
}
Thường dùng khi căn chỉnh tinh tế icon đi kèm chữ, huy hiệu nhỏ hoặc hiệu ứng nhích nhẹ khi hover.

b. Làm "mốc neo" (containing block) cho position: absolute bên trong
Đây là cách dùng phổ biến nhất trong thực tế: đặt position: relative cho phần tử cha để các phần tử con dùng position: absolute căn tọa độ theo đúng chiếc hộp cha đó, thay vì căn theo <body> hay toàn màn hình.

CSS
.card {
  position: relative; /* Làm mốc tọa độ cho phần tử con */
  padding: 16px;
}

.card-tag {
  position: absolute;
  top: 8px;
  right: 8px; /* Nằm ở góc trên bên phải của .card */
}
3. Lưu ý thực tế
Không dùng để làm bố cục lớn (layout trang): Muốn chia cột, căn giữa, xếp hàng/lưới nên dùng Flexbox hoặc CSS Grid; position: relative chỉ hợp cho tinh chỉnh cục bộ hoặc làm mốc tọa độ.

Dịch chuyển bằng transform: translate(...) thường mượt hơn cho animation: Nếu chỉ cần dịch chuyển hình ảnh/hộp khi chạy hiệu ứng chuyển động (animation/transition), transform: translate(x, y) thường tối ưu hơn top/left vì chạy trên GPU và không gây tính toán lại layout.

các thuộc tính thường dùng trong positon absolute

Khi một phần tử đã có position: absolute, nó sẽ thoát khỏi luồng bố cục thông thường (không giữ chỗ trống ban đầu) và tự định vị theo phần tử tổ tiên gần nhất có position khác static (thường là thẻ cha có position: relative), hoặc theo khung nhìn gốc nếu không có tổ tiên định vị nào.

Để điều khiển vị trí, kích thước, lớp xếp chồng và độ mượt khi dịch chuyển của phần tử position: absolute, bạn sẽ dùng thường xuyên nhóm thuộc tính dưới đây:

1. Nhóm thuộc tính căn tọa độ: top, right, bottom, left và inset
Đây là các thuộc tính cốt lõi để "ghim" phần tử vào các cạnh của hộp chứa mốc:

top, right, bottom, left: Xác định khoảng cách tính từ cạnh tương ứng của hộp mốc vào phần tử.

Có thể dùng đơn vị px, %, rem, hoặc giá trị âm (ví dụ top: -8px; để đẩy tràn ra ngoài mép trên).

Ghim vào góc: Dùng top: 0; right: 0; cho góc trên phải, bottom: 0; left: 0; cho góc dưới trái.

Kéo giãn phủ kín hộp mốc: Đặt cả 4 cạnh bằng 0 (top: 0; right: 0; bottom: 0; left: 0;) khi phần tử không tự đặt width/height cố định.

inset (viết tắt hiện đại cho cả 4 cạnh):

inset: 0; tương đương cả 4 cạnh đều là 0.

inset: 10px 20px; tương đương trên/dưới 10px, trái/phải 20px.

inset: 8px auto auto 12px; tương đương top: 8px; right: auto; bottom: auto; left: 12px;.

CSS
.card {
  position: relative;
}

.badge-new {
  position: absolute;
  top: 12px;
  right: 12px; /* Đặt huy hiệu ở góc trên bên phải thẻ */
}

.overlay-backdrop {
  position: absolute;
  inset: 0; /* Phủ kín toàn bộ kích thước của .card */
}
2. Nhóm thuộc tính căn giữa & tinh chỉnh dịch chuyển: transform
Vì top: 50%; left: 50%; mới chỉ đưa góc trên bên trái của phần tử ra đúng tâm hộp mốc, người ta thường kết hợp transform: translate(...) để đưa tâm của chính phần tử về đúng tâm:

Căn giữa tuyệt đối (cả ngang lẫn dọc):

CSS
.center-box {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
Căn giữa theo chiều ngang hoặc chiều dọc: Chỉ giữ translateX(-50%) (khi có left: 50%) hoặc translateY(-50%) (khi có top: 50%).

Lợi thế hiệu năng: Dịch chuyển bằng transform mượt hơn khi làm transition hoặc hover so với đổi top/left liên tục.

3. Nhóm thuộc tính lớp xếp chồng & độ hiển thị: z-index, opacity, pointer-events
Phần tử position: absolute dễ đè lên các nội dung khác nên các thuộc tính sau rất hay đi kèm:

z-index: Điều chỉnh thứ tự xếp chồng theo trục Z (số lớn hơn nằm trên). Lưu ý: z-index chỉ có tác dụng trên phần tử có position khác static (như relative, absolute, fixed, sticky).

opacity: Chỉnh độ trong suốt (từ 0 trong suốt hoàn toàn đến 1 rõ nét), thường dùng cho lớp phủ mờ (overlay), tooltip hoặc hiệu ứng hiện dần.

pointer-events: Điều khiển chuột/chạm có tương tác với phần tử hay "xuyên qua" nó xuống lớp dưới. Dùng pointer-events: none; khi làm lớp chữ/nhãn trang trí đè lên ảnh/nút để tránh chặn click của người dùng.

CSS
.caption-overlay {
  position: absolute;
  inset: 0;
  z-index: 2;
  opacity: 0.9;
  pointer-events: none; /* Không cản trở click vào vùng bên dưới */
}
4. Nhóm thuộc tính kiểm soát kích thước & tràn nội dung: width, height, max-width, overflow
Kích thước (width, height, max-width, max-height): Khi dùng position: absolute, phần tử không còn tự co giãn theo chiều ngang dòng như khối bình thường mà co theo nội dung bên trong (trừ khi bạn đặt width hoặc ép cả hai cạnh đối diện như left: 0; right: 0;). Đặt max-width giúp dropdown, popover hoặc tooltip không bị tràn quá rộng trên màn hình nhỏ.

overflow: Kiểm soát nội dung tràn ra khỏi hộp mốc (thường đặt overflow: hidden; ở thẻ cha position: relative nếu muốn cắt phần tử con position: absolute bị lòi ra ngoài viền bo tròn).

Bảng tóm tắt nhanh
Thuộc tính	Công dụng chính khi đi với position: absolute
top / right / bottom / left / inset	Xác định tọa độ neo theo các cạnh của hộp mốc
transform: translate(...)	Căn tâm chính xác (-50%, -50%) hoặc dịch chuyển mượt khi hover/animation
z-index	Quyết định phần tử nằm trên hay dưới các lớp khác
pointer-events: none	Cho phép click/chạm xuyên qua lớp phủ đè lên phía trên
width / max-width / height	Định kích thước rõ ràng (vì phần tử absolute không tự giãn full-width mặc định)
cách đẩy 2 thẻ ra 2 bên lề trái và lề phải trang web

Để đẩy hai thẻ (hoặc hai phần tử con) sát về lề trái và lề phải trên cùng một hàng, cách chuẩn, gọn và dễ kiểm soát nhất trong CSS hiện đại là dùng Flexbox (display: flex; justify-content: space-between;).

Dưới đây là các cách phổ biến tùy theo cấu trúc bố cục của bạn:

1. Cách chuẩn và dễ dùng nhất: Flexbox (space-between)
Đặt display: flex và justify-content: space-between cho thẻ cha bao bọc hai thẻ con. Phần tử đầu tiên sẽ sát lề trái, phần tử thứ hai sẽ sát lề phải.

HTML
<div class="row">
  <div class="box">Thẻ bên trái</div>
  <div class="box">Thẻ bên phải</div>
</div>
CSS
.row {
  display: flex;
  justify-content: space-between; /* Đẩy 2 phần tử ra 2 đầu trái - phải */
  align-items: center;           /* Căn giữa theo chiều dọc (tùy chọn) */
  width: 100%;
}
Ưu điểm: Tự co giãn theo kích thước màn hình, không làm vỡ luồng bố cục, dễ căn giữa theo chiều dọc bằng align-items: center.

2. Dùng margin-left: auto trên thẻ thứ hai (linh hoạt khi có nhiều phần tử)
Khi dùng display: flex, nếu đặt margin-left: auto; cho thẻ thứ hai, trình duyệt sẽ dồn toàn bộ khoảng trống dư vào lề trái của thẻ đó, đẩy nó sát sang phải.

CSS
.row {
  display: flex;
  align-items: center;
}

.box-right {
  margin-left: auto; /* Tự động đẩy thẻ này sang sát lề phải */
}
Khi nào hữu ích: Khi trong hàng có thêm phần tử ở giữa hoặc bạn chỉ muốn đẩy riêng một thẻ về bên phải mà vẫn giữ các thẻ khác bên trái.

3. Dùng CSS Grid (1fr auto hoặc repeat(2, auto))
Nếu bạn đang làm bố cục dạng lưới:

CSS
.row {
  display: grid;
  grid-template-columns: auto auto;
  justify-content: space-between;
  align-items: center;
}
4. Cách cũ / ít dùng hơn cho bố cục chính: float hoặc position: absolute
float: left và float: right: Ít dùng cho layout hiện đại vì dễ gặp lỗi sập chiều cao thẻ cha (height: 0), cần thêm overflow: hidden hoặc clearfix.

position: absolute (left: 0 và right: 0): Chỉ nên dùng khi muốn hai thẻ đè lên lớp nội dung khác (ví dụ nút mũi tên trái/phải trên slider ảnh), không nên dùng cho bố cục hàng ngang thông thường vì phần tử thoát khỏi luồng bình thường dễ đè hoặc chồng chéo nhau.

Lưu ý thực tế
Cần có "lề lề" cách mép màn hình? Nếu "lề trái / lề phải trang web" nghĩa là muốn có khoảng cách thở với mép màn hình thay vì dính sát 0px, hãy thêm padding: 0 16px; (hoặc đặt thẻ cha vào một .container có max-width và margin: 0 auto;).

Trên màn hình điện thoại nhỏ: Nếu hai thẻ chứa nội dung dài mà không xuống dòng, chúng có thể bị ép hẹp. Bạn có thể thêm flex-wrap: wrap; gap: 12px; vào .row để chúng tự rớt dòng gọn gàng khi thiếu chỗ.

ý nghĩa của display: flex;

Trong CSS, display: flex; (viết tắt của Flexible Box Layout) biến một phần tử thành flex container (khung chứa linh hoạt) để sắp xếp, căn chỉnh và phân bổ không gian cho các flex items (phần tử con trực tiếp bên trong nó) theo một chiều (hoặc một hàng ngang, hoặc một cột dọc).

Điểm khác biệt lớn nhất so với bố cục thông thường là khi đặt display: flex; cho thẻ cha, các thẻ con sẽ tự động xếp nối tiếp nhau trên một trục thay vì tự xuống dòng như thẻ block, đồng thời mở khóa khả năng căn giữa, giãn đều khoảng cách và co giãn kích thước cực kỳ dễ dàng.

Trục chính và trục phụ trong Flexbox, do AI tạo
Trục chính và trục phụ trong Flexbox. Nguồn: Made with Google AI
1. Hai khái niệm cốt lõi cần nắm
Flex Container (Thẻ cha có display: flex;): Là nơi bạn khai báo quy tắc bố cục chung (hướng xếp, cách căn lề, khoảng cách giữa các item, có cho phép xuống dòng hay không).

Flex Item (Các thẻ con trực tiếp): Là các phần tử nằm bên trong flex container. Chúng sẽ chịu sự điều khiển của flex layout (lưu ý: chỉ các con trực tiếp mới thành flex item, cháu chắt bên trong không bị biến đổi trực tiếp).

Trục chính (Main axis) & Trục phụ (Cross axis):

Mặc định (flex-direction: row), trục chính chạy ngang từ trái sang phải, còn trục phụ chạy dọc từ trên xuống dưới.

Nếu đổi thành flex-direction: column, trục chính sẽ chạy dọc và trục phụ chạy ngang.

2. Các thuộc tính quan trọng nhất đi kèm display: flex;
Nhóm / Thuộc tính	Đặt ở đâu	Công dụng chính
flex-direction	Thẻ cha	Chọn hướng xếp: row (ngang, mặc định), column (dọc), row-reverse, column-reverse.
justify-content	Thẻ cha	Căn chỉnh và chia khoảng cách dọc theo trục chính (flex-start, center, flex-end, space-between, space-around, space-evenly).
align-items	Thẻ cha	Căn chỉnh các phần tử dọc theo trục phụ (stretch mặc định, center, flex-start, flex-end).
gap	Thẻ cha	Tạo khoảng cách đều giữa các phần tử (ví dụ gap: 16px;) mà không cần tính margin rườm rà.
flex-wrap	Thẻ cha	Cho phép tự xuống dòng khi thiếu chỗ (wrap) thay vì ép tất cả nằm chung một hàng (nowrap).
flex (grow, shrink, basis)	Thẻ con	Quy định cách phần tử con tự giãn ra lấp đầy chỗ trống hoặc co lại khi màn hình hẹp.
3. Ví dụ thực tế
Giả sử bạn có một thanh điều hướng gồm logo bên trái và nhóm nút bên phải, tất cả đều nằm thẳng hàng giữa theo chiều dọc:

HTML
<header class="navbar">
  <div class="logo">MyBrand</div>
  <nav class="menu">
    <a href="#">Trang chủ</a>
    <a href="#">Sản phẩm</a>
    <a href="#">Liên hệ</a>
  </nav>
</header>
CSS
.navbar {
  display: flex;
  justify-content: space-between; /* Đẩy logo sang trái, menu sang phải */
  align-items: center;           /* Căn giữa theo chiều dọc */
  padding: 12px 24px;
}

.menu {
  display: flex;
  gap: 20px;                     /* Khoảng cách giữa các mục menu */
}
4. Khi nào nên dùng display: flex; và khi nào nên dùng display: grid;?
Dùng display: flex; khi: Bố cục 1 chiều — sắp xếp theo một hàng hoặc một cột (thanh navbar, cụm nút bấm, thẻ tag, danh sách nằm ngang, căn giữa một khối).

Dùng display: grid; khi: Bố cục 2 chiều — cần kiểm soát đồng thời cả hàng và cột (lưới sản phẩm nhiều cột, bảng điều khiển dashboard, bố cục trang có nhiều vùng ghép ô).

cách xóa chữ màu xanh cho thẻ a

Màu xanh mặc định của thẻ <a> (cùng với gạch chân) là kiểu dáng mặc định của trình duyệt. Để đổi sang màu chữ khác hoặc ăn theo màu chữ xung quanh, bạn dùng thuộc tính color trong CSS — và thường sẽ đi kèm text-decoration: none; để bỏ luôn gạch chân mặc định.

1. Đổi màu chữ thẻ <a> sang màu mong muốn
CSS
a {
  color: #111827;          /* Đổi sang màu đen/xám đậm thay vì xanh mặc định */
  text-decoration: none;   /* Bỏ gạch chân mặc định */
}
2. Cho thẻ <a> tự ăn theo màu chữ của thẻ cha (inherit)
Nếu thẻ <a> nằm bên trong một đoạn văn, nút bấm hoặc tiêu đề đã có màu riêng và bạn muốn chữ của link đồng bộ với màu đó:

CSS
a {
  color: inherit;          /* Kế thừa màu chữ từ phần tử cha */
  text-decoration: none;
}
3. Lưu ý các trạng thái liên kết (:visited, :hover, :active)
Ngay cả khi bạn đã đổi color cho thẻ <a>, trình duyệt vẫn có thể đổi màu khi liên kết đã từng truy cập (:visited) hoặc khi di chuột / bấm vào (:hover, :active). Để giữ màu đồng nhất, bạn có thể khai báo rõ các trạng thái này:

CSS
a,
a:visited {
  color: #1f2937;
  text-decoration: none;
}

a:hover,
a:active {
  color: #000000; /* Màu khi rê chuột hoặc đang nhấn */
}
Mẹo nhỏ
Muốn chỉ áp dụng cho một nhóm link nhất định (ví dụ menu hoặc thẻ card) thay vì toàn bộ thẻ <a> trên trang, hãy đặt class cụ thể như .nav-link { color: #333; text-decoration: none; }.

Vẫn thấy chữ màu xanh? Kiểm tra xem có quy tắc CSS nào khác có độ ưu tiên cao hơn đang ghi đè (như style inline trên thẻ HTML, selector có ID #..., hoặc rule định nghĩa ở file/dòng nằm phía sau).

nếu có thẻ li bọc ngoài thẻ a thì đổi màu chữ kiểu gì

Khi có thẻ <li> bọc ngoài thẻ <a>, bạn vẫn đổi màu chữ bằng thuộc tính color trên chính thẻ <a> (thông qua selector li a), vì trình duyệt áp dụng màu xanh mặc định trực tiếp lên thẻ <a> chứ không phải lên <li>.

Nếu bạn chỉ viết li { color: #111; }, chữ bên trong thẻ <a> vẫn sẽ giữ màu xanh mặc định do style mặc định của thẻ <a> có độ ưu tiên trực tiếp trên chính nó.

1. Cách viết đúng: chọn li a
HTML
<ul>
  <li><a href="#">Trang chủ</a></li>
  <li><a href="#">Sản phẩm</a></li>
  <li><a href="#">Liên hệ</a></li>
</ul>
CSS
li a {
  color: #111827;        /* Đổi màu chữ của thẻ <a> bên trong <li> */
  text-decoration: none; /* Bỏ gạch chân mặc định */
}
2. Nếu muốn ăn theo màu chữ đặt trên thẻ <li>
Nếu bạn đã đặt màu chữ cho <li> (hoặc <ul>/<nav>) và muốn thẻ <a> bên trong tự ăn theo màu đó:

CSS
li {
  color: #1e293b;
}

li a {
  color: inherit;        /* Lấy màu chữ từ thẻ <li> bao ngoài */
  text-decoration: none;
}
3. Giới hạn phạm vi để không ảnh hưởng toàn bộ <li> trên trang
Nếu trang web có nhiều danh sách khác nhau, hãy gắn class cho <ul>, <nav> hoặc <li> để chỉ đổi đúng menu bạn muốn:

CSS
.menu li a {
  color: #222222;
  text-decoration: none;
}

.menu li a:hover {
  color: #0f766e;        /* Đổi màu khi rê chuột */
}
Lưu ý
Dấu chấm đầu dòng của <li> (marker): Dấu chấm hoặc số thứ tự của <li> sẽ ăn theo color của thẻ <li> (nếu có đặt color trên li), còn nội dung chữ bên trong thẻ <a> sẽ ăn theo color của li a.

cách căn giữa nút button

Cách căn giữa nút <button> phụ thuộc vào việc bạn muốn căn theo chiều ngang bên trong khung chứa, căn giữa cả ngang lẫn dọc trong một khối/màn hình, hay chỉ căn chữ bên trong nút.

Dưới đây là các cách phổ biến và dễ áp dụng nhất:

1. Căn giữa theo chiều ngang (phổ biến nhất)
Cách A: Thẻ cha dùng text-align: center (nhanh gọn cho <button> đơn lẻ)
Vì <button> mặc định là inline-block, bạn chỉ cần đặt text-align: center; cho thẻ cha:

HTML
<div class="btn-wrapper">
  <button type="button">Đăng ký ngay</button>
</div>
CSS
.btn-wrapper {
  text-align: center;
}
Cách B: Thẻ cha dùng Flexbox (khuyên dùng khi có nhiều nút hoặc cần căn dọc)
CSS
.btn-wrapper {
  display: flex;
  justify-content: center; /* Căn giữa theo chiều ngang */
}
Cách C: Đặt display: block; margin: 0 auto; cho chính <button>
Khi đổi <button> thành block, margin-left: auto và margin-right: auto sẽ tự chia đều hai bên lề:

CSS
button {
  display: block;
  margin: 0 auto; /* Căn giữa ngang (trên/dưới = 0, trái/phải = tự động) */
}
2. Căn giữa cả chiều ngang lẫn chiều dọc
Nếu bạn muốn đặt <button> vào đúng tâm của một thẻ <div> hoặc toàn bộ khung nhìn (100vh), Flexbox là cách sạch sẽ nhất:

CSS
.hero-box {
  display: flex;
  justify-content: center; /* Giữa theo chiều ngang */
  align-items: center;     /* Giữa theo chiều dọc */
  min-height: 300px;       /* Cần có chiều cao để thấy rõ hiệu quả căn dọc */
}
3. Căn chữ bên trong nút <button>
Nếu bạn muốn chữ bên trong nút nằm chính giữa (ví dụ khi nút có đặt width lớn hơn chữ):

CSS
button {
  width: 220px;
  height: 44px;
  display: inline-flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
Mẹo kiểm tra nếu nút không chịu căn giữa
Kiểm tra width của thẻ cha: Nếu thẻ cha chỉ rộng bằng nội dung bên trong (không chiếm hết hàng ngang), việc căn giữa bên trong thẻ cha sẽ không thấy dịch chuyển.

Kiểm tra thuộc tính float: Nếu <button> đang có float: left hoặc float: right, hãy gỡ float trước khi dùng Flexbox hoặc margin: 0 auto.

cách căn giữ nút button so với lề trái lề phải của web

Để căn nút <button> nằm chính giữa theo chiều ngang giữa lề trái và lề phải của trang web, cách đơn giản và ổn định nhất là đặt nút bên trong một khối rộng hết chiều ngang trang rồi căn giữa nó.

Dưới đây là 3 cách phổ biến nhất:

1. Dùng display: block và margin: 0 auto (gọn nhất cho 1 nút)
Đổi <button> sang dạng khối (block) rồi đặt margin: 0 auto; để trình duyệt tự chia đều khoảng cách hai bên trái/phải:

HTML
<button class="btn-center" type="button">Xem thêm</button>
CSS
.btn-center {
  display: block;
  margin: 0 auto; /* Căn giữa đều giữa lề trái và lề phải */
}
2. Thẻ cha dùng Flexbox (justify-content: center)
Rất tiện nếu bạn muốn căn giữa một nhóm nút hoặc muốn căn thêm cả chiều dọc:

HTML
<div class="action-area">
  <button type="button">Xem thêm</button>
</div>
CSS
.action-area {
  display: flex;
  justify-content: center; /* Căn giữa theo chiều ngang */
  width: 100%;             /* Đảm bảo phủ hết chiều ngang từ trái sang phải */
}
3. Thẻ cha dùng text-align: center
Vì <button> mặc định là inline-block, bạn chỉ cần đặt text-align: center; cho thẻ bao ngoài đang rộng hết hàng ngang:

CSS
.action-area {
  text-align: center;
  width: 100%;
}
Lưu ý để căn đúng giữa toàn trang web
Kiểm tra khối bao ngoài: Nếu <button> nằm bên trong một khung hẹp (ví dụ cột bên trái hoặc hộp có chiều rộng giới hạn) thì nó sẽ căn giữa so với khung đó, không phải so với toàn bộ chiều ngang trang web. Muốn căn theo toàn trang, hãy đặt nút ở cấp khối full-width (100% chiều ngang màn hình).

Tránh dùng float: Nếu nút đang có float: left hoặc float: right, margin: 0 auto sẽ không có tác dụng — hãy xóa float trước.

căn giữa nhưng ko làm tăng kích thước của nút

Để căn nút <button> nằm chính giữa mà không làm tăng kích thước của nút, nguyên tắc cốt lõi là: không đặt width: 100% hay flex: 1 lên chính <button>, và không đặt align-items: stretch cho thẻ cha Flex/Grid (vì stretch sẽ kéo giãn phần tử con lấp đầy chiều cao/chiều rộng theo trục phụ).

Nút sẽ giữ nguyên kích thước tự nhiên theo nội dung (padding + chữ) nếu bạn áp dụng một trong các cách sau:

1. Dùng display: block; margin: 0 auto; trên <button> (không đặt width)
Khi đặt display: block mà không ghi width: 100%, kích thước của nút vẫn chỉ vừa khít nội dung + padding của nó, còn margin: 0 auto tự chia đều hai bên trái/phải:

CSS
.btn-center {
  display: block;
  margin: 0 auto; /* Giữ nguyên kích thước nút, căn đều trái - phải */
}
2. Dùng thẻ cha display: flex; justify-content: center;
Trong Flexbox, justify-content: center chỉ đẩy vị trí của nút vào giữa theo trục ngang mà không làm phình kích thước nút (miễn là bạn không đặt flex: 1 hoặc flex-grow: 1 cho nút):

CSS
.btn-row {
  display: flex;
  justify-content: center; /* Căn giữa ngang, giữ nguyên size nút */
  align-items: center;     /* Tránh bị kéo giãn chiều cao theo trục phụ */
  width: 100%;
}
3. Dùng thẻ cha text-align: center;
<button> vốn là inline-block, nên text-align: center ở thẻ cha chỉ căn vị trí của nút vào giữa và giữ nguyên kích thước vốn có của nút:

CSS
.btn-row {
  text-align: center;
  width: 100%;
}
Vì sao đôi khi nút bị tăng kích thước khi căn chỉnh?
Thẻ cha là display: flex hoặc display: grid và bị kéo giãn: Nếu trục chính của container là dọc (flex-direction: column) và align-items đang là mặc định (stretch), nút dạng block có thể bị kéo rộng hết chiều ngang khung chứa. Hãy đặt align-items: center; cho thẻ cha.

Nút có flex-grow: 1 hoặc width: 100%: Kiểm tra xem có class hoặc rule CSS nào đang ép chiều rộng của nút hay không.

Có padding hoặc font-size thay đổi ở trạng thái :hover: Nếu nút bị to ra khi di chuột, hãy kiểm tra xem :hover có tăng padding, font-size hoặc transform: scale(...) không.

cách tách 6 thẻ nếu hết trang web thì sẽ đẩy nội dung xuống dưới

Để tách 6 thẻ (như 6 thẻ sản phẩm, 6 thẻ tính năng...) giãn cách đều nhau và tự động rớt/đẩy các thẻ dư xuống hàng dưới khi hết chiều ngang trang web, cách chuẩn nhất là dùng Flexbox kết hợp flex-wrap: wrap và gap, hoặc CSS Grid với auto-fit / minmax.

Khi các thẻ xuống hàng dưới, toàn bộ khối chứa 6 thẻ cũng sẽ tự giãn chiều cao xuống dưới, đẩy các nội dung phía sau trôi xuống theo luồng bình thường mà không bị đè lên nhau.

1. Cách dùng Flexbox (flex-wrap: wrap + gap) — Dễ hiểu, linh hoạt
Đặt display: flex; cho khung chứa 6 thẻ, thêm flex-wrap: wrap; để thẻ tự xuống dòng khi không đủ chỗ, và gap để tách khoảng cách giữa các thẻ cả hàng lẫn cột:

HTML
<div class="card-list">
  <div class="card">Thẻ 1</div>
  <div class="card">Thẻ 2</div>
  <div class="card">Thẻ 3</div>
  <div class="card">Thẻ 4</div>
  <div class="card">Thẻ 5</div>
  <div class="card">Thẻ 6</div>
</div>
<section class="below-content">Nội dung nằm phía dưới</section>
CSS
.card-list {
  display: flex;
  flex-wrap: wrap; /* Hết chỗ ngang thì tự đẩy thẻ xuống hàng dưới */
  gap: 16px;       /* Khoảng cách tách giữa các thẻ (cả ngang và dọc) */
}

.card {
  flex: 1 1 220px; /* Co giãn linh hoạt, rộng tối thiểu khoảng 220px trước khi xuống dòng */
  padding: 16px;
}
Nếu muốn chia cố định số cột theo kích thước thẻ: Ví dụ muốn mỗi thẻ rộng khoảng 200px và tách nhau 20px:

CSS
.card {
  width: 200px; /* Hoặc flex: 0 0 200px; */
}
2. Cách dùng CSS Grid (repeat(auto-fit, minmax(...))) — Đều cột cực đẹp
Nếu bạn muốn các thẻ trên cùng một hàng luôn chia đều chiều ngang thay vì hàng cuối bị lệch độ rộng:

CSS
.card-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 16px; /* Tách đều cả hàng ngang lẫn hàng dọc */
}
Cơ chế: Trình duyệt tự tính xem màn hình hiện tại chứa được bao nhiêu cột rộng tối thiểu 220px; nếu vượt quá (như 6 thẻ trên màn hình vừa/nhỏ), các thẻ còn lại sẽ tự đẩy xuống hàng dưới và tự giãn đều 1fr.

3. Lưu ý để nội dung phía dưới luôn được đẩy xuống mượt mà
Không đặt height cố định cho khối chứa 6 thẻ: Nếu bạn đặt chiều cao cố định (ví dụ height: 150px;), khi 6 thẻ rớt xuống 2–3 hàng sẽ bị tràn ra ngoài hoặc đè lên nội dung phía dưới. Hãy để chiều cao tự động (auto / mặc định).

Tránh position: absolute trên các thẻ: Phần tử absolute thoát khỏi luồng bố cục nên sẽ không đẩy các thẻ khác hay nội dung bên dưới xuống khi xuống dòng.

cach chinh chu blod

Để làm chữ in đậm (bold) trong HTML/CSS, bạn có thể dùng thuộc tính font-weight trong CSS hoặc dùng thẻ HTML trực tiếp (như <strong> hoặc <b>).

1. Cách chuẩn và linh hoạt nhất: dùng font-weight trong CSS
CSS
.text-bold {
  font-weight: bold; /* Hoặc dùng số: 600 (SemiBold), 700 (Bold), 800 (ExtraBold) */
}
Giá trị phổ biến:

normal hoặc 400: Chữ thường.

600: Hơi đậm (SemiBold).

700 (tương đương bold): Chữ đậm chuẩn.

800 / 900: Đậm hơn nữa (tùy font chữ có hỗ trợ độ đậm đó hay không).

2. Dùng thẻ trực tiếp trong HTML
<strong>: Làm chữ in đậm đồng thời mang ý nghĩa nhấn mạnh nội dung quan trọng (khuyên dùng cho từ khóa, cảnh báo, thông tin quan trọng).

HTML
<p>Vui lòng kiểm tra kỹ <strong>thông tin thanh toán</strong> trước khi xác nhận.</p>
<b>: Chỉ làm chữ in đậm về mặt hiển thị mà không nhấn mạnh ngữ nghĩa đặc biệt (thường dùng cho tên sản phẩm, từ khóa thuật ngữ, nhãn hiển thị...).

HTML
<p>Sản phẩm: <b>Áo thun cơ bản</b></p>
Mẹo nhỏ
Muốn bỏ in đậm (trả về chữ thường) trên thẻ vốn đã đậm như <h1>–<h6> hoặc <strong>: Đặt font-weight: normal; hoặc font-weight: 400; trong CSS.

Đặt font-weight: 700 nhưng chữ không đậm lên? Kiểm tra xem font chữ bạn đang dùng có tải/hỗ trợ trọng lượng đậm (700) hay không (ví dụ khi nhúng Google Fonts, cần chọn thêm các mức weight như 600;700).

cách thêm biểu tưọng C congf

Ý bạn muốn nói đến biểu tượng chữ C có vòng tròn bao quanh (© - ký hiệu bản quyền Copyright) phải không? Nếu đúng là ký hiệu ©, bạn có thể chèn trực tiếp vào HTML hoặc gõ nhanh trên bàn phím theo các cách dưới đây:

1. Chèn trực tiếp trong HTML
Dùng HTML Entity (an toàn nhất, không lo lỗi bảng mã):

HTML
<footer>
  <p>&copy; 2026 Tên thương hiệu. Bảo lưu mọi quyền.</p>
</footer>
Dán trực tiếp ký tự © (miễn file HTML đã khai báo <meta charset="UTF-8">) hoặc dùng mã số Unicode:

HTML
<p>&#169; 2026 Tên thương hiệu.</p>
<p>&#xA9; 2026 Tên thương hiệu.</p>
2. Gõ nhanh ký hiệu © trên máy tính
Windows: Giữ phím Alt và gõ 0169 (trên bàn phím số Numpad) rồi thả ra. Hoặc nhấn Win + . (dấu chấm) để mở bảng biểu tượng/ký tự và tìm copyright.

macOS: Nhấn tổ hợp Option + G.

Điện thoại (iOS / Android): Mở bàn phím, chuyển sang phần ký tự đặc biệt / biểu tượng (?123 hoặc biểu tượng cảm xúc) để chọn ©.

3. Thêm bằng CSS (::before hoặc ::after)
Nếu muốn tự động chèn © trước hoặc sau một phần tử mà không cần sửa HTML:

CSS
.copyright::before {
  content: "\00A9\0020"; /* Ký tự © kèm một khoảng trắng */
}
(Nếu ý của bạn là một biểu tượng chữ C khác — như ℃ độ C, ₡ đồng Colón, hay icon của thư viện như Font Awesome/Lucide — hãy nói rõ thêm để mình gửi đúng cách chèn nhé.)

những css cơ bản đầu tiên trước khi bắt đầu làm về web

Khi bắt đầu làm web, bạn chưa cần học ngay các kỹ thuật nâng cao hay thư viện phức tạp. Chỉ cần nắm vững nhóm CSS nền tảng dưới đây là bạn đã đủ khả năng dựng giao diện sạch sẽ, căn chỉnh vị trí, tô màu và làm trang web hiển thị ổn định trên nhiều kích thước màn hình.

1. Cú pháp & cách chọn phần tử (Selector cơ bản)
Mọi quy tắc CSS đều có dạng selector { thuộc-tính: giá-trị; }:

CSS
/* Chọn theo tên thẻ HTML */
p {
  line-height: 1.6;
}

/* Chọn theo class (dùng dấu chấm . — ưu tiên dùng nhiều nhất) */
.card-title {
  font-size: 18px;
}

/* Chọn theo id (dùng dấu thăng # — chỉ nên dùng cho 1 phần tử duy nhất) */
#main-header {
  background-color: #ffffff;
}
2. Reset cơ bản & box-sizing: border-box (Nên đặt ở đầu file CSS)
Mỗi trình duyệt đều có margin/padding mặc định riêng cho thẻ <body>, <h1>, <ul>, <p>... và mặc định tính width không gồm padding + border (dễ làm hộp bị phình to ngoài ý muốn). Đoạn reset dưới đây giúp mọi thứ dễ kiểm soát ngay từ đầu:

CSS
*,
*::before,
*::after {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: system-ui, -apple-system, sans-serif;
  line-height: 1.5;
  color: #1f2937;
  background-color: #ffffff;
}

img {
  max-width: 100%;
  display: block;
}
3. Box Model: width, height, padding, border, margin
Mỗi phần tử HTML đều là một chiếc hộp gồm 4 lớp từ trong ra ngoài:

padding: Khoảng đệm bên trong viền (đẩy nội dung cách xa đường viền).

border: Đường viền bao quanh phần tử (thường đi kèm border-radius để bo góc).

margin: Khoảng cách bên ngoài viền (tạo khoảng trống giữa phần tử này với các phần tử khác).

width / height & max-width: Kích thước rộng/cao; dùng max-width giúp khung chứa co giãn gọn khi màn hình nhỏ thay vì bị tràn ngang.

CSS
.box {
  width: 100%;
  max-width: 480px;
  padding: 16px 20px;        /* Trên-dưới 16px, trái-phải 20px */
  border: 1px solid #d1d5db;
  border-radius: 8px;
  margin: 16px auto;         /* Căn giữa ngang nếu có max-width/width */
}
4. Màu sắc & chữ viết (Typography)
Màu chữ & màu nền: color (màu chữ), background-color (màu nền). Có thể viết dạng mã hex (#2563eb), rgb()/rgba() (hỗ trợ độ trong suốt) hoặc tên màu.

Kiểu & kích thước chữ:

font-family: Phông chữ.

font-size: Cỡ chữ (px, rem).

font-weight: Độ đậm (400 thường, 600 hơi đậm, 700 đậm).

line-height: Chiều cao dòng (nên đặt khoảng 1.4–1.7 cho đoạn văn dễ đọc).

text-align: Căn lề chữ (left, center, right).

text-decoration: Trang trí chữ (none để bỏ gạch chân link).

5. display & Bố cục cơ bản (Block, Inline, Flexbox, Grid)
display: block: Chiếm hết chiều ngang hàng, tự xuống dòng (div, p, section...).

display: inline / inline-block: Nằm cùng hàng; inline-block nhận được width, height, margin trên/dưới đầy đủ hơn inline.

display: flex: Sắp xếp các phần tử con theo 1 chiều (hàng ngang hoặc cột dọc), rất mạnh để căn giữa (justify-content: center; align-items: center;) hoặc đẩy hai bên (justify-content: space-between;).

display: grid: Chia bố cục 2 chiều (hàng và cột) đều đặn như lưới thẻ sản phẩm.

6. position cơ bản & trạng thái tương tác (:hover)
position:

relative: Dịch chuyển tương đối so với vị trí gốc (vẫn giữ chỗ) và làm mốc cho absolute bên trong.

absolute: Định vị theo tổ tiên gần nhất có position khác static (như relative), không giữ chỗ gốc.

fixed: Ghim cố định theo khung nhìn trình duyệt (như nút hỗ trợ hoặc thanh thông báo cố định).

Trạng thái :hover: Thay đổi giao diện khi người dùng di chuột qua (ví dụ đổi màu nút, đổi viền) kèm transition để chuyển động mượt mà.

CSS
.btn {
  background-color: #2563eb;
  color: #ffffff;
  padding: 10px 16px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.2s ease;
}

.btn:hover {
  background-color: #1d4ed8;
}
Lộ trình thực hành gợi ý ngay từ đầu
Tạo 1 file index.html và 1 file style.css liên kết với nhau bằng <link rel="stylesheet" href="style.css">.

Dựng một trang nhỏ gồm header + 1 khối giới thiệu + 3 thẻ nội dung + footer, luyện áp dụng padding/margin, border-radius, color, :hover, rồi thử sắp xếp các thẻ bằng display: flex và display: grid.
