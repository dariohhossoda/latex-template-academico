# Template LaTeX para produção acadêmica

Este repositório contém um template LaTeX para produção acadêmica, focado na escrita em formato de dissertação/tese/monografia. O template é projetado para ser flexível e adaptável a diferentes estilos e requisitos acadêmicos, facilitando a organização e formatação de documentos acadêmicos.

## Estrutura do Template
O arquivo principal é `main.tex`, que inclui os capítulos e seções do documento, assim como as seções estão divididas, a main orquestra a organização do documento, sendo que os pacotes e configurações gerais estão definidos no arquivo `preamble.tex`. O template também inclui um arquivo de referências `refs.bib` para gerenciamento de citações bibliográficas.

```
main.tex
preamble.tex
config.tex
refs.bib
sections/
    cover.tex
    acknowledgments.tex
    abstract.tex
    introduction.tex
    objectives.tex
    literature_review.tex
    methodology.tex
    results.tex
    conclusions.tex
```

No arquivo main é possível alterar a estrutura do documento, incluindo ou removendo capítulos e seções conforme necessário. O template é projetado para ser facilmente personalizável, permitindo que os usuários adaptem o formato às suas necessidades específicas.

## O que é LaTeX?
LaTeX é um sistema de preparação de documentos de alta qualidade, amplamente utilizado para a produção de documentos acadêmicos, científicos e técnicos. Ele é especialmente útil para lidar com fórmulas matemáticas complexas, referências cruzadas e formatação consistente. Diferentemente de processadores de texto tradicionais, o LaTeX é baseado em um sistema de marcação, onde o autor escreve o conteúdo e a formatação é gerenciada pelo sistema.

### Como utilizar este template?
1. Clone este repositório para o seu ambiente local.
2. Abra o arquivo `main.tex` em um editor de LaTeX de sua escolha (como Overleaf, TeXstudio, etc.).
3. Edite o conteúdo dos capítulos e seções conforme necessário, seguindo a estrutura do template.
4. Edite o arquivo `config.tex` para personalizar as configurações do documento, como nomes, títulos, etc.
5. Adicione suas referências bibliográficas no arquivo `refs.bib` utilizando o formato BibTeX.
6. Compile o documento `main.tex` para gerar o PDF final.


### Ambientes de escrita LaTeX
A seguir estão listadas alguns ambientes recomendados para utilização do LaTeX:
- **[Overleaf](https://www.overleaf.com/)**: Uma plataforma online que permite escrever, compilar e colaborar em documentos LaTeX diretamente no navegador.
- **[TeXstudio](https://www.texstudio.org/)**: Um editor de LaTeX de código aberto para desktop, com recursos avançados de edição e compilação.

Observação: Para utilizar o template localmente (todos exceto o Overleaf), é necessário ter uma distribuição LaTeX instalada, como o [MiKTeX](https://miktex.org/download).