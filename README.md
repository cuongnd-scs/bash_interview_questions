BASH SHELL INTERVIEW QUESTIONS
=============================

####[[⬆]] Shell script

1. Viết một kịch bản in ra đường dẫn tuyệt đối của chính nó
2. Viết một kịch bản in ra nội dung của chính nó
3. Viết một kịch bản có thể `reload` nội dung của chính nó
4. Viết kịch bản tương đương với lệnh `watch`
5. Viết một kịch bản hoặc một command in ra thời gian uptime tính bằng phút
6. Viết một kịch bản chia 1 file lớn thành nhiều file nhỏ kiểu line-by-line. Ví dụ có
một file 1000K dòng không thể mở lên, chia là 10 file (hoặc một số file bất kỳ). Với
tên file được định nghĩa trước (có thể dùng awk).
7. Viết một vòng lặp, lặp qua một loạt các con số được khai báo bởi một biến. Ví dụ `for x in "$i"..."$j"`

####[[⬆]] Shell command

1. Phân biệt `rsync -avz local remote` với `rsync -avz local/ remote`
2. Làm thế nào để xóa tất cả các thư mục rỗng trong một thư mục?
3. Tổ hợp phím `^ Z` dùng để làm gì?
4. So sánh `^ C` và `^ Z`
5. Làm thế nào để chờ (`sleep`) mà không phải dùng lệnh `sleep`?
6. Chuyện gì xảy ra khi nhấn `^ C` ([hint](http://plaban123.tumblr.com/post/117417983794/what-happens-when-you-hit-ctrl-c))
7. Delete/Insert dòng đầu tiên của một file có 15 triệu dòng nhanh nhất có thể?
8. Làm sao xóa một thư mục chứa 2 triệu file nhanh nhất có thể.
9. Phân biệt `$@` và `$*` với`"$@"` và `"$*"`.
10. Phân biệt `exit 0` và `exit 1`.
11. Sự khác nhau giữa `{}` và `()`, chuyện gì xảy ra nếu có `exit 0`?
12. Chuyển đổi một chuỗi thành chữ HOA hoặc chữ thường. Ví dụ `string="Hello Ajinomoto"` thành `HELLO AJINOMOTO` hoặc `hello ajinomoto`.
13. Lấy biến môi trường của một process như thế nào?

####[[⬆]] Troubleshooting

1. Một container của OpenVZ báo lỗi `Disk quota exceeded`, tuy nhiên check
bằng lệnh `df -h` thì thấy đĩa vẫn còn trống đến vài chục GB. Tình huống
gì có thể xảy ra (hint: `df -i`)
2. Khi đĩa đầy thì làm gì cho nó ... hết đầy?

####[[⬆]] Questions that can kill you

1. Bạn biết `Phusion Passenger` là gì không? Có nhân vật nổi tiếng nào
  đang làm cho họ?
2. Bạn đã từng đọc bài nào do `Phusion Passenger` viết chưa? Bài đó như thế nào
  và bạn đã học được gì từ bài đó?
3. Làm thế nào để biết hệ thống đã chạy được bao lâu rồi? (aka `uptime`)

#### [[⬆]] Funny

1. Làm sao để custom màu sắc của lệnh `ls`
2. Chuyện gì xảy ra khi chạy lệnh `yes >> /dev/null`
3. Chuyện gì xảy ra khi chạy lệnh `cat /dev/urandom > /dev/null`, phân biệt kết quả với lệnh [2]
