🧩 Cubo Mágico 3D

Projeto desenvolvido por Guilherme Hentges e Daniel Suassuna utilizando JavaScript e Three.js para simular um Cubo Mágico 3D interativo. O sistema permite movimentar as faces do cubo, embaralhá-lo automaticamente, acompanhar a quantidade de movimentos realizados e detectar quando o cubo retorna ao estado resolvido.

📖 Descrição

O projeto consiste em uma representação tridimensional de um Cubo Mágico 3x3x3 composta por 27 cubos menores. A aplicação foi desenvolvida para explorar conceitos de computação gráfica, animações em tempo real e manipulação de objetos 3D utilizando a biblioteca Three.js.

O usuário pode interagir com o cubo por meio de botões na interface ou através do teclado, realizando rotações em todas as faces do cubo e tentando retornar ao estado inicial após um embaralhamento.

🚀 Funcionalidades
Renderização de um Cubo Mágico em ambiente 3D.
Controle livre da câmera utilizando OrbitControls.
Rotação das seis faces do cubo.
Interface gráfica com botões para movimentação.
Controle por teclado.
Embaralhamento automático com movimentos aleatórios.
Exibição da mensagem "EMBARALHANDO..." durante o processo.
Contador de movimentos realizados pelo jogador.
Detecção automática de vitória.
Exibição de mensagem quando o cubo é resolvido.
🎮 Controles
Teclado
Tecla	Movimento
S	Face Superior
I	Face Inferior
F	Face Frontal
T	Face Traseira
E	Face Esquerda
D	Face Direita
Botões

A interface possui botões equivalentes aos comandos do teclado, permitindo controlar todas as faces diretamente pela tela.

🔀 Sistema de Embaralhamento

Ao clicar no botão Embaralhar, o sistema executa uma sequência de 15 movimentos aleatórios para misturar o cubo.

Durante o embaralhamento:

A mensagem "EMBARALHANDO..." é exibida.
O texto permanece piscando enquanto os movimentos são executados.
Os movimentos do embaralhamento não são contabilizados no contador do jogador.
A mensagem desaparece automaticamente ao final do processo.
📊 Contador de Movimentos

O sistema registra todos os movimentos realizados pelo usuário após o embaralhamento.

O contador é atualizado em tempo real e exibido no canto superior direito da tela.

🏆 Detecção de Vitória

Quando o cubo retorna ao seu estado original, o sistema detecta automaticamente a vitória comparando a posição e orientação dos cubinhos com o estado inicial armazenado.

Ao resolver o cubo, é exibida a mensagem:

CUBO RESOLVIDO!
🛠️ Tecnologias Utilizadas
HTML5
CSS3
JavaScript
Three.js
OrbitControls
📂 Estrutura do Projeto
Cubo Magico 3D
│
├── Interface gráfica
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
🎯 Objetivos do Projeto
Aplicar conceitos de computação gráfica.
Utilizar a biblioteca Three.js para criação de ambientes 3D.
Trabalhar com transformações geométricas e animações.
Desenvolver uma aplicação interativa utilizando JavaScript.
Simular o comportamento básico de um Cubo Mágico em ambiente virtual.