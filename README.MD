# Código fonte do Website do grupo obseRVe

Estas são informações gerais sobre a estrutura e organização do website.
O website renderizado encontra-se em (https://observe.ufscar.br/)

## Barra de navegação

Todos os itens da página inicial acessíveis na barra de navegação.

A barra de navegação também contém ícones para o Instagram e futuramente para o Youtube.

## Página principal

### Atividades

Esta página reúne todas as atividades que envolvem a participação do público interessado. Portanto, deve conter informações precisas e diretas do que se trata a atividade, de como participar, se inscrever, como chegar, etc.

Por enquanto, publicamos as seguintes atividades:

- Jornada das Estrelas
- Jornada do Sol
- Observatório a Olho Nu
- Construção de Planisfério
- Observação do céu
- Passeio dos Planetas
- Pêndulo de Foucault
- Desafios online usando H5P

### Projetos

No momento esta página está em construção. Ela é dedicada ao compartilhamento do detalhamento dos projetos e equipamentos desenvolvidos. Cada item adicionado, pode ter diferentes níveis de detalhamento para diferentes faixas etárias e diferentes públicos. 

Por exemplo, o pêndulo de Foucault pode ser incluído como um projeto nesta página, a qual pode conter sub páginas. Em uma delas mostra-se explicações simples, simulações e filmagens, por exemplo. Em outra mostra-se dados técnicos da eletrônica, da mecânica do suporte, das medidas de precessão, etc.

### Calendário de eventos

Divido nas abas de eventos agendados e eventos encerrados. Será na forma de um *quarto.org listing*, cada evento conterá a data, a forma específica de participação -- quando diferente do descrito na página de Atividades, senão será dado o link para a respectiva atividade -- formulário de inscrição, quando for o caso.

### Blog

Postagens dos eventos e visitações realizadas, com descrição da faixa etária do público e quantidade de pessoas, nome das escolas que visitaram quando for o caso, quais atividades foram realizadas no evento, etc. O texto tem que ser o mais detalhado possível.

Importante usar um mesmo padrão. A primeira postagem inserida foi a visita da escola Maria Rosa em novembro/2023. É importante usar o mesmo padrão dessa postagem para as postagens futuras.

### Equipe

Equipe do grupo Observe separada em professores, técnicos e estudantes.

### Acervo

Materiais do projeto. Cada item é separado em abas contendo descrição, especificações e formas de uso.

### Sobre o obseRVe

Explicação sobre o histórico das ações de astronomia que levaram a criação do obseRVe e a explicação da escolha do logotipo.

### Como chegar

Explicação de como acessar o Observatório a Olho Nu através de mapa gerado pela biblioteca em Python contendo explicações sobre as duas entradas do CCA-UFSCar.

### Links

Ainda não foi implementado. Mas abaixo, temos alguns exemplos.

    >- [ExpLORa](https://wordpress.ft.unicamp.br/explora/)
    >- [Observatório Astronômico da UFSCar](http://www.observatorio.ufscar.br/)
    >- [Observatório Unesp - Bauru](https://www.fc.unesp.br/#!/observatorio)
    >- [Planeta Rio](https://planeta.rio/)
    >- [Observatório Astronômico da UFSC](https://observatorio.ufsc.br/)


# Como contribuir com o desenvolvimento e atualização do website do obseRVe

Para contribuir com o projeto, você precisará usar o **Quarto** e, se possível, o GitHub.

## 1. Quarto

O website do obseRVe é desenvolvido com a ferramenta **Quarto**. Ela possui uma [documentação](https://quarto.org/) bastante amigável. Neste projeto, focamos mais em [Website](https://quarto.org/docs/websites/), mas outros recursos também serão utilizados, como inclusão de códigos python, por exemplo.

A ideia do **Quarto** é você editar todos os arquivos direto em txt usando a IDE da sua preferência. Sugerimos o [VS Code](https://code.visualstudio.com/) junto com a extensão do Quarto para VS Code.

## 2. GitHub

Se você não conhece o sistema de controle de versão **Git** ou o repositório **GitHub** e sua forma de uso, é recomendável o seu estudo na página:

[Sobre o GitHub e o Git.](https://docs.github.com/pt/get-started/start-your-journey/about-github-and-git)

A qual é subdividida em:

- Criar uma conta
- Olá, Mundo
- Configure o seu perfil
- Encontre inspiração
- Baixar arquivos
- Carregar um projeto
- Recursos de aprendizagem

Para uma documentação específica do Git, incluindo vídeos tutoriais, acesse [Git documentation](https://git-scm.com/doc).

Se você for usar o [VS Code](https://code.visualstudio.com/) para editar o website, também é recomendável o estudo do material abaixo para ter uma boa integração do VS Code com o Git e o GitHub:

- [Introduction to Git in VS Code](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git)
- [Working with GitHub in VS Code](https://code.visualstudio.com/docs/sourcecontrol/github)


### Guia direto para a linha de comando

Este é um guia direto usando a linha de comando do seu sistema operacional e, por isso, é independente do editor de texto ou da IDE usada para editar o website.

#### Primeira vez no Git

[Instale o Git no seu computador](https://git-scm.com/downloads).

#### Primeira vez no GitHub

[Crie uma conta no GitHub](https://docs.github.com/pt/get-started/start-your-journey/creating-an-account-on-github)

#### Primeira vez no repositório do obseRVe

Faça o clone do repositório.
