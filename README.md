# Projeto Fonte de Tensão 12V, Eletrônica para Computação, BCC 020. ICMC USP São Carlos
## Grupo:
  ## Joao Francisco Caprioli Barbosa Camargo de Pinho
  ## 10748500
## O Projeto
Nesse projeto, o grupo deve desenvolver uma fonte de Tensão Variável de 3V a 12V, com capacidade de 100mA. Também, deve anexar ao projeto no GitHub o circuito no site de simulação Falstad, uma imagem do circuito no site, e uma simulação do projeto no EAGLE, junto com a simulação da placa do circuito.


  # Simulacão do Falstad
  
  http://tinyurl.com/ydexx9xs
  
  ## Imagem da Simulação
  ![Imagem da simulação no Falstad](https://github.com/JotaGHz/FonteEletronica/blob/master/falstad.png)
  # Componentes usados e preços
    
    Capacitor 470 uF  25V            R$  0,33
    Transformador 110/220V -> 12+12V R$ 16,45
    Resistor 1k *3                   R$  0,24
    Resistor 120 Ohms                R$  0,23
    Resistor 5k1                     R$  0,08
    Potenciômetro 10k   MAX=0,2W     R$  1,46
    LED Vermelho                     R$  0,24
    Diodo Zener 13V     MAX=0,5W     R$  0,14
    Ponte Retificadora   25A         R$  4,94
    Transistor NPN BC337             R$  0,17
    -----------------------------------------
    Total                            R$ 24,28
  # Explicação das peças escolhidas

## Transformador 127V para 24V
  O transformador é necessário para diminuir a voltagem que passa pelo circuito. Um transformador 5:1, ou transforma 127V em cerca de 24V, facilitou a escolha das outras peças, e deu uma margem de erro grande para o resto do circuito.

## Ponte Retificadora
  A ponte retificadora serve pra "converter" a corrente alternada em corrente contínua, gerando um polo positivo em cima e um negativo em baixo, olhando para o circuito no Falstad.

## Capacitor 470uF
  O capacitor "estabiliza" a tensão de 24V. O capacitor serve para manter a corrente estável quando ela alternar. Esse capacitor tem tensão máxima suportada de 35V, sendo perfeito para o circuito. Sem o capacitor, a tensão varia muito, e poderia queimar aparelhos conectados à fonte.

## LED Vermelho e Resistor 2k
  O LED Vermelho se conecta em paralelo com o capacitor. Sem nenhum resistor, o LED "quebraria" o circuito e causaria um curto-circuito, conectando os polos positivo e negativo. O uso de 2k Ohms é para diminuir a corrente gasta pelo LED, e ser um resistor fácil de construir em série com 2 resistores 1k.
  
## Diodo Zener
  O Diodo Zener serve para "separar" a voltagem do circuito. Sendo um Diodo Zener de 13V, ele só deixa aproximadamente 13V irem para o potenciômetro e para o resistor 5.1k do circuito.
  
## Potenciometro e Resistor 5.1k
  O Potenciômetro serve para o usuário regular a tensão entre 3V e 12V. O potenciômetro de 10k foi escolhido por ser facilmente encontrado e relativamente barato. Por conta do valor do potênciometro, o resistor 5.1k "estabiliza" a voltagem, tal qual o capacitor. Foi escolhido esse resistor por conta do preço.
  
## Transistor NPN
  O transistor permite a passagem da corrente para a saída, quando a tensão nele chega a 13V, tirando apenas 0.7V, transformando os 13V dados pelo Diodo Zener em 12.3V, com pequenas oscilações.
  # Arquivos do circuito e de impressão
  
  ![Esquemático do EAGLE](https://github.com/JotaGHz/FonteEletronica/blob/master/schem.png)
  
  Esquemático simples do EAGLE, usado para fazer a placa de circuito na imagem seguinte:
  
  ![PCB do Circuito no EAGLE](https://github.com/JotaGHz/FonteEletronica/blob/master/pcb.png)
  
  Imagem do PCB do circuito, usado para construir o circuito pessoalmente.
  
  # Apresentação
  
  Vídeo:
  https://www.youtube.com/watch?v=LuaJpIQDwXM
  
  # Turma BCC 020
  # Disciplina: SSC0180-Eletrônica para Computação
