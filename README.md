# exemplo-sass
Projeto com exemplo de uso de [Sass](https://sass-lang.com/), abordando variáveis, aninhamento, imports e mixins.

Para compilar as folhas de estilo Sass, é preciso antes instalar o Sass:

### `npm i -g sass`

Após, abra um terminar na pasta raíz do projeto e execute o comando abaixo para 
compilar as folhas de estilo Sass e gerar a folha de estilo em CSS puro:

### `sass --watch css/estilos.scss css/estilos.css`

Com este comando, o compilador irá compilar automaticamente as folhas Sass sempre que houver alguma alteração, gerando a folha de estilo CSS bem formatada. Caso deseje alternativamente gerar uma folha de estilo CSS minificada, basta alterar o comando acima da seguinte maneira:

### `sass --watch css/estilos.scss css/estilos.css --style=compressed`
