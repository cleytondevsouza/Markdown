# Curso de Markdown {#m1}


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

1. Parágrafos
2. Quebras de linhas
3. Ênfase
    1. *Itálico*
    2. **Negrito**
    3. ***Itálico Negrito***
4. Citações
5. Listas
6. Código
    1. `pip install mkdocs`
    2. `python -m venv vem`
7. Barras Horizontais
8.  Links
    1. [Youtube](https://www.youtube.com)
    2. [Google](https://www.google.com "Google Buscador de qualquer coisa")
    3. <http://www.google.com.br>
    4. <email@dominio.com.br>  
9.  Imagens  

    ![Lake](https://graduacao.uninassau.digital/img/nova_uninassau_header.svg?0591)

10. Caractéres  
    \# não é um cabeçario
11. HTML  
<h1>Titulo</h1>

<details>
<summary>
Exemplo
</summary>
Texto de exemplo do uso do html para enriquecer o documento.
</details>  

## Sintaxe Estendida

---

Tabelas  

|Nome|Idade|
|----|:-----:|
|_Henrique_|32|
|***Paty Lima***|18|  

Blocos de códigos

```
SELECT
    a.nome
    a.idade
FROM a
WHERE a.nome IS NOTE MULL
```

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