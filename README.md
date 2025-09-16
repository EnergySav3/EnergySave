
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

Perfis de Usuários

Usuários Residenciais

Perfil: Pessoas comuns que desejam monitorar e reduzir o consumo de energia em suas casas, visando economia financeira e sustentabilidade ambiental.

Características: Geralmente têm conhecimento básico sobre consumo energético, usam dispositivos móveis e desktops para acesso a aplicativos, e buscam soluções práticas e intuitivas.

Objetivos: Controlar o consumo de energia em tempo real, receber alertas sobre usos anormais e seguir sugestões para reduzir a conta de luz.

Usuários Corporativos (Empresas)

Perfil: Gestores ou responsáveis pela área de manutenção e operação de empresas que buscam otimizar processos e reduzir desperdícios energéticos.

Características: Possuem conhecimento técnico médio a avançado sobre processos industriais ou administrativos, utilizam sistemas integrados e demandam relatórios detalhados para tomada de decisões.

Objetivos: Identificar pontos críticos de desperdício, integrar dados com sistemas existentes e acompanhar relatórios de eficiência energética para reduzir custos operacionais


<img width="659" height="501" alt="image" src="https://github.com/user-attachments/assets/2cd7acf2-c36c-4e2a-9eee-a88dea813fa8" />

***Análise da situação atual: antes da introdução de sua solução***

O que as pessoas fazem?

Usuários residenciais:

Consultam manualmente as faturas de energia para entender o consumo.

Têm pouca ou nenhuma visibilidade em tempo real do uso energético.

Tentam controlar o consumo de forma intuitiva, sem dados precisos.

Dependem de informações genéricas e conselhos para economizar energia.

Usuários empresariais:

Utilizam medições periódicas e manuais do consumo energético.

Dependem de sistemas fragmentados e não integrados para análise de dados.

Geram relatórios com atraso e de forma manual, dificultando ações rápidas.

Possuem dificuldade para identificar desperdícios energéticos em tempo real.

2. Quais os artefatos envolvidos?

Contas e faturas de energia elétrica impressas ou digitais.

Medidores convencionais analógicos ou digitais, com pouca conectividade.

Planilhas manuais para registro e análise de consumo (em algumas empresas).

Relatórios gerados esporadicamente, geralmente em formatos básicos.

Comunicação verbal ou por e-mail para alertas, quando há algum problema.

3. O que elas precisam saber?

Usuários residenciais:

Entender as informações gerais da conta de energia.

Como economizar energia baseado em dicas genéricas.

Reconhecer padrões básicos de consumo para tentar evitar desperdícios.

Usuários empresariais:

Como interpretar dados periódicos e muitas vezes desatualizados.

Quais setores geram maior consumo, com base em relatórios manuais.

Procedimentos para buscar redução de custos energéticos, ainda que de forma reativa.

***Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:***
O que as pessoas fazem?

Usuários residenciais:

Monitoram o consumo energético em tempo real via aplicativo.

Recebem alertas imediatos sobre uso excessivo ou anormal.

Seguem sugestões personalizadas para otimizar o consumo.

Analisam relatórios detalhados e históricos para controle financeiro e ambiental.

Usuários empresariais:

Acompanham o consumo energético em diferentes setores em dashboards integrados.

Recebem notificações automáticas e relatórios gerenciais detalhados.

Implementam ações rápidas baseadas nas sugestões do sistema para redução de desperdícios.

Integram o EnergySave com sistemas corporativos para análise avançada.

2. Quais os artefatos envolvidos?

Aplicativo móvel e plataforma web responsiva para monitoramento e análise.

Sensores inteligentes e dispositivos conectados para medição em tempo real.

Sistema automatizado de alertas via notificações e e-mails.

Relatórios digitais gerados automaticamente, com gráficos e indicadores.

Banco de dados e sistemas de análise para processamento contínuo dos dados.

3. O que elas precisam saber?

Usuários residenciais:

Como interpretar os dados apresentados em tempo real.

O significado dos alertas e como aplicar as sugestões para reduzir consumo.

Como configurar preferências pessoais no aplicativo.

Usuários empresariais:

Como utilizar dashboards para analisar consumo por setor e identificar desperdícios.

Como interpretar relatórios gerenciais para embasar decisões.

Procedimentos para integrar o sistema com processos internos e responder rapidamente a alertas.

***Cenário: Antes***

*<Preencher com o cenário idealizado antes da aplicação do seu sistema.>*

***Cenário: Depois***

*<Preencher com o cenário idealizado depois da aplicação do seu sistema.>*

## 2. Documentos gerais no repositório

***2.1. Requisitos Funcionais***

*<Link, imagem, arquivo com os requisitos funcionais.>*

***2.2. Requisitos Não Funcionais***

*<Link, imagem, arquivo com os requisitos não funcionais.>*

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
