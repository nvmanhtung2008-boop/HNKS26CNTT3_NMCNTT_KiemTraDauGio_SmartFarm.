


# Hệ thống giám sát trạm cảm biến nông trại
> Hướng dẫn chạy script
```PowerShell
.\auto_report.ps1
```
## Thiết bị
- [x] Raspberry Pi 4 Model B
- [ ] Intel NUC i3
- [ ] Orange Pi 5

## Bảng thông số phần cứng
| Tên | Đơn giá | Loại storage|
|:---|:---|:---|
|Raspberry Pi 4 Model B | 1,450,000| SSD|
| Intel NUC i3|6,200,000 | SSD|
| Orange Pi 5|2,300,000 | SSD|

## Phân tích hệ thống 
	
### Phần 1
Input của chức năng lọc log là dữ liệu trong file `log-he-thong.log`
		Process là xử lí, lọc các từ cần tìm như "critical, error"
		Output là kết quả cuối cùng được đưa ra ở `bao-cao-tong-su-co.txt`
### Phần 2
Phát biểu được sắp xếp theo DIKW lần lượt là: `b`, `c`, `d`, `a`



