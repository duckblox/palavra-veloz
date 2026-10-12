# 🏃 Palavra Veloz

> **Digite rápido. Corra mais rápido ainda.**

## ▶️ [**JOGAR AGORA → duckblox.github.io/palavra-veloz**](https://duckblox.github.io/palavra-veloz/)

*Abra o link no navegador do computador. Não precisa instalar nada nem criar conta. Precisa de internet (o jogo baixa a biblioteca 3D ao abrir) e de um teclado.*

---

Um jogo de corrida em 3D para brincar de aprender palavras: corra por mundos secretos, **digite as palavras** que aparecem para destruir barreiras, abrir portais e descobrir surpresas. Quanto mais rápido você digita, mais rápido o corredor corre.

## 🎮 Como jogar
1. Clique em **CORRER**. O corredor avança sozinho por uma pista de 3 faixas.
2. Uma **barreira de energia** aparece com uma palavra. Digite a palavra (sem Enter!) e a barreira explode. Letra errada? A palavra só treme, sem castigo.
3. Se a barreira te alcançar antes de você terminar, o corredor tropeça e perde velocidade. Não existe "fim de jogo", e a palavra volta mais tarde para você tentar de novo.
4. No fim de cada mundo aparece um **chefe** (veja abaixo). Depois dele, a cada 8 desafios surge um **portal gigante** com uma palavra mais longa. O corredor espera diante dele até você digitá-la. Aí a porta se abre e você entra em um **novo mundo**.
5. Apanhe moedas, desvie dos blocos vermelhos (ou explodi-os com **ENTER**), gaste as moedas na **garagem** e tente bater o seu recorde e o seu **fantasma**.
6. Aperte **Esc** a qualquer momento para pausar e abrir o menu.

## ⌨️ Controles
| Tecla | O que faz |
|---|---|
| **Letras** | digitam a palavra que está no topo da tela (acentos são opcionais) |
| **← →** ou **1** / **0** | trocam de faixa (**1** = esquerda, **0** = direita, perto das teclas de digitar) |
| **↑** ou **espaço** | pula |
| **↓** | desliza (e, no ar, desce mais rápido) |
| **ENTER** | lança uma 💣 bomba no bloco vermelho mais próximo à frente, em qualquer pista (gasta 1 bomba do estoque) |
| **Esc** ou **⏸** | pausa o jogo e abre o menu (garagem, álbum, painel e opções) |
| **🎵 / 🔊 / 🗣️** | ligam e desligam a música, os efeitos sonoros e a voz que lê o significado das palavras |

## 🌎 Os mundos
🌃 **Cidade Neon** → 🌲 **Floresta Ancestral** → 🌋 **Vulcão** → 🚀 **Estação Espacial** → e tudo recomeça, mais rápido e com palavras maiores.

## 🎁 Surpresas pelo caminho
- **Baús dourados**: digite a palavra para abrir e ganhar um prêmio sorteado (turbo, chuva de moedas, chuva de meteoros ou câmera lenta).
- **Combo**: a cada 5 palavras seguidas, o corredor entra em modo turbo e ganha +1 bomba.
- **Bombas** 💣: você começa com 3 (máximo 9). Abrir um portal dá +2, abrir um baú dá +1. A bomba só destrói blocos vermelhos e as bolas de energia dos chefes: as barreiras com palavras e os portais continuam precisando ser digitados.
- **Velocímetro**: mostra quantas palavras por minuto você digita. A velocidade do corredor cresce junto, e o **recorde** fica salvo.

## 👾 Chefes
Antes de cada portal, um **guardião** bloqueia a pista. Digite uma sequência de palavras para derrotá-lo: cada palavra tira 1 ponto de vida, e **2 pontos se você digitar em menos de 2,6 segundos**. Enquanto isso, ele lança bolas de energia: troque de pista (**1**, **0** ou setas), pule ou use uma bomba (**ENTER**). Se uma bola te atingir, o corredor só tropeça. Ao vencer, você ganha moedas, bombas e pontos.

## 🎨 Garagem, 👻 fantasma, 📖 álbum e 📊 painel
Tudo isso fica no menu (**Esc** ou **⏸**; também há um botão na tela inicial):
- **Garagem:** as moedas que você coleta compram cor do traje, cor do neon, acessórios (antena, chifres, coroa, halo) e trilhas de luz, inclusive versões arco-íris.
- **Fantasma:** o jogo grava a sua melhor corrida e, nas próximas, um corredor transparente repete esse ritmo. O painel mostra quantos metros você está na frente ou atrás dele.
- **Álbum:** todas as palavras, com cadeado até você digitá-las; as descobertas mostram tipo e significado.
- **Painel:** recorde, palavras certas, tempo jogado, gráfico dos últimos 7 dias e as palavras que mais precisam de treino.
- **Volumes (⚙️ Opções):** controles separados para a música, os efeitos e a voz. Enquanto a voz fala, a música abaixa sozinha para dar para ouvi-la bem. Os botões 🎵 🔊 🗣️ do topo continuam ligando e desligando cada som. Os volumes padrão já deixam a voz mais baixa que a música e os efeitos, e a escala da voz é mais precisa nos volumes baixos.
- **Modo calmo (⚙️ Opções):** sem clarões nem tremor de câmera, velocidade menor, efeitos mais suaves e letras maiores.

## 💡 O que se aprende jogando
- **198 palavras** (substantivos, adjetivos e verbos), cada uma com cor própria, escolhidas de modo a repetir pouco. Ao acertar, aparece o **significado**, e com o botão 🗣️ ligado ele também é **lido em voz alta**.
- Treino de digitação com o teclado, com palavras que ficam mais longas a cada mundo.
- Palavras erradas voltam depois, então o jogo ajuda a fixar o que ainda não foi aprendido.

## 🛠️ Para quem quer aprender a programar
O arquivo `index.html` é **todo comentado e indentado de propósito**, para servir de aula. Ele tem 3 partes: `<style>` (CSS, a aparência), `<body>` (HTML, as "caixas" da tela) e `<script>` (JavaScript, o cérebro). Comece lendo o **GUIA DO CÓDIGO** no início do script.

| Parte do código | O que você aprende |
|---|---|
| 1 · Ferramentas e vocabulário | variáveis, funções pequenas, listas (`V`) |
| 2 · A cena 3D | `scene`, `camera`, `renderer` do **Three.js** |
| 3 · O mundo | texturas desenhadas em `<canvas>`, partículas |
| 4 · O corredor | objetos 3D, grupos, estado do jogador |
| 5 · Os mundos | objetos e funções dentro de uma lista (`TH`) |
| 6 · Estado do jogo | variáveis que mudam, `localStorage`, objeto `SV` em JSON |
| 6B · A garagem | catálogo (`SHOP`), aplicar visuais ao modelo 3D |
| 7 e 8 · Efeitos e objetos | funções, `if`, `for`, sorteios |
| 9 · Som | sons criados por código (**Web Audio**) |
| 10 · Teclado | eventos (`keydown`) |
| 11 · O menu | HTML montado por código (`innerHTML`), abas, pausa |
| 12 · Laço principal | `update(dt)`, animação a ~60 quadros por segundo, chefe, fantasma |

### 🧪 Experimentos ("modo criador")
Procure os comentários **MUDE AQUI** no código, troque um valor, salve e recarregue a página:
1. Acrescente suas próprias palavras na lista `V`: `['dragão', 's', 'monstro que cospe fogo']`.
2. Em `update`, troque a velocidade inicial `15`. Fica mais fácil ou mais difícil?
3. Em `spawnT`, troque `tgtN >= 8` por `4`: os portais aparecem mais cedo.
4. Em `pickWord`, mude os tamanhos das palavras de cada nível.
5. Em `PARTE 6`, troque `bombs = 3` para começar com mais (ou menos) bombas.
6. Em `TH`, mude as cores de um mundo, ou **crie um quinto mundo** copiando um bloco.
7. Em `SHOP`, mude os preços ou invente um item novo (por exemplo, uma cor nova de traje).
8. Em `spawnT`, a vida do chefe é `Math.min(4 + level, 8)`. Quer um chefe mais fácil ou mais difícil?

## ⚠️ Avisos
**Para quem joga:** o jogo é rápido e colorido. Faça pausas, beba água e brinque também fora da tela.

**Para responsáveis:**
- Não há cadastro, compras, anúncios nem jogos de azar.
- O jogo **não coleta dados**. O que fica guardado (moedas, visuais, palavras descobertas, recordes por dia, tempo jogado, volumes e a melhor corrida) fica **apenas no navegador do próprio aparelho** (`localStorage`). Se os dados do navegador forem apagados, ou se o jogo for aberto em aba anônima, o progresso se perde. Em **⚙️ Opções**, é possível apagar tudo e recomeçar.
- Ao abrir, o navegador baixa a biblioteca Three.js do serviço `cdnjs.cloudflare.com`. É um pedido normal de um arquivo de código, sem envio de dados do jogador.
- **Estímulos visuais e sonoros:** há um clarão branco rápido (cerca de 1 segundo) ao trocar de mundo, linhas de velocidade e efeitos de explosão. Pessoas sensíveis à luz, ou que se sobrecarregam com facilidade, devem jogar com atenção e parar se sentirem desconforto. O **modo calmo** (⚙️ Opções) remove os clarões e o tremor de câmera, reduz a velocidade e aumenta as letras. O jogo também pausa sozinho ao trocar de aba. A **música e a voz começam desligadas**, e os efeitos sonoros podem ser desligados no botão 🔊.
- **Voz (opcional):** o botão 🗣️ usa a síntese de fala do navegador ou do sistema para ler o significado das palavras. Em alguns navegadores, certas vozes funcionam pela internet; se isso for um problema, deixe o botão desligado (é o padrão). O jogo escolhe a melhor voz em português instalada (de preferência pt-BR). Se não houver nenhuma, ele avisa e mantém a voz desligada. Para instalar uma, procure nas configurações do sistema (o caminho exato varia com a versão): no Windows, Hora e idioma → Fala (adicionar vozes em Português do Brasil; o Edge costuma ter as melhores); no Mac, Acessibilidade → Conteúdo Falado; no Android, os Serviços de fala do Google.
- Errar não tem punição forte: o jogo foi pensado para ser jogado sem pressão. Mesmo assim, combine um tempo de tela e jogue junto por alguns minutos, conversando sobre as palavras novas.

## 🧩 Tecnologias e créditos
HTML, CSS, JavaScript e [Three.js](https://threejs.org/) (versão r128, licença MIT). Músicas e sons são sintetizados pelo próprio código, sem arquivos de áudio. Não há imagens externas.
