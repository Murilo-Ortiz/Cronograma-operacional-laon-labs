# **Account Manager (AM)**
O Account Manager é o responsável por garantir o sucesso do cliente e o alinhamento das expectativas entre os parceiros e a equipe técnica da Laon. Ele atua como o elo principal de comunicação, gerenciando o onboarding, o acompanhamento de projetos, a priorização de demandas e a remoção de bloqueios para garantir entregas eficientes e de qualidade.

## **Principais processos executados**
Os principais processos gerenciados pelo AM e descritos nessa documentação são:
1. Onboarding de Clientes;
2. Organização e Condução de Reuniões;
3. Validações e Aprovações formais;
4. Coletas de contas e acessos;
5. Gestão de Demandas Pós-entrega;
6. Gerenciamento de documentações;
7. Avaliações e controle de qualidade.


### **Regras gerais**
Para uma melhor execução do trabalho do AM seguem-se, também algumas regras gerais:
8. Diretrizes de comunicação;
9. Cronograma operacional;
10. AM's Quick Start. 

### **Cronogramas de projetos**
Todos os projetos seguem uma mesma sequência de etapas, desde sua concepção até a entrega final e acompanhamento:
1. **Onboarding e kickoff**: primeiro contato com o cliente, onde será apresentado o fluxo de desenvolvimento da Laon, bem como coletadas as primeiras informações sobre o negócio e o produto a ser desenvolvido;
2. **Prototipação e definição das regras de negócio**: etapa onde serão construídos e apresentados o userflow, protótipos e regras de negócio do sistema;
3. **Entrega e Validação dos protótipos**: etapa, após a prototipação do sistema, onde o cliente deve validar todos os fluxos e regras criados, pré início de desenvolvimento;
4. **Desenvolvimento e codificações do sistema**: etapa onde o projeto estará sendo desenvolvido, nessa etapa, o AM irá coletar toda e qualquer informação/arquivo que seja necessária para o produto;
5. **Entrega e validação do sistema**: etapa, após o desenvovimento, onde será realizada uma entrega, apresentação e validação de todos os fluxos desenvolvidos. O cliente deverá utilizar o sistema por determinado tempo, para que possa validar a usabilidade e retornar com ajustes ou alterações a serem realizadas;
6. **Acompanhamento pós-entrega e Follow-up**: após a entrega, alterações e bugs devem ser coletados e repassados para a equipe técnica.

## **1. Onboarding de Cliente**
O onboarding é o primeiro contato oficial e define o tom da organização e comunicação do projeto. Assim que confirmada a entrada de um novo cliente deve-se seguir algumas etapas:

### **1.1 Identificação dos responsáveis**
1. Identificar quem será o Account Manager responsável pelo cliente;
2. Identificar quem será o responsável pelo projeto.

### **1.2 Criação do Grupo Oficial do projeto**
1. Criar o grupo oficial de comunicação no WhatsApp;
2. Padronização de nome: "Laon <> Nome do Projeto";
3. Integrantes: AM do projeto, cliente(s) e responsável(s) internos.

### **1.3 Mensagem de Boas Vindas e Agendamento de Kickoff**
1. Após a criação do grupo com o cliente, enviar uma mensagem de boas vindas padronizada;
2. Deve-se agendar a reunião de [kickoff de produto](#1-kickoff) com a equipe, garantindo no mínimo 48 horas de antecedência para a reunião.

#### **1.3.1 Modelo de mensagem**:
 ```text
 Bom dia/Boa tarde, pessoal! Tudo bem? 
 
 Sejam muito bem-vindos à Laon! Meu nome é Murilo, serei o Account Manager de vocês e estarei à frente da comunicação do projeto com vocês e com a nossa equipe. 
 
 Este é o grupo oficial do projeto, por aqui, iremos manter todas as comunicações relacionadas ao projeto, com exceção das aprovações formais que serão via email. 

Para seguirmos nesse processo de onboarding, gostaria de marcar uma reunião de Kickoff com vocês, conseguimos [DATAS E HORÁRIOS DISPONÍVEIS]?
 ```

## **2. Organização e Condução de Reuniões**
Para uma boa organização de reuniões segue-se uma separação em [tipos](#tipos-de-reuniões), com processos definidos para seus [agendamentos](#agendamentos-de-reuniões) e [conduções](#boas-práticas-para-condução-em-reuniões).

### **2.1 Tipos de Reuniões**
Os seguintes tipos de reuniões são definidos de acordo com o estágio de desenvolvimento do projeto: 

#### **2.1.1 Kickoff**
Reunião inicial com clientes, equipe de Product Design e responsáveis para apresentação do fluxo de criação do projeto e definição de escopo inicial. Ao final da reunião devem-se ter estabelecidos alguns pontos:

1. Definição de escopo macro do projeto: qual é o problema a ser resolvido e quais requisitos devem ser considerados?
2. Modelo de negócio e monetização;
3. Alinhamento de expectativas;
4. Definição de responsáveis.

#### **2.1.2 Reuniões de acompanhamento de projeto**
Reuniões com clientes e equipe de Product Design com o objetivo de definir escopos, funcionalidades, fluxos, regras de negócio e telas do sistema. 

As reuniões devem ser marcadas semanalmente ou de acordo com o andamento do projeto e necessidade. Deve-se atentar para:

1. Coleta de informações necessárias para o desenvolvimento dos protótipos, como regras de negócios, cálculos e valores específicos, identidade visual, etc;
2. Bloqueios e ajustes de rotas no escopo inicial (exceto para projetos de escopos fechados);
3. Sanar pendências da reunião anterior (Dúvidas);
4. Deixar sempre definida a data das próximas reuniões.

#### **2.1.3 Reunião final de projeto**
Reuniões com clientes e equipe de Product Design com o objetivo de formalizar a entrega dos protótipos, sanar dúvidas e coletar possíveis alterações.

Após a apresentação das entregas, deve-se questionar o cliente sobre:

1. Existência de CNPJ da empresa;
2. Existência de Domínio e conta AWS para hospedagem do sistema;
3. Coleta de acessos aos softwares e/ou contas de terceiros que terão integrações com o sistema; 
As informações poderão ser coletadas em [Reuniões de acompanhamento de desenvolvimento](#4-reuniões-de-acompanhamento-de-desenvolvimento) de acordo com a necessidade ou prazos definidos (ex.: criação de conta AWS depende de CNPJ válido e aprovado);

Veja a seção sobre coleta de [contas e acessos](#4-coletas-de-informações).

Após a reunião, deve-se seguir o protocolo de coleta de [aprovação formal de protótipos](#entrega-final-dos-protótipos). 
    
#### **2.1.4 Reuniões de acompanhamento de desenvolvimento**
Reuniões com clientes para atualizações do desenvolvimento do projeto e coleta de informações necessárias. Durante as reuniões, deve-se atentar para:

1. Atualizar os clientes quanto ao status dos projetos, informando as funcionalidades em desenvolvimento e a etapa em que cada projeto está (as informações devem ser coletadas em daily ou com o tech lead);
2. Apresentar as próximas etapas e planejamento;
3. Coletar itens pendentes de envio (acessos, informações, identidade visual, imagens, arquivos, etc).

Veja a seção sobre coleta de [contas e acessos](#4-coletas-de-informações).

#### **2.1.5 Reunião de entrega final de produto**
Reunião com clientes para formalização e entrega final do desenvolvimento do projeto, deve-se atentar para:

##### **2.1.5.1 Antes da reunião**
1. Marcar a reunião de entrega do produto com no mínimo 2 semanas antes da data prevista de entrega final estipulada em contrato;
2. Validar todos os fluxos para a apresentação com no mínimo 3 dias de antecedência da data da reunião de entrega;
3. Caso, durante o processo de validação, sejam encontrados bugs ou alterações a serem realizadas, deve-se criar um card nos modelos já definidos para realização dos itens e validar com o tech lead os prazos;
4. O tech lead deve definir se o produto está em condições de apresentação ou se é necessário remarcar a reunião de apresentação.

##### **2.1.5.2 Durante a reunião**
1. Seguir um fluxo de apresentação pré-planejado, mostrando os principais fluxos do projeto, estruturas de criação, edição e exclusão de dados;
2. Verificar, a cada etapa da apresentação, o bom entendimento do cliente, sanando dúvidas que possam surgir;
3. Coletar bugs ou alterações englobadas no escopo do projeto para ajuste;
4. Coletar toda e qualquer dúvida que possa surgir e que não possua a resposta de imediato, para verificar e posteriormente enviar um retorno via WhatsApp;
5. Informar o cliente do prazo de 15 a 20 dias após a entrega para uso e validação do sistema entregue. Seguir os protocolos de [validação e aprovação para entrega final de produto](#entrega-final-de-produto). 

#### **2.1.6 Reuniões de pós-entrega (acompanhamento de produto e follow-up)**
Reuniões pós-entrega são utilizadas para coletar bugs para correção, alterações solicitadas, sanar dúvidas que possam surgir durante o processo de uso ou definir novas fases do projeto. 

1. Após a reunião de entrega, deve-se marcar após 15 ou 20 dias, uma nova reunião para coleta de feedbacks, alterações ou bugs encontrados durante a [validação de produto](#entrega-final-de-produto);
2. Próximas reuniões são marcadas de acordo com a necessidade do cliente, caso necessário, averiguando-se sempre o volume de demandas semanais, pode-se definir uma reunião periódica semanal durante um determinado período, até que o volume das dúvidas e solicitações diminua. 

### **2.2 Boas práticas para condução em reuniões:**
Para que todas as reuniões ocorram conforme o esperado para cada tipo e sigam o processo definido, observe as seguintes boas práticas:

1. Entrar 5 minutos antes para testar equipamentos como microfone e câmera;
2. Manter sempre a câmera ligada durante as reuniões;
3. Gravar todas as reuniões utilizando o [ReadAI](#readai-ou-gravação-e-análise-de-reuniões);
4. Anotar pontos importantes discutidos e levantados para conferência posterior em [ata de reunião](#atas-de-reunião);
5. Sugerir melhorias ou ideias sobre o produto desenvolvido;
6. Auxiliar o time de desenvolvimento de produto a encontrar soluções para as demandas do cliente;
7. Manter a postura entusiasta e engajar o cliente a participar das reuniões, fazendo questionamentos construtivos para o projeto;
8. Caso o cliente não compareça na reunião, no horário agendado, enviar mensagem após 5 minutos, cobrando a presença. Caso não tenha retorno, cobrar novamente após 10 e 20 minutos. Após esse horário, informar o cliente que a reunião precisará ser remarcada e trazer os novos horários disponíveis. 

### **2.3 Agendamentos de reuniões**
Para que tudo siga o processo definido, observe os seguintes pontos para o agendamento das reuniões:
1. Definir objetivo claro para a reunião, baseando-se nos [tipos](#tipos-de-reuniões) descritos;
2. Coletar os emails dos clientes e da equipe interna que participarão da reunião;
3. Verificar disponibilidade da agenda com a equipe e o cliente;
4. Canal de agendamento: Utilizar o Google Calendar para agendar reuniões;
5. Agendar a reunião na agenda “Laon - Product Design” (Cor cinza);
6. Seguir o padrão de nome: Reunião - Laon & Nome do Projeto (Assunto - quando necessário).
7. Convidar apenas quem é necessário para a reunião.

#### **2.3.1 Boas práticas para agendamentos**
São boas práticas no agendamento das reuniões:
1. Sempre ter horário definido de início e fim, prorrogações e atrasos podem eventualmente ocorrer, mas não devem ser levados como regra;
2. Sempre enviar 2 horários disponíveis na agenda, levando em consideração outras reuniões e horários passados para outros clientes;
3. No dia marcado para a reunião, confirmar a presença do cliente, enviando uma mensagem no grupo do projeto, seguindo o seguinte modelo: 
```
Bom dia/Boa tarde, pessoal! Passando para confirmar a nossa reunião hoje às _h.
```

4. Não se devem marcar reuniões seguidas uma de outra, manter sempre um intervalo de pelo menos 1h entre reuniões para evitar imprevistos e deve-se tentar manter apenas uma reunião por turno (Manhã / Tarde);

## **3. Validações e Aprovações**
Após as reuniões de entrega dos protótipos e sistemas desenvolvidos, deve-se solicitar aprovação do cliente, a fim de formalizar as entregas.

### **3.1 Entrega final dos protótipos**
Após a [apresentação final dos protótipos](#3-reunião-final-de-projeto) e regras de negócio, bem como a correção de quaisquer pontos que tenham sido levantados nas últimas reuniões, deve-se enviar um email com todos os materiais do projeto em formato PDF para os clientes:
#### **3.1.1 Formalização da aprovação por email**
1. **Destinatários:** Email dos responsáveis pelo projeto, clientes, equipe da laon envolvida e ```dev@laon.com.br```;
2. **Título do Email:** ```Aprovação protótipos - (NOME DO PROJETO)```;
3. **Corpo do email:**
```
Prezados, bom dia/boa tarde!

Encaminho em anexo os protótipos do sistema da plataforma NOME DO PROJETO, em formato PDF, juntamente com o link de regras do notion (Link das regras de negócio no Notion).

Solicitamos, por gentileza, que a validação e aprovação formal sejam realizadas em resposta a este e-mail, para que possamos dar sequência às próximas etapas do projeto e formalizar a entrega final.

Atenciosamente,  

NOME  
Account Manager
```
4. **Anexos:** enviar os PDFs dos protótipos separados por painel e o link do Notion para validação das regras de negócios definidos.

#### **3.1.2 Regras gerais e Follow-up**
Após o envio dos protótipos para validação:
1. Validar aceite formal e por escrito ao email enviado;
2. Caso necessário, deve-se cobrar os clientes via WhatsApp para que formalizem a aprovação dos protótipos via email seguindo o seguinte modelo:
```
Bom dia/Boa tarde, pessoal! Conseguiram validar os protótipos encaminhados? Aguardo a formalização da aprovação via email para darmos prosseguimento no projeto.
```

3. Após o envio, cobrar uma devolutiva ou aprovação formal via email em 24h e a cada 3 dias, ou quando solicitado pelo tech lead do projeto.

### **3.2 Entrega final de produto**
Após a reunião de entrega final do desenvolvimento e coleta das devidas alterações e bugs a serem corrigidos de acordo com o escopo. Deve-se aguardar o prazo de 15 dias após a reunião para cobrar uma devolutiva formal do cliente referente ao sistema entregue. 

1. Agendar uma reunião pós-entrega, durante o período de validação, caso mostrem-se necessárias coletas de bugs, alterações englobadas no escopo ou esclarecimento de dúvidas do cliente;
2. Após o período de 15 dias, marcar uma reunião pós-entrega, para coleta de feedbacks, bugs e alterações englobadas pelo escopo. 

#### **3.2.1 Regras gerais e Follow-up**
1. Durante o período de validação, mantenha-se ativo no grupo, a cada 3 dias, verificando o andamento do processo, seguindo o seguinte modelo de mensagem:
```
Bom dia/Boa tarde, pessoal! Passando para verificar como está o processo de validação do sistema, precisam de algum auxílio ou possuem alguma dúvida? Fico à disposição caso possa ajudar em alguma coisa.
```

## **4. Coletas de Informações**
Para viabilizar a execução e o deploy dos projetos, é fundamental a coleta antecipada de acessos e a criação de contas institucionais. O AM deve validar estes itens após a aprovação dos protótipos.

#### **4.1 Domínio**
O domínio é o endereço virtual do projeto na internet e é essencial para hospedar o sistema web, criar APIs e garantir que os usuários consigam acessar a plataforma.
1. Questionar se o cliente já possui um domínio registrado;
2. Se não possuir, orientar a compra em plataformas como Registro.br ou GoDaddy utilizando o CNPJ da empresa;
3. Após adquirido o domínio, a equipe Laon precisará de acesso à tabela de DNS do domínio, para poder realizar os apontamentos necessários.

#### **4.2 Tabela de DNS**
A tabela de DNS guarda os registros que direcionam o domínio para os servidores corretos. O acesso a essa tabela é indispensável para que a equipe técnica realize os apontamentos necessários para homologação, APIs, chaves de e-mail e publicação do sistema.
1. Identificar onde o domínio do cliente está hospedado (ex: Registro.br, GoDaddy, Cloudflare, HostGator);
2. Orientar o cliente a fornecer o acesso direto à plataforma de hospedagem ou a convidar o e-mail da equipe técnica como administrador do painel de DNS;
3. Caso o cliente prefira não fornecer o acesso direto por questões de segurança, alinhar com o Tech Lead a lista de registros necessários (entradas do tipo A, CNAME, TXT ou MX) e encaminhá-la ao cliente para que a própria equipe dele realize a configuração;
4. Validar com a equipe técnica se os apontamentos propagaram corretamente.

#### **4.3 AWS**
AWS é a plataforma de serviços de computação em nuvem da Amazon. A conta é necessária para a configuração do ambiente onde será realizado o deploy do projeto. 
1. É necessário que a empresa possua um CNPJ ativo para a criação da conta;
2. Orientar a criação da conta. Informar que será necessário um cartão de crédito corporativo e que a aprovação pela AWS pode levar alguns dias;
3. Com a conta criada, solicitar que o cliente crie um usuário IAM com permissões de "AdministratorAccess";
4. Coletar o Access Key ID e o Secret Access Key e repassar de forma segura para a equipe técnica.

Tutorial de criação de conta AWS: [Link](https://drive.google.com/file/d/1mRItGxjCpg0ZcixkwfUMYvVkh1UkLFyS/view?usp=drive_link).

#### **4.4 Google Play Console (Developer)**
Google Play Console é o painel oficial de controle do Google para desenvolvedores Android. Caso o projeto inclua o desenvolvimento de aplicativos Android, será necessária a conta do Google Play Console, para realizar o deploy do aplicativo nas lojas. 
1. A criação demanda de telefone e email para recebimento de código de verificação, cartão internacional para pagamento, website intitucional da empresa, D-U-N-S Number e documentos que comprovem a existência e a autorização do criador da conta de assinar documentos em nome da mesma;
2. Exigir que a conta seja registrada sob o CNPJ da empresa (conta do tipo Organização), para evitar problemas de verificação de identidade.
3. Solicitar a criação de uma conta de desenvolvedor do Google vinculada a um e-mail corporativo do cliente (taxa única de US$ 25);
4. Orientar o cliente a acessar a aba "Usuários e permissões" no painel;
5. Solicitar o envio de um convite para o e-mail da equipe de desenvolvimento com a permissão de "Administrador" ou "Gerente de versões". O email deve ser confirmado com o Tech Lead.

Tutorial de criação de conta Google Play Console: [Link](https://drive.google.com/file/d/1XpnBK-yDOpIJO2NGyec5-hJVF2Yqkvug/view?usp=sharing).

#### **4.5 Apple Developer**
Apple Developer é o programa oficial de desenvolvedores da Apple para o ecossistema iOS. Caso o projeto inclua o desenvolvimento de aplicativos iOS, será necessária a conta do Apple Developer para realizar o deploy do aplicativo nas lojas. 
1. Verificar se o cliente possui o número D-U-N-S (padrão internacional de identificação de empresas). Se não possuir, orientar a solicitação gratuita (pode demorar até 30 dias).
2. Com o D-U-N-S em mãos, orientar a criação da conta Apple Developer do tipo "Organization" (taxa anual de US$ 99). Não aceitar contas do tipo "Individual";
3. Orientar o cliente a acessar o portal App Store Connect;
4. Solicitar que envie um convite para o e-mail da equipe de desenvolvimento com a função de "Administrador" ou "App Manager".

Tutorial de criação de conta Apple Developer: [Link](https://drive.google.com/file/d/1n3ty4-_7l1HX4rswpRhk07MCWZcAV9cp/view?usp=sharing).

#### **4.6 Termos de Uso**
Os termos de uso são o contrato legal que estabelece as regras de utilização da plataforma entre a empresa e o usuário final. Ele protege o cliente legalmente, define responsabilidades de uso e é um critério obrigatório para a aprovação nas lojas de aplicativos.
1. Informar ao cliente que este documento é obrigatório;
2. Solicitar que a assessoria jurídica do cliente redija as regras específicas para o modelo de negócio do software;
3. Coletar o documento finalizado em texto ou um link público para inserção no aplicativo.

#### **4.7 Manual de Marca**
O Manual de Marca (Brandbook) e os ativos de identidade visual são as diretrizes de design que guiam a interface do sistema. Eles garantem que o software seja desenvolvido em total conformidade com a identidade corporativa do cliente. Devem ser coletados:
1. Manual da Marca: Documento em PDF com as regras de aplicação do logo, paleta de cores (códigos HEX ou RGB) e tipografia oficial (fontes);
2. Logotipo: Arquivos do logo em alta resolução, preferencialmente em formato vetorizado (.AI, .EPS ou .SVG) e com fundo transparente (.PNG);
3. Ícones e Elementos: Versão simplificada do logo para aplicação como Favicon (ícone da aba do navegador) e App Icon (ícone para as lojas de aplicativos);
 
4. Casos de ausência de Manual de Marca: Se o cliente possuir apenas o logotipo solto e nenhuma diretriz definida, o AM deve alinhar com a equipe de Product Design e coletar com o cliente as preferências macro (ex: "preferência por tons azuis e estilo minimalista") para que o time técnico defina uma paleta funcional para as telas;

#### **4.8 Políticas de privacidade**
As políticas de privacidade são estruturadas no documento que explica de forma transparente como os dados dos usuários serão coletados, armazenados e utilizados. Ele garante a conformidade com a LGPD e é um requisito bloqueante imposto pela Apple e pelo Google (o app é rejeitado sem ele).
1. Reforçar a obrigatoriedade deste documento devido à LGPD;
2. Solicitar à assessoria jurídica do cliente a redação do documento, detalhando os dados transacionados no app;
3. Coletar um e-mail oficial de contato para exclusão de dados (ex: dpo@empresa.com.br) exigido nas lojas;
4. Coletar o documento final para inserção no sistema e nos painéis de publicação.

#### **4.9 Gateway de Pagamento**
O Gateway de Pagamento é o sistema terceirizado responsável por processar as transações financeiras (cartão de crédito, Pix, boleto) dentro da plataforma. É o motor financeiro do projeto, permitindo a automação de cobranças, recebimentos e estornos com segurança.
1. Definir junto ao cliente qual fornecedor será utilizado (ex: Stripe, Pagar.me, Mercado Pago);
2. Orientar a criação da conta no nome e CNPJ da empresa, e a realização da validação bancária exigida pelo gateway;
3. Coletar as "Chaves de Teste" (Sandbox API Keys) para a equipe iniciar as integrações;
4. Coletar as "Chaves de Produção" (Live API Keys) para habilitar pagamentos reais.

#### **4.10 Serviço de email**
Serviço de email é uma infraestrutura dedicada ao envio de e-mails automatizados do sistema (e-mails transacionais). Garante que mensagens do sistema (recuperação de senha, confirmação de conta, recibos) cheguem à caixa de entrada do usuário sem cair no spam.
1. Definir a ferramenta de disparos transacionais (ex: Amazon SES, SendGrid).
2. Orientar a criação da conta e vinculação do método de pagamento.
3. Coletar as credenciais de API com a equipe do cliente.

#### **4.11 Contato de Suporte**
São os canais oficiais pelos quais o usuário final poderá tirar dúvidas ou reportar problemas sobre a plataforma. É um campo obrigatório no preenchimento das lojas de aplicativos e vital para a experiência e retenção dos usuários.
1. Definir com o cliente quais serão os canais oficiais (E-mail, WhatsApp, Link de Helpdesk).
2. Validar se os canais estão ativos e sendo operados.

## **5. Gestão de Demandas pós-entrega**
Após a entrega final de desenvolvimento do projeto, é comum que apareçam demandas relacionadas a problemas de funcionalidades ou alterações no sistema. Para tratá-las segue-se o processo de gestão de demandas pós-entrega: 

### **5.1 Bugs**
Bugs são erros que se apresentam nas funcionalidades desenvolvidas, de forma que não funcionem como definido no escopo do projeto, como por exemplo, ação de resetar senha não funcionando ao logar, campos que deveriam estar preenchidos ou que deveriam ser editáveis e não o são, erros não tratados sendo mostrados no frontend final, etc.

O protocolo de coleta de bugs engloba a [coleta de evidências](#coleta-de-evidências) e [abertura de card](#abertura-de-cards):

#### 5.1.1 Coleta de evidências
A coleta de evidências é parte crucial da gestão de demandas pós-entrega, deve-se após comunicado pelo cliente, extrair o máximo possível de informações para que a equipe responsável consiga reproduzir e corrigir o problema. Boas práticas na coleta de evidências incluem:

1. Deve-se identificar o problema e tentar reproduzi-lo;
2. Caso o sistema esteja em produção, deve-se pedir para o cliente um acesso de teste ou que envie um vídeo/prints identificando o problema;
3. Analise o console do navegador (F12) e aba de network e identifique possíveis erros, requisições erradas, payloads e responses que apareçam e que possam auxiliar na identificação do problema;
4. Identifique se o problema que está ocorrendo está dentro do escopo do projeto.

Após a coleta das evidências e identificação do problema, segue-se para a abertura do card.

#### 5.1.2 Abertura de Cards
O card deve ser aberto no Kanban do squad correspondente ao projeto, na coluna ```DEV-TICKETS```. Para isso, segue-se o padrão:
##### **5.1.2.1 Título**
1. Utilizar como padrão: ```Nome do sistema - Bug```; 
2. Exemplo: ```Clientela - Bug```.
##### **5.1.2.2 Descrição ou Subtarefas**
1. Deve-se descrever o caminho ou fluxo até o bug, descrever o problema e o comportamento esperado;
2. Exemplo ```Painel do Usuário > Clientes > Adicionar > “Dados pessoais” > CPF. O campo de CPF não está permitindo digitar números, deveria ser possível inserir números no campo.```
##### **5.1.2.3 Anexos**
1. Utilizar a seção de comentários no card do Slack para anexar os arquivos;
2. Enviar arquivos junto com mensagem, a mensagem deve conter o texto: ```Bug (número) - breve descrição```, com o objetivo de identificar a qual demanda criada pertence cada evidência;
3. Os anexos devem conter evidências que auxiliem o responsável identificar o bug, como prints de erro no console, erros de requisição, vídeos demonstrando o fluxo do bug, etc.  
#### **5.1.3 Aviso de abertura de bug**
Após aberto o card deve-se sempre informar na daily do próximo dia, informando o tech lead e realizando uma breve explicação do problema.  
#### **5.1.4 Prazo**
O prazo padrão para correções de bugs é de até 48h, salvo exceções, entretanto deve-se coletar junto à equipe responsável o prazo e repassar para o cliente, quando necessário, seguindo a mensagem modelo:
```text
Bom dia/Boa tarde, pessoal! Sobre o problema (descrever brevemente o problema), temos um prazo para resolução até (colocar prazo). Assim que estiver resolvido trago um retorno para vocês. Fico à disposição caso precisem de mais alguma coisa. 
```
#### **5.1.5 Devolutiva**
Após a devolutiva do problema em daily pela equipe responsável, deve-se validar a correção, confirmando sua execução e solução. Após, informa-se o cliente seguindo a mensagem modelo:
```text 
Bom dia/Boa tarde, pessoal! Sobre o problema (descrever brevemente o problema), finalizamos a correção/solicitação, se puderem verificar, por gentileza, fico no aguardo e à disposição caso precisem de mais alguma coisa. 
```
1. Deve-se avisar na daily do dia seguinte que houve a entrega da correção e qual foi o retorno do cliente. 

### **5.2 Alterações**
Alterações englobam pequenos ajustes de funcionalidades como permitir a edição de campos, alterar modelos de contrato D4Sign, alterar informações de registros do sistema, etc; e alterações estruturais, desenvolvimento de novas funcionalidades não definidas em escopo ou refatoração de já existentes. 

Algumas alterações, dependendo do impacto que possuem nas funcionalidades desenvolvidas, precisam passar por orçamento e aprovação para serem executadas, esse processo é definido pelo Tech Lead responsável pelo projeto.

O processo de execução das alterações passa pelo fluxo:
1. Coleta das informações;
2. Documento de Alterações e aprovação pelo cliente;
3. Orçamento e aprovação;
4. Execução das atividades descritas;
5. Validação e Entrega. 

#### **5.2.1 Coleta das informações**:
Deve haver um entendimento claro do pedido, em reunião pós-entrega com o cliente deve-se coletar a alteração a ser realizada;

#### **5.2.2 Documento de Alterações**
1. Após definidas as alterações a serem realizadas, deve-se iniciar a construção do documento com a descrição das alterações;
2. Validar as alterações com tech lead se são factíveis levando em consideração o contexto do projeto;  
3. Enviar para o cliente validar o escopo, seguindo a mensagem modelo e anexando o documento em PDF junto com a mensagem:
``` 
Bom dia/Boa tarde,pessoal! Segue o documento com a descrição das alterações sobre as quais conversamos. Conseguem validar os pontos e as descrições no documento, por gentileza? Fico no aguardo para prosseguirmos com o orçamento
```
3. Caso existam novos itens repetir o processo de descrição e validação do cliente até aprovação final;
4. Após aprovado pelo cliente, avisar o tech lead para revisão.

#### **5.2.3 Documento de orçamento**
1. Após aprovado pelo cliente, deve-se informar o Tech Lead e coletar com o mesmo se haverá a necessidade de orçamento para as alterações solicitadas;
2. Caso as alterações não precisem de orçamento, elas seguem, dentro do prazo definido pelo Tech Lead, para desenvolvimento. Caso seja necessário orçamento para as alterações, deve-se criar o documento seguindo o modelo descrito na seção [Orçamento](#orçamentos);
3. Após receber o orçamento finalizado da equipe responsável, enviar email para aprovação do cliente;
4. Email deve conter uma breve descrição dos pontos que constam no documento, datas e prazos e cobrar a formalização de aprovação da proposta via email.
##### **5.2.3.1 Modelo de email**
1. Destinatários: ```Responsáveis, tech lead e o email: dev@laon.com.br```
2. Título: ```Proposta de alterações - Nome do projeto```
3. Corpo do email: 
```text
Prezados, boa tarde!
Segue em anexo a proposta referente aos desenvolvimentos das funcionalidades solicitadas para o sistema da Nome do projeto.
O prazo estimado para entrega das alterações é de até xx dias, após o início das atividades no dia xx/xx/xxxx considerando o tempo necessário para as etapas de prototipação, desenvolvimento e testes.
Ficamos no aguardo da aprovação para darmos início. A confirmação pode ser feita diretamente por e-mail, respondendo a esta mensagem.
Qualquer dúvida, estamos à disposição.
Atenciosamente,  
Murilo Schreiner  
Account Manager
```
##### **5.2.3.2 Após envio de email**
1. Cobrar retorno do cliente até que aprove ou negue o orçamento enviado via email;
2. Após o envio, cobrar após 3 dias, cobrar em dias alternados;
3. Após a proposta aprovada pelo cliente, deve-se comunicar o Tech Lead para aplicação de processos internos e iniciar o desenvolvimento.

#### **5.2.4 Abertura de Cards**
O card de alterações deve ser aberto junto com o início da descrição das alterações e deve ser aberto no Kanban do squad correspondente ao projeto, na coluna ```PD-BRIEFING```. Para isso, segue-se o padrão:
##### **5.2.4.1 Título**
1. Utilizar como padrão: ```Nome do sistema - Alteração```; 
2. Exemplo: ```Clientela - Alteração ```.
##### **5.2.4.2 Anexos**
1. Inicialmente anexe o documento de alterações ao card, para manter a equipe ciente;
2. Após gerado o documento de orçamento, anexe ao card e avise o Tech Lead.
3. O card deve ser criado mesmo que o documento de alterações ainda não esteja concluído, de forma a manter as atividades no planejamento do squad.
##### **5.2.4.3 Fluxo Kanban**
1. Enquanto o documento de alterações estiver sendo escrito: ```PD - Briefing```;
2. Após envio para validação do cliente: ```PD - Approval```;
3. Após validação do cliente: ```DEV - Tickets```;
4. Após enviar o documento para orçamento: ```PD - Approval```.
##### **5.2.4.4 Aviso de abertura de card**
Após aberto o card, deve-se sempre informar na daily do próximo dia, informando o tech lead e realizando uma breve explicação das alterações solicitadas.

#### **5.2.5 Entregas de Alterações e Correções**
Após o comunicado da equipe responsável de que a task foi finalizada, deve-se:
1. Verificar se a correção/alteração foi realizada com sucesso, testando o fluxo de ponta a ponta;
2. Caso algum comportamento não seja o esperado, o card deve voltar para a equipe de desenvolvimento para correção;
3. Após validado, solicita-se a validação do cliente com a mensagem modelo:
```
Bom dia/Boa tarde, pessoal! Subimos a correção/as alterações (descrever brevemente). Poderiam verificar, por gentileza? Fico no aguardo.
```

## **6. Documentações**
### **6.1 Atas de Reunião**
Todas as reuniões devem ser gravadas e documentadas. A ata será feita utilizando o relatório gerado pelo Read AI e formatada utilizando IA para se adequar ao modelo padrão. Após finalizada, ela será enviada via email para registro interno e dos clientes. 

#### **6.1.1 ReadAI (ou gravação e análise de reuniões)**
1. Todas as reuniões devem ser gravadas com o ReadAI
2. A reunião não deve ser iniciada antes de verificar se o ReadAI está gravando e registrando as informações;
3. Para encerrar a chamada do google meet, deve-se desconectar o ReadAI antes.
4. Após a reunião, acessar o relatório da reunião no painel do ReadAI (<https://app.read.ai/analytics>) e usar IA's generativas + anotações para formatar o documento no modelo padrão.

#### **6.1.2 Modelo das atas:**

[Regras - Ata de reunião - Laon ](https://docs.google.com/document/d/1ykMCn1TSGIF5OdYx-zNFTzo3t6GRHGIorZR_IDKI5iU/edit?tab=t.0)

1. As atas devem ser enviadas no mesmo dia ou no máximo no próximo dia útil.
2. Padronização de nome de arquivo: Ata de Reunião - Nome do Projeto - DD/MM/AAAA.

#### **6.1.3 Detalhamento Técnico:**

Ao registrar decisões ou solicitações, a ata deve detalhar:

1.**Caminho**: Definir a tela ou local exato da alteração.
2.**Especificação de Campos:** Tipo (Entrada/Saída), dado (numérico, texto, data), obrigatoriedade e origem (estático ou dinâmico);
3.**Lógica e Interação:** Descrever como a alteração afeta outros módulos e qual o fluxo que o usuário deve seguir;
4.**Dashboards:** Especificar métricas, cálculos detalhados e tipo de gráfico (barras, pizza, etc.);
5.**Limitações:** O que pode falhar e quais as exceções da regra de negócio;
6.**Prazos e pendências:** Descrever os itens pendentes e prazos, qual o responsável por executar os pontos em aberto, registrar prazos definidos para novas reuniões ou entregas acordadas com o cliente.

#### **6.1.4 Modelo de email:**

1.**Destinatários:** (Responsáveis, tech lead e o email: ```dev@laon.com.br```);
2.**Título:** Ata de Reunião - Laon  & (Nome do projeto) - DD/MM/AAAA;
3.**Corpo:** 
```text
Prezados, boa tarde!
Segue em anexo nossa ata da reunião realizada online/presencialmente no dia DD/MM/AAAA cujo objetivo foi (DESCREVER BREVEMENTE OS PONTOS DISCUTIDOS DURANTE A REUNIÃO SEGUINDO A ESTRUTURA ACIMA).  
          
O documento contém uma descrição dos principais pontos discutidos.   
          
Fico à disposição para qualquer dúvida ou esclarecimento. 
 
Atenciosamente,  
Murilo Schreiner  
 Account Manager
 ```
 4.**Anexos:** Anexar a ata em formato PDF;

### **6.2 Orçamentos**
Modelo de documento de orçamento:   
[Proposta (Modelo) - Nome do projeto](https://docs.google.com/document/d/1YnW8dOX-Jrw70MZkevMnffqpYq-ptGMzoAgd_cEJ0Jo)  

1. Escopo claro;
2. Os itens devem estar separados por funcionalidade conforme modelo;
3. Abrir um card em dev tickets para que o tech lead realize o orçamento;
4. Informar na daily do dia seguinte sobre a abertura do card;
5. Revisar se o documento contém quantidade de horas, prazo, valor e estimativa de início das atividades;

## **7. Avaliações e controle de qualidade**
Uma das etapas importantes durante o andamento das atividades de AM, é a coleta de avaliações e controle de qualidade. Nessa etapa, o AM deve coletar informações e feedbacks relacionados ao processo de desenvolvimento Laon, bem como da sua atuação como Account Manager durante o desenvolvimento do projeto. 
### **7.1 Laon - Product Design - NPS**
1. Link do formulário: [Link](https://forms.gle/1Ebf8zbvtM72damDA);
2. Mensagem para enviar junto com o formulário:
   ´´´text
Bom dia, pessoal! Tudo bem?
Estou entrando em contato para pedir ajuda em um ponto muito importante para nós.

Estamos realizando uma avaliação sobre a experiência dos nossos clientes com a equipe de projetos, o feedback é essencial para entendermos o que estamos fazendo bem e, principalmente, onde podemos evoluir.

Preparamos um formulário rápido (leva só alguns minutos) e sua resposta vai contribuir diretamente para a melhoria dos nossos processos e da qualidade das nossas entregas. Se puder nos ajudar, ficaremos muito gratos. Podem responder todos os envolvidos no processo de produtos.

Pesquisa: https://forms.gle/1Ebf8zbvtM72damDA

Desde já, agradeço pelo tempo.
   ´´´
3. Reforçar a resposta do formulário, caso não tenha sido respondido. 

### **7.2 Laon - Account Manager - NPS**
1. Link do formulário: [Link]([https://forms.gle/1Ebf8zbvtM72damDA](https://docs.google.com/forms/d/1ch7Mgjy1_jFqMN3ZfDCHjG7WDoVWkgmsyrV3LbNEk6Q/edit));
2. Mensagem para enviar junto com o formulário:
   ´´´text
Bom dia, pessoal! Tudo bem?
Estou entrando em contato para pedir ajuda em um ponto muito importante para nós.

Estamos realizando uma avaliação sobre a experiência dos nossos clientes com o Account Manager dos projetos, o feedback é essencial para entendermos o que estamos fazendo bem e, principalmente, onde podemos evoluir.

Preparamos um formulário rápido (leva só alguns minutos) e sua resposta vai contribuir diretamente para a melhoria dos nossos processos e da qualidade das nossas entregas. Se puder nos ajudar, ficaremos muito gratos. Podem responder todos os envolvidos no processo de produtos.

Pesquisa: https://docs.google.com/forms/d/1ch7Mgjy1_jFqMN3ZfDCHjG7WDoVWkgmsyrV3LbNEk6Q/edit

Desde já, agradeço pelo tempo.
   ´´´
3. Reforçar a resposta do formulário, caso não tenha sido respondido. 

## **8. Diretrizes de Comunicação**
1. Manter a comunicação apenas no canal dos squads, evitando conversas diretas com desenvolvedores e/ou Product Designers, apenas quando estritamente necessário;
2. Manter as comunicações com os clientes sempre nos grupos, evitando conversas paralelas e mantendo todos da equipe cientes do andamento e das decisões tomadas;
3. Utilizar o número profissional de Key Account, com foto pessoal de caráter profissional e nome ```Nome Account Manager Laon```.

## **9. Cronograma Operacional**
Para monitorar melhor as atividades a serem realizadas pelo AM durante o decorrer da semana, segue-se uma estrutura como base:

1. Atualizar os status de projetos ativos de acordo com a demanda;
2. Validar reuniões já marcadas para a semana;
3. Agendar novas reuniões necessárias;
4. Priorizar demandas da semana;
5. Acompanhamento de reuniões com clientes;
6. Participar nas dailies;
7. Acompanhamento de projetos;
8. Cobranças e follow-ups;
9. Escritas de Documentações:

### **9.1 Atualização de projetos**
Para uma boa atualização dos projetos dos clientes, segue-se um checklist de informações a serem passadas ou requisitadas:
#### Checklist:
1. Status atual (em andamento / bloqueado / entregue);
2. Enviar as fases do projeto;
3. Se em desenvolvimento informar em qual etapa de desenvolvimento se encontra o projeto;
4. Próximos passos;
5. Cobrar informações pendentes por parte do cliente;
6. Checklist de solicitações pendentes de envio por parte do cliente, como contas, documentos e informações relevantes para o desenvolvimento do projeto.

## **10. AM's Quick Start**
Para novos AMs, segue um passo a passo de quais informações, acessos e ferramentas são necessárias inicialmente
