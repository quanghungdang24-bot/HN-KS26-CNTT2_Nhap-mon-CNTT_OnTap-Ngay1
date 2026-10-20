# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Đặng Quang Hưng
- **Lớp:** CNTT2
- **Link repository:**
- **Hệ điều hành (Windows/macOS):** macOS

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
pwd
ls -a
mv lich_hoc.txt docs/
mv logo_trung_tam.png media/
mv anh_lop_hoc.jpg media/
cp media/logo_trung_tam.png archive/
rm temp_201.tmp
rm temp_202.tmp
cd ./logs
ls
cd ..
cd ./docs
cp ../media/anh_lop_hoc.jpg ../archive/
cd ..
```

### Kết quả B1 (pwd)

```text
/Users/hung/Documents/starter-kit/trung-tam-tieng-anh
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
.                       .DS_Store               archive                 data                    logs
..                      .env                    bai_lam_ngay1.md        docs                    media

./archive:
.                       ..                      anh_lop_hoc.jpg         logo_trung_tam.png

./data:
.                       ..                      hoc_vien_khoa_3.xlsx

./docs:
.               ..              .DS_Store       lich_hoc.txt

./logs:
.               ..              access.log

./media:
.                       ..                      .DS_Store               anh_lop_hoc.jpg         logo_trung_tam.png

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
