<div> 
 <h2>  『君の名は。』    </h2>

    <p>
        （きみのなは、英 : Your Name.) は、新海誠が監督・脚本を務めた2016年の日本のアニメーション映画。主演 （声の出演） は神木隆之介と上白石萌音。作画監督は安藤雅司、キャラクターデザインは田中将賀が務めた。
    </p>
    
    <h2>RANDOM: 作画監督は安藤雅司</h2>
 </div>

CSS: https://www.w3schools.com/cssref/css_selectors.php

# [[Specificity CSS (Độ ưu tiên CSS)]]
- Tham khảo

# Main CSS
 1. div p {}
	- css tất cả các thẻ p trong thẻ div
	<style>
		div p{
			color: red;
		}
	</style>

2. div > p {}
	- css tất cả các thẻ p ==khi và chỉ khi ba nó là div==

3. div + p {}
	- css cho thẻ p ==đầu tiên== ngay sau (div)(/div) kết thúc
	<div>
	</div>
	<p>Lorem</p>

4. :nth-child()
	- thường được sử dụng để xử lý các Item có điều kiện thứ tự cố định trong danh sách có.
	<ul>
	    <li>Item đầu tiên</li>
	    <li>Item thứ 2</li>
	    <li>Item thứ 3</li>
	    <li>Item thứ 4</li>
	    <li>Item thứ 5</li>
	    <li>Item thứ 6</li>
	    <li>Item thứ 7</li>
	    <li>Item thứ 8</li>
	    <li>Item cuối cùng</li>
	</ul>
5. h2:first-child {}
	- css h2 là ==child đầu tiên== trong số nhiều h2 thuộc thẻ cha <div>
	<style>
		h2:first-child{
			color: blue;
		}
	</style>





