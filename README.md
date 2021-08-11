<h3><b>Apresentação</b></h3>
O projeto do sistema de controle de vacinas tem o objetivo de estabelecer um ambiente de supervisão e monitorização das mesmas em Campina Grande — PB. Com o intuito de garantir saúde e bem-estar para todos, serão consideradas e tratadas estratégias de distribuição eficazes da vacina, assim como a fiscalização dos cidadãos para serem devidamente vacinados.
    
<h3><b>Implementação</b></h3>
A supervisão das vacinas seria realizada através do controle de seu estoque, permitindo o cadastro de novos tipos de vacina do sistema, com informações de seu fornecedor e tipo de dose (única ou dupla). Uma vez com a vacina cadastrada, o sistema possibilitará a entrada de vacinas no sistema através de lotes. Caso a vacina recebida seja de dose dupla, metade das doses do lote serão reservadas como de primeira dose e a outra metade reservada como segunda dose. Por outro lado, caso a vacina recebida seja de dose única, todas as doses deste lote serão classificadas como dose única. Além disto, o sistema possibilitará o cadastro de pessoas, para acompanhar o estado de vacinação do sistema. Outra funcionalidade do sistema trata da monitoração das vacinas, indicando:<br></br>
    
<ul><li>Número de vacinas aplicadas, caso a vacina não seja de dose única será dado o número da dosagem (1ª ou 2ª dose).</li>
<li>Número de vacinas disponíveis, caso a vacina não seja de dose única será dado o número da dosagem (1ª ou 2ª dose).</li>
<li>Número de pessoas vacináveis dado o estoque vacinas com dose única ou primeira dose dentre as disponíveis.</li></ul>
    
No escopo do projeto há 2 atores com papéis bem definidos, administrador e aplicador. O papel do administrador é de cadastrar o tipo de vacina, fornecendo as informações do fornecedor e tipo de  dose da vacina (única ou dupla).
    
Por outro lado, o papel do aplicador é de cadastrar os lotes de vacinas (dados os tipos de vacinas disponíveis pelo cadastro do administrador). Além disso, o aplicador poderá realizar o cadastro de uma pessoa a partir de suas informações, como nome, CPF e carteira SUS. Uma pessoa está atrelada a um registro de vacinação, indicando o tipo de vacina ao qual esta pessoa foi vacinada. Ademais, é possível que o aplicante informe ao sistema que uma pessoa foi vacinada com a primeira ou segunda dose (além de verificar se ela já foi vacinada com determinada vacina). Por  fim o aplicante pode consultar o status das vacinas presentes no sistema.
