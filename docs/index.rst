Cơ sở dữ liệu nội dung khoa học của ExploraScience
==================================================

Đây là thư viện lưu trữ tài liệu phục vụ việc khai thác các mô hình, trò chơi (gọi chung là *mô-đun*) tại Trung tâm khám phá Khoa học (Quy Nhơn, Bình Định).

**Thư viện này dành cho ai?**

  Thư viện này dành cho các nhân viên phổ biến khoa học, các cộng tác viên, nhà quản lý của ExploraScience muốn hiểu hơn về các nội dung khoa học được trình bày tại ExploraScience.

**Thư viện này bao gồm những gì?**

  Ở mức độ cơ bản nhất, các mô-đun trưng bày được miêu tả như những black box, như một sản phẩm hoàn thiện, và người đọc đang quan tâm đến việc sử dụng mô-đun này như thế nào, sẽ học được gì từ mô-đun này.

  Đôi khi, cấu tạo của các mô-đun sẽ được đề cập, như một cách để người chế tạo gợi nhớ lại được quá trình hoàn thiện sản phẩm, giúp ích cho việc sửa chữa các vấn đề xảy ra nếu có.

  Đôi khi, các "giáo án" giới thiệu mô-đun trưng bày cũng sẽ được bao gồm. Tuy nhiên, thư viện này ưu tiên việc trình bày các thông tin nền, các kiến thức cơ bản, để từ đó người trình bày, tùy thuộc hoàn cảnh, có thể có các sáng tạo riêng của mình trong cách truyền đạt.

**Thư viện này không bao gồm những gì?**

  Theo kinh nghiệm của chúng tôi, việc quản lý tài sản (dự toán, mua sắm, hóa đơn, đề án, nghiệm thu...) tuy rất quan trọng nhưng không nên nằm chung với các tài liệu *khai thác* sản phẩm.

**Lý do thư viện này ra đời?**

  Trước đây, ExploraScience đã tập hợp các tài liệu phổ biến khoa học và đặt chúng trên Google Drive, xếp theo cây thư mục truyền thống. Tuy nhiên cách làm này đã cho thấy nhược điểm nổi cộm nhất là *khó khăn trong việc tra cứu*. Có thể nêu một số nguyên do:

  * Các tài liệu được soạn với nhiều định dạng: word, pdf, latex, google docs... và được xếp trong một cây thư mục nhiều tầng lớp. Người cần thông tin sẽ không dễ để kiểm tra xem tài liệu cần tìm có tồn tại không, và do đó ngại tìm kiếm.
  * Định dạng tài liệu thường không đảm bảo độ thân thiện với các thiết bị di động.
  * Mọi người thường không được cấp quyền đọc/sửa kịp thời, do việc quản lý quyền truy cập với từng tài liệu và với từng người dùng là một việc rất khó khăn (thậm chí quản lý theo nhóm người dùng ở một số hệ thống khác như Synology).
  * Độ tin cậy của tài liệu thấp: người cần tra cứu sẽ không chắc các thông tin đọc được đã phải là các thông tin được cập nhật nhất chưa.

  Khó khăn trong việc tra cứu kể trên sẽ dẫn đến những hậu quả sau:

  * Người quản lý thường đưa sót tài liệu lên thư viện hoặc cấp sót quyền truy cập cho mọi người, dẫn đến việc thư viện dễ bị "bỏ bê", sau đó tác động tiêu cực trở lại tần suất sử dụng thư viện. Đây là một vòng luẩn quẩn khiến hệ thống sẽ sụp đổ sau một thời gian.
  * Khi cần thông tin (để trình bày trước công chúng, để tổng hợp viết báo cáo...), nhân viên sẽ tự mình viết ra các đoạn miêu tả mô-đun. Những thông tin không được biên tập như vậy sẽ tiềm ẩn nhiều lỗi, và các lỗi đó sẽ lan truyền đến những công việc phía sau.

  Thư viện này được ra đời để lấp các lỗ hổng trên, bằng cách thỏa mãn các tiêu chí sau:

  * Khả năng truy cập cao: Thư viện sẽ hiển thị trên nền tảng web *responsive*, tương thích với máy tính để bàn và các thiết bị di động.
  * Khả năng tìm kiếm cao: cỗ máy tìm kiếm của thư viện có thể tìm kiếm mọi từ ngữ được dùng.
  * Chất lượng cao: được đảm bảo bằng quy trình biên soạn, đóng góp, hiệu đính, biên tập (sẽ nói đến ở phần sau).

**Cách thức đóng góp cho thư viện**

  Thư viện nhận nhiều hình thức đóng góp:

  * Các cách truyền thống: bàn bạc trực tiếp, qua mạng, gửi email đến người phụ trách (ban đầu là quan.tran.fr@gmail.com)
  * Tạo một issue trên trang GitHub của thư viện (sẽ hướng dẫn cụ thể sau) để trao đổi với người phụ trách
  * Đề xuất phiên bản sửa đổi trên GitHub (sẽ hướng dẫn cụ thể sau)

  ..
    Ngôn ngữ RST qua ví dụ:
    https://draft-edx-style-guide.readthedocs.io/en/latest/ExampleRSTFile.html
    Cách fork:
    https://help.github.com/en/github/getting-started-with-github/fork-a-repo


.. toctree::
   :hidden:
   :caption: Mục lục
   :titlesonly:

   exhibits/exhibits
   shows/shows
