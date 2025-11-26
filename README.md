# React - Jogo da Velha (Tic-Tac-Toe)

Projeto React implementando o clássico Jogo da Velha, baseado no tutorial oficial do React.

## 🎯 Objetivo

Criar um jogo interativo de Jogo da Velha usando React, aplicando os principais conceitos:
- Componentes funcionais
- Props
- Estado (useState)
- "Lifting State Up" (compartilhamento de estado entre componentes)

## 📁 Estrutura do Projeto

```
src/
  ├── components/
  │   ├── Square.jsx    # Componente que representa um quadrado do tabuleiro
  │   ├── Board.jsx     # Contém 9 quadrados e controla a lógica de jogadas
  │   └── Game.jsx      # Gerencia o histórico e a navegação entre jogadas
  ├── utils/
  │   └── calculateWinner.js  # Função auxiliar para verificar vencedor
  ├── App.jsx           # Componente principal
  ├── App.css           # Estilos do jogo
  ├── main.jsx          # Ponto de entrada
  └── index.css         # Estilos globais
```

## 🚀 Como executar

1. Instale as dependências:
```bash
npm install
```

2. Execute o projeto em modo de desenvolvimento:
```bash
npm run dev
```

3. Abra o navegador em `http://localhost:5173`

## 🎮 Funcionalidades

- ✅ Tabuleiro com 9 quadrados interativos
- ✅ Alternância entre jogadores "X" e "O"
- ✅ Detecção de vencedor
- ✅ Histórico de jogadas
- ✅ Navegação "time travel" entre estados anteriores do jogo

## 📚 Conceitos Praticados

- Componentes funcionais e reutilização
- Hooks: useState
- Props e callbacks entre componentes
- Imutabilidade do estado (slice())
- "Lifting state up"
- Renderização condicional
- Mapeamento de listas (map())

## 🛠️ Tecnologias

- React 18
- Vite
- JavaScript (JSX)

## 📖 Referência

Tutorial oficial: [React - Jogo da Velha (Tic Tac Toe)](https://react.dev/learn/tutorial-tic-tac-toe)

# Exerc-cio-React-Jogo-da-Velha---Projeto-de-Front-End-Frameworks
