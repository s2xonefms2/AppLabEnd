# AppLabEnd
cách cài đặt bootstrap cho vue:
  # Yarn
  $ yarn add bootstrap-vue bootstrap

  # NPM
  $ npm install bootstrap-vue bootstrap --save
Sau đó file main.js
  import Vue from 'vue';
  import BootstrapVue from 'bootstrap-vue/dist/bootstrap-vue.esm';
  import App from 'App.vue';

  // Import the styles directly. (Or you could add them via script tags.)
  import 'bootstrap/dist/css/bootstrap.css';
  import 'bootstrap-vue/dist/bootstrap-vue.css';

  Vue.use(BootstrapVue);

  new Vue({
    el: '#app',
    render: h => h(App)
  });
