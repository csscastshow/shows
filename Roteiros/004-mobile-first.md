# Show #004 - Mobile First

## Intro
- Apresentação padrão
- intro

<hr>

## Conteúdo - Mobile first

### O que é?
- O que é mobile de verdade?
- Mobile First não é tela pequena first!
- Mobile First não é Mobile Only!

### O que é Mobile First para um Design
- Prioriza o conteúdo (é mais fácil aproveitar o maior tamanho para adicionar componentes, do que não saber o que retirar depois)
- Pensar Touch First
- Prioriza a experiência mobile (que tem menos recursos)EX: nao teclado, iluminacao, conexao, etc..

### O que é Mobile First para um Front-End
- Mobile first aplicado ao código
- Desktop First?
- Mobile First?
- Responsive first!
- Nao existe desculpa!
- Mesmo sem playout mobile, ele tem que ser mobile, logo não faz sentido!(uma vez que é Responsive first)
- Ultima opção: Desktop First > Refactor
- Hardware Ruim e Conexão Ruim

### O que realmente é mobile First para um Dev?
- Não depende de um layout mobile first para ser mobile first
- Use @media screen and (min-width) para deixar as media queries reescreverem o css em dispositivos maiores (com maior poder de processamento).
- Dicas para usar as propriedades default sempre que possível (não necessariamente apenas mobile first). Conheça bem seu css reset.
- Incremente o layout com conteúdo via ajax (nunca "apenas oculte a div")
- Se já carregou uma imagem "grande", não carregue outra ao dar resize.
- Progressive enhancement focado no hardware
- input types corretos
- Mobile First = Performance First

### Mobile First visto por um Back-End
- Falarei rapidinho sobre RESS
