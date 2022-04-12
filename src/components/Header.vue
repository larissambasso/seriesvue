<template>
<nav class="header navbar col-12 m-auto navbar-expand-lg navbar-dark bg-dark">
      <div class="container-fluid navbar col-10 m-auto">
        <a class="navbar-brand" href="/treinobootstrap/index.html" style="margin-right: 60px; font-family: Colibri, Comic Sans; font-size: 27px;">LARIFLIX</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="/treinobootstrap/index.html">Home</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown"
                aria-expanded="false">
                Minha lista
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="/treinobootstrap/assistidas.html">Assistidas</a></li>
                <li><a class="dropdown-item" href="/treinobootstrap/assistindo.html">assistindo</a></li>
                <li>
                  <hr class="dropdown-divider">
                </li>
                <li><a class="dropdown-item" href="proximas.html">Interesses</a></li>
              </ul>
            </li>
          </ul>
          <form class="d-flex">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
</template>

<script>
  
</script>

<style>
  .header{
    height:10vh;
  }
</style>
