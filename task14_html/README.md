Thực hiện : Khuê

# Tìm hiểu về HTML

[1.HTML là gì](#htmllagi)

[2.Các thẻ định dạng văn bản](#tagvanban)

[3.Thuộc tính của các thẻ](#thuoctinh)

[4.Thẻ thông tin webside](#thongtin)
### 1.HTML là gì :

HTML viết tắt của Hyper Text Markup Language là ngôn ngữ đánh dấu siêu văn bản dùng để tạo một trang web trên một website mỗi trang được gọi là một tài liệu website 

Một tài liệu HTML được tạo bởi cái phần tử HTML được gọi là các cặp thẻ trong HTML . Thường thì các thẻ sẽ đi theo từng cặp nhưng có một số thẻ không có thẻ đóng . 

Mỗi tập tin HTML sẽ được lưu lại với đuôi mở rộng `.html` hoặc `.htm`

HTML là bộ xương của website đống vai trò khai báo siêu văn bản cho website còn chỉnh sửa giao diện thuộc về CSS,JavaScrip.....

### 2.Các thẻ định dạng văn bản 

Các thẻ được viết dưới dạng : `<thẻ> nội dung </thẻ>`

Đối với thẻ ko đi theo cặp : `<thẻ> nội dung />`

a.Thẻ tiêu đề :

Trong HTML hổ trợ 6 thẻ tiêu đề : `<h1></h1> , <h2></h2> , <h3></h3> , <h4></h4> , <h5></h5> , <h6></h6>` 

Nếu bạn dùng h7 trở lên nó sẽ thành dạng text bình thường . Ví dụ :
<img src ="http://sv1.upsieutoc.com/2016/12/10/html1.png">

b.Văn bản 

Để khai báo một đoạn văn bản ta dùng thẻ : `<p></p>`

Để in đậm một nội dung ta dùng thẻ : `<strong></strong>`

Để in nghiêng một nội dung ta dùng : `<i></i>`

Để gạch chân một nội dung ta dùng : `<u></u>`

Để gạch ngang một nội dung ta dùng : `<strike></strike>`

Gạch gang : `<hr>`

Câu trích dẫn : `<quote></quote>`

Thẻ định dạng sẵn : `<pre></pre>`

Khai báo những đoạn code ngắn : `<code></code>`

Ghi chú trong HTML : `<!-- nội dung -->`


Xem thêm 1 số thẻ ở [đây](http://hocwebchuan.com/reference/tag/)

Ví dụ :
<img scr ="http://sv1.upsieutoc.com/2016/12/10/html2.png">
c.Danh sách trong HTML 

Để khai báo danh sách ta dùng thẻ : `<ol></ol>`

Trong thẻ `<ol></ol>` ta có thẻ `<li></li>` dùng để khai báo danh mục trong danh sách đó.

Ngoài thẻ `<ol></ol>` ta còn có thẻ `<ul></ul>` không có sắp xếp còn thẻ `<ol></ol>` thì có sắp xếp 

Đối với danh sách có mô tả ta dùng thẻ `<dl></dl>` nhưng trong thẻ này ta không dùng thẻ `<li></li>` mà ta sử dụng thẻ `<dt></dt>` để khai báo danh mục và dùng thẻ `<dd></dd>` để khai báo mô tả cho danh mục 

Ví dụ :
<img scr ="http://sv1.upsieutoc.com/2016/12/10/html3.png">

d.Các thẻ khác
