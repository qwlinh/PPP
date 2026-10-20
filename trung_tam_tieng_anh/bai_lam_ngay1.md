# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Vũ Quốc Linh
- **Lớp:** CNTT1
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** windows

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)
```shell
pwd
ls -force
mv lich_hoc.txt docs
mv anh_lop_hoc.jpg media
cp .\media\logo_trung_tam.PNG .\archive\
rm temp_201.tmp
rm temp_202.tmp
cd logs
ls
cd ..
cd docs
cp ../media/anh_lop_hoc.jpg ../archive
cd ..
```

### Kết quả B1 (pwd)
```text
Path
----
PS C:\Users\linhs\Downloads\starter-kit\trung_tam_tieng_anh

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text

    Directory: C:\Users\linhs\Downloads\starter-kit\trung_tam_tieng_anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
dar---        10/20/2026   3:02 PM                archive
dar---        10/20/2026   3:02 PM                data
dar---        10/20/2026   3:02 PM                docs
dar---        10/20/2026   2:40 PM                logs
dar---        10/20/2026   3:03 PM                media
-a----        10/19/2026  10:04 AM             83 .env
-a----        10/19/2026  10:04 AM            902 bai_lam_ngay1.md


    Directory: C:\Users\linhs\Downloads\starter-kit\trung_tam_tieng_anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   3:01 PM          13559 anh_lop_hoc.JPG
-a----        10/20/2026   1:34 PM           5184 logo _trung_tam.PNG


    Directory: C:\Users\linhs\Downloads\starter-kit\trung_tam_tieng_anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   1:40 PM           5070 hoc_vien_khoa_3.xlsx


    Directory: C:\Users\linhs\Downloads\starter-kit\trung_tam_tieng_anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   1:41 PM             67 lich_hoc.txt

    Directory: C:\Users\linhs\Downloads\starter-kit\trung_tam_tieng_anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   1:42 PM           1072 access.log


    Directory: C:\Users\linhs\Downloads\starter-kit\trung_tam_tieng_anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   1:33 PM          13559 anh_lop_hoc.JPG
-a----        10/20/2026   1:34 PM           5184 logo_trung_tam.PNG

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**