
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet:

##  1. Introdução

***1.1.  Nome do Grupo***

Daniel Kawata Hara - Danielkh497 

João Levi Cabral Piotto - joaolevicabralpiotto

João Pedro Lorenzetti - joaoLorenzetti

Miguel Nazario Simões - miguelnsimoes

Yaron Gonçalves Buclher - YaronBuclher

***1.2.  Nome do Sistema***

EnergySave

## ***1.3.  Propósito do Sistema***

O objetivo do sistema EnergySave é oferecer uma solução inteligente e eficiente para o monitoramento e a otimização do consumo de energia elétrica em residências e empresas. O sistema visa identificar, em tempo real, padrões de uso energético, emitir alertas sobre consumos excessivos ou anormais e sugerir soluções práticas e imediatas para reduzir desperdícios.

Entre suas principais características estão: o monitoramento contínuo do fluxo de energia, geração de relatórios de desempenho energético, interface acessível via dispositivos móveis e desktops, e integração com sistemas existentes em ambientes empresariais.

O EnergySave traz benefícios significativos como redução de custos com energia elétrica, maior controle e transparência no consumo, e contribuição direta para a sustentabilidade ambiental.

O sistema resolve problemas como a falta de visibilidade sobre o consumo energético, o desperdício não identificado, e a dificuldade em tomar decisões rápidas para otimização de energia. Seu comportamento principal é o de atuar de forma preventiva e orientativa, fornecendo dados e recomendações em tempo real, tanto para usuários residenciais quanto para empresas.

## ***1.2.  Público Alvo***

Este documento se destina aos seguintes perfis envolvidos no desenvolvimento, utilização e validação do sistema EnergySave:

Arquitetos de Software – responsáveis por definir a estrutura e a arquitetura do sistema.

Engenheiros de Software – encarregados de implementar as funcionalidades descritas neste documento.

Testadores (QA) – responsáveis pela validação e verificação do correto funcionamento do sistema.

Clientes (usuários finais) – incluindo tanto usuários residenciais quanto representantes de empresas interessadas na gestão eficiente do consumo energético.

Gerentes de Projeto – para acompanhamento do progresso, prazos e entregas do sistema.

Designers de UX/UI – que atuarão na criação de interfaces amigáveis e funcionais, compatíveis com dispositivos móveis e desktops.

Analistas de Requisitos – encarregados de mapear e manter atualizadas as necessidades dos usuários e stakeholders.

Equipe de Suporte Técnico – que oferecerá atendimento e manutenção aos usuários após o lançamento do sistema.

Especialistas em Energia e Sustentabilidade – que poderão colaborar na validação das sugestões de otimização energética propostas pelo sistema.

Investidores ou Stakeholders Institucionais – interessados na viabilidade e impacto social/ambiental do sistema.

## ***1.3. Descrição dos usuários***

O sistema EnergySave será utilizado por dois perfis principais de usuários finais, cujas necessidades e características são detalhadas a seguir.

## ***Usuários Residenciais***

Perfil: Pessoas comuns que desejam monitorar e reduzir o consumo de energia em suas casas, visando economia financeira e sustentabilidade ambiental.

Características: Geralmente têm conhecimento básico sobre consumo energético, usam dispositivos móveis e desktops para acesso a aplicativos, e buscam soluções práticas e intuitivas.

Objetivos: Controlar o consumo de energia em tempo real, receber alertas sobre usos anormais e seguir sugestões para reduzir a conta de luz.

## ***Usuários Corporativos (Empresas)***

Perfil: Gestores ou responsáveis pela área de manutenção e operação de empresas que buscam otimizar processos e reduzir desperdícios energéticos.

Características: Possuem conhecimento técnico médio a avançado sobre processos industriais ou administrativos, utilizam sistemas integrados e demandam relatórios detalhados para tomada de decisões.

Objetivos: Identificar pontos críticos de desperdício, integrar dados com sistemas existentes e acompanhar relatórios de eficiência energética para reduzir custos operacionais


## ***Usuario Residencial***


<img width="1414" height="2000" alt="Cópia de Nome" src="https://github.com/user-attachments/assets/963cf03b-3d58-4c2e-8d41-724dc68809bd" />



## ***Gestor De Energia Em Empresa***


<img width="1414" height="2000" alt="Nome" src="https://github.com/user-attachments/assets/0f0fcf78-2bc6-40ae-a444-3e05dc2a54aa" />



## ***Análise da Situação Atual: Antes da Introdução da Solução (EnergySave)***

***O que as pessoas fazem?***

***João Silva (usuário residencial):***

João tenta controlar o consumo de energia em sua casa, mas de forma intuitiva. Ele observa sua fatura de energia, tenta controlar o uso de aparelhos de forma geral, mas não tem informações detalhadas sobre o que consome mais energia.

Muitas vezes, ele não tem consciência de padrões de consumo, especialmente em horários de pico ou devido a aparelhos específicos como ar-condicionado e eletrodomésticos.

Ele pode se preocupar com o impacto ambiental, mas não sabe como otimizar o consumo de forma prática.

 ***Carlos Oliveira (gestor de energia em empresa):***

Carlos tenta reduzir os custos de energia na fábrica, mas não possui uma visão clara sobre os pontos de desperdício.

Ele verifica o consumo de energia de maneira isolada e muitas vezes com informações dispersas, sem saber o que pode ser feito para reduzir os gastos de forma eficaz.

Carlos toma decisões com base em relatórios financeiros, mas sem dados detalhados ou uma visão integrada do consumo energético em todos os setores da empresa.

***Quais os artefatos envolvidos?:***

 ***João Silva (usuário residencial):***

Contas de energia: O principal artefato utilizado para medir o consumo, mas sem informações detalhadas sobre o que está consumindo mais energia.

Aparelhos eletrônicos e ar-condicionado: São os principais responsáveis pelo consumo, mas não há controle automatizado ou dados que mostrem exatamente o impacto de cada um desses dispositivos.

Notificações manuais: João pode ajustar manualmente o uso de energia, mas sem dados precisos sobre o impacto real de suas escolhas.

 ***Carlos Oliveira (gestor de energia em empresa):***

Relatórios financeiros e de consumo: Utilizados para verificar os custos de energia, mas sem uma análise detalhada ou comparativa dos setores da empresa.

Sistemas de medição de energia: Pode haver medidores de energia nos setores, mas muitas vezes esses dados são desorganizados e pouco integrados.

Máquinas e equipamentos industriais: Responsáveis pelo alto consumo de energia, mas não há uma visão precisa de quais máquinas ou processos estão consumindo mais ou de como otimizar esses consumos.

## ***O que elas precisam saber?:***

***João Silva (usuário residencial):***

Padrões de consumo: Ele precisa entender como a energia está sendo consumida em sua casa, saber quais aparelhos são mais responsáveis pelo alto consumo e como ajustar seu comportamento para reduzir as despesas.

Alternativas de economia: João precisa de sugestões práticas sobre como economizar energia sem comprometer o conforto de sua casa, como otimizar o uso do ar-condicionado, iluminação e eletrônicos.

Informações em tempo real: Ele precisa de dados em tempo real sobre seu consumo para agir de maneira rápida quando o consumo estiver muito alto ou fora do esperado.

***Carlos Oliveira (gestor de energia em empresa):***

Onde ocorre o desperdício: Carlos precisa saber em quais setores ou máquinas ocorre o maior desperdício de energia e como distribuir melhor os recursos.

Eficiência dos processos: Ele precisa entender quais processos industriais podem ser otimizados para consumir menos energia e quais equipamentos são os maiores responsáveis pelo consumo.

Informações centralizadas e em tempo real: Ele necessita de um sistema que centralize os dados de consumo de energia de toda a empresa para gerar relatórios claros, permitindo a tomada de decisões baseadas em dados precisos e atualizados.

## ***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

 ***1. O que as pessoas fazem?***

***João Silva (usuário residencial):***

Monitora o consumo de energia em tempo real pelo aplicativo.

Recebe alertas automáticos quando há uso excessivo.

Ajusta hábitos e uso de aparelhos de acordo com sugestões do sistema.

Consulta relatórios claros para entender padrões e planejar economias.

***Carlos Oliveira (gestor de energia em empresa):***

Acompanha o consumo energético de todos os setores da fábrica em dashboards integrados.

Identifica rapidamente áreas e máquinas que consomem mais energia.

Implementa estratégias de eficiência energética baseadas nas recomendações do sistema.

Utiliza relatórios para apoiar decisões estratégicas e monitorar resultados.

## ***2. Quais os artefatos envolvidos?***

***João Silva (usuário residencial):***

Aplicativo EnergySave (mobile/desktop).

Sensores inteligentes conectados aos aparelhos.

Relatórios de consumo semanais/mensais.

Notificações automáticas com dicas de economia.

***Carlos Oliveira (gestor de energia em empresa):***

Plataforma EnergySave integrada ao ERP da empresa.

Sensores industriais espalhados pelos setores e máquinas.

Dashboards de desempenho energético.

Relatórios personalizados para tomada de decisão.

## ***3. O que elas precisam saber?***

***João Silva (usuário residencial):***

Quais aparelhos mais consomem energia e em quais horários.

Alertas de uso excessivo em tempo real.

Sugestões práticas para economizar sem perder conforto.

Evolução do consumo ao longo do tempo.

Carlos Oliveira (gestor de energia em empresa):

Quais setores e equipamentos são menos eficientes.

Comparativos de consumo antes e depois das mudanças.

Relatórios integrados unindo dados de energia e custos.

Recomendações de melhorias operacionais e técnicas.

## ***Cenário: Antes***

Antes da aplicação do EnergySave, João e Carlos enfrentam desafios significativos relacionados ao controle e otimização do consumo de energia.

***João Silva (usuário residencial):***

Não tem uma visão clara de como sua casa consome energia, especialmente em relação a aparelhos como ar-condicionado e eletrônicos.

A fatura de energia está aumentando, mas ele não sabe exatamente quais aparelhos ou comportamentos estão contribuindo para esse aumento.

Não há uma forma simples de saber como pode reduzir seu consumo ou ajustar seus hábitos de forma mais eficiente.

***Carlos Oliveira (gestor de energia empresarial):***

A empresa enfrenta dificuldades para identificar pontos específicos de desperdício de energia, pois o consumo é disperso em vários processos e maquinários.

As informações de consumo energético são obtidas de forma desorganizada, o que torna difícil otimizar os custos de forma precisa.

A falta de uma visão integrada sobre a eficiência energética da fábrica dificulta a implementação de soluções eficientes para reduzir os custos operacionais.

## ***Cenário: Depois***

Após a aplicação do EnergySave, ambos os perfis experimentam melhorias significativas no gerenciamento de energia.

João Silva:

Utilizando o sistema EnergySave, João pode monitorar em tempo real o consumo de energia em sua casa, recebendo alertas sempre que o consumo excede limites estabelecidos.

O sistema sugere soluções de otimização de energia, como desligar aparelhos em horários de pico ou investir em dispositivos mais eficientes.

João tem relatórios claros sobre seu consumo energético, permitindo que ele tome decisões informadas sobre como reduzir a conta de energia sem abrir mão do conforto.

Carlos Oliveira:

A empresa de Carlos adota o EnergySave para monitorar o consumo de energia em tempo real, com sensores espalhados por toda a fábrica.

O sistema fornece dados detalhados sobre o uso de energia, permitindo a identificação de áreas e processos ineficientes.

Com relatórios claros e sugestões de melhoria, Carlos pode implementar estratégias mais eficazes para reduzir o desperdício energético e melhorar a eficiência operacional.

A integração do sistema com os processos industriais ajuda na redução de custos operacionais, melhorando a competitividade da empresa no mercado.

## 2. Documentos gerais no repositório

## ***2.1. Requisitos Funcionais***
| Código | Descrição                                                                                                                       | Categoria                      | Dependências (RF / RNF) | Prioridade | MoSCoW |
| ------ | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------ | ----------------------- | ---------- | ------ |
| RF01   | O software deve permitir que o usuário monitore os gastos de energia mensal.                                                    | Monitoramento                  | RNF01, RNF03, RNF04     | Alta       | M      |
| RF02   | O software deve alertar quando o consumo mensal ultrapassar em 20% a média dos últimos 3 meses, em horários fora do expediente. | Notificações                   | RF01, RNF06             | Alta       | M      |
| RF03   | O software deve fornecer soluções para os problemas de gasto energético.                                                        | Otimização                     | RF01, RF02              | Média      | S      |
| RF04   | O software deve mostrar os dados em forma de gráficos de fácil interpretação para o usuário.                                    | Visualização                   | RF01                    | Média      | S      |
| RF05   | O software deve gerar relatórios personalizados de desempenho energético por período.                                           | Relatórios                     | RF01, RF04, RNF10       | Média      | S      |
| RF06   | O software deve permitir comparação de consumo entre diferentes períodos.                                                       | Análise                        | RF01                    | Média      | S      |
| RF07   | O software deve possibilitar cadastro de múltiplos dispositivos ou setores.                                                     | Cadastro / Gestão              | RF01                    | Média      | S      |
| RF08   | O software deve enviar notificações em até 5 segundos após a detecção de um pico de consumo acima de 30% da média horária.      | Notificações                   | RF01, RF02, RNF06       | Alta       | M      |
| RF09   | O software deve oferecer recomendações automáticas de economia de energia baseadas em padrões de consumo.                       | Inteligência / Recomendação    | RF01, RF02, RF03        | Baixa      | C      |
| RF10   | O software deve possibilitar exportação de relatórios em formatos comuns (PDF, Excel).                                          | Relatórios                     | RF05                    | Baixa      | C      |
| RF11   | O sistema deve permitir cadastro e autenticação de usuários com e-mail e senha, garantindo controle de acesso seguro.           | Cadastro / Segurança           | RNF11                   | Alta       | M      |
| RF12   | O sistema deve permitir cadastro e autenticação de usuários com e-mail e senha, garantindo controle de acesso seguro.           | Monitoramento / Confiabilidade | RNF12                   | Média      | S      |






## ***2.2. Requisitos Não Funcionais***
| Código | Descrição                                                                                                                                                           | Categoria        | Dependências (RF / RNF) | Prioridade | MoSCoW |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- | ----------------------- | ---------- | ------ |
| RNF01  | O sistema deve responder às consultas de consumo em tempo real em até 2 segundos.                                                                                   | Desempenho       | RF01, RNF06             | Alta       | M      |
| RNF02  | A interface deve ser responsiva e acessível em navegadores modernos, Android e iOS.                                                                                 | Usabilidade      | —                       | Alta       | M      |
| RNF03  | O software deve sugerir medidas de economia, como ajuste de horários de operação e troca de equipamentos ineficientes.                                              | Confiabilidade   | —                       | Alta       | M      |
| RNF04  | O tráfego de dados entre sensores e servidores deve ser criptografado utilizando TLS 1.3.                                                                           | Segurança        | RF01, RF08              | Alta       | M      |
| RNF05  | O sistema deve permitir armazenamento de, no mínimo, 5 anos de histórico de consumo por usuário.                                                                    | Escalabilidade   | RF01                    | Média      | S      |
| RNF06  | As notificações de alertas de consumo devem ser entregues em até 5 segundos após a detecção do evento.                                                              | Eficiência       | RF08                    | Alta       | M      |
| RNF07  | A interface deve seguir diretrizes de acessibilidade (WCAG 2.1).                                                                                                    | Usabilidade      | RNF02                   | Média      | S      |
| RNF08  | O sistema deve suportar até 50 mil usuários simultâneos mantendo o tempo médio de resposta abaixo de 2 segundos e sem aumento de erros de requisição acima de 0,5%. | Escalabilidade   | RF01, RNF01             | Alta       | M      |
| RNF09  | Atualizações e manutenções devem ser planejadas com no máximo 10 minutos de indisponibilidade.                                                                      | Manutenibilidade | RNF03                   | Média      | S      |
| RNF10  | O sistema deve gerar relatórios em até 10 segundos, mesmo para períodos de 12 meses.                                                                                | Eficiência       | RF05                    | Alta       | M      |
| RNF11  | O sistema deve utilizar mecanismos seguros de autenticação, criptografando credenciais e seguindo boas práticas OWASP para proteger dados de acesso.                | Segurança        | RF11                    | Alta       | M      |
| RNF12  | O sistema deve garantir consistência dos dados em caso de falhas de sensores, descartando informações inválidas e registrando eventos para auditoria e análise.     | Confiabilidade   | RF12                    | Média      | S      |





## ***2.3. Perguntas***

1. Na sua opinião, o monitoramento em tempo real do consumo energético é tecnicamente viável e acessível para residências e pequenas empresas hoje?

2. Quais sensores ou tecnologias você recomendaria para coletar dados de consumo com precisão e segurança?

3. Você vê alguma dificuldade em integrar sensores de medição com um sistema baseado em software (web/mobile)?

4. Acredita que sistemas como o EnergySave podem realmente promover uma redução significativa no consumo de energia? Por quê?

5. Quais estratégias ou algoritmos de análise você considera mais eficazes para sugerir otimizações de consumo energético em tempo real?

6. Em relação à automação, seria possível sugerir ou até acionar desligamentos de equipamentos em horários críticos? Isso é viável ou perigoso?

7. Como você vê a aceitação desse tipo de sistema entre usuários comuns e empresas? Existe resistência ou é algo bem-vindo?
   
8. Quais tipos de dados sobre o consumo energético você considera mais relevantes para gerar relatórios úteis e estratégicos para o usuário?

9. Quais pontos você acredita que merecem mais atenção no desenvolvimento de um sistema como esse (segurança, escalabilidade, precisão, etc.)?

10. Você teria alguma sugestão ou melhoria que poderia tornar o EnergySave mais robusto ou atrativo do ponto de vista técnico ou comercial?

## ***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>*

## ***2.5. Histórias do Usuário***

| **Código** | **História de Usuário**                                                                                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **RF01**   | Como usuário, quero monitorar os gastos de energia mensal para que eu possa acompanhar e controlar meu consumo.                                                            |
| **RF02**   | Como usuário, quero receber alertas quando o consumo mensal ultrapassar em 20% a média dos últimos 3 meses fora do expediente para que eu possa tomar medidas preventivas. |
| **RF03**   | Como usuário, quero que o sistema sugira soluções para problemas de gasto energético para que eu possa reduzir o consumo excessivo.                                        |
| **RF04**   | Como usuário, quero visualizar os dados de consumo em gráficos de fácil interpretação para que eu compreenda rapidamente meu padrão de uso.                                |
| **RF05**   | Como usuário, quero gerar relatórios personalizados de desempenho energético por período para que eu possa analisar e documentar o consumo.                                |
| **RF06**   | Como usuário, quero comparar o consumo entre diferentes períodos para que eu possa identificar mudanças ou tendências.                                                     |
| **RF07**   | Como gestor, quero cadastrar vários dispositivos ou setores para que eu possa acompanhar o consumo de cada um separadamente.                                               |
| **RF08**   | Como usuário, quero ser notificado em até 5 segundos após a detecção de um pico de consumo acima de 30% da média horária para que eu possa agir imediatamente.                                           |
| **RF09**   | Como usuário, quero receber recomendações automáticas de economia com base no padrão de consumo para que eu possa otimizar o uso de energia.                               |
| **RF10**   | Como usuário, quero exportar relatórios em formatos como PDF e Excel para que eu possa compartilhar ou arquivar as informações.                                            |
| **RF11**   | Como administrador, quero permitir o cadastro e autenticação de usuários com e-mail e senha para que o acesso ao sistema seja seguro.                                      |
| **RF12**   | Como usuário, quero me autenticar com e-mail e senha para que meu acesso ao sistema seja seguro e personalizado.                                                           |


## ***2.6. Diagramas de Caso de Uso e Especificações***

<img width="880" height="724" alt="diagramaRequisitos" src="https://github.com/user-attachments/assets/0897b575-4116-4558-87b2-fce39e53b8d4" />

## ***2.7. Diagramas de Atividades***

<img width="720" height="523" alt="JL4NJW~1" src="https://github.com/user-attachments/assets/05dea4f1-b51c-413c-bece-20233d12dcd1" />


## ***2.8. Protótipos***

[Prototipo.pdf](https://github.com/user-attachments/files/22934544/Prototipo.pdf)


## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
