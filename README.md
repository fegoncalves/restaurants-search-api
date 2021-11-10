# **_Criando um site para encontrar restaurantes usando Google Maps que consulta API do Google_**

Este projeto foi desenvolvido durante o Bootcamp Impulso React Web Developer da [Digital Innovation One](https://digitalinnovation.one/).

Foi criado um sistema web para buscar restaurantes - parecido com o serviço que o Google oferece - onde os resultados das pesquisas que o usuário fizer serão exibidos dinamicamente próximo a sua localidade.



&nbsp;
## **_Algumas funcionalidades da aplicação:_**
* Carrossel de fotos exibindo os restaurantes da área;
* Listagem vertical dos restaurantes;
* Ao selecionar uma empresa dessa listagem, será exibido as informações da mesma (inclusive se estaria aberta ou fechada);
* No mapa há marcadores indicando os estabelecimentos da região;
* Campo de pesquisa.
> Quando o projeto é iniciado e até o resultado de uma pesquisa ser exibido na listagem, o sistema mostra uma animação - um motoboy na moto fazendo entregas - durante os poucos segundos em que a página é recarregada.



&nbsp;
## **_Tecnologias utilizadas:_**
* JavaScript
* React.JS
* API do Google (Maps JavaScript API e Places API)



&nbsp;
## **_Algumas ferramentas, bibliotecas, dependências e animações utilizadas:_**
* Styled Components;
* Styled Reset;
* React Text Field;
* React Material Icon;
* React Slick;
* Slick Carousel;
* React Rating Stars Component;
* React Portals;
* Google Maps React;
* Google Place Libary;
* Redux;
* React Lottie


&nbsp;
## **_Prévia da aplicação:_**
![prévia do projeto](https://fernandagoncalves.com.br/github/restaurants.gif)



&nbsp;
## **_Como executar o projeto:_**
### _Clone o repositório:_
`git clone https://github.com/fegoncalves/restaurants-search-api.git`

### _Acesse a pasta da aplicação_
`cd restaurants-search-api`

### _Instale as dependências_
`npm install`

### _Inicie a aplicação_
`npm start` ou `yarn start`
> A aplicação será exibida no seu localhost através do endereço http://localhost:3000 



&nbsp;
### **_Para o uso da API_**
Para que a aplicação funcione normalmente em seu dispositivo, será necessário usar ou criar um projeto no [Google Cloud Platfrom](https://cloud.google.com/). 

Uma vez criado você deverá:
1. Selecionar e ativar as bibliotecas Maps JavaScript API e Places API;
2. Criar uma credencial para obter a chave API;
3. No diretório raíz da sua aplicação, crie um arquivo chamado `.env` e cole dentro deste a linha a seguir juntamente com a chave API criada.
`REACT_APP_GOOGLE_API_KEY=SuaChaveAqui`

