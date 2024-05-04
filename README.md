# Next Word Prediction

## Datasets
- datasets.zip - Tập dữ liệu gồm 8 chủ đề:
  - **Chinh tri Xa Hoi** gồm có 6.567 bài báo
  - **Doi song** gồm có 4.195 bài báo.
  - **Kinh doanh** gồm có 4.276 bài báo.
  - **Phap luat** gồm có 6.656 bài báo.
  - **Suc khoe** gồm có 4.417 bài báo.
  - **The gioi** gồm có 5.716 bài báo.
  - **The thao** gồm có 5.667 bài báo.
  - **Van hoa** gồm có 5.250 bài báo.
- preprocessing_datasets.zip - Tập dữ liệu đã được tiền xử lý từ datasets.zip:
  - Bỏ đi các dấu câu bao gồm !"#$%&'()*+, -./:;<=>?@[\\]^_`{|}~
  - Chuyển tất cả các ký tự hoa thành ký tự thường.
  - Loại bỏ các ký tự trắng liên tiếp.
  - Mỗi câu được ghi trên mỗi hàng riêng biệt và không có dấu . ở cuối câu.
  - Loại bỏ những bài báo nào có thẻ html.