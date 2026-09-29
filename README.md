# 2WLSTORE — Associação de Produtores e Artesãos Locais

Projeto desenvolvido na disciplina **CARDEVS — Desenvolvimento de Software**, com foco em Engenharia de Requisitos, Git Flow e documentação colaborativa.

## Equipe

- Will Wallac Salgado — Prontuário: **preencher**
- Integrante 2 — Prontuário: **preencher**
- Integrante 3 — Prontuário: **preencher**

## Problema de Negócio

Uma associação regional de artesãos e pequenos produtores de Caraguatatuba comercializa produtos em feiras físicas. Durante a alta temporada, existem dificuldades para controlar o estoque de itens exclusivos, além de perda de vendas por não haver reserva antecipada para turistas. A associação também não possui uma vitrine digital para apresentar o catálogo na baixa temporada. O controle atual é feito em cadernos de papel, o que gera divergências nas vendas e atrasos nos repasses aos artesãos.

## Solução Proposta

Desenvolver uma aplicação web para digitalizar o catálogo, controlar o estoque, permitir reservas antecipadas e melhorar o registro de vendas e repasses aos artesãos.

## Matriz CSD

### Certezas
1. O controle atual é feito em cadernos de papel.
2. A associação perde vendas por não aceitar reservas antecipadas.
3. Não existe uma vitrine digital para exposição do catálogo durante a baixa temporada.

### Suposições
1. Os artesãos poderão cadastrar e atualizar seus próprios produtos.
2. Os turistas utilizarão principalmente smartphones para consultar o catálogo.
3. A associação precisará acompanhar reservas e estoque em uma área administrativa.

### Dúvidas
1. A reserva exigirá pagamento antecipado ou apenas confirmação?
2. Qual será o prazo máximo para retirada de um produto reservado?
3. Quem poderá alterar o estoque: artesão, administrador ou ambos?

## Requisitos Funcionais

- **RF01 — Cadastro de produtos:** O sistema deve permitir que o artesão cadastre produtos informando nome, descrição, preço, foto e quantidade em estoque.
- **RF02 — Controle de estoque:** O sistema deve permitir a atualização da quantidade disponível de cada produto.
- **RF03 — Catálogo digital:** O sistema deve permitir que turistas visualizem os produtos disponíveis em um catálogo digital.
- **RF04 — Reserva antecipada:** O sistema deve permitir que o turista reserve um produto disponível para retirada posterior.
- **RF05 — Registro de vendas e repasses:** O sistema deve permitir que a associação registre vendas e consulte informações necessárias para organizar os repasses aos artesãos.

## Requisitos Não-Funcionais

- **RNF01 — Desempenho:** As principais páginas do sistema devem carregar em até 3 segundos em condições normais de uso.
- **RNF02 — Segurança:** O acesso às funções administrativas deve exigir autenticação e os dados de usuários devem ser protegidos contra acesso não autorizado.
- **RNF03 — Usabilidade:** A interface deve ser responsiva, simples de utilizar e adaptável a smartphones e computadores.

## Tecnologias Previstas

- HTML5
- CSS3
- JavaScript
- Git
- GitHub

## Git Flow

As alterações de código e documentação devem ser feitas em branches próprias e integradas à `main` por meio de Pull Requests.

Exemplos de branches:

- `docs/estrutura-readme`
- `feature/ambiente-dev`

Exemplos de commits semânticos:

- `docs: atualiza documentação do projeto`
- `feat: adiciona estrutura inicial do sistema`

## Backlog Inicial

As User Stories do projeto estão cadastradas na aba **Issues** do repositório, cada uma contendo critérios de aceite e labels apropriadas.
