# Primeira_Instancia_BancoDados_Azure
## Criação inicial de uma instância de banco de dados na Solução de Nuvem Azure.
## Verifique a pasta imagens/BD para prints do procedimento.
### Despesa de capital - Capex
-modelo de consulta de tipos de nuvem
-gasto inicial de dinheiro em infraestrutura física
-As depesas do CapEx têm um valor que se reduz com o tempo

Despesas Operacionais
-Gastar com produtos e serviços conforme necessário, pagamento conforme uso.
-Seja cobrado imediatamente

Modelo baseado em consumo
-Os provedores de serviço em nuvem operam em um modelo baseado em consumo, os usuários finais pagam
pelos recursos que utilizam.
-Melhor provisão de serviços
-São fornecidos preços para recursos e serviços individuais.
-A cobrança é feita com base no uso real
Microsoft learn - mais cursos para fixar

Roteiro de aprendizado
--Benefício da nuvem
	-Alta disponibilidade: se concentra em garantir a disponibilidade maxima, independentemente
de interrupções ou eventos que possam ocorrer.
         -qual porcentagem vai ficar indisponivel, qual porcentagem caracteriza mais tempo e qual 
caracteriza menos tempo

--Escalabilidade
	-capacidade de ajustar recursos para atender à demanda
        -significa que você poderá adicionar mais recursos para lidar melhor com o aumento de demanda

--Elasticidade
	-voce pode adicionar maquinas virtuais ou conteineres por meio da expansao 
	-se houver uma queda na demanda, os recursos implantados poderao ser reduzidos horizontalmente
	(de maneira automatica ou manual)

--Confiabilidade
	-Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável
e resiliente.
	-Com um design descentralizado, a nuvem permite que voce tenha recursos implantados em várias
regioes do mundo
	-Mesmo que ocorra uma catastrofe em uma regiao, as outras regioes ainda estarao em funcionamento.

--Previsibilidade
	-Permite que você avance com confiança , seja no desempenho ou no custo
	-São influenciadas pelo Microsoft Azure Well-Architected Framework.

--Seguranca

	-A nuvem oferece ferramentas de seguranca que atendem às necessidades dos clientes mas,
é importante lembrar que a implementacao de muitas delas devem ser realizadas pelo cliente
	-Se voce quiser o controle maximo da seguranca, a infraestrutura como serviço fornecerá recursos
fisicos, mas permitira que voce gerencie os sistemas operacionais e o software instalado, incluindo aplicacao 
de patches e manutencao
	-Se voce quiser que a aplicacao de patches e a manutencao sejam tratadas automaticamente, as 
implantacoes de plataforma como servico ou software como servico podem ser as melhores estratégias de
nuvem para voce.

--Governança
	-A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que estaja fora de conformidade
com seus padroes corporativos e fornece estrategias de mitigacao
	-Dependendo do seu modelo operacional, patches de software e atualizacoes tambem podem ser aplicados
automaticamente, o que ajuda na governança e segurança.
	-Ao estabelecer uma presença de governança o mais cedo possível, voce poderá manter sua presença
de nuvem atualizada, protegida e bem gerenciada.

--Gerenciabilidade
	-Um dos principais beneficios da computacao em nuvem sao as opcoes de capacidade de gerenciamento.
Há dois tipos de capacidade gerenciamento para computacao em nuvem que voce aprendera nesta serie e ambos
trazem excelentes beneficios.
	-Escalar automaticamente a implantacao de recursos com base na necessidade.
	-implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração
manual.
	-Gerenciamento feito por:
		-Por meio de um portal Web
		-Usando uma interface de linha de comando
		-Usando APIs
		-Usando o PowerShell.

--Conceitos de Nuvem
	--IaaS-infraestrutura como Servico: Servidores e armazenamento;Firewalls/segurança de rede;Planta
física/edificio do datacenter.Servico de nuvem mais flexivel.
	-Voce configura e gerencia o hardware para o seu aplicativo.

	--Paas - Plataforma como serviço:Sistemas Operacionais;Ferramentas de desenvolvedores;análise de negócios
de gerenciamento de database;Incorporando também IaaS.
	-Fornece um ambiente para a criação , o teste e a implantacao de aplicativos de software , sem 
focar no gerenciamento da infraestrutura subjacente.
	-Focado no desenvolvimento de aplicativos. O gerenciamento de plataforma é realizado pelo provedor
de nuvem;

	--SaaS-Software como servico:aplicativo/apps hospedados; Licença de software;Engloba as etapas
anteriores de PaaS e IaaS.
	-Modelo de preco de pagamento conforme o uso; Usuários pagam pelo software que utilizam em um
modelo de assinatura.

--Modelo de Responsabilidade compartilhada - Verificar na pasta imagens foto com grafico sobre isso.
 	-
