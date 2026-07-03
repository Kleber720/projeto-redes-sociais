# projeto-redes-sociais
# Projeto Redes Sociais

Este é um projeto simples desenvolvido como parte de um estudo em HTML5 e CSS3. O objetivo é criar uma página web que simula a tela de um celular, exibindo links para diferentes perfis de redes sociais.

## Descrição

A página principal apresenta a imagem de um celular. Ao clicar nos ícones de redes sociais dispostos ao lado, o conteúdo correspondente àquela rede social é carregado dentro da tela do celular (utilizando um iframe).

Cada página de rede social contém uma imagem de fundo e um link "ACESSE" que redireciona o usuário para o perfil real em uma nova aba.

## Tecnologias Utilizadas

- HTML5
- CSS3

## Estrutura de Arquivos

O projeto está organizado da seguinte forma:

- **index.html**: O arquivo principal que contém a estrutura da página, incluindo o celular e os botões de navegação para as redes sociais.
- **/pages**: Este diretório armazena as páginas HTML individuais que são carregadas no iframe.
  - `home.html`: A tela inicial padrão exibida no celular.
  - `facebook.html`, `github.html`, `instagram.html`, `x.html`, `youtube.html`: Páginas específicas para cada rede social.
- **/estilos**: Contém as folhas de estilo CSS.
  - `style.css` (não fornecido no contexto): Estilos aplicados à página principal `index.html`.
  - `social.css`: Estilos compartilhados entre as páginas de redes sociais contidas no diretório `pages`.
- **/imagens**: Armazena todas as imagens utilizadas no projeto, como as telas de fundo e os ícones.

## Como Executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em seu navegador de preferência.
3. Navegue clicando nos ícones das redes sociais.

## Nota sobre o Desenvolvimento

Para este projeto, que teve um propósito puramente de estudo, todo o desenvolvimento foi realizado diretamente na branch `main`. No entanto, em projetos colaborativos ou mais complexos, a prática recomendada é a criação de branches separadas (como `develop`, `feature/*`, etc.) para gerenciar o fluxo de trabalho de forma mais organizada e segura.
