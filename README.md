<div align="center">

 <img src="https://docusaurus.io/pt-BR/img/docusaurus_keytar.svg" alt="Logo do Docusaurus" width="15%" />

# Docusaurus Example POC
 
</div>

Este repositório no GitHub é destinado a armazenar um experimento que estou desenvolvendo para explorar a filosofia da documentação como código (Docs as Code). Essa abordagem propõe que a documentação seja escrita utilizando as mesmas ferramentas empregadas na codificação do projeto.

Em síntese, a documentação como código é uma técnica de desenvolvimento e publicação da documentação de projetos usando as mesmas ferramentas e processos aplicados no desenvolvimento do código. Isso envolve manter os arquivos de documentação junto aos de código em um repositório, facilitando o controle de versões.

## Por que Docs-as-code?

Optei por estudar essa filosofia por uma necessidade pessoal sentida ao gerenciar a documentação de meus projetos. Frequentemente, as documentações ficavam dispersas em diferentes plataformas, wikis internas e sistemas de gestão de conteúdo, tornando a publicação de novos documentos um processo trabalhoso.

Nesse cenário, surge um grande caos, pois as documentações estão distribuídas em múltiplas plataformas. A busca por informações específicas consome tempo, e, muitas vezes, a documentação encontrada está desatualizada ou duplicada em diferentes locais, exigindo análise para determinar qual versão é a mais recente.

Por exemplo, em minha experiência pessoal, precisei fornecer suporte a um novo colaborador para configurar seu ambiente de desenvolvimento. Haviam várias documentações sobre o mesmo procedimento, mas em plataformas distintas e cada uma redigida de forma única. Isso resultava em instruções conflitantes. As documentações estavam distribuídas da seguinte forma:

- Uma no Google Docs.
- Duas na página de wiki do GitLab.
- Uma no Confluence.

Como mencionado, as documentações tornaram-se confusas ao longo do tempo, pois os autores focaram apenas na entrega inicial, raramente atualizando-as posteriormente. Esse cenário beira o caos.

Diante desses problemas, decidi estudar a filosofia do Docs-as-code para encontrar uma solução definitiva para o gerenciamento da documentação nos meus projetos. O Docs-as-code visa unificar a fonte da documentação, em vez de dispersá-la. Ele centraliza todo o conteúdo, facilitando o acesso e contribuição das equipes.

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

## Conclusão

Este projeto representa apenas o início de uma série de experimentos que estou conduzindo. Estou comprometido em compilar e compartilhar todos os resultados obtidos neste estudo. Planejo publicar um artigo detalhado no Medium, onde abordarei as descobertas e insights adquiridos durante este processo. Para aqueles que têm interesse no tema, recomendo que acompanhem meu perfil no Medium. Fiquem atentos para a publicação deste material, que em breve estará disponível para leitura. Sua visita e feedback serão muito valiosos para o contínuo desenvolvimento deste e de futuros projetos.

- [Medium @reinanhs](https://medium.com/@reinanhs)

## Changelog

Por favor, veja [CHANGELOG](CHANGELOG.md) para obter mais informações sobre o que mudou recentemente.

## Seja um dos contribuidores

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou adicionar recursos a este repositório. Basta criar um fork do projeto, fazer as alterações e enviar um pull request. Suas contribuições serão bem-vindas!

Quer fazer parte desse projeto? leia [como contribuir](CONTRIBUTING.md).

## Licença

Este projeto é licenciado sob a Licença MIT. Veja o arquivo [LICENÇA](LICENSE) para mais detalhes.
