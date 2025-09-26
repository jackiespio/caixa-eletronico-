CAIXA ELETRÔNICO (Python)

Este programa simula o funcionamento de um caixa eletrônico, realizando o saque de valores em notas disponíveis.

FUNCIONALIDADE

O usuário informa um valor em reais para saque (mínimo R$ 2,00).

O programa calcula automaticamente a quantidade de notas necessárias para compor o valor solicitado.

São utilizadas notas de: 100, 50, 20, 5 e 2 reais.

O algoritmo sempre prioriza as notas maiores, entregando a menor quantidade possível de cédulas.

COMO USAR

Execute o programa em um ambiente Python (versão 3.x).

Digite o valor desejado para saque.

O programa exibirá a quantidade de notas de cada valor que serão entregues.

Exemplo:
Caixa Eletrônico
Digite um valor para saque (mínimo R$ 2,00): 186

Saque realizado com sucesso:
Notas de 100: 1
Notas de 50: 1
Notas de 20: 1
Notas de 5: 3
Notas de 2: 0

RESTRIÇÕES

O valor mínimo para saque é R$ 2,00.

O programa não verifica se o valor é possível de formar com as notas disponíveis.
Exemplo: se você pedir R$ 3,00, o programa dará 1 nota de R$ 2, mas ficará faltando R$ 1.

POSSÍVEIS MELHORIAS

Verificar se o valor digitado é realmente sacável com as notas disponíveis.

Tratar entradas inválidas (como letras ou números negativos).

Adicionar opção para sacar novamente sem reiniciar o programa
