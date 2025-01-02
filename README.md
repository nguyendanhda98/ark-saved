Quy trình tải toàn bộ file (bao gồm file lớn) vào máy khác
Clone repository như bình thường:

bash
Copy code
git clone https://github.com/username/repository.git
cd repository
Cài đặt Git LFS trên máy mới (nếu chưa cài):

bash
Copy code
git lfs install
Tải các file lớn được quản lý bởi Git LFS:

bash
Copy code
git lfs pull
