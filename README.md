# Projeto Final Desenvolvimento de jogos para Web

Este é o repositório onde contém o GDD para o jogo que será desenvolvido para a cadeira de Desenvolvimento de Jogos para Web da Uniritter 2021/2.

## Sumário

1. [Pré Requisitos](#pré-requisitos)
1. [Características do Jogo](#características-do-jogo)
1. [Controles do Player](#controles-do-player)
1. **[Pitch](#pitch)**
1. [Storytelling](#storytelling)
1. [Features](#features)


## Pré requisitos

1. Deve ser desenvolvido em contruct 3
1. Build para web
1. Build para mobile (gerar um apk)
1. Tutorial
1. Efeitos sonoros
1. Gráficos ok
1. Game design
1. Level design

## Características do jogo

---

#### Core

1. Plataforma
1. Side scroller
1. Run and Gun
1. Terá um dash
1. Terá pelo menos uma boss fight
1. Terá uma loja
    - Será possível comprar power ups na loja 
        - armas
        - bônus de dash 
        - vida extra
1. Terá um item coletável que será apenas uma moeda
1. Terá pelo menos 3 fases com inimigos diferentes para enfrentar no decorrer da fase
    - Um desses inimigos pode ser considerado um mini boss com alguma habilidade bem parecida com a do boss
    - Os inimigos terão comportamentos parecidos com o do boss para o player ir se familiarizando com o comportamento do boss e como derrota-lo.
1. Terá um tutorial atribuído no começo do jogo para explicar as funcionalidades
1. Será possível atirar para cima e para as diagonáis
1. Terá um medidor de poder que irá carregar conforme o usuário atire
    - será possível usar um golpe especial e ganhar uma vida conforme carregam
1. Sons
    - Para atirar
    - Quando o tiro atinge o alvo
    - Para dano sofrido
    - Ao morrer
    - Explosão quando inimigo morre
    - Som na fase
        - Ideia do som é ser um frenético para deixar o jogador ansioso para passar na fase
1. Boss
    - Terão comportamentos diferentes e formas de derrotar diferentes
    - Terão um modo berserker que será ativado quando a vida atual for igual a 20% da vida total
    - Ao morrer, o jogador ganha a arma do boss.
1. Dialogue System
1. "Cut scenes"
    Será uns diálogos que vão ser apresentados antes das boss fights e durante quando o boss estiver para morrer ou em interações com mini boss.
1. Será possível alterar entre armas
1. Reload system
1. Coletáveis

### Controles do Player 

- Movimentação lateral
    - Teclado: A, D
    - Controle: Left Arrow, Right Arrow
    - Mobile:
- Agachar
    - Teclado: S
    - Controle: Down Arrow
    - Mobile:
- Pulo (W, Up Arrow)
    - Teclado: A, D
    - Controle: Left Arrow, Right Arrow
    - Mobile:
- Dash
    - Teclado: Z
    - Controle: Y
    - Mobile:
- Atirar (Mouse left click)
    - Mouse: Left Click
    - Controle: X
    - Mobile:
- Especial (Mouse right click)
    - Mouse: Right click
    - Controle: B
    - Mobile:
- Recarregar arma (X)
    - Teclado: X
    - Controle: A
    - Mobile:
- Trocar de arma (C)
    - Teclado: C
    - Controle: RB
    - Mobile:

## Pitch

--- 

Será um jogo que se passa no velho oeste onde o personagem principal Gus é um pistoleiro que está setenciado a morte por seus crimes cometidos. O crime cometido foi flertar com a filha do xerife no bar local da cidade de Westland. Em Westland há 3 gangues poderosas que aterrorizam os turistas e os pessoas da cidade, a [gangue Boomer](#a-gangue-boomer), a gangue dos Pungilistas e a [gangue do Botânico](#a-gangue-do-botânico). Será o dever de Gus coletar as recompensas desses criminosos para se livrar da morte.

## Storytelling

---

### Gus, o Pistoleiro

Em inglês Gus, the Gunslinger. É um cara ordinário que possui uma mira boa e um bom gatilho. Extrovertido e brincalhão, mas não tão aventureiro e briguento quanto um pistoleiro deve ser.

### A gangue Boomer

Formada por seu capitão Ang. Conhecido por falar com sua arma e seu tiro fazer uma curva e voltar para sua arma. Ninguém entende como isso funciona, porém, ele logo ficou conhecido em Westland por seu boomer"Ang" fatal. Composta por bandidos locais que gostam de incomodar nos bares locais. Recompensa: $10.000

### A gangue do Pungilistas

É uma gangue formada por lutadores do submundo de Westlands. Possuem a fama de um soco ser que nem um tiro de tão poderoso que é. São rápidos com seus movimentos e possuem bastante resistência. Pode encontrar eles em muitos bares clandestinos, onde só ricos e aqueles que querem uma diversão diferenciada vão. Dizem que pra entrar no ringue é preciso entrar para a gangue e respeitar as regras da gangue. Quem quebra uma das regras nunca mais é visto em Westlands. A primeira regra é: nunca fale sobre a gangue dos Pungilistas. Recompensa: $35.000 

### A gangue do Botânico

Formada por seu capitão o Fritz, o Botânico conhecido por suas balas letais que contém sementes de plantas que crescem numa velocidade extraordinária e que acabam comendou ou ferindo ainda mais a pessoa que tomou seu tiro. Tornando seu tiro letal. É um botânico que fez experimentos com plantas para conseguir conter o calor dos desertos do oeste, porém seus experimentos acabaram machucando pessoas e as pessoas o viram como um louco e acabaram o condenando. Então, para sobreviver a perseguição e não ir para execução, Fritz, adicionou sementes de suas queridas plantas nas suas balas para elas usarem o corpo das pessoas ou onde quer que fossem parar para seu desenvolvimento próprio. Entrou para a máfia e logo formou sua própria gangue. Temido pelo país inteiro. Recompensa: $50.000

## Features

---

### Dialogue System

Um sistema de diálogo que irá apresentar as palavras aos poucos para ser possível ler melhor conforme o personagem vai falando e não apresentando todo o texto direto e aos poucos apresentando mais texto. No canto esquerdo terá um sprite mais detalhado do rosto da pessoa que está falando para ficar mais atrativo. Os diálogos ficarão na parte inferior da tela centralizado.