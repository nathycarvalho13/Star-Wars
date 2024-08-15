# Star-Wars
 Site sobre os personagens do filme Star Wars
Este projeto é um site que exibe informações sobre personagens da franquia Star Wars. Ele utiliza a API SWAPI (Star Wars API) para obter dados sobre os personagens e apresenta essas informações em um layout visualmente atraente. O site permite a navegação entre páginas de resultados e exibe detalhes dos personagens em um modal.

Tecnologias Utilizadas

HTML5

CSS3

JavaScript

API SWAPI (https://swapi.dev)

Font Awesome (https://fontawesome.com)

Funcionalidades

Exibição de cards com personagens de Star Wars.
Navegação entre páginas de resultados com botões "Anterior" e "Próxima".
Exibição de detalhes dos personagens em um modal ao clicar em um card.


Estrutura do Projeto

index.html: Página principal que carrega e exibe os personagens.
style.css: Estilos para a página e componentes.
script.js: Lógica para carregar personagens, navegar entre páginas e exibir modais.
assets/: Pasta contendo imagens e ícones utilizados no projeto.

Como Usar
Acesse: https://star-wars-personagens.vercel.app/

Estrutura do Código

HTML
Contém a estrutura básica da página, incluindo o cabeçalho com o logotipo e links para redes sociais, o corpo principal que exibe os personagens, e o rodapé.

CSS
Estilos personalizados para diferentes componentes, como o cabeçalho, cards de personagens, modal e botões de navegação.

JavaScript
window.onload: Carrega os personagens da primeira página ao iniciar.
loadCharacters(url): Função assíncrona que faz uma requisição à API SWAPI e exibe os personagens.
loadNextPage() e loadPreviousPage(): Funções para carregar a próxima e a anterior página de resultados.
hideModal(): Esconde o modal de detalhes do personagem.
Funções auxiliares para converter dados da API para um formato mais legível.

Autor
Desenvolvido por Nathália Carvalho.
