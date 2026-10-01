# Lịch sử cập nhật

## 2026-10-01

- Sửa lỗi Chrome báo thiếu thao tác người dùng khi chọn file HTML gốc: mở hộp chọn ngay trong lần bấm, không chặn bằng hộp xác nhận trước đó.
- Tách chọn file và cấp quyền ghi thành hai lần bấm. Chọn file chỉ liên kết, chưa ghi dữ liệu; bấm “Cho phép ghi / Lưu ngay” mới xin quyền ghi và lưu dữ liệu đã được máy chủ xác nhận.
- Giữ cảnh báo dữ liệu riêng trên màn hình, bảo vệ khi đổi tài khoản, hủy chọn file hoặc chọn nhầm file. Không thay đổi dữ liệu chấm công, phân quyền hoặc mẫu Word.

## 2026-09-30

- Cập nhật bản 65: bắt buộc đăng nhập; dữ liệu được kiểm soát quyền đọc và ghi trên máy chủ, đồng bộ chung theo thay đổi từng dòng và phát hiện xung đột.
- Giữ các chức năng chấm công, tăng ca, báo cáo, phép và xuất tài liệu; cập nhật bộ xuất Word DOCX giữ bố cục mẫu in.
- Bổ sung mục riêng cho quản lý để liên kết file HTML gốc trên PC và lưu dữ liệu đã đồng bộ vào file sau khi được cấp quyền. Chỉ tự lưu khi chương trình đang mở; dừng khi file bị sửa từ nơi khác hoặc mất quyền ghi.
- Có tải HTML kèm dữ liệu, tải bản trước lần ghi và trích dữ liệu nhúng ra JSON. Các bản chứa dữ liệu là bản riêng, không dùng làm file phát hành công khai.
- Mã website công khai không chứa dữ liệu chấm công, mật khẩu hoặc phiên đăng nhập. Dữ liệu hiện có được giữ nguyên trên máy chủ và thiết bị.

## 2026-09-02

- Bảng tổng hợp tháng: đổi tên cột “Giờ công” thành “Tổng giờ công” trên màn hình, bản in/PDF và file Excel.
- Tổng giờ công nay được tính bằng giờ công thường cộng toàn bộ giờ tăng ca OT 150%, OT 200% và OT 300%; các cột OT riêng vẫn được giữ để đối chiếu.
- Bảng tổng hợp tháng: Tổng ngày làm việc nay cộng cả ngày Chủ nhật và ngày lễ/Tết khi nhân viên có bản ghi chấm công làm việc hợp lệ.
- Giữ nguyên cách tính giờ công thường và phân loại giờ tăng ca 200%/300%, tránh cộng trùng giờ OT vào giờ công thường.

## 2026-08-31

- Bảng chấm công tháng: chuyển khu vực ký Quản lý sang bên trái, giữ tên Lê Văn Quang dưới chức danh; chuyển Người lập bảng sang bên phải trên màn hình, bản in/PDF và file Excel.
- Bảng tổng hợp chấm công: áp dụng cùng thứ tự ký Quản lý bên trái và Người lập bảng bên phải trên bản in/PDF và file Excel.
- Phiếu xin nghỉ phép: bổ sung chọn tháng và danh sách các lần nghỉ của từng nhân viên; các ngày nghỉ liên tiếp được gom thành một lần, ngày nghỉ riêng được tính là một lần và sắp từ đầu tháng đến cuối tháng.
- Khi chọn một lần nghỉ, chương trình tự điền Từ ngày, Đến ngày, tổng số ngày, lý do và loại nghỉ để in Phiếu.
- Nhân viên đã nghỉ việc vẫn xuất hiện trong danh sách in Phiếu nếu có dữ liệu nghỉ trước ngày nghỉ việc; dữ liệu từ ngày nghỉ việc trở đi không được đưa vào danh sách in.

## 2026-08-05

- Phiếu OT riêng của Lê Văn Quang: thu cột Ngày tăng ca từ 22% xuống 18% và nới mỗi cột giờ của Kế hoạch tăng ca từ 8% lên 10%.
- Giữ “Kế hoạch tăng ca”, “Từ giờ” và “Đến giờ” trên một dòng để tiêu đề bảng cân đối hơn.
- Đổi dòng tổng hợp tháng thành “Danh sách CB CNV đề nghị tăng ca: ....... CB CNV”.
- Bổ sung tên Huỳnh Ngọc Giang dưới vị trí ký Giám đốc Ban SX; giữ tên Lê Văn Quang dưới Người đề nghị.
- Phiếu OT riêng của Lê Văn Quang: để trống toàn bộ cột Tổng thời gian, chỉ điền Ngày tăng ca, Từ giờ và Đến giờ.
- Phiếu OT riêng của Lê Văn Quang: mỗi khoảng thời gian tăng ca được in trên một dòng riêng; nếu cùng ngày có nhiều khung giờ thì ngày đó được lặp lại tương ứng để dễ theo dõi.

## 2026-08-03

- Khắc phục lỗi không mở được bản in Phiếu OT riêng của Lê Văn Quang trên iPhone và một số cấu hình Chrome.
- Cửa sổ in nay được mở ngay khi người dùng bấm In Phiếu OT, sau đó mới nạp mẫu và toàn bộ dữ liệu tăng ca của Lê Văn Quang trong tháng đã chọn.
- Bổ sung thông báo hướng dẫn khi trình duyệt chặn cửa sổ bật lên; giữ nguyên luồng in Phiếu OT của các nhân viên khác.
- Bổ sung nút “In Phiếu OT Lê Văn Quang” hoạt động độc lập, không cần tích chọn nhân viên trong danh sách theo ngày.
- Phiếu riêng dùng tháng của ngày đang chọn, gom các khung giờ theo từng ngày và liệt kê đầy đủ ngày, giờ bắt đầu, giờ kết thúc cùng tổng giờ tăng ca theo mẫu Giấy đề nghị tăng ca chung.
- Nút In Phiếu OT chung trở lại đúng chức năng in theo ngày/khung giờ đã tích, kể cả khi chọn Lê Văn Quang.

## 2026-08-02

- Nhật ký/Dữ liệu: chuẩn hóa sáu nút thao tác cùng chiều rộng, chiều cao, cỡ chữ và đặt trên một hàng; màn hình nhỏ hỗ trợ vuốt ngang thay vì xuống dòng.
- Nhật ký/Dữ liệu: thay bộ lọc khoảng ngày bằng lựa chọn năm và đủ 12 tháng trong năm.
- Khi mở chương trình, bảng chi tiết chỉ hiển thị dữ liệu tháng hiện tại; dữ liệu tháng đã qua chỉ xuất hiện khi người dùng chọn đúng tháng.
- Bổ sung trạng thái tháng và số dòng đang xem, nút Về tháng hiện tại; tìm kiếm và bản in Nhật ký/Dữ liệu dùng cùng tháng đã chọn.

## 2026-08-01

- Bảng công tháng: bổ sung lựa chọn xuất Excel hoặc PDF và nút Xuất file; Excel giữ đầy đủ ngày, dữ liệu chấm công/tăng ca và nền xanh nhạt của Chủ nhật.
- Bảng tổng hợp tháng: bổ sung lựa chọn xuất Excel hoặc PDF và nút Xuất file; file Excel chỉ chứa bảng tổng hợp đang xem.
- Khi chọn PDF, chương trình mở bản xem trước A4 ngang để người dùng lưu thành PDF hoặc in trên iPhone và PC.

## 2026-07-21

- Đưa Bảng công tháng lên trên Bảng tổng hợp tháng trong tab Tổng hợp tháng.
- Bổ sung nút mũi tên mở/thu gọn độc lập cho từng bảng; cả hai bảng mặc định thu gọn và chỉ hiện nội dung khi người dùng bấm mở.
- Nhân viên đã có Ngày nghỉ việc không còn xuất hiện trong mục chọn nhanh nhân viên của Chấm công hằng ngày và Tăng ca, kể cả khi đang xem ngày chấm công cũ.
- Nhân viên nghỉ việc được loại khỏi danh sách chọn khi in Phiếu xin nghỉ phép; nếu đang được chọn thì biểu mẫu tự động xóa lựa chọn đó.
- Dữ liệu chấm công, tăng ca và nghỉ phép trước ngày nghỉ việc vẫn được giữ nguyên để tra cứu và tổng hợp lịch sử.
- Bổ sung Bảng công tháng trong Tổng hợp tháng, hiển thị đầy đủ ngày và thứ theo tháng được chọn, lấy dữ liệu trực tiếp từ Chấm công hằng ngày.
- Mỗi nhân viên có dòng Công thường và Tăng ca; riêng Lê Văn Quang chỉ có một dòng Tăng ca. Các cột Chủ nhật được tô nền xanh nhạt.
- Bổ sung mã nghỉ trên bảng công, mẫu in A4 khổ ngang và khu vực ký Người lập bảng/Quản lý ở cuối bảng.

## 2026-07-17

- Bổ sung mục Nhân viên nghỉ việc trong Cài đặt với Họ tên, Vị trí và Ngày nghỉ việc.
- Từ ngày nghỉ việc, nhân viên tự động được ẩn khỏi danh sách chấm công và tăng ca hằng ngày; dữ liệu lịch sử không bị xóa.
- Tổng hợp tháng tự ghi chú “Nghỉ việc từ ngày …” và vẫn giữ nguyên ngày công, giờ công, tăng ca, nghỉ phép trước đó.
- Chấm công hằng ngày: bổ sung nút Sửa cạnh Xóa cho từng dòng tăng ca; cho phép cập nhật nhân viên, ngày, khung giờ, thời gian trừ, lý do và ghi chú mà không tạo dòng trùng.
- Tổng hợp tháng: chuyển mẫu in sang A4 khổ ngang, cân lại độ rộng các cột và nới cột Nghỉ/Công tác/Đào tạo cùng cột Ghi chú.

## 2026-07-15

- Phiếu xin nghỉ phép: rút phần ý kiến của Trưởng bộ phận, Giám đốc ban và Phòng Nhân sự xuống còn đúng một dòng chấm cho mỗi mục.
- Phiếu xin nghỉ phép: thu gọn khoảng cách giữa các dòng thông tin và dòng ý kiến, đồng thời tăng vùng trống ký tên dưới bốn chức danh.

## 2026-07-13

- Khôi phục đầy đủ chương trình chấm công từ file gốc và phát hành trên GitHub Pages.
- Bổ sung công cụ khôi phục dữ liệu cũ an toàn, không xóa dữ liệu hiện có.
