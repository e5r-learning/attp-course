Treinamento Avançado para Programadores Profissionais
=====================================================

ATPP vem de (A)dvanced (T)raining for (P)rofessional (P)rogrammers.

ou, TAPP de (T)reinamento (A)vançado para (P)rogramadores (P)rofissionais.

A idéia é criar um treinamento intensivo para programadores que desejam dominar (ou pelo menos conhecer)
assuntos avançados de programação que são utilizados em projetos que utilizamos no nosso dia a dia
profissional, e que quase nunca temos a oportunidade de trabalhar nesses assuntos em projetos
do cotidiano "profissional" regular.

## Porque Open Source deve ser considerado

A idéia neste tópico é deixar claro que não se trata simplesmente de uma opinião pessoal por utilizar
ferramentas open source, ou do fato de utilizar ferramentas "não caras".
Mas sim, relatar como programadores profissionais de grandes empresas e instituições que criaram e criam
os grandes softwares conhecidos no mercado, aplicaram seus esforços profissionais para criar ferramentas
que posteriormente foram disponibilizadas de forma gratuita.

Ter o código fonte aberto nos possibilitou conhecer como os grandes programadores profissionais resolviam
seus problemas no dia a dia.

Por isso, considerar os projetos open source é também considerar estudar o código e técnicas dos
grandes programadores.

## Rascunho

Imagine um treinamento avançado de 2 dias (um sábado e domingo) de total imersão, como se fosse um 
Hackathon, com palestras e mão na massa falando de assuntos que não se vê no dia a dia em tutoriais
pela Internet.

As atividades seriam algo como:

1. Uma palestra introdutória de um assunto avançado qualquer
   * Aqui é levantada a experiência dos participantes em projetos que tratam do assunto
   * É bom antes saber se e como alguém já resolveu o assunto
2. Um projeto de exemplo é apresentado para que os participantes possam implementá-lo
   * Um projeto já especificado é entregue o mais completo porém simples possível
3. Após a apresentação das soluções, temos uma palestra de conclusão do assunto
   * A idéia principal é não tratar como resolver as coisas com Frameworks
   * A idéia principal é de como resolveriamos o problema se não tivessemos algo já pronto
   * O que só podemos aprender com projetos assim?
     - Listar alguns assuntos importantes que podem ser usado em outros lugares
     - Por que seria difícil aprender isso com outros projetos?
   
### Exemplo

1. Palestra: Teste de Unidade
   - Porque testar?
   - Diferença entre Testes de Unidade, Teste Fim a Fim, Teste de Integração, etc.
   - Testes de Unidade em várias Linguagens
   - Frameworks de Testes de Unidade conhecidos
   - Linguagem Formal de Especificação
   - TDD
2. Projeto: Implementar um Framework de Teste de Unidade em Linguagem Formal
   - https://github.com/erlimar/kino
   - https://github.com/erlimar/TDD-with-TDD
3. Palestra de conclusão: O que aprendemos
   - Programação fluente
   - Criar ferramentas de linha de comando
   - Pra que serve o "return" em uma função "Main()"
   - Descoberta de metadados em .NET Assembles
   - Ferramentas de linha de comando primeiro podem virar GUI, mas o inverso não é fácil/possível
   
## Outro exemplo: Como funcionam os SCM?

Como outro exemplo podemos exercitar como projeto desenvolver um software em equipe distribuída
controlando a versão por `diff`, `patch` e `tarball` (https://www.youtube.com/watch?v=6Czd1Yetaac).

Essa palestra pode ter continuação para implementar nosso próprio SCM (https://github.com/erlimar/learn-scm).

## Outros exemplos

* https://github.com/erlimar/lexsyntax
 - https://github.com/erlimar/my-parser
* https://github.com/erlimar/nde
  - https://github.com/e5r/bit
* https://github.com/erlimar/CommandLinePatterns
* https://github.com/erlimar/CryptoTest
* https://github.com/erlimar/LocalizationJS
* https://github.com/erlimar/printzip
* https://github.com/erlimar/shadowdom
  - https://github.com/e5r/jquery-toad
* https://github.com/erlimar/flow
