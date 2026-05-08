# **Key Account Manager (KAM)**
O Key Account Manager é o responsável por garantir o sucesso do cliente e o alinhamento das expectativas entre os parceiros e a equipe técnica da Laon. Ele atua como o elo principal de comunicação, gerenciando o onboarding, o acompanhamento de projetos, a priorização de demandas e a remoção de bloqueios para garantir entregas eficientes e de qualidade.

## **Principais processos executados**
Os principais processos gerenciados pelo KAM e descritos nessa documentação são:
1. [Onboarding de Clientes](#1-onboarding-de-cliente)
2. [Organização e Condução de Reuniões](#2-organização-e-condução-de-reuniões)
3. [Validações e Aprovações formais](#3-validações-e-aprovações)
4. [Gestão de Demandas Pós-entrega](#4-gestão-de-demandas-pós-entrega)
5. [Gerenciamento de Documentações](#5-documentações)
6. [Coletas de contas e acessos](#6-coletas-de-informações)

### **Regras gerais**
Para uma melhor execução do trabalho do KAM seguem-se, também algumas regras gerais:
1. [Diretrizes de comunicação](#7-diretrizes-de-comunicação)
2. [Cronograma operacional](#cronograma-operacional)

### **Cronogramas de projetos**
Todos os projetos seguem uma mesma sequência de etapas, desde sua concepção até a entrega final e acompanhamento:
1. **Onboarding e kickoff**;
2. **Prototipação e definição das regras de negócio**;
3. **Entrega e Validação dos protótipos**;
4. **Desenvolvimento e codificações do sistema**;
5. **Entrega e validação do sistema**;
6. **Acompanhamento pós-entrega e Follow-up**.

## **1. Onboarding de Cliente**
O onboarding é o primeiro contato oficial e define o tom da organização e comunicação do projeto. Assim que confirmada a entrada de um novo cliente deve-se seguir algumas etapas:
### **Identificação dos responsáveis**
1. Identificar quem será o Key Account Manager responsável pelo cliente;
2. Identificar quem será o responsável pelo projeto.
### **Criação do Grupo Oficial do projeto**
1. Criar o grupo oficial de comunicação no WhatsApp;
2. Padronização de nome: "Laon <> Nome do Projeto";
3. Integrantes: KAM do projeto, cliente(s) e responsável(s) internos.
### **Mensagem de Boas Vindas e Agendamento de Kickoff**
1. Após a criação do grupo com o cliente, enviar uma mensagem de boas vindas padronizada;
2. Deve-se agendar a reunião de [kickoff de produto](#kickoff) com a equipe, garantindo no mínimo 48 horas de antecedência para a reunião.
#### **Modelo de mensagem**:
 ```text
 Bom dia/Boa tarde, pessoal! Tudo bem? 
 
 Sejam muito bem-vindos à Laon! Meu nome é Murilo, serei o Key Account Manager de vocês e estarei à frente da comunicação do projeto com vocês e com a nossa equipe. 
 
 Este é o grupo oficial do projeto, por aqui, iremos manter todas as comunicações relacionadas ao projeto, com exceção das aprovações formais que serão via email. 

Para seguirmos nesse processo de onboarding, gostaria de marcar uma reunião de Kickoff com vocês, conseguimos [DATAS E HORÁRIOS DISPONÍVEIS]?
 ```

## **2. Organização e Condução de Reuniões**
Para uma boa organização de reuniões segue-se uma separação em [tipos](#tipos-de-reuniões), com processos definidos para seus [agendamentos](#agendamentos-de-reuniões) e [conduções](#boas-práticas-para-condução-em-reuniões).

### **Tipos de Reuniões**
Os seguintes tipos de reuniões são definidos de acordo com o estágio de desenvolvimento do projeto: 
#### **1. Kickoff**
Reunião inicial com clientes, equipe de Product Design e responsáveis para apresentação do fluxo de criação do projeto e definição de escopo inicial. Ao final da reunião devem-se ter estabelecidos alguns pontos:
1. Definição de escopo macro do projeto: qual é o problema a ser resolvido e quais requisitos devem ser considerados?
2. Modelo de negócio e monetização;
3. Alinhamento de expectativas;
4. Definição de responsáveis.

#### **2. Reuniões de acompanhamento de projeto**
Reuniões com clientes e equipe de Product Design com o obejtivo de definir escopos, funcionalidades, fluxos, regras de negócio e telas do sistema. 

As reuniões devem ser marcadas semanalmente ou de acordo com o andamento do projeto e necessidade. Deve-se atentar para:
1. Coleta de informações necessárias para o desenvolvimento dos protótipos, como regras de negócios, cálculos e valores específicos, identidade visual, etc;
2. Bloqueios e ajustes de rotas no escopo inicial (exceto para projetos de escopos fechados);
3. Sanar pendências da reunião anterior (Dúvidas);
4. Deixar sempre definida a data das próximas reuniões.

#### **3. Reunião final de projeto**
Reuniões com clientes e equipe de Product Design com o obejtivo de formalizar a entrega dos protótipos, sanar dúvidas e coletar possíveis alterações. Após a apresentação das entregas, deve-se questionar o cliente sobre:
1. Existência de CNPJ da empresa;
2. Existência de Domínio e conta AWS para hospedagem do sistema;
3. Coleta de acessos à softwares e/ou contas de terceiros que terão integrações com o sistema; 
As informações poderão ser coletadas em [Reuniões de acompanhamento de desenvolvimento](#reuniões-de-acompanhamento-de-desenvolvimento) de acordo com a necessidade ou prazos definidos (eg: criação de conta AWS depende de CNPJ válido e aprovado);

Veja a seção sobre coleta de [contas e acessos](#6coletas-de-informações).
    
#### **4. Reuniões de acompanhamento de desenvolvimento**
Reuniões com clientes para atualizações do desenvolvimento do projeto e coleta de informações necessárias. Durante as reuniões, deve-se atentar para:
1. Atualizar os cliente quanto ao status dos projetos, informando as funcionalidades em desenvolvimemnto e a etapa em que cada projeto está (as informações devem ser coletadas em daily ou com o tech lead);
2. Apresentar as próximas etapas e planejamento;
3. Coletar itens pendentes de envio (acessos, informações, identidade visual, imagens, arquivos, etc).

Veja a seção sobre coleta de [contas e acessos](#6coletas-de-informações).

#### **5. Reunião de entrega final de produto**
Reunião com clientes para formalização e entrega final do desenvolvimento do projeto, deve-se atentar para:
##### **Antes da reunião**
1. Marcar a reunião de entrega do produto com no mínimo 2 semanas antes da data prevista de entrega final estipulada em contrato;
2. Validar todos os fluxos para a apresentação com no mínimo 3 dias de antecedência da data da reunião de entrega;
3. Caso, durante o processo de validação, sejam encontrados bugs ou alterações a serem realizadas, deve-se criar um card nos modelos já definidos para realização dos itens e validar com o tech lead os prazos;
4. O techlead deve definir se o produto está em condições de apresentação ou se é necessário remarcar a reunião de apresentação.

##### **Durante a reunião**
1. Seguir um fluxo de apresentação pré-planejado, mostrando os principais fluxos do projeto, estruturas de criação, edição e exclusão de dados;
2. Verificar, a cada etapa da apresentação, o bom entendimento do cliente, sanando dúvidas que possam surgir;
3. Coletar bugs ou alterações englobadas no escopo do projeto para ajuste;
4. Coletar toda e qualquer dúvida que possa surgir e que não possua a resposta de imediato, para verificar e porteriormente enviar um retorno via WhatsApp;
5. Informar o cliente do prazo de 15 a 20 dias após a entrega para uso e validação do sistema entregue. Seguir os protocolos de [validação e aprovação para entrega final de produto](#entrega-final-de-produto). 

#### **6. Reuniões de pós-entrega (acompanhamento de produto e follow-up)**
Reuniões pós-entrega são utilizadas para coletar bugs para correção, alterações solicitadas, sanar dúvidas que possam surgir durante o processo de uso ou definir novas fases do projeto. 
##### **Instruções gerais**
1. Após a reunião de entrega, deve-se marcar após 15 ou 20 dias, uma nova reunião para coleta de feedbacks, alterações ou bugs encontrados durante a [validação](#entrega-final-de-produto);
2. Próximas reuniões são marcadas de acordo com a necessidade do cliente, caso necessário, averiguando-se sempre o volume de demandas semanais, pode-se definir uma reunião periódica semanal durante um determinado período, até que o volume das dúvidas e solicitações diminua. 

### **Boas práticas para condução em reuniões:**
Para que todas as reuniões ocorram conforme o esperado e siga o processo definido, observe as seguintes boas práticas:
1. Entrar 5 minutos antes para testar equipamentos como microfone e câmera;
2. Manter sempre a câmera ligada durante as reuniões;
3. Gravar todas as reuniões utilizando o [ReadAI](#8-readai-ou-gravaçãoanálise-de-reuniões);
4. Anotar todos os pontos discutidos e levantados para conferência posterior em [ata de reunião];
5. Sugerir melhorias ou ideias sobre o produto desenvolvido;
6. Auxiliar o time de desenvolvimento de produto a encontrar soluções para as demandas do cliente;
7. Manter a postura entusiasta e engajar o cliente a participar das reuniões, fazendo questionamentos construtivos para o projeto;

### **Agendamentos de reuniões**
Para que tudo siga o processo definido, observe os seguintes pontos para o agendamento das reuniões:
1. Definir objetivo claro para a reunião, baseando-se nos [tipos](#tipos-de-reuniões) descritos;
2. Coletar os emails dos clientes e da equipe interna que participarão da reunião;
3. Verificar disponibilidade da agenda com a equipe e o cliente;
4. Canal de agendamento: Utilizar o google calendar para agendar reuniões;
5. Agendar a reunião na agenda “Laon - Product Design” (Cor cinza);
6. Seguir o padrão de nome: Reunião - Laon & Empresa (Assunto - quando necessário).
7. Convidar apenas quem é necessário.

#### **Boas práticas para agendamentos**
São boas práticas no agendamento das reuniões:
1. Sempre ter horário definido de início e fim, prorrogações e atrasos podem eventualmente ocorrer, mas não devem ser levados como regra;
2. Sempre enviar 2 horários disponíveis na agenda, levando em consideração outras reuniões e horários passados para outros clientes;
3. No dia marcado para a reunião, confirmar a presença do cliente, enviando uma mensagem no grupo do projeto, seguindo o seguinte modelo: ```text
 Bom dia/Boa tarde, pessoal\! Passando para confirmar a nossa reunião hoje às \_\_h.
 ```;
4. Não se deve marcar reuniões seguidas uma de outra, manter sempre um intervalo de pelo menos 1h entre reuniões para evitar imprevistos e deve-se tentar manter apenas uma reunião por turno (Manhã / Tarde);

## **3. Validações e Aprovações**
Após as reuniões de entrega dos protótipos e sistemas desenvolvidos, deve-se solicitar aprovação do cliente, afim de formalizar as entregas.

### **Entrega final dos protótipos**
Após a apresentação final dos protótipos e regras de negócio, bem como a correção de quaisquer pontos que tenham sido levantados nas últimas reuniões, deve-se enviar um email com todos os materiais do projeto em formato PDF para os clientes:
#### **Formalização da aprovação por email**
1. **Destinatários:** Email dos responsáveis pelo projeto, clientes, equipe da laon envolvida e ```dev@laon.com.br```;
2. **Título do Email:**```Aprovação protótipos - (NOME DO PROJETO)```;
3. **Corpo do email:**
```Prezados, bom dia/boa tarde!

    Encaminho em anexo os protótipos do sistema da plataforma NOME DO PROJETO, em formato PDF, juntamente com o link de regras do notion (Link das regras de negócio - Notion).

    Solicitamos, por gentileza, que a validação e aprovação formal sejam realizadas em resposta a este e-mail, para que possamos dar sequência às próximas etapas do projeto e formalizar a entrega final.

    Atenciosamente,  

    NOME  
    Key Account Manager
```
4. Anexos: enviar os PDFs dos protótipos separados por painel;

#### **Regras gerais e Follow-up**
1. Validar aceite formal e por escrito ao email enviado;
2. Caso necessário, deve-se cobrar os clientes via WhatsApp para que formalizem a aprovação dos protótipos via email seguindo o seguinte modelo:
```text 
Bom dia/Boa tarde, pessoal\! Conseguiram validar os protótipos encaminhados? Aguardo a formalização da aprovação via email para darmos prosseguimento no projeto.
```
3. Após o envio, cobrar uma devolutiva ou aprovação formal via email em 24h e a cada 3 dias, ou quando solicitado pelo tech lead do projeto.

### **Entrega final de produto**
Após a reunião de entrega final do desenvolvimento e coleta das devidas alterações e bugs a serem corrigidos de acordo com o escopo. Deve-se aguardar o prazo de 15 dias após a reunião para cobrar uma devolutiva formal do cliente referente ao sistema entregue. 

1. Agendar uma reunião pós-entrega, durante o período de validação, caso mostrem-se necessárias coletas de bugs, alterações englobadas no escopo ou esclarecimento de dúvidas do cliente;
2. Após o período de 15 dias, marcar uma reunião pós-entrega, para coleta de feedbacks, bugs e alterações englobadas pelo escopo. 

#### **Regras gerais e Follow-up**
1. Durante o período de validação, mantenha-se ativo no grupo, a cada 3 dias, verificando o andamento do processo, seguindo o seguinte modelo de mensagem:
```text 
Bom dia/Boa tarde, pessoal\! Passando para verificar como está o processo de validação do sistema, precisam de algum auxílio ou possuem alguma dúvida? Fico à disposição caso possa ajudar em alguma coisa.```

## **4. Gestão de Demandas pós entrega**
Após a entrega final de desenvolvimento do projeto, é comum que apareçam demandas relacionadas à problemas de funcionalidades ou alterações no sistema. Para trata-lás segue-se o processo de gestão de demandas pós-entrega. 

### **Bugs**
Bugs são erros que se apresentam nas funcionalidades desenvolvidas, de forma que não funcionem como definido no escopo do projeto, como por exemplo, ação de resetar senha não funcionando ao logar, campos que deveriam estar preenchidos ou que deveriam ser editáveis e não o são, erros não tratados sendo mostrados no frontend final, etc.

O protocolo de coleta de bugs engloba a [coleta de evidências](#coleta-de-evidências) e [abertura de card](#abertura-de-cards):

#### Coleta de evidências
A coleta de evidências é parte crucial da gestão de demandas pós-entrega, deve-se após comunicado pelo cliente, extrair o máximo possível de informações para que a equipe responsável consiga reproduzir e corrigir o problema. Boas práticas na coleta de evidências incluem:

1. Deve-se identificar o problema e tentar reproduzi-lo;
2. Caso o sistema esteja em produção, deve-se pedir para o cliente um acesso de teste ou que envie um vídeo/prints identificando o problema;
3. Analise o console do navegador (F12) e aba de network e identifique possíveis erros, requisições erradas, payloads e responses que apareçam e que possam auxiliar na identificação do problema;
4. Identifique se o problema que está ocorrendo está dentro do escopo do projeto.

Após a coleta das evidências e identificação do problema, segue-se para a abertura do card.

#### Abertura de Cards
O card deve ser aberto no Kanban do squad correspondente ao projeto, na coluna ```DEV-TICKETS```. Para isso, segue-se o padrão:
##### **Título**
1. Utilizar como padrão: ```Nome do sistema + bug```; 
2. Exemplo: ```Clientela - Bug```;
##### **Descrição ou Subtarefas**
1. Deve-se descrever o caminho ou fluxo até o bug, descrever o problema e o comportamento esperado.
2. Exemplo ```Painel do Usuário \> Clientes \> Adicionar \> “Dados pessoais” \> CPF. O campo de CPF não está permitindo digitar números, deveria ser possível inserir números no campo.```
##### **Anexos**
1. Utilizar a seção de comentários no card do Slack para anexar os arquivos;
2. Enviar arquivos junto com mensagem, a mensagem deve conter o texto: ```Bug (número) - breve descrição```, com o objetivo de identificar a qual demanda criada pertence cada evidência;
3. Os anexos devem conter evidências que auxiliem o responsável identificar o bug, como prints de erro no console, erros de requisição, vídeos demonstrando o fluxo do bug,etc.  
#### **Aviso de abertura de bug**
Após aberto o card deve-se sempre informar na daily do próximo dia, informando o tech lead e realizando uma breve explicação do problema.  
#### **Prazo**
O prazo padrão para correções de bugs é de até 48h, porém deve-se coletar junto à equipe responsável e repassado para o cliente, seguindo a mensagem modelo:
```text
Bom dia/Boa tarde, pessoal\! Sobre o problema (descrever brevemente o problema), temos um prazo para resolução até (colocar prazo). Assim que estiver resolvido trago um retorno para vocês. Fico à disposição caso precisem de mais alguma coisa. 
```
#### **Devolutiva**
Após a devolutiva do problema em daily pela equipe responsável, deve-se validar a correção, confirmando sua execução e solução. Após, informa-se o cliente seguindo a mensagem modelo:
```text 
Bom dia/Boa tarde, pessoal\! Sobre o problema (descrever brevemente o problema), finalizamos a correção/solicitação, se puderem verificar, por gentileza, fico no aguardo e à disposição caso precisem de mais alguma coisa. 
```
1. Deve-se avisar na daily do dia seguinte que houve a entrega da correção e qual foi o retorno do cliente. 

### **Alterações**
Alterações englobam pequenos ajustes de funcionalidades como permitir a edição de campos, alterar modelos de contrato D4Sign, alterar informações de registros do sistema, etc; e alterações estruturais, desenvolvimento de novas funcionalidades não definidas em escopo ou refatoração de já existentes. 

Algumas alterações, dependendo do impacto que possuem nas funcionalidades desenvolvidas, precisam passar por orçamento e aprovação para serem executadas, esse processo é definido pelo techlead.

O processo de execução das alterações passa pelo fluxo:

#### Coleta das informações:
Deve haver um entendimento claro do pedido, em reunião pós-entrega com o cliente deve-se coletar a alteração a ser realizada;

#### **Documento de Alterações**
1. Após definidas as alterações a serem realizadas, deve-se iniciar a construção do documento com a descrição das alterações;
2. Validar as alterações com tech lead se são factíveis levando em consideração o contexto do projeto;  
3. Enviar para o cliente validar o escopo, seguindo a mensagem modelo e anexando o docuemnto em PDF junto com a mensagem:
```text 
Bom dia/Boa tarde/pessoal\! Segue o documento com a descrição das alterações sobre as quais conversamos. Conseguem validar os pontos e as descrições no documento, por gentileza? Fico no aguardo para prosseguirmos com o orçamento
```
3. Caso existam novos itens repetir o processo de descrição e validação do cliente até aprovação final;
4. Após aprovado pelo cliente, avisar o tech lead para revisão;

#### **Documento de orçamento**
1. Após aprovado pelo cliente, deve-se criar o documento de orçamento seguindo o modelo descrito na seção [Orçamento](#orçamentos)
2. Após receber o orçamento finalizado da equipe responsável, enviar email para aprovação do cliente.
3. Email deve conter uma breve descrição dos pontos que constam no documento, datas e prazos e cobrar a formalização de aprovação da proposta via email.
##### **Modelo de email**
1. Destinatários: ```Responsáveis, techlead e o email: dev@laon.com.br```
2. Título: ```Proposta de alterações - Nome do projeto```
3. Corpo do email: 
```text
Prezados, boa tarde\!
Segue em anexo a proposta referente aos desenvolvimentos das funcionalidades solicitadas para o sistema da Nome do projeto.
O prazo estimado para entrega das alterações é de até **xx dias, após o início das atividades no dia xx/xx/xxxx considerando o tempo necessário para as etapas de prototipação, desenvolvimento e testes.
Ficamos no aguardo da aprovação para darmos início. A confirmação pode ser feita diretamente por e-mail, respondendo a esta mensagem.
Qualquer dúvida, estamos à disposição.
Atenciosamente,  
Murilo Schreiner  
Key Account Manager
```
##### **Após envio de email**
1. Cobrar retorno do cliente até que aprove ou negue o orçamento enviado via email.
2. Após o envio, cobrar após 3 dias, cobrar em dias alternados. 
3. Após a proposta aprovada pelo cliente, deve-se comunicar o tech lead para iniciar o desenvolvimento.

#### Abertura de Cards
O card deve ser aberto no Kanban do squad correspondente ao projeto, na coluna ```PD-BRIEFING```. Para isso, segue-se o padrão:
##### **Título**
1. Utilizar como padrão: ```Nome do sistema - Alteração```; 
2. Exemplo: ```Clientela - Alteração ```;
##### **Anexos**
1. Inicialmente anexe o documento de alterações ao card, para manter a equipe ciente;
2. Após gerado o documento de orçamento, anexe ao card e avise o tech lead.
3. O card deve ser criado mesmo que o documento de alterações ainda não esteja concluído, de forma a manter as alterações no planejamento do squad.
##### **Fluxo Kanban**
1. Enquanto o documento de alterações estiver sendo escrito: PD - Briefing;
2. Após envio para validação do cliente: PD - Approval;
3. Após validação do cliente: DEV - Tickets;
4. Após enviar o documento para orçamento: PD - Approval;
##### **Aviso de abertura de card**
Após aberto o card deve-se sempre informar na daily do próximo dia, informando o tech lead e realizando uma breve explicação das alterações solicitadas.

#### Entregas de Alterações e Correções
Após o comunicado da equipe responsável de que a task foi finalizada, deve-se:
1. Verificar se a correção/alteração foi realizada com sucesso, testando o fluxo de ponta a ponta;
2. Caso algum comportamento não seja o esperado, o card deve voltar para a equipe de desenvolvimento para correção;
3. Após validado, solicita-se a validação do cliente com a mensagem modelo:
```text
Bom dia/Boa tarde, pessoal! Subimos a correção/as alterações (descrever brevemente). Poderiam verificar, por gentileza? Fico no aguardo.
```

## **5.Documentações**
### **Atas de Reunião**
Todas as reuniões devem ser gravadas e documentadas. A ata será feita utilizando o relatório gerado pelo Read AI e formatada utilizando IA para se adequar ao modelo padrão.

#### **ReadAI (ou gravação/análise de reuniões)**
1. Todas as reuniões devem ser gravadas com o ReadAI
2. A reunião não deve ser iniciada antes de verificar se o ReadAI está gravando e registrando as informações;
3. Para encerrar a chamada do google meet, deve-se desconectar o ReadAI antes.
4. Após a reunião, acessar o relatório da reunião no painel do ReadAI (<https://app.read.ai/analytics>) e usar o ReadAI para melhorar comunicação e descrever melhor as tarefas, alterações e escrita da ata no modelo utilizando outras IA's generativas.

#### **Modelo e Regras de escrita das atas: **

[Regras - Ata de reunião - Laon Labs](https://docs.google.com/document/d/1ykMCn1TSGIF5OdYx-zNFTzo3t6GRHGIorZR_IDKI5iU/edit?tab=t.0)

1. As atas devem ser enviadas no mesmo dia ou no máximo no próximo dia útil.
2. Padronização de nome de arquivo: Ata de Reunião - Nome do Projeto - DD/MM/AAAA.

#### **Detalhamento Técnico: **

Ao registrar decisões ou solicitações, a ata deve detalhar:

1. **Caminho**: Definir a tela ou local exato da alteração.
2. **Especificação de Campos:** Tipo (Entrada/Saída), dado (numérico, texto, data), obrigatoriedade e origem (estático ou dinâmico);
3. **Lógica e Interação:** Descrever como a alteração afeta outros módulos e qual o fluxo que o usuário deve seguir;
4. **Dashboards:** Especificar métricas, cálculos detalhados e tipo de gráfico (barras, pizza, etc.);
5. **Limitações:** O que pode falhar e quais as exceções da regra de negócio;
6. **Prazos e pendências:** Descrever os itens pendentes e prazos, qual o responsável por executar os pontos em aberto, registrar prazos definidos para novas reuniões ou entregas acordadas com o cliente.

#### **Modelo de email:**

1. **Destinatários:** (Responsáveis, techlead e o email: ```dev@laon.com.br```);
2. **Título:** Ata de Reunião - Laon Labs & (Nome do projeto) - DD/MM/AAAA;
3. **Corpo:** 
```text
Prezados, boa tarde\!
Segue em anexo nossa ata da reunião realizada online/presencialmente no dia DD/MM/AAAA cujo objetivo foi (DESCREVER BREVEMENTE OS PONTOS DISCUTIDOS DURANTE A REUNIÃO SEGUINDO A ESTRUTURA ACIMA).  
          
O documento contém uma descrição dos principais pontos discutidos.   
          
Fico à disposição para qualquer dúvida ou esclarecimento. 
 
Atenciosamente,  
Murilo Schreiner  
 Key Account Manager
 ```
 4. **Anexos:** Anexar a ata em formato PDF;

### **Orçamentos**
Modelo de documento de orçamento:   
[Proposta (Modelo) - Nome do projeto](https://docs.google.com/document/d/1YnW8dOX-Jrw70MZkevMnffqpYq-ptGMzoAgd_cEJ0Jo)  

1. Escopo claro;
2. Os itens devem estar separados por funcionalidade conforme modelo;
3. Abrir um card em dev tickets para que o techlead realize o orçamento;
4. Informar na daily do dia seguinte sobre a abertura do card;
5. Revisar se o documento contém quantidade de horas, prazo, valor e estimativa de início das atividades;

## **6.Coletas de Informações**
Para que os projetos sejam executados, são necessárias alguns acessos e contas para a equipe realizar o deploy do projeto.

#### **Domínio**
PENDENTE
#### **AWS**
AWS: Conta necessária para a configuração do ambiente onde será realizado o deploy do projeto. É necessário que a empresa possua um CNPJ ativo para a criação da conta. O processo pode demorar, por isso é essencial verificar com o cliente no início do processo se já possuem CNPJ, caso não, orientar para criar, pois será necessário para conseguir a AWS; 
DOCUMENTO PENDENTE
#### **Google Play Console (Develper)**
Google Play Console: Caso o projeto inclua o desenvolvimento de aplicativos Android, será necessária a conta do Google Play Console, para realizar o deploy do aplicativo nas lojas. A criação demanda a existência de CNPJ ativo da empresa e pode demorar, por isso é essencial coletar o acesso do desenvolvedor com as permissões necessárias. 
DOCUMENTO PENDENTE
#### **Apple Developer**
Apple Developer:Caso o projeto inclua o desenvolvimento de aplicativos IOS, será necessária a conta do Apple Developer, para realizar o deploy do aplicativo nas lojas. A criação demanda a existência de CNPJ ativo da empresa e pode demorar, por isso é essencial coletar o acesso do desenvolvedor com as permissões necessárias.
DOCUEMTNO PENDENTE 

## **7. Diretrizes de Comunicação**
1. Manter a comunicação apenas no canal dos squads, evitando conversas diretas com desenvolvedores e/ou Product Designers, apenas quando estritamente necessário;
2. Manter as comunicações com os clientes sempre nos grupos, evitando conversas paralelas e mantendo todos da equipe cientes do endamento e das decisões tomadas.


## **8. Cronograma Operacional**
### **Segunda-feira:**
1. Atualizar os status de projetos ativos de acordo com a demanda;
2. Validar reuniões já marcadas para a semana;
3. Agendar novas reuniões necessárias;
4. Priorizar demandas da semana.

### **Terça a sexta:**
1. Acompanhamento de reuniões com clientes;
2. Participar nas dailies;
3. Acompanhamento de projetos;
4. Cobranças e follow-ups;
5. Escritas de Documentações:

### Atualização de projetos**
#### Checklist:
1. Status atual (em andamento / bloqueado / entregue)
2. Enviar as fases do projeto;
3. Se em desenvolvimento informar em qual etapa de desenvolvimento se encontra o projeto;
4. Próximos passos;
5. Cobrar informações pendentes por parte do cliente;
6. Checklist de solicitações pendentes de envio por parte do cliente, como contas, documentosm e informações relevantes para o desenvolvimento do projeto.