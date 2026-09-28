# Jogo da Memória — Udacity

Projeto de estudo de **HTML, CSS e JavaScript**, desenvolvido no contexto dos exercícios da Udacity.

O objetivo é encontrar **8 pares de cartas** em um tabuleiro com **16 cartas**, procurando concluir a partida com poucos movimentos e no menor tempo possível.

## Como jogar

Selecione duas cartas para revelar seus símbolos. Cada tentativa de comparar duas cartas conta como um movimento.

Quando os símbolos são iguais, as cartas permanecem reveladas. Quando são diferentes, recebem um destaque vermelho e voltam a ficar ocultas após um breve intervalo.

A partida termina quando todos os pares são encontrados. A tela de conclusão apresenta o tempo, a quantidade de movimentos e as estrelas obtidas.

**Desafio do exercício:** encontrar todos os pares em até 12 movimentos para manter as 3 estrelas.

## Recursos presentes no código

- Embaralhamento das cartas no início da partida.
- Comparação de pares, indicação visual de acertos e erros e bloqueio temporário de cliques durante a comparação de cartas diferentes.
- Contador de movimentos, avaliação por estrelas e cronômetro, iniciado na primeira tentativa de comparar duas cartas.
- Tela de conclusão com o resumo da partida e controles de reinício.

## Tecnologias

**HTML** para a estrutura, **CSS** para a apresentação e **JavaScript** para a lógica e a interação com os elementos da página.

O projeto utiliza ícones do **Font Awesome 4.6.1** e a fonte **Coda**, carregada pelo Google Fonts. Esses recursos são obtidos pela internet; os ícones das cartas podem não aparecer quando o recurso externo estiver indisponível.

## Como executar localmente

Baixe o repositório como ZIP e extraia os arquivos, ou utilize o Git:

```sh
git clone https://github.com/juniorptboss/udacity-jogo-da-memoria.git
cd udacity-jogo-da-memoria
```

Abra o arquivo `index.html` no navegador, mantendo as pastas `css/`, `js/` e `img/` na estrutura original.

Não há etapa de compilação nem instalação de pacotes para executar a página. Mantenha a conexão com a internet para carregar os ícones e a fonte externa.

## Estrutura

```text
udacity-jogo-da-memoria/
├── README.md
├── index.html         # Tabuleiro, painel de informações e tela de conclusão
├── css/
│   └── app.css        # Estilos da interface
├── js/
│   └── app.js         # Lógica das cartas, movimentos, estrelas e tempo
└── img/
    └── geometry2.png  # Imagem disponível no repositório
```

## Contexto educacional

Este repositório registra um exercício de aprendizagem com manipulação de elementos da página, eventos de clique, arrays, comparação de dados e temporizadores em JavaScript.

A função de embaralhamento em [`js/app.js`](./js/app.js) mantém a referência ao exemplo utilizado em sua implementação.
