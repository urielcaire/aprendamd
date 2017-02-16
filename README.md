# AprendaMD
Este repositório será utilizado apenas para aprender e ensinar Markdown. Com essa 'skill' eu e você poderemos criar arquivos README.md
cada vez melhores e mais bonitos.

Fonte de aprendizagem: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

##Cabeçalhos
Para fazer cebeçãlhos, basta usar sustenidos antes da palavra. 
```
#H1
##H2
###H3
####H4
#####H5
```
#H1
##H2
###H3
####H4
#####H5  
Simples, não é?

##Quebras de linhas
As quebras de linha são feitas com dois espaços ao fim da linha.  
```
Por exemplo:
"Olá, mundo!" ficaria "Olá, mundo!  "
```
Já para iniciar um novo parágrafo, basta deixar uma linha em branco entre as frases. Exemplo:
```
Este é um parágrafo.

Eeste é outro parágrafo.
```
## Textos Destacados

```
Você pode deixar uma palavra em negrito usando **asteriscos** ou __underlines__
Para deixá-la em itálico, use apenas um par de *astericos* ou de _underlines_
Misturar os dois é simples, basta fazer isso: **_palavra_**
E, finalmente, para riscar uma palavra utilize dois pares de ~~til~~
```
Olha como fica legal meu nickname em negrito: **urielcaire** :D  
Mas em itálico fica um tanto quanto estranho:  _urielcaire_ =\  
Vamos misturar os efeitos: **_urielcaire_**. Não ficou nada agradável hahaha  
E se riscarmos isso? ~~urielcaire~~

## Listas
Ok, agora vamos trabalhar com listas :D

#### Lista Ordenada

```
Para criar uma lista ordenada basta colocar o valor do tópico e acrescentar um espaçamento.
Já para adicionar uma linha abaixo de um item da lista, como uma descrição, utilize três espaçamentos.
Exemplo:

1. PHP
   Minha primeira linguagem de programação web. Acho que vai continuar sendo a preferida por um bom tempo!

Para uma lista dentro da lista ordenada, utilize dois espaçamentos. Segue o exemplo:

3. HTML & CSS  
   Antes que me crucifiquem, vamos esclarecer duas coisas:
  1. HTML: linguagem de marcação
  2. CSS: linguagem de estilos 
```

Aí vai uma lista ordenada das minhas linguagens preferidas:

1. PHP  
   Minha primeira linguagem de programação web. Acho que vai continuar sendo a preferida por um bom tempo!  
2. JavaScript  
   Essa eu confesso que conheci através do seu famoso framework, o jQuery. Mas acredito não ter sido o único a conhecer primeiro o framework e depois a linguagem em sí. xD
3. HTML & CSS  
   Antes que me crucifiquem, vamos esclarecer duas coisas:
  1. HTML: linguagem de marcação
  2. CSS: linguagem de estilos  
   Acho que são as linguagens que todo mundo gosta ou já gostou. Quem nunca brincou um pouco com elas? ~~E quem nunca passou raiva com aquela div que insiste em ir pro outro lado?~~
4. SQL  
   Acredito que essa dispensa apresentações.
5. Java  
   Tenho uma história de amor e ódio com Java. Por algumas vezes me parece a coisa mais linda do mundo, mas por outras...
6. CQL   
   Cassandra Query Language. Ainda estou estudando este excelente banco de dados - 13/03/2017.
7. Python  
   Sem dúvida alguma, essa é a próxima linguagem que irei me dedicar a aprender. Tive pouca experiência com ela, mas já acho incrível!

Ok, temos uma lista ordenada bem completa.

#### Lista Não Ordenada

````
Para listas não ordenadas você pode usar três diferentes sinais. Observe:
* Praticar Jiu Jitsu
- Ir a praia
+ Jogar Video Game
````

Agora vamos para uma lista **não ordenada** ~~desordenada?~~ das coisas que gosto de fazer:

* Pilotar minha moto <3
* Praticar Jiu Jitsu
- Ir a praia
+ Jogar Video Game

Essa é minha lista não ordenada!

##Links
```
Há duas maneiras de criar links.

Na primeira, você coloca a palavra entre [] seguida do link entre (). Exemplo:
Aqui tem o link do [IFSP Campus Caraguatatuba](https://www.ifspcaraguatatuba.edu.br/ "IFSP's Homepage"), minha instituição de ensino do coração :D  

Na segunda você cria uma referência para o link ao final e depois a chama. Observe os dois links e as duas referências, são um pouco diferentes:
Aqui um link para o site do [DeepLibras][1], grupo de pesquisa que faço parte. Só tem gente MUITO legal e inteligente aqui!  
Aqui um link para o meu repositório [jBility]. Sem dúvidas o repositório que criei com mais carinho!

[1]: http://deeplibras.github.io/pt/
[jBility]: https://github.com/urielcaire/jbility
```

Ok, agora vamos criar alguns links.

Aqui tem o link do [IFSP Campus Caraguatatuba](https://www.ifspcaraguatatuba.edu.br/ "IFSP's Homepage"), minha instituição de ensino do coração :D  
Aqui um link para o site do [DeepLibras][1], grupo de pesquisa que faço parte. Só tem gente MUITO legal e inteligente aqui!  
Aqui um link para o meu repositório [jBility]. Sem dúvidas o repositório que criei com mais carinho!

[1]: http://deeplibras.github.io/pt/
[jBility]: https://github.com/urielcaire/jbility

## Imagens

```
Para adicionar uma imagem basta inserir uma tag seguida do link da imagem. Fica assim:
Vou começar com esse gif lindão aqui: ![alt text](https://github.com/urielcaire/learnmd/blob/master/imgs/solaire.gif "Praise the sun!")

Você também pode fazer por referência, como o link:
E agora um ícone do github: ![alt text][github]

[github]: https://github.com/urielcaire/learnmd/blob/master/imgs/github.png "Github logo"
```

Vou começar com esse gif lindão aqui: ![alt text](https://github.com/urielcaire/learnmd/blob/master/imgs/solaire.gif "Praise the sun!")  
E agora um ícone do github: ![alt text][github]

[github]: https://github.com/urielcaire/learnmd/blob/master/imgs/github.png "Github logo"

##Códigos
Agora a parte mais legal, inserir códigos!

```
Para inserir códigos você deve digitar três crases mais a linguagem que deseja mostrar e no fim de tudo 'fechar' 
com mais três crases.
Fica assim:

    ```javascript
    var init = "Olá, mundo!";
    alert(init);
    ````
```

Aqui um código em JavaScript
```javascript
var init = "Olá, mundo!";
alert(init);
```
Agora em PHP <3
```php
<?php
	while(1==1){
		echo "Eu sou um loop infinito D: ";
	}
?>
```  
Isso é realmente muito importante e legal.

##Tabelas
Acho que ainda posso precisar de algumas tabelas, vamos ver como isso funciona.

```
Observe que não há muito segredo em como montar uma tabela, a única regra é que são necessários
pelo menos três traços para cada coluna.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

```

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

##Citações

```
> Como você pode ver, citações são simples.
> E essa linha faz parte da citação anterior.
```

Aqui vai uma citação:  
> It's me, Mario!

##Linha Horizontal
```
Para acrescentar uma linha horizontal ao seu texto, insira ao menos três traços.

Exemplo:
---
```

Exemplo:
---

###I-Isso é tudo pe-pessoal!