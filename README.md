<b>Họ và tên: Nguyễn Minh Quang</b><br><b>Lớp: DHKM18A1HN</b></br><b>MÃ sv: 24174800040</b></br>
<h3><span style="color:black;font-weight:bold"><div style="text-align:center;">Kiểu dữ liệu </div></span></h3>

<h3><span style="color:blue;font-weight:bold"><div style="text-align:center;">Kiểu dữ liệu số nguyên<br>(1 byte = 8 bit)</br></div></span></h3>

Đối với số nguyên ta chia làm <span style="color:red; font-weight:bold">số nguyên không dấu và có dấu</span>, từ số byte lưu trữ ta có thể suy ra <span style="color:red;font-weight:bold">số bit</span> cần để biểu diễn số nguyên đó, quy tắc giá trị của 1 số nguyên.

<br>Giả sử số nguyên có k bit</br>
<br>- Số nguyên có dấu: -2<sup>k-1</sup> tới 2<sup>k-1</sup>-1</br>
<br>- Số nguyên không dấu: 0 tới 2<sup>k</sup>-1</br>

<h3><span style="color:orange;font-weight:bold"><div style="text-align:center;">Kiểu dữ liệu số nguyên</div></span></h3>

<div style="background-color:#f2f2f2; padding:20px; border-radius:6px; width:80%; margin:20px auto;">
<table style="width:100%; border-collapse: collapse; font-family:Arial, sans-serif;">
  <thead>
    <tr>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Kiểu dữ liệu</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Ý nghĩa</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Số byte</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Giải giá trị có thể lưu</th>
    <tr>
  </thead>
</tbody>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>short</b></td>
      <td style="border:1px solid #ccc; padding:10px;">Số nguyên có dấu</td>
      <td style="border:1px solid #ccc; padding:10px;">2 byte</td>
      <td style="border:1px solid #ccc; padding:10px;">-32768 đến 32767</td>
    </tr>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>unsigned short</b></td>
      <td style="border:1px solid #ccc; padding:10px;">Số nguyên không dấu</td>
      <td style="border:1px solid #ccc; padding:10px;">2 byte</td>
      <td style="border:1px solid #ccc; padding:10px;">0 đến 65535</td>
    </tr>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>int</b></td>
      <td style="border:1px solid #ccc; padding:10px;">Số nguyên có dấu</td>
      <td style="border:1px solid #ccc; padding:10px;">4 byte</td>
      <td style="border:1px solid #ccc; padding:10px;">-2147483648 đến 2147483647</td>
    </tr>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>unsigned int</b></td>
      <td style="border:1px solid #ccc; padding:10px;">Số nguyên không dấu</td>
      <td style="border:1px solid #ccc; padding:10px;">4 byte</td>
      <td style="border:1px solid #ccc; padding:10px;">0 đến 4294967295</td>
    </tr>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>long long</b></td>
      <td style="border:1px solid #ccc; padding:10px;">Số nguyên</td>
      <td style="border:1px solid #ccc; padding:10px;">8 byte</td>
      <td style="border:1px solid #ccc; padding:10px;">-9223372036854775808 đến 9223372036854775807</td>
    </tr>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>unsigned long long</b></td>
      <td style="border:1px solid #ccc; padding:10px;">Số nguyên không dấu</td>
      <td style="border:1px solid #ccc; padding:10px;">8 byte</td>
      <td style="border:1px solid #ccc; padding:10px;">0 đến 2<sup>64</sup>-1</td>
    </tr>
  </tbody>
</table>
</div>

<h3><span style="color:orange;font-weight:bold"><div style ="text-align:center;">Kiểu dữ liệu số thực</div></span></h3>

<div style="background-color:#f2f2f2; padding:20px; border-radius:6px; width:80%; margin:20px auto;">
<table style="width:100%; border-collapse: collapse; font-family:Arial, sans-serif;">
  <thead>
    <tr>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Kiểu dữ liệu</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Ý nghĩa</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Số byte</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Giải giá trị có thể lưu</th>
    </tr>
  </thead>
</tbody>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>float</b></td>
      <td style="border:1px solid #ccc; padding:10px;">Số thực độ chính xác đơn</td>
      <td style="border:1px solid #ccc; padding:10px;">4 byte</td>
      <td style="border:1px solid #ccc; padding:10px;">1.17549e-038 đến 3.40282e+038<br>Độ chính xác: 7 chữ số sau dấu phẩy</br></td>
    </tr>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>double</b></td>
      <td style="border:1px solid #ccc; padding:10px;">Số thực độ chính xác kép</td>
      <td style="border:1px solid #ccc; padding:10px;">8 byte</td>
      <td style="border:1px solid #ccc; padding:10px;">2.22507e-308 đến 3.40282e+308<br>Độ chính xác: 15 chữ số sau dấu phẩy</br></td>
    </tr>
  </thead>
</table>
</div>

<h3><span style="color:orange;font-weight:bold"><div style="text-align:center;">Kiểu dữ liệu đúng sai</div></span></h3>

<div style="background-color:#f2f2f2; padding:20px; border-radius:6px; width:80%; margin:20px auto;">
<table style="width:100%; border-collapse: collapse; font-family:Arial, sans-serif;">
  <thead>
    <tr>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Kiểu dữ liệu</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Ý nghĩa</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Số byte</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Giải giá trị có thể lưu</th>
    </tr>
  </thead>
</tbody>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>int</b></td>
      <td style="border:1px solid #ccc; padding:10px;">Kiểu dữ liệu luận lý</td>
      <td style="border:1px solid #ccc; padding:10px;">4 byte</td>
      <td style="border:1px solid #ccc; padding:10px;">1 là đúng<br>0 là sai</br></td>
    </tr>
  </thead>
</table>
</div>

<h3><span style="color:orange;font-weight:bold"><div style="text-align:center;">Kiểu dữ liệu ký tự</div></span></h3>

<div style="background-color:#f2f2f2; padding:20px; border-radius:6px; width:80%; margin:20px auto;">
<table style="width:100%; border-collapse: collapse; font-family:Arial, sans-serif;">
  <thead>
    <tr>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Kiểu dữ liệu</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Ý nghĩa</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Số byte</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Giải giá trị có thể lưu</th>
    </tr>
  </thead>
</tbody>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>char</b></td>
      <td style="border:1px solid #ccc; padding:10px;">Kiểu dữ liệu ký tự</td>
      <td style="border:1px solid #ccc; padding:10px;">1 byte</td>
      <td style="border:1px solid #ccc; padding:10px;">-128 tới 127</td>
    </tr>
  </thead>
</table>
</div>

<h3><span style="color:whiteblack;font-weight:bold"><div style="text-align:center;">Tổng quan về kiểu dữ liệu</div></span></h3>

<div style="background-color:#002147; padding:10px; border-radius:6px;">

<span style="color:yellow;font-weight:bold"><b>/01</b></span><span style="color:white;font-weight:bold"> Kiểu số nguyên có <span style="color:red;font-weight:bold">int</span> và <span style="color:red;font-weight:bold">long long.</span><br>>> Sử dụng long long cho các kết quả số lớn</br></span>

<span style="color:pink;font-weight:bold">/02</span><span style="color:white;font-weight:bold"> Kiểu số thực có <span style="color:red;font-weight:bold">float</span> và <span style="color:red;font-weight:bold">double.</span><br>>> Sử dụng double vì có độ chính xác cao</br></span>

<span style="color:orange;font-weight:bold">/03</span><span style="color:white;font-weight:bold"> Kiểu đúng sai dùng kiểu <span style="color:red;font-weight:bold">int</span></span>

<br><span style="color:beige;font-weight:bold">/04</span><span style="color:white;font-weight:bold"> Kiểu ký tự có<span style="color:red;font-weight:bold"> char.</span></span></br>

</div>

<h3><span style="color:red;font-weight:bold"><div style="text-align:center;">Đặc tả các kiểu dữ liệu chính</div></span></h3>
Trong ngôn ngữ lập trình C, bạn cần nắm được đặc tả của các kiểu dữ liệu. <span style="color:blue;font-weight:bold">Đặc tả đặc biệt quan trọng</span> vì nó giúp các bạn có thể <span style="color:blue;font-weight:bold">nhập giá trị cho biến</span> từ bàn phím và <span style="color:blue;font-weight:bold">in ra giá trị của biến</span> lên màn hình

<div style="background-color:#f2f2f2; padding:20px; border-radius:6px; width:80%; margin:20px auto;">
<table style="width:100%; border-collapse: collapse; font-family:Arial, sans-serif;">
  <thead>
    <tr>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Kiểu dữ liệu</th>
      <th style="border:1px solid #ccc; padding:12px; background-color:#ddd;">Đặc tả tương ứng</th>
    </tr>
  </thead>
</tbody>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>int</b></td>
      <td style="border:1px solid #ccc; padding:10px;">%d</td>
    </tr>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>long long</b></td>
      <td style="border:1px solid #ccc; padding:10px;">%lld</td>
    </tr>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>float</b></td>
      <td style="border:1px solid #ccc; padding:10px;">%f</td>
    </tr>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>double</b></td>
      <td style="border:1px solid #ccc; padding:10px;">%lf</td>
    </tr>
    <tr>
      <td style="border:1px solid #ccc; padding:10px;"><b>char</b></td>
      <td style="border:1px solid #ccc; padding:10px;">%c</td>
  </thead>
</table>
</div>
