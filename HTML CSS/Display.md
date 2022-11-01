https://viblo.asia/p/gioi-thieu-thuoc-tinh-display-trong-css-924lJ2X6lPM
### Inline
- Kích thước bằng đúng phần content's width 
- Không apply được width và height
- Có thể apply padding và margin
	- Nhận chỉ số padding và margin ở cả 4 vị trí --> Nhưng ==Chỉ bị ảnh hưởng và đẩy phần left và right==
	- Áp dụng cho hều hết các thuộc tính ==text và image==

1. span
2. a
3. button
4. ==img== (dù rằng vẫn apply được width và height)

### Block
- Kích thước bằng 100% phần tử cha nó
- Có thể apply width và height
- Có thể apply padding và margin
1. div
2. p
3. h1-h6

### CSS Display: inline-block

Giá trị `inline-block` của thuộc tính `display` là sự kết hợp của `inline` và `block`. Kiểu `display: inline-block` sẽ được sắp xếp giống với kiểu `display: inline`, nghĩa là các items sẽ được xếp cùng nhau trên một dòng. 
Tuy nhiên, các phần tử này cũng giống như các phần tử `block` ở chỗ bạn có thể thay đổi chiều rộng và chiều cao của chúng bằng CSS.

- Khi muốn chuyển các Block thành *==**Inline nhưng vẫn muốn chỉ được width, height, padding, margin***==
	- :inline-block

1. ==KHÔNG thể CSS text-aligin cho tất cả các tag "Block"==


# CSS Display
1. display:  
	- Flex : Để chia các element trong một "block" vào 1 hàng
	- Block : Để đóng các element thành 1 khối cố định
		- Flex và Block thường dùng kèm Justify-content --> https://hocwebchuan.com/tutorial/css3/display-flex.php
		- 

2. display: inline-block --> ngăn không cho các thành phần tràn ô xuống dòng