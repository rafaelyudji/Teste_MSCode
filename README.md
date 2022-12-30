Projeto referente ao processo seletivo do MS Code

Para este projeto foi utilizado HTML e CSS. As estruturas das pastas sendo:

index.html
styles.css
/img
    header-logo.png

uma pasta com os arquivos index.html, styles.css para inserção de nossos estilos .css na raiz e outra pasta /img, para inserção de nossas imagens.

. HTML

HTML é a abreviação de Hyper Text Markup Language (linguagem de marcação em hipertexto). Ou seja, não se trata de uma linguagem de programação, pois não tem lógica (algoritmos, processos etc). Ele cria a estrutura de uma página ou aplicação web, determinando a separação de layout e seu conteúdo.

Documentos .html possuem tags de estruturação básica:

```
<!doctype html>
<html>
    <head></head>
    <body></body>
</html>
```

Internamente, as tags html possuem uma anatomia básica também:

```
<nome-da-tag atributo="valor do atributo">
    conteúdo
</nome-da-tag>
```

Comentários em HTML:

<!-- Isso é um comentário. Comentários em qualquer linguagem são pedaços de código que são ignorados na renderização (na leitura do computador), mas são úteis para entedimento humano -->

. CSS

CSS é abreviação de Cascading Style Sheet (folha de estilos em cascata). É a linguagem que define estilos para o HTML, portanto, não se trata de linguagem de programação. CSS tem "cascata" no nome, devido a sua forma de determinar a propriedade de um elemento - levando em consideração hierarquia de seletores e de chamadas de estilo (inline, internal e external).

Para fazer o link de um arquivo .css em um documento .html, devemos inserir a tag <link> no <head> do documento, com o href do caminho do arquivo.
    
```
<!doctype html>
<html>
    <head>
        <link rel="stylesheet" href="css/style.css">
    </head>
    <body></body>
</html>
```
    
Dentro do arquivo .css, a anatomia é:

seletor {
    propriedade: valor;
}



