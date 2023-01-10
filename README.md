### :invalid

A pseudo-classe CSS :invalid representa qualquer elemento <input> ou <form> cujo conteúdo não esteja válido (en-US).

/* Seleciona todos os inputs inválidos */

```ruby
input:invalid {
  background-color: pink;
}
```

Essa pseudo-classe é útil para usuário identificar quais campos foram preenchidos incorretamente.

#

### :valid

A pseudo-classe CSS :valid representa qualquer <input> ou outro elemento do <form> cujo conteúdo foi validado com sucesso. Isso permite, facilmente, adicionar uma aparência que ajude o usuário a identificar os campos validados.

/* Seleciona qualquer input válido */

```ruby
input:valid {
  background-color: powderblue;
}
```

Essa pseudo-classe é útil para realçar os campos válidos para o usuário.

#

### :required

A pseudo-classe CSS :required representa qualquer <input>, <select>, ou <textarea> contendo o atributo required.

/* Seleciona qualquer <input> requerido */

```ruby
input:required {
  border: 1px dashed red;
}
```

Esta pseudo-classe é utilizada para destacar campos que devem ter dados válidos antes do formulário ser submetido.

### Esse é um atributo booleano usado para indicar que um determinando campo de formulário é obrigatório para o envio do mesmo. Ao adicionar esse atributo a um campo de formulário, o navegador obriga o usuário a inserir dados naquele campo antes de enviar o formulário.

#
#

[Gravação de tela de 10-01-2023 13:27:12.webm](https://user-images.githubusercontent.com/66473846/211607289-b95c2372-5c4a-4c66-9db8-3c4e59f03456.webm)

