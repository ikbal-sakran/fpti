<template>
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-3 col-lg-2 sidebar bg-light py-4">
          <div class="logo text-center mb-4">
            <img src="https://www.ftpi.ac.id/ftpi/wp-content/uploads/2020/01/FTPI-Logo-new.png" alt="FTPI Logo" class="img-fluid">
            <h1 class="h5">FTPI</h1>
          </div>
          <ul class="nav flex-column">
            <li class="nav-item">
              <a class="nav-link" href="#">
                <i class="fas fa-home"></i>
                Dashboard
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <i class="fas fa-file-alt"></i>
                Transaksi
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <i class="fas fa-book"></i>
                Laporan Keuangan
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <i class="fas fa-chart-bar"></i>
                Dashboard
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <i class="fas fa-cog"></i>
                Setting
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <i class="fas fa-sign-out-alt"></i>
                Log Out
              </a>
            </li>
          </ul>
        </div>
        <div class="col-md-9 col-lg-10 main">
          <div class="header d-flex justify-content-between align-items-center py-3">
            <div class="search input-group">
              <span class="input-group-text bg-white border-0"><i class="fas fa-search"></i></span>
              <input type="text" class="form-control border-0" placeholder="Pencarian">
            </div>
            <div class="user d-flex align-items-center">
              <i class="fas fa-question-circle me-3"></i>
              <i class="fas fa-bell me-3"></i>
              <img src="https://www.gravatar.com/avatar/205e460b479e2e5b48aec07710c08d50?s=200" alt="User Avatar" class="rounded-circle me-2" style="width: 30px; height: 30px;">
              <span class="me-2">radiansyahxyz</span>
              <i class="fas fa-chevron-down"></i>
            </div>
          </div>
          <div class="content d-flex justify-content-center">
            <div class="card w-100" style="max-width: 500px;">
              <div class="card-body">
                <h2 class="card-title h4">Input File</h2>
                <p class="card-text">Masukkan File yang Diinginkan</p>
                <div class="form-group mb-3">
                  <label for="nama">Nama</label>
                  <input type="text" id="nama" class="form-control" placeholder="Nama">
                </div>
                <div class="form-group mb-3">
                  <label for="tanggal">Tanggal</label>
                  <input type="date" id="tanggal" class="form-control">
                </div>
                <div class="form-group mb-3">
                  <label for="file">File</label>
                  <input type="file" id="file" class="form-control">
                </div>
                <button class="btn btn-primary">Masukkan</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>


<script>
export default {
  name: "YourComponentName", // Replace with your component's name
  data() {
    return {
      // Define your data here if needed
    };
  },
  methods: {
    // Define your methods here if needed
  }
};
</script>
