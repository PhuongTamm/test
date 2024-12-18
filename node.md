# commands
+git init: biến thư mục thành một git-repo
+ git add .: lưu dự án tại thời điểm đó, tạm thời
sau đó dùng + git commit -m 'ghi chú': quan trọng (phải git add . Trước)
+ git log: xem lịch sử commit (id nằm ở cột đầu)
+ git log --oneline: xem lịch sử (dạng ngắn hơn)
+ git checkout 'id git': để quay về git đã thực hiện lưu trước đó 
+ git checkout master: trở về git được lưu gần nhất
+ git checkout -b 'tên nhánh': tạo nhánh cho repo
+ git branch: xem các nhánh ở vị trí đứng
+ git merge 'tên nhánh': gom code từ các nhánh khác về master (nhớ checkout master - chuyển về nhánh master trước)
+ git branch -d 'tên nhánh': xoá nhánh
+ git push <tên đường dẫn> <tên nhánh>
