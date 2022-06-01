//Descrição sobre a criação de páginas com tradução automatica sem o uso de plugins usando o CMS WordPress

//Primeiro passo seria solicitar ao gestor do projeto se existe alguma tradução oficial do projeto uma vez que diversas <br>
//traduções de apis não correspondem ao que um nativo identifica como correto.<br>


//Como primeiro obstaculo precisamos saber se o usuario está no Brasil ou no exterior, como determinado por localização e não por idioma, <br>
//Devemos pegar essa localização considerando que o usuario não utlize VPN pelo seu IP, pois outro metodo iria exigir consenção a sua localização no navegador

//identificar origem do usuario que acessa a pagina. 
// Para usuarios da faixa de IP 200.128.0.0 até 200.255.0.0. será exibida a versão oficial da página em português; 
// Para usuarios fora da faixa de IP 200.128.0.0 até 200.255.0.0. será ofertado a pagina em idioma escolhido. 

//Criar a condição atraves do ip2long para saber qual faixa se trata 

//Hipotese 01 - Sem tradução realizada por especialista
// Se o cliente tiver de acordo colocar a api de consulta do google translate V2 
// Criar diretorio /EN se em ingles com a copia da pagina e traduzida pela api 

//Hipotese 02 - Com a tradução realizada previamente, 
// Colocar ela no diretorio /EN e estabelecer a condição de exibição caso esteja na zona de ip fora do pais. 
