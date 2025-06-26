# Curso de Markdown


> Esse curso será dividido em duas etapas:   
>
> * Sintaxe Básica  
> - Sintaxe Estendida  

Abordaremos os seguntes itens:
<br>
## Sentax Básica

1. Cabeçários
2. Parágrafos
3. Quebras de linhas
4. Ênfase
5. Citações
6. Listas
7. Código
8. Barras Horizontais
9. Links
10. Imagens  
11. Caractéres  
12. HTML  

## Sintaxe Estendida
13. Tabelas  
14. Blocos de códigos
15. Notas de Rodapé
16. Identificadores
17. Títulos com ID  
18. Listas definidas
19. Fomatação de Texto
20. Texto Tachado  
21. Lista de Tarefas
22. Emojis  
23. URL Automática  

## Sentax Básica

1. Cabeçários  
- \#  Atribui formatação de título nível 1 podendo ir até o nível 6.  
Ex:  
```
Código
# Título Nivel 1
## Título Nivel 2  
### Título Nivel 3  
#### Título Nivel 4  
##### Título Nivel 5  
###### Título Nivel 6
```  
Resultado
# Título Nivel 1
## Título Nivel 2  
### Título Nivel 3  
#### Título Nivel 4  
##### Título Nivel 5  
###### Título Nivel 6  

- \=== Quando digitado uma linha abaixo do texto atribui formatação de título nível 1 igualmente ao “#”  
Ex:  
Código
```
Título Nivel 1
===
```
Resultado  

Título Nivel 1
===  

- \--- Quando digitado uma linha abaixo do texto atribui formatação de  título nível 2
Ex:  

Código
```
Título Nivel 2
---
```   

Resultado  

Título Nivel 2
---  

### Parágrafos  
* 2xEnter Adiciona automaticamente um parágrafo no texto deixando um alinha em branco abaixo do mesmo. 
* 2xespaço Ao ser dado duas vezes espaço no final de uma frase dando um “enter” obtém-se a quebra de linha automática.  
* \&nsbp; Adciona um único espaço entre ao texto.  
  Ex:  
  <u>Código</u>  
  `Pa&nbsp;lavra.`  

  <u>Resultado</u>  
  Pa&nbsp;lavra.  

  * \&ensp; Adciona dois espaços entre ao texto.  
  Ex:  
  <u>Código</u>  
  `Pa&ensp;lavra.`  

  <u>Resultado</u>  
  Pa&ensp;lavra.  

  * \&emsp; Adciona quatro espaço entre ao texto.  
  Ex:  
  <u>Código</u>  
  `Pa&emsp;lavra.`  

  <u>Resultado</u>  
  Pa&emsp;lavra.

### Quebras de linhas
* `<br>` Ao ser digitado ao final de uma palavra frase ou teste promove a quebra de linha. Essa tag também é muito utilizada no html.
Ex:
`Calçado<br>`

### Ênfase
* \* Quando inserido no início e no fim de uma palavra ou texto deixa os mesmos formatados em itálico.<br> 
    Ex:  
    Código  
    `*casa*`  

    Resultado  
    *casa*  

* \** Quando inseridos no inicio e no fim de uma palavra ou texto deixa os mesmos em negrigo.  
    Ex:  
    Código  
    `**casa**`  

    Resultado  
    **casa**  

* \*** Quando inseridos no início e no fim de uma palavra ou texto deia os mesmo em itálico e negrito.  
EX:  
    Código  
    `***casa***`  

    Resultado  
    ***casa***  

### Citações  
* \> É utilizado para fazer uma citação. Quando digitado no início da palavra ou frase e se dá um espaço entre eles o texto fica formatado como uma citação.  
Ex:  
    Código  
    `> Esse texto é uma citação!`  

    Resultado  
    >Esse téxto é uma citação!  

* \>> É utilizado para criar uma citação dentro de outra citação.  
    Ex:  
    Código  
    `>Esse texto é uma citação!`  
    `>> Esse texto é uma citação denro de uma citação`  

    Resultado  
    >Esse texto é uma citação!  
    >> Esse texto é uma citação denro de uma citação  

### Listas  
* \* Quando digitado no início, antes de uma palavra ou frase cria uma lista não ordenada.  
    Ex:  
    Código 
    ``` 
    * Leite
    * Açucar
    * Limão   
    ```  
    Resultado 
    * Leite
    * Açucar
    * Limão   
    

* \+ Quando digitado no início, antes de uma palavra ou frase cria uma lista não ordenada.   
    Ex:  
    Código 
    ``` 
    + Leite
    + Açucar
    + Limão   
    ```  
    Resultado 
    + Leite
    + Açucar
    + Limão  
   
* \- Quando digitado no início, antes de uma palavra ou frase cria uma lista não ordenada.  
    Ex:  
    Código 
    ``` 
    - Leite
    - Açucar
    - Limão   
    ```  
    Resultado 
    - Leite
    - Açucar
    - Limão   

* \1. Quando digitado antes de uma palavra, no início da frase cria um alista ordenada e caso queira fazer uma sub lista é digitar embaixo de uma lista apertando a tecla “tab” antes.  
  Ex:  
  <u>Código</u> 
``` 
    1. Lava Jato
       1. Champoo
       2. Cera
       3. Franela
    2. Lavanderia
       1. Alvejante
       2. Amaciante
       3. Sabão  
```   
  <u>Resultado</u>  

       1. Lava Jato
          1. Champoo
          2. Cera
          3. Franela  
       2. Lavanderia
          1. Alvejante
          2. Amaciante
          3. Sabão  

### Código  

* \`Quando colocado no inicio de palavras ou frase o texto fica formatado como código.  
  Ex:  
  
     `pip install mkdocs`
     `python -m venv vem`   


### Barras Horizontais  

* \*** Quando utilizado em uma linha entre duas linhas em branco é gerada uma barra horizontal com a função de delimitar o contexto do conteúdo que está sendo feito  
  Ex:  
  <u>Código</u>  
  `Finalde um parágrafo  
  ***`  

  <u>Resultado</u>  
  Final de um parágrafo  
  *** 
  <br> 
* \--- Quanto utilizado em uma linha entre duas linhas em branco é gerada uma barra horizontal com a função de delimitar o contexto do conteúdo que está sendo feito.  
  Ex: 
  <u>Código</u>  
  ```
  Final de um parágrafo  

  ---   
  ``` 
  <u>Resultado</u>  
  Final de um parágrafo  

  ---  

* \___ Quanto utilizado entre duas linhas em branco é gerada uma barra horizontal com a função de delimitar o contexto do conteúdo que está sendo feito.  
  Ex: 
  <u>Código</u>  
  ```
  Final de um parágrafo  

  ___   
  ``` 
  <u>Resultado</u>  
  Final de um parágrafo  

  ___  

### Links  
* \[ ]( ) Cria um link a qualquer página ou e-mail ao clicar no título do link configurado.  
  Ex:  
  <u>Código</u>  
   `[Youtube](https://www.youtube.com)`  

  <u>Resultado</u>  
   [Youtube](https://www.youtube.com)  

* \[ ] (“ “) Cria um link a qualquer página ou e-mail ao clicar no título do link configurado deixando uma mensagem ao passa o mouse por cima do link.  
  Ex: 
  <u>Código</u>   
  `[Google](https://www.google.com "Google Buscador de qualquer coisa")`  

   <u>Resultado</u>  
   [Google](https://www.google.com "Google Buscador de qualquer coisa")  

* \< > Cria um link direto de site ou e-mail sem título.  
  Ex: 
  <u>Código</u> 

  ```  
  <https://www.google.com> <br> 
  <email@dominio.com.br>  
  ```

  <u>Resultado</u><br> 
  <https://www.google.com><br>
  <email@dominio.com.br>   

### Imagens  
* \![ ] ( “ “) Insere no projeto uma imagem destinada através de um link ou endereço local da máquina.  
  Ex:  
  <u>Código</u>  
  ```  
     ![Lake](https://graduacao.uninassau.digital/img/nova_uninassau_header.svg?0591)`  
    
    ![Lake](nabuco.png)
    ```  

  <u>Resultado</u>  

    ![Lake](https://graduacao.uninassau.digital/img/nova_uninassau_header.svg?0591)  

    ![Lake](nabuco.png)  

### Caractéres
* \ Serve para anular a formatação dos caracteres especiais do markdown para demonstração de códigos em apostilas e cursos.  
  Ex:    
  <u>Código</u>  
    `\# não é um cabeçario`  

    <u>Resultado</u>  
    # não é um cabeçario  

### HTML  
* \h1 tag do HTML que pode ser utilizada no Markdown para enriquecer o documento deixando o texto formatado como título de nível 1.  
  Ex:  
  <u>Código</u>
  `<h1>Titulo</h1>`  
  <u>Resultado</u>  
  <h1>Titulo</h1>  

* \<u> tage do HTML que pode ser utilizada no Markdown par aenriquecer o documento deixando o texto formatado com sublinhado.  
  Ex:  
  Código  
  `<u>Sublinhado</u>`  

  Resultado  
  <u>Texto Sublinhado</u>

* \<details> tag do HTML que pode ser utilizada no Markdown para enriquecer o documento criando um menu suspenso/oculto para o texto.
  Ex: 
  <u>Código</u>  
```
<details>
<summary>
Exemplo
</summary>
Texto de exemplo do uso do html para enriquecer o documento.
</details>
```  
<u>Resultado</u>
<details>
<summary>
Exemplo
</summary>
Texto de exemplo do uso do html para enriquecer o documento.
</details>  

## Sintaxe Estendida

---

### Tabelas  
* \| Serve para criar tabelas dentro de um documento markdown.  
  Ex:  
  <u>Blocos de Códigos</u>  
```  
|Nome|Idade|
|----|:-----:|
|_Henrique_|32|
|***Paty Lima***|18|  
```  
<u>Resultado</u>  
|Nome|Idade|
|----|:-----:|
|_Henrique_|32|
|***Paty Lima***|18|  

* \``` É utilizado para trabalhar com bloco de códigos.  
Ex:  
<u>códigos</u>  
\```  
SELECT  
&emsp;&ensp;&ensp;a.nome  
&emsp;&ensp;&ensp;a.idade  
FROM a  
WHERE a.nome IS NOTE MULL  
\```  
<u>Resultado</u>

``` SQL
SELECT
    a.nome
    a.idade
FROM a
WHERE a.nome IS NOTE MULL
```

### Notas de Rodapé
Para Incluir uma nota de rodapé, você precisará escrever [^1] ao lado do item [^2] que você queria adcionar a nota.

[^1]: Nota
[^2]: Detalhe

### Identificadores

# Nível 1 {#n1}


texto

## Nível 2 {#n2}

Texto

### Nível 3 {#n3}


É Obrigatório ter lido o [Nível 2](n2) antes de continuar [Nível 3](#n3)

[Markdown](#m1)


### Títulos com ID  

### Listas definidas

### Fomatação de Texto
  
#### Texto Tachado  
É ~~proibido~~ fumar **dentro** do estabeleciamento.

### Lista de Tarefas
- [x] Fazer compras
- [x] Lavar carro
- [x] Limpar casa  

### Emojis  
Gostei de aprender Markdown com vocês :heart: :blush:  

### URL Automática  
https://www.google.com.br  



Cheat Sheet