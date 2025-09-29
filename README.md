
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

Link do Padlet:

## 1. Introdução

***1.1.  Nome do Grupo***

Daniel Kawata Hara - Danielkh497 

João Levi Cabral Piotto - joaolevicabralpiotto

João Pedro Lorenzetti - joaoLorenzetti

Miguel Nazario Simões - miguelnsimoes

Yaron Gonçalves Buclher - YaronBuclher

***1.2.  Nome do Sistema***

EnergySave

***1.3.  Propósito do Sistema***

O objetivo do sistema EnergySave é oferecer uma solução inteligente e eficiente para o monitoramento e a otimização do consumo de energia elétrica em residências e empresas. O sistema visa identificar, em tempo real, padrões de uso energético, emitir alertas sobre consumos excessivos ou anormais e sugerir soluções práticas e imediatas para reduzir desperdícios.

Entre suas principais características estão: o monitoramento contínuo do fluxo de energia, geração de relatórios de desempenho energético, interface acessível via dispositivos móveis e desktops, e integração com sistemas existentes em ambientes empresariais.

O EnergySave traz benefícios significativos como redução de custos com energia elétrica, maior controle e transparência no consumo, e contribuição direta para a sustentabilidade ambiental.

O sistema resolve problemas como a falta de visibilidade sobre o consumo energético, o desperdício não identificado, e a dificuldade em tomar decisões rápidas para otimização de energia. Seu comportamento principal é o de atuar de forma preventiva e orientativa, fornecendo dados e recomendações em tempo real, tanto para usuários residenciais quanto para empresas.

***1.2.  Público Alvo***

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

***1.3. Descrição dos usuários***

O sistema EnergySave será utilizado por dois perfis principais de usuários finais, cujas necessidades e características são detalhadas a seguir.

***Usuários Residenciais***

Perfil: Pessoas comuns que desejam monitorar e reduzir o consumo de energia em suas casas, visando economia financeira e sustentabilidade ambiental.

Características: Geralmente têm conhecimento básico sobre consumo energético, usam dispositivos móveis e desktops para acesso a aplicativos, e buscam soluções práticas e intuitivas.

Objetivos: Controlar o consumo de energia em tempo real, receber alertas sobre usos anormais e seguir sugestões para reduzir a conta de luz.

***Usuários Corporativos (Empresas)***

Perfil: Gestores ou responsáveis pela área de manutenção e operação de empresas que buscam otimizar processos e reduzir desperdícios energéticos.

Características: Possuem conhecimento técnico médio a avançado sobre processos industriais ou administrativos, utilizam sistemas integrados e demandam relatórios detalhados para tomada de decisões.

Objetivos: Identificar pontos críticos de desperdício, integrar dados com sistemas existentes e acompanhar relatórios de eficiência energética para reduzir custos operacionais


***Usuario Residencial***


<img width="1414" height="2000" alt="Cópia de Nome" src="https://github.com/user-attachments/assets/963cf03b-3d58-4c2e-8d41-724dc68809bd" />



***Gestor De Energia Em Empresa***


<img width="1414" height="2000" alt="Nome" src="https://github.com/user-attachments/assets/0f0fcf78-2bc6-40ae-a444-3e05dc2a54aa" />



***Análise da Situação Atual: Antes da Introdução da Solução (EnergySave)***

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

***O que elas precisam saber?:***

***João Silva (usuário residencial):***

Padrões de consumo: Ele precisa entender como a energia está sendo consumida em sua casa, saber quais aparelhos são mais responsáveis pelo alto consumo e como ajustar seu comportamento para reduzir as despesas.

Alternativas de economia: João precisa de sugestões práticas sobre como economizar energia sem comprometer o conforto de sua casa, como otimizar o uso do ar-condicionado, iluminação e eletrônicos.

Informações em tempo real: Ele precisa de dados em tempo real sobre seu consumo para agir de maneira rápida quando o consumo estiver muito alto ou fora do esperado.

***Carlos Oliveira (gestor de energia em empresa):***

Onde ocorre o desperdício: Carlos precisa saber em quais setores ou máquinas ocorre o maior desperdício de energia e como distribuir melhor os recursos.

Eficiência dos processos: Ele precisa entender quais processos industriais podem ser otimizados para consumir menos energia e quais equipamentos são os maiores responsáveis pelo consumo.

Informações centralizadas e em tempo real: Ele necessita de um sistema que centralize os dados de consumo de energia de toda a empresa para gerar relatórios claros, permitindo a tomada de decisões baseadas em dados precisos e atualizados.

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***

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

***2. Quais os artefatos envolvidos?***

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

***3. O que elas precisam saber?***

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

***Cenário: Antes***

Antes da aplicação do EnergySave, João e Carlos enfrentam desafios significativos relacionados ao controle e otimização do consumo de energia.

***João Silva (usuário residencial):***

Não tem uma visão clara de como sua casa consome energia, especialmente em relação a aparelhos como ar-condicionado e eletrônicos.

A fatura de energia está aumentando, mas ele não sabe exatamente quais aparelhos ou comportamentos estão contribuindo para esse aumento.

Não há uma forma simples de saber como pode reduzir seu consumo ou ajustar seus hábitos de forma mais eficiente.

***Carlos Oliveira (gestor de energia empresarial):***

A empresa enfrenta dificuldades para identificar pontos específicos de desperdício de energia, pois o consumo é disperso em vários processos e maquinários.

As informações de consumo energético são obtidas de forma desorganizada, o que torna difícil otimizar os custos de forma precisa.

A falta de uma visão integrada sobre a eficiência energética da fábrica dificulta a implementação de soluções eficientes para reduzir os custos operacionais.

***Cenário: Depois***

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

***2.1. Requisitos Funcionais***


<img width="798" height="417" alt="Captura de tela 2025-09-26 190851" src="https://github.com/user-attachments/assets/2260ba06-c880-4d1c-a55c-43186cacb5de" />




***2.2. Requisitos Não Funcionais***


<img width="799" height="691" alt="Captura de tela 2025-09-29 003232" src="https://github.com/user-attachments/assets/db381ba9-0871-4928-a9bf-aff4c4fdb92e" />




***2.3. Perguntas***

*<Arquivo com as perguntas realizadas na entrevista .>*

***2.4. Entrevista***

*<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>*

***2.5. Histórias do Usuário***

*<Imagem, arquivo (PDF), link com as Histórias de Usuário.>*

***2.6. Diagramas de Caso de Uso e Especificações***

*<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>*

***2.7. Diagramas de Atividades***

*<Imagem, arquivo (PDF), link com Diagrama de Atividades.>*

***2.8. Protótipos***

*<Imagem, arquivo (PDF), link com Protótipo.>*

## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
