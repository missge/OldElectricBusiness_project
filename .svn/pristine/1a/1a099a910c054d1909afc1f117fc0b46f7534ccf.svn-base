<template>
  <div id="app">
    <!-- <router-view v-wechat-title="$route.meta.title"/> -->
    <keep-alive>
        <router-view v-wechat-title="$route.meta.title" v-if="$route.meta.keepAlive">
            <!-- 这里是会被缓存的视图组件 -->
        </router-view>
    </keep-alive>

    <router-view v-wechat-title="$route.meta.title" v-if="!$route.meta.keepAlive">
        <!-- 这里是不被缓存的视图组件 -->
    </router-view>
  </div>
</template>
<script>
// import minitUi from 'assets/minit-ui.js'
export default {
  name: 'app',
  methods:{
  	 //   weixinPay:function(data){
    //       var vm= this;
    //       if (typeof WeixinJSBridge == "undefined"){//微信浏览器内置对象。参考微信官方文档
    //         if( document.addEventListener ){
    //           document.addEventListener('WeixinJSBridgeReady', vm.onBridgeReady(data), false);
    //         }else if (document.attachEvent){
    //           document.attachEvent('WeixinJSBridgeReady', vm.onBridgeReady(data));
    //           document.attachEvent('onWeixinJSBridgeReady',vm.onBridgeReady(data));
    //         }
    //       }else{
    //         vm.onBridgeReady();
    //       }
    //     },
    //  onBridgeReady() {  
    //        WeixinJSBridge.invoke('hideOptionMenu',{},function(res){
    //       }
    //   )
    // }
},
mounted(){
    // this.weixinPay();
}
}
</script>
  
<style>
  @import 'assets/css/bootstrap.css';
   @import 'assets/css/minit_style.css';
  @import 'assets/icon-style.css';
  @import 'assets/css/reset.css';
 /*@import 'assets/css/public.css';*/
</style>
