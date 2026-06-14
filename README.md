# Raiz Up | Agrinho 2026

Projeto desenvolvido por **Eduardo Valentin Carneiro**, estudante do **3º ano D do Ensino Médio** do **Colégio Estadual Marechal Costa e Silva - EFM**, em Cidade Gaúcha, Paraná.

Subcategoria 3: **Programação Front-End com HTML, CSS e JavaScript**.

Tema oficial: **Agro forte, futuro sustentável: equilíbrio entre produção e meio ambiente**.

Site publicado: [eduardovalentincarneiro.github.io/2026](https://eduardovalentincarneiro.github.io/2026/)

## Objetivo

O Raiz Up apresenta, de maneira educativa e interativa, como tecnologia, manejo responsável, proteção da água, conservação do solo e consumo consciente podem fortalecer o agro sem romper o equilíbrio ambiental.

O visitante não apenas lê o conteúdo: suas decisões modificam indicadores, paisagens, quantidade de árvores e peixes, manchetes de 2040 e o crescimento da Semente Viva.

## Como usar

1. Use o botão **Ver resumo** para iniciar a apresentação guiada e conhecer as áreas principais.
2. No **Simulador**, marque práticas sustentáveis, ajuste a intensidade do cuidado e escolha um foco de planejamento.
3. Compare os resultados em **Dois futuros possíveis** arrastando a divisória da paisagem.
4. Explore as fontes oficiais, a linha do tempo e os pontos interativos da fazenda modelo.
5. Complete o quiz e crie um compromisso pessoal para avançar a **Semente Viva**.
6. No **Jornal do Futuro**, atualize e baixe uma capa baseada nas decisões do simulador.
7. Use o menu de configurações e os atalhos para controlar tema, fonte, modo leitura, músicas, sons ambientais e resumo narrado.

Todas as experiências que usam recursos especiais possuem alternativas por botão. O plantio por sopro, por exemplo, pode ser realizado sem liberar o microfone.

## Funcionalidades

- Simulador com cálculo de água, biodiversidade, economia, cidade e equilíbrio.
- Comparação visual entre dois futuros, com árvores, peixes, rios, energia e colheita dinâmicos.
- Jornal de 2040 com manchete, cenário e download em PNG.
- Semente Viva que cresce conforme cinco experiências são concluídas.
- Celebração animada ao completar 100% da jornada.
- Plantio por sopro com alternativa acessível sem microfone.
- Apresentação guiada com personagem, transição de folhas e oito gravações.
- Painel interativo sobre plantio, rios, energia solar, preservação e cidade.
- Quiz educativo, conquistas e mural de compromissos salvos no navegador.
- Dados reais acompanhados de links para fontes oficiais.
- Temas claro e escuro, modo leitura, ajuste de fonte e navegação por teclado.
- Controle de música, sons da natureza e reprodução de resumo gravado.
- Layout responsivo para computadores, tablets e celulares.

## Tecnologias

- **HTML5:** estrutura semântica, formulários, diálogos, áudio e acessibilidade.
- **CSS3:** identidade visual, Media Queries, animações, temas e responsividade.
- **JavaScript:** manipulação do DOM, eventos, cálculos, persistência local, áudio, canvas, microfone e geração do jornal.
- **Canvas API:** composição e exportação da capa do Jornal do Futuro.
- **Web Audio/Media APIs:** leitura de intensidade do microfone e reprodução de mídias.
- **LocalStorage:** armazenamento local de preferências, conquistas e compromissos.

## Estrutura

```text
.
|-- index.html       # Conteúdo e estrutura semântica
|-- style.css        # Identidade visual, animações e responsividade
|-- script.js        # Interações, cálculos e manipulação do DOM
|-- img/             # Imagens e identidade visual
|-- musica/          # Narrações, músicas e sons ambientais
`-- README.md        # Documentação, fontes e créditos
```

## Acessibilidade e usabilidade

- Link para pular diretamente ao conteúdo principal.
- Elementos interativos com nomes acessíveis e estados ARIA.
- Operação por teclado e fechamento de janelas com `Esc`.
- Textos alternativos nas imagens informativas.
- Modo leitura com redução de cores e contraste visual controlado.
- Ajuste do tamanho da fonte.
- Respeito à preferência `prefers-reduced-motion`.
- Alternativas para experiências que dependem de microfone.
- Feedback textual para ações, erros e mudanças de estado.

## Fontes de pesquisa

- [Conab - Safra brasileira de grãos](https://www.gov.br/conab/pt-br/assuntos/noticias/safra-de-graos-2024-205-e-estimada-pela-conab-em-350-2-milhoes-de-toneladas-e-atinge-novo-recorde-historico)
- [FAO - Perdas e desperdício de alimentos](https://www.fao.org/platform-food-loss-waste/flw-events/international-day-food-loss-and-waste/en)
- [FAO/UNEP - Políticas sobre desperdício](https://www.fao.org/policy-support/policy-themes/food-loss-and-food-waste/)
- [Governo do Paraná - Safra estadual](https://www.parana.pr.gov.br/aen/Noticia/Com-468-milhoes-de-toneladas-Parana-teve-maior-safra-de-graos-de-sua-historia-em-2425)
- [Embrapa - Rotação de culturas](https://www.embrapa.br/agencia-de-informacao-tecnologica/cultivos/milho/producao/rotacao-de-culturas)
- [MAPA - Plano ABC+](https://www.gov.br/agricultura/pt-br/assuntos/sustentabilidade/planoabc-abcmais/acoes-do-plano)

## Autoria e créditos

- Concepção, direção do projeto, seleção do conteúdo, testes e personalização: **Eduardo Valentin Carneiro**.
- Narrações `parte 1 de 8.m4a` até `parte 8 de 8.m4a` e `ler resumo pronto.m4a`: gravações fornecidas pelo estudante.
- Paisagens, personagens, ícones, animações e ilustrações construídos em HTML e CSS: desenvolvidos especificamente para o Raiz Up com direção do estudante e apoio de IA.
- Código e textos foram revisados e adaptados para o tema e para as decisões de experiência definidas pelo estudante.


## Registro do apoio por IA

Foi utilizado o **Chat GPT, da OpenAI**, como ferramenta de apoio para programação, revisão, acessibilidade, testes e criação de elementos visuais feitos em código. O estudante definiu a ideia, orientou as alterações, forneceu os áudios, avaliou os resultados e personalizou o projeto durante todo o desenvolvimento.

Prompts e solicitações que orientaram o apoio:

```text
Criar um site para o Agrinho 2026 com o tema "Agro forte, futuro sustentável: equilíbrio entre produção e meio ambiente", identidade visual própria, seções educativas, interações acessíveis e uso de HTML, CSS e JavaScript.

Adicionar uma apresentação automática com um personagem do site, transição de folhas e rolagem para as áreas explicadas, usando as oito gravações fornecidas pelo estudante.

Criar a Semente Viva, que cresce quando o visitante usa o simulador, consulta os dados, conclui o quiz, planta sementes e registra um compromisso.

Criar uma comparação de dois futuros que reaja às decisões do simulador, modificando árvores, peixes, rios, energia e colheita.

Criar um Jornal do Futuro de 2040 com manchetes e paisagens baseadas nas escolhas, permitindo baixar a capa como imagem.

Melhorar acessibilidade, modo leitura, responsividade, controles de áudio, navegação por teclado e feedback das interações.

Revisar o projeto conforme o regulamento do Concurso Agrinho Programação 2026 e remover riscos de desclassificação.
```

### Recursos sonoros e músicas

* As músicas e sons ambientais utilizados no projeto foram obtidos na plataforma **Pixabay**, que disponibiliza recursos de áudio para uso conforme seus termos de licença.

Fonte:
https://pixabay.com/pt/music/search/agricultura/

* Os arquivos de áudio foram selecionados, organizados e integrados ao projeto pelo estudante, com o objetivo de proporcionar uma experiência mais imersiva e educativa relacionada ao ambiente agrícola e à sustentabilidade.


## Contato

Eduardo Valentin Carneiro  
Colégio Estadual Marechal Costa e Silva - EFM  
Cidade Gaúcha, Paraná, Brasil  
[eduardo.valentin.carneiro@escola.pr.gov.br](mailto:eduardo.valentin.carneiro@escola.pr.gov.br)
