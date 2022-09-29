<template>
  <AboutComponent/>
</template>

<script>

import AboutComponent from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    AboutComponent
  
}
}
</script>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    list-style: none;
}


body{
    background-color: var(--color-white);
    font-family: 'Poppins', sans-serif;
    font-size: 1.1rem;
    color: var(--color-black);
    transition: var(--transition);
    line-height: 1.5;
    font-weight: 400;
    margin: 0!important;
    width:100%!important;
}
:root{
    --color-primarty: #171717;
    --color-secondary: #DA0037;
    --color-third:#444444;
    --color-fourth:#EDEDED;
    --color-white: #ffffff;
    --color-black: #000;
    --color-gray-0: #f8f8f8;
    --color-gray-1: #dbe1e8;
    --color-gray-2: #b2becd;
    --color-gray-3: #6c7983;
    --color-gray-4: #454e56;
    --color-gray-5: #2a2e35;
    --color-gray-6: #12181b;
    --br-sm-2:14px;
    --box-shadow-1:0 3px 15px rgba(0,0,0,0.2);
    --transition:all .4s ease-in-out;  
}
section{
    min-height: 100vh;
    width: 100%;
    position: absolute;
    left: 0;
    top: 0;
    padding: 3rem 18rem;
}
a{
  text-decoration: none;
}
</style>

