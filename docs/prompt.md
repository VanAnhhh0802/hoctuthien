Dự án Học Từ Thiện. Dự án có luồng hoạt động như sau.

Mentee (Người học), sẽ đăng ký vào hệ thống. Sau khi đăng ký, để tránh tài khoản rác, người học sẽ chuyển khoản 10k sang bên Thiện Nguyện App để kích hoạt tài khoản, và xác nhận tài khoản (vì thông tin lấy từ Thiện Nguyện App có thể xác minh chuyển khoản của 1 người).
Sau khi Mentee kích hoạt tài khoản, thì Mentee có thể đặt lịch học với Mentor, với giá mà Mentor quy định. Sau khi kết thúc buổi học với Mentor, nếu buổi học có chi phí, Mentee cần thanh toán hết, chuyển khoản sang bên Thiện Nguyện App thì mới được đăng ký tiếp buổi học tiếp theo.

Mentee khi muốn trở thành Mentor thì sẽ đăng ký thành Mentor, Mentor vẫn có vài trò của Mentee.
Mentee có thể xem được lịch sử dạy và lịch trống của Mentor. Mentee có thể xem được lịch sử học tập của bản thân. Mentee có thể xem thành tích đứng đầu trong tháng của Mentor và Mentee khác.

Mentor có Profile riêng để điền các thông tin và lĩnh vực muốn giảng dạy, hỗ trợ, chia sẻ.
Mentor có thể chọn số tài khoản của bên App Thiện Nguyện để khi Mentee thanh toán sẽ hiển thị lên.

Hệ thống Thiện Nguyện App là một hệ thống của MBBank, cung cấp tài khoản 4 số, dùng để hỗ trợ mục đích thiện nguyện. Thiện Nguyện App cho phép người dùng đăng ký tài khoản 4 số, và tạo chiến dịch với mã cú pháp để trong nội dung để phân luồng dòng tiền vào từng chiến dịch. Nếu không khớp nội dung chiến dịch nào, dòng tiền sẽ đi vào chiến dịch mới nhất.
Nội dung giao dịch để bảo mật, bên Thiện Nguyện App có mã hoá nếu như có 3 số liên tiếp nằm cuối 1 dãy số dài, thì sẽ bị đổi thành xxx. Vậy nên khi gửi nội dung từ thiện của hệ thống với cú pháp HOCTUTHIEN KICHHOAT ABCXYZ, hoặc HOCTUTHIEN UNGHO BCEDFG, thì các mã giao dịch sẽ chỉ là ký tự chữ, tránh số sẽ bị ẩn hệ thống không kiểm tra tự động được.
Vì Thiện Nguyện App không bắn WebHook về hệ thống HocTuThien, nhưng có API cung cấp gọi để kiểm tra giao dịch dựa vào số tài khoản (ví dụ: 2000, 1111), từ đó có thể đối chiếu thông tin khi người dùng bấm chuyển khoản thành công.

Khi hiển thị quét mã, sẽ tạo mã động dựa trên VietQR để tự động điền tài khoản, số tiền và nội dung cú pháp để tránh người dùng tự nhập dẫn đến sai sót (cũng hiển thị thông tin bên dưới mã QR để hỗ trợ người dùng Copy).
