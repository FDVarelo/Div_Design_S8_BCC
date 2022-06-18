# Div_Design_S8_BCC
Atividade da cadeira de Design Web utilizando o site http://enviartrabalho.rf.gd/div_design do professor Ricardo Lenz Cesar.

Aqui estara apenas as telas finais, com o HTML e CSS acompanhado com uma imagem de como ela ficou.

## `Site`
O site http://enviartrabalho.rf.gd/div_design é um site desenvolvido pelo professor Ricardo Lenz Cesar e é utilizado para o desenvolvimento de telas com HTML e CSS utilizando apenas div para a construção das telas.

Vale ressaltar que o site foi totalmente testado no navegador Mozilla Firefox, então, caso você esteja utilizando outros navegadores alguns atalhos ou efeitos podem não sair como o esperado, como por exemplo o Opera GX não funciona o atalho ctrl + g, pois ele tem uma atalho do proprio navegador para esse comando, então levando em conta isso, é recomendado o uso do Mozilla Firefox para a utilização da ferramenta Div_Design.

## `Hotkeys e Dicas do Div_Design`
Primeiramente a tela padrão do Div_Design

### `Painel`

- Opções → Podemos selecionar como a div será criada com relação a cor, onde pode ser selecionada a cor atual, cor aleatoria, ou cor sequencial onde toda vez que for criada uma nova div sera mudada a cor para a próxima, além de já adicionar como padrão uma borda, padding e margin para a div. 

- Clique → Temos três alternativas, Conteúdo que irá apenas criar uma div, innerHTML onde quando clicar em uma div é possível ver atributos html daquela div que foram adicionados, como texto, imagem, etc., e por fim Cor, onde irá ser utilizado para alterar cor.

- Classes → Classes criadas e salvas.

- Download → Fazer o download do HTML e CSS da página atual.

- Cores → Possível alterar a paleta de cores para outras paletas.

### `Hotkeys`

`d` → É utilizado para criar uma div, possibilitando também a criação de uma div dentro de outra, tendo assim uma hierarquia de pai e filho entre div.

`f` → É utilizado para deixar uma div como Flex, onde podemos alterar completamente aquela div, como fazer com que seus filhos se aliem da maneira que nos quisermos, como alinhas a esquerda, a direita, ao centro, etc.

`t` → É utilizado para adicionar texto em uma div (Caso queira apagar um texto você deve ir no painel Clique e escolher a opção innerHTML para alterar ou excluir o texto).

`i` → É utilizado para colocar um icone dentro de uma div, tem doi estilos de modelo/tema: FontAwesome ou MaterialDesign (para excluir ou alterar um icone é da mesma forma de um texto, ir no painel Clique e escolher a opção innerHTML, depois clicar na div que deseja retirar o icone e apagar, porém atenção pois pode acabar excluindo junto o texto).

`p` → É utilizado para criar colunas dentro das div's, sendo uma coluna criada: x x x, eu quero dizer que quero três colunas dentro da div, todas com o mesmo tamanho, já no exemplo: x xx xxx, quero dizer que tenho três colunas, a primeira com tamanho x, a segunda com tamanho 2x e a terceira com tamanho 3x, sendo que x é responsavel por x por cento da largura daquela div, ou seja se temos uma div com 200px, então o exemplo aterior ficaria como: 33,33px cada valor de x, então: 33,33px ; 66,66px ; 99,99px.

`ctrl + g` → Utilizado para criar gradiente de cores em uma div, aonde nos selecionamos acor que queremos e depois colocamos o mouse acima da div que queremos e apertamos ctrl + g, assim adicionando o gradiente a ela, vale ressaltar que a cada vez que é adicionado um gradiente ele muda entre o topo e o fim da div, ou seja, se eu quero um gradiente da cor vermelha para amarela a partir do topo da div, eu deixo a div da cor vermelha, seleciono a cor amarela na minha paleta de cores, coloco o mouse acima da div em vermelha e aperto ctrl + g, fazendo assim o top ficar em vermelho e a parte de baixo em amarela e o meio em laranja aonde ocorre o gradiente. Caso eu mude agora minha paleta para verde e aperte ctr + g na mesma div,eu vou ter um gradiente da cor verde para amarela, e assim sucessivamente.

`SpaceBar` → Ou Visual, ao apertar a barra de espaço enquando o mouse estiver sobre uma div, ira aparecer uma janela de pop-up com algumas alterações extras que podem ser feitas na div selecionada, vale ressaltar que utilizando `Page Up` e `Page Down` enquando estiver nesse modo, ele altera para outra div que tenha a mesma hierarquia, também vale ressaltar que diversos componentes do Visual podem ser controlador por pixel, ex.: 15px, 60px, etc., como também pode ser alterado pelas setas (→ ↓ ↑ ←) e por fim com [ e ] para diminuir e aumentar os valores.

Para as opçções do SpaceBar também nomeada como Visual, algumas bases são:

`Margin` - Margin da div para outra.

`Padding` - Padding do div (quando é uma div pai, é importante tirala caso queira juntar mais os filhos do pai).

`Border` - Tamanho da borda da div (Pode-se utilizar das setas → ↑ ↓ ← para direcionar a borda para apenas um lado, mas tem que ter borda para ser possível fazer isso).

`Border-Radius` - Selecionando 50% ele deixa totalmente redondo qualquer quadrado.

`w,h` - Width e Height, largura e altura, apenas a largura pode ser selecionada diretamente por texto, ex.: 50px ou 80%, porém é possível manipular eles pelas setas (→ ↓ ↑ ←), ou com [ e ] onde aumenta e diminui na mesma proporção facilitando assim a criação de quadrados maiores.

`Justify-Content` - Alinhar o conteúdo em relação a horizontal (Center, flex-end, space-between e flex-start).

`Align-Items` - Alinhar o conteúdo em relação a vertical (Center, flex-end, stretch e flex-start).

`Text-Align` - Alinhar o texto daquela div (Right, left, justify e center).

`Translate` - Com as setas (→ ↓ ↑ ←) é possível movimentar a div para qualquer lugar da tela sem se importar com Margin ou Padding.

## `Exemplos Feitos`

Dos exemplos citados acima, todos foram feitos em sala de aula, mas para a conclusão da cadeira e como nota para a finalização da N2 do semestre, foi disponibilizado a escolha de dois exemplos para serem feitos dos exemplos: (Site estilo Youtube, site estilo Jornal, Calendário, Interface Ribbon e Interface Metro UI.), os dois exemplos escolhidos foram o exemplo do Calendário, e o exemplo do Jornal.

`Exemplo Calendário`

No exemplo do Calendário foi utilizado dois div's como pais, o primeiro em azul para a organização em geral, e o segundo para a organização dos divs internos e também para servir como um background para o nosso calendário.

Após isso foram criados mais 4 div's, uma para a barra de meses com duas setas em cada extremidade com o nome no meio, outra para os dias da semana, e para isso foi utilizado a hotkey `p`, a terceira div foi para os dias do mês, também utilizando a hotkey `p`, e por fim foi utilizado a quarta div para as tags utilizadas no mês, que server como avisos.

Além disso foi tirado todas as bordar exceto da última div que foi utilizdo apenas a borda de cima dela, e ela é apenas 90% da largura total, para que a barra não fique como uma linha 100%.

`Exemplo Jornal`

No exemplo da interface de Jornal, foi utilizado a mesma coisa do Calendário, duas div's para conseguirmos ajeitar tudo e deixar como um background, e dentro deles foram criados 4 div's, a primeira foi utilizada para servir como um topbar, onde tem o login e a assinatura do jornal, logo abaixo a segunda div onde temos o logo do jornal, o nome do jonal, e-mail de contado, valor do dólar e euro, e por fim uma seletor de busca, na terceira div foi utilizada como uma barra de busca já pre-criada, com notícias, economia, esportes, viagens, produtos, e coisas boas, ou seja, as buscar mais recorrentes que foram destacadas para facil acesso, e a última div, contendo tanto noticias como tambem propagandas, e para fazer elas ficarem divididas ao meio, foi dividido em duas div's a da esquerda com cerca de 60 ~ 70% de largura, e a da direito com as propagandas com o restante da largura.

Da pra notar que foi utilado bastante o recurso de gradiente de cores `ctrl + g`.
