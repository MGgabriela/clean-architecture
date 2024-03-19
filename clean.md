# Arquitetura limpa

Este estudo tem como objetivo esclarecer alguns conceitos de arquitetura limpa, e explica-los de forma sucinta para fácil entendimento.

## O que é arquitetura?

Arquitetura de software é à estrutura fundamental de um sistema de software, composta por componentes, suas propriedades externas visíveis e as relações entre eles descrevendo os principais elementos do sistema, suas responsabilidades e como se relacionam entre si, fornecendo uma visão de alto nível do sistema. É uma abordagem abstrata que define a organização geral do software e como seus diferentes elementos interagem para cumprir os requisitos funcionais e não funcionais do sistema, suas diretrizes e padrões que orientam o design e a implementação do software, promovendo a extensibilidade, manutenibilidade, reusabilidade etc.

O objetivo da arquitetura de software é minimizar os recursos humanos necessários para construir e manter um determinado sistema.

Robert C. Martin. Arquitetura Limpa O Guia do Artesão para Estrutura e Design de Software (Locais do Kindle 536-537). Edição do Kindle. 

## Qual a importância da arquitetura?

A arquitetura de software é importânte pela:

Organização e Estruturação: Ela fornece uma estrutura organizacional para o desenvolvimento do software, ajudando os desenvolvedores a entenderem como os diferentes componentes do sistema se relacionam e interagem entre si.

Facilita a Manutenção: Uma arquitetura bem definida torna mais fácil identificar e corrigir problemas no software. Componentes bem isolados e estruturados tornam as atualizações e correções mais simples e menos propensas a causar efeitos colaterais indesejados.

Reutilização de Componentes: Uma arquitetura modular permite que os desenvolvedores reutilizem componentes em diferentes partes do sistema ou até mesmo em outros projetos, economizando tempo e esforço de desenvolvimento.

Evolução do Software: Uma arquitetura flexível e escalável permite que o software evolua com o tempo, adicionando novas funcionalidades e se adaptando a novos requisitos sem a necessidade de redesenho completo ou reescrita do sistema.

Gerenciamento de Complexidade: O design cuidadoso da arquitetura pode ajudar a reduzir a complexidade do sistema, tornando mais fácil para os desenvolvedores entenderem e trabalharem no software.

Padronização: Uma arquitetura bem definida estabelece padrões e diretrizes para o desenvolvimento de software, garantindo consistência e coesão em todo o projeto.

Desempenho e Segurança: Uma arquitetura bem planejada pode contribuir para o desempenho e segurança do software, garantindo que as considerações de desempenho e segurança sejam levadas em conta desde o início do processo de desenvolvimento.

Comunicação Eficiente: Uma arquitetura clara e bem documentada facilita a comunicação entre membros da equipe de desenvolvimento, clientes e outras partes interessadas, garantindo que todos tenham uma compreensão comum do sistema.

## O que é Arquitetura limpa?

Arquitetura Limpa, é um estilo arquitetural proposto por Robert C. Martin, que promove a criação de sistemas de software com código bem estruturado, altamente testável, e que seja fácil de entender, manter e evoluir ao longo do tempo.

A ideia central é a separação de preocupações em camadas bem definidas, onde cada camada tem uma responsabilidade específica e depende apenas das camadas inferiores, sem conhecer detalhes de implementação dessas camadas. As camadas devem ser organizadas de forma que a lógica de negócio fique isolada das tecnologias externas, como frameworks, banco de dados, UI, etc. Promovendo a manutenção de um código limpo, bem estruturado e de fácil compreensão, facilitando a colaboração entre equipes de desenvolvimento, reduzindo custos de manutenção e possibilitando uma evolução contínua do sistema ao longo do tempo.

## Quais são as características da arquitetura limpa?

Os principais princípios da Arquitetura Limpa incluem:

Independência de Frameworks: A arquitetura deve ser independente de qualquer framework externo. Os detalhes de implementação de frameworks devem ser isolados em camadas externas, garantindo que o núcleo da aplicação não dependa de tecnologias específicas.

Testabilidade: O código deve ser altamente testável, facilitando a escrita de testes automatizados que garantam o comportamento esperado do sistema.

Independência de UI: A lógica de negócio não deve depender da camada de interface com o usuário. Isso permite que diferentes interfaces possam ser facilmente adicionadas ou modificadas sem alterar a lógica subjacente.

Independência de Banco de Dados: O acesso aos dados deve ser separado da lógica de negócio, permitindo a troca de banco de dados sem impactar o restante do sistema.

Independência de Agentes Externos: A arquitetura deve ser projetada de forma a não depender de agentes externos, como serviços web ou dispositivos externos, para funcionar corretamente.

Princípio da Abstração: As decisões de design devem ser baseadas em abstrações que podem ser facilmente compreendidas e modificadas, quando necessário.

Separação de Conceitos: A arquitetura promove a separação clara de conceitos e responsabilidades, como regras de negócio, lógica de apresentação, acesso a dados e interações com o ambiente externo. Isso ajuda a manter o código limpo, coeso e de fácil compreensão.

Princípio SOLID: A Arquitetura Limpa é fortemente baseada nos princípios SOLID (Single Responsibility Principle, Open/Closed Principle, Liskov Substitution Principle, Interface Segregation Principle, Dependency Inversion Principle), que promovem a criação de código modular, flexível e reutilizável.

## Por quê design partners são importantes ?

Os design partners desempenham um papel importante no desenvolvimento de produtos de sucesso, oferecendo perspectivas valiosas, expertise especializada, colaboração criativa, validação de design e outros benefícios que podem impulsionar a inovação e a excelência no design de produtos.

Perspectiva Externa: Os design partners trazem uma perspectiva externa para o desenvolvimento do produto podendo oferecer insights e pontos de vista diferentes dos da equipe interna, ajudando a identificar oportunidades, desafios e soluções que podem ter passado despercebidos.

Experiência Especializada: Muitas vezes, os design partners são especialistas em áreas específicas de design, como design de interação, design de experiência do usuário (UX), design de interface do usuário (UI), design industrial, entre outros. Sua experiência especializada pode ser essencial para resolver problemas complexos de design e garantir a qualidade e eficácia do produto final.

Colaboração Criativa: Trabalhar com design partners promove uma colaboração criativa entre diferentes partes interessadas, incluindo designers, desenvolvedores, stakeholders e usuários finais. Isso ajuda a gerar novas ideias, explorar diferentes abordagens e encontrar soluções inovadoras para os desafios de design.

Validação do Design: Os design partners podem ajudar a validar e iterar o design do produto por meio de testes de usabilidade, pesquisas de usuário e feedback direto. Isso ajuda a garantir que o produto atenda às necessidades e expectativas dos usuários finais, aumentando sua aceitação e sucesso no mercado.

Aceleração do Processo de Design: Com a sua experiência e expertise, os design partners podem acelerar o processo de design, ajudando a evitar armadilhas comuns e a focar nos aspectos mais críticos do projeto. Isso pode resultar em ciclos de desenvolvimento mais curtos e custos mais baixos devido à eficiência no design.

Transferência de Conhecimento: Trabalhar com design partners também oferece uma oportunidade de transferência de conhecimento, permitindo que a equipe interna aprenda e adote melhores práticas de design. Isso pode fortalecer as capacidades internas de design da organização e criar uma cultura centrada no usuário.

Acesso a Recursos e Ferramentas: Os design partners podem trazer consigo recursos adicionais, como ferramentas de design, metodologias de trabalho e redes de contatos, que podem enriquecer o processo de design e melhorar a qualidade do produto final.