# Criando uma Página Web Simples - Exercício 03 (Módulo III)

Este projeto faz parte do **exercício 3** do curso Desenvolvedor Fullstack Java Júnior, do programa +PraTi. O objetivo deste exercício é criar uma página web 
simples utilizando **HTML** e **CSS**, com uma estrutura básica de um site. A página inclui elementos como **header**, **menu de navegação**, **conteúdo principal**, 
**links externos** e **footer**.

## Objetivo do Projeto

- Desenvolver uma página web com **HTML** e **CSS** contendo os principais elementos de um site simples.
- Aplicar estilização **CSS** para layout e efeitos visuais.
- Praticar a criação de um layout de duas colunas (**section** e **aside**), além de aplicar boas práticas no desenvolvimento web.

## Estrutura da Página

A página web foi estruturada da seguinte maneira:

- **Header**: Contém o título do site "Climate and Weather" e um menu de navegação com três links fictícios: **Home**, **About**, **Contact**.
- **Section**: Área principal do conteúdo, com uma breve introdução sobre o site e uma lista de notícias relacionadas ao clima.
- **Aside**: Uma lista de links externos úteis, relacionados ao clima e meteorologia.
- **Footer**: Inclui os direitos autorais da página.

![Captura de tela 2024-10-06 230543](https://github.com/user-attachments/assets/a71615ce-0c1c-4d25-a9a1-cefaeffb3db2)

## Funcionalidades

- **Menu de Navegação**: Contém links para as seções **Home**, **About** e **Contact**, além de um botão de **Login**.
- **Banner de Imagens**: Apresenta uma série de imagens meteorológicas, incluindo imagens de satélite e fenômenos climáticos.
- **Introdução**: Texto explicativo sobre a proposta do site, com foco em previsões do tempo e informações meteorológicas.
- **Seção de Notícias**: Apresenta links para notícias recentes relacionadas ao clima e previsões sazonais.
- **Links Relacionados**: O **aside** contém links externos para imagens de satélite, radar e previsões climáticas de modelos meteorológicos.
- **Rodapé**: Exibe os direitos autorais do site.

## Estilização com CSS

A estilização da página foi feita utilizando **CSS** para melhorar a experiência do usuário e a apresentação visual:

- **Cores**: O header, footer e o menu de navegação possuem cores de fundo diferenciadas para destacar cada seção.
- **Layout Flexbox**: Utilizado para criar um layout de duas colunas, onde o **section** ocupa 70% da largura da tela e o **aside** 30%.
- **Imagens no Banner**: As imagens são exibidas em um layout horizontal, ajustando-se automaticamente à largura da página.
- **Efeito Hover**: Adicionado aos links no menu de navegação e no **aside**, para mudar a cor ao passar o mouse.

## Estrutura de Arquivos

```bash
├── index.html         # Estrutura HTML da página
├── style.css          # Arquivo CSS para a estilização
└── assets/
    └── img/
        ├── imagem_satelite.png
        ├── Autocumulus.jpg
        ├── Tempestade_Campeche.jpg
        └── Água_na_Janela.JPG
```
##Instruções de Uso
Clone o repositório:

```bash
git@github.com:williammmoura/Lista_03_Pagina_Web_Simples_Dev_Fullstack_JAVA_jr_maisPraTi.git
```
Abra o arquivo index.html em um navegador de sua preferência.


##Tecnologias Utilizadas
- **HTML5**: Estrutura da página web.
- **CSS3**: Estilização da página, layout flexbox e efeitos visuais.
- **Imagens**: Arquivos de imagem relacionados ao clima para compor o banner.
