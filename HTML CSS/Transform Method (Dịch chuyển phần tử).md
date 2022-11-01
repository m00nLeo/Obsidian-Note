![[Transform img.png]]

<table style="width: 100%; height: 480px; border-collapse: collapse">
<tbody>
<tr style="height: 38px;">
<td style="text-align: center; height: 38px;"><b>Giá trị</b></td>
<td style="text-align: center; height: 38px;"><b>Mô tả</b></td>
</tr>
<tr style="height: 38px;">
<td style="height: 38px;"><span style="font-weight: 400;">translate(x,y)</span></td>
<td style="height: 38px;"><span style="font-weight: 400;">Di chuyển phần tử dọc theo trục x và trục y</span></td>
</tr>
<tr style="height: 38px;">
<td style="height: 38px;"><span style="font-weight: 400;">translateX(n)</span></td>
<td style="height: 38px;"><span style="font-weight: 400;">Di chuyển phần tử dọc theo trục x</span></td>
</tr>
<tr style="height: 38px;">
<td style="height: 38px;"><span style="font-weight: 400;">translateY(n)</span></td>
<td style="height: 38px;"><span style="font-weight: 400;">Di chuyển phần tử dọc theo trục y</span></td>
</tr>
<tr style="height: 38px;">
<td style="height: 38px;"><span style="font-weight: 400;">scale(x,y)</span></td>
<td style="height: 38px;"><span style="font-weight: 400;">Thay đổi chiều rộng và chiều cao của một phần tử</span></td>
</tr>
<tr style="height: 38px;">
<td style="height: 38px;"><span style="font-weight: 400;">scaleX(n)</span></td>
<td style="height: 38px;"><span style="font-weight: 400;">Thay đổi chiều rộng của một phần tử</span></td>
</tr>
<tr style="height: 38px;">
<td style="height: 38px;"><span style="font-weight: 400;">scaleY(n)</span></td>
<td style="height: 38px;"><span style="font-weight: 400;">Thay đổi chiều cao của một phần tử</span></td>
</tr>
<tr style="height: 38px;">
<td style="height: 38px;"><span style="font-weight: 400;">rotate(angle)</span></td>
<td style="height: 38px;"><span style="font-weight: 400;">Xoay phần tử theo một góc nào đó (angle)</span></td>
</tr>
<tr style="height: 62px;">
<td style="height: 62px;"><span style="font-weight: 400;">skew(x-angle,y-angle)</span></td>
<td style="height: 62px;"><span style="font-weight: 400;">Định dạng phần tử có độ nghiêng theo một góc nhất định</span></td>
</tr>
<tr style="height: 38px;">
<td style="height: 38px;"><span style="font-weight: 400;">skewX(angle)</span></td>
<td style="height: 38px;"><span style="font-weight: 400;">Định dạng phần tử nghiêng một góc theo trục Ox</span></td>
</tr>
<tr style="height: 38px;">
<td style="height: 38px;"><span style="font-weight: 400;">skewY(angle)</span></td>
<td style="height: 38px;"><span style="font-weight: 400;">Định dạng phần tử nghiêng một góc theo trục Oy</span></td>
</tr>
<tr style="height: 38px;">
<td style="height: 38px;"><span style="font-weight: 400;">matrix(n,n,n,n,n,n)</span></td>
<td style="height: 38px;"><span style="font-weight: 400;">Tổng hợp giữa scale, skew và translate</span></td>
</tr>
</tbody>
</table>


## Ứng dụng với [[Position]]
1. **Căn giữa phần tử**
	- Qua trái và xuống 50% của tag Parent và  Transform: translate(-50%) để quay ngược lại 50% của tag Child
		- top: 50%;
		  left: 50%;	
		  transform: translate(-50%, -50%);