# Mindmap dòng thời gian Memnet

Tài liệu này là bản mindmap chữ của thế giới *No One's Memory*. Cấu trúc chia làm 3 lớp:

Graph thuần liên kết nằm tại [Mindmap.json](./Mindmap.json). File JSON chỉ chứa `id`, `file`, và `relationships` giữa các node; không chứa tóm tắt nội dung.

| Lớp | Mục đích | Đường dẫn |
| --- | --- | --- |
| Trục chính | Nhìn nhanh toàn bộ dòng thời gian và quan hệ giữa các node | [Mindmap.md](./Mindmap.md) |
| Tóm tắt sự kiện | Mỗi mốc lớn có một file riêng để đọc nhanh | [Timeline/](./Timeline/) |
| Chi tiết node | Giải thích nhân vật, tổ chức, công nghệ, địa điểm, khái niệm | [Nodes/](./Nodes/) |

## Sơ đồ tổng

| Node gốc | Node con | Ý nghĩa trong truyện | Tài liệu liên quan |
| --- | --- | --- | --- |
| Thế giới trước 2050 | Ký ức số hóa, Cloud Memory, pre-Memlink | Tạo nền cho sự lệ thuộc vào lưu trữ ngoài não | [Pre-Collapse.md](./Timeline/Pre-Collapse.md), [Memory-Digitization.md](./Nodes/Memory-Digitization.md) |
| Đại Sụp Đổ 13/04/2050 | GMV lỗi đồng bộ, empty overwrite, mất trắng dữ liệu | Biến cố khai sinh toàn bộ bối cảnh và nỗi ám ảnh tập thể | [Great-Fallen-2050.md](./Timeline/Great-Fallen-2050.md), [Great-Fallen.md](./Nodes/Great-Fallen.md) |
| Kỷ nguyên trắng ký ức | Khủng hoảng danh tính, xã hội rơi vào trạng thái rỗng | Giải thích vì sao ký ức trở thành tài nguyên chính trị | [White-Memory-Era.md](./Timeline/White-Memory-Era.md), [White-Memory-Era.md](./Nodes/White-Memory-Era.md) |
| Hình thành Memnet 2052-2066 | Cognitive Survivalists, Memlink, MIC, luật quản lý ký ức | Nhân loại dựng lại trật tự bằng hệ thống kiểm soát ký ức | [Memnet-Rise-2052-2066.md](./Timeline/Memnet-Rise-2052-2066.md), [Memnet.md](./Nodes/Memnet.md), [Memlink.md](./Nodes/Memlink.md), [MIC-Zone.md](./Nodes/MIC-Zone.md) |
| Thời đại Memnet 2066-2074 | Kiểm duyệt ký ức, tự xóa ký ức, lỗi ký ức, người không kết nối | Bối cảnh vận hành thường nhật của thế giới hiện tại | [Controlled-Memory-Era-2066-2074.md](./Timeline/Controlled-Memory-Era-2066-2074.md), [Memory-Erasure.md](./Nodes/Memory-Erasure.md), [Unlinked.md](./Nodes/Unlinked.md) |
| Điểm khởi phát truyện 2074 | Bạch Phong, Quân Lăng, ký ức vô chủ, MIC Zone 4, chợ đen | Mở chuỗi điều tra trung tâm của cốt truyện | [Story-Trigger-2074.md](./Timeline/Story-Trigger-2074.md), [Bach-Phong.md](./Character/Bach-Phong.md), [Quan-Lang.md](./Character/Quan-Lang.md), [Ownerless-Memory.md](./Nodes/Ownerless-Memory.md), [Dark-Memory-Market.md](./Nodes/Dark-Memory-Market.md) |
| Tương lai dự báo | Sụp đổ lần hai, sự thật về Đại Sụp Đổ, tái hợp hai hệ thống | Đích đến triết lý và xung đột cuối cùng | [Future-Projection.md](./Timeline/Future-Projection.md), [Seiromemdas.md](./Character/Seiromemdas.md), [Mnemonic-Shard.md](./Nodes/Mnemonic-Shard.md) |

## Dòng thời gian rút gọn

| Giai đoạn | Mốc chính | Hệ quả |
| --- | --- | --- |
| 2030-2049 | Công nghệ ghi nhớ ngoài não phát triển mạnh | Trí nhớ tự nhiên bị thay thế dần |
| 13/04/2050 | Đại Sụp Đổ xóa sạch ký ức số hóa toàn cầu | Thế giới mất lịch sử, danh tính, dữ liệu nền |
| 2050-2052 | Kỷ nguyên trắng ký ức | Xã hội hỗn loạn và ám ảnh bởi nguy cơ quên sạch |
| 2052-2066 | Nhóm Cognitive Survivalists xây Memnet | Ký ức trở thành hạ tầng sinh tồn mới |
| 2066 | Memnet vận hành toàn cầu | Ký ức bị quản lý như tài nguyên nhà nước |
| 2068-2074 | Lỗi, kiểm duyệt, tự xóa ký ức tăng dần | Niềm tin vào tính toàn vẹn của hệ thống bắt đầu rạn |
| 2074 | Bạch Phong phát hiện ký ức vô chủ | Truyện chính khởi động |
| 2075-2080 | Nguy cơ sụp đổ lần hai và lựa chọn cuối cùng | Xung đột giữa kiểm soát, tự do, và ký ức thật |

## Luồng quan hệ giữa các node

```text
Ký ức số hóa cực độ
-> Đại Sụp Đổ
-> Kỷ nguyên trắng ký ức
-> Cognitive Survivalists tạo Memnet
-> Memlink + MIC + quản trị ký ức toàn cầu
-> Kiểm soát xã hội bằng ký ức
-> Lỗi ký ức / ký ức vô chủ / người tự xóa ký ức
-> Bạch Phong điều tra
-> Chợ đen ký ức + Mnemonic Shard + Seiromemdas
-> Hé lộ sự thật về Đại Sụp Đổ và tương lai của Memnet
```

## Gợi ý cách dùng

| Nhu cầu | Nên đọc |
| --- | --- |
| Muốn nhìn nhanh toàn bộ trục truyện | File này |
| Muốn tách từng mốc sự kiện lớn | Thư mục [Timeline](./Timeline/) |
| Muốn tra cứu từng khái niệm hoặc nhân vật | Thư mục [Nodes](./Nodes/) |
