<template>
  <div class="octadeskMenu">
    <nav class="container ">
      <div id="od-main-nav" class="collapse navbar-collapse">
        <a class="octadeskMenu-logo hidden-md-down">
          <img src="../assets/images/logos/logo-octadesk.png" width="153" height="34" alt="Logo octadesk" title="Logo octadesk">
        </a>
        <ul class="octadeskMenu-nav">
          <li class="octadeskMenu-nav-item">
            <a >Funcionalidades</a>
          </li>
          <li class="octadeskMenu-nav-item">
            <a>Cases</a>
          </li>
          <li class="octadeskMenu-nav-item">
            <a>Preços</a>
          </li>
          <li class="octadeskMenu-nav-item">
            <a>Materiais</a>
          </li>
          <li class="octadeskMenu-nav-item">
            <a>Contato</a>
          </li>
        </ul>
        <form class="octadeskMenu-form">
          <fieldset>
            <div class="input-group">
              <input
                type="email"
                class="form-control"
                placeholder="Informe seu email"
                required
              >
              <span class="input-group-btn">
                <button
                  type="submit"
                  class="btn btn-success"
                >
                  Avalie grátis
                </button>
              </span>
            </div>
          </fieldset>
        </form>
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
    padding: .5rem 1rem;
    background-color: #fff;
    color: rgba(0,0,0,.5);
    font-weight: 400;
    z-index: 1030;
    box-shadow: 0 2px 2px 0 rgba(0,0,0,.14), 0 1px 5px 0 rgba(0,0,0,.12), 0 3px 1px -2px rgba(0,0,0,.2);
  }

  .octadeskMenu-logo{
    display: inline-block;
    padding-top: .25rem;
    padding-bottom: .25rem;
    margin-right: 1rem;
    font-size: 1.25rem;
    line-height: inherit;
    white-space: nowrap;
  }

  .octadeskMenu-nav{
    display: inline-block;
    padding-left: 0;
    margin-bottom: 0;
    margin-right: auto;
    list-style: none
  }

  .octadeskMenu-nav-item{
    display: inline-block;
  }

  .octadeskMenu-form{
    display: flex;
    flex-flow: row wrap;
    align-items: center;
  }

</style>
