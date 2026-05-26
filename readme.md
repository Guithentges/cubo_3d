# 🧩 Cubo Mágico 3D

Projeto desenvolvido por **Guilherme Hentges** e **Daniel Suassuna** utilizando **JavaScript** e **Three.js** para simular um Cubo Mágico 3D interativo. A aplicação permite movimentar as faces do cubo, embaralhá-lo automaticamente, acompanhar a quantidade de movimentos realizados e detectar quando o cubo retorna ao estado resolvido.

## 📖 Descrição

O projeto consiste em uma representação tridimensional de um Cubo Mágico 3x3x3 composta por 27 cubos menores. A aplicação foi desenvolvida para explorar conceitos de computação gráfica, animações em tempo real e manipulação de objetos 3D utilizando a biblioteca Three.js.

O usuário pode interagir com o cubo através de botões na interface ou utilizando o teclado, realizando rotações em todas as faces e tentando retornar ao estado inicial após um embaralhamento.

## 🚀 Funcionalidades

- Renderização de um Cubo Mágico 3D.
- Controle livre da câmera utilizando OrbitControls.
- Rotação das seis faces do cubo.
- Controle por teclado.
- Controle por botões na interface.
- Embaralhamento automático.
- Mensagem visual durante o embaralhamento.
- Contador de movimentos.
- Detecção automática de vitória.
- Exibição de mensagem quando o cubo é resolvido.

## 🎮 Controles

### Teclado

| Tecla | Movimento |
|--------|-----------|
| S | Face Superior |
| I | Face Inferior |
| F | Face Frontal |
| T | Face Traseira |
| E | Face Esquerda |
| D | Face Direita |

### Interface

Também é possível utilizar os botões disponíveis na tela para realizar os mesmos movimentos.

## 🔀 Embaralhamento

Ao clicar no botão **Embaralhar**, o sistema executa uma sequência de movimentos aleatórios para misturar o cubo.

Durante o processo:

- A mensagem **"EMBARALHANDO..."** é exibida.
- A mensagem pisca enquanto os movimentos são executados.
- Os movimentos realizados pelo embaralhamento não são contabilizados.
- A mensagem desaparece automaticamente ao final do processo.

## 📊 Contador de Movimentos

O sistema registra todos os movimentos realizados pelo usuário após o embaralhamento.

O contador é atualizado automaticamente e exibido no canto superior direito da tela.

## 🏆 Detecção de Vitória

O estado inicial do cubo é armazenado quando a aplicação é carregada.

Após cada movimento, o sistema compara a posição e a orientação dos cubinhos com o estado inicial. Quando ambos coincidem, a mensagem:

```text
CUBO RESOLVIDO!
```

é exibida na tela indicando que o jogador resolveu o cubo.

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- Three.js
- OrbitControls

## 📂 Estrutura do Projeto

```text
projeto/
│
├── index.html
│
├── Interface
│   ├── Botões de movimentação
│   ├── Botão embaralhar
│   ├── Contador de movimentos
│   └── Mensagens de status
│
├── Sistema 3D
│   ├── Cena
│   ├── Câmera
│   ├── Renderizador
│   └── Iluminação
│
├── Cubo Mágico
│   ├── Criação dos 27 cubinhos
│   ├── Rotação das faces
│   ├── Embaralhamento
│   └── Verificação de vitória
│
└── Loop de animação
```

## 🎯 Objetivos do Projeto

- Aplicar conceitos de computação gráfica.
- Utilizar a biblioteca Three.js para desenvolvimento 3D.
- Trabalhar com transformações geométricas.
- Desenvolver animações em tempo real.
- Criar uma aplicação interativa utilizando JavaScript.
- Simular o funcionamento básico de um Cubo Mágico em ambiente virtual.

## 👨‍💻 Integrantes

- Guilherme Hentges
- Daniel Suassuna

## ▶️ Como Executar

1. Faça o download ou clone o repositório.
2. Abra o arquivo `index.html` em um navegador moderno.
3. Utilize os botões ou o teclado para movimentar o cubo.
4. Clique em **Embaralhar** para iniciar um novo desafio.
5. Tente resolver o cubo utilizando o menor número possível de movimentos.

---
Projeto acadêmico desenvolvido para estudo de computação gráfica e manipulação de objetos 3D com Three.js.