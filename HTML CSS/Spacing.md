## Padding
1. Định dạng Short: "padding: top right bottom left;"
	- padding: 10px 20px 30px ; 
		- top: 10px right: 20px bottom: 30px left: 20px

2. Là khoảng cách từ Border tới Content

## Margin
1. Định dạng Short: "margin: top right bottom left;"

2. Là khoảng cách giữa các element với nhau: như text with video with imgage....

3. ==Overlapping Margin==
	- Các element khi margin sẽ bị đè margin lên nhau
		- Rule giải quyết: Spacing Margin bằng cách chỉ margin-bottom mà không margin-top

4. Default (giá trị mặc định) margin cho cả left và right là 0 -> default là căn trái
	- CSS căn phải: **`margin-left: auto`**
	- CSS căn giữa: **`margin-right: auto`** + **`margin-left: auto`**

5. Trong các [[Position]], KHÔNG thể áp dụng Margin

## Border
1. Định dạng gốc
	- border-color: ;
	   border-width: ;
	   border-style: ;

2. Short: "border: (color) (width) (style) ;"

## Box-sizing
1. box-sizing: border-box
	- Sử dụng khi padding và border tràn quá kích cỡ chiều ngang màn hình
		- Giảm độ rộng của content để các thành phần gồm content, padding, border vừa fit với chiều ngang màn hình

2. box-sizing: content-box 
	- Set kích cỡ chiều ngang dựa theo phần content --> có thể khiến tràn viền màn hình