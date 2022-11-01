![[Position Image Example.png]]

## **Static**
- Đây được xem là giá trị hiển thị Position trong css một cách mặc định (default), các thành phần sẽ nằm theo thứ tự của văn bản. 
	- Không thể CSS 4 thuộc tính: ***Top Right Bottom Left** và **Z-Index**

## **Relative**
- Định vị trí tuyệt đối cho các thành phần, không gây ảnh hưởng tới vị trí ban đầu hay các thành phần khác.
	- Căn từ Static (được hiểu là default) là vị trí ban đầu của object
	- ==Phụ thuộc vào chính bản thân nó==

## **Absolute**
- Xác định các thuộc tính phụ thuộc vào thẻ cha của nó
	- Thuộc tính absolute xác định định tọa độ của thành phần theo một thẻ cha **`RELATIVE`** (**_nếu có_**)
		- Nếu không có thẻ cha thì nó sẽ đi theo body của toàn trang web.
		- Chỉ có thể set Relative và phụ thuộc và thẻ cha của nó  
			- KHÔNG set và phụ thuộc những tag cùng hàng

## **Fixed** 
Định vị và giúp cho phần tử luôn cố định một chỗ, ví dụ như khi bạn scroll trình duyệt chẳng hạn, phần tử sẽ không thay đổi.

## **Inherit** 
Xác định thừa hưởng thuộc tính từ thành phần cha (thành phần bao ngoài).