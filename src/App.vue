<script setup>
</script>

<template>

<!-- 
  justify-content-start: căn trái
  justify-content-center: căn giữa
  justify-content-end: căn phải
  justify-content-between
  justify-content-around
  justify-content-evenly
-->
<!-- <div class="d-flex justify-content-evenly">
  <div style="width: 200px; height: 200px;" class="bg-danger"></div>
  <div style="width: 200px; height: 200px;" class="bg-success"></div>
  <div style="width: 200px; height: 200px;" class="bg-info"></div>
  <div style="width: 200px; height: 200px;" class="bg-warning"></div>
</div> -->

  <nav class="navbar navbar-expand-lg" style="background-color: #f8ad9d;">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><i class="bi bi-house"></i> Trang chủ</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#"><i class="bi bi-bag"></i> Sản phẩm</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Lên hệ</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Tài khoản
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Đăng nhập</a></li>
              <li><a class="dropdown-item" href="#">Đăng ký</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Đăng xuất</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" aria-disabled="true">Disabled</a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>

  <div class="row">
    <div class="col-2 bg-info">sidebar left</div>
    <div class="col-8 row">

      <div class="col-xl-3 col-md-4 col-6 d-flex justify-content-center mb-3">
        <div class="card" style="width: 14rem;">
          <img src="https://studiovietnam.com/wp-content/uploads/2022/08/background-chup-anh-san-pham-02.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>

      <div class="col-xl-3 col-md-4 col-6 d-flex justify-content-center mb-3">
        <div class="card" style="width: 14rem;">
          <img src="https://studiovietnam.com/wp-content/uploads/2022/08/background-chup-anh-san-pham-02.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>

      <div class="col-xl-3 col-md-4 col-6 d-flex justify-content-center mb-3">
        <div class="card" style="width: 14rem;">
          <img src="https://studiovietnam.com/wp-content/uploads/2022/08/background-chup-anh-san-pham-02.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>

      <div class="col-xl-3 col-md-4 col-6 d-flex justify-content-center mb-3">
        <div class="card" style="width: 14rem;">
          <img src="https://studiovietnam.com/wp-content/uploads/2022/08/background-chup-anh-san-pham-02.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>

      <div class="col-xl-3 col-md-4 col-6 d-flex justify-content-center mb-3">
        <div class="card" style="width: 14rem;">
          <img src="https://studiovietnam.com/wp-content/uploads/2022/08/background-chup-anh-san-pham-02.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>

      <div class="col-xl-3 col-md-4 col-6 d-flex justify-content-center mb-3">
        <div class="card" style="width: 14rem;">
          <img src="https://studiovietnam.com/wp-content/uploads/2022/08/background-chup-anh-san-pham-02.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>

      <div class="col-xl-3 col-md-4 col-6 d-flex justify-content-center mb-3">
        <div class="card" style="width: 14rem;">
          <img src="https://studiovietnam.com/wp-content/uploads/2022/08/background-chup-anh-san-pham-02.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>

      <div class="col-xl-3 col-md-4 col-6 d-flex justify-content-center mb-3">
        <div class="card" style="width: 14rem;">
          <img src="https://studiovietnam.com/wp-content/uploads/2022/08/background-chup-anh-san-pham-02.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>


    </div>
    <div class="col-2 bg-info">sidebar right</div>
  </div>
  
</template>

<style scoped>

</style>
