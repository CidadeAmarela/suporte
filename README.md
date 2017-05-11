# suporte

Gestão do **suporte técnico prestado pela equipe de suporte da Cidade Amarela** aos condôminos, na manutenção do condomínio e na inclusão dos recursos dos novos condôminos. Neste repositório são registrados os 

A equipe de suporte realiza uma série de pequenos atendimentos e pequenos serviços,  que recisam ser registrados de forma transparente, tanto para a prestação de contas, como para demonstrar como estão sendo entendidas e interpretadas as soluções ou em que velocidade estão sendo resolvidas.

## Registro de horas

Uma série de atividades, principalmente vinculadas à comunicação, toma tempo do atendente mas não pode ser ela mesma registrada como serviço de suporte. Pode-se apenas estimar o valor de horas gastas em função por exemplo do número de e-mails recebidos.  Os membros da equipe devem registrar as horas consumidas no mês na [planilha de suporte-horas](data/suporte-horas.csv). As horas são discriminadas em função do tipo de atividade:

* e-mails: horas gastas abrindo, lendo e avaliando chamados postados por e-mail. <br/>O registro do valor de horas complementa-se pelo registro do número de e-mails de suporte.

* abertura de tickets (issue com *label* referente a suporte): horas gastas na criação do texto-padrão para registro da atividade solicitada, quando o próprio usuário não o fez. <br/>Complementa-se pelo registro do número de issues de autoria do funcionário.

* revisão ou fechamento de tickets: quando o próprio usuário redige a sua solicitação pode ser necessária alguma revisão de texto ou complementação na discusso. <br/>Complementa-se pelo registro do número de issues de autoria de terceiros nos tikets que atendeu e deu fechamento.

Nenhuma outra forma de atendimento é prevista. Foi convencionado que o tempo mínimo por resolução de ticket é de 10 minutos, e que ao gastar mais tempo o suporte deve informá-lo em uma linha separada de baixa na planilha.

## Registros dos  tikets

Estamos usando o [recurso do *Github/issues*](https://help.github.com/articles/about-issues/) para o registro dos tikcets, disponível em  [github.com/CidadeAmarela/suporte/issues](https://github.com/CidadeAmarela/suporte/issues).

Depois que o ticket é registrado pelo usuário ou pelo gerente do suporte, um dos membros da equipe assume o ticket até o seu fechamento.

Ticket de suporte é um dos métodos de suporte mais usados e seguros. Alguns tipos previtos:

* técnico: para sanar dúvidas ou dificuldades sobre o serviço contratado, sugestões, etc.

* financeiro: para anexar comprovante de pagamento, mudança de plano, renovação de domínio, cancelamento, etc.

O histórico dos tickets da CidadeAmarela é público, fica armazenado no presente repositório git, `github.com/CidadeAmarela/suporte`.

## Dúvidas

* COMO ENVIAR UM TICKET DE SUPORTE?<br/> É preciso apenas estar logado no Github. Ver ... com o passo-a-passo.

* COMO LER E RESPONDER O TICKET DE SUPORTE?<br/> Da mesma forma, interagindo pela interface Github, que também permite o uso de e-mail.

* QUAL O PRAZO DE RESPOSTA?<br/> 12hs a 24hs conforme o caso, em dias comerciais.  ... Quando for necessário um agendamento de tarefa, a agenda deve ser comunicada por escrito neste prazo, também na interface do Github. Em alguns casos, se no prazo de 90 horas você não responder o ticket, ele será fechado e então, receberá um email avisando que foi fechado. 

NOTA: Pedimos que não envie tickets de suporte com o mesmo assunto se já existem tickets em aberto. Se já existem tickets em aberto, basta respondê-lo.

-----

## Licença
Todos os conteúdos deste repositório *git*, incluindo conteúdos postados por terceiros nas *issues*, estão sob licença "Creative Commons Atribuição 3.0 Brasil".<br/>
[
&nbsp;&nbsp;![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/16/CC-BY_icon.svg/88px-CC-BY_icon.svg.png)<br/>
&nbsp;&nbsp;&nbsp;**CC-BY-3.0**](https://creativecommons.org/licenses/by/3.0/br/)

