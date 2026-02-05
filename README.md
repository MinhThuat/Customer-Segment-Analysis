# 1 Mục tiêu
- Dự án giúp bộ phận Marketing/Sales giảm tỷ lệ khách hàng rời bỏ, tăng doanh thu và đưa ra các chiến dịch phù hợp đối với từng nhóm khách hàng.
- Bộ dữ liệu được lấy từ Kaggle qua đường link: [Brazilian-E-Commerce-Public-Dataset-by-Olist-master](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
## Thông tin về bộ dữ liệu: 
- Bộ dữ liệu bao gồm 9 bảng:
    + olist_customers_dataset: chứa thông tin khách hàng bao gồm mã khách hàng (khóa chính cho bảng order) và mã khách hàng duy nhất (dùng để xác định khách hàng mua lại tại cửa hàng), vị trí của họ, mã zip và trạng thái khách hàng.
    + olist_geolocation_dataset: chứa thông tin về mã zip, tọa độ tương ứng. Dùng để vẽ bản đồ, tìm khoảng cách giữa người bán và người mua.
    + olist_order_items_dataset: chứa thông tin về mặt hàng được mua trong từng đơn hàng.
    + olist_order_payments_dataset: chứa thông tin về thanh toán và phương thức thanh toán của khách hàng.
    + olist_order_reviews_dataset: chứa thông tin về cảm nhận của khách hàng trong từng đơn hàng. Khi khách hàng nhận được sản phẩm họ mua, họ sẽ được nhận 1 email và có thể đánh giá mức độ hài lòng của bản thân.
    + olist_orders_dataset: chứa thông tin về từng đơn hàng .
    + olist_products_dataset: chứa thông tin về các sản phẩm được bán bởi Olist
    + olist_sellers_dataset: chứa thông tin về những người bán đã thực hiện các đơn đặt hàng. trên Olist. Dùng để xác định vị trí của người bán và xác định ai đã bán từng sản phẩm.
    + product_category_name_translation: Dịch tên sản phẩm ra tiếng anh.

- Lược đồ quan hệ giữa các bảng:
[Schema](data/Brazilian-E-Commerce-Public-Dataset-by-Olist-master/schema.png)
