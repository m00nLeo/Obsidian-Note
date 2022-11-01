1. Quy định các viết ==Quy chuẩn==
	- Gọi tên class:
	<div class="navbar">
      <ul class="nav-list">
        <li class="nav-item">
          <a href="#" class="nav-link active">STAR</a>
        </li>
        
        <li class="nav-item">
          <a href="#" class="nav-link">TV SHOW</a>
        </li>

        <li class="nav-item">
          <a href="#" class="nav-link">CINÉ</a>
        </li>
      </ul>
    </div>
2. Có vài tag sẽ không có tính thừa kế [[Inhentance (Sự thừa kế)]]  từ cha nó như thẻ a
	   - Nên ghi thẳng class của tag đó như .nav-link {} hoặc .nav-item a {}

3. Trường hợp nhiều các phần tử con có cùng một class mà chỉ muốn CSS một phần tử duy nhất [[Specificity CSS (Độ ưu tiên CSS)]]
	- Apply nhiều class cho phần tử đó --> class="nav-link active"
	- CSS--> .nav-link.active{}

4. Thay đổi hiệu ứng khi di chuột vào
	- a:hover{}