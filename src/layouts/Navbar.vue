<template>
  <div>
    <nav class="navbar navbar-expand-md bg-white mt-3">
      <div class="container border-bottom">
        <router-link class="navbar-brand me-5" to="/">
          <img
            src="../assets/Logo.png"
            alt="Bootstrap"
            width="120"
            height="34"
          />
        </router-link>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <div class="pages me-3">
            <ul class="navbar-nav mb-2 rounded w-100">
              <li class="nav-item activ">
                <router-link to="/">Бош сахифа</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/about">Биз хакида</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/contact">Богланиш</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/news">Янгиликлар</router-link>
              </li>
            </ul>
          </div>
          <div class="languages">
            <ul class="navbar-nav me-auto mb-2 rounded w-100">
              <li class="nav-item activ">
                <router-link to="/uzb">Узб</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/rus">Рус</router-link>
              </li>
            </ul>
          </div>
        </div>
        <div class="contact">
          <p>
            +998-(97)-221-3636 <br />
            <small class="smal">Murojat uchun</small>
          </p>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.navbar {
  height: 60px;
}

a {
  text-decoration: none;
  color: #181818;
}
.murojat {
  color: var(--black);
  font-weight: 400;
  font-size: 18px;
}
.smal {
  float: right;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  color: var(--gray);
}

.pages {
  width: 60%;
}
.languages {
  width: 15%;
}
.languages ul li {
  width: 50%;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: var(--f6);
}
.languages ul li.activ {
  background: var(--green);
  border-radius: 8px;
}

.languages ul li.activ a {
  color: var(--white);
}


.pages ul li {
  width: 25%;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: var(--f6);
}
.pages ul li.activ {
  background: var(--green);
  border-radius: 8px;
}
.pages ul li.activ a {
  color: var(--white);
}
</style>
