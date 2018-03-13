![Logo](abntex2unifei_logo.png)

abntex2unifei - v0.2
=============

Extensão da classe abntex2, segundo as normas convencionais da Universidade
Federal de Itajubá - Campus Itabira.


Criador e Mantenedor: Lucas Vieira <lucasvieira@protonmail.com>


> ATENÇÃO! Este projeto já não está sendo mantido mais por mim.
> Fique à vontade para utilizá-lo, mas lembre-se de que alterações futuras requerem um fork.


O que é
-------
Como a descrição sugere, trata-se de um arquivo que modifica certas definições
da classe abntex2 para LaTeX, sem causar alterações diretas à mesma. Ou seja,
trata-se de uma extensão da classe abntex2.

Este formato segue o padrão de contribuição ao abntex2.


Como usar
---------
Dado que você esteja trabalhando em um projeto LaTeX, e tenha instalado a classe
abntex2, basta copiar o arquivo abntex2unifei.sty para o diretório do seu
trabalho, e incluí-lo como se inclui um pacote (através do comando usepackage).

Incluir o abntex2unifei também exige que você já tenha definido sua documentclass
como abntex2, a rigor.


Como usar, parte 2: Noob Edition
--------------------------------
Caso você possua pouco conhecimento de LaTeX, está incluido também, neste
repositório, uma pasta com um template de projeto de Trabalho de Conclusão de
Curso, preenchido com exemplos de inserção de tabelas, figuras e outros
elementos relevantes. O projeto está dividido em diversos arquivos relevantes,
como citado a seguir, e elementos desnecessários podem ser comentados ou
removidos do projeto:

- main.tex

	O arquivo principal, de onde o projeto será compilado.

- config.tex

	Arquivo com configurações de preâmbulo - definições de documento e inclusão
	de bibliotecas necessárias. Também inclui configurações gerais do projeto
    (título, autor(es), etc.

- pretextual.tex

	Arquivo com elementos de pré-texto, como agradecimentos, dedicatórias, resumo
	e folha de aprovação (esta última exclusiva do abntex2unifei).

- introducao.tex

	Exemplo de introdução do trabalho.

- referencialteorico.tex

	Exemplo de referencial teórico do trabalho.

- metodologia.tex

	Exemplo de metodologia do trabalho.

- consideracoesfinais.tex

	Exemplo de considerações finais do trabalho.

- postextual.tex

	Arquivo com elementos de pós-texto, como inclusão do arquivo de referências
	bibliográficas, apêndices e anexos.

- refs.bib

	Exemplo de arquivo de bibliografia. Inclui exemplo de bibliografia via
	website para trabalhos e referências futuras.

- main.pdf

	Exemplo de PDF gerado pelo LaTeX, quando aplicado o template.

Recomenda-se o uso da IDE Texmaker para uma melhor integração com o LaTeX, ou
sites como ShareLatex para uma edição online e compartilhada.

Você pode, também, realizar o download das bibliotecas principais do LaTeX usando
os instaladores do TeXLIVE (Windows, Linux, OSX - recomendado), ou MikTeX (Windows).
Lembre-se de que a instalação destes componentes pode ser um download grande
(em torno de 11GB).

Se você estiver usando Linux, pessoalmente recomendo o uso de um wrapper para
os compiladores TeX (LaTeX, XeTeX, BibTeX) chamado rubber. Você vai encontrá-lo
facilmente nos repositórios oficiais do Ubuntu ou no repositório Community
do Arch Linux.

Contribuindo
------------
Você pode contribuir para este projeto ou solicitar mudanças, caso veja alguma
inconsistência, enviando-me um email (meus contatos estão acima) ou utilizando,
preferencialmente, a página de Issues do GitHub para o repositório desta
extensão (https://github.com/luksamuk/abntex2unifei/issues).

Você também pode realizar um fork deste repositório e fazer as suas próprias
modificações, e então enviá-las através de um pull request. Neste caso, você
será também apontado como colaborador deste projeto.


Licenciamento
-------------
abntex2unifei é distribuida sob a licença MIT, o que significa, efetivamente,
que você:

- Pode usá-la comercialmente;
- Pode distribuí-la;
- Pode modificá-la;
- Pode usá-la em um projeto privado, sem redistribuí-la.


Da mesma forma, você:

- NÃO pode responsabilizar criadores, mantenedores ou contribuidores por
quaisquer danos causados por esta extensão, uma vez que este software é
redistribuido sem garantia.


E tudo isso, desde que você:

- Inclua uma cópia da licença referida em seu uso desta extensão, ao
redistribui-la.


Para mais informações, consulte o site http://choosealicense.com/.
