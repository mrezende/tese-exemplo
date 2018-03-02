# Tese exemplo do IPT

Exemplo de tese/dissertação utilizado no IPT. Ao invés de usar o pdflatex, estou utilizando xelatex.

Este modelo é somente uma referência, caso tenha alguma sugestão ou encontre algo que não esteja de acordo com o guia de referência do IPT, basta solicitar Pull Request.


Diretório *docs*:

 - **Guia_IPT_reformado_final_2013_6.pdf** - versão disponibilizada na disciplina de Metodologia da Pesquisa no 1 quadrimestre de 2018

  - **tese-exemplo.pdf** - exemplo de pdf gerado a partir dos arquivos latex do diretório **src**.

------

Diretório *src*:
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
  
----


Compilação do documento:
  - make pdf : usando xelatex
  - make ps  : usando latex
  Ex:
      $ make pdf
  Obs: Para a compilação do documento que referencia figuras em formato 'ps' ou
       'eps' deve-se usar: 'make ps'


