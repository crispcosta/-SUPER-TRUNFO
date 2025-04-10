Super Trunfo: Brasil vs Argentina
Como compilar

Para compilar o programa, utilize um compilador C. Por exemplo, com o gcc:

gcc super_trunfo.c -o super_trunfo

Como executar

Após compilar, execute o programa com:

./super_trunfo

Funcionalidades

Cartas pré-definidas: Brasil e Argentina

Atributos disponíveis:

A: Ataque

D: Defesa

R: Recuo

N: Densidade Demográfica (vence o menor valor)

Menu interativo com prevenção de seleção repetida

Comparador de dois atributos

Determina vencedor com base na soma dos valores

Mensagens claras para vitória, derrota ou empate

Tratamento de entradas inválidas usando switch com default

Exemplo de uso
Bem-vindo ao Super Trunfo!

Escolha o primeiro atributo:
A - Ataque
D - Defesa
R - Recuo
N - Densidade Demográfica
> A

Escolha o segundo atributo (diferente do primeiro):
D - Defesa
R - Recuo
N - Densidade Demográfica
> N

Resultado:
Brasil:
Ataque: 80
Densidade Demográfica: 25

Argentina:
Ataque: 75
Densidade Demográfica: 40

Soma - Brasil: 105
Soma - Argentina: 115

Vencedor: Argentina!
