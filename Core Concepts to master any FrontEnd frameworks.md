# Core Concepts to master any FrontEnd frameworks

![frameworks](/Users/quandoh./Documents/core-concept/frameworks.png)

Ngày nay, **Front-end web development** không chỉ giới hạn ở HTML, CSS và JavaScript. Nhu cầu trải nghiệm web của người dùng ngày một cao, điều đó đòi hỏi FE phải mở rộng thêm nhiều libraries, frameworks để đáp ứng được công nghệ mới và gia tăng UI/UX. Vì thế rất nhiều frameworks được ra đời, và danh sách này sẽ còn gia tăng và phát triển trong rất nhiều năm tới. Đi kèm với đó, rất nhiều cuộc tranh cãi về việc đâu là framework tốt nhất, đâu là framework được developers chọn nhiều nhất, và dĩ nhiên, chưa bao giờ có câu trả lời thoả đáng bởi vì mỗi frameworks đều có những ưu và nhược điểm khác nhau.

Như lịch sử đã chứng minh, **web development** là một lĩnh vực phát triển với tốc độ mạnh mẽ, bạn sẽ ngụp lặn trong thế giới web nếu như không chuẩn bị sẵn sàng để chuyển từ framework này sang framework khác. Việc tiếp cận framework mới thực sự sẽ rất dễ dàng khi bạn nắm vững một vài concept chính trong bài viết này, và bạn sẽ trở thành một FE developer được săn đón trong nhiều năm tới, bất kể bạn đang chọn framework nào.

## 1. Components

Component là khái niệm cơ bản nhất mà một FE developer phải nắm, nó là nền tảng của sự phát triển giao diện người dùng nhưng cũng là khái niệm quan trọng nhất thúc đẩy sự phát triển của **Frontend frameworks** hiện đại ngày nay. Nếu không thực sự hiểu về components, ứng dụng web của bạn có thể sẽ phình to rất nhanh.
### Vậy component là gì ?

Một component là 1 tổ hợp của các phần tử HTML đi kèm với markup và các script xoay quanh các phần tử đó. Tất cả các thành phần nhỏ nhất của web sẽ nhóm lại theo các tính năng tương ứng, và quy về component.
Lấy ví dụ: để show ra Todo list có 5 items, thì chúng ta sẽ phải xây dựng 2 components:

![1_bhzdF_rtFcM3S6kubAEteA](/Users/quandoh./Documents/core-concept/1_bhzdF_rtFcM3S6kubAEteA.jpeg)

- Todo item: chứa giao diện của 1 item và các chức năng cần thiết như show content, edit & delete chính mình.
- Todo list: chứa 5 components Todo item và có chức năng show ra các items, phân trang nếu như có quá nhiều items,....

### Tại sao phải cần component ?

Nếu như ko có component Todo item, và clients thay đổi specs, không có tính năng edit item nữa, thì developer phải thực hiện xoá phần code liên quan đến việc edit **5 lần**. Điều này thực sự rất tốn thời gian so với việc chia component Todo Item và sử dụng lại, chỉ cần thay đổi content của component Todo Item **1 lần** là sẽ áp dụng cho tất cả items.

> Vì vậy bắt buộc phải chia component khi lập trình web ở bất cứ framework nào. Việc chia components giúp chúng ta có thể tái sử dụng, dễ dàng sửa đổi và mở rộng code. Code sẽ sạch sẽ và tường minh hơn rất nhiều khi components đc chia hợp lý.



