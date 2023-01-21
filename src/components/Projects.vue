

<template>
  <div id="projects">
    <div id="container">
      <a href="http://localhost:5174/typing-test/" target="_blank" class="card">Typing Test</a>
      <a href="http://localhost:5500/" div target="_blank" class="card">Quiz</a>
      <a href="/nextedit.txt" target="_blank" class="card">Nextedit code editor</a>
      <a href="/TicTacToe.txt" target="_blank" class="card">Minimax Tic Tac Toe</a>
    </div>
  </div>
</template>

<style scoped>
#projects {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 3rem;
  display: flex;
  justify-content: center;
  align-items: center;
  backdrop-filter: blur(1.5px);
}
#container {
  display: grid;
  grid-template-columns: auto auto;
  gap: 1rem;
}
.card {
  all: unset;
  cursor: pointer;
  text-align: center;
  width: 15rem;
  height: 7rem;
  line-height: 7rem;
  background-color: #010A168f;
  border-radius: 1rem;
  border: 0.5px solid #ffffff0f;
  backdrop-filter: blur(15px);
  transition: all 150ms;
}
.card:hover {
  transform: scale(105%);
}
</style>
