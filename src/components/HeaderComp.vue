<template>
  <header>
    <div class="logo">
      <img src="@/assets/imgs/logo-removebg-preview.png" />
    </div>
    <div class="menu-central">
      <span> <RouterLink to="/">Livros</RouterLink> </span>
      <span> <RouterLink to="/">Editoras</RouterLink> </span>
      <span> <RouterLink to="/">Autores</RouterLink> </span>
      <span> <RouterLink to="/">Produtos</RouterLink> </span>
    </div>
    <div class="menu-direito">
      <button @click="sair">SAIR</button>
    </div>
    <img class="img-usuario" src="@/assets/imgs/usuario.png" />
  </header>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap');

header span {
  padding: 0 30px;
  font-size: larger;
}

header {
  margin: 0;
  background-color: #616fee;
  height: 15%;
  font-size: 1.3rem;
  padding-left: 2rem;
  color: white;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

/*---------------------------------*/

.menu-central {
  padding-left: 160px;
}

.menu-central span {
  text-decoration: none;
}
  
a {
  color: inherit;
  text-decoration: none;
}

/*---------------------------------*/

.img-usuario {
  padding-right: 2%;
  padding-bottom: 7.5px;
}

.menu-direito button {
  margin-left: 400px;
  border-color: inherit;
  background-color: #616fee;
  border-radius: 30px;
  border-width: 2px;
  border-style: solid;
  color: inherit;
  font-weight: bolder;
  font-size: small;
  padding: 10px 25px 10px;
  font-family: 'Poppins' ;
}

.menu-direito button:hover {
  color: #616fee;
  background: #FFFFFF;
}

</style>
