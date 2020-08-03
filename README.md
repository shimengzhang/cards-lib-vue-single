# cards-lib-vue

> 卡片库 vue 版

## 组件内部使用
html: 

　　<Main/>

js：

    import Main from '@auto/cards-lib-vue'

    components: {
      Main
    }
## main.js 全局安装：
import Main from '@auto/cards-lib-vue'
Vue.use(Main)
然后在其他.vue文件里面，直接使用组件 <cards-lib-vue/> 即可
