<script>
  import { link } from 'svelte-spa-router'
</script>

<nav class="navbar navbar-dark bg-dark">
  <div class="container-fluid">
    <a use:link class="navbar-brand" href="/">TODO</a>
    <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon" />
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
                <a use:link class="nav-link" href="/user-create">리스트보기</a>
            </li>
            <li class="nav-item">
                <a use:link class="nav-link" href="/user-login">마이페이지</a>
            </li>
        </ul>
    </div>
  </div>
</nav>