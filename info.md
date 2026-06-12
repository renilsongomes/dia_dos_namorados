````css
/*quando esse layout foi pensado, não foi atoa, isso é basicamente o esqueleto do site do portal uol, então temos o cabeçalho, o logo  e uma barra de busca na direita, com meu e submenu e até mesmo aquele efeito na borda, e depois uma noticia em destaque e n seção destaque ainda tem alguns estagios de linhas, poderiamos fazer o mesmo com a tag <a> é só colocar o link, temos também a barra lateral que no nosso seria as novidades e temos também as listagens das noticias, pois esse layout parece simples, mas vemoos que um site grande como o uol o seu esqueleto é basicamente isso;*/
````
````html
<!--este layout foi convertido de um layout fixo para um layout responsivo, para que ele se comporte bem no tablet e no celular, então vamos estar tornando esse layout responsivo pois se observarmos esse layout pelo dev tools ele não é muito responsivo, em outras telas, ficando muito bagunçado, primeira coisa que ajustamos foi o .conteúdo, pois removemos o display:GRID e colocamos o display:block; o container geral da página, fizemos ele com 1024px e agora vamos estar mudando para que ele tenha no maximo 90% da largura do dispositivo-->
````
````javascript
//no java script vamos baixar o jquery na versão de cdn, clicando no link quue está logo depois de atribute e somos direcionados para uma pagina de download e lá neste site vamos escolher a versão mimificada(minified)
````
````css
/*uma descricão do que é o @media screen, ele está sendo utilizado aqui neste esquema para definições de regras dependendo da largura do nosso screen, sendo utilizado como uma forma de mudar as regras dependendo do tamanho  da tela em questão;
isso é importante pois assim conseguimos controlar como que o nosso layout será apresentado dependendo do tamanho da tela, variando entre tela de tablet, notbooks computadores e celulares*/
````