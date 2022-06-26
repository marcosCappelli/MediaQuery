# MediaQuery
- Com ele podemos deixar nossas páginas responsivas, e até interagir com os elementos do #html
através das regras de CSS.
- Como aplicar o mobile first em meus projetos, trabalhar com orintation, ou seja, adicionar 
em landscape, e até a outros modos, com alterar CSS para impressão e leitores de tela.

# Passos para configuração:
1 - Configurar media query na página #HTML
2 - Sintaxe 
 @media screen and (max-width: 500px) { }
  /* max-width = telas menores que alguma resolução */
3 - Outras sintaxes
  (screen, print, speech, all) 
4 - Para todos os modos all.
5 - Mobile first
  @media (min-width: 200px) { }
  min-width > max-width
6 - AND na media query
  @media (min-width: 300px) and (max-width): 600px) { }
7 - orientation
  @media (orienation: landascape) { }
8 - OR
  @media (min-width: 200px), (orientation: landascape) { }
9 - As medias query são as últimas
10 - breakpoints
  Usa-se para definir os tamanhos de resolução especificos ( tablet, laptop, desktop, telas mnaiores e tvs ) 
   
            
