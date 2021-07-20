# Markdwon, linguagem de marcação
##  O que é Markdown?

É uma linguagem de marcação textual (markup) muito usada no mundo da programação. Ela é leve, de simples formatação usando caracteres básicos. Feita para que sua conversão ao HTML seja extremamente fácil. Basicamente um simples formato de texto como .txt, apenas com o tipo .md.

Você pode encontra*los facilmente em projetos do Github com a indicação de 
<span style="color:orange">REAME</span>.

Tags HTML também funcionam dentro do arquivo.

## Como posso estar usando?

Vários editores de texto são nativos ou tem suporte á Markdown como:

Dillinger: [https://dillinger.io/](https://dillinger.io/)   
Atom: [https://atom.io/](https://atom.io/)  
VS Code : [https://code.visualstudio.com/](https://code.visualstudio.com/)  
MarkdownPad (Windows): [http://markdownpad.com/](http://markdownpad.com/)
Remarkable (Linux): [https://remarkableapp.github.io/](https://remarkableapp.github.io/)  

## Sintaxe básica

Estes itens podem variam de editor para editor contudo são comandos básicos da linguagem que devem ser aceitos por quase todos eles.

* Títulos
```markdown
# h1
## h2
### h3
#### h4
##### h5
###### h6
```
<!----->
* Texto itálico
```markdown
*italico* ou _italico_
```
<!----->
* Texto negrito
```markdown
**negrito** ou __negrito__
```
<!----->
* Citação
```markdown
> texto
```
<!----->
* Código
```markdown
`seu código`
```
<!----->
* Bloco de código
```markdown
```seu bloco de código```
~~~seu bloco de código~~~
```
<!----->
* Lista não ordenada
```markdown
* item 1
* item 2

ou

* item 1
* item 2

ou 

+ item 1
+ item 2
```
<!----->
* Lista ordenada
```markdown
1. item 1
2. item 2
```
<!----->
* Links em linha
```markdown
[texto](url)
```
<!----->
* Links em sequencia
```markdown
[texto](1) e o link [texto 2][2]

[1]: link 1
[2]: link 2
```
<!----->
* Links automáticos (uso de < e >)
```markdown
<https://www.google.com.br>
```
<!----->
* Imagens
```markdown
![Legenda](url)
```
<!----->
* Imagens em sequencia
```markdown
![Legenda](1)

[1]: link da imagem
```
<!----->
* Links + imagens
```markdown
[![legenda](url imagem)](url pagina)]
```
<!----->
* Tabelas
```markdown
| coluna 1 | coluna 2 | coluna 3 |
|------|:--------:|-------------:|
| linha 1 | linha 2 | linha 3|
```
<!----->
* Caracteres literais (blackslash scapes)
```markdown
\"frase literal com aspas\"
```
<!----->
* Abreviaturas
```markdown
Vamos abreviar para MD.

*[MD]: Markdown
```
<!----->
* Quebras de linha. Esta varia de editor e parser do código.  Tecla Enter e/ou dois espaços ao final da linha podem ser considerados
```markdown
Primeira linha
Segunda linha

ou 

Primeira linha00 (cada zero representa um espaço)
Segunda linha
```
<!----->
* Emojis
```markdown
:smile: (sua indicação é em inglês)
```

Lista de emojis: [link](https://www.webfx.com/tools/emoji*cheat*sheet/)

## Fontes

- [https://github.com/luong-komorebi/Markdown-Tutorial](https://github.com/luong-komorebi/Markdown-Tutorial)
- [https://wordpress.com/support/markdown-quick-reference/](https://wordpress.com/support/markdown-quick-reference/)
- [https://www.alura.com.br/artigos/como-trabalhar-com-markdown](https://www.alura.com.br/artigos/como-trabalhar-com-markdown)
- [https://daringfireball.net/projects/markdown/](https://daringfireball.net/projects/markdown/)
- [https://www.ime.unicamp.br/~rmiranda/md/tutorial.html](https://www.ime.unicamp.br/~rmiranda/md/tutorial.html)
- [https://blog.da2k.com.br/2015/02/08/aprenda-markdown/](https://blog.da2k.com.br/2015/02/08/aprenda-markdown/)