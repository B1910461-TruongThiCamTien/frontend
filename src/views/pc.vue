<template>
<h1>Bảng lương</h1>
<div>
    <table border="2">
        <tr>
            <th rowspan="2">STT</th>
            <th rowspan="2">Họ tên</th>
            <th colspan="2">Giới tính</th>
            <th rowspan="2">Chức vụ</th>
            <th rowspan="2">Mức lương</th>
        </tr>
        <tr>
            <th>Nam</th>
            <th>Nữ</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Trương Thị Cẩm Tiên</td>
            <td></td>
            <td>X</td>
            <td>Trưởng Phòng</td>
            <td>10 triệu/tháng</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Ho Thi B</td>
            <td></td>
            <td>X</td>
            <td>Phó Phòng</td>
            <td>8 triệu/tháng</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Nguyễn Văn A</td>
            <td>X</td>
            <td></td>
            <td>Tổ viên</td>
            <td>6 triệu/tháng</td>
        </tr>
        <tr>
            <td>4</td>
            <td>Tiên Trương</td>
            <td></td>
            <td>X</td>
            <td>Tổ viên</td>
            <td>6 triệu/tháng</td>
        </tr>
    </table>
</div>
</template>

<script>
export default {
    name: 'pc',
}

</script>

<style>
h1{
    margin: auto;
}
tr,td,th{
    padding: 10px;
}
</style>
