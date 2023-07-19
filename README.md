## Desafio Aplicação de compras :money_with_wings:

- Criar uma aplicação para lançamento de compras com cartão de crédito
- Menu para lançamento de compras
- Exibição da lista de compras realizadas e ordenadas por valor

​		O **menu** é para realizar as compras, ou seja, essas compras deverão ser armazenadas em uma lista e depois essa lista deve ser **exibida** e **ordenada por valor**.

#### Como deverá funcionar:

​		Você vai informar qual o limite do seu cartão de crédito e realizar compras até não desejar mais ou até o limite ser atingido. 

Exemplo:

**Digite o limite do cartão:** 1000

Após teclarmos "Enter", ele solicita uma descrição da compra. Digitamos "sapato".

**Digite a descrição da compra:** sapato

Logo após, ele questiona:

**Digite o valor da compra:** 150

Quando teclamos "Enter", obtemos:

br.com.programa.compras.principal.Compra realizada!

Digite 0 para sair ou 1 para continuar

Vamos continuar para realizar a compra de um armário ultrapassando o limite. 

**Digite a descrição da compra:** armários

**Digite o valor da compra:** 900

Como retorno, obtemos:

Saldo insuficiente!

COMPRAS REALIZADAS:

sapato - 150.0

Saldo do cartão: 850.0

Process finished with exit code 0

​		A outra ideia é que ao finalizar a compra com limite disponível, que as **compras sejam exibidas por ordem de valor** e não na ordem lançada na lista. 

Preenchemos as perguntas com os seguintes valores e informações:

**Digite o limite do cartão:** 1000

E fazemos as compras:

**Digite a descrição da compra:** sapato

**Digite o valor da compra:** 50

Após isso, será exibida a mensagem de compra realizada e se desejamos sair ou continuar. No caso, digitamos o número um para continuar. Preenchemos novamente:

**Digite a descrição da compra:** camisa

**Digite o valor da compra:** 15

Mais uma vez digitamos o número um para continuar e escrevemos:

**Digite a descrição da compra:** calça

**Digite o valor da compra:** 30

Agora, digitamos o número zero para sair. Como retorno, obtemos:

COMPRAS REALIZADAS:

camisa - 15.0

calça - 30.0

sapato - 50.0

Saldo do cartão: 905.0

**Foi exibido na ordem de valor**. 