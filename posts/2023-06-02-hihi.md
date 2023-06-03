
### TỔNG RAMANUJAN: 1 + 2 + 3 + ⋯ + ∞ = -1/12?
#### Mark Dodds
=========
> “Con đang nói cái quái gì vậy? Thứ này không thể nào đúng được đâu!” — Mẹ tôi

Bà đã nói như vậy khi tôi kể về phương trình toán học kỳ lạ này. Và đơn giản, ấy là một phương trình bất thường. Thực sự thì, nó đã biến logic cơ bản thành trò hề mà. Làm sao mà khi cộng những số nguyên dương với nhau, ta không chỉ nhận được một số âm mà còn là một phân số âm cơ chứ? Phân số đó là gì?
Trước khi tôi nói tiếp: Khi kể cho tôi nghe về điều này, người ta đã bảo rằng lúc đó từ ‘tổng’ không còn mang nghĩa thông thường nữa. Bởi lẽ mọi chuỗi số tôi gặp thường không hội tụ tới một con số cụ thể nào cả, vì thế chúng ta sẽ nói về một loại tổng khác, có tên gọi là Tổng Cesàro. Nói thêm tới bất kỳ ai hứng thú với toán học thì, tổng Cesàro sẽ gán các giá trị cho một vài chuỗi số không hội tụ theo nghĩa thông thường. “Tổng Cesàro được định nghĩa là giới hạn của dãy trung bình cộng của n tổng riêng đầu tiên của một chuỗi khi n tiến tới vô cùng” — Wikipedia. Tôi cũng muốn nói rằng trong suốt bài này, tôi sẽ chỉ dùng khái niệm vô hạn đếm được thôi, đó là một loại vô hạn liên quan tới tập hợp có vô hạn các số hạn mà nếu có đủ thời gian, bạn sẽ đếm được tới bất kỳ con số nào trong tập ấy. Nhờ vậy tôi có thể sử dụng một số tính chất thông thường của toán học trong các phương trình của mình như tính giao hoán chẳng hạn (tôi sẽ dùng mệnh đề này trong suốt bài viết).
Nếu bạn chưa quen với chuỗi số có tên gọi Tổng Ramanujan thì, nó được đặt tên theo một nhà toán học nổi tiếng người Ấn Độ là Srinivasa Ramanujan. Tổng này chỉ ra rằng nếu cộng tất cả các số tự nhiên lại với nhau, 1, 2, 3, 4, vv, cho đến vô cùng thì, ta sẽ nhận được kết quả là -1/12. Vầng, -0,08333333333 đó.
> ζ(-1) = 1 + 2 + 3 + 4 + ..... = -1/12

Không tin tôi ư? Cứ đọc tiếp để nhìn cách tôi làm nhé, tôi sẽ chứng minh hai mệnh đề điên không kém đâu:
> 1. 1 – 1 + 1 – 1 + 1 – 1 ⋯ = 1/2

> 2. 1 – 2 + 3 – 4 + 5 – 6 ⋯ = 1/4

Đầu tiên, phải chuẩn bị trước đã. Phép màu đích thực sắp xảy ra rồi này, thực tế thì ta không chứng minh được hai mệnh đề kia mà không có đoạn này đâu.
Tôi sẽ bắt đầu với một chuỗi số A, bằng 1 – 1 + 1 – 1 + 1 – 1 được lặp lại vô số lần. Tôi viết nó dưới dạng:
> A = 1 – 1 + 1 – 1 + 1 – 1⋯

Và thực hiện một kỹ thuật nhỏ. Ta lấy 1 trừ đi A nhé
> 1 – A = 1 - (1 – 1 + 1 – 1 + 1 – 1⋯)

Mọi chuyện diễn ra rất suôn sẻ đúng không? Và đoạn cao trào đây này. Nếu giản lược vế phải của phương trình, tôi sẽ có một thứ rất hay ho:
> 1 – A = 1 – 1 + 1 – 1 + 1 – 1 + 1⋯

Trông quen không nào? Nếu bạn đã quên mất rồi thì, đó chính là A đấy. Vâng, vế phải của phương trình chính là chuỗi số ta có ban đầu. Vì thế tôi có thể thay vế phải bằng A và làm vài trò đại số trung học đơn giản và rồi bùm!
> 1 - A = A

> 1 – A + A = A + A

> 1 = 2A

> 1/2 = A

Phương trình xinh xắn này chính là chuỗi Grandi, được đặt tên theo nhà toán học, triết gia và linh mục người Ý Guido Grandi. Đấy là tất cả nội dung của những chuỗi số này, tôi cực thích luôn ấy, dù chẳng có lịch sử cực kỳ ngầu hay những câu chuyện hấp dẫn gì đằng sau đâu. Tuy vậy, nó đã mở ra cánh cửa để ta chứng minh rất nhiều những thứ hấp dẫn khác, bao gồm cả một phương trình quan trọng trong cơ học lượng tử và thậm chí là lý thuyết dây nữa kia. Nhưng ấy là chuyện về sau. Giờ thì, ta sẽ chứng minh tiếp 2 nào: 1 – 2 + 3 – 4 + 5 – 6⋯ = 1/4.
Bắt đầu như trên tôi, đã đặt chuỗi B = 1 – 2 + 3 – 4 + 5 – 6⋯. Và giờ ta bắt đầu nghịch ngợm chút được rồi. Lần này, thay vì lấy 1 trừ cho B, ta sẽ lấy A trừ B và thu được:
> A - B = (1 – 1 + 1 – 1 + 1 – 1⋯) — (1 – 2 + 3 – 4 + 5 – 6 ⋯)

> A - B = (1 – 1 + 1 – 1 + 1 – 1⋯) — 1 + 2 – 3 + 4 – 5 + 6⋯

Ta sẽ đổi chỗ các số hạng một chút, và thấy nhiều quy tắc thú vị xuất hiện.
> A - B = (1 – 1) + (–1 + 2) + (1 – 3) + (–1 + 4) + (1 – 5) + (–1 + 6)⋯

> A - B = 0 + 1 – 2 + 3 – 4 + 5⋯

Và lại một lần nữa, ta có được chuỗi số mình đặt ra từ đầu, và ở trên kia, ta đã chứng minh được A = 1/2, vì thế ta dùng thêm một chút kiến thức đại số cơ bản và thu được mệnh đề kinh ngạc thứ hai này.
> A - B = B

> A = 2B

> 1/2 = 2B

> 1/4 = B

Ô kìa! Phương trình này không có cái tên mỹ miều nào cả, vì nhiều nhà toán học đã chứng minh được trong nhiều năm rồi, nó vẫn luôn được coi là một nghịch lý toán học. Đã có tranh luận nảy lửa trong giới học thuật vào khoảng thời gian đó liên quan đến phương trình này dù nó đã góp phần mở rộng nghiên cứu của Euler về bài toán Basel và tạo ra các hàm số quan trọng như hàm Zeta Reimann.
Giờ thì đến đoạn thăng hoa mà bạn vẫn chờ đợi này. Ta lại đặt chuỗi C = 1 + 2 + 3 + 4 + 5 + 6⋯, và bạn có thể đoán được đấy, ta sẽ lấy B trừ đi C.
> B - C = (1 – 2 + 3 – 4 + 5 – 6⋯) - (1 + 2 + 3 + 4 + 5 + 6⋯)

Và toán học vẫn chưa hết tuyệt vời đâu, ta sẽ sắp xếp lại thứ tự một vài số hạng để tạo ra thứ gì đấy quen quen, nhưng có thể không phải cái mà bạn đang ngờ đâu.
> B - C = (1 - 2 + 3 - 4 + 5 - 6⋯) - 1 - 2 - 3 - 4 - 5 - 6⋯

> B - C = (1 - 1) + (-2 - 2) + (3 - 3) + (-4 - 4) + (5 - 5) + (-6 - 6) ⋯

> B - C = 0 - 4 + 0 - 8 + 0 - 12⋯

> B - C = -4 - 8 - 12⋯

Không ngờ đúng không? Nhưng cứ chờ tiếp đi, vẫn còn một vài chiêu cuối khiến mọi thứ đáng xem đây nè. Nếu bạn có để ý một xíu thì, từng số hạng ở vế phải đều là bội của -4, ta sẽ tách nhân tử đó ra, và nhìn xem, lại xuất hiện phương trình ban đầu nè.
> B - C = -4(1 + 2 + 3)⋯

> B - C = -4C

> B = -3C

Và vì đã tính được B = 1/4, nên ta chỉ việc thế vào phương trình trên thôi:
> 1/4 = -3C

> 1/-12 = C hay C = -1/12

Giờ thì, lý do gì khiến phương trình trên quan trọng tới vậy. Với người chưa biết thì, nó được dùng trong lý thuyết dây đó. Không may là chẳng phải thứ Stephen Hawking vẫn dùng đâu, nhưng phần lý thuyết dây ban đầu lại nhắc đến nó (Lý thuyết Dây Boson). Hơi buồn khi lý thuyết dây Boson hiện đã trở nên lỗi mốt bởi chuyên ngành được ưa thích hiện nay có tên gọi lý thuyết dây siêu đối xứng, song lý thuyết dây ban đầu ấy vẫn rất hữu ích trong việc thấu hiểu các siêu dây (superstring) - phần không thể thiếu trong lý thuyết dây hiện đại mà ta vừa nhắc đến.
Tổng Ramanujan cũng có ảnh hưởng lớn tới vật lý đại cương, đặc biệt là trong cách lý giải hiện tượng có tên gọi là Hiệu ứng Casimir. Hendrik Casimir đã dự đoán rằng đối với hai tấm kim loại không tích điện được đặt trong chân không sẽ tồn tại lực hấp dẫn do sự hiện diện của các loại hạt được tạo ra từ dao động lượng tử. Trong lý giải của Casimir, ông đã sử dụng chính tổng ta vừa chứng minh để mô hình hóa năng lượng giữa hai tấm kim loại. Còn nhiều lý do khác khiến giá trị này lại quan trọng đến thế.
Vì thế, bạn hiểu tổng Ramanujan rồi đấy, ổng khám phá ra hồi đầu những năm 1900 cơ. Và tới 100 năm sau nó vẫn có ảnh hưởng lên nhiều ngành vật lý, và vẫn có thể thắng cược được những người chưa hiểu được chuyện gì đang xảy ra.
P.S. Nếu bạn vẫn thấy hứng thú và muốn tìm hiểu thêm, thì có một cuộc đối thoại giữa hai nhà vật lý giải thích phương trình điên rồ này và quan điểm của họ về tác dụng cũng như giá trị của nó. Rất đẹp, rất ngắn gọn và hấp dẫn nữa.
Bài luận này là một phần trong chuỗi các câu chuyện liên quan tới nhiều chủ đề toán học, được đăng trong Cantor’s Paradise ra hàng tuần trên Medium. Cảm ơn bạn đã đọc!
