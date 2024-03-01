---
sidebar_position: 2
---

# Visão geral

Docs as Code é uma filosofia e prática que trata a documentação com a mesma rigorosidade e processo que o desenvolvimento de software. Essa abordagem aplica princípios e ferramentas típicas do desenvolvimento de software, como controle de versão, revisão de código, testes automatizados e integração contínua, ao processo de criação e manutenção de documentação.

## Princípios-Chave

- **Controle de versão**: Assim como o código-fonte, a documentação é armazenada em sistemas de controle de versão, como Git. Isso facilita o rastreamento de mudanças, colaboração entre vários autores e a manutenção de versões consistentes da documentação com as versões do software.
- **Revisão de código**: A documentação passa por revisões e aprovações semelhantes ao código. Isso melhora a qualidade e a precisão da documentação, garantindo que várias perspectivas sejam consideradas.
- **Automação**: Ferramentas de automação são usadas para testar a precisão da documentação, verificar links quebrados, validar a sintaxe e formatar o texto, de forma semelhante aos testes automatizados no desenvolvimento de software.
- **Integração e Implantação Contínuas**: A documentação é frequentemente integrada e atualizada junto com o ciclo de vida do desenvolvimento de software, assegurando que as mudanças no código sejam refletidas na documentação em tempo real.

## Benefícios

- **Consistência**: Mantém a documentação em sincronia com o código, proporcionando informações precisas e atuais.
- **Colaboração**: Facilita a contribuição de desenvolvedores e técnicos em documentação, promovendo um esforço coletivo.
- **Qualidade**: Com revisões e testes, a qualidade da documentação é aprimorada, reduzindo erros e ambiguidades.
- **Eficiência**: A automação de tarefas repetitivas acelera o processo de atualização e manutenção da documentação.

## Ferramentas Comuns

Algumas ferramentas comuns usadas na abordagem Docs as Code incluem Git para controle de versão, plataformas como GitHub ou GitLab para hospedagem e revisão, sistemas de integração contínua como Jenkins ou Travis CI, e ferramentas de documentação como Sphinx, MkDocs ou Docusaurus.

## O que é o Docusaurus?

O Docusaurus é uma ferramenta de código aberto que se destaca na criação de documentações de projetos de forma eficiente e elegante. Desenvolvido pelo Facebook, ele é especialmente útil para projetos que buscam integrar a filosofia do Docs-as-code, proporcionando um meio simplificado e poderoso de gerenciar a documentação junto ao código-fonte.

## A Integração do Docusaurus com a filosofia Docs-as-code

A filosofia do Docs-as-code enfatiza a importância de tratar a documentação com a mesma seriedade e utilizando as mesmas ferramentas que são aplicadas no desenvolvimento do código. Neste contexto, o Docusaurus emerge como uma solução ideal. Ele permite que os documentos sejam escritos em Markdown, uma linguagem de marcação leve, e armazenados em um repositório de código, facilitando o controle de versão e a colaboração.

## Automatização com CI/CD

Um dos principais desafios no gerenciamento de documentação é manter sua atualização e sincronia com as mudanças no código. Aqui, o Docusaurus se alia à prática de integração contínua e entrega contínua (CI/CD). Essa integração permite automatizar o processo de publicação e atualização da documentação sempre que ocorrem mudanças no repositório do projeto.

Com a configuração apropriada, cada `push` no repositório pode acionar uma pipeline de CI/CD que, por sua vez, executa a construção e a publicação da documentação atualizada. Isso garante que a documentação esteja sempre alinhada com a versão mais recente do código, melhorando a confiabilidade e a acessibilidade das informações para os usuários e desenvolvedores.

Adicionalmente, estou considerando a inclusão de ferramentas específicas para validação ortográfica e de estrutura de arquivos no nosso processo de CI/CD. Essas ferramentas são essenciais para garantir a qualidade e a precisão da documentação, alinhando-as com os padrões estabelecidos. As principais ferramentas que estou avaliando para integrar a nosso fluxo de CI/CD são:

- [Vale.sh](https://vale.sh/): Esta é uma ferramenta de linting de linguagem extremamente versátil e configurável, projetada para validar a escrita em termos de estilo, gramática e legibilidade. Ela pode ser personalizada para seguir uma variedade de guias de estilo, tornando-a ideal para manter a consistência e qualidade na documentação.
- [Grammarly](https://www.grammarly.com/): É uma ferramenta avançada de verificação gramatical e ortográfica, conhecida por sua precisão em detectar uma ampla gama de erros de escrita. Sua integração ao nosso fluxo de CI/CD ajudaria a aprimorar a clareza, a correção gramatical e a eficácia da comunicação em nossos documentos.

A incorporação destas ferramentas no nosso processo de CI/CD não apenas aprimorará a qualidade da nossa documentação, mas também automatizará a revisão de textos, economizando tempo e esforço significativos. Isso assegura que os documentos se mantenham não apenas tecnicamente precisos, mas também bem escritos e fáceis de entender.
