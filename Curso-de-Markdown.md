# Curso de Markdown {#m1}


> Esse curso será dividido em duas etapas:   
>
> * Sintaxe Básica  
> - Sintaxe Estendida  

Abordaremos os seguntes itens:

## Sentax Básica

***

1. Cabeçários
2. Parágrafos
3. Quebras de linhas
4. Ênfase
    1. *Itálico*
    2. **Negrito**
    3. ***Itálico Negrito***
5. Citações
6. Listas
7. Código
    1. `pip install mkdocs`
    2. `python -m venv vem`
8. Barras Horizontais
9. Links
    1. [Youtube](https://www.youtube.com)
    2. [Google](https://www.google.com "Google Buscador de qualquer coisa")
    3. <http://www.google.com.br>
    4. <email@dominio.com.br>  
10. Imagens  

    ![Lake](https://graduacao.uninassau.digital/img/nova_uninassau_header.svg?0591)

11. Caractéres  
    \# não é um cabeçario
12. HTML  
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

Notas de Rodapé
Para Incluir uma nota de rodapé, você precisará escrever [^1] ao lado do item [^2] que você queria adcionar a nota.

[^1]: Nota
[^2]: Detalhe

Identificadores

# Nível 1 {#n1}


texto

## Nível 2 {#n2}

Texto

### Nível 3 {#n3}


É Obrigatório ter lido o [Nível 2](n2) antes de continuar [Nível 3](n3)

[Markdown](#m1)


Títulos com ID
Listas definidas
Fomatação de Texto
Lista de Tarefas
Emojis
URL Automática
Cheat Sheet