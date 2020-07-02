Projeto Fonte de Tensão 12V, Eletronica para Computacao, BCC 020. ICMC USP São Carlos

Grupo:
  Joao Francisco Caprioli Barbosa Camargo de Pinho
  
  # Simulacão do Falstad
  
  http://tinyurl.com/y78vo6qq
  
  ## Imagem da Simulação
  
  # Componentes usados e preços
    
    Capacitor 470 uF                 R$  0,33
    Transformador 220V -> 24V        R$ 36,01
    Resistor 100 Ohms                R$  0,14
    Resistor 1k                      R$  0,08
    Resistor 120 Ohms                R$  0,23
    Resistor 5k1                     R$  0,08
    Potenciômetro 10k                R$  1,46
    LED Vermelho                     R$  0,24
    Diodo Zener 13V                  R$  0,14
    Ponte Retificadora   25A         R$  4,94
    
    -----------------------------------------
    Total                            R$ 43,65
  # Explicação das peças escolhidas

## Transformador 220V para 24V
  O transformador é necessário para diminuir a voltagem que passa pelo circuito. Um transformador 5:1, ou seja de 220V para 24V, facilitou a escolha das outras peças.

## Ponte Retificadora
  A ponte retificadora serve pra "converter" a corrente alternada em corrente contínua, gerando um polo positivo em cima e um negativo em baixo, olhando para o circuito no Falstad.

## Capacitor 470uF
  O capacitor "estabiliza" a tensão de 24V. Sem o capacitor, a tensão varia muito, e poderia queimar aparelhos conectados à fonte.

## LED Vermelho e Resistor 100 Ohms
  O LED Vermelho se conecta em paralelo com o capacitor. Sem nenhum resistor, o LED "quebraria" o circuito e causaria um curto-circuito, conectando os polos positivo e negativo. O uso de 100 Ohms no resistor é para não baixar muito o brilho do LED e ser um resistor barato.
## Diodo Zener
  O Diodo Zener serve para "separar" a voltagem do circuito. Sendo um Diodo Zener de 13V, ele só deixa aproximadamente 13V irem para o potenciômetro e para o resistor 5.1k do circuito.
## Potenciometro e Resistor 5.1k
  O Potenciômetro serve para o usuário regular a tensão entre 3V e 12V. O potenciômetro de 10k foi escolhido por ser facilmente encontrado e relativamente barato. Por conta do valor do potênciometro, o resistor 5.1k "estabiliza" a voltagem, tal qual o capacitor. Foi escolhido esse resistor por conta do preço.
## Transistor NPN
  
  # Arquivos do circuito e de impressão
  
  
  
  # Apresentação
  
Turma BCC 020
Disciplina: SSC0180-Eletronica para Computacao
Tabela com os precos:



