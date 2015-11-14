BASH SHELL INTERVIEW QUESTIONS
=============================

####[[⬆]] Shell script

- Viết một kịch bản in ra đường dẫn tuyệt đối của chính nó
- Viết một kịch bản in ra nội dung của chính nó
- Viết một kịch bản có thể `reload` nội dung của chính nó
- Viết kịch bản tương đương với lệnh `watch`
- Viết một kịch bản hoặc một command in ra thời gian uptime tính bằng phút
- Viết một kịch bản chia 1 file lớn thành nhiều file nhỏ kiểu line-by-line. Ví dụ có
một file 1000K dòng không thể mở lên, chia là 10 file (hoặc một số file bất kỳ). Với
tên file được định nghĩa trước (có thể dùng awk).
- Viết một vòng lặp, lặp qua một loạt các con số được khai báo bởi một biến. Ví dụ `for x in "$i"..."$j"` 

####[[⬆]] Shell command

- Phân biệt `rsync -avz local remote` với `rsync -avz local/ remote`
- Làm thế nào để xóa tất cả các thư mục rỗng trong một thư mục?
- Tổ hợp phím `^ Z` dùng để làm gì?
- So sánh `^ C` và `^ Z`
- Làm thế nào để chờ (`sleep`) mà không phải dùng lệnh `sleep`?
- Chuyện gì xảy ra khi nhấn `^ C` ([hint](http://plaban123.tumblr.com/post/117417983794/what-happens-when-you-hit-ctrl-c))
- Delete/Insert dòng đầu tiên của một file có 15 triệu dòng nhanh nhất có thể?
- Làm sao xóa một thư mục chứa 2 triệu file nhanh nhất có thể.
- Phân biệt `$@` và `$*` với`"$@"` và `"$*"`.
- Phân biệt `exit 0` và `exit 1`.
- Sự khác nhau giữa `{}` và `()`, chuyện gì xảy ra nếu có `exit 0`?

####[[⬆]] Troubleshooting

- Một container của OpenVZ báo lỗi `Disk quota exceeded`, tuy nhiên check
bằng lệnh `df -h` thì thấy đĩa vẫn còn trống đến vài chục GB. Tình huống
gì có thể xảy ra (hint: `df -i`)
- Khi đĩa đầy thì làm gì cho nó ... hết đầy?

####[[⬆]] Questions that can kill you

- Bạn biết `Phusion Passenger` là gì không? Có nhân vật nổi tiếng nào
  đang làm cho họ?
- Bạn đã từng đọc bài nào do `Phusion Passenger` viết chưa? Bài đó như thế nào
  và bạn đã học được gì từ bài đó?
- Làm thế nào để biết hệ thống đã chạy được bao lâu rồi? (aka `uptime`)
