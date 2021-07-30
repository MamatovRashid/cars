<template>
  <div class="header">
    <div class="container">
      <div class="box">
        <div class="left">
          <svg
            width="21"
            height="21"
            viewBox="0 0 21 21"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <g clip-path="url(#clip0)">
              <path
                d="M20.5074 7.21875H18.0518L17.3693 5.5125C16.6679 3.75826 14.9941 2.625 13.1045 2.625H7.89551C6.00633 2.625 4.33207 3.75826 3.6303 5.5125L2.9478 7.21875H0.492601C0.172269 7.21875 -0.0627505 7.5198 0.0151792 7.83029L0.261273 8.81467C0.315824 9.03369 0.512699 9.1875 0.738695 9.1875H1.56188C1.01104 9.66861 0.656253 10.3679 0.656253 11.1562V13.125C0.656253 13.7862 0.90891 14.3829 1.3125 14.8448V17.0625C1.3125 17.7872 1.90026 18.375 2.625 18.375H3.9375C4.66225 18.375 5.25 17.7872 5.25 17.0625V15.75H15.75V17.0625C15.75 17.7872 16.3378 18.375 17.0625 18.375H18.375C19.0998 18.375 19.6875 17.7872 19.6875 17.0625V14.8448C20.0911 14.3834 20.3438 13.7866 20.3438 13.125V11.1562C20.3438 10.3679 19.989 9.66861 19.4385 9.1875H20.2617C20.4877 9.1875 20.6846 9.03369 20.7391 8.81467L20.9852 7.83029C21.0628 7.5198 20.8277 7.21875 20.5074 7.21875ZM6.06744 6.48744C6.36645 5.74014 7.09037 5.25 7.89551 5.25H13.1045C13.9096 5.25 14.6336 5.74014 14.9326 6.48744L15.75 8.53125H5.25L6.06744 6.48744ZM3.9375 13.1168C3.15 13.1168 2.625 12.5934 2.625 11.8084C2.625 11.0234 3.15 10.5 3.9375 10.5C4.725 10.5 5.90625 11.6776 5.90625 12.4626C5.90625 13.2476 4.725 13.1168 3.9375 13.1168ZM17.0625 13.1168C16.275 13.1168 15.0938 13.2476 15.0938 12.4626C15.0938 11.6776 16.275 10.5 17.0625 10.5C17.85 10.5 18.375 11.0234 18.375 11.8084C18.375 12.5934 17.85 13.1168 17.0625 13.1168Z"
                fill="currentColor"
              />
            </g>
          </svg>
          <p>carslot.</p>
        </div>
        <div class="right">
            <div class="language">
                <p>
                    ENG
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M6 9L12 15L18 9" stroke="#343A40" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                </p>
            </div>
            <button>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M11 19C15.4183 19 19 15.4183 19 11C19 6.58172 15.4183 3 11 3C6.58172 3 3 6.58172 3 11C3 15.4183 6.58172 19 11 19Z" stroke="#343A40" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M21 21L16.65 16.65" stroke="#343A40" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.header {
  padding: 30px 0;
  font-weight: 500;
}
.box{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.left {
  display: flex;
  align-items: center;
}
.left p {
  margin-left: 40px;
  font-size: 24px;
}
.right{
    display: flex;
    align-items: center;
}
.language{
    cursor: pointer;
}
.language p{
    font-size: 18px;
    display: flex;
    align-items: center;
}
.language p svg{
    margin-left: 18px;
}

.right button{
    margin-left: 110px;
}
</style>
