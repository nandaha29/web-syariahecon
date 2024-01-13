<template>
  <!--  router implement -->
  <!-- <RouterLink to="/">dashboard</RouterLink>
  <RouterLink to="/about">about</RouterLink> -->

  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="../assets/LogoNavbar.png" alt="" />
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <form class="d-flex">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search" />
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" aria-current="page"><RouterLink to="/">Beranda</RouterLink></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page"><RouterLink to="/about">Berita</RouterLink></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page"><RouterLink to="/">Kelas</RouterLink></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page"><RouterLink to="/">Halal Blockchain</RouterLink></a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>
