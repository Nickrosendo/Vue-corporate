<template>
  <div class="octadeskMenu">
    <nav class="container ">
      <div id="od-main-nav" class="collapse navbar-collapse">
        <a class="navbar-brand hidden-md-down">
          <img src="../assets/images/logos/logo-octadesk.png" width="153" height="34" alt="Logo octadesk" title="Logo octadesk">
        </a>
      <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
			<li class="nav-item">
				<a class="nav-link">Funcionalidades</a>
			</li>
			<li class="nav-item">
				<a class="nav-link">Cases</a>
			</li>
			<li class="nav-item">
				<a class="nav-link">Preços</a>
			</li>
			<li class="nav-item">
				<a class="nav-link">Materiais</a>
			</li>
			<li class="nav-item">
				<a class="nav-link">Contato</a>
			</li>
		</ul>
      </div>
    </nav>
  </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .octadeskMenu{
    position: fixed;
    top: 	0;
    left: 0;
    right: 0;
    background-color: #fff;
    font-weight: 400;
    z-index: 1030;
    box-shadow: 0 2px 2px 0 rgba(0,0,0,.14), 0 1px 5px 0 rgba(0,0,0,.12), 0 3px 1px -2px rgba(0,0,0,.2);
  }

</style>
