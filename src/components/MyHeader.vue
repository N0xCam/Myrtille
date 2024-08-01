<script setup lang="ts">

</script>

<template>
  <div id="menu">
   <div id="myrtille">
   <img src="../assets/logo_Myrtille.png">
   </div>

   <div id="rubriques">
    <ul>
      <li id="presentation">
        Présentation
      </li>
      <li  id="creations">
        Mes Créations
      </li>
      <li id="contact">
        Me contacter
      </li>
    </ul>
   </div>
  </div>
</template>

<style scoped>

* {
  display:flex;
  background-color: plum;
  height: 20em;
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;
  font-weight: normal;
  
}

#img{
  width: 2em;
  height: 10em;
  padding-bottom: 1em;
  padding-left: 1em;
  
};

ul {
  height: 10em;
  width: 7em;
}

#menu {
  display: flex;
  flex-direction: column;  
  height: 15em;
}

#rubriques {
  font-family: "caviar", sans-serif;
  font-size: 2em;
  
}

nav {
  display: flex;
  justify-content: space-between;
  width: 40%
}

#presentation {
  height: 10em;
  width: 7em;
}

#creations {
  height: 10em;
  width: 7em;
}

#contact {
  height: 10em;
  width: 7em;
}

</style>
