# convert-xls-to-csv
Cách chuyển file từ định dạng Excel sang CSV trên Linux

## Chương trình bảng tính Gnumeric
Gnumeric không có mặt theo mặc định trong kho lưu trữ của centos 7 của bạn, trước tiên bạn phải cài đặt bản phát hành lux mới nhất.
Đầu tiên tải về:
```
wget http://repo.iotti.biz/CentOS/7/noarch/lux-release-7-1.noarch.rpm
```

Tiếp theo là cài đặt repo:
```
rpm -Uvh lux-release-7-1.noarch.rpm
```

Cài đặt Gnumberic:
```
yum install gnumeric -y
```

Câu lệnh để chuyển file:
```
ssconvert file_can_chuyen.xlsx file_moi.csv
```

*Minh Tân Lê*
