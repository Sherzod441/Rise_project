<template>
  <div class="container">
    <div class="row">
      <div class="col-md-5">
        <p class="header-1"> дунёнинг етакчи махсулотлари билан ракобатлаша оладиган <span class="green">гипсокартонлар</span> </p>
      </div>
      <div class="col-md-3"></div>
      <div class="col-md-4">
        <p class="header-2">Sifatni qadirlaydiganlar uchun ishonchli gipsakartonlarni hammasi “RISE GROUP”da mujassamlashgan.</p>
      </div>
    </div>
    <div class="row mb-5">
      <div class="col-md-12">
        <img src="../assets/image1.png" alt="">
      </div>
    </div>
    <div class="row">
      <div class="col-md-1"><span class="small me-3 ">Afzalliklarimiz</span></div>
      <div class="col-md-1"></div>
      <div class="col-md-10 ">
        <p class="header-3 "> Xorijiy mamlakatlar bilan raqobatlasha  oladigan mahsulotimizning asosiy afzalliklari quyidagilardan iborat </p>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4">
        <div class="card">
          nagap
        </div>

      </div>
      <div class="col-md-4">
          <div class="card">
            nagap
          </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          nagap
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header-1{
  font-style: normal;
font-weight: 400;
font-size: 40px;
}
.green{
  color: var(--green);
}
.header-2{
  margin-top:150px;
  display: flex;
  align-items: flex-end;
  justify-content: bottom;
  font-weight: 400;
  font-size: 18px;
  color: var(--gray);
}
.small{
  font-weight: 400;
  font-size: 16px;
  color: var(--gray)
}
.header-3{
  font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 40px;
line-height: 44px;
/* identical to box height, or 110% */
display: flex;
align-items: flex-end;
  color: var(--black)
}

.card{
  text-align: center;
}
</style>
