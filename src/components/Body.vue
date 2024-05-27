<template>

<div class="container mt-5  ">
    <!-- Thanh tìm kiếm -->   
    <div class="container-fluid" >  
      <form class="d-flex" role="search">        
        <input class="form-control me-2" type="search" placeholder="Dịch Vụ Cần Tìm" aria-label="Search">
         <input class="form-control me-2" type="search" placeholder="Địa Chỉ" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Seach</button>
       </form>
    </div>
    <div class="container-fluid" >  
      <table class="table">
      <thead>
       <tr>
         <th scope="col">20.592</th>
         <th scope="col">1.836</th>
         <th scope="col">1.677</th>
         <th scope="col">55.571</th>
       </tr>
       <tr>
         <th scope="col">DOANH NGHIỆP ĐƯỢC KẾT NỐI</th>
         <th scope="col">HỘ KINH DOANH ĐƯỢC KẾT NỐI</th>
         <th scope="col">ĐẠI LÝ THUẾ, KẾ TOÁN DỊCH VỤ</th>
         <th scope="col">NGƯỜI DÙNG</th>
       </tr>
      </thead>
      </table>
    </div>
    <div class="container-fluid" >  
      <table class="table">
      <thead>
       <tr>
         <th  scope="col">
            <img src="C:\Users\vdlinh\source\repos\Vuejs\Day2\First_Project\src\assets\Image\image2.png" 
            alt="Ảnh mô tả" class="img-fluid rounded custom-image">
         </th>
         <th scope="col">
            <h3>Nền tảng kế toán dịch vụ</h3>
            <h5>MISA ASP là nền tảng kế toán dịch vụ giúp kết nối doanh nghiệp, 
                hộ kinh doanh, cá nhân kinh doanh có nhu cầu thuê dịch vụ kế 
                toán với tổ chức cung ứng dịch vụ kế toán, thuế uy tín, chất lượng, 
                chuyên nghiệp trên toàn quốc.
            </h5>
            <button type="button" class="btn btn-success">Nhận Tư Vấn Miễn Phí</button>
        </th>
       </tr>
       
      </thead>
      </table>
    </div>
    <div class="container-fluid" > 
    <h2>Kế toán dịch vụ tiêu biểu</h2>

    </div>  
 </div>

    
</template>

<script>
export default {
  name: 'Body', // Tên của component
};

</script>

<style scoped>
.custom-image {
  /* Đặt kích thước cho hình ảnh */
  width: 1500px;
  height: auto; /* Đảm bảo tỷ lệ hình ảnh không bị méo */
  /* Bo tròn viền của hình ảnh */
  border-radius: 10px;
  /* Thêm độ trong suốt cho hình ảnh */
  opacity: 0.8;
  /* Đặt vị trí của hình ảnh */
  position: relative;
  left: 50%;
  transform: translateX(-50%);
  
  
}

/* Khi con trỏ di chuột qua hình ảnh */
.custom-image:hover {
  opacity: 1; /* Tăng độ trong suốt */
  transform: scale(1.1); /* Phóng to hình ảnh */
}
/* Custom CSS styles */
/* You can add custom styles here */
</style>
