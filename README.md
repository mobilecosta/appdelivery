PROJETO APP DELIVERY


Plataforma de intermediação de entrega

Cadastros:
	Cadastro dos estabelecimentos – PJ 
	Cadastro dos entregadores – MEI, com emissão de NF fora do APP

Operação:
	Estabelecimento recebe encomenda e digita endereço para entrega na plataforma
	APP dispara chamada para entregadores próximos e disponíveis
		Mais próximo e não fazendo entrega atende, caso esteja fazendo entrega, 		não chama.
		Tal estabelecimento tem entrega para fazer em tal lugar com x km e vai 			pagar x 
		Aceitar ou cancelar ?
			Quem aceitar primeiro leva
 				Se aceitar vai aparecer a foto do entregador
				Retorna mensagem para o estabelecimento “Fulano aceitou e 				está a caminho”
 				O entregador tem 15 minutos para chegar e pegar a entrega
				Vai levar a entrega e finalizar no APP com o recebimento 					(máquina cartão, dinheiro, troco) ou se já estiver pago, só 					finaliza
Como é feita a cobrança:
	Parametrizável conforme exemplo
		Até 3 km 5 reais a partir de 3 km cobra mais 1,25 por km rodado 
		Pagamento semanal, quinzenal ou mensal conforme contrato com o 			entregador 
		Acerta direto com o entregador
Relatorio com dados do entregador/entrega, como: Endereço, Dia, Hora, KM, Valor acertado das entregas

Cobra do Estabelecimento taxa de utilização do APP parametrizável conforme contrato
	Taxa 120 reais mensais ou 60 quinzenal ou 30 semanal (exemplo)
	Taxa por entrega até 3 km 5 reais + 20%  a partir de 3 km cobra mais 1,25 por km rodado + 20%
