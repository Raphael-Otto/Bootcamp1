<script>
export default {
  data() {
    return {
      jogadores: [
        {
          id: "72b60663-4943-4f37-a782-3b0688d5b313",
          nome: "Jogador 1",
          time: "Time 1",
        },
        {
          id: "e91ca40f-1b1c-40d9-a589-a6d74b42f6c5",
          nome: "Jogador 2",
          time: "Time 2",
        },
        {
          id: "d181a6a6-fa46-426e-bd5a-9a9ee19356d6",
          nome: "Jogador 3",
          time: "Time 3",
        },
        {
          id: "e0b9c7d6-06d5-405f-a674-0e4b286a6b6a",
          nome: "Jogador 4",
          time: "Time 4",
        },
        {
          id: "0daa3bee-b872-4ca7-87ef-42481f434a9a",
          nome: "Jogador 5",
          time: "Time 5",
        },
      ],
    };
  },
};
</script>

<template>
  <div class="container">
    <div class="title">
      <h2>Gerenciamento de Jogadores</h2>
    </div>
    <div class="form-input">
      <input type="text" />
      <button>Salvar</button>
    </div>
    <div class="list-jogadores">
      <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>Nome</th>
            <th>Time</th>
          </tr>
        </thead>
        <tbody>
          <tr v-for="jogadores in jogadores" :key="jogadores.id">
            <td>{{ jogadores.id }}</td>
            <td>{{ jogadores.nome }}</td>
            <td>{{ jogadores.time }}</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>
