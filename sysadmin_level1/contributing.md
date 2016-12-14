## Quy định viết ghi chú commit

Ban đầu sẽ có có cảm giác khó khăn, nhưng các thành viên có gắng tuân thủ nhé :+1:

1. Tạo thư mục con tương ứng với tên Task như yêu cầu trong phần **Mô tả Task**. Định dạng thường là `TaskXX_Ten_Task_cu_the`. Tạo tệp báo cáo trong thư mục đó, đặt tên `README.md`. Định dạng tệp báo cáo theo **Mẫu quy định**.

2. Đối với báo cáo có hình ảnh, gom tất cả hình ảnh vào thư mục `Images`, `images`, `img`, đặt trong thư mục của Task hiện tại. Đánh số hình ảnh tăng dần `[so-thu-tu].[phan-duoi-tep]`. Ví dụ: tên thư mục là `Images`, tên hình ảnh là `1.jpg`, thì liên kết tham chiếu trong `README.md` sẽ là `Images/1.jpg`.

3. Định dạng ghi chú commit: `[bieu-tuong] [hanh-dong] [ten-file-thay-doi]`. Ví dụ: `:pill: Fix README.md` (hiển thị ":pill: Fix README.md"). 

4. Sử dụng ghi chú **hành động** như sau: 
	* `Add new files` khi lần đầu commit hoặc khi upload thêm file mới.
	* `Update [ten-file-thay-doi]` khi thay đổi bất kỳ trên một file.
	* `Update some files` khi thay đổi bất kỳ trên nhiều files mà không upload file mới.
	* `Fix [ten-file-thay-doi]` khi sửa chữa các lỗi trên một file.
	* `Delete some files` khi xóa file hoặc folder bất kỳ.

5. Sử dụng các **[biểu tượng đi kèm](http://www.emoji-cheat-sheet.com/)** như sau :
	* :memo: | `:memo:` khi lần đầu commit hoặc khi làm việc với `README.md`.
	* :floppy_disk: | `:floppy_disk:` khi bổ sung các tài nguyên như văn bản, mã nguồn, hình ảnh.
	* :link: | `:link:` khi bổ sung link mới vào phần `Tài liệu tham khảo`.
	* :pill: | `:pill:` khi sữa chữa các lỗi.
	* :fire: | `:fire:` khi xóa file hoặc folder.

**Một số ví dụ:**

* Lần đầu tạo folder Task mới và tạo file `README.md`, dùng `:memo: Add new files` (hiển thị ":memo: Add new files").
* Upload 1 file `.pdf, .php, .jpg, ...`, dùng `:floppy_disk: Add new files` (hiển thị ":floppy_disk: Add new files").
* Làm việc với `README.md`, như nhập dữ liệu, thay đổi, ..., dùng `:memo: Update README.md` (hiển thị ":memo: Update README.md").
* **Thay đổi một lúc nhiều files**, dùng `:memo: Update some files` (hiển thị ":memo: Update some files").
* Xóa 1 file bất kỳ, dùng `:fire: Delete some files` (hiển thị ":fire: Delete some files").
* Bổ sung link vào phần Tài liệu ham khảo, dùng `:link: Update README.md` (hiển thị ":link: Update README.md").
* Sửa chữa các lỗi (thường do Team lead thực hiện), dùng `:pill: Fix [ten-file-sua-chua]` (hiển thị ":pill: Fix [ten-file-sua-chua]").

**Chỉ cần nhớ hai cái này là dùng nhiều nhất:**

* Lần đầu commit thường dùng `:memo: Add new files` (hiển thị ":memo: Add new files"). Upload thêm files thì thay biểu tượng thành `:floppy_disk:` (:floppy_disk:).
* Sau khi đã thay đổi một số thứ, dùng `:memo: Update some files` (hiển thị ":memo: Update some files").


---

Quy định được tạo bởi: **Hà Văn Toàn**.
