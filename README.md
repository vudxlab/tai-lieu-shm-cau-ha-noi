# Bộ tài liệu tham khảo về SHM cầu Hà Nội

Kho này tổng hợp, kiểm kê và đánh giá tài liệu cho nhiệm vụ:

> **Nghiên cứu xây dựng khung kiến trúc tổng thể của hệ thống đánh giá sức khỏe công trình cầu trọng điểm của thành phố Hà Nội.**

## Kết quả hiện tại

Danh mục gốc gồm **70 mục**, chia thành 8 nhóm A–H:

- **37/70 mục (52,9%)**: đã có đầy đủ toàn văn theo tiêu chí nghiêm ngặt.
- **38/70 mục (54,3%)**: nếu tính thêm C3, do OGC 20-082r4 được xác nhận có nội dung kỹ thuật đồng nhất với ISO 19156:2023, trừ trang nhãn hiệu và bản quyền.
- **5 mục**: mới có một phần tài liệu thành phần.
- **19 mục**: cần mua bản chính thức.
- **8 mục**: đã xác định nguồn nhưng bị chặn tải, yêu cầu đăng ký, thư viện hoặc thao tác thủ công.
- **70/70 mục**: đã xác định nguồn, phạm vi và tình trạng tiếp cận.

Tỷ lệ được tính theo **mục tài liệu**, không phải số file. Một mục có thể bao gồm nhiều phần, phụ lục, tiêu chuẩn hoặc bộ dữ liệu.

## Cấu trúc kho

```text
├── README.md                         # Tổng quan và hướng dẫn sử dụng
├── 00_DANH_MUC_GOC.docx             # Danh mục tài liệu ban đầu
├── DANH_GIA_TRUOC_KHI_MUA.md        # Đánh giá 22 tài liệu thương mại
├── DEEP_RESEARCH_REPORT.md           # Kết quả nghiên cứu sâu và trạng thái từng mục
├── BAO_CAO_THU_THAP.md               # Báo cáo thu thập ban đầu
├── manifest.csv / manifest.json      # Danh mục máy đọc được
├── collection_report.json            # Báo cáo thu thập có cấu trúc
├── DEEP_RESEARCH_REPORT.json         # Kết quả nghiên cứu sâu có cấu trúc
├── deep_commercial.json              # Hồ sơ chi tiết tài liệu thương mại
└── files/
    ├── A/  Phân cấp rủi ro và quản lý cầu
    ├── B/  Hướng dẫn kỹ thuật SHM
    ├── C/  Chuẩn dữ liệu và kiến trúc
    ├── D/  Ngưỡng cảnh báo và phân tích dữ liệu
    ├── E/  Chương trình quan trắc và nghiên cứu điển hình
    ├── F/  Văn bản pháp luật và tiêu chuẩn Việt Nam
    ├── G/  Định mức và chi phí
    ├── H/  Tiêu chuẩn hệ thống và quản lý tài sản
    └── PREVIEW/  Bản xem trước và tài liệu tương đương để đánh giá mua
```

## Nên đọc theo thứ tự

1. `README.md` — tổng quan.
2. `DEEP_RESEARCH_REPORT.md` — trạng thái mới nhất của từng mục.
3. `DANH_GIA_TRUOC_KHI_MUA.md` — tài liệu nào nên mua trước, mua sau hoặc chưa cần mua.
4. `files/PREVIEW/UU_TIEN_MUA.md` — danh sách mua ngắn gọn.
5. `00_DANH_MUC_GOC.docx` — danh mục gốc của nhiệm vụ.

## Giải thích trạng thái

- `downloaded_complete` — đã có đủ toàn văn của các thành phần được nêu trong mục.
- `downloaded_partial` — đã có file nhưng chưa đủ mọi thành phần.
- `open_text_identical_equivalent` — có đặc tả mở được cơ quan phát hành xác nhận đồng nhất về nội dung kỹ thuật.
- `purchase_required` — cần mua bản chính thức hoặc giấy phép sử dụng.
- `source_found_download_blocked_or_manual` — đã có nguồn nhưng cần đăng ký, thư viện, tài khoản hoặc tải thủ công.

## Tài liệu nên mua trước

1. **UNI/TR 11634:2026** — thiết kế và vận hành hệ thống quan trắc kết cấu.
2. **ISO/IEC/IEEE 42010:2022** — phương pháp mô tả kiến trúc hệ thống.
3. **ISO 55001:2024** — yêu cầu đối với hệ thống quản lý tài sản.
4. **JT/T 1037-2022** — quy phạm hệ thống SHM cầu đường bộ của Trung Quốc.
5. **ISO 13822:2010** — đánh giá kết cấu hiện hữu; kiểm tra tình trạng sửa đổi trước khi mua.
6. **TCVN 11823**, ưu tiên Phần 1, 3 và 4.
7. **ISO/IEC 27002:2022** — thiết kế biện pháp kiểm soát an toàn thông tin.
8. **ISO 13824:2020** — quy trình đánh giá và xử lý rủi ro kết cấu.

## Những tài liệu có thể hoãn mua

- **ISO 19156:2023:** có thể dùng OGC 20-082r4 để nghiên cứu nội dung; chỉ mua nếu hồ sơ bắt buộc viện dẫn bản mang nhãn ISO.
- **ISO 55002:2018:** đang có rủi ro chuyển phiên bản; tạm dùng IAM Anatomy v4 và hướng dẫn BSI về ISO 55001:2024.
- **ISO 17359:** có tính khái quát cho máy móc, giá trị bổ sung trực tiếp cho SHM cầu không cao.
- **UNI EN 16991:** có thể hoãn nếu khung kiểm tra dựa trên rủi ro đã được đáp ứng bằng Linee Guida Ponti và ISO 13824.
- **Sách Farrar & Worden:** nên mượn thư viện hoặc mua sách cũ trước khi mua mới.

## Lưu ý bản quyền và trích dẫn

- Kho này phục vụ nghiên cứu nội bộ và kiểm kê tài liệu.
- Bản xem trước, bài báo diễn giải và tài liệu tương đương không thay thế bản tiêu chuẩn chính thức khi nghiệm thu hoặc áp dụng yêu cầu quy phạm.
- Không tái phân phối tiêu chuẩn thương mại nếu giấy phép không cho phép.
- Khi sử dụng tài liệu chính thức, phải ghi đúng số hiệu, phiên bản, amendment/corrigendum, cơ quan ban hành và URL nguồn.
- Mỗi tài liệu giữ nguyên quyền tác giả và giấy phép của đơn vị phát hành; kho này không áp dụng một giấy phép chung cho các file của bên thứ ba.

## Cảnh báo phiên bản

- Mua **UNI/TR 11634:2026**, không mua nhầm bản 2016 cho triển khai mới.
- Dùng **ISO/IEC/IEEE 42010:2022**, không dùng bản 2011 làm chuẩn hiện hành.
- Dùng **ISO/IEC 25010:2023**; nội dung chất lượng khi sử dụng đã chuyển sang ISO/IEC 25019:2023.
- ISO/IEC 27001:2022 cần đối chiếu **Amendment 1:2024**.
- MBEI hiện hành cần đủ interim revisions 2022, 2024 và 2025.
- Kiểm tra trạng thái ISO 13822, ISO 13824 và ISO 2394 ngay trước khi đặt mua.

## File lớn không đưa lên GitHub

`files/A/A9_FHWA-NHI-23-024_BIRM_2023.pdf` có kích thước khoảng 120 MB, vượt giới hạn 100 MB của GitHub nên bị loại khỏi Git. Nguồn chính thức:

- Trang tài liệu: https://rosap.ntl.bts.gov/view/dot/71829
- File PDF: https://rosap.ntl.bts.gov/view/dot/71829/dot_71829_DS1.pdf

## Quy trình mua minh bạch

1. Liên kết mỗi tài liệu với công việc hoặc sản phẩm cụ thể của nhiệm vụ.
2. Kiểm tra phiên bản, amendment, corrigendum và trạng thái hiệu lực.
3. Ghi rõ vì sao tài liệu mở hiện có chưa đáp ứng.
4. Xin báo giá từ nhà phát hành hoặc VSQI.
5. Lưu quyết định mua, hóa đơn, giấy phép và phạm vi được chia sẻ.
6. Ghi đúng phiên bản đã mua trong báo cáo và hồ sơ nghiệm thu.
