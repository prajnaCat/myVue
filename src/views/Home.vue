<template>
  
    <el-container direction="vertical" style="height: 45rem;">
                  
    </el-container>
</template>

<script>

export default {
  name: "home",

  components: {
   
  },
  data() {
      
    },

    mounted(){
        
    },

    methods: {
        

        profileSuccess: function (data) {
          console.log("dataataaaa=",data);
          // this.queryUserInfo();
        },

        isPc() {
            let flag = navigator.userAgent.match(/(phone|pad|pod|iPhone|iPod|ios|iPad|Android|Mobile|BlackBerry|IEMobile|MQQBrowser|JUC|Fennec|wOSBrowser|BrowserNG|WebOS|Symbian|Windows Phone)/i);
            if(flag){
                return false;
            }else{
                return true;
            }
        }
    },
  
};

</script>

<style>
  
</style>
