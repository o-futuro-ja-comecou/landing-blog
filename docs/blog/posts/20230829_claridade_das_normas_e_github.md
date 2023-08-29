---
date: 2023-08-26
authors: [gabrielbdornas]
description: >
  Our new blog is built with the brand new built-in blog plugin. You can build
  a blog alongside your documentation or standalone
categories:
  - Blog
links:
  - Getting started with Insiders: insiders/getting-started.md#requirements
  - setup/setting-up-a-blog.md#built-in-blog-plugin
---

# Por que o GitHub pode ser utilizado por diversos tipos de equipe para facilitar o entendimento das normas de sua organização.

Recentemente li a newsletter [Psychological Safety and Norm Clarity in Software Engineering Teams](https://newsletter.abinoda.com/p/engineering-team-norm-clarity?utm_source=post-email-title&publication_id=996688&post_id=136340388&isFreemail=true&utm_medium=email) escrita por Abi Noda.
Em seu texto, Noda faz um breve resumo sobre sua leitura do artigo [Psychological safety and norm clarity in software engineering teams](https://dl.acm.org/doi/10.1145/3195836.3195847?utm_source=substack&utm_medium=email)[^1], que examina como a segurança psicológica e a clareza das normas impactam na eficácia de uma equipe[^2].

**Neste sentido, segurança psicológica se refere à crença de um grupo em relação à segurança para expressar opiniões, assumir riscos e cometer erros sem o receio de consequências negativas**.
Ela cria um ambiente no qual os indivíduos se sentem à vontade para compartilhar ideias, fazer perguntas e contribuir de forma autêntica, o que promove a inovação e a colaboração.
Por exemplo, um membro pode se sentir à vontade para apontar problemas em uma solução proposta, mesmo que isso signifique discordar do líder, sabendo que suas preocupações serão valorizadas e consideradas.

Por outro lado, **normas sociais** são regras e padrões de comportamento amplamente aceitos e seguidos por um grupo.
Elas definem o que é considerado apropriado ou esperado em termos de comportamento, interações e desempenho.
Podem incluir a maneira como as reuniões são conduzidas, a pontualidade nas entregas e a qualidade das contribuições individuais.
Um exemplo poderia ser o incentivo para que todos os membros da equipe participem ativamente das reuniões de brainstorming, encorajando colaboração e a diversidade de ideias.

**Sendo assim, este estudo destaca a crescente importância dos fatores humanos, como a segurança psicológica e as normas sociais, para o desempenho da equipe**.
Os resultados indicam que a clareza das normas na equipe tem um impacto mais significativo no desempenho e na satisfação do que a segurança psicológica.
**Sugerindo um enfoque na descrição apropriada das normas existentes, o estudo incentiva líderes a trabalharem o aprimoramento da compreensão do comportamento aceitável como forma de ganho de eficiência**.

Em minha opinião, além de fazer todo sentido pensar em aumento de produtividade quando trabalhamos em um ambiente onde as regras são claras e conhecidas, esta conclusão pode ser integrada com  os conceitos de "coleta" e "clareza" amplamente abordados por David Allen no livro [Getting Things Done](https://www.amazon.com/Getting-Things-Done-Stress-Free-Productivity/dp/0143126563).
Allen defende a importância de coletar todas as tarefas, ideias e informações em um sistema confiável, a fim de liberar a mente para um pensamento claro e criativo.
Ambos os conceitos destacam a importância de se ter uma visão organizada e transparente de tarefas e padrões organizacionais.
Assim como a coleta de tarefas ajuda a aliviar a sobrecarga mental, a descrição apropriada das normas existentes permite que os membros da equipe tenham uma compreensão mais clara das expectativas, eliminando a ambiguidade e promovendo um ambiente de trabalho mais saudável e produtivo.

A grande pergunta é: **como?**
Como conseguir tirar esses conceitos do papel?
Quais ferramentas e práticas podemos utilizar neste processo?
**Para mim, uma ótima ferramenta para introduzir (ou aperfeiçoar) nossos processos de entendimento das normas existentes e o registro adequado de atividades é o GitHub[^3]**.

O GitHub é uma plataforma amplamente utilizada para o gerenciamento de projetos de desenvolvimento de software e **colaboração entre equipes**. Funciona como um repositório online onde os desenvolvedores podem armazenar, compartilhar e colaborar no código-fonte de seus projetos. **Além disso, ele oferece recursos de gestão de projetos que facilitam a coordenação e comunicação entre equipes**.
Uma das funcionalidades mais notáveis para mim é a abertura de "Issues", que para mim pode ser entendida como gestão de tickets.
**Issue são usados para rastrear tarefas, problemas, melhorias ou discussões relacionadas ao projeto**.
Essa funcionalidade permite que os membros da equipe discutam ideias de forma estruturada.
Através delas é possível comunicar-se eficientemente, atribuir tarefas a membros específicos, monitorar o progresso e, **principalmente manter um registro das decisões tomadas.**
Isso simplifica a comunicação, melhora a visibilidade das normas e contribui para uma colaboração mais organizada e eficaz.

Apesar de ter sido inicialmente concebido como uma plataforma para desenvolvimento de software, eu defendo que o GitHub oferece uma abordagem flexível que pode ser aplicada em diversas áreas de trabalho.
Isso acontece porque, embora seja frequentemente associado a código, o código em si nada mais é do que um formato de texto estruturado. Portanto, o GitHub pode ser facilmente adaptado para grupos que não estão focados diretamente no desenvolvimento de software[^4].
Por exemplo, equipes de redação podem usar o GitHub para colaborar na criação e revisão de documentos, acompanhando sugestões e edições através das issues.
Servidores públicos podem usar o GitHub para colaborar na criação e revisão de editais de licitação, ou também para receberem contribuições em cosultas públicas diversas[^5].
Equipes de marketing podem gerenciar campanhas e projetos, atribuindo tarefas, compartilhando materiais e mantendo um registro de discussões relevantes.
Até mesmo equipes de design podem aproveitar o GitHub para rastrear iterações de projetos, gerenciar feedback e manter um histórico de decisões de design.
A flexibilidade da plataforma permite que grupos de diferentes áreas explorem suas funcionalidades para otimizar a colaboração e a gestão de projetos, independentemente do seu foco principal.

Conclusão?

[^1]: Escrito por pesquisadores da Universidade de Tecnologia Chalmers, na Suécia.
[^2]: Tanto o artigo quanto o resumo citados analisam eficiência em equipes de engenharia de software.
[^3]: GitLab e Bitbucket são outros exemplos de ferramentas.
[^4]: Um bom exemplo de issues de repositório para organização de conteúdo que não é código: https://mschermann.github.io/data_viz_reader/
[^5]: A Diretoria Central de Transparência Ativa da CGE/MG utilizou para receber propostas no [Guia de Transparência Ativa](https://transparencia-mg.github.io/guia-transparencia-ativa/v3/organizacao-dos-conteudos/) e no [Manual do Portal de Dados Abertos de Minas Gerais](https://transparencia-mg.github.io/manual-dados-mg/0.1/2.%20Ciclo%20de%20publica%C3%A7%C3%A3o%20de%20dados/005_escolha_das_bases/), inclusive com sistemas de comentários nos rodapés das páginas criadas em sites estáticos (livemark, mkdocs), estilo blog
