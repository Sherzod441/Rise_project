<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-white mt-3 mb-3">
      <div class="container border-bottom">
        <div class="row">
          <div class="col-md-2">
            <a class="navbar-brand me-5" href="#">
              <img
                src="../assets/Logo.png"
                alt="Bootstrap"
                width="120"
                height="34"
              />
            </a>
          </div>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <div class="col-md-6">
              <ul class="navbar-nav me-4 mb-2 rounded">
                <li class="nav-item me-5 activ">
                  <router-link to="/">Бош сахифа</router-link>
                </li>
                <li class="nav-item me-5">
                  <router-link to="/about">Биз хакида</router-link>
                </li>
                <li class="nav-item me-5">
                  <router-link to="/contact">Богланиш</router-link>
                </li>
                <li class="nav-item">
                  <router-link to="/news">Янгиликлар</router-link>
                </li>
              </ul>
            </div>
            <div class="col-md-2">
              <ul class="navbar-nav me-auto mb-2 rounded">
                <li class="nav-item me-5">
                  <router-link to="/uzb">Узб</router-link>
                </li>
                <li class="nav-item me-5">
                  <router-link to="/rus">Рус</router-link>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-md-2">
            <p class="murojat">
              +998-(97)-221-3636 <br />
              <small class="smal">Murojat uchun</small>
            </p>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  text-decoration: none;
  color: #181818;
}
.murojat {
  color: var(--black);
  font-weight: 400;
  font-size: 18px;
}
.navbar-nav {
  background-color: var(--f6);
}
.smal {
  float: right;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  color: var(--gray);
}
li.activ {
  background-color: var(--green);
}
li.activ a {
  color: white;
}
li {
  width: 140px;
  height: 50px;
}
</style>