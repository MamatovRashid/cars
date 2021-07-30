<template>
  <div class="footer">
      <div class="container">
          <div class="box">
              <div class="left">
                  <div class="col">
                      <span> {{year}} </span>
                      <p>Year</p>
                  </div>
                  <div class="col">
                      <span> {{millage}} </span>
                      <p>Millage</p>
                  </div>
                  <div class="col">
                      <span> {{model}} </span>
                      <p> {{marka}} </p>
                  </div>
              </div>
              <div class="right">
                  <a href="#">
                      Full Detials
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M5 12H19" stroke="#343A40" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M12 5L19 12L12 19" stroke="#343A40" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                  </a>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            year: 2020,
            millage: 3650,
            model: 'Mercedes-Benz',
            marka: 'C-Class 2020'
        }
    },
}
</script>

<style scoped>
    .footer{
        border-top: 5px solid #343A40;
        padding: 12px 0;
        background: #CED4DA;
    }
    span{
        font-weight: 700;
        font-size: 24px;
    }
    .box{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .box p{
        font-size: 18px;
        font-weight: 500;
    }
    .left{
        display: flex;
        align-items: center;
    }
    .col:not(:last-child){
        margin-right: 120px;
    }
    .right a{
        color: #343A40;
        font-weight: 500;
        font-size: 24px;
        display: flex;
        align-items: center;
    }
     .right a svg{
         margin-left: 13px;
     }
</style>