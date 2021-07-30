<template>
  <div class="main1">
      <div class="container">
          <div class="box" :style=" { 'background-image' : 'url(' + carImg + ')' } ">
              <h1 v-html="dollar+price"></h1>
              <p>Las Vega, NV</p>
              <div class="buttonbox">
                  <button>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12 19V5" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M5 12L12 5L19 12" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                  </button>
                  <p>{{id}}</p>
                  <button>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M12 5V19" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M19 12L12 19L5 12" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                  </button>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            id: 1,
            carImg: '/img/car1.ec7686d3.png',
            dollar: '&dollar;',
            price: '1,250,560'
        }
    },
}
</script>
<style scoped>
    .box{
        position: relative;
        width: 100%;
        padding: 15px 0;
        height: calc(100vh - 96px - 92px);
        background-repeat: no-repeat;
        background-position: center center;
    }
    .box h1{
        font-weight: 700;
        font-size: 36px;
        margin-bottom: 10px;
    }
    .box p{
        color: #6C757D;
        font-weight: 600;
        font-size: 18px;
    }
    .buttonbox{
        position: absolute;
        right: 0;
        top: 50%;
        transform: translateY(-50%);
        display: flex;
        align-items: center;
        flex-direction: column;
    }
    .buttonbox p{
        font-size: 24px;
        font-weight: 600;
        margin: 60px 0;
        color: #343A40;
    }
    .buttonbox button{
        display: flex;
        justify-content: center;
        align-items: center;
        width: 46px;
        height: 46px;
        border-radius: 100%;
    }
    .buttonbox button:hover{
        color: #F8F9FA;
        background: #343A40;
    }
</style>