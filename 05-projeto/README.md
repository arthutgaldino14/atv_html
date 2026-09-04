# Projeto integrador — gabarito da entrega 3 (ciclo 4)

Este é o `index.html` da aula 03 depois da aula 04, já dentro da **estrutura
obrigatória** combinada no ciclo 3.

## O que mudou do ciclo 3 para o ciclo 4

No HTML, três linhas — e nenhuma tag nova:

| Mudança | Onde |
|---|---|
| `<link rel="stylesheet" href="css/estilo.css">` | no `<head>` |
| `imagens/foto.jpg` virou `img/foto.jpg` | na `<section id="gostos">`, para bater com a estrutura obrigatória |
| um comentário no topo explicando o arquivo | logo depois do `<body>` |

Todo o resto da diferença está em **`frontend/css/estilo.css`**, escrito com o
que a aula 04 cobre: seletor de tipo, classe, id, agrupamento, descendente,
seletor de atributo, pseudo-classes, cascata e herança.

Caixa (box model), web fonts e layout em flex/grid entram nas aulas 05 e 06.
O menu, por exemplo, está com `display: inline-block` — que funciona e é o jeito
clássico; o jeito de hoje é `display: flex`, e ele chega na aula 05.

## Como abrir

1. Abra **a pasta `05-projeto` inteira** no VS Code (*Arquivo → Abrir Pasta*),
   não só o `frontend/`.
2. Abra `frontend/index.html` e clique em **Go Live** (extensão Live Server).

## A estrutura

```
.
├─ README.md
├─ frontend/               tudo o que roda no navegador
│   ├─ index.html
│   ├─ css/
│   │   └─ estilo.css      ← a aula 04 inteira está aqui
│   ├─ js/
│   │   └─ script.js       vazio até o ciclo 6
│   └─ img/
│       └─ foto.jpg        imagem de espaço reservado; troque pela sua
└─ backend/                tudo o que roda no servidor
    ├─ config/
    │   └─ conexao.php     vazio até o ciclo 8
    └─ processa-contato.php
```

## O que conferir no seu

- O `<link>` está no `<head>` e o caminho é `css/estilo.css`, tudo em
  minúsculas.
- **Nenhum `style=""` sobrou no HTML** e não há `<style>` no `<head>`.
- A tabela tem `border-collapse`, cabeçalho em cor e zebra.
- O formulário tem `label` em bloco, campos escolhidos por
  `input[type="..."]` e `:focus` visível — navegue por Tab para conferir.
- A página continua validando no W3C: <https://validator.w3.org>.
