


# Hướng Dẫn Chạy Scripts
## Di chuyển đến thư mục chứa script
cd ..
cd .\scripts

## Chạy file script tự động báo cáo
.\auto_report.ps1
## Checklist kiểm tra thiết bị

-   [x] Kiểm tra kết nối mạng và cảm biến tại trạm 
    
-   [ ] Xác thực quyền truy cập và file cấu hình `.env` ẩn
    
-   [ ] Chạy file script tự động hóa 

|ma_linh_kien|ten_thiet_bi|don_gia |loai_storage|
| :-: | :-: |:-: | :-: |
| LK01 | pberRasry Pi 4 Model B|  1,450,000 | SSD |
| LK02 | Intel NUC i3          |  6,200,000 | SSD |
| LK03 | Orange Pi 5           |  2,300,000 | SSD |
| LK04 | Dell Optiplex Micro   |  5,400,000 | HDD |
| LK05 | Mini PC Fanless N100  |  4,200,000 | SSD |
| LK06 | Synology DS220j NAS   |  3,900,000 | HDD |

## Chức năng lọc log
- Input: các file văn bản chứa dữ liệu log hệ thống mà chương trình cần đọc vào
- Process: để quét qua từng dòng, giữ lại các dòng chứa từ khóa quan trọng như từ khóa ERROR 
- Output: danh sách các dòng lỗi đã được lọc sạch, hiển thị trực tiếp lên màn hình
## DIKW
- D: dữ liệu thô (b)
- I: nhận biết (c)
- K:  có suy nghĩ (d)
- W: khả năng đưa ra quyết định (a)
