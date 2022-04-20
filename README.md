# ArbitragemNano
# Este é um projeto com o intuito de realizar arbitragem da criptomoeda NANO entre duas corretoras estrangeiras.
# Por ser um mercado descentralizado, cada corretora de criptomoedas possui um preço devido a oferta e demanda serem divergentes em cada sítio, isto é diferentemente da
#bolsa de valores de São Paulo, a B3, todos ativos negociados no mercado secundário precisam passar pela B3. 
Assim, independendente da corretora que está operando para comprar ações, seja XP ou Banco Inter por exemplo isto não afetará o preço do ativo. Isto afeta sim no caso das
criptomoedas pelo motivo já dito anteriormente. 
Assim, vem a ideia de arbitrar entre corretoras, comprar onde está barato e vender onde está mais caro.

A ideia é simples, mas é composta por muitas variáveis tais como integração API com as corretoras, taxas, volatilidade de mercado e escolha do ativo a ser arbitrato.

O ativo escolhido foi a https://nano.org/, ativo com transações quase que instantaneas e rede capaz de ter uma taxa nula de transferencia. Por estar realizando um projeto 
com fim financeiro, é imprescendivel a velocidade e baixo custo que o ativo deve proporcionar e este é o caso com a NANO. Infelizmente não consigo fugir das taxas de saque,
deposito e negociação das corretoras então este estão como variáveis dentro do codigo.

Usando a documentação API da Kraken: https://docs.kraken.com/rest/
Usando a documentação API de cliente da Binance: https://binance-docs.github.io/apidocs/spot/en/#change-log