# css_sass

### aulas 1 2 3

+ substituicao de variaveis
+ substiruicao por mixin
+ aninhamento de clases e elementos filhos

### Aula 6
+ Uso do placeholder para evitar duplicar codigo no CSS. Isso deixa mais performática a execução do CSS;
+ Para substituições de código mais complexas com variaveis e parametros continuar usando o mixin pois o template não permite isso;

### Aula 7

+ Por uma questão de praticidade é interessante deixar as declarações que serão sobrescritas pela media query próximo das originais.

+ Se incomodar muito as media queries repetidas, você pode usar um plugin para o Grunt chamado 'Combine media queries' que as organiza: 
    + https://github.com/frontendfriends/grunt-combine-mq
    + https://www.alura.com.br/curso-online-gruntjs

+ Sintaxe correta para concatenar uma variável de tipo string: #{$variavel}

+ Mesmo com o CSS ficando com várias media queries sendo repetidas ao longo do código, apenas habilitando a compactação gzip no servidor, já elimina esse problema.
