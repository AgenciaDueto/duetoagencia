# duetoagencia

1.Execute create-nuxt-app my-project<br>
cd my-project

Certifique-se de ter node sass and sass-loader instalado
<br>
2.Execute npm i -D node-sass sass-loader
<br>
3.Em seu nuxt.config.js, inclua seu SCSS no qual você importará todos os outros SCSS.<br>
  css: [ 
      '@/assets/scss/main.scss'
  ]<br>
COMO MÁGICA! Agora seu SCSS está sendo compilado e será inserido automaticamente em uma <style>tag em sua cabeça. 
Para mais informações, confira os documentos do Nuxt.js em CSS.
