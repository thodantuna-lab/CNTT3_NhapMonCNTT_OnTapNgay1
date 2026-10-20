# BÀI LÀM – ÔN TẬP NGÀY 1

- **Trần Minh Quân:**
- **CNTT3**
- **Link repository:**
- **Hệ điều hành (Windows/macOS):**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh> pwd
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh> ls -r
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh> mv .\trung-tam-tieng-anh\Lich_Hoc.txt .\trung-tam-tieng-anh\docs\
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh> mv .\Logo_Trung_Tam.PNG,.\Anh_Lop_Hoc.JPG .\media\
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh> cp .\media\Logo_Trung_Tam.PNG .\archive\
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh> rm .\temp_201.tmp
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh> rm .\temp_202.tmp
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh> cd .\logs\
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\logs> ls
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\logs> cd ..
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh> cd .\docs\PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\docs> cp ..\media\Anh_Lop_Hoc.JPG ..\archive\
PS C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\docs> cd ..
```

### Kết quả B1 (pwd)

```text
 Directory:
    C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   5:44 PM                trung-tam-tieng-a
                                                  nh
------        10/19/2026  10:04 AM            902 bai_lam_ngay1.md


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng
    -anh\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   5:39 PM                archive
d-----        10/20/2026   5:39 PM                data
d-----        10/20/2026   5:39 PM                docs
d-----        10/20/2026   5:40 PM                logs
d-----        10/20/2026   5:39 PM                media
------        10/19/2026  10:04 AM             83 .env
-a----        10/19/2026  10:04 AM          13559 Anh_Lop_Hoc.JPG
-a----        10/19/2026  10:04 AM            902 bai_lam_ngay1.md
-a----        10/19/2026  10:04 AM             67 Lich_Hoc.txt
-a----        10/19/2026  10:04 AM           5184 Logo_Trung_Tam.PN
                                                  G
------        10/19/2026  10:04 AM             22 temp_201.tmp
------        10/19/2026  10:04 AM             22 temp_202.tmp


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng
    -anh\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           5070 Hoc_Vien_Khoa_3.x
                                                  lsx


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng
    -anh\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           1072 Access.log

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text

    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   5:54 PM                archive
d-----        10/20/2026   5:39 PM                data
d-----        10/20/2026   5:47 PM                docs
d-----        10/20/2026   5:40 PM                logs
d-----        10/20/2026   5:50 PM                media
-a----        10/19/2026  10:04 AM             83 .env
-a----        10/19/2026  10:04 AM            902 bai_lam_ngay1.md


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM          13559 Anh_Lop_Hoc.JPG
-a----        10/19/2026  10:04 AM           5184 Logo_Trung_Tam.PNG


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           5070 Hoc_Vien_Khoa_3.xlsx


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM             67 Lich_Hoc.txt


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           1072 Access.log


    Directory: C:\Users\admin\Downloads\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM          13559 Anh_Lop_Hoc.JPG
-a----        10/19/2026  10:04 AM           5184 Logo_Trung_Tam.PNG

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
