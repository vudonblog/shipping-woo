# shipping-woo

Shipping Delivered Woocommerce
Hiển thị Delivered cho từng danh mục cụ thể
Copy đoạn code vào funtions.php của childen themes
chú ý muốn hiển thị thêm cho danh mục nào thì chỉ việc copy cụm 

//áp dụng cho 1 danh mục
if (has_term('apparel','product_cat')) 
		{	
			$songayxulymin=5; 	
			$songayxulymax=7;
			$songayshipmin=7; 
			$songayshipmax=10;
		}
		
//áp dụng ̀cho danh mục apparel hoặc danh mục father
if (has_term('apparel','product_cat')||has_term('father','product_cat')) 
		{
			$songayxulymin=5; 
			$songayxulymax=7;
			$songayshipmin=7; 
			$songayshipmax=10;
		}
	
dán vào sau cụm if tiếp đó rồi thay apparel bằng tên đường dẫn của danh mục đó chỉnh sửa ngày theo ý và lưu lại.
