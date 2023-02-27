
  OOCSS

  Criadora: Nicole Sullivan

  O que seria um objeto no css?
  Qualquer padrão visual que se repete e que pode 
  ser transformado em um snippet independente.

  O que é estrutura no css?
  Tudo que é "invisível", width, height, margin, padding,
  overflow, etc...
  Estrutura trabalha em como as "coisas" são dispostas

  O que é visual no css? 
  Tudo o que é visível, cores, fontes, sombras, degradês, etc...

  OBS: Estrutura não é apenas containers, todo componente tem estrutura e visual, um botão por exemplo tem propriedades invisíveis(estrutura) e propriedades visíveis(visual).

  Princípios do OOCSS:

    1º Separar estrura do visual

    2º Independência entre Contêiner e Conteúdo:
      - Evitar o uso de estilos que dependam de localização.
      - Um objeto deve manter suas características, não importando onde esteja.

  Melhores práticas:

    1 - Criar uma biblioteca de componentes
      - Design system

    2 - Usar estilos semânticos consistentes

    3 - Fazer módulos que sejam transparentes
      - "background-color: transparent"

    4 - Ser flexível
      - Responsividade

    5 - Aprender a trabalhar com Grids
      - Css Grids

    6 - Minimizar seletores
      - Baixa especificidade Css

    7 - Separar estrutura e visual

    8 - Separar container e conteúdo

    9 - Criar objetos extensíveis através de classes

    10 - Usar reset e fontes da YUI
      - Normalize css
      - Google Fonts

  Armadilhas a Evitar:

    1 - Criar estilos dependentes de localização

    2 - Especificar a qual Tag Html uma classe se aplica

    3 - Usar IDs

    4 - Usar sombras e bordas arredondadas em backgrounds irregulares

    5 - Não criar sprite para todas as imagens

    6 - Definir a altura de objetos/componentes

    7 - Usar imagem como texto

    8 - Ser redundante
      - Repetição de código

    9 - Fazer otimização prematura