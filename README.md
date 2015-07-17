# abntex2unb

Este é um projeto com customizações do [abnTeX2](http://abnTeX2.googlecode.com) para trabalhos acadêmicos da Universidade de Brasília.

A biblioteca [abnTeX2](http://abnTeX2.googlecode.com) já atende os padrões exigidos pela UnB! Esta biblioteca adiciona informações opcionais ao documento.

<sub>Atenção! Este não é um projeto oficial da Universidade de Brasília - UnB. O nome dessa instituição é utilizado apenas para indicar que o padrão dos arquivos gerados com a biblioteca abnTeX2 em conjunto com essa customização estarão de acordo com as suas normas.</sub>

## Como usar

1. Copie os arquivos [`abntex2unb.sty`](abntex2unb.sty) e
[`marca_unb.jpg`](marca_unb.jpg) para o seu projeto;
2. Adicione o pacote `\usepackage{abntex2unb}` ao seu projeto.

### Exemplo

O arquivo `document.tex`
```latex
% ...

\usepackage{./abntex2unb}

% ...

\titulo{Título do Trabalho Acadêmico}
\autor{Fulano de Tal}
\data{2015, julho}
\orientador{Prof. Dr. Beltrano da Silva}
\coorientador{Prof. Dr. Ciclano Bragança}
\instituicao{%
  Universidade de Brasília -- UnB
  \par
  Faculdade de Educação
  \par
  Programa de Pós-Graduação em Educação}
\tipotrabalho{Tese (Doutorado)}
\preambulo{Modelo canônico de trabalho monográfico acadêmico em conformidade com
as normas ABNT apresentado à comunidade de usuários \LaTeX.}

% ...
```

Capa                      | Folha de Rosto
:------------------------:|:----------------------------------------------:
![Capa](/sample/capa.png) | ![Folha de Rosto](/sample/folha_de_rosto.png)

## Referências

- http://www.bce.unb.br/normas-bibliograficas/
- http://www.marca.unb.br
