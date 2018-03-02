# Tese exemplo do IPT

Exemplo de tese/dissertação utilizado no IPT. Ao invés de usar o pdflatex, estou utilizando xelatex.

Este modelo é somente uma referência, caso tenha alguma sugestão ou encontre algo que não esteja de acordo com o guia de referência do IPT, basta solicitar Pull Request.



Arquivo principal: 
  -'tese-exemplo.tex'

Arquivos dos capítulos e apêndice:
  - 'cap-introducao.tex'
  - 'cap-conceitos.tex'
  - 'cap-conclusoes.tex'
  - 'ape-conjuntos.tex'

Arquivo de bibliografia: 
  -'bibliografia.bib'

Diretório de figuras: 
  - './figuras/'
  
Compilação do documento:
  - make pdf : usando xelatex
  - make ps  : usando latex
  Ex:
      $ make pdf
  Obs: Para a compilação do documento que referencia figuras em formato 'ps' ou
       'eps' deve-se usar: 'make ps'

      
