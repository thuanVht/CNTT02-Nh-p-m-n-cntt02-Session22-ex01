# Bài 1 : Tìm kiếm tài liệu học tập chính thống bằng Google
 Viết một chuỗi truy vấn (Query) sử dụng toán tử **filetype:**, **site:** và dấu ngoặc kép " " để tìm trực tiếp tệp tin PDF trên máy chủ của trường.
 "site:ptit.edu.vn filetype:pdf Nhập môn Công nghệ Thông tin"
| Thành phần | Tác dụng |
|---|---|
| `site:ptit.edu.vn` | Chỉ tìm trong máy chủ chính thức của trường, nên không lẫn web quảng cáo hay web nạp thẻ |
| `filetype:pdf` | Chỉ trả về tệp PDF, không trả về trang bài viết |
| `"Nhập môn Công nghệ Thông tin"` | Dấu ngoặc kép buộc Google khớp đúng nguyên cụm từ, không tách rời từng chữ |

1 "Nhập môn Công nghệ Thông tin"	Dấu ngoặc kép buộc Google khớp đúng nguyên cụm từ, không tách rời từng chữ
 Sử dụng toán tử trừ **-** để loại bỏ ít nhất 2 trang web "rác" thường xuyên xuất hiện trong kết quả tìm kiếm.
- "site:ptit.edu.vn filetype:pdf Nhập môn Công nghệ Thông tin -site:scribd.com -site:123docz.net -site:tailieu.vn"
 Mô tả tại sao việc dùng toán tử **filetype:** lại giúp tiết kiệm thời gian hơn so với việc gõ "tải sách..." thông thường.
2 Vì sao filetype: tiết kiệm thời gian hơn gõ “tải sách...”?
- Lọc theo định dạng thật của tệp, không theo từ khóa. Cụm “tải sách…” khiến Google trả về các trang có chứa chữ đó, và đa số là web SEO, quảng cáo, trang đếm ngược rồi bắt nạp thẻ. filetype:pdf chỉ trả về đúng tệp PDF.
- Mở thẳng tài liệu. Bạn không phải đi qua trang trung gian, các nút “Download” giả hay popup quảng cáo.
- An toàn hơn. Các trang “tải sách” thường chèn nút tải giả dẫn đến mã độc hoặc phần mềm quảng cáo. Một tệp PDF nằm trên máy chủ .edu.vn có độ tin cậy cao hơn nhiều.
- Kết quả gọn. Danh sách ngắn và đúng loại tài liệu, nên bạn không phải lọc qua hàng chục trang không liên quan.
