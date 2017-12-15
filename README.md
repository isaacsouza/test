Algoritmo: CS Rush
Temos um sistema de balanceamento de clientes entre os CS. Dependendo do tamanho do cliente temos que colocar CS's mais experientes para atendê-los. Um CS pode atender mais de um cliente.
Dado o cenário o sistema distribui os clientes com os CS's de capacidade de atendimento mais proxima (maior) do que o tamanho do cliente.
Dada as estruturas CS, que contento id (int) e nivel (inteiro <= 100) e Cliente com id (int) e tamanho (inteiro <= 100) escrever o método que dado um array de CS's e um array de Clientes, distribui os CS's para os clientes apropriados.


Constraints:
 - Todos os CS's devem ter níveis diferentes.
 - Um cliente pode ficar sem ser atendido, nesse caso atribuir para o id 0

Exemplo:

Com o input:
Cs id 1, nivel 20
Cs id 2, nivel 60
Cs id 3, nivel 90
Cs id 4, nivel 40
Cs id 5, nivel 70

Cliente id 1, tamanho 90
Cliente id 2, tamanho 20
Cliente id 3, tamanho 70
Cliente id 4, tamanho 40
Cliente id 5, tamanho 60
Cliente id 6, tamanho 10
Cliente id 7, tamanho 50
Cliente id 8, tamanho 100
Cliente id 9, tamanho 80
Cliente id 10, tamanho 30

Cs: 1 Atende cliente: 2, 6
Cs: 2 Atende cliente: 5, 7
Cs: 3 Atende cliente: 1, 9
Cs: 4 Atende cliente: 4, 10 
Cs: 5 Atende cliente: 3
Cliente 8 não será atendido no momento.
