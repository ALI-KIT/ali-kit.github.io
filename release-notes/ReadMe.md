# Release Notes 

## Tháng 11/2020

#### Tuần 01 (Ongoing)

## Tháng 10/2020

#### Tuần 05
 - Đã hoàn thành chức năng đăng nhập đăng ký (chờ kiểm thử)
 
#### Tuần 04
- Crawler có thể parse được bất kỳ trang báo nào miễn là cung cấp url trang rss hoặc trang sitemap. Sử dụng thư viện lib Readability (dùng trong Reader mode của Firefox) của Mozilla và 1 lib khác (Article Parser) để lấy dc title, description, content của bài viết (article 
- Thêm nguồn tin mới gồm 24h, vtv news, kenh14, tiền phong
- Cập nhật thuật toán lọc tin tức để lấy được các tin dựa vào keywords (vd: quận 9) từ các trường của tin tức (tags, title, description và content), (trước đó chỉ dựa vào field keywords[])
+ Admin cũng có thể thêm ds keywords mới cho quận 9, thêm nguồn tin mới (cung cấp url trang rss hoặc sitemap)
