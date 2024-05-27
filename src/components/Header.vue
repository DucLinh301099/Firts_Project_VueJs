<template>
<div>
<nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
         <a class="navbar-brand" href="#">
         <img src="C:\Users\vdlinh\source\repos\Vuejs\Day2\First_Project\src\assets\Image\logoAspMisa.png" alt="Your Logo">
         </a>
         <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Tìm Kế Toán</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link active dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dành Cho KTDV
          </a>
          <ul class="dropdown-menu dropdown-menu-end">
           <li><button class="dropdown-item" type="button">Nền Tảng Misa Asp</button></li>
           <li><button class="dropdown-item" type="button">Misa Asp Kế Toán</button></li>
           <li><button class="dropdown-item" type="button">Misa Asp Quản Lý</button></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link active dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dành Cho DN
          </a>
          <ul class="dropdown-menu dropdown-menu-end">
           <li><button class="dropdown-item" type="button">Nền Tảng Misa Asp</button></li>
           <li><button class="dropdown-item" type="button">Misa Asp Kế Toán</button></li>
           <li><button class="dropdown-item" type="button">Misa Asp Quản Lý</button></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link active dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Tin Tức
          </a>
          <ul class="dropdown-menu dropdown-menu-end">
           <li><button class="dropdown-item" type="button">Action</button></li>
           <li><button class="dropdown-item" type="button">Another action</button></li>
           <li><button class="dropdown-item" type="button">Something else here</button></li>
          </ul>
        </li>
        <li class=" nav-item dropdown">
          <a class="nav-link active dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Giới Thiệu Misa Asp
          </a>
          <ul class="dropdown-menu dropdown-menu-end">
           <li><button class="dropdown-item" type="button">Nền Tảng Misa Asp</button></li>
           <li><button class="dropdown-item" type="button">Misa Asp Kế Toán</button></li>
           <li><button class="dropdown-item" type="button">Misa Asp Quản Lý</button></li>
          </ul>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <button class="btn btn-outline-success" type="submit">Đăng Ký</button>
      </form>
      <form class="d-flex" role="search">
        <button class="btn btn-outline-primary" type="submit">Đăng Nhập</button>
      </form>
    </div>
  </div>
</nav>
</div>
  
</template>

<script>
export default {
  name: 'Header', // Tên của component
};
</script>

<style scoped>
/* Thêm CSS tại đây để tạo kiểu cho header và navbar */

.navbar-brand img {
            height: 50px; /* Thiết lập chiều cao là 100px */
            width: auto; /* Đảm bảo tỷ lệ hình ảnh tự động được giữ nguyên */
        }
header {
  background-color: #333;
  color: #fff;
}

nav ul {
  list-style-type: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}
</style>
