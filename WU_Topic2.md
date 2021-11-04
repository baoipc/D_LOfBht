<!DOCTYPE html>
<html>
<body>
    <p><h1>Topic: function,array(1d and 2d),string,struct</h1></p>
    <p><h2>I.Hàm</h2></p>
    <p id ="first">
        <h3>1.Khái niệm</h3>
        <p>một tính năng rất quan trọng trong hầu hết các ngôn ngữ lập trình, nó giúp lập trình viên tạo ra những đoạn code có tính kế thừa, giúp việc phát triển và bảo trì dễ dàng hơn</p>
        <h3>2.Các loại hàm trong C++</h3>
        <ul>
            <li>
                Hàm định nghĩa sẳn, hay còn gọi là thư viện hàm.
            </li>
            <li>Hàm do người dùng tự định nghĩa.Có 2 loại: hàm trả về kết quả, hàm không trả về kết quả
                <ul>
                    <li>Hàm không có giá trị trả về</li>
                    <li>Hàm có giá trị trả về</li>
                </ul>
            </li>
        </ul>
        <h3>3.Cú pháp khai báo hàm</h3>
        <ul>
            <li>return_type</li>
            <li>function_name</li>
            <li>parameter list</li>
            <li>statement(s)</li>
        </ul>
        <h3>4.Cách viết</h3>
        <ul>
            <li>Hàm có giá trị trả về</li>
            <li>Hàm không có giá trị trả về</li>
            <li>Hàm không có tham số</li>
            <li>Hàm có tham số</li>
        </ul>
        <h3>5.Truyền đối số cho hàm</h3>
        <ul>
            <li>Truyền đối số là giá trị</li>
            <li>Truyền đối số là tham chiếu</li>
            <li>Truyền đối số là địa chỉ</li>
        </ul>
        <h2>Vài thứ hay ho trong lúc tìm hiểu</h3>
        <ul>
            <li>gán giá trị khởi tạo cho tham số trong hàm</li>
            <li>Tham số hằng: const giá_trị tên_biến , khi tác động đến biến sẽ báo lỗi</li>
            <li>Overloading: dùng hàm cùng tên nhưng khai báo khác kiểu dữ liệu trả về</li>
        </ul>
        <p><h2>II.Mảng</h2></p>
        <p><h3>1.Mảng 1 chiều</h3></p>
        <p><h4>a.Khái niệm</h4></p>
        <p>- Một kiểu dữ liệu có cấu trúc do người lập trình định nghĩa.</p>
        <p>- Biểu diễn một dãy các biến có cùng kiểu. Ví dụ: dãy các số nguyên, dãy các ký tự</p>
        <p>- Kích thước được xác định ngay khi khai báo và không bao giờ thay đổi (mảng tĩnh)</p>
        <p style="font-color:red;">=>C++ luôn chỉ định <b>một khối nhớ liên tục</b> cho một biến kiểu mảng.</p>
        <p><h3>b.Cú pháp</h3></p>
        <p><h4>Khai báo</h4></p>
        <p>Kiểu_dữ_liệu Tên_biến_mảng[số phần tử]</p>
        <p>Phải xác định <số phần tử> cụ thể (hằng số) khi khai báo</p>
        <p>Một mảng liên tục có chỉ số từ 0 đến <tổng số phần tử> - 1</p>
        <p>Bộ nhớ sử dụng = <tổng số phần tử> * sizeof(<kiểu cơ sở>)</p>
        <p>Khởi tạo giá trị cho mảng:</p>
        <ul>
            <li>Khởi tạo giá trị cho mọi phần tử của mảng</li>
            <li>Khởi tạo giá trị cho một số phần tử đầu mảng</li>
            <li>Khởi tạo giá trị 0 cho mọi phần tử của mảng</li>
            <li>Tự động xác định số lượng phần tử</li>
        </ul>
        <p><h4>Nhập dữ liệu</h4></p>
        <p>Tên_biến_mảng[chỉ_số]=giá_trị</p>
        <p><h4>Xuất các phần tử</h4></p>
        <p>Tên_biến_mảng[chỉ_số]</p>
    </p>
</body>
</html>
