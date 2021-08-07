# GAN_model
GAN model with new technologies

B1. Chạy lần lượt các code cell để thực hiện liên kết drive cá nhân (tạo sẵn thư mục Kaggle trong My Drive),mục 
upload file sẽ upload file kaggle.json đã download sẵn từ api kaggle cá nhân, sau đó chạy code cell download data
VN_celeb theo link. Nếu bị lỗi không thấy file json thì có thể mở mục file bên trái colab,tìm đến folder gdrive/Kaggle
và upload trực tiếp file kaggle.json vào đó.


B2.Thực hiện unzip sau khi tải xong data, cd đến /content. Sau đó upload file DiffAugment_tf.py vào thư mục chính content,
bố cục folders và files như hình ảnh bên dưới.


B3.Chạy model. Có thể chạy theo 2 hướng dùng diff_augment hoặc không,mặc định dùng diff_augment,chi tiết về việc lựa chọn
ở dòng chú thích bên trong code cell #2 lines below for non-diffAugment .
![image](https://user-images.githubusercontent.com/46078489/128594081-e615ec90-de4b-41b0-a467-a9245def6a17.png)
